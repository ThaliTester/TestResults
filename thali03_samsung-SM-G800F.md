#### Test 586983493da948e_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
I/ActivityManager( 2423): Killing 5195:com.vlingo.midas/u0a34 (adj 15): empty #43
,--------- beginning of /dev/log/main
D/AndroidRuntime( 6079): 
D/AndroidRuntime( 6079): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6079): CheckJNI is OFF
D/AndroidRuntime( 6079): setted country_code = Poland
D/AndroidRuntime( 6079): setted countryiso_code = PL
D/AndroidRuntime( 6079): setted sales_code = PLS
D/AndroidRuntime( 6079): readGMSProperty: start
D/AndroidRuntime( 6079): readGMSProperty: already setted!!
D/AndroidRuntime( 6079): readGMSProperty: end
D/AndroidRuntime( 6079): addProductProperty: start
D/dalvikvm( 6079): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6079): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6079): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6079): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6079): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6079): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6079): failed to load memtrack module: -2
D/dalvikvm( 6079): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6079): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 6079): Shutting down VM
D/dalvikvm( 6079): GC_CONCURRENT freed 98K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
,D/dalvikvm( 5876): GC_EXPLICIT freed 901K, 28% free 10000K/13828K, paused 3ms+10ms, total 46ms
D/dalvikvm( 2833): GC_EXPLICIT freed 347K, 27% free 10291K/13912K, paused 5ms+7ms, total 48ms
,E/SPPClientService( 5051): [b] __InitReply__,
,V/AlarmManager( 2423): waitForAlarm result :4,
,D/Finsky  ( 5073): [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
,V/AlarmManager( 2423): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/dalvikvm( 5073): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5073): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5073): VFY: replacing opcode 0x62 at 0x0038
D/SensorService( 2423):   0.1 -0.0 9.9
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 2851): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
,W/dalvikvm( 2851): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 2851): VFY: replacing opcode 0x6e at 0x0046
,I/System.out( 5073): Thread-366(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5073): Thread-366(ApacheHTTPLog):isShipBuild true
,I/System.out( 5073): Thread-366(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/PowerManagerService( 2423): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2583 (0x0)
I/PowerManagerService( 2423): Nap time...
,D/PowerManagerService( 2423): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2423): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2423): Going to sleep due to screen timeout...
D/PowerManagerService( 2423): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2423): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/DisplayPowerController( 2423): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,I/DisplayPowerController( 2423): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
D/Sensors ( 2423): LightSensor enable = 0
,D/Sensors ( 2423): LightSensor enableSensor = 0
,I/SurfaceFlinger( 1922): id=16 createSurf (720x1280),-1 flag=20004, FlectronBea
,D/SensorManager( 2423): unregisterListener ::   
,D/DisplayPowerController( 2423): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,I/Sensors ( 2423): HAL:resetDataRates mEnabled=4
D/DisplayPowerController( 2423): !@ElectronBeam entry
,D/SensorManager( 2423): unregisterListener ::   
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3369): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/IcingInternalCorpora( 3145): getNumBytesRead when not calculated.
,D/lights  ( 2423): lcd : 0 +
,D/lights  ( 2423): lcd : 0 -
D/MISC PowerHAL( 2423): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2423): sysfs_write +: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2423): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2423): miscpower_set_interactive: /sys/class/input/input0/enabled
D/PowerManagerService( 2423): blankAllDisplays() is called.
D/PowerManagerService( 2423): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2423): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2423): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2423): sysfs_write +: /sys/class/input/input0/enabled: 0
V/WindowOrientationListener( 2423): WindowOrientationListener disabled
D/SensorService( 2423): AutoRotationSensor::activate (ident=0x887254e8, enabled=0)
I/Sensors ( 2423): HAL: batch Dry Run is complete
D/KeyguardViewMediator( 2583): onScreenTurnedOff(3)
D/MISC PowerHAL( 2423): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2423): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2423): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2423): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2423): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2423): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2423): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2423): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2423): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2423): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/SEC PowerHAL( 2423): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/PowerManagerService( 2423): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SurfaceFlinger( 1922): Screen released, type=0 flinger=0x41bf5550
D/SensorManager( 2423): unregisterListener ::   
D/InputDispatcher( 2423): setInputDispatchMode: enabled=0, frozen=0
,D/Launcher.HomeView( 2788): onPause
,D/LockPatternUtils( 2583): isPcwEnable = 10
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/LockPatternUtils( 2583): isPcwEnable = 10
D/StatusBarManagerService( 2423): tr p:2788,o:f
,D/KeyguardViewMediator( 2583): setting alarm to turn off keyguard, seq = 2
,D/LightsService( 2423): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2423) 
,I/SensorManagerA( 2423): getReportingMode :: sensor.mType = 5
D/Sensors ( 2423): LightSensor setDelay = 200000000
D/Sensors ( 2423): LightSensor setSensorDelay = 200000000
,D/Sensors ( 2423): Light sensor flush: not enabled 0
,D/LightsService( 2423): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On,
D/Sensors ( 2423): LightSensor enable = 1
D/Sensors ( 2423): LightSensor enableSensor = 1
,D/SensorManager( 2423): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/BatteryService( 2423): turn on LED for fully charged
,D/Launcher.HomeView( 2788): onStop,
D/VibratorService( 2423): JNI vibratorOff()
,I/display ( 1922): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(36),
,I/WifiTrafficPoller( 2423): evaluateTrafficStatsPolling,
,D/STATUSBAR-NotificationService( 2423): ACTION_SCREEN_OFF,
D/LightsService( 2423): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2423) 
,D/LightsService( 2423): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off,
I/System.out( 5073): Thread-366 calls detatch()
I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2423): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2423): intent received android.intent.action.SCREEN_OFF,
,D/IpRemoteDisplayController( 2423): Bridge Server is not available,
,D/PersonaManagerService( 2423): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2423): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2583): makeExpandedInvisible
D/PhoneStatusBarView( 2583): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2766): applyRouting return - 2 
,E/NfcService( 2766): callback == null
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/LockPatternUtils( 2583): isPcwEnable = 10
,D/SurfaceControl( 2423): Excessive delay in blankDisplay() while turning screen off: 221ms
I/libsuspend( 2423): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2423): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2423): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 223ms
D/PowerManagerService( 2423): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2423): [PWL] Off : 0s ago
I/PowerManagerService( 2423): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 360, Delta = 0
,D/QuickConnect[1.1][2] ( 4642): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 4642): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4642): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422a1308
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422a1308
D/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4642): stopLeScan()
,D/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - call stopLeScan() complete
,D/Sensors ( 2423): LightSensor enable = 0
,D/Sensors ( 2423): LightSensor enableSensor = 0
D/SensorManager( 2423): unregisterListener ::   
,D/lights  ( 2423): led_pattern : 5 +
D/LightsService( 2423): [SvcLED]  onSensorChanged::light value = 0
,D/lights  ( 2423): led_pattern : 5 -
D/LightsService( 2423): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PowerManagerService( 2423): [PWL] sb release: PowerManagerService.Broadcasts
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5073): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5073): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5073): untagSocket(68) failed with errno -22
,I/System.out( 5073): Thread-367 calls detatch()
,D/Finsky  ( 5073): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5073): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5073): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5073): untagSocket(68) failed with errno -22
,I/System.out( 5073): Thread-366 calls detatch()
,D/dalvikvm( 2423): GC_EXPLICIT freed 565K, 14% free 24366K/28028K, paused 9ms+17ms, total 225ms
,D/dalvikvm( 5876): GC_EXPLICIT freed 895K, 28% free 10016K/13828K, paused 3ms+7ms, total 39ms
,D/dalvikvm( 5073): GC_CONCURRENT freed 1970K, 24% free 10670K/13908K, paused 3ms+7ms, total 45ms
,D/dalvikvm( 5073): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2833): GC_EXPLICIT freed 359K, 27% free 10289K/13912K, paused 3ms+7ms, total 42ms
,D/dalvikvm( 5073): GC_CONCURRENT freed 694K, 15% free 12017K/13988K, paused 3ms+3ms, total 62ms
,D/dalvikvm( 5073): WAIT_FOR_CONCURRENT_GC blocked 42ms
,D/dalvikvm( 5073): GC_FOR_ALLOC freed 1352K, 20% free 12389K/15320K, paused 40ms, total 40ms
,D/dalvikvm( 5073): GC_FOR_ALLOC freed 1491K, 22% free 13187K/16728K, paused 37ms, total 38ms
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5876): GC_EXPLICIT freed 906K, 28% free 10014K/13828K, paused 3ms+10ms, total 47ms
,D/dalvikvm( 2833): GC_EXPLICIT freed 355K, 27% free 10291K/13912K, paused 5ms+9ms, total 56ms
,I/ActivityManager( 2423): Waited long enough for: ServiceRecord{430cfa68 u0 com.sec.android.gallery3d/.app.BackgroundCache}
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5073): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5073): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5073): untagSocket(68) failed with errno -22
,I/System.out( 5073): Thread-367 calls detatch()
,D/AmoledAdjustTimer( 2423): prevTemp = 302, currTemp = 303, prevStep = 4, currStep = 4
,I/dalvikvm( 2423): Jit: resizing JitTable from 8192 to 16384
D/Finsky  ( 5073): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager( 2423): waitForAlarm result :4
V/AlarmManager( 2423): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/WearableService( 2737): callingUid 10012, callindPid: 2737
D/Finsky  ( 5073): [390] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/DeviceConnectionService( 2737): client connected with version: 8296000
D/Finsky  ( 5073): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5073): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/System.out( 5073): Thread-377(HTTPLog):isShipBuild true
I/System.out( 5073): Thread-377(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/dalvikvm( 5876): GC_EXPLICIT freed 885K, 28% free 10005K/13828K, paused 4ms+9ms, total 47ms
,V/AlarmManager( 2423): waitForAlarm result :4,
,D/KeyguardViewMediator( 2583): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2,
,V/AlarmManager( 2423): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
D/LockPatternUtils( 2583): isPcwEnable = 10
D/KeyguardViewMediator( 2583): in doKeyguardLocked mIsRollUp false null
,D/PersonaManager( 2583): isKioskContainerExistOnDevice
,D/LockPatternUtils( 2583): isPcwEnable = 10,
D/LockPatternUtils( 2583): isPcwEnable = 10
,D/KeyguardViewMediator( 2583): doKeyguard: not showing because lockscreen is off,
,D/dalvikvm( 2833): GC_EXPLICIT freed 341K, 26% free 10298K/13912K, paused 4ms+8ms, total 46ms
,I/PowerManagerService( 2423): [PWL] Off : 5s ago
,D/PackageManager( 2423): [MSG] MCS_UNBIND
,I/PackageManager( 2423): calling disconnectService()
,D/PackageManager( 2423): Trying to unbind to DefaultContainerService
,I/ActivityManager( 2423): Killing 5317:com.policydm/1000 (adj 15): empty #43
,V/AlarmManager( 2423): waitForAlarm result :8,
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK,
V/AlarmManager( 2423): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2423): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
V/AlarmManager( 2423): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 2423): GC_EXPLICIT freed 972K, 13% free 24412K/28028K, paused 10ms+16ms, total 244ms,
,D/dalvikvm( 5876): GC_EXPLICIT freed 874K, 28% free 10010K/13828K, paused 3ms+9ms, total 45ms,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/dalvikvm( 2833): GC_EXPLICIT freed 350K, 26% free 10305K/13912K, paused 6ms+8ms, total 51ms,
,D/dalvikvm( 5876): GC_EXPLICIT freed 873K, 28% free 10008K/13828K, paused 3ms+8ms, total 49ms,
,D/dalvikvm( 2833): GC_EXPLICIT freed 346K, 26% free 10309K/13912K, paused 4ms+7ms, total 46ms,
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2423): stay LED for fully charged,
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3369): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 350, Delta = -10
,D/dalvikvm( 5876): GC_EXPLICIT freed 871K, 28% free 10008K/13828K, paused 3ms+9ms, total 44ms
,D/dalvikvm( 2833): GC_EXPLICIT freed 354K, 26% free 10316K/13912K, paused 5ms+7ms, total 56ms
,D/dalvikvm( 2423): GC_EXPLICIT freed 351K, 13% free 24401K/28028K, paused 10ms+16ms, total 214ms
,D/dalvikvm( 5876): GC_EXPLICIT freed 872K, 28% free 10006K/13828K, paused 3ms+9ms, total 45ms
,D/dalvikvm( 2833): GC_EXPLICIT freed 355K, 26% free 10329K/13912K, paused 4ms+7ms, total 46ms
,D/AmoledAdjustTimer( 2423): prevTemp = 303, currTemp = 304, prevStep = 4, currStep = 4
,D/dalvikvm( 5876): GC_CONCURRENT freed 1492K, 25% free 10502K/13828K, paused 1ms+11ms, total 46ms
,I/SettingSearch/SearchIntentReceiver( 2833): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2833): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 2833): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 2833): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2833): LOCALE_CHANGED call search setting db finish!!
,I/PowerManagerService( 2423): [PWL] Off : 15s ago,
,V/AlarmManager( 2423): waitForAlarm result :4,
,V/AlarmManager( 2423): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
D/Headlines( 5381): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5381): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5381): Breath 41497 latestRequest time : 1454986290089 current time : 1454986331586,
,D/Finsky  ( 5073): [379] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5073): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 340, Delta = -10,
,E/Watchdog( 2423): !@Sync 3,
,D/AmoledAdjustTimer( 2423): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,I/Icing   ( 3145): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music,
,I/Icing   ( 3145): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2423): mCoverManager.getCoverState() : true
,D/BatteryService( 2423): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3369): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2423): [PWL] Off : 30s ago,
,V/AlarmManager( 2423): waitForAlarm result :4,
,V/AlarmManager( 2423): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 330, Delta = -10,
,D/FactoryTest( 5148): Not factory mode,
,D/FactoryTest( 5148): Not factory mode. isFactoryMode() returend false,
D/MTPRx   ( 5148): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5148): still no open session command from host, so toast,
W/ContextImpl( 5148): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5148): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy( 2423): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,D/CustomFrequencyManagerService( 2423): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2423  pkgName : ACTIVITY_RESUME_BOOSTER@4,
,I/SurfaceFlinger( 1922): id=17 createSurf (16x16),-1 flag=20004, EimLayer
,I/SurfaceFlinger( 1922): id=18 createSurf (16x16),-1 flag=20004, EimLayer,
W/ActivityManager( 2423): mDVFSHelper.acquire()
,D/PointerIcon( 2423): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 2423): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2423): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2423): setHoveringSpenCustomIcon IconType is same.1
,E/MTPRx   ( 5148): started activity for popup
,I/SQLiteSecureOpenHelper( 3543): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3543): getDatabaseLocked(b,b,pwd)...,
,E/SettingsReceiverActivity( 5148): PREF_DONT_ASK_AGAIN : true,
D/PointerIcon( 2423): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2423): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2423): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2423): setHoveringSpenCustomIcon IconType is same.1,
D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false,
D/StatusBarManagerService( 2423): tr p:2788,o:f
D/StatusBarManagerService( 2423): semi p:2788,o:f
,W/InputMethodManagerService( 2423): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@42e46a28 attribute=android.view.inputmethod.EditorInfo@43000750, token = android.os.BinderProxy@42e03be8
,D/SettingsReceiverActivity( 5148): dev.kiessupport is : TRUE
,D/CustomFrequencyManagerService( 2423): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2423  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2423): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2423): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2423  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/AmoledAdjustTimer( 2423): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService( 2423): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2423  tag : ACTIVITY_RESUME_BOOSTER@8,
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2423): stay LED for fully charged
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3369): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 330, Delta = 0,
,I/SurfaceFlinger( 1922): id=18 Removed EimLayer (5/10),
I/SurfaceFlinger( 1922): id=18 Removed EimLayer (-2/10)
,I/SurfaceFlinger( 1922): id=17 Removed EimLayer (4/9)
,I/SurfaceFlinger( 1922): id=17 Removed EimLayer (-2/9),
,D/AmoledAdjustTimer( 2423): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2423): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2423): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3369): Disconnected process message: 10
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,I/PowerManagerService( 2423): [PWL] Off : 50s ago,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 330, Delta = 0,
,V/AlarmManager( 2423): waitForAlarm result :4,
,V/AlarmManager( 2423): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5381): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5381): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5381): Breath 74805 latestRequest time : 1454986290089 current time : 1454986364894,
,I/VacuumService( 2737): Vacuum at: now=1454986365139 tag=VacuumService,
,D/dalvikvm( 2851): GC_EXPLICIT freed 1729K, 23% free 10815K/13884K, paused 7ms+8ms, total 63ms,
,E/Watchdog( 2423): !@Sync 4,
,I/PhenotypeConfigurator( 2737): Scheduling Phenotype for one-off execution 12676 seconds from now (1454986365685),
,D/GetConfigurationSnapshotOperation( 2737): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2737): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader,
,W/dalvikvm( 2737): VFY: unable to find class referenced in signature (Landroid/net/Network;),
,W/dalvikvm( 2737): VFY: unable to find class referenced in signature (Landroid/net/Network;),
,W/dalvikvm( 2737): VFY: unable to find class referenced in signature (Landroid/net/Network;),
I/dalvikvm( 2737): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2737): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2737): VFY: replacing opcode 0x6e at 0x00bb,
,I/GoogleURLConnFactory( 2737): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 2423): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 2737): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2737): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2737): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 2737): Thread-110(HTTPLog):isShipBuild true
,I/System.out( 2737): Thread-110(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 2737): GC_FOR_ALLOC freed 1443K, 21% free 11682K/14768K, paused 49ms, total 50ms
,D/LocationManagerService( 2423): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/AmoledAdjustTimer( 2423): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,V/AlarmManager( 2423): waitForAlarm result :8,
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,V/AlarmManager( 2423): waitForAlarm result :8,
,D/Headlines( 5381): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5381): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5381): Breath 90048 latestRequest time : 1454986290089 current time : 1454986380137,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2423): stay LED for fully charged,
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3369): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 330, Delta = 0,
,W/ProcessCpuTracker( 2423): Skipping unknown process pid 6402,
W/ProcessCpuTracker( 2423): Skipping unknown process pid 6407
,W/ProcessCpuTracker( 2423): Skipping unknown process pid 6415,
,W/ProcessCpuTracker( 2423): Skipping unknown process pid 6418
,D/AmoledAdjustTimer( 2423): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2423): [PWL] Off : 75s ago,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = -10,
,E/Watchdog( 2423): !@Sync 5,
,D/AmoledAdjustTimer( 2423): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2423): stay LED for fully charged,
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3369): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,V/AlarmManager( 2423): waitForAlarm result :8,
,D/Headlines( 5381): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5381): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5381): Breath 120025 latestRequest time : 1454986290089 current time : 1454986410114
,D/Headlines( 5381): stop ,
,D/Headlines( 5381): Breath.onDestroy : ,
I/ActivityManager( 2423): Killing 5355:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2423): [PWL] Off : 105s ago,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2423): stay LED for fully charged
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
D/UiModeManager( 2423): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3369): Disconnected process message: 10
D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2423): !@Sync 6,
,D/AmoledAdjustTimer( 2423): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,V/AlarmManager( 2423): waitForAlarm result :8,
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2423): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2423): mCoverManager.getCoverState() : true
,D/BatteryService( 2423): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3369): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2423): !@Sync 7,
,D/AmoledAdjustTimer( 2423): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2423): stay LED for fully charged,
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3369): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2423): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2423): !@Sync 8,
,D/AmoledAdjustTimer( 2423): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2423): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,V/AlarmManager( 2423): waitForAlarm result :8,
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2423): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
D/UiModeManager( 2423): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3369): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2423): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2423): !@Sync 9,
,D/AmoledAdjustTimer( 2423): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2423): [PWL] Off : 225s ago,
,D/TimaService( 2423): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2423): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2423): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2423): initializing...,
I/TLC_TIMA_PKM_initialize( 2423): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2423): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2423): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2423): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2423): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2423): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2423): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2423): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2423): device_id = 0x0
I/TZ: mc_tlc_communication( 2423): tlc_open() was called
,I/TZ: mc_tlc_communication( 2423): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2423): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2423): Opening the session
,I/TZ: mc_tlc_communication( 2423): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2423): Trustlet response is completed,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2423): stay LED for fully charged
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3369): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2423): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2423): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2423): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2423): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2423): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2423): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,V/AlarmManager( 2423): waitForAlarm result :8,
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 2423): GC_CONCURRENT freed 3466K, 17% free 24606K/29464K, paused 10ms+15ms, total 199ms,
,D/dalvikvm( 2423): WAIT_FOR_CONCURRENT_GC blocked 189ms,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,V/AlarmManager( 2423): waitForAlarm result :4,
,V/AlarmManager( 2423): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 6974): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 6974):  
,I/SELinux ( 6974): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6974):  
I/SELinux ( 6974):  
,I/SELinux ( 6974): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 6974): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6974): >>>>> Normal User
,E/dalvikvm( 6974): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 6974): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 6974): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 6974): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6974): Added TimaKesytore provider,
,D/dalvikvm( 6974): GC_CONCURRENT freed 3000K, 31% free 9566K/13840K, paused 3ms+2ms, total 28ms,
,D/dalvikvm( 6974): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2423): Killing 5393:com.google.android.apps.magazines/u0a115 (adj 15): empty #43,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2423): !@Sync 11,
,D/AmoledAdjustTimer( 2423): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2423): [PWL] Off : 275s ago,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2423): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3369): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2423): !@Sync 12,
,D/AmoledAdjustTimer( 2423): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4,
,V/AlarmManager( 2423): waitForAlarm result :4,
,V/AlarmManager( 2423): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,E/SPPClientService( 5051): [b] __PingReply__,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,V/AlarmManager( 2423): waitForAlarm result :8,
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2423): !@Sync 13,
,D/AmoledAdjustTimer( 2423): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2423): [PWL] Off : 330s ago,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2423): mCoverManager.getCoverState() : true
,D/BatteryService( 2423): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3369): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2423): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2423): !@Sync 14,
,D/AmoledAdjustTimer( 2423): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,V/AlarmManager( 2423): waitForAlarm result :8,
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2423): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = -10
,E/Watchdog( 2423): !@Sync 15
,D/AmoledAdjustTimer( 2423): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2423): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2423): stay LED for fully charged
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3369): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2423): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2423): !@Sync 16
,D/AmoledAdjustTimer( 2423): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :8
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2423): !@Sync 17
,D/AmoledAdjustTimer( 2423): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2423): [PWL] Off : 455s ago
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2423): !@Sync 18
,D/AmoledAdjustTimer( 2423): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2423): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3369): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2423): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :8
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 19
,D/dalvikvm( 2423): GC_FOR_ALLOC freed 2511K, 18% free 24475K/29736K, paused 199ms, total 199ms
D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/TimaService( 2423): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2423): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2423): TimaServiceHandler.handleMessage what =1
,I/PowerManagerService( 2423): [PWL] Off : 525s ago
I/PowerManagerService( 2423): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2423): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2423): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2423, ws=null) (elapsedTime=26)
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2423): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2423): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2423): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2423): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2423): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :8
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 21
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/GAV2    ( 5164): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5164): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true
,D/BatteryService( 2423): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3369): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2423): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 22
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2423): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2423): stay LED for fully charged
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3369): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2423): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :8
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2423): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2423): <AppSync3 Whitelist>
,V/AlarmManager( 2423): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true
,D/BatteryService( 2423): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3369): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2423): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 23
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 24
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :8
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2423): [PWL] Off : 680s ago
,E/Watchdog( 2423): !@Sync 25
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :4
,I/SensorManagerA( 2423): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2423): LightSensor setDelay = 200000000
,D/Sensors ( 2423): LightSensor setSensorDelay = 200000000
,D/LightsService( 2423): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/Sensors ( 2423): Light sensor flush: not enabled 0
D/Sensors ( 2423): LightSensor enable = 1
,D/Sensors ( 2423): LightSensor enableSensor = 1
,D/SensorManager( 2423): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2423): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3145): Aggregate from 1454985209119 (log), 1454985209119 (data)
,D/Sensors ( 2423): LightSensor enable = 0
,D/Sensors ( 2423): LightSensor enableSensor = 0
,D/SensorManager( 2423): unregisterListener ::   
D/LightsService( 2423): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2423): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 26
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2423): stay LED for fully charged
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3369): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2423): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :8
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 3805): GC_CONCURRENT freed 2898K, 31% free 9723K/13892K, paused 2ms+3ms, total 36ms
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 27
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2423): [PWL] Off : 765s ago
,E/Watchdog( 2423): !@Sync 28
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :8
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2423): GC_FOR_ALLOC freed 2464K, 18% free 24514K/29736K, paused 177ms, total 177ms
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 29
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService( 2423): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2423): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2423): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2423): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2423): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2423): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2423): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2423): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :8
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2423): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3369): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2423): [PWL] Off : 855s ago
,E/Watchdog( 2423): !@Sync 31
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :4
,V/AlarmManager( 2423): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 8317): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8317):  
,I/SELinux ( 8317): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8317):  
I/SELinux ( 8317):  
,I/SELinux ( 8317): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8317): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 8317): >>>>> Normal User
,E/dalvikvm( 8317): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux ( 8317): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 8317): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8317): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8317): Added TimaKesytore provider
,D/dalvikvm( 8317): GC_CONCURRENT freed 2997K, 31% free 9568K/13836K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 8317): WAIT_FOR_CONCURRENT_GC blocked 22ms
,E/dalvikvm( 8317): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
,W/dalvikvm( 8317): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 8317): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 8317): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 8317): Link of class 'Lal;' failed
E/dalvikvm( 8317): Could not find class 'al', referenced from method b.a
W/dalvikvm( 8317): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 8317): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 8317): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 8317): Link of class 'Lan;' failed
E/dalvikvm( 8317): Could not find class 'an', referenced from method b.a
W/dalvikvm( 8317): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 8317): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm( 8317): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 8317): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 8317): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 8317): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 8317): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 8317): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 8317): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 8317): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 8317): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 8317): VFY: replacing opcode 0x23 at 0x0005
,D/dalvikvm( 8317): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
W/dalvikvm( 8317): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 8317): Link of class 'Lal;' failed
,D/dalvikvm( 8317): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm( 8317): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 8317): Link of class 'Lan;' failed
,D/dalvikvm( 8317): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm( 8317): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a,
,I/dalvikvm( 8317): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a,
W/dalvikvm( 8317): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 8317): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 8317): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 8317): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 8317): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 8317): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 8317): VFY: unable to resolve instance field 36
,D/dalvikvm( 8317): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 8317): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 8317): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 8317): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 8317): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 8317): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 8317): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4235d828
,D/dalvikvm( 8317): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4235d828
,D/dalvikvm( 8317): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4235d828, skipping init
,D/dalvikvm( 8317): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4235d828
,D/dalvikvm( 8317): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4235d828
,V/JNIHelp ( 8317): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/dalvikvm( 8317): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 8317): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 8317): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 8317): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4235d828
,D/dalvikvm( 8317): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x4235d828
,D/dalvikvm( 8317): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4235d828
,D/dalvikvm( 8317): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4235d828
,I/dalvikvm( 8317): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 8317): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 8317): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm( 8317): DexOpt: --- BEGIN 'ads385773146.jar' (bootstrap=0) ---
,I/ProviderInstaller( 8317): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm( 8345): DexOpt: load 5ms, verify+opt 14ms, 194052 bytes
,D/dalvikvm( 8317): DexOpt: --- END 'ads385773146.jar' (success) ---
,D/dalvikvm( 8317): DEX prep '/data/data/com.google.android.youtube/cache/ads385773146.jar': unzip in 1ms, rewrite 103ms
,E/YouTube MDX( 8317): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm( 8317): GC_CONCURRENT freed 1878K, 23% free 10694K/13836K, paused 4ms+9ms, total 55ms
,D/ConnectivityService( 2423): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2583): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2583): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2583): updateDataNetType()
,D/STATUSBAR-NetworkController( 2583): NoService, mRoamingIconId = 0
,E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 8317): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
,I/dalvikvm( 8317): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
,W/dalvikvm( 8317): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 8317): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 8317): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 8317): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 8317): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 8317): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
,W/dalvikvm( 8317): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 8317): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 8317): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 8317): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 8317): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 8317): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 8317): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 8317): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 8317): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm( 8317): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 8317): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 8317): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm( 8317): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 8317): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 8317): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/dalvikvm( 8317): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 8317): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 8317): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
,W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 8317): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
D/dalvikvm( 8317): VFY: replacing opcode 0x6e at 0x0002
W/ContextImpl( 8317): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 8317): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 8317): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
,W/InstanceID/Rpc( 8317): Found 10012
,E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 8317): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/System.out( 8317): Thread-563(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 8317): Thread-563(ApacheHTTPLog):isShipBuild true
,I/System.out( 8317): Thread-563(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 8317): Thread-563 calls detatch()
,D/dalvikvm( 8317): GC_CONCURRENT freed 1353K, 19% free 11345K/13936K, paused 5ms+6ms, total 49ms
,I/System.out( 8317): Thread-554 calls detatch()
,I/ActivityManager( 2423): Killing 5397:com.samsung.android.magazine.service/u0a110 (adj 15): empty #43
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true
,D/BatteryService( 2423): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3369): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 32
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :8
,E/SPPClientService( 5051): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :8
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true
,D/BatteryService( 2423): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3369): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2423): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 33
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2423): [PWL] Off : 950s ago
,E/Watchdog( 2423): !@Sync 34
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :8
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 35
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 36
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :8
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 37
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2423): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 38
,D/dalvikvm( 2423): GC_FOR_ALLOC freed 3125K, 18% free 24511K/29736K, paused 206ms, total 206ms
D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2423): stay LED for fully charged
,D/UiModeManager( 2423): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3369): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3369): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2423): waitForAlarm result :8
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2788): GC_CONCURRENT freed 6148K, 36% free 19995K/31164K, paused 11ms+7ms, total 82ms
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 39
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/TimaService( 2423): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2423): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2423): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2423): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2423): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2423): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2423): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2423): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :8
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2423): [PWL] Off : 1155s ago
,E/Watchdog( 2423): !@Sync 41
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2423): !@Sync 42
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :4
,V/AlarmManager( 2423): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5051): [b] __PingReply__
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2423): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2423): waitForAlarm result :8
,V/AlarmManager( 2423): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2423): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2423): <AppSync3 Whitelist>
,V/AlarmManager( 2423): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 310, Delta = 0
,TIME-OUT KILL (timeout was 1200000ms),D/AmoledAdjustTimer( 2423): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
D/AndroidRuntime( 9206): 
D/AndroidRuntime( 9206): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 9206): CheckJNI is OFF
D/AndroidRuntime( 9206): setted country_code = Poland
D/AndroidRuntime( 9206): setted countryiso_code = PL
D/AndroidRuntime( 9206): setted sales_code = PLS
D/AndroidRuntime( 9206): readGMSProperty: start
D/AndroidRuntime( 9206): readGMSProperty: already setted!!
D/AndroidRuntime( 9206): readGMSProperty: end
D/AndroidRuntime( 9206): addProductProperty: start
D/dalvikvm( 9206): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 9206): Added shared lib libjavacore.so 0x0
D/dalvikvm( 9206): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 9206): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 9206): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 9206): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 9206): failed to load memtrack module: -2
D/dalvikvm( 9206): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 9206): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2423): START PACKAGE DELETE: observer{1119071680}
D/PackageManager( 2423): pkg{<packageName>}
D/PackageManager( 2423): user{0}
D/PackageManager( 2423): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2423): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2423): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2423): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2423): [MSG] DELETE_PACKAGE_AS_USER
D/dalvikvm( 2423): GC_EXPLICIT freed 1447K, 18% free 24497K/29736K, paused 8ms+14ms, total 197ms
D/AndroidRuntime( 9206): Shutting down VM
D/PackageManager( 2423): return delete result to caller: 1119071680
D/PackageManager( 2423): returnCode: -1
D/dalvikvm( 9206): GC_CONCURRENT freed 96K, 14% free 667K/768K, paused 2ms+0ms, total 6ms
I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2423):   Scheme: "sms"
I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2423):   Scheme: "smsto"
I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2423):   Scheme: "mms"
I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2423):   Scheme: "mmsto"
I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :

```
