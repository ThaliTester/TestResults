#### Test 58380500c26a9ef_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
D/daemonapp( 4885): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 4885): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 4885): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 4885): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 4885): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 4885): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4885): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4885): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4885): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 4885): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 4885): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 4885): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 4885): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 4885): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454994900000
D/daemonapp( 4885): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454983628100
D/daemonapp( 4885): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 4885): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
I/Icing   ( 3264): updateResources: need to parse f{com.google.android.gms}
D/daemonapp( 4885): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 4885): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 4885): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 4885): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/FaceInterface( 3746): startFaceScan() : going on
E/SPPClientService( 5093): [g] getNetMCC return empty string
D/FaceInterface( 3746): startFaceScan() is called.
E/SPPClientService( 5093): [g] getNetMNC return empty string
D/ContentApp( 2725): startScan() is called.
D/FaceValue( 2725): mSleepTime: 800
D/FaceValue( 2725): mMaxThreadNum: 2
W/FaceValue( 2725): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
D/ContentApp( 2725): startScan() is end.
D/ContentApp( 2725): face_restore FINISHED_TYPE: 3
D/Mms/MessagesLockscreen( 5276): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
D/FaceScanner( 2725): isNeedToRestore : start
W/Binder  ( 2583): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 2583): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
W/Binder  ( 2583): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
W/Binder  ( 2583): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
W/Binder  ( 2583): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
W/Binder  ( 2583): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
W/Binder  ( 2583): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
W/Binder  ( 2583): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
W/Binder  ( 2583): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
W/Binder  ( 2583): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
W/Binder  ( 2583): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
W/Binder  ( 2583): 	at android.view.View.inflate(View.java:18495)
W/Binder  ( 2583): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
W/Binder  ( 2583): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
W/Binder  ( 2583): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
W/Binder  ( 2583): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
W/Binder  ( 2583): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
W/Binder  ( 2583): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 2583): 	at dalvik.system.NativeStart.run(Native Method)
W/Binder  ( 2583): Caused by: java.lang.reflect.InvocationTargetException
W/Binder  ( 2583): 	at java.lang.reflect.Constructor.constructNative(Native Method)
W/Binder  ( 2583): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
W/Binder  ( 2583): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
W/Binder  ( 2583): 	... 16 more
W/Binder  ( 2583): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
W/Binder  ( 2583): 	at android.os.Handler.<init>(Handler.java:200)
W/Binder  ( 2583): 	at android.os.Handler.<init>(Handler.java:114)
W/Binder  ( 2583): 	at android.widget.TextClock.<init>(TextClock.java:130)
W/Binder  ( 2583): 	at android.widget.TextClock.<init>(TextClock.java:191)
W/Binder  ( 2583): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
W/Binder  ( 2583): 	... 19 more
E/JavaBinder( 2583): *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
E/JavaBinder( 2583): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
E/JavaBinder( 2583): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
E/JavaBinder( 2583): 	at android.view.View.inflate(View.java:18495)
E/JavaBinder( 2583): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
E/JavaBinder( 2583): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
E/JavaBinder( 2583): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
E/JavaBinder( 2583): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
E/JavaBinder( 2583): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
E/JavaBinder( 2583): 	at android.os.Binder.execTransact(Binder.java:404)
E/JavaBinder( 2583): 	at dalvik.system.NativeStart.run(Native Method)
E/JavaBinder( 2583): Caused by: java.lang.reflect.InvocationTargetException
E/JavaBinder( 2583): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/JavaBinder( 2583): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
E/JavaBinder( 2583): 	... 16 more
E/JavaBinder( 2583): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
E/JavaBinder( 2583): 	at android.os.Handler.<init>(Handler.java:200)
E/JavaBinder( 2583): 	at android.os.Handler.<init>(Handler.java:114)
E/JavaBinder( 2583): 	at android.widget.TextClock.<init>(TextClock.java:130)
E/JavaBinder( 2583): 	at android.widget.TextClock.<init>(TextClock.java:191)
E/JavaBinder( 2583): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
E/JavaBinder( 2583): 	... 19 more
I/SettingSearch/SearchIntentReceiver( 2840): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 2840): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
I/SettingSearch/SearchIntentReceiver( 2840): InitTitleDBThread start --> mDoingInitTitleDB : true
I/SettingSearch/SearchIntentReceiver( 2840): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 2840): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
I/SettingSearch/SettingsSearchManager( 2840): Infomation -> numtitleinfo : 0 numSearchinfo : 319
D/AndroidRuntime( 6118): 
D/AndroidRuntime( 6118): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6118): CheckJNI is OFF
D/AndroidRuntime( 6118): setted country_code = Poland
D/AndroidRuntime( 6118): setted countryiso_code = PL
D/AndroidRuntime( 6118): setted sales_code = PLS
D/AndroidRuntime( 6118): readGMSProperty: start
D/AndroidRuntime( 6118): readGMSProperty: already setted!!
D/AndroidRuntime( 6118): readGMSProperty: end
D/AndroidRuntime( 6118): addProductProperty: start
D/dalvikvm( 6118): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6118): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6118): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6118): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6118): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SettingSearch/SettingsSearchManager( 2840):  Infomation -> getItem size : 319
E/memtrack( 6118): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6118): failed to load memtrack module: -2
W/ContextImpl( 5794): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/dalvikvm( 6118): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
W/ContextImpl( 5794): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/CacheService( 5794): onCreate
D/CacheService( 5794): onBind
D/AndroidRuntime( 6118): Calling main entry com.android.commands.am.Am
I/MusicLeanback( 5794): Conditions not met for autocaching.
I/MusicLeanback( 5794): Stop autocaching.
D/CacheService( 5794): onDestroy
I/Icing.InternalIcingCorporaProvider( 6059): UpdateCorporaTask done [took 1148 ms] updated apps [took 1148 ms] 
--------- beginning of /dev/log/system
I/ActivityManager( 2403): Killing 5297:com.sec.pcw.device/1000 (adj 15): empty #43
D/AndroidRuntime( 6118): Shutting down VM
D/dalvikvm( 6118): GC_CONCURRENT freed 99K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
,I/Icing   ( 3264): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,D/FactoryTestApp( 5179): [DummyFtClient$onDestroy] Destroy DummyFtClient service
D/FactoryTestApp( 5179): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 5179): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
I/FactoryTestApp( 5179): [ModuleCommon$isRunningFtClient] RUNNING_FTCLIENT : false
D/FactoryTestApp( 5179): [DummyFtClient$onDestroy] kill process
,I/Process ( 5179): Sending signal. PID: 5179 SIG: 9
,I/ActivityManager( 2403): Process com.sec.factory (pid 5179) (adj 0) has died.
I/FaceInterface( 3746): startFaceScan() : going on
D/FaceInterface( 3746): startFaceScan() is called.
,D/ContentApp( 2725): startScan() is called.
,D/ContentApp( 2725): startScan() is end.
,D/ContentApp( 2725): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 2725): isNeedToRestore : start
,I/Icing   ( 3264): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,I/Icing   ( 3264): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
,D/dalvikvm( 2840): GC_EXPLICIT freed 521K, 26% free 10266K/13692K, paused 3ms+9ms, total 58ms
,D/dalvikvm( 2403): GC_EXPLICIT freed 1020K, 13% free 24532K/28192K, paused 8ms+22ms, total 234ms
,I/Icing   ( 3264): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
,D/dalvikvm( 5940): GC_EXPLICIT freed 906K, 26% free 10149K/13684K, paused 5ms+10ms, total 64ms
,D/SensorService( 2403):   0.2 -0.1 9.9
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SPPClientService( 5093): [b] __ProvisionReply__
,E/SPPClientService( 5093): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5093): [d] null
,V/AlarmManager( 2403):  next == MAX_VALUE
,E/SPPClientService( 5093): [g] getPLMN return empty string
,E/SPPClientService( 5093): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5093): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5093): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5093): [g] getNetMCC return empty string
,D/dalvikvm( 5093): GC_CONCURRENT freed 2147K, 24% free 10407K/13680K, paused 7ms+4ms, total 64ms
,D/dalvikvm( 2840): GC_EXPLICIT freed 343K, 25% free 10282K/13692K, paused 4ms+7ms, total 47ms
,D/PowerManagerService( 2403): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2583 (0x0)
I/PowerManagerService( 2403): Nap time...
,D/PowerManagerService( 2403): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2403): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2403): Going to sleep due to screen timeout...
,D/PowerManagerService( 2403): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2403): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/DisplayPowerController( 2403): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,I/DisplayPowerController( 2403): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,D/Sensors ( 2403): LightSensor enable = 0
,D/Sensors ( 2403): LightSensor enableSensor = 0
,D/DisplayPowerController( 2403): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
D/SensorManager( 2403): unregisterListener ::   
,I/SurfaceFlinger( 1921): id=19 createSurf (720x1280),-1 flag=20004, FlectronBea
,D/DisplayPowerController( 2403): !@ElectronBeam entry
I/Sensors ( 2403): HAL:resetDataRates mEnabled=4
D/SensorManager( 2403): unregisterListener ::   
D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4355, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 5940): GC_EXPLICIT freed 1027K, 27% free 10011K/13684K, paused 3ms+8ms, total 42ms
,I/ActivityManager( 2403): Killing 5311:com.sec.android.cloudagent/u0a2 (adj 15): empty #43
,D/lights  ( 2403): lcd : 0 +
,D/lights  ( 2403): lcd : 0 -
D/MISC PowerHAL( 2403): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/input/input1/enabled: 0
V/WindowOrientationListener( 2403): WindowOrientationListener disabled
D/SensorService( 2403): AutoRotationSensor::activate (ident=0x7c30ede0, enabled=0)
,I/Sensors ( 2403): HAL: batch Dry Run is complete
D/KeyguardViewMediator( 2583): onScreenTurnedOff(3)
D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2403): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/input/input0/enabled: 0
D/PowerManagerService( 2403): blankAllDisplays() is called.
D/PowerManagerService( 2403): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2403): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2403): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/SurfaceFlinger( 1921): Screen released, type=0 flinger=0x412ab550
,D/SensorManager( 2403): unregisterListener ::   
,D/InputDispatcher( 2403): setInputDispatchMode: enabled=0, frozen=0
,D/PowerManagerService( 2403): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/LockPatternUtils( 2583): isPcwEnable = 10
D/LockPatternUtils( 2583): isPcwEnable = 10
,D/SurfaceControl( 2403): Excessive delay in blankDisplay() while turning screen off: 208ms
I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(30)
I/libsuspend( 2403): !@[s] autosuspend_autosleep_enable
I/libsuspend( 2403): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2403): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 210ms
D/PowerManagerService( 2403): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2403): [PWL] Off : 0s ago
I/PowerManagerService( 2403): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2403): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2403): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=2403, ws=null) (elapsedTime=208)
I/PowerManagerService( 2403): [PWL]   PowerManagerService.Broadcasts: ref count=1
I/DBG_DM  ( 4264): [3.19.140541][Line:400][onPause] 
D/KeyguardViewMediator( 2583): setting alarm to turn off keyguard, seq = 2
I/SQLiteSecureOpenHelper( 3555): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3555): getDatabaseLocked(b,b,pwd)...
D/LightsService( 2403): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2403) 
I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
D/Sensors ( 2403): LightSensor setDelay = 200000000
D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
D/Sensors ( 2403): Light sensor flush: not enabled 0
D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/Sensors ( 2403): LightSensor enable = 1
D/Sensors ( 2403): LightSensor enableSensor = 1
D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2403): turn on LED for fully charged
D/VibratorService( 2403): JNI vibratorOff()
I/WifiTrafficPoller( 2403): evaluateTrafficStatsPolling
D/STATUSBAR-NotificationService( 2403): ACTION_SCREEN_OFF
I/dalvikvm( 2403): Jit: resizing JitTable from 8192 to 16384
D/LightsService( 2403): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2403) 
D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2403): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
D/IpRemoteDisplayController( 2403): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 2403): Bridge Server is not available
D/PersonaManagerService( 2403): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 2403): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2583): makeExpandedInvisible
D/PhoneStatusBarView( 2583): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is finished!!!! 
I/NfcService( 2770): applyRouting return - 2 
E/NfcService( 2770): callback == null
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
D/LockPatternUtils( 2583): isPcwEnable = 10
D/SSRMv2:SIOP( 2403): SIOP:: AP = 360, Delta = 0
D/QuickConnect[1.1][2] ( 4686): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 4686): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4686): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4686): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42278ac8
V/QuickConnect[1.1][2] ( 4686): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42278ac8
D/QuickConnect[1.1][2] ( 4686): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4686): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4686): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4686): stopLeScan()
D/QuickConnect[1.1][2] ( 4686): BleHelper.stopScan - call stopLeScan() complete
D/PowerManagerService( 2403): [PWL] sb release: PowerManagerService.Broadcasts
D/Sensors ( 2403): LightSensor enable = 0
D/Sensors ( 2403): LightSensor enableSensor = 0
D/LightsService( 2403): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager( 2403): unregisterListener ::   
D/lights  ( 2403): led_pattern : 5 +
I/ActivityManager( 2403): Waited long enough for: ServiceRecord{4333c0f0 u0 com.sec.spp.push/.PushClientService}
D/lights  ( 2403): led_pattern : 5 -
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/SPPClientService( 5093): [b] __InitReply__
,V/AlarmManager( 2403): waitForAlarm result :4
,D/Finsky  ( 5116): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/dalvikvm( 5116): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5116): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5116): VFY: replacing opcode 0x62 at 0x0038
,V/GLSActivity( 2852): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2852): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5116): Thread-369(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5116): Thread-369(ApacheHTTPLog):isShipBuild true
,I/System.out( 5116): Thread-369(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/IcingInternalCorpora( 3264): getNumBytesRead when not calculated.
,D/dalvikvm( 2840): GC_EXPLICIT freed 347K, 25% free 10289K/13692K, paused 8ms+7ms, total 58ms
,I/System.out( 5116): Thread-369 calls detatch()
,V/GLSActivity( 2852): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2852): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 5940): GC_EXPLICIT freed 898K, 27% free 10005K/13684K, paused 5ms+9ms, total 53ms
,I/qtaguid ( 5116): Failed write_ctrl(u 68) res=-1 errno=22
,I/qtaguid ( 5116): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5116): untagSocket(68) failed with errno -22
,I/System.out( 5116): Thread-370 calls detatch()
,D/Finsky  ( 5116): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 2852): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2852): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2403): GC_EXPLICIT freed 650K, 13% free 25270K/28936K, paused 8ms+17ms, total 216ms
,I/qtaguid ( 5116): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5116): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5116): untagSocket(68) failed with errno -22
,I/System.out( 5116): Thread-369 calls detatch()
,D/dalvikvm( 5116): GC_CONCURRENT freed 1993K, 23% free 10595K/13700K, paused 4ms+5ms, total 58ms
,D/dalvikvm( 5116): GC_CONCURRENT freed 693K, 14% free 11943K/13756K, paused 3ms+3ms, total 40ms
,D/dalvikvm( 5116): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 5116): GC_FOR_ALLOC freed 1383K, 18% free 12394K/15088K, paused 40ms, total 41ms
,D/dalvikvm( 5116): GC_FOR_ALLOC freed 1491K, 21% free 13191K/16496K, paused 41ms, total 42ms
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 2840): GC_EXPLICIT freed 352K, 25% free 10296K/13692K, paused 4ms+8ms, total 48ms
,D/PackageManager( 2403): [MSG] MCS_UNBIND
I/PackageManager( 2403): calling disconnectService()
,D/PackageManager( 2403): Trying to unbind to DefaultContainerService
,I/ActivityManager( 2403): Killing 5238:com.vlingo.midas/u0a34 (adj 15): empty #43
,D/dalvikvm( 5940): GC_EXPLICIT freed 901K, 27% free 10014K/13684K, paused 3ms+10ms, total 51ms
,V/AlarmManager( 2403): waitForAlarm result :4
,D/KeyguardViewMediator( 2583): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/LockPatternUtils( 2583): isPcwEnable = 10
D/KeyguardViewMediator( 2583): in doKeyguardLocked mIsRollUp false null
D/PersonaManager( 2583): isKioskContainerExistOnDevice
,D/LockPatternUtils( 2583): isPcwEnable = 10
D/LockPatternUtils( 2583): isPcwEnable = 10
,D/KeyguardViewMediator( 2583): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService( 2403): [PWL] Off : 5s ago
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 300, prevStep = 4, currStep = 4
,V/GLSActivity( 2852): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2852): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5116): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5116): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5116): untagSocket(68) failed with errno -22
,I/System.out( 5116): Thread-370 calls detatch()
,I/ActivityManager( 2403): Waited long enough for: ServiceRecord{43085a60 u0 com.sec.android.gallery3d/.app.BackgroundCache}
,D/dalvikvm( 2840): GC_EXPLICIT freed 354K, 25% free 10302K/13692K, paused 4ms+9ms, total 56ms
,D/dalvikvm( 5940): GC_EXPLICIT freed 905K, 27% free 10012K/13684K, paused 4ms+12ms, total 59ms
,D/Finsky  ( 5116): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 2403): waitForAlarm result :4,
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/WearableService( 2737): callingUid 10012, callindPid: 2737,
,D/Finsky  ( 5116): [393] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/DeviceConnectionService( 2737): client connected with version: 8296000,
,D/Finsky  ( 5116): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null},
,D/Finsky  ( 5116): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected,
,V/GLSActivity( 2852): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 2852): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/System.out( 5116): Thread-380(HTTPLog):isShipBuild true,
,I/System.out( 5116): Thread-380(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,D/dalvikvm( 2403): GC_EXPLICIT freed 815K, 13% free 25302K/28936K, paused 8ms+16ms, total 213ms,
,D/dalvikvm( 2840): GC_EXPLICIT freed 358K, 25% free 10303K/13692K, paused 4ms+7ms, total 47ms,
,D/dalvikvm( 5940): GC_EXPLICIT freed 883K, 27% free 10003K/13684K, paused 3ms+8ms, total 46ms,
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/dalvikvm( 2840): GC_EXPLICIT freed 349K, 25% free 10311K/13692K, paused 4ms+7ms, total 46ms,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 350, Delta = -10
,D/dalvikvm( 5940): GC_EXPLICIT freed 873K, 27% free 10007K/13684K, paused 3ms+9ms, total 45ms,
,D/dalvikvm( 2840): GC_EXPLICIT freed 349K, 25% free 10318K/13692K, paused 4ms+7ms, total 50ms
D/dalvikvm( 5940): GC_EXPLICIT freed 875K, 27% free 10005K/13684K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 2403): GC_EXPLICIT freed 340K, 13% free 25298K/28936K, paused 8ms+16ms, total 208ms,
,D/dalvikvm( 2840): GC_EXPLICIT freed 350K, 25% free 10323K/13692K, paused 4ms+7ms, total 48ms
,D/dalvikvm( 5940): GC_EXPLICIT freed 870K, 27% free 10004K/13684K, paused 3ms+9ms, total 44ms,
,I/PowerManagerService( 2403): [PWL] Off : 15s ago,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 302, prevStep = 4, currStep = 4,
,D/dalvikvm( 5940): GC_EXPLICIT freed 873K, 27% free 10003K/13684K, paused 3ms+9ms, total 44ms,
,D/dalvikvm( 2840): GC_EXPLICIT freed 355K, 25% free 10332K/13692K, paused 5ms+7ms, total 48ms,
,D/dalvikvm( 5940): GC_CONCURRENT freed 1464K, 24% free 10495K/13684K, paused 2ms+9ms, total 35ms
,I/SettingSearch/SearchIntentReceiver( 2840): InitTitleDBThread end --> mDoingInitTitleDB : false,
,I/SettingSearch/SearchIntentReceiver( 2840): LOCALE_CHANGED call search setting db finish!!,
,I/SettingSearch/SearchIntentReceiver( 2840): InitTitleDBThread start --> mDoingInitTitleDB : true,
,I/SettingSearch/SearchIntentReceiver( 2840): InitTitleDBThread end --> mDoingInitTitleDB : false,
,I/SettingSearch/SearchIntentReceiver( 2840): LOCALE_CHANGED call search setting db finish!!,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2403): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 340, Delta = -10,
,E/Watchdog( 2403): !@Sync 3,
,D/AmoledAdjustTimer( 2403): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,I/Icing   ( 3264): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music
,I/Icing   ( 3264): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3385): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2403): [PWL] Off : 30s ago,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = -10,
,V/AlarmManager( 2403): waitForAlarm result :4,
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5461): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5461): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5461): Breath 51620 latestRequest time : 1454983611266 current time : 1454983662887
,D/Finsky  ( 5116): [382] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5116): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/FactoryTest( 5191): Not factory mode,
,D/FactoryTest( 5191): Not factory mode. isFactoryMode() returend false,
D/MTPRx   ( 5191): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5191): still no open session command from host, so toast,
W/ContextImpl( 5191): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5191): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy( 2403): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@4,
,W/ActivityManager( 2403): mDVFSHelper.acquire(),
,D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1,
,E/MTPRx   ( 5191): started activity for popup,
,E/SettingsReceiverActivity( 5191): PREF_DONT_ASK_AGAIN : true,
,D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1,
,W/InputMethodManagerService( 2403): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@42f679c0 attribute=android.view.inputmethod.EditorInfo@4309bb18, token = android.os.BinderProxy@4333b8f0,
,I/SQLiteSecureOpenHelper( 3555): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3555): getDatabaseLocked(b,b,pwd)...
,D/SettingsReceiverActivity( 5191): dev.kiessupport is : TRUE
,I/DBG_DM  ( 4264): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4264): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 47
,I/DBG_DM  ( 4264): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4264): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4264): [3.19.140541][Line:418][onResume] Postpone Count : 47
,I/DBG_DM  ( 4264): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4264): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4264): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2403): sendNotification(2) - 4
,I/DBG_DM  ( 4264): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 47
,I/DBG_DM  ( 4264): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4264): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4264): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4264): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4264): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4264): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4264): setTransGradationMode to true
,D/PhoneStatusBar( 2583): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2403): semi p:4264,o:t
I/DBG_DM  ( 4264): [3.19.140541][Line:400][onPause] 
,D/AmoledAdjustTimer( 2403): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2403): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@8
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2403): stay LED for fully charged,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3385): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
,V/AlarmManager( 2403): ___SyncScheduler (v3) ACTIVATED___,
V/AlarmManager( 2403): <AppSync3 Whitelist>
,V/AlarmManager( 2403): (AppSync) ### 0 added ###,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3385): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/PowerManagerService( 2403): [PWL] Off : 50s ago,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0,
,E/Watchdog( 2403): !@Sync 4,
,V/AlarmManager( 2403): waitForAlarm result :4,
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5461): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5461): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5461): Breath 74811 latestRequest time : 1454983611266 current time : 1454983686077,
,I/VacuumService( 2737): Vacuum at: now=1454983686341 tag=VacuumService,
,D/dalvikvm( 3264): GC_CONCURRENT freed 2154K, 22% free 12001K/15276K, paused 5ms+6ms, total 73ms,
,D/dalvikvm( 2852): GC_EXPLICIT freed 1931K, 23% free 10849K/13956K, paused 6ms+10ms, total 86ms,
,I/PhenotypeConfigurator( 2737): Scheduling Phenotype for one-off execution 1455 seconds from now (1454983686924)
,D/GetConfigurationSnapshotOperation( 2737): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, ,
,I/PhenotypeFlagCommitter( 2737): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader,
,W/dalvikvm( 2737): VFY: unable to find class referenced in signature (Landroid/net/Network;),
,W/dalvikvm( 2737): VFY: unable to find class referenced in signature (Landroid/net/Network;),
,W/dalvikvm( 2737): VFY: unable to find class referenced in signature (Landroid/net/Network;),
I/dalvikvm( 2737): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2737): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2737): VFY: replacing opcode 0x6e at 0x00bb,
,I/GoogleURLConnFactory( 2737): Using platform SSLCertificateSocketFactory,
,D/LocationManagerService( 2403): getLastLocation: Request[POWER_NONE passive fastest=0 num=1],
,I/System.out( 2737): Thread-116(HTTPLog):isShipBuild true,
,I/System.out( 2737): Thread-116(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,D/dalvikvm( 2737): GC_CONCURRENT freed 1709K, 20% free 11857K/14752K, paused 9ms+8ms, total 69ms,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,D/LocationManagerService( 2403): getLastLocation: Request[POWER_NONE passive fastest=0 num=1],
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3385): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2403): waitForAlarm result :8,
,D/Headlines( 5461): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5461): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5461): Breath 90034 latestRequest time : 1454983611266 current time : 1454983701300,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2403): stay LED for fully charged,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3385): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0,
,I/PowerManagerService( 2403): [PWL] Off : 75s ago,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = -10
,E/Watchdog( 2403): !@Sync 5,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,D/Headlines( 5461): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5461): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5461): Breath 120029 latestRequest time : 1454983611266 current time : 1454983731295
,D/Headlines( 5461): stop ,
,D/Headlines( 5461): Breath.onDestroy : ,
I/ActivityManager( 2403): Killing 5379:com.policydm/1000 (adj 15): empty #43
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,I/PowerManagerService( 2403): [PWL] Off : 105s ago,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2403): !@Sync 6,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2403): !@Sync 7,
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 2403): GC_CONCURRENT freed 3671K, 17% free 25533K/30444K, paused 7ms+15ms, total 194ms,
,D/dalvikvm( 2403): WAIT_FOR_CONCURRENT_GC blocked 188ms
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 8,
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3385): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 9,
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,I/PowerManagerService( 2403): [PWL] Off : 225s ago,
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2403): initializing...,
I/TLC_TIMA_PKM_initialize( 2403): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2403): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2403): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2403): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2403): root = 0, root_len = 1,
I/TZ: mc_tlc_communication( 2403): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2403): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2403): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2403): device_id = 0x0
I/TZ: mc_tlc_communication( 2403): tlc_open() was called
,I/TZ: mc_tlc_communication( 2403): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2403): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2403): Opening the session
,I/TZ: mc_tlc_communication( 2403): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2403): Trustlet response is completed,
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2403): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :4,
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7087): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7087):  
,I/SELinux ( 7087): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7087):  
I/SELinux ( 7087):  
,I/SELinux ( 7087): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7087): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7087): >>>>> Normal User
,E/dalvikvm( 7087): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7087): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7087): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7087): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7087): Added TimaKesytore provider,
,D/dalvikvm( 7087): GC_CONCURRENT freed 3014K, 31% free 9559K/13688K, paused 3ms+2ms, total 28ms,
,D/dalvikvm( 7087): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2403): Killing 5417:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3385): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2403): !@Sync 11,
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,I/PowerManagerService( 2403): [PWL] Off : 275s ago,
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
D/BatteryService( 2403): stay LED for fully charged
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3385): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2403): !@Sync 12,
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :4,
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,E/SPPClientService( 5093): [b] __PingReply__
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2403): !@Sync 13
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2403): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = -10
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 10
,E/Watchdog( 2403): !@Sync 14
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2403): !@Sync 15
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2403): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2403): !@Sync 16
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2403): !@Sync 17
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2403): [PWL] Off : 455s ago
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2403): GC_FOR_ALLOC freed 2931K, 18% free 25357K/30756K, paused 179ms, total 180ms
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2403): !@Sync 18
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2403): !@Sync 19
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2403): [PWL] Off : 525s ago
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2403): !@Sync 20
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2403): !@Sync 21
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/GAV2    ( 5207): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5207): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2583): GC_CONCURRENT freed 15743K, 34% free 33852K/50704K, paused 25ms+11ms, total 112ms
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2403): !@Sync 22
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 600s ago
,V/AlarmManager( 2403): waitForAlarm result :8
,D/LightsService( 2403): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
D/Sensors ( 2403): LightSensor setDelay = 200000000
D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
D/Sensors ( 2403): Light sensor flush: not enabled 0
D/Sensors ( 2403): LightSensor enable = 1
D/Sensors ( 2403): LightSensor enableSensor = 1
D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2403): LightSensor enable = 0
,D/Sensors ( 2403): LightSensor enableSensor = 0
,D/LightsService( 2403): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2403): unregisterListener ::   
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2403): !@Sync 23
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2403): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2403): <AppSync3 Whitelist>
,V/AlarmManager( 2403): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2403): !@Sync 24
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2403): !@Sync 25
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 3751): GC_CONCURRENT freed 2908K, 30% free 9726K/13752K, paused 4ms+3ms, total 61ms
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2403): !@Sync 26
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 27
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2403): [PWL] Off : 765s ago
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2403): GC_FOR_ALLOC freed 2689K, 18% free 25400K/30756K, paused 180ms, total 180ms
,E/Watchdog( 2403): !@Sync 28
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 29
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2403): !@Sync 30
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2403): [PWL] Off : 855s ago
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 31
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/ConnectivityService( 2403): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2583): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2583): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2583): updateDataNetType()
,D/STATUSBAR-NetworkController( 2583): NoService, mRoamingIconId = 0
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2403): !@Sync 32
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,E/SPPClientService( 5093): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 33
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2403): [PWL] Off : 950s ago
,E/Watchdog( 2403): !@Sync 34
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 35
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2403): !@Sync 36
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 37
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2403): GC_FOR_ALLOC freed 2637K, 18% free 25448K/30756K, paused 183ms, total 183ms
,E/Watchdog( 2403): !@Sync 38
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 39
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2403): !@Sync 40
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2403): [PWL] Off : 1155s ago
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 41
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3385): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 42
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5093): [b] __PingReply__
,V/AlarmManager( 2403): waitForAlarm result :8
,I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
,D/LightsService( 2403): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2403): LightSensor setDelay = 200000000
D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
D/Sensors ( 2403): Light sensor flush: not enabled 0
D/Sensors ( 2403): LightSensor enable = 1
D/Sensors ( 2403): LightSensor enableSensor = 1
D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2403): LightSensor enable = 0
,D/Sensors ( 2403): LightSensor enableSensor = 0
,D/LightsService( 2403): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2403): unregisterListener ::   
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 43
,TIME-OUT KILL (timeout was 1200000ms),D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
D/AndroidRuntime( 9359): 
D/AndroidRuntime( 9359): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 9359): CheckJNI is OFF
D/AndroidRuntime( 9359): setted country_code = Poland
D/AndroidRuntime( 9359): setted countryiso_code = PL
D/AndroidRuntime( 9359): setted sales_code = PLS
D/AndroidRuntime( 9359): readGMSProperty: start
D/AndroidRuntime( 9359): readGMSProperty: already setted!!
D/AndroidRuntime( 9359): readGMSProperty: end
D/AndroidRuntime( 9359): addProductProperty: start
D/dalvikvm( 9359): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 9359): Added shared lib libjavacore.so 0x0
D/dalvikvm( 9359): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 9359): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 9359): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 9359): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 9359): failed to load memtrack module: -2
D/dalvikvm( 9359): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 9359): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2403): START PACKAGE DELETE: observer{1118482512}
D/PackageManager( 2403): pkg{<packageName>}
D/PackageManager( 2403): user{0}
D/PackageManager( 2403): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2403): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2403): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2403): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2403): [MSG] DELETE_PACKAGE_AS_USER
D/dalvikvm( 2403): GC_EXPLICIT freed 1545K, 18% free 25341K/30756K, paused 8ms+14ms, total 210ms
D/AndroidRuntime( 9359): Shutting down VM
D/PackageManager( 2403): return delete result to caller: 1118482512
D/PackageManager( 2403): returnCode: -1
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
D/dalvikvm( 9359): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+1ms, total 4ms
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "sms"
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "smsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "mms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "mmsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2403): stay LED for fully charged
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3385): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3385): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4

```
