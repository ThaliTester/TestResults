#### Test 58380500a584679_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
D/lights  ( 2403): lcd : 0 +
D/lights  ( 2403): lcd : 0 -
D/MISC PowerHAL( 2403): miscpower_set_interactive: /sys/class/input/input1/enabled
D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/input/input1/enabled: 0
--------- beginning of /dev/log/system
D/PowerManagerService( 2403): blankAllDisplays() is called.
D/PowerManagerService( 2403): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2403): [PWL] sb acquire: PowerManagerService.Broadcasts
V/WindowOrientationListener( 2403): WindowOrientationListener disabled
D/SensorService( 2403): AutoRotationSensor::activate (ident=0x88491e78, enabled=0)
I/Sensors ( 2403): HAL: batch Dry Run is complete
D/KeyguardViewMediator( 2578): onScreenTurnedOff(3)
D/PowerManagerService( 2403): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2403): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SensorManager( 2403): unregisterListener ::   
D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/InputDispatcher( 2403): setInputDispatchMode: enabled=0, frozen=0
D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/PowerManagerService( 2403): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SurfaceFlinger( 1920): Screen released, type=0 flinger=0x40c36550
D/LockPatternUtils( 2578): isPcwEnable = 10
D/LockPatternUtils( 2578): isPcwEnable = 10
D/Launcher.HomeView( 2774): onPause
E/SPPClientService( 5058): [b] __InitReply__
D/StatusBarManagerService( 2403): tr p:2774,o:f
D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/KeyguardViewMediator( 2578): setting alarm to turn off keyguard, seq = 2
D/LightsService( 2403): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2403) 
I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
D/Sensors ( 2403): LightSensor setDelay = 200000000
D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
D/Sensors ( 2403): Light sensor flush: not enabled 0
D/Sensors ( 2403): LightSensor enable = 1
D/Sensors ( 2403): LightSensor enableSensor = 1
D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2403): turn on LED for fully charged
D/VibratorService( 2403): JNI vibratorOff()
D/Launcher.HomeView( 2774): onStop
I/WifiTrafficPoller( 2403): evaluateTrafficStatsPolling
D/STATUSBAR-NotificationService( 2403): ACTION_SCREEN_OFF
D/LightsService( 2403): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2403) 
D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2403): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
D/IpRemoteDisplayController( 2403): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 2403): Bridge Server is not available
D/PersonaManagerService( 2403): ACTION_SCREEN_OFF onReceive
D/SurfaceControl( 2403): Excessive delay in blankDisplay() while turning screen off: 216ms
I/libsuspend( 2403): !@[s] autosuspend_autosleep_enable
I/libsuspend( 2403): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2403): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 217ms
D/PersonaManagerServiceHandler( 2403): MSG_ACTION_SCREEN_OFF called
D/PowerManagerService( 2403): SecHardwareInterface.setBatteryADC : false
D/STATUSBAR-PhoneStatusBar( 2578):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2578): makeExpandedInvisible
I/PowerManagerService( 2403): [PWL] Off : 0s ago
D/PhoneStatusBarView( 2578): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2578):      ACTION_SCREEN_OFF is finished!!!! 
I/PowerManagerService( 2403): [PWL]   PowerManagerService.Broadcasts: ref count=1
I/NfcService( 2755): applyRouting return - 2 
E/NfcService( 2755): callback == null
I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(28)
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
D/LockPatternUtils( 2578): isPcwEnable = 10
D/Sensors ( 2403): LightSensor enable = 0
D/Sensors ( 2403): LightSensor enableSensor = 0
D/LightsService( 2403): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager( 2403): unregisterListener ::   
D/lights  ( 2403): led_pattern : 5 +
D/lights  ( 2403): led_pattern : 5 -
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SSRMv2:SIOP( 2403): SIOP:: AP = 360, Delta = 0
D/QuickConnect[1.1][2] ( 4643): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 4643): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4643): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4227a5b0
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4227a5b0
D/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4643): stopLeScan()
D/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - call stopLeScan() complete
D/PowerManagerService( 2403): [PWL] sb release: PowerManagerService.Broadcasts
V/AlarmManager( 2403): waitForAlarm result :4
D/Finsky  ( 5077): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/dalvikvm( 5077): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5077): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5077): VFY: replacing opcode 0x62 at 0x0038
V/GLSActivity( 2846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/System.out( 5077): Thread-367(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 5077): Thread-367(ApacheHTTPLog):isShipBuild true
I/System.out( 5077): Thread-367(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/IcingInternalCorpora( 3288): getNumBytesRead when not calculated.
D/AndroidRuntime( 6090): 
D/AndroidRuntime( 6090): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6090): CheckJNI is OFF
D/AndroidRuntime( 6090): setted country_code = Poland
D/AndroidRuntime( 6090): setted countryiso_code = PL
D/AndroidRuntime( 6090): setted sales_code = PLS
D/AndroidRuntime( 6090): readGMSProperty: start
D/AndroidRuntime( 6090): readGMSProperty: already setted!!
D/AndroidRuntime( 6090): readGMSProperty: end
D/AndroidRuntime( 6090): addProductProperty: start
I/System.out( 5077): Thread-367 calls detatch()
D/dalvikvm( 6090): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6090): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6090): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6090): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6090): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
V/GLSActivity( 2846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/dalvikvm( 2829): WAIT_FOR_CONCURRENT_GC blocked 1ms
D/dalvikvm( 2829): GC_EXPLICIT freed 352K, 26% free 10296K/13760K, paused 3ms+7ms, total 55ms
E/memtrack( 6090): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6090): failed to load memtrack module: -2
D/dalvikvm( 6090): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/dalvikvm( 5871): GC_EXPLICIT freed 901K, 28% free 10010K/13720K, paused 3ms+8ms, total 45ms
I/qtaguid ( 5077): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5077): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5077): untagSocket(68) failed with errno -22
I/System.out( 5077): Thread-366 calls detatch()
D/Finsky  ( 5077): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
D/AndroidRuntime( 6090): Calling main entry com.android.commands.am.Am
D/dalvikvm( 2846): GC_EXPLICIT freed 1084K, 21% free 10837K/13688K, paused 7ms+7ms, total 60ms
V/GLSActivity( 2846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 6090): Shutting down VM
D/dalvikvm( 6090): GC_CONCURRENT freed 99K, 13% free 714K/816K, paused 0ms+0ms, total 5ms
,I/qtaguid ( 5077): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5077): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5077): untagSocket(68) failed with errno -22
,I/System.out( 5077): Thread-367 calls detatch()
,D/dalvikvm( 5077): GC_CONCURRENT freed 2087K, 24% free 10479K/13716K, paused 5ms+5ms, total 67ms
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5077): GC_CONCURRENT freed 744K, 15% free 11782K/13716K, paused 4ms+4ms, total 53ms
,D/dalvikvm( 5077): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 5077): GC_FOR_ALLOC freed 922K, 15% free 12600K/14760K, paused 37ms, total 37ms
,D/dalvikvm( 5077): GC_FOR_ALLOC freed 1759K, 22% free 12951K/16408K, paused 34ms, total 35ms
,I/dalvikvm( 2403): Jit: resizing JitTable from 8192 to 16384
I/ActivityManager( 2403): Waited long enough for: ServiceRecord{43223df8 u0 com.sec.android.gallery3d/.app.BackgroundCache}
,D/dalvikvm( 5871): GC_EXPLICIT freed 905K, 28% free 10009K/13720K, paused 2ms+5ms, total 30ms
,D/dalvikvm( 2829): GC_EXPLICIT freed 359K, 26% free 10302K/13760K, paused 4ms+5ms, total 32ms
,D/dalvikvm( 2403): GC_EXPLICIT freed 544K, 13% free 24484K/28012K, paused 7ms+28ms, total 241ms
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 299, prevStep = 4, currStep = 4
V/AlarmManager( 2403): waitForAlarm result :8
V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager( 2403): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2403): <AppSync3 Whitelist>
V/AlarmManager( 2403): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
V/GLSActivity( 2846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 2403): waitForAlarm result :4
,D/KeyguardViewMediator( 2578): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/LockPatternUtils( 2578): isPcwEnable = 10
D/KeyguardViewMediator( 2578): in doKeyguardLocked mIsRollUp false null
D/PersonaManager( 2578): isKioskContainerExistOnDevice
D/LockPatternUtils( 2578): isPcwEnable = 10
D/LockPatternUtils( 2578): isPcwEnable = 10
D/KeyguardViewMediator( 2578): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService( 2403): [PWL] Off : 5s ago
,I/qtaguid ( 5077): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5077): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5077): untagSocket(68) failed with errno -22
,I/System.out( 5077): Thread-366 calls detatch()
,D/dalvikvm( 5871): GC_EXPLICIT freed 876K, 28% free 10007K/13720K, paused 3ms+9ms, total 47ms
,D/dalvikvm( 2829): GC_EXPLICIT freed 348K, 26% free 10302K/13760K, paused 4ms+16ms, total 75ms
,D/Finsky  ( 5077): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/WearableService( 2733): callingUid 10012, callindPid: 2733
,D/Finsky  ( 5077): [390] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 2733): client connected with version: 8296000
,D/Finsky  ( 5077): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5077): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5077): Thread-377(HTTPLog):isShipBuild true
,I/System.out( 5077): Thread-377(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5871): GC_EXPLICIT freed 874K, 28% free 10012K/13720K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 2829): GC_EXPLICIT freed 352K, 26% free 10305K/13760K, paused 4ms+7ms, total 57ms
,D/PackageManager( 2403): [MSG] MCS_UNBIND
,I/PackageManager( 2403): calling disconnectService()
,D/PackageManager( 2403): Trying to unbind to DefaultContainerService
,I/ActivityManager( 2403): Killing 5342:com.policydm/1000 (adj 15): empty #43
,D/dalvikvm( 2403): GC_EXPLICIT freed 982K, 13% free 24508K/28012K, paused 9ms+15ms, total 219ms
,D/dalvikvm( 5871): GC_EXPLICIT freed 874K, 28% free 10009K/13720K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 2829): GC_EXPLICIT freed 352K, 26% free 10307K/13760K, paused 4ms+7ms, total 46ms
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 350, Delta = -10
,D/dalvikvm( 5871): null clazz in OP_INSTANCE_OF, single-stepping
,D/dalvikvm( 5871): GC_EXPLICIT freed 872K, 28% free 10008K/13720K, paused 4ms+9ms, total 46ms
,D/dalvikvm( 2829): GC_EXPLICIT freed 354K, 26% free 10314K/13760K, paused 4ms+7ms, total 48ms
,D/dalvikvm( 5871): GC_EXPLICIT freed 871K, 28% free 10006K/13720K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 2829): GC_EXPLICIT freed 353K, 25% free 10324K/13760K, paused 4ms+7ms, total 47ms
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 300, prevStep = 4, currStep = 4
,D/dalvikvm( 5871): GC_CONCURRENT freed 1473K, 24% free 10491K/13720K, paused 1ms+10ms, total 41ms
,I/SettingSearch/SearchIntentReceiver( 2829): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2829): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 2829): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 2829): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2829): LOCALE_CHANGED call search setting db finish!!
,I/PowerManagerService( 2403): [PWL] Off : 15s ago
,V/AlarmManager( 2403): waitForAlarm result :4,
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/dalvikvm( 5077): GC_CONCURRENT freed 7127K, 34% free 16205K/24480K, paused 4ms+6ms, total 101ms,
,D/dalvikvm( 5077): WAIT_FOR_CONCURRENT_GC blocked 87ms,
,D/Finsky  ( 5077): [379] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5077): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.,
,D/BatteryService( 2403): level:100, scale:100, status:3, health:9, present:true, voltage: 4356, temperature: 299, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 2403): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
D/lights  ( 2403): led_pattern : 0 +
D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/LightsService( 2403): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/BatteryService( 2403): turn off LED
,D/lights  ( 2403): led_pattern : 0 -,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PowerManagerService( 2403): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2403): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2403): Waking up from sleep...
D/PowerManagerService( 2403): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2403): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2403): [s] WAKEFULNESS_AWAKE
D/PowerManagerService( 2403): [s] UserActivityState : 0 -> 1
,D/lights  ( 2403): button : 1 +
,D/lights  ( 2403): button : 1 -
D/PowerManagerService( 2403): [PWL] sb acquire: PowerManagerService.Display
D/UsbDeviceManager( 2403): handleMessage -> MSG_POWER_STATE = 0
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/DisplayPowerController( 2403): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2403): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
I/DisplayPowerController( 2403): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2403): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2403): [DAB] no lux value from sensor manager
D/PowerUI ( 2578): Overvoltage/Undervoltage (recovered) so turn on the screen.
,I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/Sensors ( 2403): LightSensor setDelay = 200000000
D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
D/Sensors ( 2403): Light sensor flush: not enabled 0
D/DisplayPowerController( 2403): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 2403): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/PowerManagerService( 2403): [api] [s] wakeUp (uid: 10019 pid: 2578) eventTime = 106230
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/Sensors ( 2403): LightSensor enable = 1
D/Sensors ( 2403): LightSensor enableSensor = 1
,D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 1
,I/Sensors ( 2403): HAL: batch Dry Run is complete
,D/PowerManagerService( 2403): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 6ms
,I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 65558
V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,I/Sensors ( 2403): HAL:resetDataRates mEnabled=4
I/libsuspend( 2403): !@[s] autosuspend_autosleep_disable
,D/PowerManagerService( 2403): unblankAllDisplays() is called.
D/HeadsetStateMachine( 3356): Disconnected process message: 10
I/libsuspend( 2403): !@[s] autosuspend_autosleep_disable done
,D/SurfaceFlinger( 1920): Screen acquired, type=0 flinger=0x40c36550
D/PowerManagerService( 2403): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
,D/RampAnimator( 2403): Light Animator Finished currentValue=8
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
D/SensorManager( 2403): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/SensorService( 2403): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2403): AutoRotationSensor::activate (ident=0x898f81f0, enabled=1)
D/SensorService( 2403): AutoRotationSensor::AR_init
,I/Sensors ( 2403): HAL: batch Dry Run is complete
,D/PowerManagerService( 2403): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 19ms
,I/Sensors ( 2403): HAL:resetDataRates mEnabled=4
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
,D/SensorManager( 2403): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,V/KeyguardServiceDelegate( 2403): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@42f85548)
,D/KeyguardViewMediator( 2578): onScreenTurnedOn, seq = 3
,D/KeyguardViewMediator( 2578): notifyScreenOnLocked,
D/KeyguardViewMediator( 2578): handleNotifyScreenOn
D/KeyguardViewManager( 2578): onScreenTurnedOn()
I/KeyguardEffectViewMain( 2578): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 2578): KeyguardEffectViewParticleSpace : screenTurnedOn
,D/VisualEffectParticleEffect( 2578): screenOnAnimationStart
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
V/KeyguardViewManager( 2578): send wm null token: host was null
,V/KeyguardServiceDelegate( 2403): **** SHOWN CALLED ****
,D/InputDispatcher( 2403): setInputDispatchMode: enabled=1, frozen=0
,I/SurfaceFlinger( 1920): id=16 Removed FlectronBea (8/8)
I/WindowManager( 2403): No lock screen! windowToken=null
D/PowerManagerNotifier( 2403): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,D/PowerManagerService( 2403): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2403): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2403): !@ElectronBeam exit
I/SELinux ( 6150): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6150):  
I/SurfaceFlinger( 1920): id=16 Removed FlectronBea (-2/8)
D/lights  ( 2403): lcd : 8 +
D/lights  ( 2403): lcd : 8 -
,D/LockPatternUtils( 2578): isPcwEnable = 10
,D/NotificationService( 2403): cancelNotificationLocked
D/NotificationService( 2403):  hasClearableItems
D/NotificationService( 2403):  has clearable items no 
D/NotificationService( 2403): cancelNotificationLocked: cancel alarm
D/UsbDeviceManager( 2403): sending intent : ACTION_USB_CABLE_STATE : connected = false
D/STATUSBAR-StatusBarManagerService( 2403): sendNotification(3) - 5
,D/NotificationService( 2403): cancelNotificationLocked: cancel alarm
D/DisplayPowerController( 2403): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2403): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/BatteryMeterView( 2578): onDraw batteryColor : -1
,I/SELinux ( 6150): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6150):  
I/SELinux ( 6150):  
,I/SELinux ( 6150): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6150): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6150): >>>>> Normal User
,E/dalvikvm( 6150): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 6150): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6150): in addTimaSignatureService
D/SensorService( 2403): AutoRotationSensor::process: Acc  eventTimestamp = 106333939219, previousAccTimestamp = 86068237125, difference = 20265702094 
,D/SensorService( 2403): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/TimaKeyStoreProvider( 6150): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6150): Added TimaKesytore provider
,D/DisplayPowerController( 2403): [api] [DAB] onSensorChanged : 1st lux : 0.0
,D/DisplayPowerController( 2403): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,D/SensorService( 2403): AutoRotationSensor::process: Acc  eventTimestamp = 106400601886, previousAccTimestamp = 86068237125, difference = 20332364761 
D/SensorService( 2403):  [AR] 0.2 -0.0 9.9
,D/SensorService( 2403): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/SurfaceControl( 2403): Excessive delay in unblankDisplay() while turning screen on: 241ms
,D/MISC PowerHAL( 2403): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2403): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 243ms
,D/LightsService( 2403): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2403) 
,D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/UsbDeviceManager( 2403): received ACTION_POWER_DISCONNECTED = -1
D/LightsService( 2403): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 340, Delta = -10
,D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/input/input1/enabled: 1
D/MISC PowerHAL( 2403): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/input/input0/enabled: 1
,D/LockPatternUtils( 2578): isPcwEnable = 10
,D/SamsungIME( 2974): showDlgMsgBox : false true true
,I/FPMS_FingerprintManagerService( 2598): onReceive: android.intent.action.USER_PRESENT
D/LightsService( 2403): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2403) 
D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2403): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
V/AlarmManager( 2403): waitForAlarm result :8
D/PalmMotionService( 2403): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2403): SURFACE_PALM_SWIPE: 1
,I/NfcService( 2755): applyRouting return - 2 
E/MotionRecognitionService( 2403):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/SSRMv2:TSP:AirViewOnOff( 2403): SettingsAirViewInfo:: 000000000
E/NfcService( 2755): callback == null
,D/Launcher( 2774): onRestart, Launcher: 1110052064
D/Launcher( 2774): onStart, Launcher: 1110052064
,D/Launcher.HomeView( 2774): onStart
,D/Launcher( 2774): onResume, Launcher: 1110052064
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/StatusBarManagerService( 2403): semi p:2774,o:f
,D/Launcher.HomeView( 2774): onResume
D/StatusBarManagerService( 2403): tr p:2774,o:f
D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2403): semi p:2774,o:f
,D/MenuAppsGridFragment( 2774): onResume
,I/WifiTrafficPoller( 2403): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2403): ACTION_SCREEN_ON
D/LightsService( 2403): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2403) 
,D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2403): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=on)
,I/SecExternalDisplayIntents_Java( 2403): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController( 2403): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2403): Bridge Server is not available
D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2403): Excessive delay in MISC setInteractive(true) while turning screen on: 159ms
D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
D/PowerManagerService( 2403): Excessive delay in nativeSetInteractive(true): 160ms
,D/PowerManagerService( 2403): SecHardwareInterface.setBatteryADC : true
D/PersonaManagerService( 2403): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 2403): MSG_ACTION_SCREEN_ON called
,I/NfcService( 2755): NFC: Screen On & Cover Open
,I/NfcService( 2755): applyRouting return - 2 
,E/NfcService( 2755): callback == null
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2578): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,D/dalvikvm( 6150): GC_CONCURRENT freed 2994K, 31% free 9565K/13712K, paused 11ms+4ms, total 52ms
,D/dalvikvm( 6150): WAIT_FOR_CONCURRENT_GC blocked 39ms
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 340, Delta = 0
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(8)
,D/dalvikvm( 2403): GC_EXPLICIT freed 1190K, 13% free 24502K/28012K, paused 8ms+17ms, total 208ms
,D/QuickConnect[1.1][2] ( 4643): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
,V/QuickConnect[1.1][2] ( 4643): BleHelper.shouldScanBleBg - 
,D/QuickConnect[1.1][2] ( 4643): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4227a5b0
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4227a5b0
V/QuickConnect[1.1][2] ( 4643): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4227a5b0
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4227a5b0
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4227a5b0
D/QuickConnect[1.1][2] ( 4643): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 4643): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 4643): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 4643): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,I/SELinux ( 6166): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6166):  
I/ActivityManager( 2403): Killing 5382:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43
,D/PowerManagerService( 2403): [PWL] sb release: PowerManagerService.Broadcasts
,I/SELinux ( 6166): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6166):  
I/SELinux ( 6166):  
,I/SELinux ( 6166): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6166): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6166): >>>>> Normal User
,E/dalvikvm( 6166): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
,E/SELinux ( 6166): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6166): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6166): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6166): Added TimaKesytore provider
,D/dalvikvm( 6166): GC_CONCURRENT freed 3014K, 31% free 9553K/13716K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 6166): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(3)
,I/KIES_RECEIVE( 6166): [APK BnR] Receive KIES_USB_DISCONNECT
W/ContextImpl( 6166): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
,E/TranscodeReceiver( 5875): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,D/videowall-Global( 5875): core_num = 4
,D/dalvikvm( 5875): No JNI_OnLoad found in /system/lib/libsavsff.so 0x422c7380, skipping init
,W/linker  ( 5875): libvwengine.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/videowall-Global( 5875): density : 2.0 width : 720 height : 1280 Raw width : 720 Raw height : 1280
,D/videowall-Global( 5875): dsp : 720, swkey : false, Cores : 4, Clock : 0
,I/SELinux ( 6178): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6178):  
,I/SELinux ( 6178): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6178):  
I/SELinux ( 6178):  
,I/SELinux ( 6178): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6178): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 6178): >>>>> Normal User
,E/dalvikvm( 6178): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 6178): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 6178): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6178): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6178): Added TimaKesytore provider
,D/dalvikvm( 6178): GC_CONCURRENT freed 3001K, 31% free 9571K/13720K, paused 3ms+2ms, total 22ms
,D/dalvikvm( 6178): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/SELinux ( 6194): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6194):  
,I/ActivityManager( 2403): Killing 5437:com.google.android.apps.magazines/u0a115 (adj 15): empty #43
,D/dalvikvm( 1921): GC_EXPLICIT freed 44K, 12% free 9501K/10696K, paused 4ms+5ms, total 49ms
D/SSRMv2:TSP:AirViewOnOff( 2403): SettingsAirViewInfo:: 000000000
,I/SELinux ( 6194): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6194):  
I/SELinux ( 6194):  
,I/SELinux ( 6194): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6194): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6194): >>>>> Normal User
,E/dalvikvm( 6194): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
,E/SELinux ( 6194): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9501K/10696K, paused 3ms+4ms, total 34ms
,D/TimaKeyStoreProvider( 6194): in addTimaSignatureService
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
D/TimaKeyStoreProvider( 6194): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6194): Added TimaKesytore provider
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9501K/10696K, paused 2ms+4ms, total 33ms
,D/dalvikvm( 6194): GC_CONCURRENT freed 3006K, 31% free 9566K/13720K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 6194): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/lights  ( 2403): button : 0 +
,D/lights  ( 2403): button : 0 -
,I/iu.Environment( 5489): update battery state; isPlugged? false*
,I/iu.SyncManager( 5489): SYNC; picasa accounts
,I/ActivityManager( 2403): Killing 5441:com.samsung.android.magazine.service/u0a110 (adj 15): empty #43
,I/iu.Environment( 3288): update battery state; isPlugged? false*
D/PicasaUploader( 6194):    wifiOnlyPhoto changed to true
D/PicasaUploader( 6194):    wifiOnlyVideo changed to true
,D/PicasaUploader( 6194):    syncOnBattery changed to true
,D/PicasaUploaderSync( 6194): sync account database
,I/iu.UploadsManager( 5489): num queued entries: 0
I/GCoreUlr( 2733): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,I/iu.UploadsManager( 5489): num updated entries: 0
,I/iu.UploadsManager( 3288): num queued entries: 0
,I/iu.UploadsManager( 3288): num updated entries: 0
,I/iu.SyncManager( 5489): NEXT; no task
I/iu.SyncManager( 3288): NEXT; no task
,I/GCoreUlr( 2733): DispatchingService.onCreate()
,D/PicasaUploaderSync( 6194): accounts in DB=1
D/PicasaUploaderSyncManager( 6194): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PicasaUploaderSyncManager( 6194): background data: true
,D/PicasaUploaderSyncManager( 6194): battery info: false
,D/LockPatternUtils( 2578): isPcwEnable = 10
,I/GCoreUlr( 2733): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/Headlines( 5425): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5425): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5425): Breath 43797 latestRequest time : 1455067533419 current time : 1455067577216
,D/Mms/UIEventReceiver( 5238): ui event
,I/GCoreUlr( 2733): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
E/Watchdog( 2403): !@Sync 3
,I/GCoreUlr( 2733): Unbound from all location providers
,I/GCoreUlr( 2733): Place inference reporting - stopped
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4846): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4846): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
I/GCoreUlr( 2733): DispatchingService.onDestroy()
,I/GCoreUlr( 2733): Stopping handler for UlrDispSvcFast
,D/comsamsunglog( 4846): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4846): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 4846): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4846): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
I/GCoreUlr( 2733): Unbound from all location providers
,I/GCoreUlr( 2733): Place inference reporting - stopped
,D/daemonapp( 4846): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1455077520000
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1455067577354
,D/daemonapp( 4846): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/dalvikvm( 4846): GC_CONCURRENT freed 2697K, 28% free 9905K/13756K, paused 6ms+4ms, total 48ms
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 4846): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,D/SensorService( 2403):   0.1 -0.0 9.9
,I/Icing   ( 3288): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music
,I/Icing   ( 3288): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2403): level:100, scale:100, status:2, health:2, present:true, voltage: 4342, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/PowerManagerService( 2403): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/PowerUI ( 2578): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2403): [api] [s] wakeUp (uid: 10019 pid: 2578) eventTime = 116179
,D/PowerUI ( 2578): playSound : 1
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,V/Vibrator( 2578): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,V/Vibrator( 2578): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
D/UsbDeviceManager( 2403): handleMessage -> MSG_POWER_STATE = 1
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
I/EntropyMixer( 2403): Writing entropy...
V/VibratorService( 2403): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2403): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2403): JNI vibratorOff()
D/VibratorService( 2403): JNI vibratorOn() : 100
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
D/PowerUI ( 2578): RINGER_MODE_VIBRATE
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
D/UsbDeviceManager( 2403): sending intent : ACTION_USB_CABLE_STATE : connected = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
E/TranscodeReceiver( 5875): onReceive : android.intent.action.ACTION_POWER_CONNECTED
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,D/BatteryMeterView( 2578): onDraw batteryColor : -1
,D/TranscodeService( 5875): onCreate()
,I/SELinux ( 6216): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6216):  
,D/dalvikvm( 5875): No JNI_OnLoad found in /system/lib/libsavsvc.so 0x422c7380, skipping init
,D/dalvikvm( 5875): No JNI_OnLoad found in /system/lib/libsavscmn.so 0x422c7380, skipping init
,D/dalvikvm( 5875): No JNI_OnLoad found in /system/lib/libsthmb.so 0x422c7380, skipping init
,D/TranscodeService( 5875): power? : true / screen off : false
,D/TranscodeService( 5875): releaseTranscodeThread.
D/VibratorService( 2403): JNI vibratorOff()
,I/SELinux ( 6216): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6216):  
I/SELinux ( 6216):  
,I/SELinux ( 6216): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6216): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6216): >>>>> Normal User
,E/dalvikvm( 6216): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 6216): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6216): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6216): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6216): Added TimaKesytore provider
,D/dalvikvm( 6216): GC_CONCURRENT freed 2997K, 31% free 9572K/13720K, paused 5ms+2ms, total 30ms
,D/dalvikvm( 6216): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/sCloudBackupApp( 6216): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 6216): Other Intent
,D/PicasaUploaderSyncManager( 6194): battery info: true
,I/iu.Environment( 5489): update battery state; isPlugged? true*
,I/iu.UploadsManager( 5489): num queued entries: 0
,I/iu.UploadsManager( 5489): num updated entries: 0
,I/iu.SyncManager( 5489): NEXT; no task
,I/iu.FingerprintManager( 5489): Start processing all media
,I/iu.FingerprintManager( 5489): Start processing media store URI: content://media/external/images/media
,I/iu.Environment( 3288): update battery state; isPlugged? true*
,I/iu.FingerprintManager( 5489): Start processing media store URI: content://media/external/video/media
,I/iu.UploadsManager( 3288): num queued entries: 0
,I/iu.UploadsManager( 3288): num updated entries: 0
,E/NetworkScheduler.SchedulerReceiver( 2846): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 2846): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/iu.SyncManager( 3288): NEXT; no task
,I/GCoreUlr( 2733): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/iu.FingerprintManager( 3288): Start processing all media
,I/GCoreUlr( 2733): DispatchingService.onCreate()
,I/iu.FingerprintManager( 3288): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5489): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 5489): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 5489): Finished generating fingerprints; 0.068 seconds
,I/iu.FingerprintManager( 5489):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/iu.FingerprintManager( 3288): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 3288): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3288): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3288): Finished generating fingerprints; 0.071 seconds
,I/iu.FingerprintManager( 3288):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2733): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 340, Delta = 0
,I/GCoreUlr( 2733): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2733): Unbound from all location providers
,I/GCoreUlr( 2733): Place inference reporting - stopped
,I/GCoreUlr( 2733): DispatchingService.onDestroy()
,I/GCoreUlr( 2733): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2733): Unbound from all location providers
,I/GCoreUlr( 2733): Place inference reporting - stopped
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/FactoryTest( 5152): Not factory mode
,D/FactoryTest( 5152): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 5152): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5152): still no open session command from host, so toast
W/ContextImpl( 5152): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5152): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy( 2403): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2403): mDVFSHelper.acquire()
I/SurfaceFlinger( 1920): id=17 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1920): id=18 createSurf (16x16),-1 flag=20004, EimLayer
,D/Launcher.HomeView( 2774): onPause
D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
,E/MTPRx   ( 5152): started activity for popup
,D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2403): tr p:2774,o:f
,E/SettingsReceiverActivity( 5152): PREF_DONT_ASK_AGAIN : true
D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
,D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2403): tr p:2774,o:f
D/StatusBarManagerService( 2403): semi p:2774,o:f
,I/SQLiteSecureOpenHelper( 3552): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3552): getDatabaseLocked(b,b,pwd)...
,W/InputMethodManagerService( 2403): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@43025230 attribute=android.view.inputmethod.EditorInfo@4321cc18, token = android.os.BinderProxy@422d6e48
,D/SettingsReceiverActivity( 5152): dev.kiessupport is : TRUE
,D/Launcher( 2774): onResume, Launcher: 1110052064
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2403): semi p:2774,o:f
,D/Launcher.HomeView( 2774): onResume
,D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/MenuAppsGridFragment( 2774): onResume
D/StatusBarManagerService( 2403): tr p:2774,o:f
D/StatusBarManagerService( 2403): semi p:2774,o:f
,D/Mms/UIEventReceiver( 5238): ui event
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(12)
,I/SurfaceFlinger( 1920): id=18 Removed EimLayer (5/9)
I/SurfaceFlinger( 1920): id=18 Removed EimLayer (-2/9)
,I/SurfaceFlinger( 1920): id=17 Removed EimLayer (4/8)
,I/SurfaceFlinger( 1920): id=17 Removed EimLayer (-2/8)
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(6)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2403):   0.2 -0.1 9.9
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2403): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@8
,D/SensorService( 2403):   0.2 -0.0 9.9
,I/ActivityManager( 2403): Waited long enough for: ServiceRecord{432b1438 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2403):   0.2 -0.0 9.8
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
,D/PowerManagerService( 2403): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2578
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService( 2403): sendNotification(1) - 5
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/NotificationService( 2403): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/RCPManagerService( 2403): NotificationReceiver onReceive()
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/RCPManagerService( 2403):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
D/RCPManagerService( 2403): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298403
D/RCPManagerService( 2403): getPolicy: policy value returned = false
,D/RCPManagerService( 2403): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2403): app label == com.android.systemui
D/RCPManagerService( 2403): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298403
,D/UserManagerService( 2403): User -1does not exists!!
D/RCPManagerService( 2403): getPolicy: policy value returned = true
D/RCPManagerService( 2403): Calling User is -1
,D/RCPManagerService( 2403): userid of SBN ==-1
E/PersonaManagerService( 2403): returning null in  getPersonasForUser
,D/ProgressBar( 2578): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2578): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422bb6e8
,D/BatteryMeterView( 2578): onDraw batteryColor : -1
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(55)
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = -10
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
D/SensorService( 2403):   0.2 -0.1 9.9
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(59)
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 300, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,I/ActivityManager( 2403): Waited long enough for: ServiceRecord{43278820 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(55)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5425): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5425): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5425): Breath 73404 latestRequest time : 1455067533419 current time : 1455067606823
,I/VacuumService( 2733): Vacuum at: now=1455067607023 tag=VacuumService
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 3288): GC_CONCURRENT freed 1899K, 21% free 12092K/15144K, paused 5ms+5ms, total 67ms
,E/Watchdog( 2403): !@Sync 4
,D/dalvikvm( 2733): GC_CONCURRENT freed 1820K, 21% free 11590K/14628K, paused 13ms+10ms, total 82ms
,I/PhenotypeConfigurator( 2733): Scheduling Phenotype for one-off execution 12105 seconds from now (1455067607551)
,D/GetConfigurationSnapshotOperation( 2733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2733): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2733): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2733): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2733): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 2403): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 2733): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 2733): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2733): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 2733): Thread-113(HTTPLog):isShipBuild true
,I/System.out( 2733): Thread-113(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/LocationManagerService( 2403): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 2733): GC_CONCURRENT freed 1355K, 18% free 12194K/14768K, paused 4ms+11ms, total 50ms
,D/LocationManagerService( 2403): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2403): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/PowerManagerService( 2403): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2403): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2403): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/RampAnimator( 2403): Light Animator Finished currentValue=2
D/lights  ( 2403): lcd : 2 +
,D/lights  ( 2403): lcd : 2 -
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 301, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2403):   0.2 -0.1 9.9
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2403): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2403): [PWL] On : 106222 (39954 ms ago)
I/PowerManagerService( 2403): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService( 2403): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2578, ws=null) (elapsedTime=19928)
,D/PowerManagerService( 2403): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2578 (0x0)
,I/PowerManagerService( 2403): Nap time...
D/PowerManagerService( 2403): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2403): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2403): Going to sleep due to screen timeout...
,D/PowerManagerService( 2403): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2403): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,D/Sensors ( 2403): LightSensor enable = 0
,D/Sensors ( 2403): LightSensor enableSensor = 0
D/DisplayPowerController( 2403): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,D/SensorManager( 2403): unregisterListener ::   
,I/SurfaceFlinger( 1920): id=19 createSurf (720x1280),-1 flag=20004, FlectronBea
I/DisplayPowerController( 2403): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
I/DisplayPowerController( 2403): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,I/Sensors ( 2403): HAL:resetDataRates mEnabled=4
D/DisplayPowerController( 2403): !@ElectronBeam entry
,D/SensorManager( 2403): unregisterListener ::   
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3356): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2403): lcd : 0 +
,D/lights  ( 2403): lcd : 0 -
D/MISC PowerHAL( 2403): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/input/input1/enabled: 0
D/PowerManagerService( 2403): blankAllDisplays() is called.
D/PowerManagerService( 2403): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2403): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/input/input0/enabled: 0
,V/WindowOrientationListener( 2403): WindowOrientationListener disabled
D/SensorService( 2403): AutoRotationSensor::activate (ident=0x898f81f0, enabled=0)
,I/Sensors ( 2403): HAL: batch Dry Run is complete
D/PowerManagerService( 2403): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2403): [PWL] sb release: PowerManagerService.Display
D/KeyguardViewMediator( 2578): onScreenTurnedOff(3)
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
,D/PowerManagerService( 2403): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SensorManager( 2403): unregisterListener ::   
D/InputDispatcher( 2403): setInputDispatchMode: enabled=0, frozen=0
D/SurfaceFlinger( 1920): Screen released, type=0 flinger=0x40c36550
,D/LockPatternUtils( 2578): isPcwEnable = 10
,D/Launcher.HomeView( 2774): onPause
,D/LockPatternUtils( 2578): isPcwEnable = 10
,D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2403): tr p:2774,o:f
,D/KeyguardViewMediator( 2578): setting alarm to turn off keyguard, seq = 3
,D/LightsService( 2403): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2403) ,
,I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
D/Sensors ( 2403): LightSensor setDelay = 200000000
D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
D/Sensors ( 2403): Light sensor flush: not enabled 0
,D/Sensors ( 2403): LightSensor enable = 1
D/Sensors ( 2403): LightSensor enableSensor = 1
,D/Launcher.HomeView( 2774): onStop
D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2403): turn on LED for fully charged
D/VibratorService( 2403): JNI vibratorOff()
,I/WifiTrafficPoller( 2403): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2403): ACTION_SCREEN_OFF
,D/LightsService( 2403): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2403) 
,D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2403): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2403): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2403): Bridge Server is not available
,D/PersonaManagerService( 2403): ACTION_SCREEN_OFF onReceive
D/STATUSBAR-PhoneStatusBar( 2578):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2578): makeExpandedInvisible
,D/PersonaManagerServiceHandler( 2403): MSG_ACTION_SCREEN_OFF called
D/PhoneStatusBarView( 2578): marqueeStatusBar:123, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2578):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2755): applyRouting return - 2 
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SurfaceControl( 2403): Excessive delay in blankDisplay() while turning screen off: 230ms
I/libsuspend( 2403): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2403): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2403): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 233ms
D/PowerManagerService( 2403): SecHardwareInterface.setBatteryADC : false
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(29)
,D/Sensors ( 2403): LightSensor enable = 0
,D/Sensors ( 2403): LightSensor enableSensor = 0
,D/LightsService( 2403): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager( 2403): unregisterListener ::   
D/lights  ( 2403): led_pattern : 5 +
,D/lights  ( 2403): led_pattern : 5 -
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0
,D/dalvikvm( 2403): GC_EXPLICIT freed 2383K, 13% free 24630K/28280K, paused 11ms+22ms, total 246ms
,E/NfcService( 2755): callback == null
I/PowerManagerService( 2403): [PWL] Off : 0s ago
I/PowerManagerService( 2403): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2403): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2403): [PWL]       PARTIAL_WAKE_LOCK              'RILJ1' (uid=1001, pid=2751, ws=null) (elapsedTime=250)
I/PowerManagerService( 2403): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/LockPatternUtils( 2578): isPcwEnable = 10
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0
,D/QuickConnect[1.1][2] ( 4643): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 4643): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4643): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4227a5b0
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4227a5b0
D/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - shouldScanBleBg = false
,I/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4643): stopLeScan()
,D/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 5875): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 5875): power? : true / screen off : true
,D/PowerManagerService( 2403): [PWL] sb release: PowerManagerService.Broadcasts
D/TranscodeService( 5875): Music is = false
D/TranscodeService( 5875): runvideoplayer is false
,D/TranscodeService( 5875): Thread start
,D/TranscodeService( 5875): WakeLock.acquire()
,D/videowall-FileMgr( 5875): thumbnailDBSync -1
,D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onInitialize : 273
,D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onSetOnInfoListener : add 273
I/PrGenericPlugin( 1923): [A] ENTER onInitialize : 0x111
,I/PrGenericPlugin( 1923): [A] LEAVE onInitialize : 0x111
,D/TranscodeService( 5875): Thread end
,D/TranscodeService( 5875): WakeLock.release()
D/TranscodeService( 5875): onDestroy()
,D/TranscodeService( 5875): releaseTranscodeThread.
,V/ApplicationPolicy( 2403): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,I/ActivityManager( 2403): Killing 4732:com.android.email/u0a157 (adj 15): empty #43
,D/AmoledAdjustTimer( 2403): prevTemp = 301, currTemp = 302, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,V/AlarmManager( 2403): waitForAlarm result :4,
,D/KeyguardViewMediator( 2578): received DELAYED_KEYGUARD_ACTION with seq = 3, mDelayedShowingSequence = 3,
V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/LockPatternUtils( 2578): isPcwEnable = 10,
,D/KeyguardViewMediator( 2578): in doKeyguardLocked mIsRollUp false null
,D/PersonaManager( 2578): isKioskContainerExistOnDevice,
,D/LockPatternUtils( 2578): isPcwEnable = 10,
D/LockPatternUtils( 2578): isPcwEnable = 10
,D/KeyguardViewMediator( 2578): doKeyguard: not showing because lockscreen is off,
,I/PowerManagerService( 2403): [PWL] Off : 5s ago,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2403): waitForAlarm result :8,
,D/Headlines( 5425): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5425): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5425): Breath 90026 latestRequest time : 1455067533419 current time : 1455067623445,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3356): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 15s ago,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate,
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0,
,E/Watchdog( 2403): !@Sync 5,
,D/AmoledAdjustTimer( 2403): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2403): [PWL] Off : 30s ago,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0,
,V/AlarmManager( 2403): waitForAlarm result :4,
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/AmoledAdjustTimer( 2403): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,D/Headlines( 5425): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5425): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5425): Breath 120025 latestRequest time : 1455067533419 current time : 1455067653444
,D/Headlines( 5425): stop ,
,D/Headlines( 5425): Breath.onDestroy : ,
I/ActivityManager( 2403): Killing 4834:com.samsung.android.service.travel/u0a170 (adj 15): empty #43
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2403): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2403): [PWL] Off : 50s ago,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2403): !@Sync 6,
,D/AmoledAdjustTimer( 2403): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,I/ClearcutLoggerApiImpl( 2846): disconnect managed GoogleApiClient,
,D/AmoledAdjustTimer( 2403): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate,
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3356): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 75s ago,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate,
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2403): !@Sync 7,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3356): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 105s ago,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2403): !@Sync 8,
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2403): stay LED for fully charged,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3356): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2403): !@Sync 9,
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2403): initializing...,
I/TLC_TIMA_PKM_initialize( 2403): root = 0, root_strlen = 1,
I/TLC_TIMA_PKM_initialize( 2403): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2403): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2403): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 2403): root = 0, root_len = 1
,I/TZ: mc_tlc_communication( 2403): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2403): aligned max_sendmsg_size = 262208,
I/TZ: mc_tlc_communication( 2403): aligned max_recvmsg_size = 262208,
I/TZ: mc_tlc_communication( 2403): device_id = 0x0
,I/TZ: mc_tlc_communication( 2403): tlc_open() was called
,I/TZ: mc_tlc_communication( 2403): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2403): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2403): Opening the session
,I/TZ: mc_tlc_communication( 2403): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2403): Trustlet response is completed,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3356): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2403): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :4,
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 6852): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 6852):  
,I/SELinux ( 6852): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6852):  
I/SELinux ( 6852):  
,I/SELinux ( 6852): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 6852): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6852): >>>>> Normal User
,E/dalvikvm( 6852): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 6852): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 6852): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 6852): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 6852): Added TimaKesytore provider,
,D/dalvikvm( 6852): GC_CONCURRENT freed 2994K, 31% free 9574K/13720K, paused 4ms+2ms, total 26ms,
,D/dalvikvm( 6852): WAIT_FOR_CONCURRENT_GC blocked 17ms,
,I/ActivityManager( 2403): Killing 5301:com.sec.android.fotaclient/u0a11 (adj 15): empty #43,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2403): stay LED for fully charged,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3356): Disconnected process message: 10,
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 2578): GC_CONCURRENT freed 15681K, 34% free 33900K/50724K, paused 27ms+10ms, total 102ms,
,E/Watchdog( 2403): !@Sync 11,
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 6894,
W/ProcessCpuTracker( 2403): Skipping unknown process pid 6899
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 6904
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 6909
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 6912
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 6915,
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3356): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 225s ago,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2403): !@Sync 12
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5058): [b] __PingReply__
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/dalvikvm( 2403): GC_FOR_ALLOC freed 2729K, 18% free 24603K/29648K, paused 191ms, total 191ms
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 13
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 275s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2403): !@Sync 14
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2403): !@Sync 15
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2403): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2403): !@Sync 16
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2403): !@Sync 17
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2403): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2403): !@Sync 18
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 19
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 455s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2403): !@Sync 20
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 2403): GC_FOR_ALLOC freed 2468K, 18% free 24522K/29648K, paused 193ms, total 194ms
,E/Watchdog( 2403): !@Sync 21
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/GAV2    ( 5171): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5171): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 525s ago
,V/AlarmManager( 2403): waitForAlarm result :4
,E/Watchdog( 2403): !@Sync 22
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2403): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2403): <AppSync3 Whitelist>
,V/AlarmManager( 2403): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 23
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 24
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 3786): GC_CONCURRENT freed 2925K, 30% free 9724K/13796K, paused 13ms+3ms, total 55ms
,D/dalvikvm( 3786): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 25
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 26
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 680s ago
,E/Watchdog( 2403): !@Sync 27
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 28
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 29
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,I/PowerManagerService( 2403): [PWL] Off : 765s ago
I/PowerManagerService( 2403): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2403): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2403): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2403, ws=null) (elapsedTime=90)
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 8206
,E/Watchdog( 2403): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2403): GC_FOR_ALLOC freed 2616K, 18% free 24522K/29648K, paused 175ms, total 175ms
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 31
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :4
,D/LightsService( 2403): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
D/Sensors ( 2403): LightSensor setDelay = 200000000
D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
D/Sensors ( 2403): Light sensor flush: not enabled 0
D/Sensors ( 2403): LightSensor enable = 1
D/Sensors ( 2403): LightSensor enableSensor = 1
D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/DBG_DM  ( 4231): [3.19.140541][Line:666][onReceive] FotaPostpone callback received
,I/DBG_DM  ( 4231): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 3
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
,D/NotificationService( 2403): cancelNotificationLocked
D/NotificationService( 2403):  hasClearableItems
D/NotificationService( 2403):  has clearable items no 
D/NotificationService( 2403): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2403): cancelNotificationLocked: cancel alarm
D/STATUSBAR-StatusBarManagerService( 2403): sendNotification(3) - 3
D/LightsService( 2403): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2403) 
D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,I/DBG_DM  ( 4231): [3.19.140541][Line:5174][xdbSetDownloadPostponeStatus] Set Download Postpone status : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4231): [3.19.140541][Line:369][handleMessage] event ->214
,I/DBG_DM  ( 4231): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.android.launcher2.Launcher
,I/DBG_DM  ( 4231): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,I/DBG_DM  ( 4231): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
W/ContextImpl( 4231): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
,I/DBG_DM  ( 4231): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,E/DBG_DM  ( 4231): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
,I/DBG_DM  ( 4231): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : true
,E/DBG_DM  ( 4231): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@4237a8a0
,I/DBG_DM  ( 4231): [3.19.140541][Line:2047][xdmCallUiDialogActivity] UI_id:219
,W/ContextImpl( 4231): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 com.wssyncmldm.XDMService.xdmCallUiDialogActivity:2053 com.wssyncmldm.XDMService.access$300:81 com.wssyncmldm.XDMService$1.handleMessage:349 
,W/ContextImpl( 4231): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 com.wssyncmldm.XDMService.xdmCallUiDialogActivity:2053 com.wssyncmldm.XDMService.access$300:81 
V/ApplicationPolicy( 2403): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2403): mDVFSHelper.acquire()
I/SurfaceFlinger( 1920): id=20 createSurf (16x16),-1 flag=20004, EimLayer
,I/SurfaceFlinger( 1920): id=21 createSurf (16x16),-1 flag=20004, EimLayer
D/Sensors ( 2403): LightSensor enable = 0
,D/Sensors ( 2403): LightSensor enableSensor = 0
,D/SensorManager( 2403): unregisterListener ::   
D/LightsService( 2403): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
,I/SQLiteSecureOpenHelper( 3552): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3552): getDatabaseLocked(b,b,pwd)...
,I/DBG_DM  ( 4231): [3.19.140541][Line:2096][onResume] 
,I/DBG_DM  ( 4231): [3.19.140541][Line:2137][xuiDlgShow] id 219
,I/DBG_DM  ( 4231): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 52
,I/DBG_DM  ( 4231): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@4
D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2403): mDVFSHelper.acquire()
,I/DBG_DM  ( 4231): [3.19.140541][Line:250][xuiDownloadProgressInit] 
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/DBG_DM  ( 4231): [3.19.140541][Line:2088][onPause] 
D/StatusBarManagerService( 2403): semi p:4231,o:f
,V/WindowManager( 2403): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,I/DBG_DM  ( 4231): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 52
,I/DBG_DM  ( 4231): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/SurfaceFlinger( 1920): id=9 Removed Mauncher (8/10)
,I/SurfaceFlinger( 1920): id=9 Removed Mauncher (-2/10)
,D/Launcher( 2774): onTrimMemory. Level: 20
,I/dalvikvm( 4231): Total arena pages for JIT: 18
,I/DBG_DM  ( 4231): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:76][onCreate] Postpone Count : 52
,E/MoreInfoHPW_ViewGroup( 4231): Parent view is not a TextView
,D/checkbox( 4231): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
,D/checkbox( 4231): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4231): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4231): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,I/DBG_DM  ( 4231): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4231): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2403): sendNotification(1) - 4
,I/DBG_DM  ( 4231): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 52
,D/ProgressBar( 2578): setProgressDrawable drawableHeight = 12
,I/DBG_DM  ( 4231): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,D/ProgressBar( 2578): setProgressDrawable drawableHeight = 12
,I/DBG_DM  ( 4231): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/PhoneStatusBar( 2578): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422bb6e8
,I/DBG_DM  ( 4231): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 52
,I/DBG_DM  ( 4231): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,I/DBG_DM  ( 4231): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 52
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/DBG_DM  ( 4231): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,I/DBG_DM  ( 4231): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4231): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 52
,I/DBG_DM  ( 4231): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
D/ConnectivityService( 2403): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
,I/DBG_DM  ( 4231): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:418][onResume] Postpone Count : 52
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4231): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2403): sendNotification(2) - 4
,I/DBG_DM  ( 4231): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 52
,I/DBG_DM  ( 4231): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4231): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,I/DBG_DM  ( 4231): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4231): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/Activity( 4231): setTransGradationMode to true
,D/PhoneStatusBar( 2578): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2403): semi p:4231,o:t
,I/DBG_DM  ( 4231): [3.19.140541][Line:400][onPause] 
,I/DBG_DM  ( 4231): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4231): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 52
,I/DBG_DM  ( 4231): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:418][onResume] Postpone Count : 52
,I/DBG_DM  ( 4231): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4231): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2403): sendNotification(2) - 4
I/DBG_DM  ( 4231): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 52
,I/DBG_DM  ( 4231): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4231): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4231): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,I/DBG_DM  ( 4231): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4231): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4231): setTransGradationMode to true
D/PhoneStatusBar( 2578): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4231): [3.19.140541][Line:400][onPause] 
,D/StatusBarManagerService( 2403): semi p:4231,o:t
,D/checkbox( 4231): TwCheckBox.onAttachedToWindow()
,D/PhoneStatusBar( 2578): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2403): semi p:4231,o:t
,I/SurfaceFlinger( 1920): id=22 createSurf (1x1),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2403): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2403): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/IInputConnectionWrapper( 4231): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@8
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 32
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3356): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,E/SPPClientService( 5058): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3356): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 855s ago
,E/Watchdog( 2403): !@Sync 33
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 34
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
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
,I/PowerManagerService( 2403): [PWL] Off : 950s ago
,E/Watchdog( 2403): !@Sync 36
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3356): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3356): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 37
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 38
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 39
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2403): GC_FOR_ALLOC freed 2718K, 18% free 24603K/29648K, paused 198ms, total 198ms
D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 41
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 42
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5058): [b] __PingReply__
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2403): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2403): <AppSync3 Whitelist>
,V/AlarmManager( 2403): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,TIME-OUT KILL (timeout was 1200000ms),I/PowerManagerService( 2403): [PWL] Off : 1155s ago
D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
D/AndroidRuntime( 9137): 
D/AndroidRuntime( 9137): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 9137): CheckJNI is OFF
D/AndroidRuntime( 9137): setted country_code = Poland
D/AndroidRuntime( 9137): setted countryiso_code = PL
D/AndroidRuntime( 9137): setted sales_code = PLS
D/AndroidRuntime( 9137): readGMSProperty: start
D/AndroidRuntime( 9137): readGMSProperty: already setted!!
D/AndroidRuntime( 9137): readGMSProperty: end
D/AndroidRuntime( 9137): addProductProperty: start
D/dalvikvm( 9137): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 9137): Added shared lib libjavacore.so 0x0
D/dalvikvm( 9137): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 9137): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 9137): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 9137): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 9137): failed to load memtrack module: -2
D/dalvikvm( 9137): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 9137): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2403): START PACKAGE DELETE: observer{1123372008}
D/PackageManager( 2403): pkg{<packageName>}
D/PackageManager( 2403): user{0}
D/PackageManager( 2403): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2403): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2403): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2403): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2403): [MSG] DELETE_PACKAGE_AS_USER
D/dalvikvm( 2403): GC_EXPLICIT freed 1087K, 18% free 24570K/29648K, paused 8ms+15ms, total 208ms
D/PackageManager( 2403): return delete result to caller: 1123372008
D/AndroidRuntime( 9137): Shutting down VM
D/PackageManager( 2403): returnCode: -1
D/dalvikvm( 9137): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 5ms
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "sms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
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

```
