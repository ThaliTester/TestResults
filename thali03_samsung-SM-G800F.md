#### Test 584164489c56086_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 2831): GC_EXPLICIT freed 350K, 24% free 10284K/13528K, paused 4ms+8ms, total 52ms
,--------- beginning of /dev/log/system
I/ActivityManager( 2418): Killing 5273:com.sec.android.cloudagent/u0a2 (adj 15): empty #43
D/dalvikvm( 5898): GC_EXPLICIT freed 1028K, 26% free 10011K/13440K, paused 3ms+9ms, total 59ms
E/SPPClientService( 5055): [b] __ProvisionReply__
E/SPPClientService( 5055): [a] [ConnectionManager] Connection is already disconnected.
E/SPPClientService( 5055): [d] null
V/AlarmManager( 2418):  next == MAX_VALUE
E/SPPClientService( 5055): [g] getPLMN return empty string
E/SPPClientService( 5055): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
E/SPPClientService( 5055): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
E/SPPClientService( 5055): [a] [ConnectionManager] Connection is already disconnected.
D/dalvikvm( 5055): GC_CONCURRENT freed 2131K, 23% free 10407K/13440K, paused 3ms+15ms, total 57ms
E/SPPClientService( 5055): [g] getNetMCC return empty string
D/AndroidRuntime( 6089): 
D/AndroidRuntime( 6089): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6089): CheckJNI is OFF
D/AndroidRuntime( 6089): setted country_code = Poland
D/AndroidRuntime( 6089): setted countryiso_code = PL
D/AndroidRuntime( 6089): setted sales_code = PLS
D/AndroidRuntime( 6089): readGMSProperty: start
D/AndroidRuntime( 6089): readGMSProperty: already setted!!
D/AndroidRuntime( 6089): readGMSProperty: end
D/AndroidRuntime( 6089): addProductProperty: start
D/dalvikvm( 6089): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6089): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6089): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6089): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6089): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6089): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6089): failed to load memtrack module: -2
D/dalvikvm( 6089): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6089): Calling main entry com.android.commands.am.Am
D/SensorService( 2418):   0.2 -0.0 9.9
D/AndroidRuntime( 6089): Shutting down VM
D/dalvikvm( 6089): GC_CONCURRENT freed 99K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 2418): Waited long enough for: ServiceRecord{4375caf0 u0 com.sec.spp.push/.PushClientService}
,D/dalvikvm( 2831): GC_EXPLICIT freed 354K, 24% free 10292K/13528K, paused 4ms+7ms, total 49ms
D/dalvikvm( 5898): GC_EXPLICIT freed 899K, 26% free 10005K/13440K, paused 3ms+9ms, total 48ms
,D/PowerManagerService( 2418): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2578 (0x0)
,I/PowerManagerService( 2418): Nap time...
,D/PowerManagerService( 2418): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2418): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2418): Going to sleep due to screen timeout...
,D/PowerManagerService( 2418): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController( 2418): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
D/DisplayPowerController( 2418): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
D/Sensors ( 2418): LightSensor enable = 0
,D/Sensors ( 2418): LightSensor enableSensor = 0
,D/SensorManager( 2418): unregisterListener ::   
I/DisplayPowerController( 2418): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,I/DisplayPowerController( 2418): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
I/SurfaceFlinger( 1920): id=19 createSurf (720x1280),-1 flag=20004, FlectronBea
I/Sensors ( 2418): HAL:resetDataRates mEnabled=4
,D/SensorManager( 2418): unregisterListener ::   ,
D/DisplayPowerController( 2418): !@ElectronBeam entry,
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
E/SPPClientService( 5055): [b] __InitReply__
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2418): lcd : 0 +
,D/lights  ( 2418): lcd : 0 -
,D/MISC PowerHAL( 2418): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2418): sysfs_write +: /sys/class/input/input1/enabled: 0
V/WindowOrientationListener( 2418): WindowOrientationListener disabled
D/SensorService( 2418): AutoRotationSensor::activate (ident=0x7458c278, enabled=0)
,I/Sensors ( 2418): HAL: batch Dry Run is complete
,D/KeyguardViewMediator( 2578): onScreenTurnedOff(3)
D/PowerManagerService( 2418): blankAllDisplays() is called.
D/PowerManagerService( 2418): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2418): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2418): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2418): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2418): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2418): sysfs_write +: /sys/class/input/input0/enabled: 0
D/SensorManager( 2418): unregisterListener ::   
D/InputDispatcher( 2418): setInputDispatchMode: enabled=0, frozen=0
D/MISC PowerHAL( 2418): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2418): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2418): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SurfaceFlinger( 1920): Screen released, type=0 flinger=0x411e6550
D/PowerManagerService( 2418): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/LockPatternUtils( 2578): isPcwEnable = 10
,D/LockPatternUtils( 2578): isPcwEnable = 10
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(38)
,V/AlarmManager( 2418): waitForAlarm result :4
D/SurfaceControl( 2418): Excessive delay in blankDisplay() while turning screen off: 188ms
,I/libsuspend( 2418): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2418): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2418): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 189ms
D/PowerManagerService( 2418): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2418): [PWL] Off : 0s ago
I/PowerManagerService( 2418): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2418): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2418): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=2418, ws=null) (elapsedTime=195)
I/PowerManagerService( 2418): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 360, Delta = 0
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(4)
,I/DBG_DM  ( 4232): [3.19.140541][Line:400][onPause] 
,I/SQLiteSecureOpenHelper( 3552): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3552): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 2578): setting alarm to turn off keyguard, seq = 2,
,D/Finsky  ( 5076): [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/LightsService( 2418): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2418) 
D/dalvikvm( 5076): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5076): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5076): VFY: replacing opcode 0x62 at 0x0038
,I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 5
D/Sensors ( 2418): LightSensor setDelay = 200000000
,D/Sensors ( 2418): LightSensor setSensorDelay = 200000000
D/Sensors ( 2418): Light sensor flush: not enabled 0
D/Sensors ( 2418): LightSensor enable = 1
,D/Sensors ( 2418): LightSensor enableSensor = 1
,D/LightsService( 2418): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/SensorManager( 2418): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2418): turn on LED for fully charged
D/VibratorService( 2418): JNI vibratorOff()
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2418): ACTION_SCREEN_OFF
D/LightsService( 2418): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2418) 
,D/LightsService( 2418): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=off)
,I/SecExternalDisplayIntents_Java( 2418): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2418): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2418): Bridge Server is not available
,V/GLSActivity( 2837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PersonaManagerService( 2418): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2418): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2578):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2578): makeExpandedInvisible
D/PhoneStatusBarView( 2578): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2578):      ACTION_SCREEN_OFF is finished!!!! 
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/NfcService( 2762): applyRouting return - 2 
,E/NfcService( 2762): callback == null
,D/LockPatternUtils( 2578): isPcwEnable = 10
,D/Sensors ( 2418): LightSensor enable = 0
,D/Sensors ( 2418): LightSensor enableSensor = 0
D/SensorManager( 2418): unregisterListener ::   
,D/lights  ( 2418): led_pattern : 5 +
D/LightsService( 2418): [SvcLED]  onSensorChanged::light value = 24
,D/lights  ( 2418): led_pattern : 5 -
D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SSRMv2:SIOP( 2418): SIOP:: AP = 360, Delta = 0
,D/QuickConnect[1.1][2] ( 4644): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 4644): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4644): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,V/QuickConnect[1.1][2] ( 4644): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42976fa8
V/QuickConnect[1.1][2] ( 4644): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42976fa8
,D/QuickConnect[1.1][2] ( 4644): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4644): BleHelper.stopScan - shouldScanBleBg = false
,I/QuickConnect[1.1][2] ( 4644): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4644): stopLeScan()
,D/QuickConnect[1.1][2] ( 4644): BleHelper.stopScan - call stopLeScan() complete
,D/PowerManagerService( 2418): [PWL] sb release: PowerManagerService.Broadcasts
,I/System.out( 5076): Thread-368(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5076): Thread-368(ApacheHTTPLog):isShipBuild true
,I/System.out( 5076): Thread-368(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/IcingInternalCorpora( 3258): getNumBytesRead when not calculated.
,I/System.out( 5076): Thread-368 calls detatch()
,V/GLSActivity( 2837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5076): Failed write_ctrl(u 68) res=-1 errno=22,
I/qtaguid ( 5076): Untagging socket 68 failed errno=-22,
W/NetworkManagementSocketTagger( 5076): untagSocket(68) failed with errno -22
,I/System.out( 5076): Thread-367 calls detatch(),
,D/dalvikvm( 2418): GC_EXPLICIT freed 656K, 11% free 25203K/28088K, paused 9ms+20ms, total 230ms,
,D/Finsky  ( 5076): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1],
,V/GLSActivity( 2837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 2837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5076): Failed write_ctrl(u 68) res=-1 errno=22
,I/qtaguid ( 5076): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5076): untagSocket(68) failed with errno -22
,I/System.out( 5076): Thread-368 calls detatch()
,D/dalvikvm( 2831): GC_EXPLICIT freed 351K, 24% free 10300K/13528K, paused 4ms+8ms, total 50ms
,D/dalvikvm( 5076): GC_CONCURRENT freed 2102K, 23% free 10471K/13440K, paused 4ms+6ms, total 59ms
,D/dalvikvm( 5898): GC_EXPLICIT freed 901K, 26% free 10014K/13440K, paused 4ms+11ms, total 55ms
,D/dalvikvm( 5076): GC_CONCURRENT freed 770K, 13% free 11748K/13440K, paused 3ms+4ms, total 47ms,
,D/dalvikvm( 5076): WAIT_FOR_CONCURRENT_GC blocked 21ms,
,D/dalvikvm( 5076): GC_FOR_ALLOC freed 935K, 14% free 12604K/14492K, paused 35ms, total 35ms,
,D/dalvikvm( 5076): GC_FOR_ALLOC freed 1008K, 17% free 12908K/15388K, paused 38ms, total 39ms,
,I/ActivityManager( 2418): Waited long enough for: ServiceRecord{43988410 u0 com.sec.android.gallery3d/.app.BackgroundCache},
,D/dalvikvm( 5076): GC_CONCURRENT freed 2060K, 18% free 14265K/17192K, paused 5ms+4ms, total 62ms,
,D/dalvikvm( 5076): WAIT_FOR_CONCURRENT_GC blocked 30ms,
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/dalvikvm( 5898): GC_EXPLICIT freed 905K, 26% free 10013K/13440K, paused 3ms+7ms, total 39ms,
,I/ActivityManager( 2418): Waited long enough for: ServiceRecord{438a33a8 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,D/dalvikvm( 2831): GC_EXPLICIT freed 348K, 24% free 10308K/13528K, paused 4ms+9ms, total 55ms
,I/dalvikvm( 2418): Jit: resizing JitTable from 8192 to 16384
,D/dalvikvm( 2837): GC_EXPLICIT freed 1046K, 21% free 10924K/13736K, paused 5ms+8ms, total 66ms
,V/GLSActivity( 2837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5076): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5076): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5076): untagSocket(68) failed with errno -22
,I/System.out( 5076): Thread-367 calls detatch()
,D/AmoledAdjustTimer( 2418): prevTemp = 304, currTemp = 305, prevStep = 4, currStep = 4
,D/KeyguardViewMediator( 2578): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
V/AlarmManager( 2418): waitForAlarm result :4
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/LockPatternUtils( 2578): isPcwEnable = 10
D/KeyguardViewMediator( 2578): in doKeyguardLocked mIsRollUp false null
D/PersonaManager( 2578): isKioskContainerExistOnDevice
,D/LockPatternUtils( 2578): isPcwEnable = 10
D/LockPatternUtils( 2578): isPcwEnable = 10
,D/KeyguardViewMediator( 2578): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService( 2418): [PWL] Off : 5s ago
,D/Finsky  ( 5076): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 2418): waitForAlarm result :4
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/WearableService( 2733): callingUid 10012, callindPid: 2733
,D/Finsky  ( 5076): [390] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 2733): client connected with version: 8296000
,D/Finsky  ( 5076): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5076): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 5898): GC_EXPLICIT freed 876K, 26% free 10012K/13440K, paused 3ms+10ms, total 54ms
,I/System.out( 5076): Thread-378(HTTPLog):isShipBuild true
,I/System.out( 5076): Thread-378(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/PackageManager( 2418): [MSG] MCS_UNBIND
,I/PackageManager( 2418): calling disconnectService()
,D/PackageManager( 2418): Trying to unbind to DefaultContainerService
,I/ActivityManager( 2418): Killing 5236:com.vlingo.midas/u0a34 (adj 15): empty #43
,D/dalvikvm( 2831): GC_EXPLICIT freed 357K, 24% free 10299K/13528K, paused 4ms+11ms, total 57ms
,D/dalvikvm( 2418): GC_EXPLICIT freed 828K, 11% free 25250K/28088K, paused 9ms+16ms, total 215ms
,D/dalvikvm( 5898): GC_EXPLICIT freed 874K, 26% free 10016K/13440K, paused 3ms+8ms, total 45ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 353K, 24% free 10306K/13528K, paused 4ms+7ms, total 46ms
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager( 2418): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2418): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
V/AlarmManager( 2418): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 5898): WAIT_FOR_CONCURRENT_GC blocked 1ms
,D/dalvikvm( 5898): GC_EXPLICIT freed 874K, 26% free 10014K/13440K, paused 3ms+9ms, total 45ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 345K, 24% free 10312K/13528K, paused 4ms+8ms, total 49ms
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4351, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 350, Delta = -10
,D/dalvikvm( 5898): GC_EXPLICIT freed 872K, 26% free 10013K/13440K, paused 3ms+9ms, total 45ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 356K, 24% free 10316K/13528K, paused 4ms+8ms, total 47ms
,D/dalvikvm( 2418): GC_EXPLICIT freed 531K, 11% free 25228K/28088K, paused 8ms+15ms, total 207ms
,D/dalvikvm( 5898): GC_EXPLICIT freed 871K, 26% free 10011K/13440K, paused 4ms+9ms, total 47ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 350K, 24% free 10326K/13528K, paused 7ms+7ms, total 49ms
,D/dalvikvm( 5898): GC_CONCURRENT freed 1476K, 22% free 10496K/13440K, paused 2ms+9ms, total 37ms
,I/SettingSearch/SearchIntentReceiver( 2831): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2831): LOCALE_CHANGED call search setting db finish!!,
,D/AmoledAdjustTimer( 2418): prevTemp = 305, currTemp = 306, prevStep = 4, currStep = 4,
,I/SettingSearch/SearchIntentReceiver( 2831): InitTitleDBThread start --> mDoingInitTitleDB : true,
,I/SettingSearch/SearchIntentReceiver( 2831): InitTitleDBThread end --> mDoingInitTitleDB : false,
,I/SettingSearch/SearchIntentReceiver( 2831): LOCALE_CHANGED call search setting db finish!!,
,I/PowerManagerService( 2418): [PWL] Off : 15s ago,
,V/AlarmManager( 2418): waitForAlarm result :4,
,D/Headlines( 5426): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5426): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5426): Breath 40901 latestRequest time : 1455009628585 current time : 1455009669486,
,D/Finsky  ( 5076): [380] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5076): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.,
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged,
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 340, Delta = -10
,E/Watchdog( 2418): !@Sync 3,
,D/AmoledAdjustTimer( 2418): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,I/Icing   ( 3258): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music,
,I/Icing   ( 3258): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2418): stay LED for fully charged,
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2418): [PWL] Off : 30s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 340, Delta = 0
,V/AlarmManager( 2418): waitForAlarm result :4
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/FactoryTest( 5154): Not factory mode
,D/FactoryTest( 5154): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 5154): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5154): still no open session command from host, so toast
W/ContextImpl( 5154): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5154): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy( 2418): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService( 2418): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2418): mDVFSHelper.acquire()
,D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,E/MTPRx   ( 5154): started activity for popup
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
I/SQLiteSecureOpenHelper( 3552): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3552): getDatabaseLocked(b,b,pwd)...
,E/SettingsReceiverActivity( 5154): PREF_DONT_ASK_AGAIN : true
,D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
W/InputMethodManagerService( 2418): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@437a5300 attribute=android.view.inputmethod.EditorInfo@436ad238, token = android.os.BinderProxy@43502bc8
,D/SettingsReceiverActivity( 5154): dev.kiessupport is : TRUE
,I/DBG_DM  ( 4232): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4232): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 48
,I/DBG_DM  ( 4232): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4232): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4232): [3.19.140541][Line:418][onResume] Postpone Count : 48
,I/DBG_DM  ( 4232): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4232): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4232): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2418): sendNotification(2) - 4
,I/DBG_DM  ( 4232): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 48
,I/DBG_DM  ( 4232): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4232): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4232): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4232): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4232): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4232): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4232): setTransGradationMode to true
,D/PhoneStatusBar( 2578): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2418): semi p:4232,o:t
I/DBG_DM  ( 4232): [3.19.140541][Line:400][onPause] 
,D/CustomFrequencyManagerService( 2418): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2418): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2418): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/AmoledAdjustTimer( 2418): prevTemp = 306, currTemp = 305, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService( 2418): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  tag : ACTIVITY_RESUME_BOOSTER@8
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = -10,
,D/AmoledAdjustTimer( 2418): prevTemp = 305, currTemp = 306, prevStep = 4, currStep = 4,
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2418): [PWL] Off : 50s ago,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0,
,V/AlarmManager( 2418): waitForAlarm result :4,
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5426): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5426): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5426): Breath 73363 latestRequest time : 1455009628585 current time : 1455009701948
,I/VacuumService( 2733): Vacuum at: now=1455009702188 tag=VacuumService
,E/Watchdog( 2418): !@Sync 4
,I/PhenotypeConfigurator( 2733): Scheduling Phenotype for one-off execution 929 seconds from now (1455009702703)
,D/dalvikvm( 2733): GC_FOR_ALLOC freed 1308K, 20% free 11567K/14436K, paused 48ms, total 48ms
,D/GetConfigurationSnapshotOperation( 2733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2733): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2733): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2733): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2733): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 2418): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 2733): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2733): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2733): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 2733): Thread-111(HTTPLog):isShipBuild true
,I/System.out( 2733): Thread-111(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/LocationManagerService( 2418): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 2733): GC_CONCURRENT freed 1386K, 17% free 12116K/14516K, paused 5ms+8ms, total 56ms
,D/LocationManagerService( 2418): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2418): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/AmoledAdjustTimer( 2418): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2418): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,V/AlarmManager( 2418): waitForAlarm result :8,
,D/Headlines( 5426): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5426): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5426): Breath 90027 latestRequest time : 1455009628585 current time : 1455009718612,
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2418): waitForAlarm result :8,
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2418): [PWL] Off : 75s ago,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0,
,E/Watchdog( 2418): !@Sync 5,
,D/AmoledAdjustTimer( 2418): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged,
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2418): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,V/AlarmManager( 2418): waitForAlarm result :8,
,D/Headlines( 5426): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5426): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5426): Breath 120029 latestRequest time : 1455009628585 current time : 1455009748614
,D/Headlines( 5426): stop ,
,D/Headlines( 5426): Breath.onDestroy : ,
I/ActivityManager( 2418): Killing 5358:com.policydm/1000 (adj 15): empty #43
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 306, currTemp = 305, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2418): [PWL] Off : 105s ago,
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0,
,E/Watchdog( 2418): !@Sync 6,
,D/AmoledAdjustTimer( 2418): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4,
,I/ClearcutLoggerApiImpl( 2837): disconnect managed GoogleApiClient,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2418): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2418): waitForAlarm result :8,
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2418): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2418): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2418): !@Sync 7,
,D/AmoledAdjustTimer( 2418): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4,
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2418): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2418): !@Sync 8,
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2418): [PWL] Off : 180s ago,
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2418): stay LED for fully charged,
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0,
,D/dalvikvm( 2418): GC_CONCURRENT freed 3741K, 16% free 25346K/30076K, paused 11ms+13ms, total 194ms,
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2418): waitForAlarm result :8,
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2418): !@Sync 9,
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2418): [PWL] Off : 225s ago
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2418): initializing...,
I/TLC_TIMA_PKM_initialize( 2418): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2418): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2418): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2418): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2418): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2418): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2418): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2418): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2418): device_id = 0x0
I/TZ: mc_tlc_communication( 2418): tlc_open() was called,
,I/TZ: mc_tlc_communication( 2418): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2418): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2418): Opening the session
,I/TZ: mc_tlc_communication( 2418): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2418): Trustlet response is completed,
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2418): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2418): waitForAlarm result :8,
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,V/AlarmManager( 2418): waitForAlarm result :4,
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 6994): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 6994):  
,I/SELinux ( 6994): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6994):  
I/SELinux ( 6994):  
,I/SELinux ( 6994): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6994): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6994): >>>>> Normal User
,E/dalvikvm( 6994): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 6994): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 6994): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 6994): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 6994): Added TimaKesytore provider,
,D/dalvikvm( 6994): GC_CONCURRENT freed 3000K, 29% free 9571K/13440K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 6994): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2418): Killing 5397:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2418): !@Sync 11,
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2418): [PWL] Off : 275s ago
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 12
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :4
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5055): [b] __PingReply__
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 13
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2418): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 14
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 15
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2418): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 16
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 17
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2418): [PWL] Off : 455s ago
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,D/dalvikvm( 2418): GC_FOR_ALLOC freed 2671K, 17% free 25311K/30268K, paused 209ms, total 209ms
D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2418): !@Sync 18
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 19
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2418): [PWL] Off : 525s ago
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2418): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 21
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/GAV2    ( 5170): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5170): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 22
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 600s ago
,V/AlarmManager( 2418): waitForAlarm result :8
,I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 5
,D/LightsService( 2418): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/Sensors ( 2418): LightSensor setDelay = 200000000
D/Sensors ( 2418): LightSensor setSensorDelay = 200000000
D/Sensors ( 2418): Light sensor flush: not enabled 0
D/Sensors ( 2418): LightSensor enable = 1
D/Sensors ( 2418): LightSensor enableSensor = 1
D/SensorManager( 2418): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2418): LightSensor enable = 0
,D/Sensors ( 2418): LightSensor enableSensor = 0
,D/LightsService( 2418): [SvcLED]  onSensorChanged::light value = 29
,D/SensorManager( 2418): unregisterListener ::   
D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2418): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2418): <AppSync3 Whitelist>
,V/AlarmManager( 2418): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 3697): GC_CONCURRENT freed 2891K, 28% free 9727K/13488K, paused 14ms+3ms, total 69ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 23
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 24
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 7934
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 7939
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 7941
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 7942
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 7944
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 7946
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 7947
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 7949
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 7951
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 680s ago
,E/Watchdog( 2418): !@Sync 25
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 26
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 27
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/dalvikvm( 2418): GC_FOR_ALLOC freed 2666K, 17% free 25315K/30268K, paused 203ms, total 203ms
D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2418): [PWL] Off : 765s ago
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 28
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 29
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2418): !@Sync 30
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2418): [PWL] Off : 855s ago
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 31
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2418): waitForAlarm result :4
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :4
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/ConnectivityService( 2418): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
,D/STATUSBAR-NetworkController( 2578): updateDataNetType()
,D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 32
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,E/SPPClientService( 5055): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 33
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 950s ago
,E/Watchdog( 2418): !@Sync 34
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 35
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 36
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 37
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 38
,D/dalvikvm( 2418): GC_FOR_ALLOC freed 2731K, 17% free 25335K/30268K, paused 205ms, total 205ms
D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 39
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 10
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2418): !@Sync 40
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2418): [PWL] Off : 1155s ago
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 41
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 42
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :4
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3258): Aggregate from 1455008921334 (log), 1455008921334 (data)
,D/dalvikvm( 3258): GC_CONCURRENT freed 1795K, 19% free 12086K/14748K, paused 5ms+6ms, total 60ms
,W/SQLiteConnectionPool( 3258): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/SPPClientService( 5055): [b] __PingReply__
,V/AlarmManager( 2418): waitForAlarm result :8
,D/LightsService( 2418): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 5
D/Sensors ( 2418): LightSensor setDelay = 200000000
D/Sensors ( 2418): LightSensor setSensorDelay = 200000000
D/Sensors ( 2418): Light sensor flush: not enabled 0
D/Sensors ( 2418): LightSensor enable = 1
D/Sensors ( 2418): LightSensor enableSensor = 1
D/SensorManager( 2418): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2418): LightSensor enable = 0
,D/Sensors ( 2418): LightSensor enableSensor = 0
,D/SensorManager( 2418): unregisterListener ::   
D/LightsService( 2418): [SvcLED]  onSensorChanged::light value = 20
D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2418): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2418): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2418): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1200000ms)
```
