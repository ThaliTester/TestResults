#### Test 58135655812b57f_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
D/PowerManagerService( 2403): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2581 (0x0)
I/PowerManagerService( 2403): Nap time...
D/PowerManagerService( 2403): [s] WAKEFULNESS_NAPPING
--------- beginning of /dev/log/main
D/Sensors ( 2403): LightSensor enable = 0
D/Sensors ( 2403): LightSensor enableSensor = 0
I/PowerManagerService( 2403): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2403): Going to sleep due to screen timeout...
D/PowerManagerService( 2403): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2403): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2403): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/DisplayPowerController( 2403): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/DisplayPowerController( 2403): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
D/SensorManager( 2403): unregisterListener ::   
I/SurfaceFlinger( 1921): id=19 createSurf (720x1280),-1 flag=20004, FlectronBea
I/Sensors ( 2403): HAL:resetDataRates mEnabled=4
D/SensorManager( 2403): unregisterListener ::   
D/DisplayPowerController( 2403): !@ElectronBeam entry
D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3355): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/lights  ( 2403): lcd : 0 +
D/lights  ( 2403): lcd : 0 -
D/MISC PowerHAL( 2403): miscpower_set_interactive: /sys/class/input/input1/enabled
D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/input/input1/enabled: 0
D/PowerManagerService( 2403): blankAllDisplays() is called.
V/WindowOrientationListener( 2403): WindowOrientationListener disabled
D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2403): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/input/input0/enabled: 0
D/PowerManagerService( 2403): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2403): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2403): [PWL] sb release: PowerManagerService.Display
D/SensorService( 2403): AutoRotationSensor::activate (ident=0x7ad1d7b8, enabled=0)
I/Sensors ( 2403): HAL: batch Dry Run is complete
D/KeyguardViewMediator( 2581): onScreenTurnedOff(3)
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
D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/SurfaceFlinger( 1921): Screen released, type=0 flinger=0x40ad7550
D/PowerManagerService( 2403): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SensorManager( 2403): unregisterListener ::   
D/InputDispatcher( 2403): setInputDispatchMode: enabled=0, frozen=0
D/LockPatternUtils( 2581): isPcwEnable = 10
D/LockPatternUtils( 2581): isPcwEnable = 10
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(37)
D/SurfaceControl( 2403): Excessive delay in blankDisplay() while turning screen off: 203ms
I/libsuspend( 2403): !@[s] autosuspend_autosleep_enable
I/libsuspend( 2403): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2403): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 203ms
D/PowerManagerService( 2403): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2403): [PWL] Off : 0s ago
I/PowerManagerService( 2403): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2403): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2403): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=2403, ws=null) (elapsedTime=193)
I/PowerManagerService( 2403): [PWL]   PowerManagerService.Broadcasts: ref count=1
I/DBG_DM  ( 4226): [3.19.140541][Line:400][onPause] 
D/KeyguardViewMediator( 2581): setting alarm to turn off keyguard, seq = 2
I/SQLiteSecureOpenHelper( 3551): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3551): getDatabaseLocked(b,b,pwd)...
D/LightsService( 2403): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2403) 
I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/Sensors ( 2403): LightSensor setDelay = 200000000
D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
D/Sensors ( 2403): Light sensor flush: not enabled 0
D/Sensors ( 2403): LightSensor enable = 1
D/Sensors ( 2403): LightSensor enableSensor = 1
D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2403): turn on LED for fully charged
D/VibratorService( 2403): JNI vibratorOff()
D/SSRMv2:SIOP( 2403): SIOP:: AP = 360, Delta = 0
I/WifiTrafficPoller( 2403): evaluateTrafficStatsPolling
V/AlarmManager( 2403): waitForAlarm result :4
D/Finsky  ( 5077): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/dalvikvm( 5077): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5077): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5077): VFY: replacing opcode 0x62 at 0x0038
V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/STATUSBAR-NotificationService( 2403): ACTION_SCREEN_OFF
D/LightsService( 2403): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2403) 
D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1930): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2403): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
D/IpRemoteDisplayController( 2403): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 2403): Bridge Server is not available
D/PersonaManagerService( 2403): ACTION_SCREEN_OFF onReceive
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2581): makeExpandedInvisible
D/PhoneStatusBarView( 2581): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is finished!!!! 
D/PersonaManagerServiceHandler( 2403): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
I/NfcService( 2760): applyRouting return - 2 
E/NfcService( 2760): callback == null
D/Sensors ( 2403): LightSensor enable = 0
D/Sensors ( 2403): LightSensor enableSensor = 0
D/LightsService( 2403): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager( 2403): unregisterListener ::   
D/lights  ( 2403): led_pattern : 5 +
V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/lights  ( 2403): led_pattern : 5 -
V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/dalvikvm( 2403): Jit: resizing JitTable from 8192 to 16384
D/LockPatternUtils( 2581): isPcwEnable = 10
D/SSRMv2:SIOP( 2403): SIOP:: AP = 360, Delta = 0
D/QuickConnect[1.1][2] ( 4643): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 4643): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4643): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b6030
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b6030
D/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4643): stopLeScan()
D/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - call stopLeScan() complete
D/PowerManagerService( 2403): [PWL] sb release: PowerManagerService.Broadcasts
I/System.out( 5077): Thread-366(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 5077): Thread-366(ApacheHTTPLog):isShipBuild true
I/System.out( 5077): Thread-366(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
E/SPPClientService( 5057): [b] __InitReply__
D/AndroidRuntime( 6087): 
D/AndroidRuntime( 6087): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6087): CheckJNI is OFF
D/AndroidRuntime( 6087): setted country_code = Poland
D/AndroidRuntime( 6087): setted countryiso_code = PL
D/AndroidRuntime( 6087): setted sales_code = PLS
D/AndroidRuntime( 6087): readGMSProperty: start
D/AndroidRuntime( 6087): readGMSProperty: already setted!!
D/AndroidRuntime( 6087): readGMSProperty: end
D/AndroidRuntime( 6087): addProductProperty: start
D/dalvikvm( 6087): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6087): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6087): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6087): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6087): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/IcingInternalCorpora( 3287): getNumBytesRead when not calculated.
D/dalvikvm( 2825): GC_EXPLICIT freed 356K, 31% free 10298K/14912K, paused 5ms+7ms, total 65ms
E/memtrack( 6087): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6087): failed to load memtrack module: -2
D/dalvikvm( 6087): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/dalvikvm( 5896): GC_EXPLICIT freed 901K, 29% free 10016K/13932K, paused 2ms+6ms, total 34ms
D/AndroidRuntime( 6087): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 6087): Shutting down VM
D/dalvikvm( 6087): GC_CONCURRENT freed 99K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/System.out( 5077): Thread-366 calls detatch()
V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5077): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5077): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5077): untagSocket(68) failed with errno -22
,I/System.out( 5077): Thread-367 calls detatch()
,D/Finsky  ( 5077): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5077): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5077): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5077): untagSocket(68) failed with errno -22
,I/System.out( 5077): Thread-366 calls detatch()
,D/dalvikvm( 5077): GC_CONCURRENT freed 2096K, 25% free 10488K/13944K, paused 4ms+5ms, total 72ms
,D/dalvikvm( 5077): GC_CONCURRENT freed 732K, 16% free 11804K/13944K, paused 5ms+4ms, total 48ms
,D/dalvikvm( 5077): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/ActivityManager( 2403): Waited long enough for: ServiceRecord{42f464f8 u0 com.sec.android.gallery3d/.app.BackgroundCache}
,D/dalvikvm( 5077): GC_FOR_ALLOC freed 919K, 16% free 12605K/14972K, paused 41ms, total 42ms
,D/dalvikvm( 5077): GC_FOR_ALLOC freed 1759K, 23% free 12955K/16620K, paused 39ms, total 39ms
,D/dalvikvm( 2825): GC_EXPLICIT freed 348K, 31% free 10306K/14912K, paused 3ms+6ms, total 42ms
,D/dalvikvm( 5896): GC_EXPLICIT freed 906K, 29% free 10014K/13932K, paused 3ms+8ms, total 41ms
,D/dalvikvm( 2403): GC_EXPLICIT freed 651K, 12% free 25169K/28504K, paused 7ms+20ms, total 221ms
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5077): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5077): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5077): untagSocket(68) failed with errno -22
,I/System.out( 5077): Thread-367 calls detatch()
,D/AmoledAdjustTimer( 2403): prevTemp = 305, currTemp = 306, prevStep = 4, currStep = 4
,D/dalvikvm( 2825): GC_EXPLICIT freed 352K, 31% free 10308K/14912K, paused 5ms+10ms, total 57ms
,D/Finsky  ( 5077): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 5896): GC_EXPLICIT freed 883K, 29% free 10005K/13932K, paused 4ms+14ms, total 64ms
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/KeyguardViewMediator( 2581): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/KeyguardViewMediator( 2581): in doKeyguardLocked mIsRollUp false null
,D/WearableService( 2738): callingUid 10012, callindPid: 2738
,D/PersonaManager( 2581): isKioskContainerExistOnDevice
,D/Finsky  ( 5077): [389] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/LockPatternUtils( 2581): isPcwEnable = 10
D/LockPatternUtils( 2581): isPcwEnable = 10
,D/KeyguardViewMediator( 2581): doKeyguard: not showing because lockscreen is off
,D/DeviceConnectionService( 2738): client connected with version: 8296000
,D/Finsky  ( 5077): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5077): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PowerManagerService( 2403): [PWL] Off : 5s ago
I/PowerManagerService( 2403): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2403): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2403): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService' (uid=10031, pid=5077, ws=null) (elapsedTime=157)
,I/System.out( 5077): Thread-377(HTTPLog):isShipBuild true
,I/System.out( 5077): Thread-377(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 5896): GC_EXPLICIT freed 874K, 29% free 10010K/13932K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 2825): GC_EXPLICIT freed 343K, 31% free 10318K/14912K, paused 5ms+7ms, total 49ms
,D/PackageManager( 2403): [MSG] MCS_UNBIND
I/PackageManager( 2403): calling disconnectService()
D/PackageManager( 2403): Trying to unbind to DefaultContainerService
I/ActivityManager( 2403): Killing 5206:com.vlingo.midas/u0a34 (adj 15): empty #43
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2403): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2403): <AppSync3 Whitelist>
,V/AlarmManager( 2403): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 2403): GC_EXPLICIT freed 880K, 12% free 25169K/28504K, paused 8ms+16ms, total 210ms
,D/dalvikvm( 5896): GC_EXPLICIT freed 866K, 29% free 10014K/13932K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 2825): GC_EXPLICIT freed 359K, 31% free 10310K/14912K, paused 4ms+7ms, total 47ms
,D/BatteryService( 2403): level:100, scale:100, status:3, health:9, present:true, voltage: 4356, temperature: 307, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/LightsService( 2403): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 2403): turn off LED
,D/LightsService( 2403): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/lights  ( 2403): led_pattern : 0 +
,D/lights  ( 2403): led_pattern : 0 -
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/PowerManagerService( 2403): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2403): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2403): Waking up from sleep...
D/PowerManagerService( 2403): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2403): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2403): [s] WAKEFULNESS_AWAKE
D/lights  ( 2403): button : 1 +
,D/lights  ( 2403): button : 1 -
,I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
D/PowerManagerService( 2403): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 2403): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 2403): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2403): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/PowerUI ( 2581): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/DisplayPowerController( 2403): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/PowerManagerService( 2403): [api] [s] wakeUp (uid: 10019 pid: 2581) eventTime = 96111
D/Sensors ( 2403): LightSensor setDelay = 200000000
,D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/DisplayPowerController( 2403): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2403): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2403): [DAB] no lux value from sensor manager
D/DisplayPowerController( 2403): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/libsuspend( 2403): !@[s] autosuspend_autosleep_disable
I/libsuspend( 2403): !@[s] autosuspend_autosleep_disable done
V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3355): Disconnected process message: 10
D/Sensors ( 2403): Light sensor flush: not enabled 0
,D/Sensors ( 2403): LightSensor enable = 1
D/SurfaceFlinger( 1921): Screen acquired, type=0 flinger=0x40ad7550
,D/Sensors ( 2403): LightSensor enableSensor = 1
D/PowerManagerService( 2403): unblankAllDisplays() is called.
D/PowerManagerService( 2403): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 65558
D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 1
,I/Sensors ( 2403): HAL: batch Dry Run is complete
D/PowerManagerService( 2403): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 14ms
D/UsbDeviceManager( 2403): handleMessage -> MSG_POWER_STATE = 0
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,I/Sensors ( 2403): HAL:resetDataRates mEnabled=4
D/UsbDeviceManager( 2403): sending intent : ACTION_USB_CABLE_STATE : connected = false
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
D/RampAnimator( 2403): Light Animator Finished currentValue=8
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
,D/SensorService( 2403): AutoRotationSensor::changed settle time to [1],
D/SensorService( 2403): AutoRotationSensor::activate (ident=0x7e82a4b8, enabled=1),
D/SensorService( 2403): AutoRotationSensor::AR_init
,I/Sensors ( 2403): HAL: batch Dry Run is complete,
,D/SensorManager( 2403): registerListener :: 2, MPL Accelerometer, 200000, 0,  
,I/SELinux ( 6116): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 6116):  
,D/PowerManagerService( 2403): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 28ms,
I/Sensors ( 2403): HAL:resetDataRates mEnabled=4
D/NotificationService( 2403): cancelNotificationLocked
,D/NotificationService( 2403):  hasClearableItems
D/NotificationService( 2403):  has clearable items no 
D/NotificationService( 2403): cancelNotificationLocked: cancel alarm,
,D/NotificationService( 2403): cancelNotificationLocked: cancel alarm,
D/STATUSBAR-StatusBarManagerService( 2403): sendNotification(3) - 5,
D/LightsService( 2403): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2403) 
D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off,
D/UsbDeviceManager( 2403): received ACTION_POWER_DISCONNECTED = -1
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2,
D/LightsService( 2403): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SensorManager( 2403): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  ,
,V/KeyguardServiceDelegate( 2403): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@42e3ce80)
,D/InputDispatcher( 2403): setInputDispatchMode: enabled=1, frozen=0
,D/KeyguardViewMediator( 2581): onScreenTurnedOn, seq = 3
,D/KeyguardViewMediator( 2581): notifyScreenOnLocked
,D/KeyguardViewMediator( 2581): handleNotifyScreenOn
D/KeyguardViewManager( 2581): onScreenTurnedOn()
,I/KeyguardEffectViewMain( 2581): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 2581): KeyguardEffectViewParticleSpace : screenTurnedOn
,D/VisualEffectParticleEffect( 2581): screenOnAnimationStart
V/KeyguardViewManager( 2581): send wm null token: host was null
,V/KeyguardServiceDelegate( 2403): **** SHOWN CALLED ****
I/WindowManager( 2403): No lock screen! windowToken=null
,D/LockPatternUtils( 2581): isPcwEnable = 10
,I/SELinux ( 6116): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6116):  
I/SELinux ( 6116):  
,I/SELinux ( 6116): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6116): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6116): >>>>> Normal User
,E/dalvikvm( 6116): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 6116): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/BatteryMeterView( 2581): onDraw batteryColor : -1
,D/TimaKeyStoreProvider( 6116): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6116): Cannot add TimaSignature Service, License check Failed
D/SensorService( 2403): AutoRotationSensor::process: Acc  eventTimestamp = 96231171382, previousAccTimestamp = 86053416729, difference = 10177754653 
,D/SensorService( 2403): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/ActivityThread( 6116): Added TimaKesytore provider
,D/DisplayPowerController( 2403): [api] [DAB] onSensorChanged : 1st lux : 0.0
,D/DisplayPowerController( 2403): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,D/SurfaceControl( 2403): Excessive delay in unblankDisplay() while turning screen on: 229ms
,D/MISC PowerHAL( 2403): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2403): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 231ms
,D/PowerManagerNotifier( 2403): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,D/PowerManagerService( 2403): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2403): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SurfaceFlinger( 1921): id=19 Removed FlectronBea (10/10)
,D/DisplayPowerController( 2403): !@ElectronBeam exit
I/SurfaceFlinger( 1921): id=19 Removed FlectronBea (-2/10)
D/lights  ( 2403): lcd : 8 +
D/SensorService( 2403): AutoRotationSensor::process: Acc  eventTimestamp = 96297833786, previousAccTimestamp = 86053416729, difference = 10244417057 
D/SensorService( 2403):  [AR] 0.2 -0.0 9.9
D/SensorService( 2403): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/input/input1/enabled: 1
,D/MISC PowerHAL( 2403): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/input/input0/enabled: 1
,D/lights  ( 2403): lcd : 8 -
D/DisplayPowerController( 2403): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2403): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/LockPatternUtils( 2581): isPcwEnable = 10
D/SamsungIME( 2976): showDlgMsgBox : false true true
,I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.USER_PRESENT
,I/DBG_DM  ( 4226): [3.19.140541][Line:408][onResume] 
V/AlarmManager( 2403): waitForAlarm result :8
D/LightsService( 2403): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2403) 
D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/PalmMotionService( 2403): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2403): SURFACE_PALM_SWIPE: 1
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,I/NfcService( 2760): applyRouting return - 2 
E/MotionRecognitionService( 2403):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService( 2403): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/NfcService( 2760): callback == null
D/SSRMv2:TSP:AirViewOnOff( 2403): SettingsAirViewInfo:: 000000000
,I/DBG_DM  ( 4226): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 45
,I/WifiTrafficPoller( 2403): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2403): ACTION_SCREEN_ON
,D/LightsService( 2403): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2403) 
D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2403): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,I/DBG_DM  ( 4226): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 1930): setParameters(screen_state=on)
,I/SecExternalDisplayIntents_Java( 2403): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,I/DBG_DM  ( 4226): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4226): [3.19.140541][Line:418][onResume] Postpone Count : 45
,D/IpRemoteDisplayController( 2403): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 2403): Bridge Server is not available
,D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
,D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2403): Excessive delay in MISC setInteractive(true) while turning screen on: 166ms
D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
,D/SEC PowerHAL( 2403): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
D/SEC PowerHAL( 2403): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,I/DBG_DM  ( 4226): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
D/PowerManagerService( 2403): Excessive delay in nativeSetInteractive(true): 168ms
D/PowerManagerService( 2403): SecHardwareInterface.setBatteryADC : true
,D/PersonaManagerService( 2403): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2403): MSG_ACTION_SCREEN_ON called
,D/dalvikvm( 6116): GC_FOR_ALLOC freed 3018K, 32% free 9556K/13936K, paused 46ms, total 47ms
,I/DBG_DM  ( 4226): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,I/NfcService( 2760): NFC: Screen On & Cover Open
D/STATUSBAR-NetworkController( 2581): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,I/NfcService( 2760): applyRouting return - 2 
,E/NfcService( 2760): callback == null
,I/DBG_DM  ( 4226): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService( 2403): sendNotification(2) - 4
I/DBG_DM  ( 4226): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 45
D/dalvikvm( 6116): GC_CONCURRENT freed 229K, 32% free 9580K/13936K, paused 17ms+21ms, total 62ms
I/DBG_DM  ( 4226): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4226): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4226): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4226): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4226): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4226): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,I/SELinux ( 6131): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6131):  
,D/Activity( 4226): setTransGradationMode to true
I/ActivityManager( 2403): Killing 5340:com.policydm/1000 (adj 15): empty #43
,D/StatusBarManagerService( 2403): semi p:4226,o:t
D/PhoneStatusBar( 2581): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/SELinux ( 6131): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6131):  
I/SELinux ( 6131):  
,I/SELinux ( 6131): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6131): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6131): >>>>> Normal User
,E/dalvikvm( 6131): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
,E/SELinux ( 6131): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 350, Delta = -10
,D/TimaKeyStoreProvider( 6131): in addTimaSignatureService
,D/QuickConnect[1.1][2] ( 4643): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
,D/TimaKeyStoreProvider( 6131): Cannot add TimaSignature Service, License check Failed
,V/QuickConnect[1.1][2] ( 4643): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4643): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b6030
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b6030
D/ActivityThread( 6131): Added TimaKesytore provider
V/QuickConnect[1.1][2] ( 4643): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b6030
,V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b6030
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b6030
D/QuickConnect[1.1][2] ( 4643): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 4643): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 4643): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 4643): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 4846): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4846): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,D/PowerManagerService( 2403): [PWL] sb release: PowerManagerService.Broadcasts
,D/dalvikvm( 6131): GC_CONCURRENT freed 3003K, 32% free 9568K/13936K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 6131): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/KIES_RECEIVE( 6131): [APK BnR] Receive KIES_USB_DISCONNECT
W/ContextImpl( 6131): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
,E/TranscodeReceiver( 5853): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,D/videowall-Global( 5853): core_num = 4
,D/dalvikvm( 5853): No JNI_OnLoad found in /system/lib/libsavsff.so 0x422a1c50, skipping init
,W/linker  ( 5853): libvwengine.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/videowall-Global( 5853): density : 2.0 width : 720 height : 1280 Raw width : 720 Raw height : 1280
,D/videowall-Global( 5853): dsp : 720, swkey : false, Cores : 4, Clock : 0
,I/SELinux ( 6143): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6143):  
,I/SELinux ( 6143): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6143):  
I/SELinux ( 6143):  
,I/SELinux ( 6143): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6143): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 6143): >>>>> Normal User
,E/dalvikvm( 6143): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 6143): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 6143): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6143): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6143): Added TimaKesytore provider
,D/dalvikvm( 6143): GC_CONCURRENT freed 2994K, 32% free 9582K/13936K, paused 4ms+3ms, total 28ms
,D/dalvikvm( 6143): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/SELinux ( 6159): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6159):  
,I/ActivityManager( 2403): Killing 5393:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 13% free 9505K/10912K, paused 4ms+5ms, total 50ms
,I/SELinux ( 6159): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6159):  
I/SELinux ( 6159):  
,I/SELinux ( 6159): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6159): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6159): >>>>> Normal User
,E/dalvikvm( 6159): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
,E/SELinux ( 6159): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10912K, paused 2ms+4ms, total 33ms
,D/TimaKeyStoreProvider( 6159): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6159): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6159): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10912K, paused 3ms+4ms, total 32ms
,D/dalvikvm( 5896): GC_EXPLICIT freed 872K, 29% free 10013K/13932K, paused 4ms+12ms, total 50ms
,D/dalvikvm( 6159): GC_CONCURRENT freed 2999K, 32% free 9570K/13932K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 6159): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2825): GC_EXPLICIT freed 343K, 31% free 10319K/14912K, paused 3ms+7ms, total 48ms
,I/iu.Environment( 5488): update battery state; isPlugged? false*
,I/iu.SyncManager( 5488): SYNC; picasa accounts
,I/ActivityManager( 2403): Killing 5436:com.google.android.apps.magazines/u0a115 (adj 15): empty #43
,I/iu.Environment( 3287): update battery state; isPlugged? false*
,I/iu.UploadsManager( 5488): num queued entries: 0
,I/iu.UploadsManager( 3287): num queued entries: 0
,I/iu.UploadsManager( 5488): num updated entries: 0
,I/iu.UploadsManager( 3287): num updated entries: 0
I/iu.SyncManager( 3287): NEXT; no task
,I/iu.SyncManager( 5488): NEXT; no task
,I/GCoreUlr( 2738): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,I/GCoreUlr( 2738): DispatchingService.onCreate()
D/PicasaUploader( 6159):    wifiOnlyPhoto changed to true
D/PicasaUploader( 6159):    wifiOnlyVideo changed to true
,D/PicasaUploader( 6159):    syncOnBattery changed to true
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:TSP:AirViewOnOff( 2403): SettingsAirViewInfo:: 000000000,
,D/PicasaUploaderSync( 6159): sync account database,
,D/PicasaUploaderSync( 6159): accounts in DB=1
,D/PicasaUploaderSyncManager( 6159): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PicasaUploaderSyncManager( 6159): background data: true
,D/PicasaUploaderSyncManager( 6159): battery info: false
,D/LockPatternUtils( 2581): isPcwEnable = 10
,I/GCoreUlr( 2738): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4846): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4846): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/lights  ( 2403): button : 0 +
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/lights  ( 2403): button : 0 -
,D/comsamsunglog( 4846): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4846): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4846): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4846): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 4846): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454951100000
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454948703404
,D/daemonapp( 4846): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 4846): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/GCoreUlr( 2738): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2738): Unbound from all location providers
,I/GCoreUlr( 2738): Place inference reporting - stopped
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4846): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4846): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
I/GCoreUlr( 2738): DispatchingService.onDestroy()
,I/GCoreUlr( 2738): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2738): Unbound from all location providers
,I/GCoreUlr( 2738): Place inference reporting - stopped
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 4846): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4846): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4846): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4846): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4846): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4846): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4846): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 2403): GC_EXPLICIT freed 1213K, 12% free 25204K/28504K, paused 8ms+14ms, total 198ms
,D/dalvikvm( 5896): GC_EXPLICIT freed 872K, 29% free 10011K/13932K, paused 4ms+10ms, total 48ms
,D/dalvikvm( 2825): GC_EXPLICIT freed 356K, 31% free 10328K/14912K, paused 5ms+8ms, total 53ms
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2403): prevTemp = 306, currTemp = 307, prevStep = 4, currStep = 4
,D/dalvikvm( 5896): GC_CONCURRENT freed 1473K, 25% free 10495K/13932K, paused 1ms+9ms, total 32ms
,I/SettingSearch/SearchIntentReceiver( 2825): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2825): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 2825): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 2825): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2825): LOCALE_CHANGED call search setting db finish!!
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager( 2403): waitForAlarm result :4
,D/Headlines( 5420): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/Headlines( 5420): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 5420): Breath 40656 latestRequest time : 1454948669560 current time : 1454948710218
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 5077): GC_CONCURRENT freed 7124K, 35% free 16214K/24696K, paused 5ms+5ms, total 98ms
,D/dalvikvm( 5077): WAIT_FOR_CONCURRENT_GC blocked 83ms
,D/Finsky  ( 5077): [379] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5077): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/BatteryService( 2403): level:100, scale:100, status:2, health:2, present:true, voltage: 4350, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
D/PowerUI ( 2581): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2403): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/PowerManagerService( 2403): [api] [s] wakeUp (uid: 10019 pid: 2581) eventTime = 106081
V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/PowerUI ( 2581): playSound : 1
,I/AudioFlinger( 1930): sleepTime is reduced to minimum forcely
D/UsbDeviceManager( 2403): handleMessage -> MSG_POWER_STATE = 1
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,I/AudioFlinger( 1930): sleepTime is reduced to minimum forcely
,I/EntropyMixer( 2403): Writing entropy...
I/AudioFlinger( 1930): sleepTime is reduced to minimum forcely
V/Vibrator( 2581): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
,V/Vibrator( 2581): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
,I/AudioFlinger( 1930): sleepTime is reduced to minimum forcely
D/UsbDeviceManager( 2403): sending intent : ACTION_USB_CABLE_STATE : connected = true
V/VibratorService( 2403): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2403): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2403): JNI vibratorOff()
,I/AudioFlinger( 1930): sleepTime is reduced to minimum forcely
,D/VibratorService( 2403): JNI vibratorOn() : 100
E/TranscodeReceiver( 5853): onReceive : android.intent.action.ACTION_POWER_CONNECTED
I/AudioFlinger( 1930): sleepTime is reduced to minimum forcely
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/PowerUI ( 2581): RINGER_MODE_VIBRATE
,I/AudioFlinger( 1930): sleepTime is reduced to minimum forcely
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/AudioFlinger( 1930): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1930): sleepTime is reduced to minimum forcely
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
I/AudioFlinger( 1930): sleepTime is reduced to minimum forcely
D/TranscodeService( 5853): onCreate()
,D/BatteryMeterView( 2581): onDraw batteryColor : -1
,I/SELinux ( 6178): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6178):  
,D/dalvikvm( 5853): No JNI_OnLoad found in /system/lib/libsavsvc.so 0x422a1c50, skipping init
,D/dalvikvm( 5853): No JNI_OnLoad found in /system/lib/libsavscmn.so 0x422a1c50, skipping init
,D/dalvikvm( 5853): No JNI_OnLoad found in /system/lib/libsthmb.so 0x422a1c50, skipping init
D/TranscodeService( 5853): power? : true / screen off : false
,D/TranscodeService( 5853): releaseTranscodeThread.
,D/VibratorService( 2403): JNI vibratorOff()
,I/SELinux ( 6178): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6178):  
I/SELinux ( 6178):  
,I/SELinux ( 6178): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6178): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6178): >>>>> Normal User
,E/dalvikvm( 6178): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 6178): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6178): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6178): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6178): Added TimaKesytore provider
,D/dalvikvm( 6178): GC_CONCURRENT freed 2997K, 32% free 9577K/13936K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 6178): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/sCloudBackupApp( 6178): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 6178): Other Intent
,D/PicasaUploaderSyncManager( 6159): battery info: true
,I/iu.Environment( 5488): update battery state; isPlugged? true*
,I/iu.UploadsManager( 5488): num queued entries: 0
,I/iu.UploadsManager( 5488): num updated entries: 0
,I/iu.SyncManager( 5488): NEXT; no task
,I/iu.FingerprintManager( 5488): Start processing all media
,I/iu.FingerprintManager( 5488): Start processing media store URI: content://media/external/images/media
,I/iu.Environment( 3287): update battery state; isPlugged? true*
,I/iu.UploadsManager( 3287): num queued entries: 0
,I/iu.FingerprintManager( 5488): Start processing media store URI: content://media/external/video/media
,I/iu.UploadsManager( 3287): num updated entries: 0
,I/iu.SyncManager( 3287): NEXT; no task
,E/NetworkScheduler.SchedulerReceiver( 2854): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2854): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/GCoreUlr( 2738): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/GCoreUlr( 2738): DispatchingService.onCreate()
,I/iu.FingerprintManager( 3287): Start processing all media
,I/iu.FingerprintManager( 5488): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3287): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5488): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 5488): Finished generating fingerprints; 0.076 seconds
,I/iu.FingerprintManager( 5488):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/iu.FingerprintManager( 3287): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 3287): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3287): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3287): Finished generating fingerprints; 0.070 seconds
,I/iu.FingerprintManager( 3287):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2738): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/GCoreUlr( 2738): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2738): Unbound from all location providers
,I/GCoreUlr( 2738): Place inference reporting - stopped
,I/GCoreUlr( 2738): DispatchingService.onDestroy(),
,I/GCoreUlr( 2738): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2738): Unbound from all location providers
,I/GCoreUlr( 2738): Place inference reporting - stopped
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 350, Delta = 0
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2403):   0.2 -0.0 9.9
,E/Watchdog( 2403): !@Sync 3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2403): prevTemp = 307, currTemp = 306, prevStep = 4, currStep = 4
,I/Icing   ( 3287): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music
,I/Icing   ( 3287): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A
,D/SensorService( 2403):   0.2 -0.1 9.9
,I/ActivityManager( 2403): Waited long enough for: ServiceRecord{4312d688 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/BatteryService( 2403): level:100, scale:100, status:2, health:2, present:true, voltage: 4381, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 340, Delta = -10
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/FactoryTest( 5152): Not factory mode
,D/FactoryTest( 5152): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5152): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5152): still no open session command from host, so toast
W/ContextImpl( 5152): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5152): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy( 2403): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2403): mDVFSHelper.acquire()
,I/DBG_DM  ( 4226): [3.19.140541][Line:359][onUserLeaveHint] 
I/SQLiteSecureOpenHelper( 3551): getWritableDatabase(pwd)
D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
I/SQLiteSecureOpenHelper( 3551): getDatabaseLocked(b,b,pwd)...
,E/MTPRx   ( 5152): started activity for popup
,I/DBG_DM  ( 4226): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 45
,I/DBG_DM  ( 4226): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4226): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4226): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,I/DBG_DM  ( 4226): [3.19.140541][Line:362][onUserLeaveHint] Home Key!!
,I/DBG_DM  ( 4226): [3.19.140541][Line:315][xuiFotaPostponeDefault] 
,I/DBG_DM  ( 4226): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4226): [3.19.140541][Line:5174][xdbSetDownloadPostponeStatus] Set Download Postpone status : 3
,I/DBG_DM  ( 4226): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 3 / Notification IndicatorState : 3
D/NotificationService( 2403): cancelNotificationLocked
D/NotificationService( 2403):  hasClearableItems
D/NotificationService( 2403):  has clearable items no 
D/NotificationService( 2403): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2403): cancelNotificationLocked: cancel alarm
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
D/STATUSBAR-StatusBarManagerService( 2403): sendNotification(3) - 4
,I/DBG_DM  ( 4226): [3.19.140541][Line:3638][xdbSetFUMOStatus] FUMO_Status : 220
D/LightsService( 2403): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2403) 
D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2403): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:1
D/STATUSBAR-StatusBarManagerService( 2403): sendNotification(1) - 3
,D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
,I/DBG_DM  ( 4226): [3.19.140541][Line:368][xuiFotaPostponeDefault] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
,I/DBG_DM  ( 4226): [3.19.140541][Line:503][xuiFotaPostponeStartTimer] 
,D/PhoneStatusBar( 2581): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422f7ae0
,I/DBG_DM  ( 4226): [3.19.140541][Line:400][onPause] 
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2,
,V/WindowOrientationListener( 2403): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowOrientationListener( 2403): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 2403): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/Launcher( 2788): onRestart, Launcher: 1110306192
D/Launcher( 2788): onStart, Launcher: 1110306192
,D/Launcher.HomeView( 2788): onStart
,E/SettingsReceiverActivity( 5152): PREF_DONT_ASK_AGAIN : true
,I/SQLiteSecureOpenHelper( 3551): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3551): getDatabaseLocked(b,b,pwd)...
,I/SurfaceFlinger( 1921): id=20 createSurf (720x1280),1 flag=4, Mauncher
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(13)
,D/STATUSBAR-StatusBarManagerService( 2403): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
,D/StatusBarManagerService( 2403): tr p:2788,o:f
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2403): semi p:2788,o:f
,D/SettingsReceiverActivity( 5152): dev.kiessupport is : TRUE
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Launcher( 2788): onResume, Launcher: 1110306192
,D/Launcher.HomeView( 2788): onResume
D/StatusBarManagerService( 2403): semi p:2788,o:f
D/StatusBarManagerService( 2403): tr p:2788,o:f
D/StatusBarManagerService( 2403): semi p:2788,o:f
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/MenuAppsGridFragment( 2788): onResume
,D/WallpaperManager( 2788): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
,D/Mms/UIEventReceiver( 5231): ui event
,D/WallpaperManager( 2788): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 2788): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2403): mDVFSHelper.release()
,D/checkbox( 4226): TwCheckBox.onDetachedToWindow()
,I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (9/10)
,I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@8
,I/SurfaceFlinger( 1921): id=17 Removed EimLayer (5/9)
,I/SurfaceFlinger( 1921): id=17 Removed EimLayer (-2/9)
I/SurfaceFlinger( 1921): id=16 Removed EimLayer (4/8)
,I/SurfaceFlinger( 1921): id=16 Removed EimLayer (-2/8)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@8
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2403): prevTemp = 306, currTemp = 307, prevStep = 4, currStep = 4
,I/ActivityManager( 2403): Waited long enough for: ServiceRecord{43290a28 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/PowerManagerService( 2403): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2581
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/NotificationService( 2403): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null])),
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-StatusBarManagerService( 2403): sendNotification(1) - 5
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/RCPManagerService( 2403): NotificationReceiver onReceive()
D/RCPManagerService( 2403):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
,D/RCPManagerService( 2403): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298403
D/RCPManagerService( 2403): getPolicy: policy value returned = false
D/RCPManagerService( 2403): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2403): app label == com.android.systemui
,D/RCPManagerService( 2403): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298403
D/RCPManagerService( 2403): getPolicy: policy value returned = true
D/RCPManagerService( 2403): Calling User is -1
,D/RCPManagerService( 2403): userid of SBN ==-1
D/UserManagerService( 2403): User -1does not exists!!
E/PersonaManagerService( 2403): returning null in  getPersonasForUser
,D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2581): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422f7ae0
,D/BatteryMeterView( 2581): onDraw batteryColor : -1
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(59)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 340, Delta = 0
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(60)
,D/PowerManagerService( 2403): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2403): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2403): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2403): lcd : 2 +
D/RampAnimator( 2403): Light Animator Finished currentValue=2
,D/lights  ( 2403): lcd : 2 -
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/AmoledAdjustTimer( 2403): prevTemp = 307, currTemp = 308, prevStep = 4, currStep = 4
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(56)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2403):   0.2 -0.1 9.9
,D/PowerManagerService( 2403): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2403): [PWL] On : 96105 (39977 ms ago)
I/PowerManagerService( 2403): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService( 2403): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2581, ws=null) (elapsedTime=9882)
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5420): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5420): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5420): Breath 72649 latestRequest time : 1454948669560 current time : 1454948742209
,D/dalvikvm( 2854): GC_EXPLICIT freed 1517K, 23% free 10815K/13928K, paused 5ms+7ms, total 62ms
,I/VacuumService( 2738): Vacuum at: now=1454948742494 tag=VacuumService
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 340, Delta = 0
,I/PhenotypeConfigurator( 2738): Scheduling Phenotype for one-off execution 10916 seconds from now (1454948742964)
,D/dalvikvm( 2738): GC_CONCURRENT freed 1837K, 23% free 11669K/14964K, paused 5ms+7ms, total 70ms
,D/dalvikvm( 2738): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/GetConfigurationSnapshotOperation( 2738): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2738): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 2738): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2738): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2738): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2738): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2738): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2738): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2738): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 2403): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 2738): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2738): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2738): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 2738): Thread-113(HTTPLog):isShipBuild true
,I/System.out( 2738): Thread-113(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2403):   0.1 -0.0 9.9
,D/LocationManagerService( 2403): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/Watchdog( 2403): !@Sync 4
,D/dalvikvm( 2738): GC_CONCURRENT freed 1466K, 20% free 12169K/15064K, paused 4ms+10ms, total 51ms
,D/LocationManagerService( 2403): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 308, currTemp = 309, prevStep = 4, currStep = 4
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2403):   0.2 -0.0 9.9
,D/PowerManagerService( 2403): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2581 (0x0)
I/PowerManagerService( 2403): Nap time...
,D/PowerManagerService( 2403): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2403): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2403): Going to sleep due to screen timeout...
,D/PowerManagerService( 2403): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2403): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
D/Sensors ( 2403): LightSensor enable = 0
,D/Sensors ( 2403): LightSensor enableSensor = 0
,D/SensorManager( 2403): unregisterListener ::   
D/DisplayPowerController( 2403): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,I/SurfaceFlinger( 1921): id=21 createSurf (720x1280),-1 flag=20004, FlectronBea
I/DisplayPowerController( 2403): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,I/DisplayPowerController( 2403): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,I/Sensors ( 2403): HAL:resetDataRates mEnabled=4
,D/SensorManager( 2403): unregisterListener ::   
D/DisplayPowerController( 2403): !@ElectronBeam entry
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2403): lcd : 0 +
,D/lights  ( 2403): lcd : 0 -
,D/MISC PowerHAL( 2403): miscpower_set_interactive: /sys/class/input/input1/enabled
D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/input/input1/enabled: 0
,V/WindowOrientationListener( 2403): WindowOrientationListener disabled
D/PowerManagerService( 2403): blankAllDisplays() is called.
D/PowerManagerService( 2403): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2403): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2403): [PWL] sb release: PowerManagerService.Display
D/SensorService( 2403): AutoRotationSensor::activate (ident=0x7e82a4b8, enabled=0)
I/Sensors ( 2403): HAL: batch Dry Run is complete
D/KeyguardViewMediator( 2581): onScreenTurnedOff(3)
D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2403): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2403): sysfs_write +: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2403): sysfs_write -: /sys/class/input/input0/enabled: 0
D/SensorManager( 2403): unregisterListener ::   
D/InputDispatcher( 2403): setInputDispatchMode: enabled=0, frozen=0
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
D/PowerManagerService( 2403): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SurfaceFlinger( 1921): Screen released, type=0 flinger=0x40ad7550
D/LockPatternUtils( 2581): isPcwEnable = 10
D/Launcher.HomeView( 2788): onPause
D/LockPatternUtils( 2581): isPcwEnable = 10
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2403): tr p:2788,o:f
D/KeyguardViewMediator( 2581): setting alarm to turn off keyguard, seq = 3
,D/Launcher.HomeView( 2788): onStop
D/LightsService( 2403): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2403) 
,I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
D/Sensors ( 2403): LightSensor setDelay = 200000000
D/Sensors ( 2403): LightSensor setSensorDelay = 200000000,
D/Sensors ( 2403): Light sensor flush: not enabled 0
,D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On,
D/Sensors ( 2403): LightSensor enable = 1
D/Sensors ( 2403): LightSensor enableSensor = 1
,D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  ,
D/BatteryService( 2403): turn on LED for fully charged
D/VibratorService( 2403): JNI vibratorOff()
,I/WifiTrafficPoller( 2403): evaluateTrafficStatsPolling,
,D/STATUSBAR-NotificationService( 2403): ACTION_SCREEN_OFF,
D/LightsService( 2403): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2403) 
,D/LightsService( 2403): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off,
I/AudioHardwareTinyALSA( 1930): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2403): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2403): intent received android.intent.action.SCREEN_OFF,
,D/IpRemoteDisplayController( 2403): Bridge Server is not available,
,D/PersonaManagerService( 2403): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2403): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2581): makeExpandedInvisible
D/PhoneStatusBarView( 2581): marqueeStatusBar:123, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2760): applyRouting return - 2 
,E/NfcService( 2760): callback == null
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SurfaceControl( 2403): Excessive delay in blankDisplay() while turning screen off: 225ms
I/libsuspend( 2403): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2403): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2403): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 226ms
D/PowerManagerService( 2403): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2403): [PWL] Off : 0s ago
I/PowerManagerService( 2403): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2403): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2403): [PWL]       PARTIAL_WAKE_LOCK              'GCoreFlp' (uid=10012, pid=2738, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=21)
I/PowerManagerService( 2403): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/LockPatternUtils( 2581): isPcwEnable = 10
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(29)
D/SSRMv2:SIOP( 2403): SIOP:: AP = 340, Delta = 0
,D/QuickConnect[1.1][2] ( 4643): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 4643): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4643): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b6030
V/QuickConnect[1.1][2] ( 4643): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b6030
D/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4643): stopLeScan()
,D/QuickConnect[1.1][2] ( 4643): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 5853): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 5853): power? : true / screen off : true
,D/PowerManagerService( 2403): [PWL] sb release: PowerManagerService.Broadcasts
D/TranscodeService( 5853): Music is = false
D/TranscodeService( 5853): runvideoplayer is false
,D/TranscodeService( 5853): Thread start
,D/LightsService( 2403): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2403): LightSensor enable = 0
D/Sensors ( 2403): LightSensor enableSensor = 0
D/SensorManager( 2403): unregisterListener ::   
D/lights  ( 2403): led_pattern : 5 +
,D/lights  ( 2403): led_pattern : 5 -
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 2403): GC_EXPLICIT freed 3172K, 16% free 25008K/29644K, paused 9ms+18ms, total 224ms
D/TranscodeService( 5853): WakeLock.acquire()
,D/videowall-FileMgr( 5853): thumbnailDBSync -1
,D/WVMDrmPlugIn( 1929): WVMDrmPlugin::onInitialize : 2217
,D/WVMDrmPlugIn( 1929): WVMDrmPlugin::onSetOnInfoListener : add 2217
I/PrGenericPlugin( 1929): [A] ENTER onInitialize : 0x8a9
,I/PrGenericPlugin( 1929): [A] LEAVE onInitialize : 0x8a9
,D/TranscodeService( 5853): Thread end
,D/TranscodeService( 5853): WakeLock.release()
D/TranscodeService( 5853): onDestroy()
,D/TranscodeService( 5853): releaseTranscodeThread.
,V/ApplicationPolicy( 2403): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,I/ActivityManager( 2403): Killing 5440:com.samsung.android.magazine.service/u0a110 (adj 15): empty #43
,D/AmoledAdjustTimer( 2403): prevTemp = 309, currTemp = 310, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :4,
,D/KeyguardViewMediator( 2581): received DELAYED_KEYGUARD_ACTION with seq = 3, mDelayedShowingSequence = 3,
,D/LockPatternUtils( 2581): isPcwEnable = 10,
,D/KeyguardViewMediator( 2581): in doKeyguardLocked mIsRollUp false null,
,D/PersonaManager( 2581): isKioskContainerExistOnDevice,
,D/LockPatternUtils( 2581): isPcwEnable = 10,
D/LockPatternUtils( 2581): isPcwEnable = 10
,D/KeyguardViewMediator( 2581): doKeyguard: not showing because lockscreen is off,
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/PowerManagerService( 2403): [PWL] Off : 5s ago,
,V/AlarmManager( 2403): waitForAlarm result :8,
,D/Headlines( 5420): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5420): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5420): Breath 90025 latestRequest time : 1454948669560 current time : 1454948759585,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 2581): GC_CONCURRENT freed 15599K, 34% free 34002K/50956K, paused 21ms+11ms, total 140ms,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3355): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 340, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 310, currTemp = 310, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 15s ago,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = -10,
,E/Watchdog( 2403): !@Sync 5,
,D/AmoledAdjustTimer( 2403): prevTemp = 310, currTemp = 309, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3355): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2403): [PWL] Off : 30s ago,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0,
,V/AlarmManager( 2403): waitForAlarm result :4,
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/AmoledAdjustTimer( 2403): prevTemp = 309, currTemp = 308, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,D/Headlines( 5420): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5420): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5420): Breath 120023 latestRequest time : 1454948669560 current time : 1454948789584
,D/Headlines( 5420): stop ,
,D/Headlines( 5420): Breath.onDestroy : ,
I/ActivityManager( 2403): Killing 4732:com.android.email/u0a157 (adj 15): empty #43
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3355): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 308, currTemp = 307, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2403): [PWL] Off : 50s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0
,E/Watchdog( 2403): !@Sync 6,
,D/AmoledAdjustTimer( 2403): prevTemp = 307, currTemp = 306, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3355): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 306, currTemp = 305, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 75s ago,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2403): stay LED for fully charged,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3355): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0,
,E/Watchdog( 2403): !@Sync 7,
,D/AmoledAdjustTimer( 2403): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2403): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2403): stay LED for fully charged,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 105s ago,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2403): !@Sync 8,
,D/AmoledAdjustTimer( 2403): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2403): !@Sync 9,
,D/AmoledAdjustTimer( 2403): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2403): initializing...,
I/TLC_TIMA_PKM_initialize( 2403): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2403): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2403): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2403): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2403): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2403): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2403): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 2403): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2403): device_id = 0x0
,I/TZ: mc_tlc_communication( 2403): tlc_open() was called
,I/TZ: mc_tlc_communication( 2403): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2403): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2403): Opening the session
,I/TZ: mc_tlc_communication( 2403): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2403): Trustlet response is completed,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 6758,
,E/Watchdog( 2403): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2403): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3355): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2403): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :4,
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 6862): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6862):  
,I/SELinux ( 6862): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6862):  
I/SELinux ( 6862):  
I/SELinux ( 6862): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 6862): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6862): >>>>> Normal User
,E/dalvikvm( 6862): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 6862): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6862): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 6862): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 6862): Added TimaKesytore provider,
,D/dalvikvm( 6862): GC_CONCURRENT freed 3001K, 32% free 9572K/13936K, paused 3ms+2ms, total 27ms,
,D/dalvikvm( 6862): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/ActivityManager( 2403): Killing 4834:com.samsung.android.service.travel/u0a170 (adj 15): empty #43,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2403): !@Sync 11,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 225s ago,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2403): !@Sync 12,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :4,
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,E/SPPClientService( 5057): [b] __PingReply__,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3355): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2403): !@Sync 13,
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 275s ago,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/dalvikvm( 2403): GC_FOR_ALLOC freed 3025K, 18% free 24923K/30344K, paused 199ms, total 200ms,
D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 14
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 299, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2403): !@Sync 15
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2403): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2403): !@Sync 16
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 7353
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 7364
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2403): !@Sync 17
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2403): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2403): !@Sync 18
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2403): !@Sync 19
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 455s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2403): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 3740): GC_CONCURRENT freed 2893K, 31% free 9728K/13980K, paused 13ms+2ms, total 58ms
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2403): !@Sync 21
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/GAV2    ( 5171): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5171): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2403): !@Sync 22
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2403): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2403): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2403): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 23
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 24
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/dalvikvm( 2403): GC_FOR_ALLOC freed 2883K, 18% free 24912K/30344K, paused 197ms, total 198ms
D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 25
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 26
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 680s ago
,E/Watchdog( 2403): !@Sync 27
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 28
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 29
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2403): [PWL] Off : 765s ago
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 31
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :4
,I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
,D/LightsService( 2403): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2403): LightSensor setDelay = 200000000
D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
D/Sensors ( 2403): Light sensor flush: not enabled 0
,D/Sensors ( 2403): LightSensor enable = 1
,D/Sensors ( 2403): LightSensor enableSensor = 1
,D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors ( 2403): LightSensor enable = 0
D/Sensors ( 2403): LightSensor enableSensor = 0
,D/SensorManager( 2403): unregisterListener ::   
D/LightsService( 2403): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/ConnectivityService( 2403): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 32
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :12
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5057): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3287): Aggregate from 1454947778902 (log), 1454947778902 (data)
,D/dalvikvm( 3287): GC_CONCURRENT freed 1791K, 21% free 12115K/15264K, paused 6ms+8ms, total 66ms
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2403): [PWL] Off : 855s ago
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 33
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 34
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/dalvikvm( 2403): GC_FOR_ALLOC freed 2859K, 18% free 24942K/30344K, paused 204ms, total 205ms
D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 35
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 950s ago
,E/Watchdog( 2403): !@Sync 36
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 37
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 38
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 39
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 41
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3355): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3355): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 42
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5057): [b] __PingReply__
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2403): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2403): <AppSync3 Whitelist>
,V/AlarmManager( 2403): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2403): [PWL] Off : 1155s ago
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1200000ms)
```
