#### Test 61432979f791f6f_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
D/Mms/MessagesLockscreen( 5027): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
W/Binder  ( 2581): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 2581): android.view.InflateException: Binary XML file line #11: Error inflating class com.android.keyguard.sec.SecKeyguardTextClock
W/Binder  ( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
W/Binder  ( 2581): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
W/Binder  ( 2581): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
W/Binder  ( 2581): 	at android.view.View.inflate(View.java:18495)
W/Binder  ( 2581): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
W/Binder  ( 2581): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
W/Binder  ( 2581): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
W/Binder  ( 2581): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
W/Binder  ( 2581): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
W/Binder  ( 2581): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 2581): 	at dalvik.system.NativeStart.run(Native Method)
W/Binder  ( 2581): Caused by: java.lang.reflect.InvocationTargetException
W/Binder  ( 2581): 	at java.lang.reflect.Constructor.constructNative(Native Method)
W/Binder  ( 2581): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
W/Binder  ( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
W/Binder  ( 2581): 	... 16 more
W/Binder  ( 2581): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
W/Binder  ( 2581): 	at android.os.Handler.<init>(Handler.java:200)
W/Binder  ( 2581): 	at android.os.Handler.<init>(Handler.java:114)
W/Binder  ( 2581): 	at android.widget.TextClock.<init>(TextClock.java:130)
W/Binder  ( 2581): 	at android.widget.TextClock.<init>(TextClock.java:191)
W/Binder  ( 2581): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
W/Binder  ( 2581): 	... 19 more
E/JavaBinder( 2581): *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
E/JavaBinder( 2581): android.view.InflateException: Binary XML file line #11: Error inflating class com.android.keyguard.sec.SecKeyguardTextClock
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
E/JavaBinder( 2581): 	at android.view.View.inflate(View.java:18495)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
E/JavaBinder( 2581): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
E/JavaBinder( 2581): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
E/JavaBinder( 2581): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
E/JavaBinder( 2581): 	at android.os.Binder.execTransact(Binder.java:404)
E/JavaBinder( 2581): 	at dalvik.system.NativeStart.run(Native Method)
E/JavaBinder( 2581): Caused by: java.lang.reflect.InvocationTargetException
E/JavaBinder( 2581): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/JavaBinder( 2581): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
E/JavaBinder( 2581): 	... 16 more
E/JavaBinder( 2581): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
E/JavaBinder( 2581): 	at android.os.Handler.<init>(Handler.java:200)
E/JavaBinder( 2581): 	at android.os.Handler.<init>(Handler.java:114)
E/JavaBinder( 2581): 	at android.widget.TextClock.<init>(TextClock.java:130)
E/JavaBinder( 2581): 	at android.widget.TextClock.<init>(TextClock.java:191)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
E/JavaBinder( 2581): 	... 19 more
W/Binder  ( 2581): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 2581): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
W/Binder  ( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
W/Binder  ( 2581): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
W/Binder  ( 2581): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
W/Binder  ( 2581): 	at android.view.View.inflate(View.java:18495)
W/Binder  ( 2581): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
W/Binder  ( 2581): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
W/Binder  ( 2581): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
W/Binder  ( 2581): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
W/Binder  ( 2581): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
W/Binder  ( 2581): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 2581): 	at dalvik.system.NativeStart.run(Native Method)
W/Binder  ( 2581): Caused by: java.lang.reflect.InvocationTargetException
W/Binder  ( 2581): 	at java.lang.reflect.Constructor.constructNative(Native Method)
W/Binder  ( 2581): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
W/Binder  ( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
W/Binder  ( 2581): 	... 16 more
W/Binder  ( 2581): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
W/Binder  ( 2581): 	at android.os.Handler.<init>(Handler.java:200)
W/Binder  ( 2581): 	at android.os.Handler.<init>(Handler.java:114)
W/Binder  ( 2581): 	at android.widget.TextClock.<init>(TextClock.java:130)
W/Binder  ( 2581): 	at android.widget.TextClock.<init>(TextClock.java:191)
W/Binder  ( 2581): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
W/Binder  ( 2581): 	... 19 more
E/JavaBinder( 2581): *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
E/JavaBinder( 2581): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
E/JavaBinder( 2581): 	at android.view.View.inflate(View.java:18495)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
E/JavaBinder( 2581): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
E/JavaBinder( 2581): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
E/JavaBinder( 2581): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
E/JavaBinder( 2581): 	at android.os.Binder.execTransact(Binder.java:404)
E/JavaBinder( 2581): 	at dalvik.system.NativeStart.run(Native Method)
E/JavaBinder( 2581): Caused by: java.lang.reflect.InvocationTargetException
E/JavaBinder( 2581): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/JavaBinder( 2581): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
E/JavaBinder( 2581): 	... 16 more
E/JavaBinder( 2581): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
E/JavaBinder( 2581): 	at android.os.Handler.<init>(Handler.java:200)
E/JavaBinder( 2581): 	at android.os.Handler.<init>(Handler.java:114)
E/JavaBinder( 2581): 	at android.widget.TextClock.<init>(TextClock.java:130)
E/JavaBinder( 2581): 	at android.widget.TextClock.<init>(TextClock.java:191)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
E/JavaBinder( 2581): 	... 19 more
I/SettingSearch/SearchIntentReceiver( 5010): action : android.settings.CHANGED_ICC_LOCK_ENABLE
--------- beginning of /dev/log/system
D/WifiDisplayAdapter( 2422): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/CscFactoryReceiver( 2771): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 2771): Media DB Scanner finished.
D/CscFactoryReceiver( 2771): start service to Set Ringtone
D/CscFactoryReceiver( 2771): start service to Set Notification
D/CscFactoryReceiver( 2771): start service to Set Alarmtone
D/CscUpdateService( 2771): onStart
E/CscUpdateService( 2771): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 2771): only ringtone update
D/CscUpdateService( 2771): onStart
E/CscUpdateService( 2771): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 2771): only notification update
D/CscUpdateService( 2771): onStart
E/CscUpdateService( 2771): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 2771): only alarmtone update
E/CscParser( 2771): update(): xml file exist
E/CscParser( 2771): update(): xml file exist
E/CscParser( 2771): update(): xml file exist
I/SELinux ( 5117): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5117):  
D/lights  ( 2422): lcd : 0 +
D/PowerManagerService( 2422): Excessive delay in LCD_Task is start: 21ms
D/lights  ( 2422): lcd : 0 -
D/MISC PowerHAL( 2422): miscpower_set_interactive: /sys/class/input/input1/enabled
D/MISC PowerHAL( 2422): sysfs_write +: /sys/class/input/input1/enabled: 0
D/PowerManagerService( 2422): blankAllDisplays() is called.
D/dalvikvm( 1924): GC_EXPLICIT freed 43K, 8% free 9507K/10252K, paused 3ms+3ms, total 34ms
W/CSCSettings( 2771): Setting Ringtones (type) : 1
W/CSCSettings( 2771): Setting Ringtones (type) : 4
I/DBG_DM  ( 4071): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 19 sec
I/SELinux ( 5117): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5117):  
I/SELinux ( 5117):  
I/SELinux ( 5117): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/MISC PowerHAL( 2422): sysfs_write -: /sys/class/input/input1/enabled: 0
E/SELinux ( 5117): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5117): >>>>> Normal User
E/dalvikvm( 5117): >>>>> com.samsung.indexservice [ userId:0 | appId:10004 ]
D/CscParser( 2771): RingTone: null
D/MISC PowerHAL( 2422): miscpower_set_interactive: /sys/class/input/input0/enabled
D/CscParser( 2771): AlarmTone: null
W/CSCSettings( 2771): 1. Tag_Str: null
E/SELinux ( 5117): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/CSCSettings( 2771): 1. Tag_Str: null
D/MISC PowerHAL( 2422): sysfs_write +: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2422): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2422): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2422): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/PowerManagerService-JNI( 2422): Excessive delay in MISC setInteractive(false) while turning screen off: 29ms
D/SEC PowerHAL( 2422): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2422): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2422): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2422): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2422): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2422): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2422): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/SEC PowerHAL( 2422): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/PowerManagerService( 2422): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
W/CSCSettings( 2771): Setting Ringtones (type) : 2
D/CscParser( 2771): MessageTone: null
W/CSCSettings( 2771): 1. Tag_Str: null
D/PowerManagerService( 2422): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2422): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2422): [PWL] sb release: PowerManagerService.Display
D/dalvikvm( 1924): GC_EXPLICIT freed <1K, 8% free 9507K/10252K, paused 2ms+3ms, total 28ms
I/CastUtils( 5079): Removing provider: MediaRouter.RouteProviderInfo{ packageName=com.google.android.gms }
D/KeyguardViewMediator( 2581): onScreenTurnedOff(3)
I/display ( 1923): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(43)
I/ActivityManager( 2422): Killing 4113:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43
V/WindowOrientationListener( 2422): WindowOrientationListener disabled
D/SensorService( 2422): AutoRotationSensor::activate (ident=0x74649f00, enabled=0)
I/Sensors ( 2422): HAL: batch Dry Run is complete
D/SurfaceFlinger( 1923): Screen released, type=0 flinger=0x408d5550
D/SensorManager( 2422): unregisterListener ::   
D/InputDispatcher( 2422): setInputDispatchMode: enabled=0, frozen=0
D/Launcher.HomeView( 2801): onPause
D/dalvikvm( 1924): GC_EXPLICIT freed <1K, 8% free 9507K/10252K, paused 3ms+5ms, total 31ms
D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2422): tr p:2801,o:f
D/LockPatternUtils( 2581): isPcwEnable = 10
I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
D/TimaKeyStoreProvider( 5117): in addTimaSignatureService
D/Sensors ( 2422): LightSensor setDelay = 200000000
D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/LightsService( 2422): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2422) 
D/LightsService( 2422): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/Sensors ( 2422): Light sensor flush: not enabled 0
D/Sensors ( 2422): LightSensor enable = 1
D/Sensors ( 2422): LightSensor enableSensor = 1
D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/LockPatternUtils( 2581): isPcwEnable = 10
D/BatteryService( 2422): turn on LED for fully charged
D/VibratorService( 2422): JNI vibratorOff()
D/KeyguardViewMediator( 2581): setting alarm to turn off keyguard, seq = 1
D/TimaKeyStoreProvider( 5117): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5117): Added TimaKesytore provider
D/Launcher.HomeView( 2801): onStop
I/ActivityManager( 2422): Waited long enough for: ServiceRecord{42fa0f78 u0 com.sec.knox.seandroid/.service.SEAndroidLauncher}
I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
D/STATUSBAR-NotificationService( 2422): ACTION_SCREEN_OFF
D/LightsService( 2422): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2422) 
I/AudioHardwareTinyALSA( 1927): setParameters(screen_state=off)
D/LightsService( 2422): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/SecExternalDisplayIntents_Java( 2422): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
D/IpRemoteDisplayController( 2422): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 2422): Bridge Server is not available
D/PersonaManagerService( 2422): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 2422): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2581): makeExpandedInvisible
D/PhoneStatusBarView( 2581): marqueeStatusBar:121, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is finished!!!! 
I/NfcService( 2777): applyRouting return - 2 
E/NfcService( 2777): callback == null
D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
D/LockPatternUtils( 2581): isPcwEnable = 10
D/SSRMv2:SIOP( 2422): SIOP:: AP = 350, Delta = 0
D/QuickConnect[1.1][2] ( 4459): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 4459): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4459): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4459): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4220eb58
V/QuickConnect[1.1][2] ( 4459): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4220eb58
D/QuickConnect[1.1][2] ( 4459): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4459): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4459): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4459): stopLeScan()
D/QuickConnect[1.1][2] ( 4459): BleHelper.stopScan - call stopLeScan() complete
D/SurfaceControl( 2422): Excessive delay in blankDisplay() while turning screen off: 234ms
I/libsuspend( 2422): !@[s] autosuspend_autosleep_enable
I/libsuspend( 2422): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2422): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 237ms
D/PowerManagerService( 2422): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2422): [PWL] Off : 0s ago
I/PowerManagerService( 2422): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2422): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2422): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2422, ws=WorkSource{10045}) (elapsedTime=16756)
I/PowerManagerService( 2422): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10012, pid=3269, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=35)
I/PowerManagerService( 2422): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/PowerManagerService( 2422): [PWL] sb release: PowerManagerService.Broadcasts
D/Sensors ( 2422): LightSensor enable = 0
D/Sensors ( 2422): LightSensor enableSensor = 0
D/SensorManager( 2422): unregisterListener ::   
D/lights  ( 2422): led_pattern : 5 +
D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 0
D/lights  ( 2422): led_pattern : 5 -
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/dalvikvm( 5117): GC_CONCURRENT freed 3005K, 28% free 9565K/13272K, paused 2ms+1ms, total 20ms
D/dalvikvm( 5117): WAIT_FOR_CONCURRENT_GC blocked 17ms
I/Mms/MmsApp( 5027):  start initViewCache mms
D/dalvikvm( 2422): GC_EXPLICIT freed 1024K, 12% free 23899K/27056K, paused 9ms+19ms, total 232ms
I/IndexBroadcastProcessorService( 5117): lucene onHandleIntent-ACTION_MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 4983): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.MEDIA_SCANNER_FINISHED
W/ActivityThread( 4983): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/FactoryTestApp( 4983): [XMLDataStorage$parseXML] is Live Demo : false
D/FactoryTestApp( 4983): [XMLDataStorage$parseXML] modelXML=sm-g800f.dat
D/FactoryTestApp( 4983): [XMLDataStorage$parseXML] deviceXML=kminilte.dat
D/FactoryTestApp( 4983): [XMLDataStorage$parseXML] nameXML=kminiltexx.dat
I/IndexBroadcastProcessorService( 5117): lucene systemReadyToIndex
I/IndexService( 5117): lucene onCreate ...service
I/FactoryTestApp( 4983): [XMLDataStorage$parseAsset] Convert dat file: sm-g800f.dat
E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5117): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5117): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/dalvikvm( 5117): Could not find method java.lang.management.ManagementFactory.getPlatformMBeanServer, referenced from method org.apache.lucene.util.RamUsageEstimator.<clinit>
W/dalvikvm( 5117): VFY: unable to resolve static method 5877: Ljava/lang/management/ManagementFactory;.getPlatformMBeanServer ()Ljavax/management/MBeanServer;
D/dalvikvm( 5117): VFY: replacing opcode 0x71 at 0x01ed
I/IndexService( 5117): lucene beginIndexing
D/FactoryTestApp( 4983): [XMLDataStorage$parseAsset] Decode base file: factory.dat
I/IndexService( 5117): lucene onDestroy start
I/IndexService( 5117): lucene onDestroy end
I/IndexService( 5117): lucene cleanupEverything start
I/IndexService( 5117): ERROR: null
E/ParserThreadsListManager( 5117): Lucene Interrupt in run
I/IndexService( 5117): lucene cleanupEverything end
I/Process ( 5117): Sending signal. PID: 5117 SIG: 9
I/ActivityManager( 2422): Process com.samsung.indexservice (pid 5117) (adj 9) has died.
I/ActivityManager( 2422): Waited long enough for: ServiceRecord{42c1bb60 u0 com.samsung.android.sconnect/.periph.PeriphService}
D/Mms/ComposeMessageFragment( 5027): fillCache, easy = false
D/dalvikvm( 4983): GC_CONCURRENT freed 2535K, 25% free 10060K/13292K, paused 10ms+2ms, total 65ms
D/checkbox( 5027): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
I/DBG_DM  ( 4071): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 20 sec
D/checkbox( 5027): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5027): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5027): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/dalvikvm( 4649): GC_CONCURRENT freed 2288K, 23% free 10275K/13268K, paused 1ms+28ms, total 80ms
D/AndroidRuntime( 5136): 
D/AndroidRuntime( 5136): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5136): CheckJNI is OFF
D/AndroidRuntime( 5136): setted country_code = Poland
D/AndroidRuntime( 5136): setted countryiso_code = PL
D/AndroidRuntime( 5136): setted sales_code = PLS
D/AndroidRuntime( 5136): readGMSProperty: start
D/AndroidRuntime( 5136): readGMSProperty: already setted!!
D/AndroidRuntime( 5136): readGMSProperty: end
D/AndroidRuntime( 5136): addProductProperty: start
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APP
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FAILHIST_VERSION
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=MODEL_NAME
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=MODEL_NUMBER
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=MODEL_HARDWARE_REVISION
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=CHIPSET_MANUFACTURE
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=CHIPSET_NAME
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=DEVICE_TYPE
D/dalvikvm( 5136): Trying to load lib libjavacore.so 0x0
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=PANEL_TYPE
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_ACCELEROMETER
D/dalvikvm( 5136): Added shared lib libjavacore.so 0x0
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_GYROSCOPE
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=REAR_CAMERA_TYPE
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=ISP_FLASH_TEST_SMD
D/dalvikvm( 5136): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5136): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5136): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TORCH_MODE_FLASH_ON_CURRENT
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SPEAKER_COUNT
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=MIC_COUNT
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SVC_LED_TEST_BRIGHTNESS
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_VIBRATOR
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_LTE
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_QWERTY_KEY
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_FRONT_CAMERA
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_RCV
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APO
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_BOOST_MEDIASCAN
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_NVBACKUP_CMD
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_EPEN
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_SENSORHUB
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_CAM_ISP
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_CAM_FRONT_NOT_ISP
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_SECOND_MIC_TEST
D/AbsListView( 5027): Get MotionRecognitionManager
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_IRLED_FEEDBACK_IC
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=HW_VER_EFS
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_BOOK_COVER
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=NEED_LPA_MODE_SET
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=MULTI_TSK_THD
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_HOVER_HIGHTLIGHT
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FACTOLOG_SYSTEM_INFO_UPDATE
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_AUTO_WAKELOCK
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_AP_EX_THERM_ADC
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=CAL_AP_TEMP
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_SELFTEST_PWC_DISPLAY
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_GLOVE_MODE
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FONT_SIZE
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=RAM_SIZE_IF
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_FONT_SIZE
D/MotionRecognitionService( 2422):  ssp status : false
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_SEMI_FUNCTION_TEST
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_TEST_UI_ORIENTATION
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_UP
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_DOWN
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=KEY_TEST_POWER
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=KEY_TEST_APP_SWITCH
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=KEY_TEST_HOME
I/dalvikvm( 5027): Could not find method android.sec.multiwindow.MultiWindow.createInstance, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 5027): VFY: unable to resolve static method 1401: Landroid/sec/multiwindow/MultiWindow;.createInstance (Landroid/app/Activity;)Landroid/sec/multiwindow/MultiWindow;
D/dalvikvm( 5027): VFY: replacing opcode 0x71 at 0x03bb
I/dalvikvm( 5027): Could not find method android.sec.multiwindow.MultiWindow.isMultiWindow, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 5027): VFY: unable to resolve virtual method 1402: Landroid/sec/multiwindow/MultiWindow;.isMultiWindow ()Z
D/dalvikvm( 5027): VFY: replacing opcode 0x74 at 0x0759
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=KEY_TEST_BACK
I/dalvikvm( 5027): Could not find method android.sec.multiwindow.MultiWindow.isMultiWindow, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 5027): VFY: unable to resolve virtual method 1402: Landroid/sec/multiwindow/MultiWindow;.isMultiWindow ()Z
D/dalvikvm( 5027): VFY: replacing opcode 0x74 at 0x07e8
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=KEY_TEST_SEARCH
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=KEY_TEST_FOCUS
D/checkbox( 5027): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5027): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5027): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5027): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=KEY_TEST_CAMERA
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=KEY_TEST_F1
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=KEY_TEST_TOUCH_KEY_ODER
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=KEY_TEST_VIEW_TABLE
V/WebViewChromium( 5027): Binding Chromium to the main looper Looper (main, tid 1) {42204320}
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=IS_KEY_TEST_THRESHOLD
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_UP
I/chromium( 5027): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5027): Initializing chromium process, renderers=0
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_DOWN
D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=IS_TSP_STANDARD_CHANNEL
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=IS_SENSOR_TEST_ACC_REVERSE
W/chromium( 5027): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SUPPORT_GEOMAGNETIC_ALPS_CAL
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=GEOMAGNETIC_IC_POINT
D/libEGL  ( 5027): loaded /system/lib/egl/libEGL_mali.so
E/memtrack( 5136): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5136): failed to load memtrack module: -2
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SENSOR_TEST_ACC_BIT
D/libEGL  ( 5027): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=IS_VIBETONZ_UNSUPPORTED
D/libEGL  ( 5027): loaded /system/lib/egl/libGLESv2_mali.so
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=IS_IRLED_TEST_SPLIT_COMMAND
I/Mali    ( 5027): Mali API Version : 401
I/Mali    ( 5027): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=AT_SPKSTEST
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=AT_GPSSTEST
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=AT_BATTEST_RESET_WHEN_READ
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=PA0_TEMP_ADC
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=PA1_TEMP_ADC
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=NEED_ACK_FOR_CAMERA_STOP
D/dalvikvm( 5027): GC_CONCURRENT freed 909K, 13% free 11630K/13276K, paused 3ms+3ms, total 25ms
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=HALL_IC_TEST
D/dalvikvm( 5136): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=HUMITEMP_TEST
D/dalvikvm( 4983): GC_CONCURRENT freed 1733K, 23% free 10352K/13292K, paused 3ms+2ms, total 45ms
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=IS_NEW_TSP_SELFTEST_SYNAPTICS
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_PEEK_TO_PEEK
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_IR_CURRENT_CHANGE
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
D/checkbox( 5027): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5027): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5027): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5027): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SYS_INFO_FONT_SIZE
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SYS_INFO_MEMORY_SIZE
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SYS_INFO_OUT_POSITION
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_WIDTH
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_HEIGHT
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_SPEC_MAX_MINUS_MIN
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS_PWC
D/checkbox( 5027): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5027): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5027): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5027): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS_PWC
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_Y_CYPRESS
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_Y_CYPRESS
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_X_CYPRESS
D/AndroidRuntime( 5136): Calling main entry com.android.commands.am.Am
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_X_CYPRESS
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS
D/checkbox( 5027): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5027): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5027): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5027): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MIN
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MAX
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MIN
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MAX
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_START
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_END
D/checkbox( 5027): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_START
D/checkbox( 5027): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5027): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5027): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_END
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MIN
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MAX
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MIN
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MAX
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_AVG
D/checkbox( 5027): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5027): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5027): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5027): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_AVG
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_AVG
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_MAX
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_AVG
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_MAX
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_MAX
D/checkbox( 5027): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5027): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5027): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5027): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_AVG
D/AndroidRuntime( 5136): Shutting down VM
D/dalvikvm( 5136): GC_CONCURRENT freed 99K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_MAX
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_AVG
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_SAMPLE_NO
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_PEAK_IR
D/checkbox( 5027): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5027): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5027): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5027): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_IR
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_NOISE_IR
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_RED
D/Mms/BubbleViewCache( 5027): fillCache bubble = 8
D/Mms/Synchronizer( 5027): [start]    dbSync()
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=BOOTLOADER_VERSION
D/TP/MmsSmsProvider( 2771): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 2771): syncDBData start
D/TP/MmsSmsProvider( 2771): match 0:Elapsed time : 1.998 ms
V/TP/MmsSmsProvider( 2771): syncDBData sms end
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=BATTERY_TEST_MODE
V/TP/MmsSmsProvider( 2771): syncDBData mms end
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=BATTERY_VOLT_AVER
V/TP/MmsSmsProvider( 2771): syncDBData end
D/Mms/Synchronizer( 5027): [end]    dbSync()
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=BATTERY_VF_OCV
D/Mms/MessagingNotification( 5027): checkBadgeCount unreadCount=0 badgeCount=0
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_CELCIUS
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=SEC_EXT_THERMISTER_ADC
D/TP/MmsSmsProvider( 2771): match 6:Elapsed time : 1.774 ms
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_ADC
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=PA1_THERMISTER_ADC
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_COMMAND_CMD
D/dalvikvm( 4983): GC_CONCURRENT freed 2033K, 23% free 10353K/13292K, paused 3ms+2ms, total 31ms
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_COMMAND_STATUS
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=TSP_COMMAND_RESULT
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=LED_RED
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=LED_GREEN
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=LED_BLUE
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=PATH_HALLIC_STATE
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=KEY_PRESSED_POWER
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=APCHIP_TEMP_ADC
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_PAM
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT_CELCIUS
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=USB3_TYPE_CHECK
D/FactoryTestApp( 4983): [XMLDataStorage$redefinitionById] id=LPA_MODE_SET
D/FactoryTestApp( 4983): [XMLDataStorage$parseAsset] SemiFunctionMenu
D/FactoryTestApp( 4983): [Support$Values.getString] id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 4983): [Support$Properties.get] property=ro.factory.factory_binary
D/FactoryTestApp( 4983): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=S.LSI
D/FactoryTestApp( 4983): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=S.LSI
D/FactoryTestApp( 4983): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=S.LSI
I/FactoryTestApp( 4983): [ModuleCommon$ModuleCommon] Create ModuleCommon
I/FactoryTestApp( 4983): [ModuleCommon$setMediascanningCounter]  
I/FactoryTestApp( 4983): [ModuleCommon$getMediaScanningCount] get : 0
D/FactoryTest( 4983): User mode
,I/FactoryTestApp( 4983): [ModuleCommon$getMediaScanningCount] get : 1
W/ContextImpl( 4983): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:269 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 5166): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5166):  
,I/SELinux ( 5166): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5166):  
I/SELinux ( 5166):  
,I/SELinux ( 5166): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5166): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5166): >>>>> Normal User
,E/dalvikvm( 5166): >>>>> com.sec.android.gallery3d [ userId:0 | appId:10047 ]
,E/SELinux ( 5166): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5166): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5166): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5166): Added TimaKesytore provider
,I/DBG_DM  ( 4071): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 21 sec
,D/dalvikvm( 5166): GC_CONCURRENT freed 3007K, 28% free 9571K/13276K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 5166): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/Icing   ( 3269): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music
,W/System.err( 5166): java.lang.NoSuchFieldException: SYSTEM_UI_FLAG_REMOVE_NAVIGATION
,W/System.err( 5166): 	at java.lang.Class.getField(Class.java:724)
W/System.err( 5166): 	at com.sec.android.gallery3d.util.GalleryFeature.checkSystemUiVisibility(GalleryFeature.java:1588)
W/System.err( 5166): 	at com.sec.android.gallery3d.util.GalleryFeature.init(GalleryFeature.java:364)
W/System.err( 5166): 	at com.sec.android.gallery3d.app.GalleryAppImpl.getDataManager(GalleryAppImpl.java:247)
W/System.err( 5166): 	at com.sec.android.gallery3d.provider.GalleryProvider.onCreate(GalleryProvider.java:140)
W/System.err( 5166): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
,W/System.err( 5166): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
W/System.err( 5166): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
W/System.err( 5166): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
W/System.err( 5166): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
W/System.err( 5166): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5166): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 5166): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5166): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 5166): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 5166): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 5166): 	at java.lang.reflect.Method.invoke(Method.java:515)
,W/System.err( 5166): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 5166): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 5166): 	at dalvik.system.NativeStart.main(Native Method)
,W/ServiceManager( 2422): Permission failure: com.samsung.permission.SSENSOR from uid=10047 pid=5166
D/PermissionCache( 2422): checking com.samsung.permission.SSENSOR for uid=10047 => denied (349 us)
E/SensorService( 2422): Permission Denial : SEC Private Sensor 
,E/SensorService( 2422): Permission Denial : SEC Private Sensor 
,D/dalvikvm( 4649): GC_CONCURRENT freed 2009K, 23% free 10226K/13268K, paused 2ms+10ms, total 60ms
D/Spen    ( 5166): SpenSdk version level = 55
,D/Spen    ( 5166): SpenSdk jar version = 3.0.109
D/Spen    ( 5166): SpenSdk apk version = 3.0.109
,D/Spen    ( 5166): Server UPDATE Check
,W/linker  ( 5166): libSPenBase.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/SPenError( 5166): JNI_OnLoad
D/JNI_Bitmap( 5166): Init .. Done
D/SPenSpiDecoder( 5166): JNI_OnLoad .. Done
,D/SPenError( 5166): JNI_OnLoad Success
,D/PluginManager( 5166): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
,D/PluginManager( 5166): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni( 5166): JNI_OnLoad
,D/Init_SPenSdk_Jni( 5166): JNI_OnLoad .. Done
,D/Model_ObjectBase_Jni( 5166): JNI_OnLoad .. Done
,D/Model_ObjectStroke_Jni( 5166): JNI_OnLoad .. Done
,D/Model_ObjectImage_Jni( 5166): JNI_OnLoad .. Done
,D/Model_ObjectText_Jni( 5166): JNI_OnLoad .. Done
,D/Model_ObjectContainer_Jni( 5166): JNI_OnLoad .. Done
,D/Model_PageDoc_Jni( 5166): JNI_OnLoad .. Done
,D/Model_NoteDoc_Jni( 5166): check build type eng[0]
D/Model_NoteDoc_Jni( 5166): JNI_OnLoad .. Done
,D/Model_NoteFile_Jni( 5166): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni( 5166): JNI_OnLoad .. Done
,D/Model   ( 5166): OnLoad class Done
,I/Icing   ( 3269): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A
,D/dalvikvm( 5166): No JNI_OnLoad found in /system/lib/libSPenSkia.so 0x421f5500, skipping init
,D/SPen_Library( 5166): Draw Engine JNI_OnLoad enter!!
,D/SPen_Library( 5166): Canvas JNI_OnLoad enter!!
D/SPen_Library( 5166): Canvas JNI_OnLoad Success
,D/SPen_Library( 5166): TextView JNI_OnLoad enter!!
D/SPen_Library( 5166): TextView JNI_OnLoad Success
,D/SPen_Library( 5166): Text JNI_OnLoad enter!!
D/SPen_Library( 5166): Text JNI_OnLoad Success
D/SPen_Library( 5166): FontManager JNI_OnLoad enter!!
D/SPen_Library( 5166): FontManager JNI_OnLoad Success
D/SPen_Library( 5166): CapturePage JNI_OnLoad enter!!
D/SPen_Library( 5166): CapturePage JNI_OnLoad Success
D/SPen_Library( 5166): Multi JNI_OnLoad enter!!
D/SPen_Library( 5166): Multi JNI_OnLoad Success
D/SPen_Library( 5166): Draw Engine JNI_OnLoad Success
D/SPen_Library( 5166): Brush JNI_OnLoad enter!!
D/SPen_Library( 5166): Brush JNI_OnLoad Success
,D/SPen_Library( 5166): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library( 5166): ChineseBrush JNI_OnLoad Success
,D/SPen_Library( 5166): InkPen JNI_OnLoad enter!!
,D/SPen_Library( 5166): InkPen JNI_OnLoad Success
,D/SPen_Library( 5166): Marker JNI_OnLoad enter!!
,D/SPen_Library( 5166): Marker JNI_OnLoad Success
,D/SPen_Library( 5166): Pencil JNI_OnLoad enter!!
,D/SPen_Library( 5166): Pencil JNI_OnLoad Success
,D/SPen_Library( 5166): NativePen JNI_OnLoad enter!!
,D/SPen_Library( 5166): NativePen JNI_OnLoad Success
,D/SPen_Library( 5166): MagicPen JNI_OnLoad enter!!
,D/SPen_Library( 5166): MagicPen JNI_OnLoad Success
,W/linker  ( 5166): libSPenHSV.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/dalvikvm( 5166): No JNI_OnLoad found in /system/lib/libSPenHSV.so 0x421f5500, skipping init
,D/dalvikvm( 5166): No JNI_OnLoad found in /system/lib/libSPenVIRecognition.so 0x421f5500, skipping init
D/dalvikvm( 5166): No JNI_OnLoad found in /system/lib/libSPenVITextAll.so 0x421f5500, skipping init
D/Spen    ( 5166): SpenSdk Libraries are loaded.
,D/Init_SPenSdk_Jni( 5166): SPenSdk_init2
,D/Init_SPenSdk( 5166): Init - screen_width = 720, screen_height = 1280, maxCacheSize = 5 M
D/Init_SPenSdk( 5166): Total S Pen SDK Directory Size = 0
,D/Spen    ( 5166): initialize complete
,W/GalleryUtils( 5166): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,I/PackageManager( 2422): findPreferredActivity: No PreferredActivities set
,D/NearbySource( 5166): Nearby Source Create!
,D/NearbyContext( 5166): Nearby Context Create!
,E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5166): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 5166): Samsung link source created
,W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
D/SLinkClient( 5166): query devices()
,I/SELinux ( 5179): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5179):  
,I/SELinux ( 5179): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5179):  
I/SELinux ( 5179):  
,I/SELinux ( 5179): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5179): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5179): >>>>> Normal User
,E/dalvikvm( 5179): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
,E/SELinux ( 5179): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 5179): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5179): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5179): Added TimaKesytore provider
,W/ContextImpl( 4649): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1659 android.content.ContextWrapper.sendStickyBroadcast:439 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:841 <bottom of call stack> 
,I/DBG_DM  ( 4071): [3.19.140541][Line:838][onReceive] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 4071): [3.19.140541][Line:842][onReceive] status  = 1
,I/Process ( 4649): Sending signal. PID: 4649 SIG: 9
,E/DBG_DM  ( 4071): Warning!!! [3.19.140541][Line:853][onReceive] Device is ok
,I/DBG_DM  ( 4071): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.android.launcher2.Launcher
,D/dalvikvm( 5179): GC_CONCURRENT freed 2994K, 28% free 9571K/13268K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 5179): WAIT_FOR_CONCURRENT_GC blocked 24ms
I/ActivityManager( 2422): Process com.sec.android.app.sysscope (pid 4649) (adj 0) has died.
,I/DBG_DM  ( 4071): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 22 sec
,I/DBG_DM  ( 4071): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,E/DBG_DM  ( 4071): Warning!!! [3.19.140541][Line:224][xdmAgentTaskHandler] Network Status is not ready. DM Not Initialized
,I/DBG_DM  ( 4071): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.android.launcher2.Launcher
,I/SLinkClient( 5166): queryDevices : cursor.getCount() = [ 0 ]
,D/SLinkClient( 5166): onStorageUpdated(), uri = [ slink://slink ]
,E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5179): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
,W/ActivityManager( 2422): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
,E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5179): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
,D/GalleryCacheReady( 5166): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady( 5166): handleMeidaScanFinish()
,E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5166): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5166): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,I/SELinux ( 5204): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5204):  
,E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5166): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
,D/ContactProvider( 5166): getAllContactInfoList Start
,D/FaceInterface( 5166): requestFaceScan() is called.
,I/FaceInterface( 5166): startFaceScan() : waiting 5 sec
,I/ActivityManager( 2422): Killing 4126:com.samsung.android.scloud.sync/u0a64 (adj 15): empty #43
I/SELinux ( 5204): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5204):  
I/SELinux ( 5204):  
I/SELinux ( 5204): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5204): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5204): >>>>> Normal User
E/dalvikvm( 5204): >>>>> com.sec.android.app.music:service [ userId:0 | appId:10152 ]
E/SELinux ( 5204): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5204): in addTimaSignatureService
,W/LocalSuggestAlbumData( 5166): query fail: 
,W/LocalSuggestAlbumData( 5166): query fail: 
,D/TimaKeyStoreProvider( 5204): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5204): Added TimaKesytore provider
,D/dalvikvm( 2723): GC_EXPLICIT freed 353K, 30% free 10011K/14176K, paused 6ms+9ms, total 63ms
,D/ContactProvider( 5166): getAllContactInfoList End
,I/syncContacts( 5166): thread: 380, sync time = 230
D/dalvikvm( 5204): GC_CONCURRENT freed 2998K, 28% free 9572K/13272K, paused 5ms+1ms, total 35ms
,D/dalvikvm( 5204): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/com.samsung.musicplus.bitmapcache.BitmapCache( 5204): Allocated bitmap cache: 13421772
,E/CscFactoryReceiver( 2771): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 2771): Media DB Scanner finished.
,D/CscFactoryReceiver( 2771): start service to Set Ringtone
,D/CscFactoryReceiver( 2771): start service to Set Notification
,D/CscFactoryReceiver( 2771): start service to Set Alarmtone
,I/ActivityManager( 2422): Killing 4139:com.wssnps/1000 (adj 15): empty #43
D/CscUpdateService( 2771): onStart
E/CscUpdateService( 2771): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 2771): only ringtone update
D/CscUpdateService( 2771): onStart
E/CscParser( 2771): update(): xml file exist
E/CscUpdateService( 2771): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 2771): only notification update
E/CscParser( 2771): update(): xml file exist
D/CscUpdateService( 2771): onStart
E/CscUpdateService( 2771): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 2771): only alarmtone update
E/CscParser( 2771): update(): xml file exist
,I/SELinux ( 5222): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5222):  
,W/CSCSettings( 2771): Setting Ringtones (type) : 4
D/CscParser( 2771): AlarmTone: null
,W/CSCSettings( 2771): 1. Tag_Str: null
,W/CSCSettings( 2771): Setting Ringtones (type) : 1
,D/CscParser( 2771): RingTone: null
,W/CSCSettings( 2771): 1. Tag_Str: null
,W/CSCSettings( 2771): Setting Ringtones (type) : 2
,D/CscParser( 2771): MessageTone: null
,W/CSCSettings( 2771): 1. Tag_Str: null
,I/SELinux ( 5222): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5222):  
I/SELinux ( 5222):  
,I/SELinux ( 5222): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5222): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5222): >>>>> Normal User
,E/dalvikvm( 5222): >>>>> com.samsung.indexservice [ userId:0 | appId:10004 ]
,E/SELinux ( 5222): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5222): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5222): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5222): Added TimaKesytore provider
,D/dalvikvm( 5222): GC_CONCURRENT freed 3002K, 28% free 9572K/13276K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 5222): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/FactoryTestApp( 4983): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.MEDIA_SCANNER_FINISHED
,I/FactoryTestApp( 4983): [XMLDataStorage$parsingXML] FtClient => data parsing was completed.
D/FactoryTestApp( 4983): [FactoryTestBroadcastReceiver$onReceive] ACTION_MEDIA_SCANNER_FINISHED => XML data parsing was failed.
D/FactoryTestApp( 4983): [Support$Values.getString] id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 4983): [Support$Properties.get] property=ro.factory.factory_binary
,I/FactoryTestApp( 4983): [ModuleCommon$setMediascanningCounter]  
,I/FactoryTestApp( 4983): [ModuleCommon$getMediaScanningCount] get : 1
,I/IndexBroadcastProcessorService( 5222): lucene onHandleIntent-ACTION_MEDIA_SCANNER_FINISHED
,D/FactoryTest( 4983): User mode
I/FactoryTestApp( 4983): [ModuleCommon$getMediaScanningCount] get : 2
,I/FactoryTestApp( 4983): [ModuleCommon$getMediaScanningCount] get : 2
,D/FactoryTestApp( 4983): [Support$Values.getBoolean] id=FACTORY_TEST_APO, value=true
D/FactoryTestApp( 4983): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 4983): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
,I/FactoryTestApp( 4983): [ModuleCommon$isRunningFtClient] RUNNING_FTCLIENT : false
,I/FactoryTestApp( 4983): [FactoryTestBroadcastReceiver$USER MODE] BOOT_COMPLETE
,I/IndexBroadcastProcessorService( 5222): lucene systemReadyToIndex
,I/FactoryTestApp( 4983): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted] start DummyFtClient service for APO
,I/IndexService( 5222): lucene onCreate ...service,
W/ContextImpl( 4983): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:577 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:278 
,D/FactoryTestApp( 4983): [Support$Values.getBoolean] id=SUPPORT_BOOST_MEDIASCAN, value=true,
,I/FactoryTestApp( 4983): [FactoryTestBroadcastReceiver$wake lock] SUPPORT_BOOST_MEDIASCAN,
I/FactoryTestApp( 4983): [ModulePower$ModulePower] Create ModulePower
I/FactoryTestApp( 4983): [ModulePower$doMediaScanWakeLock] wake=false,
D/FactoryTest( 4983): User mode
,I/FactoryTestApp( 4983): [ModuleCommon$15 Test Ready flag] set
,I/FactoryTestApp( 4983): [ModuleCommon$isFirstBoot] before : false,
,E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 5222): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/GalleryCacheReady( 5166): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,D/FactoryTestApp( 4983): [DummyFtClient$onCreate] Create DummyFtClient service
,I/FactoryTestApp( 4983): [XMLDataStorage$parsingXML] FtClient => data parsing was completed.
,W/ContextImpl( 5222): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
D/FactoryTestApp( 4983): [DummyFtClient$onReceive] ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
D/FactoryTestApp( 4983): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 4983): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
D/GalleryCacheReady( 5166): handleMeidaScanFinish()
,D/FactoryTestApp( 4983): [Support$Values.getBoolean] id=SUPPORT_AUTO_WAKELOCK, value=false
D/FactoryTestApp( 4983): [DummyFtClient$onStartCommand] ...
,D/FactoryTestApp( 4983): [DummyFtClient$sendBootCompletedAndFinish] ...
D/FactoryTestApp( 4983): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 4983): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
,D/FactoryTestApp( 4983): [IPCWriterToSecPhoneService$ResponseWriter] Create IPCWriterToSecPhoneService
,I/FactoryTestApp( 4983): [IPCWriterToSecPhoneService$connectToSecPhoneService]  
W/ContextImpl( 4983): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:141 
,D/FaceInterface( 5166): requestFaceScan() is called.
D/GalaxyFinderApplication( 3813): [Slink platform] The state of Slink geocode service is true
D/LocationTagReadyService( 3813): SLink location service is enable. content://media/external/images/media not register
D/GalaxyFinderApplication( 3813): [Slink platform] The state of Slink geocode service is true
D/LocationTagReadyService( 3813): SLink location service is enable. content://media/external/video/media not register
,D/GalaxyFinderApplication( 3813): [Slink platform] The state of Slink geocode service is true
,W/LocalSuggestAlbumData( 5166): query fail: 
,I/FaceInterface( 5166): startFaceScan() : waiting 5 sec
,W/LocalSuggestAlbumData( 5166): query fail: 
,I/SELinux ( 5243): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5243):  
,I/LocationTagReadyService( 3813): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3813): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3813): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3813): [Slink platform] The state of Slink geocode service is true,
,I/dalvikvm( 5222): Could not find method java.lang.management.ManagementFactory.getPlatformMBeanServer, referenced from method org.apache.lucene.util.RamUsageEstimator.<clinit>,
W/dalvikvm( 5222): VFY: unable to resolve static method 5877: Ljava/lang/management/ManagementFactory;.getPlatformMBeanServer ()Ljavax/management/MBeanServer;
,D/dalvikvm( 5222): VFY: replacing opcode 0x71 at 0x01ed
,I/SELinux ( 5248): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5248):  
I/SELinux ( 5243): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5243):  
I/SELinux ( 5243):  
I/SELinux ( 5243): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5243): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5243): >>>>> Normal User
E/dalvikvm( 5243): >>>>> com.sec.phone [ userId:0 | appId:1001 ]
,E/SELinux ( 5243): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PackageManager( 2422): [MSG] SEND_PENDING_BROADCAST
D/PackageManager( 2422): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10012, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@430b8568, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,I/SELinux ( 5260): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5260):  
,I/GallerySearchProvider( 5166): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,D/TimaKeyStoreProvider( 5243): in addTimaSignatureService
,I/SELinux ( 5248): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5248):  
I/SELinux ( 5248):  
,I/SELinux ( 5248): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5248): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5248): >>>>> Normal User
,E/dalvikvm( 5248): >>>>> com.android.calendar [ userId:0 | appId:10144 ]
,E/SELinux ( 5248): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5243): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5243): Added TimaKesytore provider
,I/SELinux ( 5260): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5260):  
I/SELinux ( 5260):  
,I/SELinux ( 5260): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/TimaKeyStoreProvider( 5248): in addTimaSignatureService
E/SELinux ( 5260): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5260): >>>>> Normal User
,E/dalvikvm( 5260): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 5260): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5248): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5248): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 5260): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5260): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5260): Added TimaKesytore provider
,D/RegisteredServicesCache( 2777): empty dynamic service
,I/IndexService( 5222): lucene beginIndexing
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "sms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{430e4bc0 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 5260): GC_CONCURRENT freed 2996K, 28% free 9581K/13276K, paused 5ms+2ms, total 41ms
,D/dalvikvm( 5260): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 5243): GC_CONCURRENT freed 2999K, 28% free 9570K/13272K, paused 17ms+2ms, total 73ms
,D/dalvikvm( 5243): WAIT_FOR_CONCURRENT_GC blocked 57ms
,D/dalvikvm( 5248): GC_CONCURRENT freed 2992K, 28% free 9580K/13272K, paused 2ms+2ms, total 38ms
,D/dalvikvm( 5248): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/SELinux ( 5288): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5288):  
,I/InputReader( 2422): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "sms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 5288): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5288):  
I/SELinux ( 5288):  
,I/SELinux ( 5288): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5288): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5288): >>>>> Normal User
,E/dalvikvm( 5288): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,I/IndexService( 5222): lucene onDestroy start
,E/SELinux ( 5288): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/IndexService( 5222): lucene onDestroy end
,I/IndexService( 5222): lucene cleanupEverything start
I/IndexService( 5222): ERROR: null
,E/ParserThreadsListManager( 5222): Lucene Interrupt in run
I/IndexService( 5222): lucene cleanupEverything end
,I/Process ( 5222): Sending signal. PID: 5222 SIG: 9
,I/ActivityManager( 2422): Process com.samsung.indexservice (pid 5222) (adj 9) has died.
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 5222
,I/FactoryTestApp( 4983): [IPCWriterToSecPhoneService$onServiceConnected] connected done
,D/FactoryTestApp( 4983): [IPCWriterToSecPhoneService$write] Send Response Message to SecPhone
D/FactoryTestApp( 4983): [IPCWriterToSecPhoneService$write] Response ��
,D/TimaKeyStoreProvider( 5288): in addTimaSignatureService
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mms"
,D/TimaKeyStoreProvider( 5288): Cannot add TimaSignature Service, License check Failed
,I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/ActivityThread( 5288): Added TimaKesytore provider
,D/AT_Distributor( 1957): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/AT_Distributor( 1957): SetAtdStatus(), 1_1_0
D/AT_Distributor( 1957): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/FactoryTestApp( 4983): [IPCWriterToSecPhoneService$handleMessage] Send BOOT COMPLETED done
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 5288): GC_CONCURRENT freed 2999K, 28% free 9571K/13268K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 5288): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/MediaStoreImporter( 5079): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,V/KVNProvider( 5288): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5288): getFindoCursor query string : 
,V/KVNProvider( 5288): getTagSearchCursor() tagSearchCursor count : 0
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 5310): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5310):  
,I/SELinux ( 5314): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5314):  
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 2422): Killing 4151:com.samsung.android.app.accesscontrol/u0a67 (adj 15): empty #43
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 5310): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5310):  
I/SELinux ( 5310):  
,I/SELinux ( 5310): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5310): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5310): >>>>> Normal User
E/dalvikvm( 5310): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10145 ]
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SELinux ( 5310): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/SELinux ( 5314): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5314):  
I/SELinux ( 5314):  
,I/SELinux ( 5314): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/TimaKeyStoreProvider( 5310): in addTimaSignatureService
E/SELinux ( 5314): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5314): >>>>> Normal User
,E/dalvikvm( 5314): >>>>> com.android.providers.calendar [ userId:0 | appId:10045 ]
,E/SELinux ( 5314): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5310): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5310): Added TimaKesytore provider
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 5314): in addTimaSignatureService
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 5314): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5314): Added TimaKesytore provider
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 5310): GC_CONCURRENT freed 2998K, 28% free 9571K/13268K, paused 4ms+2ms, total 26ms
,D/dalvikvm( 5310): WAIT_FOR_CONCURRENT_GC blocked 16ms
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/dalvikvm( 5314): GC_CONCURRENT freed 3011K, 28% free 9560K/13272K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 5314): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/ActivityManager( 2422): Killing 4167:com.samsung.android.app.airwakeupview/u0a69 (adj 15): empty #43
I/SettingSearchManagerReceiver( 2771): onReceive : android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 2771): addSearchInfoDB
,I/SELinux ( 5334): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5334):  
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/GCoreNlp( 2735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/dalvikvm( 1924): GC_EXPLICIT freed 43K, 8% free 9507K/10252K, paused 3ms+3ms, total 32ms
I/SELinux ( 5334): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5334):  
I/SELinux ( 5334):  
,I/SELinux ( 5334): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5334): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5334): >>>>> Normal User
,E/dalvikvm( 5334): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10162 ]
,E/SELinux ( 5334): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 1924): GC_EXPLICIT freed <1K, 8% free 9507K/10252K, paused 2ms+3ms, total 26ms,
,D/TimaKeyStoreProvider( 5334): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5334): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5334): Added TimaKesytore provider
,D/dalvikvm( 1924): GC_EXPLICIT freed <1K, 8% free 9507K/10252K, paused 2ms+3ms, total 25ms
,D/dalvikvm( 5334): GC_CONCURRENT freed 2998K, 28% free 9577K/13272K, paused 3ms+1ms, total 24ms
,D/dalvikvm( 5334): WAIT_FOR_CONCURRENT_GC blocked 20ms,
,D/LocationProviderProxy( 2422): applying state to connected service,
,D/LocationProviderProxy( 2422): applying state to connected service,
,I/PowerManagerService( 2422): [PWL] Off : 5s ago,
I/PowerManagerService( 2422): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2422): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2422): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2422, ws=WorkSource{10045}) (elapsedTime=21758)
I/PowerManagerService( 2422): [PWL]       PARTIAL_WAKE_LOCK              'StartingAlertService' (uid=10144, pid=5248, ws=null) (elapsedTime=422)
,I/PowerManagerService( 2422): [PWL]       PARTIAL_WAKE_LOCK              'GCoreFlp' (uid=10012, pid=2735, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=22),
,W/ApplicationsProvider( 2955): Could not fetch usage stats,
W/ApplicationsProvider( 2955): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2955): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2955): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2955): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2955): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2955): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2955): ,	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2955): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2955): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2955): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2955): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2955): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/dalvikvm( 2422): GC_EXPLICIT freed 1992K, 11% free 24107K/27056K, paused 7ms+18ms, total 167ms,
,I/ActivityManager( 2422): Killing 4179:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty #43,
,I/SettingSearchManagerReceiver( 2771): endInsert,
,I/ActivityManager( 2422): Killing 4193:com.sec.android.nearby.mediaserver/u0a74 (adj 15): empty #43,
,D/AssistantMenuSettingSearch( 4205): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS,
,D/AssistantMenuSettingSearch( 4205): Make Setting DB,
,W/ContextImpl( 4205): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:123 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:35 ,
,I/knox    ( 4400): InnerIntentReceiver.onReceive() : com.sec.knox.seandroid.alarm.LOG_UPLOAD_ALARM_INTENT,
W/ContextImpl( 4400): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.InnerIntentReceiver.onReceive:171 android.app.ActivityThread.handleReceiver:2698 
,D/knox    ( 4400): KNOXAgentService. startJobThread() start,
D/knox    ( 4400): KNOXAgentService. JobThread()
D/knox    ( 4400): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4400): KNOXAgentService. startJobThread() wait
,D/knox    ( 4400): startFileChecker
D/knox    ( 4400): KNOXAgentService : onCreate()
,D/knox    ( 4400): KNOXAgentService : set alarms for deniallog and usage data upload
,I/knox    ( 4400): start checking file is exist to uploading
D/knox    ( 4400): KNOXAgentService : onDestroy().
,D/knox    ( 4400): ModuleBase.cancelAllAlarmManageModule()
D/knox    ( 4400): notiShow :0 / context pref : 2
,I/knox    ( 4400): denial log zip completed
,D/daemonapp( 4687): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4687): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4687): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4687): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 4687): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4687): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 4687): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4687): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 4687): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 4687): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4687): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/comdaemonstockapp( 4687): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: widgetappstockclockDAEMON_PROCESS_START
,D/comdaemonstockapp( 4687): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,D/comdaemonstockapp( 4687): [Daemon_Stock]>>> StockclockDaemonService.java:113 [0:0] isFirstRunning , false
,D/daemonapp( 4687): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4687): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4687): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2422): stay LED for fully charged
D/daemonapp( 4687): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/comsamsunglog( 4687): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4687): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4687): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4687): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 4687): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 4687): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
D/daemonapp( 4687): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:424 [0:0] today==null,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/daemonapp( 4687): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4687): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4687): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4687): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 4687): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4687): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4687): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4687): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 4687): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4687): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4687): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/daemonapp( 4687): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4687): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4687): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4687): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 4687): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4687): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 4687): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4687): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 4687): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4687): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4687): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4687): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/GCM     ( 2832): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/GCoreFlp( 2735): No location to return for getLastLocation()
,W/FusedLocationProvider( 2735): location=null
,I/ActivityManager( 2422): Killing 4218:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #43
,E/SPPClientService( 4898): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,I/SELinux ( 5364): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5364):  
,I/SELinux ( 5364): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5364):  
I/SELinux ( 5364):  
,I/SELinux ( 5364): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5364): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5364): >>>>> Normal User
,E/dalvikvm( 5364): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 5364): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 5364): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5364): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5364): Added TimaKesytore provider
,D/dalvikvm( 5364): GC_CONCURRENT freed 3007K, 28% free 9564K/13272K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 5364): WAIT_FOR_CONCURRENT_GC blocked 28ms
,E/SPPClientService( 5364): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5364): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 5364): PushLog.txt file is not deleted.
D/SPPClientService( 5364): PushLog.txt file is not deleted.
,D/SPPClientService( 5364): ============PushLog. stop!
,I/SELinux ( 5381): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5381):  
,I/ActivityManager( 2422): Killing 4230:com.blurb.checkout/u0a79 (adj 15): empty #43
,I/SELinux ( 5381): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5381):  
I/SELinux ( 5381):  
,I/SELinux ( 5381): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5381): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5381): >>>>> Normal User
,E/dalvikvm( 5381): >>>>> com.sec.spp.push:RemoteNotiProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 5381): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 5381): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5381): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5381): Added TimaKesytore provider
,D/dalvikvm( 5381): GC_CONCURRENT freed 3011K, 28% free 9566K/13276K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 5381): WAIT_FOR_CONCURRENT_GC blocked 25ms
,E/SPPClientService( 5381): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5381): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 5381): PushLog.txt file is not deleted.
D/SPPClientService( 5381): PushLog.txt file is not deleted.
,D/SPPClientService( 5381): ============PushLog. stop!
,D/NtpTrustedTime( 2422): forceRefresh() from cache miss
,D/NtpTrustedTime( 2422): forceRefresh Fail.
I/ActivityManager( 2422): Killing 4242:com.sec.knox.bridge/1000 (adj 15): empty #43
V/NetworkStats( 2422): performPollLocked(flags=0x3)
W/SocketClient( 1917): write error (Broken pipe)
,V/NetworkStats( 2422): performPollLocked() took 25ms
D/NtpTrustedTime( 2422): forceRefresh() from cache miss
D/NtpTrustedTime( 2422): forceRefresh Fail.
,E/MTPRx   ( 4995): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 4995): check value of boot_completed is1
,E/MTPRx   ( 4995): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4995): Sd-Card path/storage/extSdCard
E/MTPRx   ( 4995): Status for mount/Unmount :removed
,E/MTPRx   ( 4995): SDcard is not available
W/MTPRx   ( 4995): value of connected istrue
W/MTPRx   ( 4995): value of configured istrue
W/MTPRx   ( 4995): value of mtpEnabled istrue
,W/MTPRx   ( 4995): value of ptpEnabled isfalse
E/MTPRx   ( 4995): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 4995): mtpRunningStatus1
,E/MTPRx   ( 4995): MTP already launched. So return.
,I/SELinux ( 5400): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5400):  
,I/SELinux ( 5400): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5400):  
I/SELinux ( 5400):  
,I/SELinux ( 5400): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5400): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5400): >>>>> Normal User
,E/dalvikvm( 5400): >>>>> com.sec.android.diagmonagent [ userId:0 | appId:1000 ]
,E/SELinux ( 5400): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5400): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5400): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5400): Added TimaKesytore provider
D/dalvikvm( 4746): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4746): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4746): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4746): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4746): VFY: unable to resolve instance field 36
,D/dalvikvm( 4746): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4746): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4746): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4746): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4746): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4746): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4746): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42bcd288
,D/dalvikvm( 4746): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42bcd288
,D/dalvikvm( 4746): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42bcd288, skipping init
,D/dalvikvm( 4746): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42bcd288
,D/dalvikvm( 4746): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42bcd288
,V/JNIHelp ( 4746): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 5400): GC_CONCURRENT freed 2997K, 28% free 9579K/13276K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 5400): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 4746): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42bcd288
,D/dalvikvm( 4746): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42bcd288
D/dalvikvm( 4746): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42bcd288
,D/dalvikvm( 4746): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42bcd288
,I/FactoryTestApp( 4983): [IPCWriterToSecPhoneService$disConnectSecPhoneService]  
,I/DBG_DIAGMONDM( 5400): [1.140541.0531][Line:472][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_DIAGMONDM( 5400): [1.140541.0531][Line:48][onCreate] myUserId : 0
,I/ProviderInstaller( 4746): Installed default security provider GmsCore_OpenSSL
,I/DBG_DIAGMONDM( 5400): [1.140541.0531][Line:376][xdbDMffs_Init] 
,I/DBG_DIAGMONDM( 5400): [1.140541.0531][Line:70][onCreate] nStatus : 0
,I/DBG_DIAGMONDM( 5400): [1.140541.0531][Line:24][onReceive] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 2422): Killing 4254:com.sec.android.app.clockpackage/u0a88 (adj 15): empty #43
I/DBG_DM  ( 4071): [3.19.140541][Line:139][onReceive] com.sec.intent.action.SYSSCOPESTATUS
,I/SELinux ( 5418): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5418):  
,I/SELinux ( 5418): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5418):  
I/SELinux ( 5418):  
,I/SELinux ( 5418): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5418): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5418): >>>>> Normal User
,E/dalvikvm( 5418): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 5418): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5418): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5418): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5418): Added TimaKesytore provider
,D/dalvikvm( 5418): GC_CONCURRENT freed 3002K, 28% free 9574K/13276K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 5418): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/Icing.InternalIcingCorporaProvider( 5418): Updating corpora: A: com.google.android.gms, C: MAYBE
,I/SELinux ( 5432): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5432):  
,I/FaceInterface( 5166): startFaceScan() : going on
,D/FaceInterface( 5166): startFaceScan() is called.
,D/ContentApp( 2723): startScan() is called.
,D/FaceValue( 2723): mSleepTime: 800
,D/FaceValue( 2723): mMaxThreadNum: 2
,W/FaceValue( 2723): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
D/ContentApp( 2723): startScan() is end.
D/ContentApp( 2723): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 2723): isNeedToRestore : start
,I/SELinux ( 5432): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5432):  
I/SELinux ( 5432):  
,I/SELinux ( 5432): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5432): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SELinux ( 5439): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5439):  
E/dalvikvm( 5432): >>>>> Normal User
,E/dalvikvm( 5432): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10073 ]
,E/SELinux ( 5432): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/LocationManagerService( 2422): getProviders()=[passive]
,D/TimaKeyStoreProvider( 5432): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5432): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5432): Added TimaKesytore provider
,I/SELinux ( 5439): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5439):  
I/SELinux ( 5439):  
,I/SELinux ( 5439): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5439): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5439): >>>>> Normal User
,E/dalvikvm( 5439): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 5439): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5439): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5439): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5439): Added TimaKesytore provider
,D/dalvikvm( 5432): GC_CONCURRENT freed 2999K, 28% free 9577K/13276K, paused 11ms+2ms, total 40ms
,D/dalvikvm( 5432): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/FileShare-Server( 5432): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,I/SELinux ( 5462): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5462):  
I/ActivityManager( 2422): Killing 4267:com.samsung.android.app.colorblind/1000 (adj 15): empty #43
,D/dalvikvm( 5439): GC_CONCURRENT freed 3003K, 28% free 9572K/13272K, paused 4ms+4ms, total 41ms
,D/dalvikvm( 5439): WAIT_FOR_CONCURRENT_GC blocked 31ms
,I/SELinux ( 5462): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5462):  
I/SELinux ( 5462):  
,I/SELinux ( 5462): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5462): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5462): >>>>> Normal User
,E/dalvikvm( 5462): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 5462): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5462): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5462): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5462): Added TimaKesytore provider
,I/ActivityManager( 2422): Killing 4279:com.dropbox.android/u0a95 (adj 15): empty #43
,D/dalvikvm( 5462): GC_CONCURRENT freed 3012K, 28% free 9563K/13276K, paused 3ms+3ms, total 29ms
,D/dalvikvm( 5462): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/SELinux ( 5477): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5477):  
,I/ActivityManager( 2422): Killing 4300:com.sec.esdk.elm/u0a98 (adj 15): empty #43
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{42faf500 u0 com.google.android.gms/.gcm.GcmService}
,I/SELinux ( 5477): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5477):  
I/SELinux ( 5477):  
,I/SELinux ( 5477): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5477): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5477): >>>>> Normal User
,E/dalvikvm( 5477): >>>>> com.google.android.apps.plus [ userId:0 | appId:10133 ]
,E/SELinux ( 5477): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5477): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5477): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5477): Added TimaKesytore provider
,I/FaceInterface( 5166): startFaceScan() : going on,
,D/FaceInterface( 5166): startFaceScan() is called.
,D/ContentApp( 2723): startScan() is called.,
D/ContentApp( 2723): startScan() is end.,
D/ContentApp( 2723): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 2723): isNeedToRestore : start,
,D/FactoryTestApp( 4983): [DummyFtClient$onDestroy] Destroy DummyFtClient service,
D/FactoryTestApp( 4983): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm,
,I/FactoryTestApp( 4983): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm,
I/FactoryTestApp( 4983): [ModuleCommon$isRunningFtClient] RUNNING_FTCLIENT : false,
,D/FactoryTestApp( 4983): [DummyFtClient$onDestroy] kill process
,I/Process ( 4983): Sending signal. PID: 4983 SIG: 9,
,D/dalvikvm( 5477): GC_CONCURRENT freed 2987K, 28% free 9591K/13276K, paused 8ms+2ms, total 37ms,
,D/dalvikvm( 5477): WAIT_FOR_CONCURRENT_GC blocked 22ms,
,I/ActivityManager( 2422): Process com.sec.factory (pid 4983) (adj 0) has died.,
,I/Icing.InternalIcingCorporaProvider( 5418): UpdateCorporaTask done [took 927 ms] updated apps [took 927 ms] ,
,I/ActivityManager( 2422): Killing 4315:com.sec.android.fwupgrade/1000 (adj 15): empty #43,
,D/dalvikvm( 2422): GC_EXPLICIT freed 1492K, 12% free 24047K/27056K, paused 9ms+24ms, total 269ms,
,D/BezelQuickConnect( 4474): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED,
,D/BezelQuickConnect( 4474): BezelBroadcastReceiver - packageName : com.google.android.gms,
,I/ActivityManager( 2422): Killing 4329:com.sec.factory.camera/1000 (adj 15): empty #43
,D/PackageBroadcastService( 3269): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
I/dalvikvm( 4913): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4913): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4913): VFY: replacing opcode 0x6e at 0x0017,
,I/PackageBroadcastService( 3269): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 3269): updateResources: need to parse f{com.google.android.gms},
W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/KeyguardViewMediator( 2581): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,W/ContextImpl( 5079): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 ,
,D/LockPatternUtils( 2581): isPcwEnable = 10,
,D/KeyguardViewMediator( 2581): in doKeyguardLocked mIsRollUp false null,
,I/iu.UploadsManager( 5477): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/PersonaManager( 2581): isKioskContainerExistOnDevice
,W/ContextImpl( 5079): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/LockPatternUtils( 2581): isPcwEnable = 10
D/LockPatternUtils( 2581): isPcwEnable = 10
,D/KeyguardViewMediator( 2581): doKeyguard: not showing because lockscreen is off
,D/CacheService( 5079): onCreate
,I/SettingSearch/SearchIntentReceiver( 5010): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 5010): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SearchIntentReceiver( 5010): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 5010): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 5010): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,D/CacheService( 5079): onBind
,D/dalvikvm( 3269): GC_CONCURRENT freed 1937K, 20% free 11440K/14168K, paused 9ms+13ms, total 103ms
,I/SettingSearch/SettingsSearchManager( 5010): Infomation -> numtitleinfo : 0 numSearchinfo : 319
,I/MusicLeanback( 5079): Conditions not met for autocaching.
,I/MusicLeanback( 5079): Stop autocaching.
,D/CacheService( 5079): onDestroy
,I/iu.UploadsManager( 5477): End new media; added: 0, uploading: 0, time: 326 ms
,I/iu.Environment( 5477): update battery state; isPlugged? true*
,I/iu.Environment( 5477): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.FingerprintManager( 5477): Start processing all media
,I/iu.FingerprintManager( 5477): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5477): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 5477): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 5477): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 5477): Finished generating fingerprints; 0.058 seconds
,I/iu.FingerprintManager( 5477):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/SettingSearch/SettingsSearchManager( 5010):  Infomation -> getItem size : 319
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 340, Delta = -10
,I/Icing   ( 3269): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
,D/Icing   ( 3269): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 3269): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
,I/Icing   ( 3269): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,I/Icing   ( 3269): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,D/dalvikvm( 5010): GC_EXPLICIT freed 666K, 26% free 9895K/13268K, paused 3ms+7ms, total 49ms
,D/dalvikvm( 5334): GC_EXPLICIT freed 907K, 24% free 10153K/13272K, paused 3ms+10ms, total 51ms
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{430fdc50 u0 com.samsung.android.MtpApplication/.MtpService}
,I/ActivityManager( 2422): Killing 4341:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
,D/dalvikvm( 2422): GC_EXPLICIT freed 818K, 12% free 24017K/27056K, paused 8ms+15ms, total 209ms
,I/CheckinService( 3269): Done disabling old GoogleServicesFramework version
,D/dalvikvm( 5334): GC_EXPLICIT freed 1027K, 25% free 10014K/13272K, paused 3ms+8ms, total 47ms
,D/dalvikvm( 5010): GC_EXPLICIT freed 332K, 26% free 9926K/13268K, paused 5ms+6ms, total 46ms
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2422): [PWL] Off : 15s ago
,D/dalvikvm( 5334): GC_EXPLICIT freed 891K, 25% free 10015K/13272K, paused 3ms+9ms, total 47ms
,D/dalvikvm( 5010): GC_EXPLICIT freed 355K, 26% free 9938K/13268K, paused 3ms+7ms, total 46ms
,V/AlarmManager( 2422): waitForAlarm result :8
,D/dalvikvm( 5334): GC_EXPLICIT freed 902K, 25% free 10025K/13272K, paused 3ms+9ms, total 47ms
,D/dalvikvm( 5010): GC_EXPLICIT freed 362K, 26% free 9938K/13268K, paused 3ms+6ms, total 42ms
,E/Watchdog( 2422): !@Sync 2
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{42ef4c98 u0 com.sec.android.gallery3d/.app.BackgroundCache}
,V/AlarmManager( 2422): waitForAlarm result :8
D/NtpTrustedTime( 2422): forceRefresh() from cache miss
D/NtpTrustedTime( 2422): forceRefresh Fail.
,D/dalvikvm( 2422): GC_EXPLICIT freed 434K, 12% free 23970K/27056K, paused 7ms+16ms, total 207ms
,D/dalvikvm( 5334): GC_EXPLICIT freed 905K, 25% free 10023K/13272K, paused 3ms+8ms, total 45ms
W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5010): GC_EXPLICIT freed 360K, 26% free 9946K/13268K, paused 3ms+5ms, total 42ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 330, Delta = -10
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/dalvikvm( 5334): GC_EXPLICIT freed 882K, 25% free 10014K/13272K, paused 3ms+8ms, total 45ms
,D/dalvikvm( 5010): GC_EXPLICIT freed 352K, 25% free 9952K/13268K, paused 3ms+6ms, total 42ms
,D/dalvikvm( 5334): GC_EXPLICIT freed 874K, 25% free 10019K/13272K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 5010): GC_EXPLICIT freed 352K, 25% free 9967K/13268K, paused 4ms+6ms, total 43ms
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 2422): GC_EXPLICIT freed 360K, 12% free 23957K/27056K, paused 7ms+16ms, total 206ms
,D/dalvikvm( 5334): GC_EXPLICIT freed 874K, 25% free 10016K/13272K, paused 4ms+8ms, total 46ms
,D/dalvikvm( 5010): GC_EXPLICIT freed 343K, 25% free 9979K/13268K, paused 3ms+6ms, total 42ms
,D/dalvikvm( 5334): null clazz in OP_INSTANCE_OF, single-stepping
,W/IcingInternalCorpora( 3269): getNumBytesRead when not calculated.
,D/dalvikvm( 5334): GC_EXPLICIT freed 873K, 25% free 10015K/13272K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 5010): GC_EXPLICIT freed 352K, 25% free 9997K/13268K, paused 3ms+6ms, total 43ms
,D/dalvikvm( 5334): GC_EXPLICIT freed 871K, 25% free 10013K/13272K, paused 3ms+9ms, total 45ms
,D/dalvikvm( 5010): GC_EXPLICIT freed 353K, 25% free 10009K/13268K, paused 3ms+6ms, total 44ms
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5334): GC_CONCURRENT freed 1477K, 21% free 10502K/13272K, paused 2ms+9ms, total 36ms
,I/SettingSearch/SearchIntentReceiver( 5010): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 5010): LOCALE_CHANGED call search setting db finish!!
V/AlarmManager( 2422): waitForAlarm result :4
V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Finsky  ( 4913): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/dalvikvm( 4913): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4913): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4913): VFY: replacing opcode 0x62 at 0x0038
I/PowerManagerService( 2422): [PWL] Off : 30s ago
I/PowerManagerService( 2422): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2422): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2422): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2422, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=6)
V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SettingSearch/SearchIntentReceiver( 5010): InitTitleDBThread start --> mDoingInitTitleDB : true
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 330, Delta = 0
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SettingSearch/SearchIntentReceiver( 5010): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 5010): LOCALE_CHANGED call search setting db finish!!
,I/System.out( 4913): Thread-357(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4913): Thread-357(ApacheHTTPLog):isShipBuild true
,I/System.out( 4913): Thread-357(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 4913): Thread-357 calls detatch()
,W/Finsky  ( 4913): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/dalvikvm( 2422): GC_EXPLICIT freed 372K, 12% free 23969K/27056K, paused 12ms+16ms, total 212ms
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4913): Thread-358 calls detatch()
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4913): Thread-357 calls detatch()
,W/Finsky  ( 4913): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/dalvikvm( 4913): GC_CONCURRENT freed 1749K, 19% free 10898K/13344K, paused 4ms+5ms, total 40ms
,D/dalvikvm( 4913): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4913): Thread-358 calls detatch()
,W/Finsky  ( 4913): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 4913): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Finsky  ( 4913): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/WearableService( 2735): callingUid 10012, callindPid: 2735
,D/DeviceConnectionService( 2735): client connected with version: 8296000
,D/Finsky  ( 4913): [381] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4913): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4913): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
,D/BatteryService( 2422): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = -10,
,I/Icing   ( 3269): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music,
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,I/Icing   ( 3269): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 4913): GC_CONCURRENT freed 1833K, 19% free 11110K/13644K, paused 3ms+5ms, total 37ms
,D/dalvikvm( 4913): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/Finsky  ( 4913): [370] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4913): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/Watchdog( 2422): !@Sync 3,
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
,V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___,
V/AlarmManager( 2422): <AppSync3 Whitelist>,
,V/AlarmManager( 2422): (AppSync) ### 0 added ###,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2,
,I/PowerManagerService( 2422): [PWL] Off : 50s ago,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/FactoryTest( 4995): Not factory mode,
,D/FactoryTest( 4995): Not factory mode. isFactoryMode() returend false,
D/MTPRx   ( 4995): DRIVER_TIME_OUT 60s lapsed,
,D/MTPRx   ( 4995): still no open session command from host, so toast,
W/ContextImpl( 4995): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4995): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy( 2422): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@4,
,W/ActivityManager( 2422): mDVFSHelper.acquire(),
I/SurfaceFlinger( 1923): id=15 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1923): id=16 createSurf (16x16),-1 flag=20004, EimLayer
,D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
,D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1,
,E/MTPRx   ( 4995): started activity for popup,
,I/SQLiteSecureOpenHelper( 3522): getWritableDatabase(pwd),
,I/SQLiteSecureOpenHelper( 3522): getDatabaseLocked(b,b,pwd)...,
,E/SettingsReceiverActivity( 4995): PREF_DONT_ASK_AGAIN : true,
,D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false,
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false,
D/StatusBarManagerService( 2422): tr p:2801,o:f
D/StatusBarManagerService( 2422): semi p:2801,o:f
W/InputMethodManagerService( 2422): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@431d3c90 attribute=android.view.inputmethod.EditorInfo@42d8ada8, token = android.os.BinderProxy@42a29f40
,D/SettingsReceiverActivity( 4995): dev.kiessupport is : TRUE,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@4,
,W/ActivityManager( 2422): mDVFSHelper.release(),
,D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@8,
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4,
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@8,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/SurfaceFlinger( 1923): id=16 Removed EimLayer (5/10),
I/SurfaceFlinger( 1923): id=15 Removed EimLayer (4/9),
,I/SurfaceFlinger( 1923): id=16 Removed EimLayer (-2/9)
,I/SurfaceFlinger( 1923): id=15 Removed EimLayer (-2/9),
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2422): [PWL] Off : 75s ago,
,E/Watchdog( 2422): !@Sync 4
,V/AlarmManager( 2422): waitForAlarm result :4,
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/NtpTrustedTime( 2422): forceRefresh() from cache miss,
,D/NtpTrustedTime( 2422): forceRefresh Fail.,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2422): [PWL] Off : 105s ago,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 5,
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/ClearcutLoggerApiImpl( 2832): disconnect managed GoogleApiClient,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2422): !@Sync 6,
,V/AlarmManager( 2422): waitForAlarm result :4,
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/NtpTrustedTime( 2422): forceRefresh() from cache miss,
,D/NtpTrustedTime( 2422): forceRefresh Fail.,
,D/dalvikvm( 2832): GC_EXPLICIT freed 1641K, 19% free 10817K/13228K, paused 5ms+8ms, total 63ms,
,I/VacuumService( 2735): Vacuum at: now=1457078849772 tag=VacuumService,
,I/PowerManagerService( 2422): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,E/Watchdog( 2422): !@Sync 7,
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/PowerManagerService( 2422): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 8,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2422): [PWL] Off : 225s ago,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 9,
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4,
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2422): initializing...,
I/TLC_TIMA_PKM_initialize( 2422): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2422): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2422): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2422): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2422): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2422): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2422): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 2422): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2422): device_id = 0x0
I/TZ: mc_tlc_communication( 2422): tlc_open() was called
,I/TZ: mc_tlc_communication( 2422): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2422): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2422): Opening the session
,I/TZ: mc_tlc_communication( 2422): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2422): Trustlet response is completed,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2422): [PWL] Off : 275s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2422): GC_FOR_ALLOC freed 3348K, 15% free 24131K/28368K, paused 205ms, total 205ms
D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 6354): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6354):  
,I/SELinux ( 6354): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6354):  
I/SELinux ( 6354):  
,I/SELinux ( 6354): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6354): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6354): >>>>> Normal User
,E/dalvikvm( 6354): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 6354): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6354): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6354): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6354): Added TimaKesytore provider
,D/dalvikvm( 6354): GC_CONCURRENT freed 3014K, 28% free 9563K/13276K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 6354): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/ActivityManager( 2422): Killing 4384:com.samsung.helphub/1000 (adj 15): empty #43
,E/Watchdog( 2422): !@Sync 11
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient( 1917): write error (Broken pipe)
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2422): !@Sync 12
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2422): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 13
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 10
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 14
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 15
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 16
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2422): [PWL] Off : 455s ago
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 17
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 18
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 525s ago
,E/Watchdog( 2422): !@Sync 19
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/dalvikvm( 2422): GC_FOR_ALLOC freed 2717K, 16% free 24079K/28584K, paused 200ms, total 200ms
D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 21
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 2422): waitForAlarm result :4
,D/LightsService( 2422): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
D/Sensors ( 2422): LightSensor setDelay = 200000000
D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/Sensors ( 2422): Light sensor flush: not enabled 0
D/Sensors ( 2422): LightSensor enable = 1
D/Sensors ( 2422): LightSensor enableSensor = 1
D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/PowerManagerService( 2422): [PWL] Off : 600s ago
,I/PowerManagerService( 2422): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2422): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2422): [PWL]       PARTIAL_WAKE_LOCK              'Event Log Service' (uid=10012, pid=3269, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=29)
,I/EventLogService( 3269): Aggregate from 1457077452270 (log), 1457077452270 (data)
,D/Sensors ( 2422): LightSensor enable = 0
,D/Sensors ( 2422): LightSensor enableSensor = 0
,D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 16
,D/SensorManager( 2422): unregisterListener ::   
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 22
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 23
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2422): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
V/AlarmManager( 2422): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/dalvikvm( 2422): Jit: resizing JitTable from 8192 to 16384
E/Watchdog( 2422): !@Sync 24
,I/PowerManagerService( 2422): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 25
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 26
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 765s ago
,E/Watchdog( 2422): !@Sync 27
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm( 3664): GC_CONCURRENT freed 2866K, 27% free 9730K/13304K, paused 11ms+3ms, total 58ms
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 28
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 29
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm( 2422): GC_FOR_ALLOC freed 2580K, 16% free 24135K/28584K, paused 177ms, total 177ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 855s ago
I/PowerManagerService( 2422): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2422): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2422): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2422, ws=null) (elapsedTime=3285)
,E/Watchdog( 2422): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 31
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 32
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 33
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,I/PowerManagerService( 2422): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 34
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 35
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 36
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 37
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/dalvikvm( 2422): GC_FOR_ALLOC freed 2449K, 16% free 24108K/28584K, paused 193ms, total 193ms
D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 38
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 39
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1155s ago
I/PowerManagerService( 2422): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2422): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2422): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2422, ws=null) (elapsedTime=3318)
,E/Watchdog( 2422): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 41
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2832): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 2422): waitForAlarm result :8
,I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2422): LightSensor setDelay = 200000000
,D/LightsService( 2422): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/Sensors ( 2422): Light sensor flush: not enabled 0
D/Sensors ( 2422): LightSensor enable = 1
D/Sensors ( 2422): LightSensor enableSensor = 1
D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2422): LightSensor enable = 0
,D/Sensors ( 2422): LightSensor enableSensor = 0
,D/SensorManager( 2422): unregisterListener ::   
D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1200000ms),D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): stay LED for fully charged
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
D/AndroidRuntime( 8952): 
D/AndroidRuntime( 8952): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8952): CheckJNI is OFF
D/AndroidRuntime( 8952): setted country_code = Poland
D/AndroidRuntime( 8952): setted countryiso_code = PL
D/AndroidRuntime( 8952): setted sales_code = PLS
D/AndroidRuntime( 8952): readGMSProperty: start
D/AndroidRuntime( 8952): readGMSProperty: already setted!!
D/AndroidRuntime( 8952): readGMSProperty: end
D/AndroidRuntime( 8952): addProductProperty: start
D/dalvikvm( 8952): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 8952): Added shared lib libjavacore.so 0x0
D/dalvikvm( 8952): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 8952): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 8952): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 8952): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 8952): failed to load memtrack module: -2
D/dalvikvm( 8952): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 8952): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2422): START PACKAGE DELETE: observer{1121364776}
D/PackageManager( 2422): pkg{<packageName>}
D/PackageManager( 2422): user{0}
D/ApplicationPolicy( 2422): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2422): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2422): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2422): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager( 2422): [MSG] DELETE_PACKAGE_AS_USER
D/dalvikvm( 2422): GC_EXPLICIT freed 1241K, 16% free 24112K/28584K, paused 5ms+10ms, total 152ms
D/AndroidRuntime( 8952): Shutting down VM
D/PackageManager( 2422): return delete result to caller: 1121364776
D/PackageManager( 2422): returnCode: -1
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "sms"
D/dalvikvm( 8952): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+0ms, total 3ms
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :

```
