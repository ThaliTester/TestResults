#### Test 797510159e44f0b_thali01_samsung-SM-G900F Logs


```
--------- beginning of system
,08-12 21:57:11.349   753  1235 V AlarmManager: Expired Alarm result :4
--------- beginning of main
08-12 21:57:11.369  4865  4931 I Finsky  : [681] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
08-12 21:57:11.369   753   753 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
08-12 21:57:11.369   753   753 V AlarmManagerEXT: <AppSync3 Whitelist>
08-12 21:57:11.369   753   753 V AlarmManagerEXT: (AppSync) ### 0 added ###
08-12 21:57:11.379  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-12 21:57:11.379  1373  1373 I PERF    : received broadcast android.intent.action.TIME_TICK
08-12 21:57:11.379  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 21:57:11.399  1373  1373 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
08-12 21:57:11.399  1373  1373 D SecKeyguardClockView: HomeTimezone(): 1
08-12 21:57:11.399  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 21:57:11.399  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 21:57:11.409  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 21:57:11.409  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 21:57:11.409  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 21:57:11.409  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 21:57:11.409  1373  1373 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 21:57:11.409   753  2228 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-12 21:57:11.409   753  2228 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4308, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-12 21:57:11.409   753  2228 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-12 21:57:11.409   753  2228 D BatteryService: stay LED for charging
08-12 21:57:11.409   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-12 21:57:11.419   753   753 I MotionRecognitionService: Plugged
08-12 21:57:11.419   753   753 D MotionRecognitionService:   cableConnection= 1
08-12 21:57:11.419   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 21:57:11.419   753   753 D MotionRecognitionService: skip setTransmitPower. 
08-12 21:57:11.429  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-12 21:57:11.429  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 21:57:11.439  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-12 21:57:11.439  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 21:57:11.439  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 21:57:11.439  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 21:57:11.439  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 21:57:11.439  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
08-12 21:57:11.479  1373  1373 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 21:57:11.689  4865  4931 I Finsky  : [681] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
08-12 21:57:11.689  4865  4865 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
08-12 21:57:11.699   753  1409 I ActivityManager: Killing 3978:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
08-12 21:57:11.709   753   767 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
08-12 21:57:12.229  2112  2112 E audit   : type=1400 msg=audit(1471031832.229:285): avc:  denied  { execmod } for  pid=6322 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 21:57:12.229  2112  2112 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 21:57:12.229  2112  2112 E audit   : type=1300 msg=audit(1471031832.229:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fcc000 a1=51000 a2=5 a3=4 items=0 ppid=3548 ppcomm=adbd pid=6322 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 21:57:12.229  2112  2112 E audit   : type=1327 msg=audit(1471031832.229:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 21:57:12.229  2112  2112 E audit   : type=1320 msg=audit(1471031832.229:285): 
08-12 21:57:12.279  2112  2112 E audit   : type=1400 msg=audit(1471031832.279:286): avc:  denied  { execmod } for  pid=6322 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 21:57:12.279  2112  2112 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 21:57:12.279  2112  2112 E audit   : type=1300 msg=audit(1471031832.279:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f8c000 a1=51000 a2=5 a3=4 items=0 ppid=3548 ppcomm=adbd pid=6322 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 21:57:12.279  2112  2112 E audit   : type=1327 msg=audit(1471031832.279:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 21:57:12.279  2112  2112 E audit   : type=1320 msg=audit(1471031832.279:286): 
08-12 21:57:12.329   753  3454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-12 21:57:12.329  2112  2112 E audit   : type=1400 msg=audit(1471031832.329:287): avc:  denied  { execmod } for  pid=6322 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 21:57:12.329  2112  2112 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 21:57:12.329  2112  2112 E audit   : type=1300 msg=audit(1471031832.329:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f8c000 a1=51000 a2=5 a3=4 items=0 ppid=3548 ppcomm=adbd pid=6322 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 21:57:12.329  2112  2112 E audit   : type=1327 msg=audit(1471031832.329:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 21:57:12.329  2112  2112 E audit   : type=1320 msg=audit(1471031832.329:287): 
08-12 21:57:12.329  6322  6322 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 21:57:12.329  6322  6322 D AndroidRuntime: CheckJNI is OFF
08-12 21:57:12.329  6322  6322 D AndroidRuntime: readGMSProperty: start
08-12 21:57:12.329  6322  6322 D AndroidRuntime: readGMSProperty: already setted!!
08-12 21:57:12.339  6322  6322 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-12 21:57:12.339  6322  6322 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-12 21:57:12.339  6322  6322 D AndroidRuntime: readGMSProperty: end
08-12 21:57:12.339  6322  6322 D AndroidRuntime: addProductProperty: start
08-12 21:57:12.339  6322  6322 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 21:57:12.339  6322  6322 W art     : aedf3000-b1d19000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-12 21:57:12.339  6322  6322 W art     : b1d19000-b3f88000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-12 21:57:12.339  6322  6322 W art     : b3f88000-b3f89000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-12 21:57:12.339  6322  6322 W art     : b3f89000-b3f8a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.339  6322  6322 W art     : b42bb000-b42e4000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 21:57:12.339  6322  6322 W art     : b42e4000-b4732000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-12 21:57:12.339  6322  6322 W art     : b4732000-b4733000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b4733000-b473d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-12 21:57:12.339  6322  6322 W art     : b473d000-b473e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-12 21:57:12.339  6322  6322 W art     : b473e000-b4740000 rw-p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-12 21:57:12.339  6322  6322 W art     : b485e000-b4861000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-12 21:57:12.339  6322  6322 W art     : b4861000-b4862000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-12 21:57:12.339  6322  6322 W art     : b4862000-b4863000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-12 21:57:12.339  6322  6322 W art     : b4863000-b4864000 r--p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b4864000-b4884000 r--s 00000000 00:0b 6702       /dev/__properties__
08-12 21:57:12.339  6322  6322 W art     : b4884000-b5295000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-12 21:57:12.339  6322  6322 W art     : b5295000-b5296000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5296000-b52df000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-12 21:57:12.339  6322  6322 W art     : b52df000-b52e0000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-12 21:57:12.339  6322  6322 W art     : b52e0000-b52e8000 rw-p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b52e8000-b52e9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.339  6322  6322 W art     : b52e9000-b531e000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-12 21:57:12.339  6322  6322 W art     : b531e000-b531f000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b531f000-b5320000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-12 21:57:12.339  6322  6322 W art     : b5320000-b5321000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-12 21:57:12.339  6322  6322 W art     : b5321000-b5379000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-12 21:57:12.339  6322  6322 W art     : b5379000-b537a000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b537a000-b537b000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-12 21:57:12.339  6322  6322 W art     : b537b000-b537c000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-12 21:57:12.339  6322  6322 W art     : b537d000-b5383000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 21:57:12.339  6322  6322 W art     : b5383000-b5384000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 21:57:12.339  6322  6322 W art     : b5384000-b5385000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 21:57:12.339  6322  6322 W art     : b5385000-b5387000 rw-p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5388000-b5392000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 21:57:12.339  6322  6322 W art     : b5392000-b5395000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 21:57:12.339  6322  6322 W art     : b5395000-b5396000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 21:57:12.339  6322  6322 W art     : b5397000-b53ae000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 21:57:12.339  6322  6322 W art     : b53ae000-b53af000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b53af000-b53b0000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 21:57:12.339  6322  6322 W art     : b53b0000-b53b1000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 21:57:12.339  6322  6322 W art     : b53b2000-b53bc000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-12 21:57:12.339  6322  6322 W art     : b53bc000-b53bd000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-12 21:57:12.339  6322  6322 W art     : b53bd000-b53be000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-12 21:57:12.339  6322  6322 W art     : b53be000-b53c2000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 21:57:12.339  6322  6322 W art     : b53c2000-b53c3000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 21:57:12.339  6322  6322 W art     : b53c3000-b53c4000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 21:57:12.339  6322  6322 W art     : b53c4000-b53da000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-12 21:57:12.339  6322  6322 W art     : b53da000-b53db000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-12 21:57:12.339  6322  6322 W art     : b53db000-b53dc000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-12 21:57:12.339  6322  6322 W art     : b53dc000-b53e9000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-12 21:57:12.339  6322  6322 W art     : b53e9000-b53ea000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-12 21:57:12.339  6322  6322 W art     : b53ea000-b53eb000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-12 21:57:12.339  6322  6322 W art     : b53eb000-b544b000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-12 21:57:12.339  6322  6322 W art     : b544b000-b544e000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-12 21:57:12.339  6322  6322 W art     : b544e000-b5452000 rw-p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5452000-b54b3000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-12 21:57:12.339  6322  6322 W art     : b54b3000-b54b4000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-12 21:57:12.339  6322  6322 W art     : b54b4000-b5503000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-12 21:57:12.339  6322  6322 W art     : b5503000-b5505000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-12 21:57:12.339  6322  6322 W art     : b5505000-b5506000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-12 21:57:12.339  6322  6322 W art     : b5506000-b5507000 rw-p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5507000-b550e000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 21:57:12.339  6322  6322 W art     : b550e000-b550f000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 21:57:12.339  6322  6322 W art     : b550f000-b5510000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-12 21:57:12.339  6322  6322 W art     : avc_common.so
08-12 21:57:12.339  6322  6322 W art     : b5511000-b5514000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 21:57:12.339  6322  6322 W art     : b5514000-b5515000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 21:57:12.339  6322  6322 W art     : b5515000-b5516000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-12 21:57:12.339  6322  6322 W art     : enc_common.so
08-12 21:57:12.339  6322  6322 W art     : b5517000-b551b000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-12 21:57:12.339  6322  6322 W art     : b551b000-b551c000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b551c000-b551d000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-12 21:57:12.339  6322  6322 W art     : b551d000-b551e000 rw-p 00005000 b3:17 2510       /syste
08-12 21:57:12.339  6322  6322 W art     : m/lib/libpowermanager.so
08-12 21:57:12.339  6322  6322 W art     : b551f000-b553c000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 21:57:12.339  6322  6322 W art     : b553c000-b553d000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 21:57:12.339  6322  6322 W art     : b553d000-b553e000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 21:57:12.339  6322  6322 W art     : b553f000-b5544000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 21:57:12.339  6322  6322 W art     : b5544000-b5545000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 21:57:12.339  6322  6322 W art     : b5545000-b5546000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 21:57:12.339  6322  6322 W art     : b5547000-b5578000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 21:57:12.339  6322  6322 W art     : b5578000-b557b000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 21:57:12.339  6322  6322 W art     : b557b000-b557c000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 21:57:12.339  6322  6322 W art     : b557d000-b55b8000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-12 21:57:12.339  6322  6322 W art     : b55b8000-b55b9000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-12 21:57:12.339  6322  6322 W art     : b55b9000-b55ba000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-12 21:57:12.339  6322  6322 W art     : b55bb000-b55c2000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-12 21:57:12.339  6322  6322 W art     : b55c2000-b55c3000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b55c3000-b55c4000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-12 21:57:12.339  6322  6322 W art     : b55c4000-b55c5000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-12 21:57:12.339  6322  6322 W art     : b55c5000-b55c6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.339  6322  6322 W art     : b55c6000-b55dd000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-12 21:57:12.339  6322  6322 W art     : b55dd000-b55de000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b55de000-b55e1000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-12 21:57:12.339  6322  6322 W art     : b55e1000-b55e2000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-12 21:57:12.339  6322  6322 W art     : b55e2000-b5601000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-12 21:57:12.339  6322  6322 W art     : b5601000-b5602000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-12 21:57:12.339  6322  6322 W art     : b5602000-b5603000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-12 21:57:12.339  6322  6322 W art     : b5603000-b5641000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-12 21:57:12.339  6322  6322 W art     : b5641000-b5642000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5642000-b5644000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-12 21:57:12.339  6322  6322 W art     : b5644000-b5645000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-12 21:57:12.339  6322  6322 W art     : b5646000-b564d000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 21:57:12.339  6322  6322 W art     : b564d000-b564e000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 21:57:12.339  6322  6322 W art     : b564e000-b564f000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 21:57:12.339  6322  6322 W art     : b5650000-b5653000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 21:57:12.339  6322  6322 W art     : b5653000-b5654000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 21:57:12.339  6322  6322 W art     : b5654000-b5655000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 21:57:12.339  6322  6322 W art     : b5655000-b565b000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 21:57:12.339  6322  6322 W art     : b565b000-b565c000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b565c000-b565d000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 21:57:12.339  6322  6322 W art     : b565d000-b565e000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 21:57:12.339  6322  6322 W art     : b565e000-b5667000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-12 21:57:12.339  6322  6322 W art     : b5667000-b5668000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-12 21:57:12.339  6322  6322 W art     : b5668000-b5669000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-12 21:57:12.339  6322  6322 W art     : b5669000-b56fa000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 21:57:12.339  6322  6322 W art     : b56fa000-b56fb000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b56fb000-b5706000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 21:57:12.339  6322  6322 W art     : b5706000-b5707000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 21:57:12.339  6322  6322 W art     : b5708000-b571a000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-12 21:57:12.339  6322  6322 W art     : b571a000-b571b000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-12 21:57:12.339  6322  6322 W art     : b571b000-b571c000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-12 21:57:12.339  6322  6322 W art     : b571d000-b5722000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-12 21:57:12.339  6322  6322 W art     : b5722000-b5723000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-12 21:57:12.339  6322  6322 W art     : b5723000-b5724000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-12 21:57:12.339  6322  6322 W art     : b5725000-b5792000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-12 21:57:12.339  6322  6322 W art     : b5792000-b5793000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5793000-b5795000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-12 21:57:12.339  6322  6322 W art     : b5795000-b5796000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-12 21:57:12.339  6322  6322 W art     : b5796000-b5797000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.339  6322  6322 W art     : b5797000-b579e000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 21:57:12.339  6322  6322 W art     : b579e000-b579f000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 21:57:12.339  6322  6322 W art     : b579f000-b57a0000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 21:57:12.339  6322  6322 W art     : b57a1000-b5821000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 21:57:12.339  6322  6322 W art     : b5821000-b5822000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5822000-b5823000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 21:57:12.339  6322  6322 W art     : b5823000-b5824000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 21:57:12.339  6322  6322 W art     : b5824000-b583b000 rw-p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b583b000-b5872000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-12 21:57:12.339  6322  6322 W art     : ib/libqc-opt.so
08-12 21:57:12.339  6322  6322 W art     : b5872000-b5873000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 21:57:12.339  6322  6322 W art     : b5873000-b5874000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 21:57:12.339  6322  6322 W art     : b5874000-b5890000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 21:57:12.339  6322  6322 W art     : b5890000-b5891000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 21:57:12.339  6322  6322 W art     : b5891000-b5892000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 21:57:12.339  6322  6322 W art     : b5893000-b58f4000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-12 21:57:12.339  6322  6322 W art     : b58f4000-b58f6000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-12 21:57:12.339  6322  6322 W art     : b58f6000-b58f7000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-12 21:57:12.339  6322  6322 W art     : b58f8000-b591f000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-12 21:57:12.339  6322  6322 W art     : b591f000-b5920000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5920000-b5921000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-12 21:57:12.339  6322  6322 W art     : b5921000-b5922000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-12 21:57:12.339  6322  6322 W art     : b5923000-b592b000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 21:57:12.339  6322  6322 W art     : b592b000-b592d000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 21:57:12.339  6322  6322 W art     : b592d000-b592e000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 21:57:12.339  6322  6322 W art     : b592f000-b5932000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-12 21:57:12.339  6322  6322 W art     : b5932000-b5933000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-12 21:57:12.339  6322  6322 W art     : b5933000-b5934000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-12 21:57:12.339  6322  6322 W art     : b5934000-b5938000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-12 21:57:12.339  6322  6322 W art     : b5938000-b5939000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5939000-b593a000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-12 21:57:12.339  6322  6322 W art     : b593a000-b593b000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-12 21:57:12.339  6322  6322 W art     : b593b000-b594b000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-12 21:57:12.339  6322  6322 W art     : b594b000-b594c000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-12 21:57:12.339  6322  6322 W art     : b594c000-b594d000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-12 21:57:12.339  6322  6322 W art     : b594d000-b5993000 rw-p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5993000-b599c000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-12 21:57:12.339  6322  6322 W art     : b599c000-b599d000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-12 21:57:12.339  6322  6322 W art     : b599d000-b599e000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-12 21:57:12.339  6322  6322 W art     : b599f000-b59a4000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-12 21:57:12.339  6322  6322 W art     : b59a4000-b59a5000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-12 21:57:12.339  6322  6322 W art     : b59a5000-b59a6000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-12 21:57:12.339  6322  6322 W art     : b59a6000-b59a9000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 21:57:12.339  6322  6322 W art     : b59a9000-b59aa000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b59aa000-b59ab000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 21:57:12.339  6322  6322 W art     : b59ab000-b59ac000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 21:57:12.339  6322  6322 W art     : b59ad000-b59c5000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 21:57:12.339  6322  6322 W art     : b59c5000-b59c6000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b59c6000-b59c7000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 21:57:12.339  6322  6322 W art     : b59c7000-b59c8000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 21:57:12.339  6322  6322 W art     : b59c9000-b5b63000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-12 21:57:12.339  6322  6322 W art     : b5b63000-b5b64000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5b64000-b5b71000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-12 21:57:12.339  6322  6322 W art     : b5b71000-b5b72000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-12 21:57:12.339  6322  6322 W art     : b5b72000-b5b76000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-12 21:57:12.339  6322  6322 W art     : b5b76000-b5b77000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5b77000-b5b78000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-12 21:57:12.339  6322  6322 W art     : b5b78000-b5b79000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-12 21:57:12.339  6322  6322 W art     : b5b79000-b5b8c000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-12 21:57:12.339  6322  6322 W art     : b5b8c000-b5b8d000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-12 21:57:12.339  6322  6322 W art     : b5b8d000-b5b8e000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-12 21:57:12.339  6322  6322 W art     : b5b8e000-b5b8f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 21:57:12.339  6322  6322 W art     : b5b8f000-b5bda000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-12 21:57:12.339  6322  6322 W art     : b5bda000-b5bdb000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-12 21:57:12.339  6322  6322 W art     : b5bdb000-b5bdc000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-12 21:57:12.339  6322  6322 W art     : b5bdc000-b5bde000 rw-p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5bdf000-b5bf0000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 21:57:12.339  6322  6322 W art     : b5bf0000-b5bf1000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5bf1000-b5bf2000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 21:57:12.339  6322  6322 W art     : b5bf2000-b5bf3000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 21:57:12.339  6322  6322 W art     : b5bf4000-b5bfe000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-12 21:57:12.339  6322  6322 W art     : b5bfe000-b5c00000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-12 21:57:12.339  6322  6322 W art     : b5c00000-b5c01000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-12 21:57:12.339  6322  6322 W art     : b5c01000-b5c1a000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-12 21:57:12.339  6322  6322 W art     : b5c1a000-b5c1b000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-12 21:57:12.339  6322  6322 W art     : b5c1b000-b5c1e000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-12 21:57:12.339  6322  6322 W art     : b5c1e000-b5c22000 rw-p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5c22000-b5c96000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-12 21:57:12.339  6322  6322 W art     : b5c96000-b5c97000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5c97000-b5c9a000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-12 21:57:12.339  6322  6322 W art     : b5c9a000-b5c9b000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-12 21:57:12.339  6322  6322 W art     : b5c9b000-b5c9c000 r--p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5c9c000-b5c9f000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-12 21:57:12.339  6322  6322 W art     : b5c9f000-b5ca0000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-12 21:57:12.339  6322  6322 W art     : b5ca0000-b5ca1000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-12 21:57:12.339  6322  6322 W art     : b5ca1000-b5ca2000 r--p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5ca2000-b5ca7000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 21:57:12.339  6322  6322 W art     : b5ca7000-b5ca8000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 21:57:12.339  6322  6322 W art     : b5ca8000-b5ca9000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 21:57:12.339  6322  6322 W art     : b5ca9000-b5caa000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.339  6322  6322 W art     : b5caa000-b5cad000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 21:57:12.339  6322  6322 W art     : b5cad000-b5cae000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 21:57:12.339  6322  6322 W art     : b5cae000-b5caf000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 21:57:12.339  6322  6322 W art     : b5caf000-b5cb0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.339  6322  6322 W art     : b5cb0000-b5cb4000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-12 21:57:12.339  6322  6322 W art     : b5cb4000-b5cb5000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-12 21:57:12.339  6322  6322 W art     : b5cb5000-b5cb6000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-12 21:57:12.339  6322  6322 W art     : b5cb6000-b5cb7000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 21:57:12.339  6322  6322 W art     : b5cb7000-b5cbb000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 21:57:12.339  6322  6322 W art     : b5cbb000-b5cbc000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 21:57:12.339  6322  6322 W art     : b5cbc000-b5cbd000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 21:57:12.339  6322  6322 W art     : b5cbd000-b5cbe000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.339  6322  6322 W art     : b5cbe000-b5ccc000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-12 21:57:12.339  6322  6322 W art     : b5ccc000-b5ccd000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b5ccd000-b5cce000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-12 21:57:12.339  6322  6322 W art     : b5cce000-b5ccf000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-12 21:57:12.339  6322  6322 W art     : b5ccf000-b5cd9000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 21:57:12.339  6322  6322 W art     : b5cd9000-b5cdc000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 21:57:12.339  6322  6322 W art     : b5cdc000-b5cdd000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 21:57:12.339  6322  6322 W art     : b5cdd000-b5cde000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.339  6322  6322 W art     : b5cde000-b5ce8000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-12 21:57:12.339  6322  6322 W art     : b5ce8000-b5ceb000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-12 21:57:12.339  6322  6322 W art     : b5ceb000-b5cec000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-12 21:57:12.339  6322  6322 W art     : b5cec000-b5cf0000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-12 21:57:12.339  6322  6322 W art     : b5cf0000-b5cf1000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-12 21:57:12.339  6322  6322 W art     : b5cf1000-b5cf2000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-12 21:57:12.339  6322  6322 W art     : b5cf2000-b5cf3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.339  6322  6322 W art     : b5cf3000-b5d00000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-12 21:57:12.339  6322  6322 W art     : b5d00000-b5d02000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-12 21:57:12.339  6322  6322 W art     : b5d02000-b5d03000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-12 21:57:12.339  6322  6322 W art     : b5d03000-b6115000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-12 21:57:12.339  6322  6322 W art     : b6115000-b6116000 ---p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b6116000-b611f000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-12 21:57:12.339  6322  6322 W art     : b611f000-b6123000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-12 21:57:12.339  6322  6322 W art     : b6123000-b6124000 rw-p 00000000 00:00 0 
08-12 21:57:12.339  6322  6322 W art     : b6124000-b612b000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-12 21:57:12.339  6322  6322 W art     : b612b000-b612c000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-12 21:57:12.339  6322  6322 W art     : b612c000-b612d000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-12 21:57:12.339  6322  6322 W art     : b612d000-b612e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.339  6322  6322 W art     : b612e000-b6149000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-12 21:57:12.339  6322  6322 W art     : b6149000-b614a000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-12 21:57:12.339  6322  6322 W art     : b614a000-b614b000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-12 21:57:12.349  6322  6322 W art     : b614b000-b614c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.349  6322  6322 W art     : b614c000-b6198000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 21:57:12.349  6322  6322 W art     : b6198000-b6199000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6199000-b619a000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 21:57:12.349  6322  6322 W art     : b619a000-b619b000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 21:57:12.349  6322  6322 W art     : b619b000-b619c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.349  6322  6322 W art     : b619c000-b61a0000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-12 21:57:12.349  6322  6322 W art     : b61a0000-b61a1000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b61a1000-b61a2000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-12 21:57:12.349  6322  6322 W art     : b61a2000-b61a3000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-12 21:57:12.349  6322  6322 W art     : b61a3000-b61db000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-12 21:57:12.349  6322  6322 W art     : b61db000-b61dc000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-12 21:57:12.349  6322  6322 W art     : b61dc000-b61dd000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-12 21:57:12.349  6322  6322 W art     : b61dd000-b61de000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.349  6322  6322 W art     : b61de000-b627c000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-12 21:57:12.349  6322  6322 W art     : b627c000-b627d000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b627d000-b629b000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-12 21:57:12.349  6322  6322 W art     : b629b000-b629c000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-12 21:57:12.349  6322  6322 W art     : b629c000-b640f000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-12 21:57:12.349  6322  6322 W art     : b640f000-b641a000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-12 21:57:12.349  6322  6322 W art     : b641a000-b641b000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-12 21:57:12.349  6322  6322 W art     : b641b000-b6532000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-12 21:57:12.349  6322  6322 W art     : b6532000-b653d000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-12 21:57:12.349  6322  6322 W art     : b653d000-b653e000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-12 21:57:12.349  6322  6322 W art     : b653e000-b6542000 rw-p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6542000-b6566000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-12 21:57:12.349  6322  6322 W art     : b6566000-b6568000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-12 21:57:12.349  6322  6322 W art     : b6568000-b6569000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-12 21:57:12.349  6322  6322 W art     : b6569000-b660f000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-12 21:57:12.349  6322  6322 W art     : b660f000-b661c000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-12 21:57:12.349  6322  6322 W art     : b661c000-b661d000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-12 21:57:12.349  6322  6322 W art     : b661d000-b661e000 rw-p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b661e000-b6671000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-12 21:57:12.349  6322  6322 W art     : b6671000-b6672000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6672000-b6673000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-12 21:57:12.349  6322  6322 W art     : b6673000-b6674000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-12 21:57:12.349  6322  6322 W art     : b6674000-b6679000 rw-p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6679000-b668b000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-12 21:57:12.349  6322  6322 W art     : b668b000-b668c000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b668c000-b668d000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-12 21:57:12.349  6322  6322 W art     : b668d000-b668e000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-12 21:57:12.349  6322  6322 W art     : b668e000-b6695000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 21:57:12.349  6322  6322 W art     : b6695000-b6696000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 21:57:12.349  6322  6322 W art     : b6696000-b6697000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 21:57:12.349  6322  6322 W art     : b6697000-b6698000 rw-p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6698000-b669b000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-12 21:57:12.349  6322  6322 W art     : b669b000-b669c000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-12 21:57:12.349  6322  6322 W art     : b669c000-b669d000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-12 21:57:12.349  6322  6322 W art     : b669d000-b66a1000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-12 21:57:12.349  6322  6322 W art     : b66a1000-b66a2000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-12 21:57:12.349  6322  6322 W art     : b66a2000-b66a3000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-12 21:57:12.349  6322  6322 W art     : b66a3000-b66b1000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-12 21:57:12.349  6322  6322 W art     : b66b1000-b66b2000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b66b2000-b66b3000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-12 21:57:12.349  6322  6322 W art     : b66b3000-b66b4000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-12 21:57:12.349  6322  6322 W art     : b66b4000-b66bd000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 21:57:12.349  6322  6322 W art     : b66bd000-b66be000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 21:57:12.349  6322  6322 W art     : b66be000-b66bf000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 21:57:12.349  6322  6322 W art     : b66bf000-b6725000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-12 21:57:12.349  6322  6322 W art     : b6725000-b6726000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6726000-b6728000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-12 21:57:12.349  6322  6322 W art     : b6728000-b6731000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-12 21:57:12.349  6322  6322 W art     : b6731000-b6734000 rw-p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6734000-b67cb000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-12 21:57:12.349  6322  6322 W art     : b67cb000-b67cd000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-12 21:57:12.349  6322  6322 W art     : b67cd000-b67ce000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-12 21:57:12.349  6322  6322 W art     : b67ce000-b67cf000 rw-p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b67cf000-b6af0000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-12 21:57:12.349  6322  6322 W art     : b6af0000-b6af1000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6af1000-b6b0c000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-12 21:57:12.349  6322  6322 W art     : b6b0c000-b6b10000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-12 21:57:12.349  6322  6322 W art     : b6b10000-b6b15000 rw-p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6b15000-b6b1d000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 21:57:12.349  6322  6322 W art     : b6b1d000-b6b1e000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 21:57:12.349  6322  6322 W art     : b6b1e000-b6b1f000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 21:57:12.349  6322  6322 W art     : b6b1f000-b6b4d000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-12 21:57:12.349  6322  6322 W art     : b6b4d000-b6b4e000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6b4e000-b6b55000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-12 21:57:12.349  6322  6322 W art     : b6b55000-b6b56000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-12 21:57:12.349  6322  6322 W art     : b6b56000-b6b9c000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-12 21:57:12.349  6322  6322 W art     : b6b9c000-b6b9d000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6b9d000-b6ba0000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-12 21:57:12.349  6322  6322 W art     : b6ba0000-b6ba1000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-12 21:57:12.349  6322  6322 W art     : b6ba1000-b6bbc000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-12 21:57:12.349  6322  6322 W art     : b6bbc000-b6bc0000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-12 21:57:12.349  6322  6322 W art     : b6bc0000-b6bc1000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-12 21:57:12.349  6322  6322 W art     : b6bc1000-b6c0e000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-12 21:57:12.349  6322  6322 W art     : b6c0e000-b6c0f000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6c0f000-b6c1b000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-12 21:57:12.349  6322  6322 W art     : b6c1b000-b6c1c000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-12 21:57:12.349  6322  6322 W art     : b6c1c000-b6c29000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-12 21:57:12.349  6322  6322 W art     : b6c29000-b6c2a000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6c2a000-b6c2b000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-12 21:57:12.349  6322  6322 W art     : b6c2b000-b6c2c000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-12 21:57:12.349  6322  6322 W art     : b6c2c000-b6c34000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-12 21:57:12.349  6322  6322 W art     : b6c34000-b6c35000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6c35000-b6c36000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-12 21:57:12.349  6322  6322 W art     : b6c36000-b6c37000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-12 21:57:12.349  6322  6322 W art     : b6c37000-b6c3e000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-12 21:57:12.349  6322  6322 W art     : b6c3e000-b6c3f000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-12 21:57:12.349  6322  6322 W art     : b6c3f000-b6c40000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-12 21:57:12.349  6322  6322 W art     : b6c40000-b6c54000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-12 21:57:12.349  6322  6322 W art     : b6c54000-b6c56000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-12 21:57:12.349  6322  6322 W art     : b6c56000-b6c57000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-12 21:57:12.349  6322  6322 W art     : b6c57000-b6c7f000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-12 21:57:12.349  6322  6322 W art     : b6c7f000-b6c81000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-12 21:57:12.349  6322  6322 W art     : b6c81000-b6c82000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-12 21:57:12.349  6322  6322 W art     : b6c82000-b6c85000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-12 21:57:12.349  6322  6322 W art     : b6c85000-b6c86000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-12 21:57:12.349  6322  6322 W art     : b6c86000-b6c87000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-12 21:57:12.349  6322  6322 W art     : b6c87000-b6c90000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-12 21:57:12.349  6322  6322 W art     : b6c90000-b6c91000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-12 21:57:12.349  6322  6322 W art     : b6c91000-b6c92000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-12 21:57:12.349  6322  6322 W art     : b6c92000-b6cb2000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-12 21:57:12.349  6322  6322 W art     : b6cb2000-b6cb3000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-12 21:57:12.349  6322  6322 W art     : b6cb3000-b6cb4000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-12 21:57:12.349  6322  6322 W art     : b6cb4000-b6d27000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-12 21:57:12.349  6322  6322 W art     : b6d27000-b6d2b000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-12 21:57:12.349  6322  6322 W art     : b6d2b000-b6d2e000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-12 21:57:12.349  6322  6322 W art     : b6d2e000-b6d38000 rw-p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6d38000-b6dc0000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-12 21:57:12.349  6322  6322 W art     : b6dc0000-b6dc1000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6dc1000-b6dc5000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-12 21:57:12.349  6322  6322 W art     : b6dc5000-b6dc6000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-12 21:57:12.349  6322  6322 W art     : b6dc6000-b6dc7000 rw-p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6dc7000-b6df0000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-12 21:57:12.349  6322  6322 W art     : b6df0000-b6df1000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6df1000-b6df4000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-12 21:57:12.349  6322  6322 W art     : b6df4000-b6df5000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-12 21:57:12.349  6322  6322 W art     : b6df5000-b6ecf000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 21:57:12.349  6322  6322 W art     : b6ecf000-b6ed6000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 21:57:12.349  6322  6322 W art     : b6ed6000-b6ede000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 21:57:12.349  6322  6322 W art     : b6ede000-b6edf000 rw-p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6edf000-b6ee0000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 21:57:12.349  6322  6322 W art     : b6ee0000-b6ee1000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-12 21:57:12.349  6322  6322 W art     : b6ee1000-b6ee2000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.349  6322  6322 W art     : b6ee2000-b6ee5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.349  6322  6322 W art     : b6ee5000-b6f0a000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-12 21:57:12.349  6322  6322 W art     : b6f0a000-b6f0b000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6f0b000-b6f12000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-12 21:57:12.349  6322  6322 W art     : b6f12000-b6f13000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-12 21:57:12.349  6322  6322 W art     : b6f13000-b6f1a000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-12 21:57:12.349  6322  6322 W art     : b6f1a000-b6f1b000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-12 21:57:12.349  6322  6322 W art     : b6f1b000-b6f1c000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-12 21:57:12.349  6322  6322 W art     : b6f1c000-b6f1d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.349  6322  6322 W art     : b6f1d000-b6f35000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-12 21:57:12.349  6322  6322 W art     : b6f35000-b6f36000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6f36000-b6f37000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-12 21:57:12.349  6322  6322 W art     : b6f37000-b6f38000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-12 21:57:12.349  6322  6322 W art     : b6f38000-b6f46000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-12 21:57:12.349  6322  6322 W art     : b6f46000-b6f47000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6f47000-b6f48000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-12 21:57:12.349  6322  6322 W art     : b6f48000-b6f49000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-12 21:57:12.349  6322  6322 W art     : b6f49000-b6f4a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 21:57:12.349  6322  6322 W art     : b6f4a000-b6f4c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.349  6322  6322 W art     : b6f4c000-b6f4d000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.349  6322  6322 W art     : b6f4d000-b6f4e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 21:57:12.349  6322  6322 W art     : b6f4e000-b6f4f000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-12 21:57:12.349  6322  6322 W art     : b6f4f000-b6f50000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 21:57:12.349  6322  6322 W art     : b6f50000-b6f70000 r--s 00000000 00:0b 6702       /dev/__properties__
08-12 21:57:12.349  6322  6322 W art     : b6f70000-b6f71000 r--p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6f71000-b6f72000 ---p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6f72000-b6f74000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-12 21:57:12.349  6322  6322 W art     : b6f74000-b6f75000 r-xp 00000000 00:00 0          [sigpage]
08-12 21:57:12.349  6322  6322 W art     : b6f75000-b6f90000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-12 21:57:12.349  6322  6322 W art     : b6f90000-b6f91000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-12 21:57:12.349  6322  6322 W art     : b6f91000-b6f93000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-12 21:57:12.349  6322  6322 W art     : b6f93000-b6f95000 rw-p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : b6f95000-b6f9a000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-12 21:57:12.349  6322  6322 W art     : b6f9a000-b6f9b000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-12 21:57:12.349  6322  6322 W art     : b6f9b000-b6f9c000 rw-p 00000000 00:00 0 
08-12 21:57:12.349  6322  6322 W art     : bec8e000-becaf000 rw-p 00000000 00:00 0          [stack]
08-12 21:57:12.349  6322  6322 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-12 21:57:12.389  6322  6322 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 21:57:12.439  6322  6322 I Radio-JNI: register_android_hardware_Radio DONE
08-12 21:57:12.439  6322  6322 E AffinityControl: AffinityControl: registerfunction enter
08-12 21:57:12.459  6322  6322 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 21:57:12.469   753  1409 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-12 21:57:12.489   753  1409 D ActivityManager: mDVFSHelper.acquire()
08-12 21:57:12.489   753  1409 D FocusedStackFrame: Set to : 0
08-12 21:57:12.489   753  1409 V WindowManager: addAppToken: AppWindowToken{9d51ea6 token=Token{aa52001 ActivityRecord{2b731e8 u0 com.test.thalitest/.MainActivity t167}}} to stack=1 task=167 at 0
08-12 21:57:12.499   753   877 D SecWifiDisplayUtil: Metadata value : none
08-12 21:57:12.499   753   877 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6975c7e V.E...... R.....ID 0,0-0,0}
08-12 21:57:12.499   753   877 D ISSUE_DEBUG: InputChannelName : 950d22c Starting com.test.thalitest
08-12 21:57:12.509   753  1409 I ActivityManager: Start proc 6336:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-12 21:57:12.509  6336  6336 E Zygote  : v2
08-12 21:57:12.509  6336  6336 I libpersona: KNOX_SDCARD checking this for 10004
08-12 21:57:12.509   753  1409 D InputDispatcher: Focused application set to: xxxx
08-12 21:57:12.509  6336  6336 I libpersona: KNOX_SDCARD not a persona
08-12 21:57:12.509  6336  6336 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:12.509   753  1409 D InputDispatcher: Focus left window: 1721
08-12 21:57:12.509  6336  6336 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 21:57:12.509   753  1318 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-12 21:57:12.509  6322  6322 D AndroidRuntime: Shutting down VM
08-12 21:57:12.509  6336  6336 E Zygote  : accessInfo : 0
08-12 21:57:12.509  6336  6336 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-12 21:57:12.519   292   292 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, uhalitest
08-12 21:57:12.529   753   877 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:753 uid:1000
08-12 21:57:12.529   753   877 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 21:57:12.529   753   877 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:753 uid:1000
08-12 21:57:12.529   753   877 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-12 21:57:12.529   753   877 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-12 21:57:12.539  6336  6336 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 21:57:12.539  6336  6336 D ActivityThread: Added TimaKeyStore provider
08-12 21:57:12.539   753  1625 V WindowOrientationListener: setCurrentAppOrientation :-1
08-12 21:57:12.539   753  1625 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-12 21:57:12.549   753   824 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{950d22c u0 d0 Starting com.test.thalitest}
08-12 21:57:12.549  1373  1373 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-12 21:57:12.549  1721  1881 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-12 21:57:12.549  1721  1721 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-12 21:57:12.549   753  1625 D ActivityManager:  Launching com.test.thalitest, updated priority
08-12 21:57:12.569   292  1851 D libEGL  : eglTerminate EGLDisplay = 0xb0aaa64c
08-12 21:57:12.569   292  1851 D libEGL  : eglTerminate EGLDisplay = 0xb0aaa64c
08-12 21:57:12.579   292   344 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-12 21:57:12.579   292  1851 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-12 21:57:12.589   753   877 V WindowStateAnimator: Finishing drawing window Window{950d22c u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-12 21:57:12.589  2430  2447 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-12 21:57:12.589  1721  1721 V ActivityThread: updateVisibility : ActivityRecord{3a7064d token=android.os.BinderProxy@9c4df26 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-12 21:57:12.589  1721  1721 D Launcher: onTrimMemory. Level: 20
08-12 21:57:12.589   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbebec3a4
08-12 21:57:12.589   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbebec364
,08-12 21:57:12.879   753  1625 I WindowManager: Screenshot max retries 4 of Token{aa52001 ActivityRecord{2b731e8 u0 com.test.thalitest/.MainActivity t167}} appWin=Window{950d22c u0 d0 Starting com.test.thalitest} drawState=2
,08-12 21:57:12.879   753   822 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,08-12 21:57:12.889   753  1318 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-12 21:57:12.899  6336  6336 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 21:57:12.909   753  3416 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 21:57:12.929  6336  6336 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 21:57:12.929  6336  6336 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 21:57:12.939  6336  6336 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-12 21:57:12.969  6336  6336 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 21:57:12.979  6336  6336 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-12 21:57:12.989  6336  6336 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 5927-5930)
,08-12 21:57:12.989  6336  6336 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-12 21:57:12.999  6336  6336 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {318b436}
,08-12 21:57:12.999  6336  6336 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-12 21:57:13.009  6336  6336 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-12 21:57:13.009  6336  6353 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-12 21:57:13.009  6336  6336 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-12 21:57:13.039  6336  6336 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 21:57:13.039  6336  6336 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 21:57:13.039  6336  6336 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 21:57:13.039  6336  6336 I Adreno-EGL: Local Branch: ss
08-12 21:57:13.039  6336  6336 I Adreno-EGL: Remote Branch: 
08-12 21:57:13.039  6336  6336 I Adreno-EGL: Local Patches: 
08-12 21:57:13.039  6336  6336 I Adreno-EGL: Reconstruct Branch: 
,08-12 21:57:13.039  6336  6336 D libEGL  : eglInitialize EGLDisplay = 0xbeb91dac
,08-12 21:57:13.089   753   767 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-12 21:57:13.089   753   767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-12 21:57:13.129  6336  6336 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-12 21:57:13.139  6336  6336 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 21:57:13.139  6336  6336 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-12 21:57:13.139  6336  6336 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-12 21:57:13.139  6336  6336 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-12 21:57:13.159  6336  6336 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-12 21:57:13.159  6336  6336 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-12 21:57:13.229  6336  6336 D SecWifiDisplayUtil: Metadata value : none
,08-12 21:57:13.239  6336  6336 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{c311d04 I.E...... R.....ID 0,0-0,0}
,08-12 21:57:13.239  6336  6383 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 21:57:13.239   753  1745 D ISSUE_DEBUG: InputChannelName : b11dd19 com.test.thalitest/com.test.thalitest.MainActivity
,08-12 21:57:13.239   753  1218 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-12 21:57:13.239   753  1218 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-12 21:57:13.239   753   753 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 21:57:13.239   753   753 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-12 21:57:13.259  6336  6336 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6336
,08-12 21:57:13.259   753   767 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6336 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 21:57:13.259   753  1327 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-12 21:57:13.269   753  1327 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-12 21:57:13.269   753  1327 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-12 21:57:13.269   753  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 21:57:13.269   753  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 21:57:13.269   753  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 21:57:13.269   753  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-12 21:57:13.269   753  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 21:57:13.269   753  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 21:57:13.269   753  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,08-12 21:57:13.269   753  1327 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 21:57:13.279  6336  6353 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-12 21:57:13.279  6336  6336 D SecWifiDisplayUtil: Metadata value : none
,08-12 21:57:13.289   292   292 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, NainActivit
,08-12 21:57:13.289   753   765 D InputDispatcher: Focus entered window: 6336
,08-12 21:57:13.289   753   877 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:753 uid:1000
08-12 21:57:13.289   753   877 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 21:57:13.289   753   877 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:753 uid:1000
08-12 21:57:13.289   753   877 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 21:57:13.289  6336  6383 D libEGL  : eglInitialize EGLDisplay = 0x9caf97c4
08-12 21:57:13.289  6336  6383 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 21:57:13.349  6336  6336 V ActivityThread: updateVisibility : ActivityRecord{5df400f token=android.os.BinderProxy@15ec517 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-12 21:57:13.349  6336  6336 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-12 21:57:13.349  6336  6336 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-12 21:57:13.349   753  1218 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-12 21:57:13.359  6336  6336 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-12 21:57:13.369  5444  5444 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
,08-12 21:57:13.369  5444  5444 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-12 21:57:13.369  5444  5444 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
,08-12 21:57:13.369  5444  5444 I art     : System.exit called, status: 0
08-12 21:57:13.369  5444  5444 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-12 21:57:13.389   753  1741 V WindowStateAnimator: Finishing drawing window Window{b11dd19 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-12 21:57:13.389  6336  6336 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-12 21:57:13.389  6336  6336 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@15ec517 time:106336
,08-12 21:57:13.399   753   877 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 21:57:13.399   753   753 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 21:57:13.399   753   753 I KnoxTimeoutHandler: SD activityfalse
,08-12 21:57:13.399   753   877 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +523ms (total +907ms)
,08-12 21:57:13.399   753   877 D ActivityManager: mDVFSHelper.release()
08-12 21:57:13.399   753   877 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2b731e8 u0 com.test.thalitest/.MainActivity t167} time:106348
,08-12 21:57:13.399  5395  5395 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-12 21:57:13.399   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbebec364
,08-12 21:57:13.409   753  1745 I ActivityManager: Process com.samsung.aasaservice (pid 5444)(adj 0) has died(94,743)
08-12 21:57:13.409   753   877 D ViewRootImpl: #3 mView = null
,08-12 21:57:13.409   292  1851 I SurfaceFlinger: id=19 Removed uhalitest (7/9)
,08-12 21:57:13.409   292  1683 I SurfaceFlinger: id=19 Removed uhalitest (-2/9)
,08-12 21:57:13.409  6336  6392 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-12 21:57:13.409  6336  6392 D libEGL  : eglInitialize EGLDisplay = 0x9a25e3ec
,08-12 21:57:13.409   753  1745 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-12 21:57:13.409   753  1745 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-12 21:57:13.419   753  1745 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
,08-12 21:57:13.419   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbebec3a4
,08-12 21:57:13.429   753   822 I ActivityManager: Start proc 6396:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
,08-12 21:57:13.429   753  1318 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-12 21:57:13.429  6396  6396 E Zygote  : v2
,08-12 21:57:13.429  6396  6396 I libpersona: KNOX_SDCARD checking this for 10014
08-12 21:57:13.429  6396  6396 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:13.429  6396  6396 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 21:57:13.439  6396  6396 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 21:57:13.439  6396  6396 E Zygote  : accessInfo : 0
,08-12 21:57:13.439  6396  6396 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
,08-12 21:57:13.459  6396  6396 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 21:57:13.459  6396  6396 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:13.459  6336  6336 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6336
,08-12 21:57:13.469   753  2228 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca15eb6 6396:com.google.android.partnersetup/u0a14}
,08-12 21:57:13.469   753  1318 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-12 21:57:13.469  6396  6396 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
,08-12 21:57:13.479  6396  6396 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,08-12 21:57:13.509   753  1620 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca15eb6 6396:com.google.android.partnersetup/u0a14}
,08-12 21:57:13.529   753  1620 I ActivityManager: Start proc 6413:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
,08-12 21:57:13.529  6413  6413 E Zygote  : v2
08-12 21:57:13.529  6413  6413 I libpersona: KNOX_SDCARD checking this for 10015
08-12 21:57:13.529  6413  6413 I libpersona: KNOX_SDCARD not a persona
08-12 21:57:13.529   753  1318 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-12 21:57:13.529  6413  6413 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:13.529  6413  6413 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 21:57:13.529  6413  6413 E Zygote  : accessInfo : 0
08-12 21:57:13.529  6413  6413 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-12 21:57:13.529   753  1318 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-12 21:57:13.539   753  2227 I ActivityManager: Killing 5547:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-12 21:57:13.549   753  1742 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-12 21:57:13.559  6413  6413 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 21:57:13.559  6413  6413 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:13.569   753  1741 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{587c68d 6413:com.samsung.groupcast/u0a15}
,08-12 21:57:13.579  6413  6413 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
,08-12 21:57:13.579  6336  6336 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 21:57:13.599  6413  6413 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
,08-12 21:57:13.619  6413  6413 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
,08-12 21:57:13.619  6413  6413 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
,08-12 21:57:13.619  6413  6413 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-12 21:57:13.619  6413  6413 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-12 21:57:13.619  6413  6413 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-12 21:57:13.619  6413  6413 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-12 21:57:13.619  6413  6413 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-12 21:57:13.619  6413  6413 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-12 21:57:13.619  6413  6413 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-12 21:57:13.619  6413  6413 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 21:57:13.619  6413  6413 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-12 21:57:13.619  6413  6413 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-12 21:57:13.619  6413  6413 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 21:57:13.619  6413  6413 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-12 21:57:13.619  6413  6413 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-12 21:57:13.629   753  1409 I ActivityManager: Killing 5632:com.sec.android.app.camera/u0a153 (adj 15): DHA:empty #37
,08-12 21:57:13.629   753  1409 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5ee10bc 1884:com.sec.android.app.shealth:remote/u0a34}
,08-12 21:57:13.649  6426  6426 E Zygote  : v2
08-12 21:57:13.649  6426  6426 I libpersona: KNOX_SDCARD checking this for 10041
08-12 21:57:13.649  6426  6426 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:13.649   753   765 I ActivityManager: Start proc 6426:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
,08-12 21:57:13.649   753  1318 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-12 21:57:13.649  6426  6426 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:13.649  6426  6426 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 21:57:13.649  6426  6426 E Zygote  : accessInfo : 0
,08-12 21:57:13.649  6426  6426 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
,08-12 21:57:13.649   753  1318 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-12 21:57:13.659   753  1440 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.camera, Auto Run ON
,08-12 21:57:13.689  6426  6426 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 21:57:13.689  6426  6426 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:13.699   753  1799 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{75cb042 6426:com.samsung.android.sdk.samsunglink/u0a41}
,08-12 21:57:13.699  6426  6426 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
,08-12 21:57:13.749  6336  6438 D jxcore_app_log: JniHelper::setJavaVM(0xb47bc000), pthread_self() = -1717307088
,08-12 21:57:13.759  6336  6438 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 21:57:13.759  6336  6438 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 21:57:13.759  6336  6438 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 21:57:13.759  6336  6438 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 21:57:13.759  6336  6438 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 21:57:13.759  6336  6438 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d415d added. We now have 1 listener(s)
,08-12 21:57:13.759  6336  6438 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-12 21:57:13.759  6336  6438 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-12 21:57:13.759  6336  6438 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 21:57:13.759  6336  6438 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 21:57:13.769  6336  6438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 21:57:13.769  6336  6438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 21:57:13.769  6336  6438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 21:57:13.769  6336  6438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-12 21:57:13.769  6336  6438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 21:57:13.769  6336  6438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 21:57:13.769  6336  6438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 21:57:13.769  6336  6438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 21:57:13.769  6336  6438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 21:57:13.769  6336  6438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 21:57:13.769  6336  6438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 21:57:13.769  6336  6438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 21:57:13.769  6336  6438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 21:57:13.769  6336  6438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-12 21:57:13.769  6336  6438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afcaaa0 added. We now have 1 listener(s)
08-12 21:57:13.769  6336  6438 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 21:57:13.769  6336  6438 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 21:57:13.769  6336  6438 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 21:57:13.769  6336  6438 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 21:57:13.769  6336  6438 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-12 21:57:13.769  6336  6438 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 21:57:13.769  6336  6438 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 21:57:13.769  6336  6438 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-12 21:57:13.779  6336  6438 D BluetoothAdapter: STATE_ON
,08-12 21:57:13.779  6336  6438 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-12 21:57:13.779  6336  6438 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 21:57:13.779  6336  6438 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 21:57:13.779  6336  6438 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 21:57:13.779  6336  6438 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 21:57:13.779  6336  6438 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 21:57:13.779  6336  6438 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 21:57:13.779  6336  6438 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 21:57:13.779  6336  6438 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 21:57:13.779  6336  6438 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 21:57:13.779  6336  6438 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 21:57:13.779  6336  6438 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 21:57:13.779  6336  6336 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 21:57:13.779  6336  6336 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 21:57:13.789  6426  6426 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 21:57:13.789  6426  6426 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 21:57:13.809  6336  6336 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 21:57:13.849  6426  6426 I SL_DEBUG: isLoggable:: isProductShip = 1
,08-12 21:57:13.849  6426  6426 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
,08-12 21:57:13.859   753  1745 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
,08-12 21:57:13.869   753  1798 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
,08-12 21:57:13.869   753  1742 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
,08-12 21:57:13.869   753  1409 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
,08-12 21:57:13.869   753  1741 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
,08-12 21:57:13.879   753  2219 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
,08-12 21:57:13.879   753  1440 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-12 21:57:13.879   753  2228 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-12 21:57:13.879   753  2125 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-12 21:57:13.879   753  1218 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
,08-12 21:57:13.889   753  3417 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-12 21:57:13.979  6426  6426 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
,08-12 21:57:13.979  6426  6426 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-12 21:57:13.979  6426  6426 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-12 21:57:13.979  6426  6426 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-12 21:57:13.979  6426  6426 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-12 21:57:13.979  6426  6426 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-12 21:57:13.979  6426  6426 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-12 21:57:13.979  6426  6426 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-12 21:57:13.979  6426  6426 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-12 21:57:13.979  6426  6426 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-12 21:57:13.979  6426  6426 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 21:57:13.979  6426  6426 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-12 21:57:13.979  6426  6426 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-12 21:57:13.979  6426  6426 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-12 21:57:13.979  6426  6426 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
,08-12 21:57:13.979  6426  6426 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-12 21:57:13.989   753  1440 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a9b1e53 1656:android.process.acore/u0a19}
,08-12 21:57:13.999   753  2125 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6e464c 5125:com.sec.android.gallery3d/u0a47}
,08-12 21:57:13.999  5125  5125 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-12 21:57:14.009   753  1798 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 21:57:14.019  6451  6451 E Zygote  : v2
08-12 21:57:14.019  6451  6451 I libpersona: KNOX_SDCARD checking this for 10050
08-12 21:57:14.019  6451  6451 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:14.019  6451  6451 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:14.019  6451  6451 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 21:57:14.019  6451  6451 E Zygote  : accessInfo : 0
,08-12 21:57:14.019  6451  6451 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-12 21:57:14.019   753  1742 I ActivityManager: Start proc 6451:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
,08-12 21:57:14.049  6451  6451 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 21:57:14.049  6451  6451 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:14.059   753  2219 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba8aec 6451:com.sec.android.app.myfiles/u0a50}
,08-12 21:57:14.059   753  2219 I ActivityManager: Killing 5234:com.android.mms/u0a49 (adj 15): DHA:empty #37
,08-12 21:57:14.069  6451  6451 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
,08-12 21:57:14.079   753  1218 D CountryDetector: No listener is left
,08-12 21:57:14.079   753  1799 D ActivityManager: isAutoRunBlockedApp:: com.android.mms, Auto Run ON
,08-12 21:57:14.089  6451  6451 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
,08-12 21:57:14.129  6451  6451 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,08-12 21:57:14.139   753  1798 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{821a7b 2841:com.android.settings/1000}
,08-12 21:57:14.159   329   329 E installd: system dir 0 : /system/app/
08-12 21:57:14.159   329   329 E installd: system dir 1 : /system/priv-app/
08-12 21:57:14.159   329   329 E installd: system dir 2 : /vendor/app/
08-12 21:57:14.159   329   329 E installd: system dir 3 : /oem/app/
08-12 21:57:14.159   753  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{821a7b 2841:com.android.settings/1000}
,08-12 21:57:14.169   753   917 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,08-12 21:57:14.169  6465  6465 E Zygote  : v2
08-12 21:57:14.169  6465  6465 I libpersona: KNOX_SDCARD checking this for 10169
08-12 21:57:14.169  6465  6465 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:14.179  6465  6465 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:14.179  6465  6465 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 21:57:14.179  6465  6465 E Zygote  : accessInfo : 0
,08-12 21:57:14.179  6465  6465 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
,08-12 21:57:14.179   753  1741 I ActivityManager: Start proc 6465:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,08-12 21:57:14.209  6465  6465 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 21:57:14.209  6465  6465 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:14.229  3681  3681 D FactoryTest: User mode
,08-12 21:57:14.229   753  1620 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{73b69d8 6465:com.samsung.android.provider.shootingmodeprovider/u0a169}
,08-12 21:57:14.229  3681  3681 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-12 21:57:14.229  3681  3681 D MTPRx   : still no open session command from host, so toast
,08-12 21:57:14.239   753  1625 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-12 21:57:14.249   753  1625 D ActivityManager: mDVFSHelper.acquire()
,08-12 21:57:14.249   753  1625 V WindowManager: addAppToken: AppWindowToken{4389d97 token=Token{3967016 ActivityRecord{39c1131 u0 com.samsung.android.MtpApplication/.USBConnection t168}}} to stack=1 task=168 at 0
,08-12 21:57:14.249   753  1625 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-12 21:57:14.259  6465  6465 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
,08-12 21:57:14.259  6465  6465 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
,08-12 21:57:14.269   753  1625 D InputDispatcher: Focused application set to: xxxx
,08-12 21:57:14.269   753  1625 D InputDispatcher: Focus left window: 6336
,08-12 21:57:14.269   753   822 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-12 21:57:14.269  3681  3681 E MTPRx   : started activity for popup
,08-12 21:57:14.269  1447  1447 D Recents : onTaskStackChanged
,08-12 21:57:14.279   753   877 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:753 uid:1000
08-12 21:57:14.279   753   877 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 21:57:14.279   753   877 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:753 uid:1000
08-12 21:57:14.279   753   877 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 21:57:14.279  3681  3681 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-12 21:57:14.279  3681  3681 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-12 21:57:14.279  1447  1447 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-12 21:57:14.289  3681  3681 D MTPUSBConnection: onCreate in USBConnection
08-12 21:57:14.289  3681  3681 V MTPUSBConnection: Registering broadcast receiver.
,08-12 21:57:14.289  3681  3681 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-12 21:57:14.299   753  1745 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-12 21:57:14.319   753  2125 I ActivityManager: Killing 5644:com.sec.android.GeoLookout/u0a112 (adj 15): DHA:empty #37
,08-12 21:57:14.319   753  2125 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ebc585 1711:com.android.phone/1001}
,08-12 21:57:14.339   753  2125 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{77011ee 1826:com.google.android.googlequicksearchbox:search/u0a61}
,08-12 21:57:14.339  3681  3681 D TAG     : dev.kiessupport is : TRUE
,08-12 21:57:14.349  1447  1447 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-12 21:57:14.349   753  1409 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.GeoLookout, Auto Run ON
,08-12 21:57:14.359   753  1218 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{77011ee 1826:com.google.android.googlequicksearchbox:search/u0a61}
,08-12 21:57:14.369  3681  3681 D SecWifiDisplayUtil: Metadata value : none
,08-12 21:57:14.369  3681  3681 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{3cfadc7 V.E...... R.....I. 0,0-0,0}
,08-12 21:57:14.379  3681  6480 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 21:57:14.379   753  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e0ba88f 6272:com.samsung.android.sm.provider/1000}
,08-12 21:57:14.379   753  1218 D ISSUE_DEBUG: InputChannelName : 2883f25 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-12 21:57:14.379   753  1218 D InputDispatcher: Focus entered window: 3681
,08-12 21:57:14.379   753   824 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2883f25 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-12 21:57:14.379  1373  1373 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
08-12 21:57:14.379   753   877 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:753 uid:1000
,08-12 21:57:14.379   753   877 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 21:57:14.379   753   877 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:753 uid:1000
08-12 21:57:14.379   753   877 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 21:57:14.389  1826  6479 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-12 21:57:14.399  3681  3681 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{10e8ebf I.E...... R.....I. 0,0-0,0}
,08-12 21:57:14.399   753  2219 D ISSUE_DEBUG: InputChannelName : 3243eab com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-12 21:57:14.399  6482  6482 E Zygote  : v2
,08-12 21:57:14.399   753  2228 I ActivityManager: Start proc 6482:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-12 21:57:14.399  6482  6482 I libpersona: KNOX_SDCARD checking this for 5012
08-12 21:57:14.399  6482  6482 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:14.399  6482  6482 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:14.399  6482  6482 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 21:57:14.409  6482  6482 E Zygote  : accessInfo : 0
,08-12 21:57:14.409  6482  6482 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
,08-12 21:57:14.409   753  1798 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-12 21:57:14.409   753  1798 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 21:57:14.409   753   753 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 21:57:14.419   753   753 I KnoxTimeoutHandler: Shared devices show user statefalse
08-12 21:57:14.419   753   753 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-12 21:57:14.429  6493  6493 E Zygote  : v2
08-12 21:57:14.429  6493  6493 I libpersona: KNOX_SDCARD checking this for 10210
08-12 21:57:14.429  6493  6493 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:14.429  6493  6493 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:14.429  6493  6493 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 21:57:14.429  6493  6493 E Zygote  : accessInfo : 0
,08-12 21:57:14.439  6493  6493 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,08-12 21:57:14.439   753   822 I ActivityManager: Start proc 6493:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
,08-12 21:57:14.449   292   292 I SurfaceFlinger: id=21 createSurf (145x145),1 flag=4, VSBConnecti
,08-12 21:57:14.469  3681  6480 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 21:57:14.469  3681  6480 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 21:57:14.469  3681  6480 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 21:57:14.469  3681  6480 I Adreno-EGL: Local Branch: ss
08-12 21:57:14.469  3681  6480 I Adreno-EGL: Remote Branch: 
08-12 21:57:14.469  3681  6480 I Adreno-EGL: Local Patches: 
08-12 21:57:14.469  3681  6480 I Adreno-EGL: Reconstruct Branch: 
,08-12 21:57:14.479  3681  6480 D libEGL  : eglInitialize EGLDisplay = 0x9f0357c4
,08-12 21:57:14.479  3681  6480 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 21:57:14.479  6493  6493 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 21:57:14.479  6493  6493 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:14.489  6482  6482 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 21:57:14.499  6482  6482 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:14.499  6493  6493 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,08-12 21:57:14.509   753  2227 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4c8f908 6482:com.samsung.android.sm.devicesecurity/5012}
,08-12 21:57:14.549   292   292 I SurfaceFlinger: id=22 createSurf (193x193),1 flag=4, VSBConnecti
,08-12 21:57:14.559  6493  6493 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,08-12 21:57:14.559  6482  6482 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
,08-12 21:57:14.569  1826  6479 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-12 21:57:14.589  3681  3681 V ActivityThread: updateVisibility : ActivityRecord{a6658ea token=android.os.BinderProxy@549cff4 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-12 21:57:14.589  3681  3681 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-12 21:57:14.599  6482  6482 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
,08-12 21:57:14.609  1826  6479 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-12 21:57:14.619  6493  6493 D AASAservice: onCreate()
,08-12 21:57:14.639   753  1625 I ActivityManager: Killing 5162:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-12 21:57:14.639  5395  5395 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,08-12 21:57:14.679   753  1741 I ActivityManager: Killing 5148:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-12 21:57:14.699   753   767 V WindowStateAnimator: Finishing drawing window Window{2883f25 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-12 21:57:14.699   753  1741 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{432be00 3196:com.android.contacts/u0a19}
,08-12 21:57:14.699  3681  3681 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-12 21:57:14.699   753  2219 V WindowStateAnimator: Finishing drawing window Window{3243eab u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-12 21:57:14.699  3681  3681 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-12 21:57:14.699  3681  3681 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-12 21:57:14.709   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbebec364
,08-12 21:57:14.709   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbebec364
,08-12 21:57:14.719   753  1625 V WindowStateAnimator: Finishing drawing window Window{2883f25 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-12 21:57:14.719   753  1798 V WindowStateAnimator: Finishing drawing window Window{3243eab u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-12 21:57:14.719  3681  3681 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@549cff4 time:107662
,08-12 21:57:14.719   753  1409 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-12 21:57:14.729   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbebec364
,08-12 21:57:14.739   753   767 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
,08-12 21:57:14.749   753   765 I ActivityManager: Start proc 6511:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
,08-12 21:57:14.749  6511  6511 E Zygote  : v2
,08-12 21:57:14.749  6511  6511 I libpersona: KNOX_SDCARD checking this for 10049
08-12 21:57:14.749  6511  6511 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:14.749  6511  6511 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 21:57:14.749  6511  6511 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 21:57:14.749   753   877 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 21:57:14.749  6511  6511 E Zygote  : accessInfo : 0
08-12 21:57:14.749   753   753 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 21:57:14.749  6511  6511 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-12 21:57:14.749   753   877 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +484ms (total +502ms)
,08-12 21:57:14.749   753   877 D ActivityManager: mDVFSHelper.release()
08-12 21:57:14.749   753   753 I KnoxTimeoutHandler: SD activityfalse
08-12 21:57:14.749   753   877 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{39c1131 u0 com.samsung.android.MtpApplication/.USBConnection t168} time:107698
,08-12 21:57:14.759   753  1742 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-12 21:57:14.789  6511  6511 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 21:57:14.789  6511  6511 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:14.819   753  1218 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{11b0d52 6511:com.android.mms/u0a49}
,08-12 21:57:14.839  6511  6511 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-12 21:57:14.849  4036  6523 W IcingInternalCorpora: getNumBytesRead when not calculated.
,08-12 21:57:14.879  1826  6479 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 492 ms] updated apps [took 492 ms] 
,08-12 21:57:14.889  6511  6511 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-12 21:57:14.899  6511  6511 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,08-12 21:57:14.939  6511  6511 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-12 21:57:14.939  6511  6524 D Mms/ArtClassLoader: init before art first
,08-12 21:57:14.949  6511  6525 D Mms/ArtClassLoader: init before art second
,08-12 21:57:14.949  6511  6511 D Mms/TelephonyPermission: start operation mode monitor
,08-12 21:57:14.949  6511  6526 D Mms/ArtClassLoader: init before art third
,08-12 21:57:14.949  6511  6511 D Mms/TelephonyPermission: User ID is null set current User Id
,08-12 21:57:14.959  6511  6526 D Mms/ArtClassLoader: init [DONE] art
,08-12 21:57:14.979  6511  6511 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-12 21:57:14.979  6511  6511 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-12 21:57:14.989  6511  6511 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-12 21:57:14.989  6511  6511 D Mms/TelephonyPermission: isDefault true
,08-12 21:57:14.989  6511  6511 D Mms/MmsApp: onCreate() com.android.mms
,08-12 21:57:15.019  6511  6511 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-12 21:57:15.029  6511  6511 D Mms/MmsApp: [start]    initCountryIso consume time = 89.8975
,08-12 21:57:15.029   753   767 D CountryDetector: The first listener is added
,08-12 21:57:15.039  6336  6439 W jxcore-log: Initializing JXcore engine
08-12 21:57:15.039  6336  6439 W jxcore-log: JXcore engine is ready
,08-12 21:57:15.039  6511  6511 D Mms/MmsApp: [end]    initCountryIso consume time = 8.358907
08-12 21:57:15.039  6511  6511 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.1025
,08-12 21:57:15.039  6511  6524 D Mms/ArtClassLoader: init [DONE] art
,08-12 21:57:15.049  6511  6511 D Mms/MmsConfig: before partial update
,08-12 21:57:15.079  2112  2112 E audit   : type=1400 msg=audit(1471031835.079:288): avc:  denied  { ioctl } for  pid=6439 comm="Thread-884" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 21:57:15.079  2112  2112 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-12 21:57:15.079  2112  2112 E audit   : type=1300 msg=audit(1471031835.079:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9991a3c8 items=0 ppid=350 ppcomm=main pid=6439 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-884" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-12 21:57:15.079  2112  2112 E audit   : type=1327 msg=audit(1471031835.079:288): proctitle="com.test.thalitest"
08-12 21:57:15.079  2112  2112 E audit   : type=1320 msg=audit(1471031835.079:288): 
,08-12 21:57:15.079  2112  2112 E audit   : type=1400 msg=audit(1471031835.079:289): avc:  denied  { ioctl } for  pid=6439 comm="Thread-884" path="socket:[36728]" dev="sockfs" ino=36728 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-12 21:57:15.079  2112  2112 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 21:57:15.079  2112  2112 E audit   : type=1300 msg=audit(1471031835.079:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3b a1=5451 a2=3 a3=9991a3c8 items=0 ppid=350 ppcomm=main pid=6439 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-884" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-12 21:57:15.079  2112  2112 E audit   : type=1327 msg=audit(1471031835.079:289): proctitle="com.test.thalitest"
08-12 21:57:15.079  2112  2112 E audit   : type=1320 msg=audit(1471031835.079:289): 
,08-12 21:57:15.089  6511  6525 D Mms/ArtClassLoader: init [DONE] art
08-12 21:57:15.089  6511  6511 D Mms/MmsConfig: Load Resize quality : 80
,08-12 21:57:15.089  6511  6511 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
,08-12 21:57:15.089  6511  6511 D EasySignUpManager_1.0.5: isAuth is false
08-12 21:57:15.089  6511  6511 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-12 21:57:15.089  6511  6511 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-12 21:57:15.089  6511  6511 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-12 21:57:15.089  6336  6439 W jxcore-log: Starting JXcore engine
08-12 21:57:15.099  6511  6511 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-12 21:57:15.099  6511  6511 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-12 21:57:15.099  6511  6511 D EasySignUpManager_1.0.5: isAuth is false
08-12 21:57:15.099  6511  6511 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-12 21:57:15.099  6511  6511 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-12 21:57:15.099  6511  6511 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-12 21:57:15.099  1711  1905 D TP/MmsSmsProvider: query, match:2117, calling pid = 6511, accessRestricted = false
,08-12 21:57:15.109  1711  1905 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 2.173 ms
,08-12 21:57:15.109  6511  6511 E CscParser: mps_code.dat does not exist
,08-12 21:57:15.109  6511  6511 E CscParser: customer_path =/system/csc/customer.xml
08-12 21:57:15.109  6511  6511 E CscParser: fileName + /system/csc/customer.xml
,08-12 21:57:15.119  6511  6511 E CscParser: mps_code.dat does not exist
,08-12 21:57:15.119  6511  6511 E CscParser: customer_path =/system/csc/customer.xml
08-12 21:57:15.119  6511  6511 E CscParser: fileName + /system/csc/customer.xml
,08-12 21:57:15.129  6511  6511 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-12 21:57:15.129  6511  6511 D Mms/MmsConfig:  enable multiwindow = true
,08-12 21:57:15.129  6511  6511 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-12 21:57:15.129  6511  6511 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
,08-12 21:57:15.129  6511  6511 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-12 21:57:15.129  6511  6511 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
,08-12 21:57:15.129  6511  6511 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
,08-12 21:57:15.129  6511  6511 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-12 21:57:15.129  6511  6511 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-12 21:57:15.139  6511  6511 D Mms/MmsConfig: [end]    init() consume time = 100.838125
,08-12 21:57:15.139  6511  6511 D Mms/Contact: [start]    init() consume time = 4.456093
,08-12 21:57:15.149  6511  6511 D Mms/Contact: [end]    init consume time = 9.791302
,08-12 21:57:15.159  6511  6532 D Mms/DraftCache: [start]    rebuildCache consume time = 5.266407
,08-12 21:57:15.159  1711  1730 D TP/MmsSmsProvider: query, match:13, calling pid = 6511, accessRestricted = false
,08-12 21:57:15.159  6511  6511 D Mms:transaction: roaming -> false (slotId = 0)
08-12 21:57:15.159  6511  6511 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-12 21:57:15.159  6511  6511 D Mms:transaction: auto download without roaming -> true
08-12 21:57:15.159  6511  6511 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,08-12 21:57:15.159  6511  6511 D Mms:transaction: roaming -> false (slotId = 1)
08-12 21:57:15.169  6511  6511 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
,08-12 21:57:15.169  6511  6511 D Mms:transaction: auto download without roaming -> true
,08-12 21:57:15.169  6511  6511 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-12 21:57:15.169  6511  6511 D Mms:transaction: auto download during roaming secondary -> false
08-12 21:57:15.169  1711  1730 D TP/MmsSmsProvider: query, match 13:Elapsed time : 3.727 ms
08-12 21:57:15.169  6511  6511 D Mms:transaction: mAutoDownload ------> true
,08-12 21:57:15.169  1711  1906 D TP/MmsSmsProvider: query, match:12, calling pid = 6511, accessRestricted = false
,08-12 21:57:15.169  1711  1906 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.730 ms
,08-12 21:57:15.169  6511  6532 D Mms/DraftCache: [end]    rebuildCache consume time = 16.119895
,08-12 21:57:15.179  6336  6439 W jxcore-log: Platform android
08-12 21:57:15.179  6336  6439 W jxcore-log: 
08-12 21:57:15.179  6336  6439 W jxcore-log: Process ARCH arm
08-12 21:57:15.179  6336  6439 W jxcore-log: 
,08-12 21:57:15.189  6511  6511 D ComposerPerformance: 1471031835203 ms / [DONE] Composer constructor
,08-12 21:57:15.189  6511  6511 D CII     : Log Level [5]
08-12 21:57:15.189  6511  6511 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-12 21:57:15.189  6511  6511 I Mms/ReservationManager: ReservationManager()
08-12 21:57:15.189  6511  6511 I Mms/ReservationManager: resetAfterConnected()
,08-12 21:57:15.189  6511  6534 D Mms/Conversation: [start]    init() consume time = 18.674792
,08-12 21:57:15.199  1711  1737 D TP/MmsSmsProvider: delete, match:1, calling pid = 6511
,08-12 21:57:15.199  1711  1737 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-12 21:57:15.199  1711  1737 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-12 21:57:15.199  1711  1737 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-12 21:57:15.199  1711  1737 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,08-12 21:57:15.199  1711  1737 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-12 21:57:15.199  1711  1730 D TP/MmsSmsProvider: query, match:7, calling pid = 6511, accessRestricted = false
,08-12 21:57:15.209  1711  1730 D TP/MmsSmsProvider: query, match 7:Elapsed time : 2.210 ms
,08-12 21:57:15.209  1711  1737 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-12 21:57:15.219  1711  1737 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
,08-12 21:57:15.219  1711  1737 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-12 21:57:15.219  1711  1737 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-12 21:57:15.219  6511  6511 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-12 21:57:15.219  1711  1737 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 12.800 ms
08-12 21:57:15.219  1711  1737 D TP/MmsSmsProvider: need read changed broadcast:false
08-12 21:57:15.219  6511  6534 D Mms/Conversation: [end]    init consume time = 25.89474
,08-12 21:57:15.219  6511  6534 D Mms/MessagingNotification: [start]    init() consume time = 2.149166
,08-12 21:57:15.219  6511  6511 D Mms/MmsApp: [end]    onCreate() consume time = 1.642917
,08-12 21:57:15.219  6511  6511 D Mms/MmsApp: [end]    onCreate() consume time = 0.455052
,08-12 21:57:15.219  6511  6534 D Mms/MessagingNotification: [end]    init consume time = 0.954844
,08-12 21:57:15.229  6511  6536 D Mms/Synchronizer: [start]    doSync consume time = 5.260521
08-12 21:57:15.229  6511  6511 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-12 21:57:15.229  1711  1906 D TP/MmsSmsProvider: query, match:0, calling pid = 6511, accessRestricted = false
08-12 21:57:15.229  1711  1906 V TP/MmsSmsProvider: getSimpleConversations entered.
08-12 21:57:15.229  1711  1906 D TP/MmsSmsProvider: query, match 0:Elapsed time : 1.169 ms
08-12 21:57:15.229  6511  6511 D Mms:transaction: roaming ------> false, mSimSlot = 0
08-12 21:57:15.229  6511  6511 D Mms:transaction: roaming -> false (slotId = 0)
08-12 21:57:15.229  6511  6511 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-12 21:57:15.239  6511  6511 D Mms:transaction: auto download without roaming -> true
08-12 21:57:15.239  6511  6511 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-12 21:57:15.239  6511  6511 D Mms:transaction: mAutoDownload ------> true
08-12 21:57:15.239  6511  6535 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 7.460573
08-12 21:57:15.239  6537  6537 E Zygote  : v2
08-12 21:57:15.239  6537  6537 I libpersona: KNOX_SDCARD checking this for 1000
08-12 21:57:15.239  6537  6537 I libpersona: KNOX_SDCARD not a persona
08-12 21:57:15.249  6537  6537 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:15.249  6537  6537 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 21:57:15.249   753  1620 I ActivityManager: Start proc 6537:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
08-12 21:57:15.249  6537  6537 E Zygote  : accessInfo : 0
08-12 21:57:15.259  1711  1737 D TP/MmsSmsProvider: update, match:300, calling pid = 6511
08-12 21:57:15.259  1711  1737 V TP/MmsSmsProvider: syncDBData start
08-12 21:57:15.259  1711  1737 V TP/MmsSmsProvider: syncDBData sms end
08-12 21:57:15.259  1711  1737 V TP/MmsSmsProvider: syncDBData mms end
08-12 21:57:15.259  1711  1737 V TP/MmsSmsProvider: syncDBData end
08-12 21:57:15.259  1711  1737 D TP/MmsSmsProvider: update, match 300:Elapsed time : 5.377 ms
08-12 21:57:15.259  1711  1905 D TP/MmsSmsProvider: query, match:400, calling pid = 6511, accessRestricted = false
,08-12 21:57:15.269  6511  6535 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 36.161093
,08-12 21:57:15.269   753  3417 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-12 21:57:15.279  6511  6536 D Mms/Synchronizer: [end]    doSync consume time = 5.643126
,08-12 21:57:15.279  6017  6029 D BadgeProvider: query, [selection] : package=?
,08-12 21:57:15.289  6537  6537 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 21:57:15.289  6537  6537 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:15.299   753  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6b9d250 6537:com.samsung.android.bbc.bbcagent/1000}
,08-12 21:57:15.299  6511  6534 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-12 21:57:15.309  1711  1906 D TP/SmsProvider: query,matched:26, calling pid = 6511
,08-12 21:57:15.309  1711  1906 D TP/SmsProvider: query, match 26:Elapsed time : 1.212 ms
,08-12 21:57:15.319  1711  1905 D TP/MmsSmsProvider: query, match:6, calling pid = 6511, accessRestricted = false
,08-12 21:57:15.329  1711  1905 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.337 ms
,08-12 21:57:15.359   753  2227 I ActivityManager: Start proc 6549:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
08-12 21:57:15.359  6549  6549 E Zygote  : v2
08-12 21:57:15.359  6549  6549 I libpersona: KNOX_SDCARD checking this for 10024
08-12 21:57:15.359  6549  6549 I libpersona: KNOX_SDCARD not a persona
08-12 21:57:15.359  6549  6549 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:15.359  6549  6549 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 21:57:15.359  6549  6549 E Zygote  : accessInfo : 0
08-12 21:57:15.359  6549  6549 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-12 21:57:15.379  6537  6537 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-12 21:57:15.389  6549  6549 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 21:57:15.389  6549  6549 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:15.399   753   765 I ActivityManager: Killing 5201:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-12 21:57:15.409   753   763 I art     : Background partial concurrent mark sweep GC freed 169861(10MB) AllocSpace objects, 7(2MB) LOS objects, 27% free, 42MB/58MB, paused 1.712ms total 140.242ms
,08-12 21:57:15.419  1447  1447 D Recents : onTaskStackChanged
,08-12 21:57:15.419  6549  6549 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-12 21:57:15.429  6537  6537 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-12 21:57:15.449   753  1745 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-12 21:57:15.449  6336  6439 I jxcore-log: JXcore Cordova bridge is ready!
08-12 21:57:15.449  6336  6439 I jxcore-log: 
,08-12 21:57:15.449  6336  6439 W jxcore-log: JXcore engine is started
,08-12 21:57:15.459  6336  6438 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 21:57:15.459  6336  6336 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 21:57:15.469  6549  6549 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-12 21:57:15.479  6561  6561 E Zygote  : v2
08-12 21:57:15.479  6561  6561 I libpersona: KNOX_SDCARD checking this for 10097
08-12 21:57:15.479  6561  6561 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:15.479   753  1741 I ActivityManager: Start proc 6561:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-12 21:57:15.479  6561  6561 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:15.479  6561  6561 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 21:57:15.479   753  1741 I ActivityManager: Killing 4670:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-12 21:57:15.479  6561  6561 E Zygote  : accessInfo : 0
08-12 21:57:15.479  6561  6561 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-12 21:57:15.509  6549  6549 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-12 21:57:15.519  6561  6561 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 21:57:15.519  6561  6561 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:15.519   753  1409 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5131c49 6561:com.google.android.apps.docs/u0a97}
,08-12 21:57:15.529  6511  6534 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-12 21:57:15.529  6561  6561 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 21:57:15.559   753  2125 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-12 21:57:15.569  6549  6549 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-12 21:57:15.579  6549  6549 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-12 21:57:15.579   753  1362 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/167_task.xml.bak
,08-12 21:57:15.579  6549  6549 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-12 21:57:15.579  6561  6561 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-12 21:57:15.589  6549  6549 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-12 21:57:15.589  6549  6549 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-12 21:57:15.589  6549  6549 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-12 21:57:15.589  6549  6549 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-12 21:57:15.599  6549  6549 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-12 21:57:15.599  6549  6549 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-12 21:57:15.599  6549  6549 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-12 21:57:15.599  6549  6549 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-12 21:57:15.599  6549  6549 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-12 21:57:15.609  6549  6549 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-12 21:57:15.879  6561  6575 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-12 21:57:15.879  6561  6575 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-12 21:57:15.879  6561  6575 I GAv4    :   adb logcat -s GAv4
,08-12 21:57:15.889  4036  5012 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-12 21:57:15.889  6561  6575 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 21:57:15.899   753  2227 V AlarmManager:  remove PendingIntent] PendingIntent{f683405: PendingIntentRecord{15dc5a com.google.android.apps.docs broadcastIntent}}
,08-12 21:57:15.899  6561  6575 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-12 21:57:15.899  6561  6575 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-12 21:57:15.939  6561  6581 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-12 21:57:15.959  4036  5012 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-12 21:57:16.029  6561  6561 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-12 21:57:16.029  6561  6561 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-12 21:57:16.069  6561  6575 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
08-12 21:57:16.069  6561  6575 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-12 21:57:16.069  6561  6575 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
,08-12 21:57:16.069  6561  6575 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-12 21:57:16.099  4036  5012 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-12 21:57:16.119   753  2227 I ActivityManager: Start proc 6587:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,08-12 21:57:16.119  6587  6587 E Zygote  : v2
08-12 21:57:16.119  6587  6587 I libpersona: KNOX_SDCARD checking this for 10098
08-12 21:57:16.119  6587  6587 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:16.119  6587  6587 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:16.119  6587  6587 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 21:57:16.119  6587  6587 E Zygote  : accessInfo : 0
,08-12 21:57:16.119  6587  6587 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-12 21:57:16.119   753  2227 I ActivityManager: Killing 5500:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
,08-12 21:57:16.169  6587  6587 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 21:57:16.169  6587  6587 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:16.169   753  1798 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
,08-12 21:57:16.189   753  1741 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6456426 6587:com.sec.android.automotive.drivelink/u0a98}
,08-12 21:57:16.219  6587  6587 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-12 21:57:16.229  6587  6587 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-12 21:57:16.249  2103  2103 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 21:57:16.249  2103  2103 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 21:57:16.279  6587  6587 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-12 21:57:16.279  2103  2103 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 21:57:16.289   753  2228 V AlarmManager:  remove PendingIntent] PendingIntent{d1ad1fe: PendingIntentRecord{8dafd5f com.sec.android.automotive.drivelink broadcastIntent}}
,08-12 21:57:16.289  6587  6603 I GMPM    : App measurement is starting up
,08-12 21:57:16.309  6587  6603 E GMPM    : getGoogleAppId failed with status: 10
,08-12 21:57:16.309  6587  6603 E GMPM    : Uploading is not possible. App measurement disabled
,08-12 21:57:16.309  6587  6587 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-12 21:57:16.309   753  1799 V AlarmManager:  remove PendingIntent] PendingIntent{4eb03ac: PendingIntentRecord{8dafd5f com.sec.android.automotive.drivelink broadcastIntent}}
,08-12 21:57:16.329  6561  6576 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 21:57:16.339  6587  6587 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-12 21:57:16.349  6587  6587 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-12 21:57:16.399  6561  6576 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
08-12 21:57:16.399  6609  6609 I libpersona: KNOX_SDCARD checking this for 10032
08-12 21:57:16.399  6609  6609 E Zygote  : v2
08-12 21:57:16.399  6609  6609 I libpersona: KNOX_SDCARD not a persona
08-12 21:57:16.399  6609  6609 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:16.399  6609  6609 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 21:57:16.399  6609  6609 E Zygote  : accessInfo : 0
08-12 21:57:16.399  6609  6609 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-12 21:57:16.399   753  1218 I ActivityManager: Start proc 6609:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-12 21:57:16.399   753  1318 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-12 21:57:16.429  6561  6576 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-12 21:57:16.429  6561  6576 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-12 21:57:16.429  6561  6576 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-12 21:57:16.429  6609  6609 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 21:57:16.429  6609  6609 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:16.439   753  1318 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-12 21:57:16.449  6609  6609 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-12 21:57:16.459  6561  6576 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-12 21:57:16.459  6609  6609 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-12 21:57:16.549  6587  6587 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-12 21:57:16.549  6587  6587 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-12 21:57:16.559  6587  6587 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-12 21:57:16.569  6609  6609 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-12 21:57:16.579  6587  6587 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDFri Aug 12 21:57:16 GMT+02:00 2016
,08-12 21:57:16.589   753  1235 V AlarmManager: Expired Alarm result :4
,08-12 21:57:16.589  6623  6623 E Zygote  : v2
08-12 21:57:16.589  6623  6623 I libpersona: KNOX_SDCARD checking this for 1000
08-12 21:57:16.589  6623  6623 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:16.589  6623  6623 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:16.589  6623  6623 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 21:57:16.589   753  1440 I ActivityManager: Start proc 6623:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-12 21:57:16.589  6623  6623 E Zygote  : accessInfo : 0
,08-12 21:57:16.589   753  1440 I ActivityManager: Killing 5672:com.sec.android.app.shealth/u0a34 (adj 15): DHA:empty #37
,08-12 21:57:16.589   753  1440 I ActivityManager: Killing 4776:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-12 21:57:16.619  6623  6623 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 21:57:16.619  6623  6623 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:16.619  6587  6587 D DialogFlow: initQueue()
,08-12 21:57:16.629   753  2125 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5ded6f1 6623:com.samsung.android.app.filterinstaller/1000}
,08-12 21:57:16.629  6623  6623 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-12 21:57:16.649  6623  6623 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-12 21:57:16.649   753  1625 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,08-12 21:57:16.659  6623  6623 E FilterPackageIntentReceiver: This package is not a effect filter
,08-12 21:57:16.659   753  2227 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-12 21:57:16.669   753   767 I ActivityManager: Start proc 6636:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
,08-12 21:57:16.679  6636  6636 E Zygote  : v2
08-12 21:57:16.679  6636  6636 I libpersona: KNOX_SDCARD checking this for 1000
08-12 21:57:16.679  6636  6636 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:16.679  6636  6636 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:16.679  6636  6636 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 21:57:16.679  6636  6636 E Zygote  : accessInfo : 0
,08-12 21:57:16.679   753   767 I ActivityManager: Killing 5097:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-12 21:57:16.699  6636  6636 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 21:57:16.699  6636  6636 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:16.709   753  6253 I HarmonyEASService: Updating for all 1
,08-12 21:57:16.709   753  1798 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e78f12d 6636:com.samsung.helphub/1000}
,08-12 21:57:16.709  6609  6609 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-12 21:57:16.719  6636  6636 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-12 21:57:16.719   753  1620 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-12 21:57:16.729   753  3416 D SSRM:n  : SIOP:: AP = 480, PST = 446, CUR = 450, LCD = 0
,08-12 21:57:16.739  6636  6636 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-12 21:57:16.759   753  1620 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-12 21:57:16.789  6651  6651 E Zygote  : v2
,08-12 21:57:16.789  6651  6651 I libpersona: KNOX_SDCARD checking this for 1000
08-12 21:57:16.789  6651  6651 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:16.789   753  1799 I ActivityManager: Start proc 6651:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
08-12 21:57:16.789  6651  6651 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 21:57:16.789  6651  6651 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 21:57:16.789   753  1799 I ActivityManager: Killing 5535:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-12 21:57:16.789  6651  6651 E Zygote  : accessInfo : 0
,08-12 21:57:16.809   753  1798 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-12 21:57:16.809  6609  6609 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-12 21:57:16.809  6609  6609 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-12 21:57:16.819  6609  6609 D DialogFlow: initQueue()
,08-12 21:57:16.819  6651  6651 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 21:57:16.819  6651  6651 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:16.829   753  2125 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8cafdc 6651:com.samsung.android.app.mirrorlink/1000}
,08-12 21:57:16.829  6651  6651 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-12 21:57:16.849  6651  6651 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-12 21:57:16.879  6651  6651 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-12 21:57:16.879  6651  6651 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-12 21:57:16.879   753  1440 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e938da 5560:com.google.android.apps.plus/u0a134}
,08-12 21:57:16.889   753  1745 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e938da 5560:com.google.android.apps.plus/u0a134}
,08-12 21:57:16.909   753  2228 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e938da 5560:com.google.android.apps.plus/u0a134}
,08-12 21:57:16.949   753  2227 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-12 21:57:16.959   753   767 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-12 21:57:16.959   753  1742 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-12 21:57:16.959   753  2228 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-12 21:57:16.959   753  1409 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-12 21:57:16.969   753  1798 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-12 21:57:16.969   753  1625 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-12 21:57:16.969   753  1218 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-12 21:57:16.979  6665  6665 E Zygote  : v2
08-12 21:57:16.979  6665  6665 I libpersona: KNOX_SDCARD checking this for 10165
08-12 21:57:16.979  6665  6665 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:16.979  6665  6665 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 21:57:16.979  6665  6665 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 21:57:16.979   753  2125 I ActivityManager: Start proc 6665:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,08-12 21:57:16.979  6665  6665 E Zygote  : accessInfo : 0
,08-12 21:57:16.979  6665  6665 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-12 21:57:16.989   753   767 I ActivityManager: Killing 5380:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-12 21:57:17.009   753  1742 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-12 21:57:17.009  6665  6665 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 21:57:17.009  6665  6665 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:17.019   753  1625 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c0e0e6b 6665:com.sec.kidsplat.installer/u0a165}
,08-12 21:57:17.029  6665  6665 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-12 21:57:17.039  6665  6665 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-12 21:57:17.049   753   767 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c0e0e6b 6665:com.sec.kidsplat.installer/u0a165}
,08-12 21:57:17.049  6665  6665 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-12 21:57:17.069  6677  6677 E Zygote  : v2
08-12 21:57:17.069  6677  6677 I libpersona: KNOX_SDCARD checking this for 10142
08-12 21:57:17.069  6677  6677 E Zygote  : isSdpEnabledProcess - SDP enabled
08-12 21:57:17.069  6677  6677 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:17.069  6677  6677 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:17.069  6677  6677 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 21:57:17.069   753   765 I ActivityManager: Start proc 6677:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-12 21:57:17.069  6677  6677 E Zygote  : accessInfo : 64
08-12 21:57:17.069  6677  6677 E Zygote  : isSdpEnabledProcess - SDP enabled
08-12 21:57:17.069  6677  6677 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
,08-12 21:57:17.069  6677  6677 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-12 21:57:17.069   753   765 I ActivityManager: Killing 5712:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-12 21:57:17.089   753  1440 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-12 21:57:17.089  6677  6677 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 21:57:17.089  6677  6677 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:17.099   753  1218 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c22edc8 6677:com.sec.android.app.sbrowser/u0a142}
,08-12 21:57:17.099  6677  6677 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-12 21:57:17.119  6677  6677 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-12 21:57:17.189  6677  6677 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-12 21:57:17.189  6677  6677 D ManifestProvider: onCreate()
,08-12 21:57:17.209  6677  6677 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-12 21:57:17.209  6677  6677 I SBrowserUtils: getSystemProperty of country_code : Poland
,08-12 21:57:17.209  6677  6677 I SBrowserUtils: getSystemProperty of country_code : Poland
08-12 21:57:17.209  6677  6677 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-12 21:57:17.209  6677  6677 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-12 21:57:17.219  6677  6677 D [MM]MHDataBaseProvider: onCreate()
,08-12 21:57:17.229  6677  6677 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@532b7d3)
,08-12 21:57:17.249   753  1218 I ActivityManager: Killing 5395:com.policydm/1000 (adj 15): DHA:empty #37
,08-12 21:57:17.249   753  1218 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f424bcb 2103:com.google.android.gms.persistent/u0a11}
,08-12 21:57:17.259  6511  6511 I Mms/MmsApp:  start initViewCache mms
,08-12 21:57:17.269  4036  6692 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 21:57:17.269   753  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7055538 4036:com.google.android.gms/u0a11}
,08-12 21:57:17.269  4036  6691 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-12 21:57:17.279  4036  6692 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 21:57:17.299   753  2228 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-12 21:57:17.299  6493  6493 D AASAservice: onDestroy()
,08-12 21:57:17.309  4036  4036 D AsyncTaskServiceImpl: Submit a task: nzm
,08-12 21:57:17.309  4036  6692 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 21:57:17.309  6493  6493 I art     : System.exit called, status: 80
08-12 21:57:17.309  6493  6493 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-12 21:57:17.319  4036  6692 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 21:57:17.319   753  2219 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f424bcb 2103:com.google.android.gms.persistent/u0a11}
,08-12 21:57:17.329   753  3454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 21:57:17.339   753  1799 I ActivityManager: Process com.samsung.aasaservice (pid 6493)(adj 0) has died(58,731)
,08-12 21:57:17.339   753  1799 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-12 21:57:17.349  4036  5014 D nzm     : Processing package: com.test.thalitest
,08-12 21:57:17.359   753  1741 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7055538 4036:com.google.android.gms/u0a11}
,08-12 21:57:17.369  4036  4036 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 21:57:17.379   350   350 I Zygote  : Process 6493 exited cleanly (80)
,08-12 21:57:17.389  4036  5014 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
08-12 21:57:17.389  4036  5014 D nzm     : Found info for package com.test.thalitest in db.
,08-12 21:57:17.469   753  2227 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bd4947c 4865:com.android.vending/u0a29}
,08-12 21:57:17.539   753   767 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5835f50 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{68b100b 6064:com.sec.android.app.samsungapps/u0a39}
,08-12 21:57:17.549  4865  4865 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-12 21:57:17.549  2103  2103 D WearableService: callingUid 10011, callindPid: 2103
,08-12 21:57:17.569  4865  4865 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-12 21:57:17.579  4865  4865 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-12 21:57:17.579  4865  4865 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-12 21:57:17.589  6700  6700 E Zygote  : v2
08-12 21:57:17.589  6700  6700 I libpersona: KNOX_SDCARD checking this for 10034
08-12 21:57:17.589  6700  6700 I libpersona: KNOX_SDCARD not a persona
08-12 21:57:17.589  6700  6700 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:17.589  6700  6700 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 21:57:17.589   753   753 I ActivityManager: Start proc 6700:com.sec.android.app.shealth/u0a34 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
08-12 21:57:17.589  6700  6700 E Zygote  : accessInfo : 0
08-12 21:57:17.589  6700  6700 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
,08-12 21:57:17.609  6511  6511 D Mms/BubbleViewCache: fillCache bubble = 4
,08-12 21:57:17.609   753   753 I BackgroundCompactionService: onStart. jobID=801
,08-12 21:57:17.609   753   753 I BackgroundCompactionService: onStart done. jobID=801
,08-12 21:57:17.619  6700  6700 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 21:57:17.619  6700  6700 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:17.619   753  6712 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,08-12 21:57:17.619   753  6712 I BackgroundCompactionService: compact_memory command done
,08-12 21:57:17.629   753  1440 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7324f10 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ae2ba09 6700:com.sec.android.app.shealth/u0a34}
,08-12 21:57:17.659  6700  6700 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-12 21:57:17.759  6700  6700 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-12 21:57:17.779  6700  6700 I MultiDex: VM with version 2.1.0 has multidex support
,08-12 21:57:17.779  6700  6700 I MultiDex: install
,08-12 21:57:17.779  6700  6700 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 21:57:17.779  6700  6700 I MultiDex: install
08-12 21:57:17.779  6700  6700 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 21:57:17.879  6609  6650 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 21:57:17.879  6609  6650 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 21:57:17.899  6700  6700 D HealthDataStore: Service for HealthDataStore is connected
,08-12 21:57:17.899  6700  6700 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-12 21:57:17.899   753  2219 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7324f10 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5ee10bc 1884:com.sec.android.app.shealth:remote/u0a34}
,08-12 21:57:17.909  6700  6700 D HealthConsole: Service for HealthDataConsole is connected
,08-12 21:57:17.919  6700  6700 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-12 21:57:17.919  6700  6700 E HealthDataStore: disconnectService: Context instance is invalid
,08-12 21:57:17.929   753  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7324f10 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5ee10bc 1884:com.sec.android.app.shealth:remote/u0a34}
,08-12 21:57:17.929  6609  6650 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 21:57:17.929  6609  6650 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-12 21:57:17.929  6609  6650 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-12 21:57:17.939   753  1318 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-12 21:57:17.939   753  1318 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-12 21:57:17.939   753  1745 V AlarmManager:  remove PendingIntent] PendingIntent{950e6d4: PendingIntentRecord{410af70 com.google.android.gms broadcastIntent}}
,08-12 21:57:17.949   753  1409 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9bf107d u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f424bcb 2103:com.google.android.gms.persistent/u0a11}
,08-12 21:57:17.949  6609  6650 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 21:57:17.949  6609  6650 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 21:57:18.569  4036  5094 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
08-12 21:57:18.629  4036  5094 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
08-12 21:57:18.639  4036  5094 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
08-12 21:57:18.639  4036  5094 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-12 21:57:20.299   753  3416 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 21:57:21.479   753  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:57:21.479   753  1218 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4345, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 21:57:21.479   753  1218 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-12 21:57:21.479   753  1218 D BatteryService: stay LED for charging
08-12 21:57:21.479   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 21:57:21.489   753   753 I MotionRecognitionService: Plugged
,08-12 21:57:21.489   753   753 D MotionRecognitionService:   cableConnection= 1
,08-12 21:57:21.489   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 21:57:21.489   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 21:57:21.489  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:57:21.489  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 21:57:21.489  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 21:57:21.499  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 21:57:21.499  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 21:57:21.509  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 21:57:21.509  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 21:57:21.509  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 21:57:22.529   753   917 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-12 21:57:22.569   753   917 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-12 21:57:24.209   753   917 D PackageManager: [MSG] MCS_UNBIND
,08-12 21:57:24.219   753  1742 I ActivityManager: Killing 5824:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-12 21:57:24.269   753  2228 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-12 21:57:26.769   753  3416 D SSRM:n  : SIOP:: AP = 460, PST = 447, CUR = 450, LCD = 0
,08-12 21:57:27.879   753  1583 E Watchdog: !@Sync 3 [08-12 21:57:27.892]
,08-12 21:57:27.969   753  1318 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-12 21:57:27.969   753  1318 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-12 21:57:29.919   753  1218 I ActivityManager: Killing 5847:com.sec.android.cloudagent/u0a2 (adj 15): DHA:empty #37
,08-12 21:57:29.949   753  2227 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.cloudagent, Auto Run ON
,08-12 21:57:32.479   753  1235 V AlarmManager: Expired Alarm result :4
,08-12 21:57:32.489   753   822 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{83f9c40 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f424bcb 2103:com.google.android.gms.persistent/u0a11}
,08-12 21:57:32.509  6336  6439 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 21:57:32.509  6336  6439 I jxcore-log: 
,08-12 21:57:32.519  6336  6439 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 21:57:32.519  6336  6439 I jxcore-log: 
,08-12 21:57:32.519  6336  6439 D BluetoothAdapter: STATE_ON
,08-12 21:57:32.529  6336  6439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 21:57:32.529  6336  6439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 21:57:32.529  6336  6439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 21:57:32.529  6336  6439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 21:57:32.529  6336  6439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 21:57:32.529  6336  6439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 21:57:32.529  6336  6439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 21:57:32.529  6336  6439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 21:57:32.529   753  1620 V AlarmManager:  remove PendingIntent] PendingIntent{a71acbe: PendingIntentRecord{74ab34d com.google.android.gms broadcastIntent}}
,08-12 21:57:32.529  6336  6439 D BluetoothAdapter: STATE_ON
,08-12 21:57:32.529  6336  6439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 21:57:32.529  6336  6439 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 21:57:32.529  6336  6439 I jxcore-log: 
,08-12 21:57:32.529  6336  6439 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 21:57:32.529  6336  6439 I jxcore-log: 
,08-12 21:57:32.539  4865  4931 I Finsky  : [681] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,08-12 21:57:32.539   753  2125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:57:32.549   753  2125 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4358, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-12 21:57:32.549   753  2125 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-12 21:57:32.549   753  2125 D BatteryService: stay LED for charging
08-12 21:57:32.549   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 21:57:32.549   753   753 I MotionRecognitionService: Plugged
08-12 21:57:32.549   753   753 D MotionRecognitionService:   cableConnection= 1
08-12 21:57:32.549   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 21:57:32.549   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 21:57:32.569  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-12 21:57:32.569  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 21:57:32.569  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 21:57:32.599  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-12 21:57:32.599  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 21:57:32.609  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 21:57:32.609  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 21:57:32.609  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 21:57:32.649   753  1409 V AlarmManager:  remove PendingIntent] PendingIntent{aa23c6c: PendingIntentRecord{74ab34d com.google.android.gms broadcastIntent}}
,08-12 21:57:32.729  4036  6741 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-12 21:57:32.729  4036  6741 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-12 21:57:32.749  2103  2103 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 21:57:32.759   753  1745 V AlarmManager:  remove PendingIntent] PendingIntent{3cb9517: PendingIntentRecord{74ab34d com.google.android.gms broadcastIntent}}
,08-12 21:57:32.779   753   822 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{be5ad04 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f424bcb 2103:com.google.android.gms.persistent/u0a11}
,08-12 21:57:32.809   753  2125 V AlarmManager:  remove PendingIntent] PendingIntent{9a12ed: PendingIntentRecord{74ab34d com.google.android.gms broadcastIntent}}
,08-12 21:57:32.919   753   765 V AlarmManager:  remove PendingIntent] PendingIntent{7929570: PendingIntentRecord{74ab34d com.google.android.gms broadcastIntent}}
,08-12 21:57:32.949  6336  6439 I jxcore-log: Unit Test app is loaded
08-12 21:57:32.949  6336  6439 I jxcore-log: 
,08-12 21:57:32.949  6336  6439 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 21:57:32.949  6336  6439 I jxcore-log: 
,08-12 21:57:32.949  6336  6439 I jxcore-log: My device name is: samsung-SM-G900F
08-12 21:57:32.949  6336  6439 I jxcore-log: 
,08-12 21:57:32.949  6336  6336 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 21:57:32.959  6336  6439 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 21:57:32.959  6336  6439 I jxcore-log: 
,08-12 21:57:33.049  4865  4931 I Finsky  : [681] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,08-12 21:57:33.049  4865  4865 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-12 21:57:33.059  6748  6748 E Zygote  : v2
08-12 21:57:33.059  6748  6748 I libpersona: KNOX_SDCARD checking this for 10011
08-12 21:57:33.059  6748  6748 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:33.059   753  1745 I ActivityManager: Start proc 6748:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,08-12 21:57:33.059  6748  6748 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 21:57:33.059  6748  6748 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 21:57:33.059  6748  6748 E Zygote  : accessInfo : 0
,08-12 21:57:33.059  6748  6748 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,08-12 21:57:33.099  6748  6748 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 21:57:33.099  6748  6748 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:33.119  6748  6748 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 21:57:33.149  6748  6748 I MultiDex: VM with version 2.1.0 has multidex support
,08-12 21:57:33.149  6748  6748 I MultiDex: install
08-12 21:57:33.149  6748  6748 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 21:57:33.179  6748  6748 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-12 21:57:33.189  6748  6748 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-12 21:57:33.189  6748  6748 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-12 21:57:33.199  6748  6748 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-12 21:57:33.229  6748  6748 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-12 21:57:33.249  6748  6748 D ChimeraCfgMgr: Reading stored module config
,08-12 21:57:33.349  2103  2103 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=b542dc69-4299-4d69-8046-99543415c66c
,08-12 21:57:33.359  6748  6762 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-12 21:57:33.359  2103  2103 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 21:57:33.359  2103  2103 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 21:57:33.389   325   325 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6748)
,08-12 21:57:33.439   325   976 D WVCdm   : Instantiating CDM.
,08-12 21:57:33.439   325   969 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6748)
08-12 21:57:33.439   325   969 I WVCdm   : CdmEngine::OpenSession
08-12 21:57:33.439   325   969 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-12 21:57:33.449   325   969 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-12 21:57:33.449   325   969 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
08-12 21:57:33.449   325   969 D DrmWidevineDash: Service_Initialize: starts!
08-12 21:57:33.449   325   969 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-12 21:57:33.449   325   969 D QSEECOMAPI: : App is not loaded in QSEE
08-12 21:57:33.449   325   969 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-12 21:57:33.449   325   969 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-12 21:57:33.449   325   969 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-12 21:57:33.449   325   969 D QSEECOMAPI: : App is not loaded in QSEE
08-12 21:57:33.449   325   969 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-12 21:57:33.449   325   969 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-12 21:57:33.449   325   969 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-12 21:57:33.449   325   969 D QSEECOMAPI: : App is not loaded in QSEE
,08-12 21:57:33.469   325   969 D QSEECOMAPI: : Loaded image: APP id = 3
,08-12 21:57:33.469   753   763 I art     : Background partial concurrent mark sweep GC freed 39055(2MB) AllocSpace objects, 14(280KB) LOS objects, 27% free, 42MB/58MB, paused 1.903ms total 123.049ms
,08-12 21:57:33.469   325   969 D DrmWidevineDash: Service_Initialize: ends! returns 0
08-12 21:57:33.469   325   969 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaefd3000
08-12 21:57:33.469   325   969 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaefd3000
,08-12 21:57:33.489   325   969 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-12 21:57:33.489   325   969 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-12 21:57:33.489   325   969 D DrmWidevineDash: hlos api version =  10
08-12 21:57:33.489   325   969 D DrmWidevineDash: tz api version =  10
08-12 21:57:33.489   325   969 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,08-12 21:57:33.489   325   969 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-12 21:57:33.509   325   969 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,08-12 21:57:33.509   325   969 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-12 21:57:33.509   325   969 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xaf200924
,08-12 21:57:33.509   325   969 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-12 21:57:33.509   325   969 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-12 21:57:33.509   325   969 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xae3d30a8, dataLength=8
,08-12 21:57:33.509   325   969 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-12 21:57:33.509   325   969 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xae8f8400, wrapped_rsa_key_length=1280
,08-12 21:57:33.519   325   969 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-12 21:57:33.519   325   969 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-12 21:57:33.519   325   971 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-12 21:57:33.519   325   971 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
08-12 21:57:33.519   325   971 I WVCdm   : CdmEngine::GenerateKeyRequest
08-12 21:57:33.519   325   971 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xaf5733c0, idLength=0xaf0fef2c
,08-12 21:57:33.529  6748  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 21:57:33.529  6748  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 21:57:33.529   325   971 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-12 21:57:33.529   325   971 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,08-12 21:57:33.529   325   971 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-12 21:57:33.529   325   971 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
08-12 21:57:33.529   325   971 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
08-12 21:57:33.529   325   971 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,08-12 21:57:33.529   325   971 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
08-12 21:57:33.529   325   971 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-12 21:57:33.529   325   971 D DrmWidevineDash: hlos api version =  10
08-12 21:57:33.529   325   971 D DrmWidevineDash: tz api version =  10
08-12 21:57:33.529   325   971 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-12 21:57:33.529   325   971 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,08-12 21:57:33.529   325   971 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
08-12 21:57:33.529   325   971 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-12 21:57:33.529   325   971 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,08-12 21:57:33.529   325   971 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-12 21:57:33.529   325   971 D WVCdm   : PrepareKeyRequest: nonce=1334556033
08-12 21:57:33.529   303  1137 D EnterpriseController: netId is 0
08-12 21:57:33.529   303  1137 D Netd    : getNetworkForDns: using netid 502 for uid 10011
08-12 21:57:33.529   325   971 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1dc4300
,08-12 21:57:33.529   325   971 D DrmWidevineDash: message_length=1631, signature=0xaf57b3c0, signature_length=2937057284
,08-12 21:57:33.579  6748  6759 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6748, getuid(): 10011
,08-12 21:57:33.589  2103  2489 W GCoreFlp: No location to return for getLastLocation()
,08-12 21:57:33.619   325   971 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-12 21:57:33.619   325   976 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6748)
,08-12 21:57:33.619   325   976 I WVCdm   : CdmEngine::CloseSession
08-12 21:57:33.619   325   976 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,08-12 21:57:33.619   325   976 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-12 21:57:33.619   325   976 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,08-12 21:57:33.619   325   976 D DrmWidevineDash: Service_Uninitialize: starts!
08-12 21:57:33.619   325   976 D QSEECOMAPI: : QSEECom_dealloc_memory 
,08-12 21:57:33.619   325   976 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
08-12 21:57:33.629   325   976 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-12 21:57:33.629   325   976 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-12 21:57:33.659  4036  6742 D UdcContextInitService: registered all accounts: true
,08-12 21:57:33.669  2103  2586 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 21:57:33.679  2103  2694 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-12 21:57:33.739  6748  6759 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6748, getuid(): 10011
,08-12 21:57:33.749   753  1409 V AlarmManager:  remove PendingIntent] PendingIntent{3d20ffb: PendingIntentRecord{74ab34d com.google.android.gms broadcastIntent}}
,08-12 21:57:33.869  6748  6759 I qtaguid : Untagging socket 21
,08-12 21:57:33.909  6748  6759 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 21:57:33.909  6748  6759 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 21:57:33.949  2103  6777 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-12 21:57:33.949  2103  6774 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-12 21:57:33.969  2103  6777 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-12 21:57:33.969  2103  6774 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-12 21:57:33.989  2103  6777 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-12 21:57:33.989  2103  6774 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-12 21:57:33.989  2103  6774 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-12 21:57:34.019  2103  6774 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 21:57:34.079   753  1625 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 21:57:34.129  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 21:57:34.129  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 21:57:34.129   303  1137 D EnterpriseController: netId is 0
08-12 21:57:34.129   303  1137 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 21:57:34.179  2103  6774 I qtaguid : Tagging socket 59 with tag 1000040100000000{268436481,0} uid 10011, pid: 2103, getuid(): 10011
,08-12 21:57:34.209  6779  6779 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-12 21:57:34.209  2103  6774 I qtaguid : Tagging socket 62 with tag 1000040100000000{268436481,0} uid 10011, pid: 2103, getuid(): 10011
,08-12 21:57:34.289  6779  6779 I dex2oat : ----------------------------------------------------
08-12 21:57:34.289  6779  6779 I dex2oat : <SS>: S T A R T I N G . . .
08-12 21:57:34.289  6779  6779 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
,08-12 21:57:34.289  6779  6779 I dex2oat : dex2oat took 84.412ms (threads: 4) arena alloc=285KB java alloc=67KB native alloc=1670KB free=1657KB
,08-12 21:57:34.299  6748  6759 W System  : ClassLoader referenced unknown path: 
,08-12 21:57:34.299  6748  6759 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,08-12 21:57:34.309  6748  6759 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 21:57:34.309  6748  6759 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 21:57:34.309  6748  6759 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 21:57:34.309  6748  6759 I Adreno-EGL: Local Branch: ss
08-12 21:57:34.309  6748  6759 I Adreno-EGL: Remote Branch: 
08-12 21:57:34.309  6748  6759 I Adreno-EGL: Local Patches: 
08-12 21:57:34.309  6748  6759 I Adreno-EGL: Reconstruct Branch: 
,08-12 21:57:34.309  6748  6759 D libEGL  : eglInitialize EGLDisplay = 0xb2f37264
,08-12 21:57:34.369  6748  6759 D libEGL  : eglTerminate EGLDisplay = 0xb2f372bc
,08-12 21:57:34.379  6748  6759 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 21:57:34.379  6748  6759 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 21:57:34.379  6748  6759 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 21:57:34.379  6748  6759 I Adreno-EGL: Local Branch: ss
08-12 21:57:34.379  6748  6759 I Adreno-EGL: Remote Branch: 
08-12 21:57:34.379  6748  6759 I Adreno-EGL: Local Patches: 
08-12 21:57:34.379  6748  6759 I Adreno-EGL: Reconstruct Branch: 
08-12 21:57:34.379  6748  6759 D libEGL  : eglInitialize EGLDisplay = 0xb2f37264
,08-12 21:57:34.419  6748  6759 D libEGL  : eglTerminate EGLDisplay = 0xb2f372bc
,08-12 21:57:34.459  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 21:57:34.459  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 21:57:34.459   303  1137 D EnterpriseController: netId is 0
08-12 21:57:34.459   303  1137 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 21:57:34.469  2103  6774 I qtaguid : Tagging socket 63 with tag fffffca200000000{4294966434,0} uid -1, pid: 2103, getuid(): 10011
,08-12 21:57:34.499  2103  6774 I qtaguid : Tagging socket 66 with tag fffffca200000000{4294966434,0} uid -1, pid: 2103, getuid(): 10011
,08-12 21:57:34.559  6748  6759 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 21:57:34.559  6748  6759 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 21:57:34.559  6748  6759 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 21:57:34.559  6748  6759 I Adreno-EGL: Local Branch: ss
08-12 21:57:34.559  6748  6759 I Adreno-EGL: Remote Branch: 
08-12 21:57:34.559  6748  6759 I Adreno-EGL: Local Patches: 
08-12 21:57:34.559  6748  6759 I Adreno-EGL: Reconstruct Branch: 
08-12 21:57:34.559  6748  6759 D libEGL  : eglInitialize EGLDisplay = 0xb2f37264
,08-12 21:57:34.599  6748  6759 D libEGL  : eglTerminate EGLDisplay = 0xb2f372bc
,08-12 21:57:34.689   753  1440 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 21:57:34.699  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 21:57:34.699  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 21:57:34.699  2103  6774 I qtaguid : Tagging socket 63 with tag fffff33b00000000{4294964027,0} uid -1, pid: 2103, getuid(): 10011
,08-12 21:57:34.739  2103  6744 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 21:57:34.739  2103  6744 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 21:57:34.739  2103  6744 I qtaguid : Tagging socket 56 with tag 1000040100000000{268436481,0} uid 10011, pid: 2103, getuid(): 10011
,08-12 21:57:34.769  2103  6744 I qtaguid : Tagging socket 69 with tag 1000040100000000{268436481,0} uid 10011, pid: 2103, getuid(): 10011
,08-12 21:57:34.789   753  2227 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 21:57:34.809  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 21:57:34.809  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 21:57:34.809  2103  6774 I qtaguid : Tagging socket 63 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 2103, getuid(): 10011
,08-12 21:57:34.909  2103  2694 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 21:57:34.909   753  1218 V AlarmManager:  remove PendingIntent] PendingIntent{a4c8c2e: PendingIntentRecord{74ab34d com.google.android.gms broadcastIntent}}
,08-12 21:57:34.919  2103  2694 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-12 21:57:34.929  2103  2694 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-12 21:57:33.735+0200, stopTime=2016-08-12 21:57:34.939+0200, duration=1204ms
,08-12 21:57:34.949   753  1741 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 21:57:34.949  2103  6794 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 21:57:34.949  2103  6794 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 21:57:34.949   303  1137 D EnterpriseController: netId is 0
08-12 21:57:34.949   303  1137 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 21:57:34.959  2103  6794 I qtaguid : Tagging socket 71 with tag 1000310500000000{268448005,0} uid 10011, pid: 2103, getuid(): 10011
,08-12 21:57:34.969  2103  6774 W Uploader: UNKNOWN no longer exists, so no auth token.
,08-12 21:57:34.989  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 21:57:34.989  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 21:57:34.989  2103  6774 I qtaguid : Tagging socket 63 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2103, getuid(): 10011
,08-12 21:57:34.999  2103  6794 I qtaguid : Tagging socket 73 with tag 1000310500000000{268448005,0} uid 10011, pid: 2103, getuid(): 10011
,08-12 21:57:35.079   753  1799 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 21:57:35.079  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 21:57:35.079  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 21:57:35.079  2103  6774 I qtaguid : Tagging socket 63 with tag 11065c0800000000{285629448,0} uid -1, pid: 2103, getuid(): 10011
,08-12 21:57:35.169   753  1440 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 21:57:35.179  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 21:57:35.179  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 21:57:35.179  2103  6774 I qtaguid : Tagging socket 63 with tag fffffb1f00000000{4294966047,0} uid -1, pid: 2103, getuid(): 10011
,08-12 21:57:35.269   753   765 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 21:57:35.279  2103  6794 I qtaguid : Untagging socket 71
,08-12 21:57:35.279  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 21:57:35.279  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 21:57:35.279  2103  6774 I qtaguid : Tagging socket 63 with tag 11065fff00000000{285630463,0} uid -1, pid: 2103, getuid(): 10011
,08-12 21:57:35.279  2103  2694 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-12 21:57:35.369   753  2219 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 21:57:35.379  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 21:57:35.379  2103  6774 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 21:57:35.379  2103  6774 I qtaguid : Tagging socket 63 with tag 11065c9100000000{285629585,0} uid -1, pid: 2103, getuid(): 10011
,08-12 21:57:35.519   753  2228 V AlarmManager:  remove PendingIntent] PendingIntent{ab1415c: PendingIntentRecord{74ab34d com.google.android.gms broadcastIntent}}
,08-12 21:57:35.549  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 21:57:35.549  6336  6439 I jxcore-log: 
,08-12 21:57:36.189  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 21:57:36.189  6336  6439 I jxcore-log: 
,08-12 21:57:36.219  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 21:57:36.219  6336  6439 I jxcore-log: 
,08-12 21:57:36.829   753  3416 D SSRM:n  : SIOP:: AP = 450, PST = 447, CUR = 450, LCD = 0
,08-12 21:57:37.099  2103  6795 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 21:57:37.099  2103  6795 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 21:57:37.099  2103  6795 I qtaguid : Tagging socket 71 with tag 1000310200000000{268448002,0} uid 10011, pid: 2103, getuid(): 10011
,08-12 21:57:37.309  2103  6795 I qtaguid : Untagging socket 71
,08-12 21:57:37.319  2103  2694 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-12 21:57:37.339   753  3454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 21:57:37.659  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 21:57:37.659  6336  6439 I jxcore-log: 
,08-12 21:57:37.899  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 21:57:37.899  6336  6439 I jxcore-log: 
,08-12 21:57:37.909  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 21:57:37.909  6336  6439 I jxcore-log: 
,08-12 21:57:37.909  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 21:57:37.909  6336  6439 I jxcore-log: 
,08-12 21:57:37.929  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 21:57:37.929  6336  6439 I jxcore-log: 
,08-12 21:57:37.939  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 21:57:37.939  6336  6439 I jxcore-log: 
,08-12 21:57:38.639  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 21:57:38.639  6336  6439 I jxcore-log: 
,08-12 21:57:38.649  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 21:57:38.649  6336  6439 I jxcore-log: 
,08-12 21:57:38.659  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 21:57:38.659  6336  6439 I jxcore-log: 
,08-12 21:57:38.669  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 21:57:38.669  6336  6439 I jxcore-log: 
,08-12 21:57:38.719  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 21:57:38.719  6336  6439 I jxcore-log: 
,08-12 21:57:38.779  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 21:57:38.779  6336  6439 I jxcore-log: 
,08-12 21:57:38.789  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 21:57:38.789  6336  6439 I jxcore-log: 
,08-12 21:57:38.959  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 21:57:38.959  6336  6439 I jxcore-log: 
,08-12 21:57:38.989  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 21:57:38.989  6336  6439 I jxcore-log: 
,08-12 21:57:38.999  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 21:57:38.999  6336  6439 I jxcore-log: 
,08-12 21:57:38.999  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 21:57:38.999  6336  6439 I jxcore-log: 
,08-12 21:57:39.019  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 21:57:39.019  6336  6439 I jxcore-log: 
,08-12 21:57:39.109  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 21:57:39.109  6336  6439 I jxcore-log: 
,08-12 21:57:39.119  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 21:57:39.119  6336  6439 I jxcore-log: 
,08-12 21:57:39.149  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 21:57:39.149  6336  6439 I jxcore-log: 
,08-12 21:57:39.169  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 21:57:39.169  6336  6439 I jxcore-log: 
,08-12 21:57:39.179  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 21:57:39.179  6336  6439 I jxcore-log: 
,08-12 21:57:39.219  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 21:57:39.219  6336  6439 I jxcore-log: 
,08-12 21:57:39.229  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 21:57:39.229  6336  6439 I jxcore-log: 
,08-12 21:57:39.439  6336  6439 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 21:57:39.439  6336  6439 I jxcore-log: 
,08-12 21:57:39.449  6336  6439 D BluetoothAdapter: STATE_ON
,08-12 21:57:39.459  6336  6439 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-12 21:57:39.459  6336  6439 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-12 21:57:39.459  6336  6439 I jxcore-log: 
,08-12 21:57:39.739   753  1218 I ActivityManager: Killing 5488:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,08-12 21:57:39.769   753  1440 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,08-12 21:57:42.629   753  2219 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:57:42.639   753  2219 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 21:57:42.639   753  2219 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 21:57:42.639   753  2219 D BatteryService: stay LED for charging
,08-12 21:57:42.649   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 21:57:42.669   753   753 I MotionRecognitionService: Plugged
,08-12 21:57:42.669   753   753 D MotionRecognitionService:   cableConnection= 1
,08-12 21:57:42.669  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:57:42.669  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 21:57:42.669  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 21:57:42.669   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 21:57:42.669   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 21:57:42.699  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 21:57:42.699  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 21:57:42.709  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 21:57:42.709  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 21:57:42.709  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 21:57:46.879   753  3416 D SSRM:n  : SIOP:: AP = 410, PST = 439, CUR = 450, LCD = 0
,08-12 21:57:52.699   753  1799 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:57:52.709   753  1799 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4387, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 21:57:52.709   753  1799 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 21:57:52.709   753  1799 D BatteryService: stay LED for charging
,08-12 21:57:52.709   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 21:57:52.729   753   753 I MotionRecognitionService: Plugged
,08-12 21:57:52.729   753   753 D MotionRecognitionService:   cableConnection= 1
,08-12 21:57:52.729   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 21:57:52.739   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 21:57:52.749  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:57:52.749  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:57:52.749  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 21:57:52.779  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 21:57:52.779  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 21:57:52.789  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 21:57:52.789  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 21:57:52.789  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 21:57:56.949   753  3416 D SSRM:n  : SIOP:: AP = 380, PST = 429, CUR = 450, LCD = 0
,08-12 21:57:56.949   753  3416 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,08-12 21:57:57.029  6827  6827 E Zygote  : v2
,08-12 21:57:57.029  6827  6827 I libpersona: KNOX_SDCARD checking this for 10053
08-12 21:57:57.029  6827  6827 I libpersona: KNOX_SDCARD not a persona
,08-12 21:57:57.039   753   822 I ActivityManager: Start proc 6827:com.sec.android.app.videoplayer/u0a53 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
,08-12 21:57:57.039   753  1318 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-12 21:57:57.039  6827  6827 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 21:57:57.039  6827  6827 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 21:57:57.039  6827  6827 E Zygote  : accessInfo : 0
,08-12 21:57:57.049  6827  6827 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,08-12 21:57:57.059   753  3416 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 21:57:57.109  6827  6827 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 21:57:57.109  6827  6827 D ActivityThread: Added TimaKeyStore provider
,08-12 21:57:57.119  2782  2782 D ContentApp:  LEVEL : 0
,08-12 21:57:57.159   753   767 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c42edeb u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bbf1748 6827:com.sec.android.app.videoplayer/u0a53}
,08-12 21:57:57.159   753  1318 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-12 21:57:57.169  6827  6827 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-12 21:57:57.199  6827  6827 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,08-12 21:57:57.229  6827  6827 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-12 21:57:57.249  6827  6827 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-12 21:57:57.259  6827  6827 D videowall-Global: core_num = 4
,08-12 21:57:57.269  6827  6827 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
08-12 21:57:57.269  6827  6827 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,08-12 21:57:57.289  6827  6827 D TranscodeReceiver:  SIOP_LEVEL: 0
,08-12 21:57:57.289   753  2125 I ActivityManager: Killing 5864:com.google.android.apps.photos/u0a199 (adj 15): DHA:empty #37
,08-12 21:57:57.309   753   765 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,08-12 21:57:57.339   753  3454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 21:57:57.889   753  1583 E Watchdog: !@Sync 4 [08-12 21:57:57.899]
,08-12 21:57:58.709  1656  1744 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 21:57:59.989   753  1235 V AlarmManager: Expired Alarm result :8
,08-12 21:58:02.789   753  2228 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:58:02.789   753  2228 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 21:58:02.799   753  2228 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 21:58:02.799   753  2228 D BatteryService: stay LED for charging
,08-12 21:58:02.799   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 21:58:02.829   753   753 I MotionRecognitionService: Plugged
,08-12 21:58:02.829  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:58:02.829  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 21:58:02.829  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 21:58:02.829   753   753 D MotionRecognitionService:   cableConnection= 1
,08-12 21:58:02.829   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 21:58:02.839   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 21:58:02.849  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 21:58:02.849  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 21:58:02.859  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 21:58:02.859  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 21:58:02.859  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 21:58:07.129   753  3416 D SSRM:n  : SIOP:: AP = 350, PST = 422, CUR = 450, LCD = 0
,08-12 21:58:12.829   753  1235 V AlarmManager: Expired Alarm result :4
,08-12 21:58:12.909   753   765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:58:12.909   753   765 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4387, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 21:58:12.909   753   765 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-12 21:58:12.909   753   765 D BatteryService: stay LED for charging
,08-12 21:58:12.949  6861  6861 E Zygote  : v2
,08-12 21:58:12.949   753  1235 I ActivityManager: Start proc 6861:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,08-12 21:58:12.949  6861  6861 I libpersona: KNOX_SDCARD checking this for 1000
,08-12 21:58:12.949  6861  6861 I libpersona: KNOX_SDCARD not a persona
,08-12 21:58:12.959  6861  6861 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 21:58:12.959  6861  6861 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 21:58:12.959  6861  6861 E Zygote  : accessInfo : 0
,08-12 21:58:12.979  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-12 21:58:12.979  1373  1373 I PERF    : received broadcast android.intent.action.TIME_TICK
08-12 21:58:12.979  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
,08-12 21:58:12.989   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 21:58:12.989  1373  1373 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-12 21:58:12.989  1373  1373 D SecKeyguardClockView: HomeTimezone(): 1
,08-12 21:58:12.989   753   753 I MotionRecognitionService: Plugged
08-12 21:58:12.989   753   753 D MotionRecognitionService:   cableConnection= 1
08-12 21:58:12.989   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 21:58:12.989   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 21:58:12.999  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 21:58:12.999  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 21:58:12.999  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 21:58:12.999  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 21:58:12.999  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 21:58:12.999  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 21:58:12.999  1373  1373 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 21:58:12.999  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-12 21:58:12.999  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 21:58:12.999  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-12 21:58:12.999  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:58:12.999  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 21:58:12.999  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 21:58:12.999  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 21:58:13.019  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 21:58:13.019  6861  6861 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 21:58:13.019  6861  6861 D ActivityThread: Added TimaKeyStore provider
,08-12 21:58:13.029  6861  6861 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,08-12 21:58:13.049  6861  6861 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,08-12 21:58:13.049  1373  1373 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 21:58:13.069   753  1620 I ActivityManager: Killing 5933:com.google.android.apps.magazines/u0a127 (adj 15): DHA:empty #37
,08-12 21:58:13.089   753  1745 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.magazines, Auto Run ON
,08-12 21:58:17.199   753  3416 D SSRM:n  : SIOP:: AP = 340, PST = 415, CUR = 450, LCD = 0
,08-12 21:58:17.339   753  3454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 21:58:22.999   753  1620 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:58:23.009   753  1620 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 21:58:23.009   753  1620 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 21:58:23.019   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 21:58:23.019  4036  5047 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 21:58:23.029   753   753 I MotionRecognitionService: Plugged
,08-12 21:58:23.029   753   753 D MotionRecognitionService:   cableConnection= 1
,08-12 21:58:23.039   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 21:58:23.039   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 21:58:23.049   753  1620 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 39ms
,08-12 21:58:23.049   753  1620 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 753) 
,08-12 21:58:23.059  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:58:23.059  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:58:23.069  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 21:58:23.069  1373  1373 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 21:58:23.079   753  1620 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,08-12 21:58:23.099   753  1620 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,08-12 21:58:23.109   753  1620 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,08-12 21:58:23.109  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 21:58:23.109  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 21:58:23.109  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:58:23.109  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:58:23.109  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:58:23.129   753  1620 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,08-12 21:58:23.129   753  1620 D BatteryService: turn on LED for fully charged
,08-12 21:58:23.499   753  1217 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,08-12 21:58:23.499   753   902 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,08-12 21:58:23.499   753   902 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,08-12 21:58:23.509   753   902 D SensorManager: unregisterListener ::   
,08-12 21:58:23.519   753   902 D lights  : led_pattern : 5 +
,08-12 21:58:23.529   753   902 D lights  : led_pattern : 5 -
,08-12 21:58:23.539   753   902 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,08-12 21:58:23.539   753   902 V AlarmManager:  remove PendingIntent] PendingIntent{c1dff96: PendingIntentRecord{a9b717 android broadcastIntent}}
,08-12 21:58:25.609  2103  3298 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 21:58:27.259   753  3416 D SSRM:n  : SIOP:: AP = 330, PST = 407, CUR = 450, LCD = 0
,08-12 21:58:27.259   753  3416 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,08-12 21:58:27.279  2782  2782 D ContentApp:  LEVEL : -1
,08-12 21:58:27.299   753   822 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9c63992 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bbf1748 6827:com.sec.android.app.videoplayer/u0a53}
,08-12 21:58:27.309  6827  6827 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-12 21:58:27.309  6827  6827 D TranscodeReceiver:  SIOP_LEVEL: -1
,08-12 21:58:27.899   753  1583 E Watchdog: !@Sync 5 [08-12 21:58:27.908]
,08-12 21:58:28.249   753  3417 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,08-12 21:58:28.259   753   822 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c9e66b7 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e0ba88f 6272:com.samsung.android.sm.provider/1000}
,08-12 21:58:28.369   753  3417 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,08-12 21:58:28.379   753   822 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{86c4d8d u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e0ba88f 6272:com.samsung.android.sm.provider/1000}
,08-12 21:58:33.079   753  2125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:58:33.079   753  2125 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 21:58:33.079   753  2125 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 21:58:33.089   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 21:58:33.099   753   753 I MotionRecognitionService: Plugged
,08-12 21:58:33.099   753   753 D MotionRecognitionService:   cableConnection= 1
,08-12 21:58:33.109   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 21:58:33.109   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 21:58:33.119   753  2125 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 38ms
,08-12 21:58:33.119   753  2125 D BatteryService: stay LED for fully charged
,08-12 21:58:33.129  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:58:33.129  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:58:33.129  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 21:58:33.149  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 21:58:33.149  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 21:58:33.159  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:58:33.159  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:58:33.159  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:58:37.339   753  3454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 21:58:37.369   753  3416 D SSRM:n  : SIOP:: AP = 330, PST = 399, CUR = 450, LCD = 0
,08-12 21:58:43.169   753  2227 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:58:47.429   753  3416 D SSRM:n  : SIOP:: AP = 320, PST = 385, CUR = 450, LCD = 0
,08-12 21:58:53.259   753  2125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:58:53.269   753  2125 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 21:58:53.269   753  2125 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 21:58:53.269   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 21:58:53.279   753   753 I MotionRecognitionService: Plugged
,08-12 21:58:53.289   753   753 D MotionRecognitionService:   cableConnection= 1
,08-12 21:58:53.289   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 21:58:53.289   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 21:58:53.289   753  2125 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,08-12 21:58:53.299   753  2125 D BatteryService: stay LED for fully charged
,08-12 21:58:53.299  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:58:53.309  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:58:53.309  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 21:58:53.329  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 21:58:53.329  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 21:58:53.339  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:58:53.339  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:58:53.339  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:58:57.349   753  3454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 21:58:57.489   753  3416 D SSRM:n  : SIOP:: AP = 320, PST = 369, CUR = 450, LCD = 0
,08-12 21:58:57.899   753  1583 E Watchdog: !@Sync 6 [08-12 21:58:57.912]
,08-12 21:58:58.719  1656  1744 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 21:58:59.989   753  1235 V AlarmManager: Expired Alarm result :8
,08-12 21:59:03.349   753  1440 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:59:07.549   753  3416 D SSRM:n  : SIOP:: AP = 310, PST = 354, CUR = 450, LCD = 0
,08-12 21:59:13.439   753  1620 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:59:17.349   753  3454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 21:59:17.619   753  3416 D SSRM:n  : SIOP:: AP = 310, PST = 340, CUR = 450, LCD = 0
,08-12 21:59:23.529   753  1625 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:59:23.539   753  1625 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 21:59:23.539   753  1625 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 21:59:23.539   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 21:59:23.559   753   753 I MotionRecognitionService: Plugged
,08-12 21:59:23.559   753   753 D MotionRecognitionService:   cableConnection= 1
,08-12 21:59:23.559   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 21:59:23.559   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 21:59:23.569   753  1625 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-12 21:59:23.569   753  1625 D BatteryService: stay LED for fully charged
,08-12 21:59:23.579  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:59:23.579  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 21:59:23.579  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 21:59:23.589  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 21:59:23.589  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 21:59:23.599  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:59:23.609  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:59:23.609  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:59:27.679   753  3416 D SSRM:n  : SIOP:: AP = 310, PST = 330, CUR = 450, LCD = 0
,08-12 21:59:27.899   753  1583 E Watchdog: !@Sync 7 [08-12 21:59:27.916]
,08-12 21:59:33.619   753  2228 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:59:33.619   753  2228 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 21:59:33.629   753  2228 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 21:59:33.629   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 21:59:33.639   753   753 I MotionRecognitionService: Plugged
,08-12 21:59:33.639   753   753 D MotionRecognitionService:   cableConnection= 1
,08-12 21:59:33.649   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 21:59:33.649   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 21:59:33.659   753  2228 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-12 21:59:33.659   753  2228 D BatteryService: stay LED for fully charged
,08-12 21:59:33.669  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:59:33.669  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:59:33.679  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 21:59:33.689  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 21:59:33.689  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 21:59:33.699  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:59:33.699  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 21:59:33.699  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:59:37.359   753  3454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 21:59:37.749   753  3416 D SSRM:n  : SIOP:: AP = 310, PST = 323, CUR = 450, LCD = 0
,08-12 21:59:43.709   753  1798 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:59:43.709   753  1798 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 21:59:43.709   753  1798 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 21:59:43.719   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 21:59:43.729   753   753 I MotionRecognitionService: Plugged
,08-12 21:59:43.729   753   753 D MotionRecognitionService:   cableConnection= 1
,08-12 21:59:43.739   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 21:59:43.739   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 21:59:43.739   753  1798 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,08-12 21:59:43.749   753  1798 D BatteryService: stay LED for fully charged
,08-12 21:59:43.759  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:59:43.759  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 21:59:43.759  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 21:59:43.779  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 21:59:43.779  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 21:59:43.789  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:59:43.789  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:59:43.789  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 21:59:47.809   753  3416 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 450, LCD = 0
,08-12 21:59:53.799   753  1741 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 21:59:57.359   753  3454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 21:59:57.869   753  3416 D SSRM:n  : SIOP:: AP = 300, PST = 315, CUR = 450, LCD = 0
,08-12 21:59:57.909   753  1583 E Watchdog: !@Sync 8 [08-12 21:59:57.920]
,08-12 21:59:58.809  1656  1744 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 21:59:59.039  1656  1744 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 217ms lastUpdatedAfter : 164201ms
,08-12 22:00:03.889   753  1745 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:00:03.899   753  1745 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:00:03.899   753  1745 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 22:00:03.899   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:00:03.909   753   753 I MotionRecognitionService: Plugged
,08-12 22:00:03.909   753   753 D MotionRecognitionService:   cableConnection= 1
,08-12 22:00:03.919   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 22:00:03.919   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:00:03.929   753  1745 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,08-12 22:00:03.929   753  1745 D BatteryService: stay LED for fully charged
,08-12 22:00:03.929  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-12 22:00:03.929  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 22:00:03.929  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:00:03.939  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:00:03.939  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:00:03.949  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:00:03.959  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:00:03.959  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:00:07.929   753  3416 D SSRM:n  : SIOP:: AP = 300, PST = 312, CUR = 450, LCD = 0
,08-12 22:00:13.979   753  2125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:00:13.979   753  2125 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:00:13.989   753  2125 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 22:00:13.989   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:00:13.999   753   753 I MotionRecognitionService: Plugged
,08-12 22:00:13.999   753   753 D MotionRecognitionService:   cableConnection= 1
,08-12 22:00:14.009   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 22:00:14.009   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:00:14.009   753  2125 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-12 22:00:14.019   753  2125 D BatteryService: stay LED for fully charged
,08-12 22:00:14.029  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:00:14.029  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 22:00:14.029  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:00:14.039  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:00:14.039  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:00:14.049  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:00:14.049  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:00:14.059  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:00:17.369   753  3454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:00:17.989   753  3416 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450, LCD = 0
,08-12 22:00:24.069   753  1440 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:00:24.079   753  1440 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:00:24.079   753  1440 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 22:00:24.079   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:00:24.099   753   753 I MotionRecognitionService: Plugged
,08-12 22:00:24.099   753   753 D MotionRecognitionService:   cableConnection= 1
,08-12 22:00:24.099   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 22:00:24.099   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:00:24.109   753  1440 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-12 22:00:24.109   753  1440 D BatteryService: stay LED for fully charged
,08-12 22:00:24.129  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:00:24.129  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 22:00:24.129  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:00:24.139  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:00:24.139  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:00:24.149  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:00:24.149  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 22:00:24.149  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:00:27.919   753  1583 E Watchdog: !@Sync 9 [08-12 22:00:27.926]
,08-12 22:00:28.049   753  3416 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450, LCD = 0
,08-12 22:00:34.139   753  1625 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:00:37.369   753  3454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:00:38.109   753  3416 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450, LCD = 0
,08-12 22:00:42.999   753  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-12 22:00:43.009   753  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-12 22:00:43.009   753  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,08-12 22:00:43.029   753  1229 I TLC_TIMA_PKM_initialize: initializing...
,08-12 22:00:43.029   753  1229 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,08-12 22:00:43.029   753  1229 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,08-12 22:00:43.039   753  1229 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,08-12 22:00:43.039   753  1229 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,08-12 22:00:43.039   753  1229 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,08-12 22:00:43.049   753  1229 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,08-12 22:00:43.049   753  1229 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,08-12 22:00:43.049   753  1229 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,08-12 22:00:43.059   753  1229 D QSEECOMAPI: : App is not loaded in QSEE
,08-12 22:00:43.109   753  1229 D QSEECOMAPI: : Loaded image: APP id = 3
,08-12 22:00:43.129   753  1229 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-12 22:00:43.139   753  1229 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-12 22:00:44.229   753   765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:00:46.439   753  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-12 22:00:46.439   753  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-12 22:00:46.459   753  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-12 22:00:46.459   753  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-12 22:00:48.159   753  3416 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450, LCD = 0
,08-12 22:00:50.219   303  1133 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-12 22:00:50.219   303  1133 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-12 22:00:50.219   303  1133 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-12 22:00:56.989   303  1133 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-12 22:00:56.989   303  1133 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-12 22:00:56.989   303  1133 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-12 22:00:57.369   753  3454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:00:57.919   753  1583 E Watchdog: !@Sync 10 [08-12 22:00:57.932]
,08-12 22:00:58.229   753  3416 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450, LCD = 0
,08-12 22:00:59.139  1656  1744 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 22:00:59.199   753  1235 V AlarmManager: Expired Alarm result :4
,08-12 22:00:59.219  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-12 22:00:59.219  1373  1373 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-12 22:00:59.229  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
,08-12 22:00:59.279  1373  1373 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-12 22:00:59.289   753  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:00:59.289   753  1218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-12 22:00:59.289   753  1218 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-12 22:00:59.289   753  1218 D BatteryService: stay LED for fully charged
,08-12 22:00:59.289  1373  1373 D SecKeyguardClockView: HomeTimezone(): 1
,08-12 22:00:59.319  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:00:59.319  1548  1548 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-12 22:00:59.329  1548  1548 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-12 22:00:59.349  1548  1548 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-12 22:00:59.349  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:00:59.349  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:00:59.349  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:00:59.349  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:00:59.359   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-12 22:00:59.359  1373  1373 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:00:59.369  2096  2096 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:00:59.369  2096  2661 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:00:59.369   753   753 I MotionRecognitionService: Plugged
,08-12 22:00:59.379   753   753 D MotionRecognitionService:   cableConnection= 1
,08-12 22:00:59.379   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 22:00:59.379   753   753 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:00:59.379  1373  1373 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:00:59.399  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-12 22:00:59.399  1373  1373 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:00:59.399  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:00:59.399  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 22:00:59.399  1373  1373 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:00:59.409  1373  1373 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:00:59.439  1373  1373 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:01:00.199   753  1235 V AlarmManager: Expired Alarm result :8
,08-12 22:01:03.139  1548  1548 I wpa_supplicant: nl80211: Received scan results (35 BSSes)
,08-12 22:01:03.139   303  1134 D Netd    : Iface wlan0 link up
,08-12 22:01:03.149  1548  1548 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,08-12 22:01:03.189   753   826 D Tethering: interfaceLinkStateChanged wlan0, true
,08-12 22:01:03.199   753  1319 D WifiP2pService: InactiveState{ what=147461 }
,08-12 22:01:03.199   753  1319 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-12 22:01:03.199   753  1319 D WifiP2pService: DefaultState{ what=147461 }
08-12 22:01:03.199   753   826 D Tethering: interfaceStatusChanged wlan0, true
,08-12 22:01:03.259   753   822 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{75d3589 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fc4008b 1373:com.android.systemui/u0a58}
,08-12 22:01:04.069  6336  6439 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 22:01:04.069  6336  6439 I jxcore-log: 
,08-12 22:01:05.239  2112  2112 E audit   : type=1400 msg=audit(1471032065.229:290): avc:  denied  { execmod } for  pid=6959 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-12 22:01:05.239  2112  2112 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-12 22:01:05.239  2112  2112 E audit   : type=1300 msg=audit(1471032065.229:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fbe000 a1=51000 a2=5 a3=4 items=0 ppid=3548 ppcomm=adbd pid=6959 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-12 22:01:05.249  2112  2112 E audit   : type=1327 msg=audit(1471032065.229:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-12 22:01:05.249  2112  2112 E audit   : type=1320 msg=audit(1471032065.229:290): 
,08-12 22:01:05.289  2112  2112 E audit   : type=1400 msg=audit(1471032065.289:291): avc:  denied  { execmod } for  pid=6959 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 22:01:05.289  2112  2112 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-12 22:01:05.289  2112  2112 E audit   : type=1300 msg=audit(1471032065.289:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f82000 a1=51000 a2=5 a3=4 items=0 ppid=3548 ppcomm=adbd pid=6959 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-12 22:01:05.289  2112  2112 E audit   : type=1327 msg=audit(1471032065.289:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-12 22:01:05.289  2112  2112 E audit   : type=1320 msg=audit(1471032065.289:291): 
,08-12 22:01:05.329  2112  2112 E audit   : type=1400 msg=audit(1471032065.329:292): avc:  denied  { execmod } for  pid=6959 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 22:01:05.329  2112  2112 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 22:01:05.329  2112  2112 E audit   : type=1300 msg=audit(1471032065.329:292): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f80000 a1=51000 a2=5 a3=4 items=0 ppid=3548 ppcomm=adbd pid=6959 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 22:01:05.329  6959  6959 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 22:01:05.329  2112  2112 E audit   : type=1327 msg=audit(1471032065.329:292): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-12 22:01:05.329  2112  2112 E audit   : type=1320 msg=audit(1471032065.329:292): 
,08-12 22:01:05.339  6959  6959 D AndroidRuntime: CheckJNI is OFF
,08-12 22:01:05.339  6959  6959 D AndroidRuntime: readGMSProperty: start
08-12 22:01:05.339  6959  6959 D AndroidRuntime: readGMSProperty: already setted!!
08-12 22:01:05.339  6959  6959 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-12 22:01:05.339  6959  6959 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-12 22:01:05.339  6959  6959 D AndroidRuntime: readGMSProperty: end
08-12 22:01:05.339  6959  6959 D AndroidRuntime: addProductProperty: start
,08-12 22:01:05.349  6959  6959 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 22:01:05.349  6959  6959 W art     : aede5000-b1d0b000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-12 22:01:05.349  6959  6959 W art     : b1d0b000-b3f7a000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-12 22:01:05.349  6959  6959 W art     : b3f7a000-b3f7b000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-12 22:01:05.349  6959  6959 W art     : b3f7b000-b3f7c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b42ba000-b42e3000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 22:01:05.349  6959  6959 W art     : b42e3000-b4731000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-12 22:01:05.349  6959  6959 W art     : b4731000-b4732000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b4732000-b473c000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-12 22:01:05.349  6959  6959 W art     : b473c000-b473d000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-12 22:01:05.349  6959  6959 W art     : b473d000-b473f000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b473f000-b4740000 r--p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-12 22:01:05.349  6959  6959 W art     : b4850000-b4853000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-12 22:01:05.349  6959  6959 W art     : b4853000-b4854000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-12 22:01:05.349  6959  6959 W art     : b4854000-b4855000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-12 22:01:05.349  6959  6959 W art     : b4855000-b4856000 r--p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b4856000-b4876000 r--s 00000000 00:0b 6702       /dev/__properties__
08-12 22:01:05.349  6959  6959 W art     : b4876000-b5287000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-12 22:01:05.349  6959  6959 W art     : b5287000-b5288000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5288000-b52d1000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-12 22:01:05.349  6959  6959 W art     : b52d1000-b52d2000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-12 22:01:05.349  6959  6959 W art     : b52d2000-b52da000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b52da000-b52db000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b52db000-b5310000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-12 22:01:05.349  6959  6959 W art     : b5310000-b5311000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5311000-b5312000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-12 22:01:05.349  6959  6959 W art     : b5312000-b5313000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-12 22:01:05.349  6959  6959 W art     : b5313000-b536b000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-12 22:01:05.349  6959  6959 W art     : b536b000-b536c000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b536c000-b536d000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-12 22:01:05.349  6959  6959 W art     : b536d000-b536e000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-12 22:01:05.349  6959  6959 W art     : b536f000-b5375000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 22:01:05.349  6959  6959 W art     : b5375000-b5376000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 22:01:05.349  6959  6959 W art     : b5376000-b5377000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 22:01:05.349  6959  6959 W art     : b5377000-b5379000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b537a000-b5384000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 22:01:05.349  6959  6959 W art     : b5384000-b5387000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 22:01:05.349  6959  6959 W art     : b5387000-b5388000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 22:01:05.349  6959  6959 W art     : b5389000-b53a0000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 22:01:05.349  6959  6959 W art     : b53a0000-b53a1000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b53a1000-b53a2000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 22:01:05.349  6959  6959 W art     : b53a2000-b53a3000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 22:01:05.349  6959  6959 W art     : b53a4000-b53ae000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-12 22:01:05.349  6959  6959 W art     : b53ae000-b53af000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-12 22:01:05.349  6959  6959 W art     : b53af000-b53b0000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-12 22:01:05.349  6959  6959 W art     : b53b0000-b53b4000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 22:01:05.349  6959  6959 W art     : b53b4000-b53b5000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 22:01:05.349  6959  6959 W art     : b53b5000-b53b6000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 22:01:05.349  6959  6959 W art     : b53b6000-b53cc000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-12 22:01:05.349  6959  6959 W art     : b53cc000-b53cd000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-12 22:01:05.349  6959  6959 W art     : b53cd000-b53ce000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-12 22:01:05.349  6959  6959 W art     : b53ce000-b53db000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-12 22:01:05.349  6959  6959 W art     : b53db000-b53dc000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-12 22:01:05.349  6959  6959 W art     : b53dc000-b53dd000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-12 22:01:05.349  6959  6959 W art     : b53dd000-b543d000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
,08-12 22:01:05.349  6959  6959 W art     : b543d000-b5440000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-12 22:01:05.349  6959  6959 W art     : b5440000-b5444000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5444000-b54a5000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so,
08-12 22:01:05.349  6959  6959 W art     : b54a5000-b54a6000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-12 22:01:05.349  6959  6959 W art     : b54a6000-b54f5000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-12 22:01:05.349  6959  6959 W art     : b54f5000-b54f7000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-12 22:01:05.349  6959  6959 W art     : b54f7000-b54f8000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-12 22:01:05.349  6959  6959 W art     : b54f8000-b54f9000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b54f9000-b5500000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,08-12 22:01:05.349  6959  6959 W art     : b5500000-b5501000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 22:01:05.349  6959  6959 W art     : b5501000-b5502000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,08-12 22:01:05.349  6959  6959 W art     : b5503000-b5506000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 22:01:05.349  6959  6959 W art     : b5506000-b5507000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 22:01:05.349  6959  6959 W art     : b5507000-b5508000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 22:01:05.349  6959  6959 W art     : b5509000-b550d000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-12 22:01:05.349  6959  6959 W art     : b550d000-b550e000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b550e000-b550f000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-12 22:01:05.349  6959  6959 W art     : b550f000-b5510000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
,08-12 22:01:05.349  6959  6959 W art     : b5511000-b552e000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 22:01:05.349  6959  6959 W art     : b552e000-b552f000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 22:01:05.349  6959  6959 W art     : b552f000-b5530000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 22:01:05.349  6959  6959 W art     : b5531000-b5536000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 22:01:05.349  6959  6959 W art     : b5536000-b5537000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 22:01:05.349  6959  6959 W art     : b5537000-b5538000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 22:01:05.349  6959  6959 W art     : b5539000-b556a000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 22:01:05.349  6959  6959 W art     : b556a000-b556d000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 22:01:05.349  6959  6959 W art     : b556d000-b556e000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
,08-12 22:01:05.349  6959  6959 W art     : b556f000-b55aa000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-12 22:01:05.349  6959  6959 W art     : b55aa000-b55ab000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
,08-12 22:01:05.349  6959  6959 W art     : b55ab000-b55ac000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-12 22:01:05.349  6959  6959 W art     : b55ad000-b55b4000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-12 22:01:05.349  6959  6959 W art     : b55b4000-b55b5000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b55b5000-b55b6000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
,08-12 22:01:05.349  6959  6959 W art     : b55b6000-b55b7000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-12 22:01:05.349  6959  6959 W art     : b55b7000-b55b8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b55b8000-b55cf000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-12 22:01:05.349  6959  6959 W art     : b55cf000-b55d0000 ---p 00000000 00:00 0 ,
08-12 22:01:05.349  6959  6959 W art     : b55d0000-b55d3000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-12 22:01:05.349  6959  6959 W art     : b55d3000-b55d4000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
,08-12 22:01:05.349  6959  6959 W art     : b55d4000-b55f3000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-12 22:01:05.349  6959  6959 W art     : b55f3000-b55f4000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-12 22:01:05.349  6959  6959 W art     : b55f4000-b55f5000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so,
08-12 22:01:05.349  6959  6959 W art     : b55f5000-b5633000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-12 22:01:05.349  6959  6959 W art     : b5633000-b5634000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5634000-b5636000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-12 22:01:05.349  6959  6959 W art     : b5636000-b5637000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-12 22:01:05.349  6959  6959 W art     : b5638000-b563f000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 22:01:05.349  6959  6959 W art     : b563f000-b5640000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 22:01:05.349  6959  6959 W art     : b5640000-b5641000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
,08-12 22:01:05.349  6959  6959 W art     : b5642000-b5645000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 22:01:05.349  6959  6959 W art     : b5645000-b5646000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 22:01:05.349  6959  6959 W art     : b5646000-b5647000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
,08-12 22:01:05.349  6959  6959 W art     : b5647000-b564d000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 22:01:05.349  6959  6959 W art     : b564d000-b564e000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b564e000-b564f000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 22:01:05.349  6959  6959 W art     : b564f000-b5650000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 22:01:05.349  6959  6959 W art     : b5650000-b5659000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-12 22:01:05.349  6959  6959 W art     : b5659000-b565a000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-12 22:01:05.349  6959  6959 W art     : b565a000-b565b000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-12 22:01:05.349  6959  6959 W art     : b565b000-b56ec000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 22:01:05.349  6959  6959 W art     : b56ec000-b56ed000 ---p 00000000 00:00 0 ,
,08-12 22:01:05.349  6959  6959 W art     : b56ed000-b56f8000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 22:01:05.349  6959  6959 W art     : b56f8000-b56f9000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 22:01:05.349  6959  6959 W art     : b56fa000-b570c000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-12 22:01:05.349  6959  6959 W art     : b570c000-b570d000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-12 22:01:05.349  6959  6959 W art     : b570d000-b570e000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-12 22:01:05.349  6959  6959 W art     : b570f000-b5714000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
,08-12 22:01:05.349  6959  6959 W art     : b5714000-b5715000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-12 22:01:05.349  6959  6959 W art     : b5715000-b5716000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-12 22:01:05.349  6959  6959 W art     : b5717000-b5784000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-12 22:01:05.349  6959  6959 W art     : b5784000-b5785000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5785000-b5787000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-12 22:01:05.349  6959  6959 W art     : b5787000-b5788000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-12 22:01:05.349  6959  6959 W art     : b5788000-b5789000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 22:01:05.349  6959  6959 W art     : b5789000-b5790000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 22:01:05.349  6959  6959 W art     : b5790000-b5791000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 22:01:05.349  6959  6959 W art     : b5791000-b5792000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 22:01:05.349  6959  6959 W art     : b5793000-b5813000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 22:01:05.349  6959  6959 W art     : b5813000-b5814000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5814000-b5815000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 22:01:05.349  6959  6959 W art     : b5815000-b5816000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
,08-12 22:01:05.349  6959  6959 W art     : b5816000-b582d000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b582d000-b5864000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-12 22:01:05.349  6959  6959 W art     : ib/libqc-opt.so
08-12 22:01:05.349  6959  6959 W art     : b5864000-b5865000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 22:01:05.349  6959  6959 W art     : b5865000-b5866000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 22:01:05.349  6959  6959 W art     : b5866000-b5882000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 22:01:05.349  6959  6959 W art     : b5882000-b5883000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 22:01:05.349  6959  6959 W art     : b5883000-b5884000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 22:01:05.349  6959  6959 W art     : b5885000-b58e6000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-12 22:01:05.349  6959  6959 W art     : b58e6000-b58e8000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-12 22:01:05.349  6959  6959 W art     : b58e8000-b58e9000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-12 22:01:05.349  6959  6959 W art     : b58ea000-b5911000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-12 22:01:05.349  6959  6959 W art     : b5911000-b5912000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5912000-b5913000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-12 22:01:05.349  6959  6959 W art     : b5913000-b5914000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-12 22:01:05.349  6959  6959 W art     : b5915000-b591d000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 22:01:05.349  6959  6959 W art     : b591d000-b591f000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 22:01:05.349  6959  6959 W art     : b591f000-b5920000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 22:01:05.349  6959  6959 W art     : b5921000-b5924000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-12 22:01:05.349  6959  6959 W art     : b5924000-b5925000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-12 22:01:05.349  6959  6959 W art     : b5925000-b5926000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-12 22:01:05.349  6959  6959 W art     : b5926000-b592a000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-12 22:01:05.349  6959  6959 W art     : b592a000-b592b000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b592b000-b592c000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-12 22:01:05.349  6959  6959 W art     : b592c000-b592d000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-12 22:01:05.349  6959  6959 W art     : b592d000-b593d000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-12 22:01:05.349  6959  6959 W art     : b593d000-b593e000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-12 22:01:05.349  6959  6959 W art     : b593e000-b593f000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-12 22:01:05.349  6959  6959 W art     : b593f000-b5985000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5985000-b598e000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-12 22:01:05.349  6959  6959 W art     : b598e000-b598f000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-12 22:01:05.349  6959  6959 W art     : b598f000-b5990000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-12 22:01:05.349  6959  6959 W art     : b5991000-b5996000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-12 22:01:05.349  6959  6959 W art     : b5996000-b5997000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-12 22:01:05.349  6959  6959 W art     : b5997000-b5998000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-12 22:01:05.349  6959  6959 W art     : b5998000-b599b000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 22:01:05.349  6959  6959 W art     : b599b000-b599c000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b599c000-b599d000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 22:01:05.349  6959  6959 W art     : b599d000-b599e000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 22:01:05.349  6959  6959 W art     : b599f000-b59b7000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 22:01:05.349  6959  6959 W art     : b59b7000-b59b8000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b59b8000-b59b9000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 22:01:05.349  6959  6959 W art     : b59b9000-b59ba000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 22:01:05.349  6959  6959 W art     : b59bb000-b5b55000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-12 22:01:05.349  6959  6959 W art     : b5b55000-b5b56000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5b56000-b5b63000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-12 22:01:05.349  6959  6959 W art     : b5b63000-b5b64000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-12 22:01:05.349  6959  6959 W art     : b5b64000-b5b68000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-12 22:01:05.349  6959  6959 W art     : b5b68000-b5b69000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5b69000-b5b6a000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-12 22:01:05.349  6959  6959 W art     : b5b6a000-b5b6b000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-12 22:01:05.349  6959  6959 W art     : b5b6b000-b5b7e000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-12 22:01:05.349  6959  6959 W art     : b5b7e000-b5b7f000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-12 22:01:05.349  6959  6959 W art     : b5b7f000-b5b80000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-12 22:01:05.349  6959  6959 W art     : b5b81000-b5bcc000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-12 22:01:05.349  6959  6959 W art     : b5bcc000-b5bcd000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-12 22:01:05.349  6959  6959 W art     : b5bcd000-b5bce000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-12 22:01:05.349  6959  6959 W art     : b5bce000-b5bd0000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5bd0000-b5bd1000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 22:01:05.349  6959  6959 W art     : b5bd1000-b5be2000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 22:01:05.349  6959  6959 W art     : b5be2000-b5be3000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5be3000-b5be4000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 22:01:05.349  6959  6959 W art     : b5be4000-b5be5000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 22:01:05.349  6959  6959 W art     : b5be6000-b5bf0000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-12 22:01:05.349  6959  6959 W art     : b5bf0000-b5bf2000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-12 22:01:05.349  6959  6959 W art     : b5bf2000-b5bf3000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-12 22:01:05.349  6959  6959 W art     : b5bf3000-b5c0c000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-12 22:01:05.349  6959  6959 W art     : b5c0c000-b5c0d000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-12 22:01:05.349  6959  6959 W art     : b5c0d000-b5c10000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-12 22:01:05.349  6959  6959 W art     : b5c10000-b5c14000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5c14000-b5c88000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-12 22:01:05.349  6959  6959 W art     : b5c88000-b5c89000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5c89000-b5c8c000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-12 22:01:05.349  6959  6959 W art     : b5c8c000-b5c8d000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-12 22:01:05.349  6959  6959 W art     : b5c8e000-b5c91000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-12 22:01:05.349  6959  6959 W art     : b5c91000-b5c92000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-12 22:01:05.349  6959  6959 W art     : b5c92000-b5c93000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-12 22:01:05.349  6959  6959 W art     : b5c93000-b5c94000 r--p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5c94000-b5c99000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 22:01:05.349  6959  6959 W art     : b5c99000-b5c9a000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 22:01:05.349  6959  6959 W art     : b5c9a000-b5c9b000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 22:01:05.349  6959  6959 W art     : b5c9b000-b5c9c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b5c9c000-b5c9f000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 22:01:05.349  6959  6959 W art     : b5c9f000-b5ca0000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 22:01:05.349  6959  6959 W art     : b5ca0000-b5ca1000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 22:01:05.349  6959  6959 W art     : b5ca1000-b5ca2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b5ca2000-b5ca6000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-12 22:01:05.349  6959  6959 W art     : b5ca6000-b5ca7000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-12 22:01:05.349  6959  6959 W art     : b5ca7000-b5ca8000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-12 22:01:05.349  6959  6959 W art     : b5ca8000-b5ca9000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 22:01:05.349  6959  6959 W art     : b5ca9000-b5cad000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 22:01:05.349  6959  6959 W art     : b5cad000-b5cae000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 22:01:05.349  6959  6959 W art     : b5cae000-b5caf000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 22:01:05.349  6959  6959 W art     : b5caf000-b5cb0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b5cb0000-b5cbe000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-12 22:01:05.349  6959  6959 W art     : b5cbe000-b5cbf000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b5cbf000-b5cc0000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-12 22:01:05.349  6959  6959 W art     : b5cc0000-b5cc1000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-12 22:01:05.349  6959  6959 W art     : b5cc1000-b5ccb000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 22:01:05.349  6959  6959 W art     : b5ccb000-b5cce000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 22:01:05.349  6959  6959 W art     : b5cce000-b5ccf000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 22:01:05.349  6959  6959 W art     : b5ccf000-b5cd0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b5cd0000-b5cda000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-12 22:01:05.349  6959  6959 W art     : b5cda000-b5cdd000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-12 22:01:05.349  6959  6959 W art     : b5cdd000-b5cde000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-12 22:01:05.349  6959  6959 W art     : b5cde000-b5ce2000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-12 22:01:05.349  6959  6959 W art     : b5ce2000-b5ce3000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-12 22:01:05.349  6959  6959 W art     : b5ce3000-b5ce4000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-12 22:01:05.349  6959  6959 W art     : b5ce4000-b5ce5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b5ce5000-b5cf2000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-12 22:01:05.349  6959  6959 W art     : b5cf2000-b5cf4000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-12 22:01:05.349  6959  6959 W art     : b5cf4000-b5cf5000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-12 22:01:05.349  6959  6959 W art     : b5cf5000-b6107000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-12 22:01:05.349  6959  6959 W art     : b6107000-b6108000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6108000-b6111000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-12 22:01:05.349  6959  6959 W art     : b6111000-b6115000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-12 22:01:05.349  6959  6959 W art     : b6115000-b6116000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6116000-b611d000 r-xp 00000000 b3:17 2571       /system/lib/libaud
08-12 22:01:05.349  6959  6959 W art     : ioutils.so
08-12 22:01:05.349  6959  6959 W art     : b611d000-b611e000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-12 22:01:05.349  6959  6959 W art     : b611e000-b611f000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-12 22:01:05.349  6959  6959 W art     : b611f000-b6120000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b6120000-b613b000 r-xp 00000000
08-12 22:01:05.349  6959  6959 W art     :  b3:17 1184       /system/lib/libz.so
08-12 22:01:05.349  6959  6959 W art     : b613b000-b613c000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-12 22:01:05.349  6959  6959 W art     : b613c000-b613d000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-12 22:01:05.349  6959  6959 W art     : b613d000-b613e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b613e000-b618a000 r-xp 00000000 b3:17 994        
08-12 22:01:05.349  6959  6959 W art     : /system/lib/libharfbuzz_ng.so
08-12 22:01:05.349  6959  6959 W art     : b618a000-b618b000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b618b000-b618c000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 22:01:05.349  6959  6959 W art     : b618c000-b618d000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 22:01:05.349  6959  6959 W art     : b618d000-b618e000 r--p 00000000 00:00 0          [anon:li
08-12 22:01:05.349  6959  6959 W art     : nker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b618e000-b6192000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-12 22:01:05.349  6959  6959 W art     : b6192000-b6193000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6193000-b6194000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-12 22:01:05.349  6959  6959 W art     : b6194000-b6195000 rw-p 00005000 b3:17 2681       /system/lib/libu
08-12 22:01:05.349  6959  6959 W art     : sbhost.so
08-12 22:01:05.349  6959  6959 W art     : b6195000-b61cd000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-12 22:01:05.349  6959  6959 W art     : b61cd000-b61ce000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-12 22:01:05.349  6959  6959 W art     : b61ce000-b61cf000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-12 22:01:05.349  6959  6959 W art     : b61cf000-b61d0000 r--p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     :          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b61d0000-b626e000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-12 22:01:05.349  6959  6959 W art     : b626e000-b626f000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b626f000-b628d000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-12 22:01:05.349  6959  6959 W art     : b628d000-b628e000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
08-12 22:01:05.349  6959  6959 W art     : .so
08-12 22:01:05.349  6959  6959 W art     : b628e000-b6401000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-12 22:01:05.349  6959  6959 W art     : b6401000-b640c000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-12 22:01:05.349  6959  6959 W art     : b640c000-b640d000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-12 22:01:05.349  6959  6959 W art     : b640d000-b6524000 r-xp 00000000
08-12 22:01:05.349  6959  6959 W art     :  b3:17 2041       /system/lib/libicuuc.so
08-12 22:01:05.349  6959  6959 W art     : b6524000-b652f000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-12 22:01:05.349  6959  6959 W art     : b652f000-b6530000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-12 22:01:05.349  6959  6959 W art     : b6530000-b6534000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6534000-b6558000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
08-12 22:01:05.349  6959  6959 W art     : o
08-12 22:01:05.349  6959  6959 W art     : b6558000-b655a000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-12 22:01:05.349  6959  6959 W art     : b655a000-b655b000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-12 22:01:05.349  6959  6959 W art     : b655b000-b6601000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-12 22:01:05.349  6959  6959 W art     : b6601000-b660e000 r--p 000a5000 b3:17 13
08-12 22:01:05.349  6959  6959 W art     : 2        /system/lib/libcrypto.so
08-12 22:01:05.349  6959  6959 W art     : b660e000-b660f000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-12 22:01:05.349  6959  6959 W art     : b660f000-b6610000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6610000-b6663000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-12 22:01:05.349  6959  6959 W art     : b6663000-b6664000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6664000-b6665000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-12 22:01:05.349  6959  6959 W art     : b6665000-b6666000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-12 22:01:05.349  6959  6959 W art     : b6666000-b666b000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b666b000-b667d000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-12 22:01:05.349  6959  6959 W art     : b667d000-b667e000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b667e000-b667f000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-12 22:01:05.349  6959  6959 W art     : b667f000-b6680000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-12 22:01:05.349  6959  6959 W art     : b6680000-b6687000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 22:01:05.349  6959  6959 W art     : b6687000-b6688000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 22:01:05.349  6959  6959 W art     : b6688000-b6689000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 22:01:05.349  6959  6959 W art     : b6689000-b668a000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b668a000-b668d000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-12 22:01:05.349  6959  6959 W art     : b668d000-b668e000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
,08-12 22:01:05.349  6959  6959 W art     : b668e000-b668f000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-12 22:01:05.349  6959  6959 W art     : b668f000-b6693000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-12 22:01:05.349  6959  6959 W art     : b6693000-b6694000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-12 22:01:05.349  6959  6959 W art     : b6694000-b6695000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-12 22:01:05.349  6959  6959 W art     : b6695000-b66a3000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-12 22:01:05.349  6959  6959 W art     : b66a3000-b66a4000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b66a4000-b66a5000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-12 22:01:05.349  6959  6959 W art     : b66a5000-b66a6000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-12 22:01:05.349  6959  6959 W art     : b66a6000-b66af000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 22:01:05.349  6959  6959 W art     : b66af000-b66b0000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 22:01:05.349  6959  6959 W art     : b66b0000-b66b1000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 22:01:05.349  6959  6959 W art     : b66b1000-b6717000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-12 22:01:05.349  6959  6959 W art     : b6717000-b6718000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6718000-b671a000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-12 22:01:05.349  6959  6959 W art     : b671a000-b6723000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-12 22:01:05.349  6959  6959 W art     : b6723000-b6726000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6726000-b67bd000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-12 22:01:05.349  6959  6959 W art     : b67bd000-b67bf000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-12 22:01:05.349  6959  6959 W art     : b67bf000-b67c0000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-12 22:01:05.349  6959  6959 W art     : b67c0000-b67c1000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b67c1000-b6ae2000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-12 22:01:05.349  6959  6959 W art     : b6ae2000-b6ae3000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6ae3000-b6afe000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-12 22:01:05.349  6959  6959 W art     : b6afe000-b6b02000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-12 22:01:05.349  6959  6959 W art     : b6b02000-b6b07000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6b07000-b6b0f000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 22:01:05.349  6959  6959 W art     : b6b0f000-b6b10000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 22:01:05.349  6959  6959 W art     : b6b10000-b6b11000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 22:01:05.349  6959  6959 W art     : b6b11000-b6b3f000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-12 22:01:05.349  6959  6959 W art     : b6b3f000-b6b40000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6b40000-b6b47000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-12 22:01:05.349  6959  6959 W art     : b6b47000-b6b48000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-12 22:01:05.349  6959  6959 W art     : b6b48000-b6b8e000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-12 22:01:05.349  6959  6959 W art     : b6b8e000-b6b8f000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6b8f000-b6b92000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-12 22:01:05.349  6959  6959 W art     : b6b92000-b6b93000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-12 22:01:05.349  6959  6959 W art     : b6b93000-b6bae000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-12 22:01:05.349  6959  6959 W art     : b6bae000-b6bb2000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-12 22:01:05.349  6959  6959 W art     : b6bb2000-b6bb3000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-12 22:01:05.349  6959  6959 W art     : b6bb3000-b6c00000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-12 22:01:05.349  6959  6959 W art     : b6c00000-b6c01000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6c01000-b6c0d000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-12 22:01:05.349  6959  6959 W art     : b6c0d000-b6c0e000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-12 22:01:05.349  6959  6959 W art     : b6c0e000-b6c1b000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-12 22:01:05.349  6959  6959 W art     : b6c1b000-b6c1c000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6c1c000-b6c1d000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-12 22:01:05.349  6959  6959 W art     : b6c1d000-b6c1e000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-12 22:01:05.349  6959  6959 W art     : b6c1e000-b6c26000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-12 22:01:05.349  6959  6959 W art     : b6c26000-b6c27000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6c27000-b6c28000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-12 22:01:05.349  6959  6959 W art     : b6c28000-b6c29000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-12 22:01:05.349  6959  6959 W art     : b6c29000-b6c30000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-12 22:01:05.349  6959  6959 W art     : b6c30000-b6c31000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-12 22:01:05.349  6959  6959 W art     : b6c31000-b6c32000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-12 22:01:05.349  6959  6959 W art     : b6c32000-b6c46000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-12 22:01:05.349  6959  6959 W art     : b6c46000-b6c48000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-12 22:01:05.349  6959  6959 W art     : b6c48000-b6c49000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-12 22:01:05.349  6959  6959 W art     : b6c49000-b6c71000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-12 22:01:05.349  6959  6959 W art     : b6c71000-b6c73000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-12 22:01:05.349  6959  6959 W art     : b6c73000-b6c74000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-12 22:01:05.349  6959  6959 W art     : b6c74000-b6c77000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-12 22:01:05.349  6959  6959 W art     : b6c77000-b6c78000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-12 22:01:05.349  6959  6959 W art     : b6c78000-b6c79000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-12 22:01:05.349  6959  6959 W art     : b6c79000-b6c82000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-12 22:01:05.349  6959  6959 W art     : b6c82000-b6c83000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-12 22:01:05.349  6959  6959 W art     : b6c83000-b6c84000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-12 22:01:05.349  6959  6959 W art     : b6c84000-b6ca4000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-12 22:01:05.349  6959  6959 W art     : b6ca4000-b6ca5000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-12 22:01:05.349  6959  6959 W art     : b6ca5000-b6ca6000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-12 22:01:05.349  6959  6959 W art     : b6ca6000-b6d19000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-12 22:01:05.349  6959  6959 W art     : b6d19000-b6d1d000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-12 22:01:05.349  6959  6959 W art     : b6d1d000-b6d20000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-12 22:01:05.349  6959  6959 W art     : b6d20000-b6d2a000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6d2a000-b6db2000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-12 22:01:05.349  6959  6959 W art     : b6db2000-b6db3000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6db3000-b6db7000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-12 22:01:05.349  6959  6959 W art     : b6db7000-b6db8000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-12 22:01:05.349  6959  6959 W art     : b6db8000-b6db9000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6db9000-b6de2000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-12 22:01:05.349  6959  6959 W art     : b6de2000-b6de3000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6de3000-b6de6000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-12 22:01:05.349  6959  6959 W art     : b6de6000-b6de7000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-12 22:01:05.349  6959  6959 W art     : b6de7000-b6ec1000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 22:01:05.349  6959  6959 W art     : b6ec1000-b6ec8000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 22:01:05.349  6959  6959 W art     : b6ec8000-b6ed0000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 22:01:05.349  6959  6959 W art     : b6ed0000-b6ed1000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6ed1000-b6ed2000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 22:01:05.349  6959  6959 W art     : b6ed2000-b6ed3000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-12 22:01:05.349  6959  6959 W art     : b6ed3000-b6ed4000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b6ed4000-b6ed7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b6ed7000-b6efc000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-12 22:01:05.349  6959  6959 W art     : b6efc000-b6efd000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6efd000-b6f04000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-12 22:01:05.349  6959  6959 W art     : b6f04000-b6f05000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-12 22:01:05.349  6959  6959 W art     : b6f05000-b6f0c000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-12 22:01:05.349  6959  6959 W art     : b6f0c000-b6f0d000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-12 22:01:05.349  6959  6959 W art     : b6f0d000-b6f0e000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-12 22:01:05.349  6959  6959 W art     : b6f0e000-b6f0f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b6f0f000-b6f27000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-12 22:01:05.349  6959  6959 W art     : b6f27000-b6f28000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6f28000-b6f29000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-12 22:01:05.349  6959  6959 W art     : b6f29000-b6f2a000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-12 22:01:05.349  6959  6959 W art     : b6f2a000-b6f38000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-12 22:01:05.349  6959  6959 W art     : b6f38000-b6f39000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6f39000-b6f3a000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-12 22:01:05.349  6959  6959 W art     : b6f3a000-b6f3b000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-12 22:01:05.349  6959  6959 W art     : b6f3b000-b6f3c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 22:01:05.349  6959  6959 W art     : b6f3c000-b6f3e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b6f3e000-b6f3f000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b6f3f000-b6f40000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 22:01:05.349  6959  6959 W art     : b6f40000-b6f41000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-12 22:01:05.349  6959  6959 W art     : b6f41000-b6f42000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:01:05.349  6959  6959 W art     : b6f42000-b6f62000 r--s 00000000 00:0b 6702       /dev/__properties__
08-12 22:01:05.349  6959  6959 W art     : b6f62000-b6f63000 r--p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6f63000-b6f64000 ---p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6f64000-b6f66000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-12 22:01:05.349  6959  6959 W art     : b6f66000-b6f67000 r-xp 00000000 00:00 0          [sigpage]
08-12 22:01:05.349  6959  6959 W art     : b6f67000-b6f82000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-12 22:01:05.349  6959  6959 W art     : b6f82000-b6f83000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-12 22:01:05.349  6959  6959 W art     : b6f83000-b6f85000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-12 22:01:05.349  6959  6959 W art     : b6f85000-b6f87000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : b6f87000-b6f8c000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-12 22:01:05.349  6959  6959 W art     : b6f8c000-b6f8d000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-12 22:01:05.349  6959  6959 W art     : b6f8d000-b6f8e000 rw-p 00000000 00:00 0 
08-12 22:01:05.349  6959  6959 W art     : be93f000-be960000 rw-p 00000000 00:00 0          [stack]
08-12 22:01:05.349  6959  6959 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-12 22:01:05.399  6959  6959 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 22:01:05.449  6959  6959 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 22:01:05.459  6959  6959 E AffinityControl: AffinityControl: registerfunction enter,
,08-12 22:01:05.479  6959  6959 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 22:01:05.489   753  1745 D PackageManager: START PACKAGE DELETE: observer{167098766}
08-12 22:01:05.489   753  1745 D PackageManager: pkg{<packageName>}
08-12 22:01:05.489   753  1745 D PackageManager: user{0}
08-12 22:01:05.489   753  1745 D PackageManager: caller{2000}
08-12 22:01:05.489   753  1745 D PackageManager: flags{2}
08-12 22:01:05.489   753  1745 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-12 22:01:05.489   753  1745 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-12 22:01:05.499   753  1745 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-12 22:01:05.499   753  1745 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-12 22:01:05.499   753  1745 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-12 22:01:05.499   753   917 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-12 22:01:05.499   753   917 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-12 22:01:05.499   753   917 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-12 22:01:05.499   753   917 D ApplicationPolicy: getApplicationUninstallationEnabled
08-12 22:01:05.499   753   917 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-12 22:01:05.499   753   917 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-12 22:01:05.499   753   917 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-12 22:01:05.499   753   917 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-12 22:01:05.499   753   917 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-12 22:01:05.499   753   917 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-12 22:01:05.499   753   822 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-12 22:01:05.499   753   822 I ActivityManager: Killing 6336:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
,08-12 22:01:05.529   753   917 D AASAinstall: there is not AASApackages.xml file
,08-12 22:01:05.559   753  1745 D GraphicsStats: Buffer count: 4
,08-12 22:01:05.559   753  2219 I WindowState: WIN DEATH: Window{b11dd19 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 22:01:05.559   753   765 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@dfd75af)
,08-12 22:01:05.559   753  1327 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 22:01:05.559   753  1327 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 22:01:05.559   292   355 I SurfaceFlinger: id=20 Removed NainActivit (4/10)
,08-12 22:01:05.569   292  1851 I SurfaceFlinger: id=20 Removed NainActivit (-2/10)
08-12 22:01:05.569   753  1327 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 22:01:05.569   292  1683 I SurfaceFlinger: id=20 Removed NainActivit (-2/10)
,08-12 22:01:05.579   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbebec3a4
,08-12 22:01:05.829   753   917 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-12 22:01:05.919   753   917 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-12 22:01:05.919   753   822 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 22:01:05.919   753   822 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-12 22:01:05.929   753   822 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-12 22:01:05.929   331   331 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-12 22:01:05.929   753   917 I art     : Starting a blocking GC Explicit
,08-12 22:01:05.929   753   822 E ActivityManager: Failure starting process com.test.thalitest
08-12 22:01:05.929   753   822 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-12 22:01:05.929   753   822 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5273)
08-12 22:01:05.929   753   822 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5190)
08-12 22:01:05.929   753   822 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5028)
08-12 22:01:05.929   753   822 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2639)
08-12 22:01:05.929   753   822 E ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:2338)
08-12 22:01:05.929   753   822 E ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:2215)
08-12 22:01:05.929   753   822 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.ensureActivitiesVisibleLocked(ActivityStackSupervisor.java:6684)
08-12 22:01:05.929   753   822 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7381)
08-12 22:01:05.929   753   822 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9142)
08-12 22:01:05.929   753   822 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8765)
08-12 22:01:05.929   753   822 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8920)
08-12 22:01:05.929   753   822 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:461)
08-12 22:01:05.929   753   822 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2597)
08-12 22:01:05.929   753   822 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:01:05.929   753   822 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
08-12 22:01:05.929   753   822 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 22:01:05.929   753   822 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-12 22:01:05.929   753   822 I ActivityManager:   Force finishing activity ActivityRecord{2b731e8 u0 com.test.thalitest/.MainActivity t167}
,08-12 22:01:06.059   753   917 I art     : Explicit concurrent mark sweep GC freed 125159(7MB) AllocSpace objects, 117(2MB) LOS objects, 27% free, 41MB/57MB, paused 1.509ms total 122.833ms
,08-12 22:01:06.089   753   917 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 22:01:06.089   753   917 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-12 22:01:06.089   753   917 D AASAinstall: there is not AASApackages.xml file
08-12 22:01:06.089   753   917 D PackageManager: result of delete: 1{167098766}
,08-12 22:01:06.089  6959  6959 I art     : System.exit called, status: 0
08-12 22:01:06.089  6959  6959 I AndroidRuntime: VM exiting with result code 0.
08-12 22:01:06.099   753   917 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-12 22:01:06.099   753   917 D PackageManager: userId{-1}
08-12 22:01:06.099   753   917 D PackageManager: andCode{true}
,08-12 22:01:06.109   753   917 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-12 22:01:06.119  6107  6982 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-12 22:01:06.119  6107  6982 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-12 22:01:06.129  6107  6982 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-12 22:01:06.179   753   822 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-12 22:01:06.179   753   822 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 22:01:06.179   753   822 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-12 22:01:06.189   753   753 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.189   753   753 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.199   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.199   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.199   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.199  1373  1373 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,08-12 22:01:06.199  1373  1373 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-12 22:01:06.209   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.209   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.209   753   877 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.209   753   877 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.209   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.209   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 22:01:06.209   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 22:01:06.209   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.209   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.209   753   753 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.219   753  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 22:01:06.219  1995  1995 E SamsungIME: mOCRHelper is null
,08-12 22:01:06.219   753   753 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.219   753   753 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.219  2103  2586 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 22:01:06.229   753   753 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.229   753   753 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.229   753   815 W System.err: remove failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml
08-12 22:01:06.229   753   753 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-12 22:01:06.229   753   753 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.229   753   815 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml.bak -> /data/system/users/0/runtime-permissions.xml
,08-12 22:01:06.229   753   753 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.229   753   753 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.229   753   753 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.229   753   753 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 22:01:06.229   753   753 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.229   753   753 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.239   753   822 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{da4edec u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81838ec 4321:com.samsung.klmsagent/u0a18}
,08-12 22:01:06.239  1711  1711 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 22:01:06.239   753   753 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.249  4321  4321 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Fri Aug 12 22:01:06 GMT+02:00 2016
,08-12 22:01:06.249   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.249   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.249   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.259  3196  3211 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 22:01:06.259  3196  3211 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 22:01:06.259  3196  3211 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 22:01:06.259  3196  3211 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 22:01:06.259   753  1799 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-12 22:01:06.259  4321  4321 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-12 22:01:06.259   753   815 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.269  4321  4321 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-12 22:01:06.269  4321  4321 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-12 22:01:06.269  4321  4321 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-12 22:01:06.269   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-12 22:01:06.269   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.269   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-12 22:01:06.269   753   753 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 22:01:06.269  4321  6999 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-12 22:01:06.269  4321  6999 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-12 22:01:06.269  4321  6999 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
,08-12 22:01:06.269  4321  6999 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-12 22:01:06.269  4321  6999 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-12 22:01:06.269  4321  6999 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-12 22:01:06.269   753  1318 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
08-12 22:01:06.269   753  1318 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-12 22:01:06.269   753  1317 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-12 22:01:06.269   753  1317 D NtpTrustedTime: currentTimeMillis() cache hit
08-12 22:01:06.269   753  1317 V NetworkStats: performPollLocked(flags=0x3)
,08-12 22:01:06.269  4321  6999 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-12 22:01:06.279   753  2227 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{da4edec u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{add8fe1 753:system/1000}
08-12 22:01:06.279   753  1317 D NtpTrustedTime: currentTimeMillis() cache hit
08-12 22:01:06.279   753  1317 V NetworkStats: performPollLocked() took 6ms
,08-12 22:01:06.279   753  1317 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ce50c39 in tid 1317 (NetworkStats)
,08-12 22:01:06.279  4321  6999 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-12 22:01:06.279   753  1362 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/167_task.xml
08-12 22:01:06.279  2112  2112 E audit_log: File locking failed. error= Bad file descriptor
,08-12 22:01:06.279  2112  2112 E audit_log: File locking failed. error= Bad file descriptor
,08-12 22:01:06.289  4321  6999 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x727febe6 in tid 6999 (IntentService[K)
,08-12 22:01:06.289  4321  6999 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 22:01:06.289  2112  2112 E audit_log: File locking failed. error= Bad file descriptor
,08-12 22:01:06.349   350   350 I Zygote  : Process 4321 exited due to signal (7)
,08-12 22:01:06.369   329   329 E installd: eof
08-12 22:01:06.369   329   329 E installd: failed to read size
08-12 22:01:06.369   329   329 I installd: closing connection
,08-12 22:01:06.369   291   291 I ServiceManager: service 'sb_service' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'servicediscovery' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'updatelock' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'notification' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'devicestoragemonitor' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'location' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'country_detector' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'sec_location' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'search' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'execute' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'dropbox' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'wallpaper' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'audio' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'DockObserver' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'midi' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'usb' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'serial' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'kiesusb' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'jobscheduler' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'backup' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'appwidget' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'voiceinteraction' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'SecExternalDisplayService' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'diskstats' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'mDNIe' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'AAS' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'MSCS' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'spengestureservice' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'quickconnect' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'samplingprofiler' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'commontime_management' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'dreams' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'graphicsstats' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'print' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'restrictions' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'media_session' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'media_router' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'sec_analytics' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'telecom' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'otp_service' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'enterprise_shared_device_policy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'knox_timakeystore_policy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'enterprise_policy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'statusbar' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'clipboard' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'clipboardEx' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'network_management' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'trust' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'fingerprint' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'ABTPersistenceService' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'textservices' died
08-12 22:01:06.369  1373  1398 W Sensors : sensorser,vice died [0xacebacc0]
08-12 22:01:06.369   291   291 I ServiceManager: service 'network_score' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'netstats' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'netpolicy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'wifip2p' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'wifi' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'wifihs20' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'wifiscanner' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'rttmanager' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'ethernet' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'connectivity' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'knox_ccm_policy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'enterprise_license_policy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'application_policy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'wifi_policy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'phone_restriction_policy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'remoteinjection' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'knox_ucsm_policy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'edm_proxy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'mum_container_policy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'enterprise_billing_policy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'edmnativehelper' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'lpnet' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'imms' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'user' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'procstats' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'meminfo' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'gfxinfo' died
08-12 22:01:06.369   325   976 W AudioFlinger: power manager service died !!!
08-12 22:01:06.369   291   291 I ServiceManager: service 'dbinfo' died
08-12 22:01:06.369   325   976 W AudioFlinger: power manager service died !!!
08-12 22:01:06.369   291   291 I ServiceManager: service 'cpuinfo' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'permission' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'processinfo' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'sensorservice' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'mdm.remotedesktop' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'battery' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'usagestats' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'webviewupdate' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'scheduling_policy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'telephony.registry' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'persona' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'launcherapps' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'voip' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'persona_policy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'alarm' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'context_aware' died
,08-12 22:01:06.369   291   291 I ServiceManager: service 'scontext' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'barbeam' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'multiwindow_facade' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'window' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'input' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'bluetooth_manager' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'rcp' died
,08-12 22:01:06.369   291   291 I ServiceManager: service 'input_method' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'accessibility' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'cover' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'mount' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'lock_settings' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'deviceidle' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'device_policy' died
,08-12 22:01:06.369   291   291 I ServiceManager: service 'harmony_eas_service' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'sdp' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'sdp_log' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'dlp' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'log_manager_service' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'package' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'activity' died
,08-12 22:01:06.369   291   291 I ServiceManager: service 'SEAMService' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'media.camera.proxy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'account' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'content' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'DirEncryptService' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'LSManager' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'ReactiveService' died
,08-12 22:01:06.369   291   291 I ServiceManager: service 'DeviceRootKeyService' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'EngineeringModeService' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'SatsService' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'sedenial' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'vibrator' died
08-12 22:01:06.379  2112  2112 E audit_log: File locking failed. error= Bad file descriptor
,08-12 22:01:06.369   291   291 I ServiceManager: service 'tw_toolbox' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'tima' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'iccc' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'cepproxyks' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'emailksproxy' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'CustomFrequencyManagerService' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'consumer_ir' died
,08-12 22:01:06.369   291   291 I ServiceManager: service 'uimode' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'batterystats' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'appops' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'power' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'display' died
08-12 22:01:06.369   291   291 I ServiceManager: service 'media_projection' died
08-12 22:01:06.369  2158  2190 W Sensors : sensorservice died [0xad7ffd80]
08-12 22:01:06.369  1721  1735 W Sensors : sensorservice died [0xad7e6880]
08-12 22:01:06.369  2841  2852 W Sensors : sensorservice died [0xad7fcb40]
,08-12 22:01:06.379  1373  1628 E WifiManager: Channel connection lost
08-12 22:01:06.379  1700  1700 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2be5e76 in tid 1700 (com.android.nfc)
08-12 22:01:06.379  2103  2148 W Sensors : sensorservice died [0xad763cc0]
08-12 22:01:06.379  1700  1700 F libc    : Unable to open connection to debuggerd: Connection refused
08-12 22:01:06.379  2103  2582 E WifiManager: Channel connection lost
08-12 22:01:06.379  1711  1711 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
,08-12 22:01:06.379  1711  2509 E WifiManager: Channel connection lost
08-12 22:01:06.379  2841  3165 E WifiManager: Channel connection lost
08-12 22:01:06.379   292   355 D libEGL  : eglTerminate EGLDisplay = 0xb65bf6fc
,08-12 22:01:06.379  3196  3211 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x732d3a98 in tid 3211 (AccountChangeLi)
08-12 22:01:06.379   292   355 I SurfaceFlinger: restart the boot-animation @ binderDied
08-12 22:01:06.379   292   292 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a24000
08-12 22:01:06.379   292   292 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
,08-12 22:01:06.379  1884  1897 W Sensors : sensorservice died [0xad7ffec0]
,08-12 22:01:06.389  2096  2096 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ec88c64 in tid 2096 (droid.bluetooth)
,08-12 22:01:06.389  3196  3211 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 22:01:06.389  2096  2096 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 22:01:06.389  2112  2112 E audit_log: File locking failed. error= Bad file descriptor
,08-12 22:01:06.389  2112  2112 E audit_log: File locking failed. error= Bad file descriptor
,08-12 22:01:06.399   292   344 I SurfaceFlinger: id=2 Removed GocusedStac (4/9)
,08-12 22:01:06.399   292   344 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/8)
08-12 22:01:06.399   292   344 I SurfaceFlinger: id=4 Removed EimLayer(An (0/7)
08-12 22:01:06.399   292   344 I SurfaceFlinger: id=14 Removed EimLayer(Di (3/6)
08-12 22:01:06.399   292   344 I SurfaceFlinger: id=15 Removed EimLayer(An (0/5)
08-12 22:01:06.399   292   344 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
08-12 22:01:06.399   292   344 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/5)
08-12 22:01:06.399   292   344 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/5)
08-12 22:01:06.399   292   344 I SurfaceFlinger: id=21 Removed VSBConnecti (2/4)
08-12 22:01:06.399   292   344 I SurfaceFlinger: id=22 Removed VSBConnecti (1/3)
08-12 22:01:06.399   292  1683 I SurfaceFlinger: id=5 Removed TtatusBar (1/2)
08-12 22:01:06.399   292  1683 I SurfaceFlinger: id=5 Removed TtatusBar (-2/2)
08-12 22:01:06.399   292  1683 I SurfaceFlinger: id=7 Removed JmageWallpa (0/1)
08-12 22:01:06.399   292  1683 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/1)
,08-12 22:01:06.399   292  1851 I SurfaceFlinger: id=14 Removed EimLayer(Di (-2/1)
08-12 22:01:06.399   292  1851 I SurfaceFlinger: id=15 Removed EimLayer(An (-2/1)
08-12 22:01:06.399   292  1851 I SurfaceFlinger: id=18 Removed DolorFade (0/0)
08-12 22:01:06.399   292  1851 I SurfaceFlinger: id=18 Removed DolorFade (-2/0)
08-12 22:01:06.399   292  1851 I SurfaceFlinger: id=21 Removed VSBConnecti (-2/0)
08-12 22:01:06.399   292  1851 I SurfaceFlinger: id=22 Removed VSBConnecti (-2/0)
,08-12 22:01:06.409  1826  1985 E WifiManager: Channel connection lost
,08-12 22:01:06.409  5733  5792 E WifiManager: Channel connection lost
,08-12 22:01:06.419  2841  2841 D BluetoothPbap: Proxy object disconnected
,08-12 22:01:06.419  2841  2841 D PbapServerProfile: Bluetooth service disconnected
08-12 22:01:06.419  2150  2150 D BluetoothA2dp: Proxy object disconnected
08-12 22:01:06.419  2841  2841 D BluetoothSap: Proxy object disconnected
,08-12 22:01:06.419  2841  2841 D SapProfile: Bluetooth service disconnected
,08-12 22:01:06.419  2841  2841 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b933e7c in tid 2841 (ndroid.settings)
,08-12 22:01:06.419  2841  2841 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 22:01:06.419  2112  2112 E audit_log: File locking failed. error= Bad file descriptor
,08-12 22:01:06.419   291   291 I ServiceManager: service 'nfc' died
08-12 22:01:06.419   291   291 I ServiceManager: service 'secontroller' died
08-12 22:01:06.419   291   291 I ServiceManager: service 'nfccontroller' died
,08-12 22:01:06.429   350   350 I Zygote  : Process 3196 exited due to signal (7)
,08-12 22:01:06.469   350   350 I Zygote  : Process 1700 exited due to signal (7)
,08-12 22:01:06.469   350   350 I Zygote  : Process 2096 exited due to signal (7)
,08-12 22:01:06.469   350   350 I Zygote  : Process 2841 exited due to signal (7)
,08-12 22:01:06.629   292   550 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-12 22:01:06.629   292   292 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-12 22:01:06.649   290   290 I lowmemorykiller: ActivityManager disconnected
08-12 22:01:06.649   290   290 I lowmemorykiller: Closing Activity Manager data connection
,08-12 22:01:06.879   292   292 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-12 22:01:06.879   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbebec3a4
,08-12 22:01:06.889   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbebec38c
,08-12 22:01:06.889   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbebec38c
,08-12 22:01:06.889   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbebec38c
,08-12 22:01:06.899   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbebec38c
08-12 22:01:06.899   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbebec38c
,08-12 22:01:06.899   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbebec38c
08-12 22:01:06.899   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbebec38c
,08-12 22:01:06.899   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbebec3a4
,08-12 22:01:06.919   292   292 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,08-12 22:01:06.919   292   292 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
08-12 22:01:06.919   292   292 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,08-12 22:01:06.959   292   550 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
