#### Test 575312431be71d2_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
E/SPPClientService( 5056): [b] __InitReply__
,D/dalvikvm( 2831): GC_EXPLICIT freed 343K, 27% free 10293K/13992K, paused 4ms+7ms, total 51ms
D/dalvikvm( 5885): GC_EXPLICIT freed 899K, 29% free 10004K/13900K, paused 3ms+7ms, total 40ms
D/AndroidRuntime( 6082): 
D/AndroidRuntime( 6082): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6082): CheckJNI is OFF
D/AndroidRuntime( 6082): setted country_code = Poland
D/AndroidRuntime( 6082): setted countryiso_code = PL
D/AndroidRuntime( 6082): setted sales_code = PLS
D/AndroidRuntime( 6082): readGMSProperty: start
D/AndroidRuntime( 6082): readGMSProperty: already setted!!
D/AndroidRuntime( 6082): readGMSProperty: end
D/AndroidRuntime( 6082): addProductProperty: start
D/dalvikvm( 6082): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6082): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6082): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6082): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6082): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
--------- beginning of /dev/log/system
V/AlarmManager( 2424): waitForAlarm result :4
D/Finsky  ( 5075): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager( 2424): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/dalvikvm( 5075): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5075): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5075): VFY: replacing opcode 0x62 at 0x0038
V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 2854): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
W/dalvikvm( 2854): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/dalvikvm( 2854): VFY: replacing opcode 0x6e at 0x0046
D/SensorService( 2424):   0.2 -0.0 9.9
E/memtrack( 6082): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6082): failed to load memtrack module: -2
D/dalvikvm( 6082): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/System.out( 5075): Thread-366(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 5075): Thread-366(ApacheHTTPLog):isShipBuild true
I/System.out( 5075): Thread-366(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/AndroidRuntime( 6082): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 6082): Shutting down VM
D/dalvikvm( 6082): GC_CONCURRENT freed 99K, 13% free 714K/816K, paused 0ms+1ms, total 4ms
,W/IcingInternalCorpora( 3145): getNumBytesRead when not calculated.
D/PowerManagerService( 2424): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2583 (0x0)
I/PowerManagerService( 2424): Nap time...
D/PowerManagerService( 2424): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2424): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2424): Going to sleep due to screen timeout...
D/PowerManagerService( 2424): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2424): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2424): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
I/DisplayPowerController( 2424): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
D/Sensors ( 2424): LightSensor enable = 0
D/DisplayPowerController( 2424): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
D/Sensors ( 2424): LightSensor enableSensor = 0
D/SensorManager( 2424): unregisterListener ::   
I/SurfaceFlinger( 1920): id=16 createSurf (720x1280),-1 flag=20004, FlectronBea
I/Sensors ( 2424): HAL:resetDataRates mEnabled=4
D/SensorManager( 2424): unregisterListener ::   
D/DisplayPowerController( 2424): !@ElectronBeam entry
I/System.out( 5075): Thread-366 calls detatch()
D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4351, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3370): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/lights  ( 2424): lcd : 0 +
D/lights  ( 2424): lcd : 0 -
D/MISC PowerHAL( 2424): miscpower_set_interactive: /sys/class/input/input1/enabled
D/MISC PowerHAL( 2424): sysfs_write +: /sys/class/input/input1/enabled: 0
V/WindowOrientationListener( 2424): WindowOrientationListener disabled
D/SensorService( 2424): AutoRotationSensor::activate (ident=0x81c38998, enabled=0)
D/MISC PowerHAL( 2424): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2424): miscpower_set_interactive: /sys/class/input/input0/enabled
I/Sensors ( 2424): HAL: batch Dry Run is complete
D/MISC PowerHAL( 2424): sysfs_write +: /sys/class/input/input0/enabled: 0
D/PowerManagerService( 2424): blankAllDisplays() is called.
D/PowerManagerService( 2424): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2424): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2424): [PWL] sb release: PowerManagerService.Display
D/KeyguardViewMediator( 2583): onScreenTurnedOff(3)
D/MISC PowerHAL( 2424): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2424): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2424): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2424): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2424): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2424): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2424): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2424): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2424): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2424): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/SEC PowerHAL( 2424): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/SurfaceFlinger( 1920): Screen released, type=0 flinger=0x40f4b550
D/PowerManagerService( 2424): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SensorManager( 2424): unregisterListener ::   
D/InputDispatcher( 2424): setInputDispatchMode: enabled=0, frozen=0
V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Launcher.HomeView( 2778): onPause
D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2424): tr p:2778,o:f
D/LockPatternUtils( 2583): isPcwEnable = 10
D/LockPatternUtils( 2583): isPcwEnable = 10
D/LightsService( 2424): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2424) 
I/SensorManagerA( 2424): getReportingMode :: sensor.mType = 5
D/Sensors ( 2424): LightSensor setDelay = 200000000
D/Sensors ( 2424): LightSensor setSensorDelay = 200000000
D/Sensors ( 2424): Light sensor flush: not enabled 0
D/LightsService( 2424): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/Sensors ( 2424): LightSensor enable = 1
D/Sensors ( 2424): LightSensor enableSensor = 1
D/SensorManager( 2424): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2424): turn on LED for fully charged
D/VibratorService( 2424): JNI vibratorOff()
D/KeyguardViewMediator( 2583): setting alarm to turn off keyguard, seq = 2
D/Launcher.HomeView( 2778): onStop
I/WifiTrafficPoller( 2424): evaluateTrafficStatsPolling
D/STATUSBAR-NotificationService( 2424): ACTION_SCREEN_OFF
D/LightsService( 2424): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2424) 
D/LightsService( 2424): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2424): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
D/IpRemoteDisplayController( 2424): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 2424): Bridge Server is not available
D/PersonaManagerService( 2424): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 2424): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2583): makeExpandedInvisible
D/PhoneStatusBarView( 2583): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is finished!!!! 
I/NfcService( 2756): applyRouting return - 2 
E/NfcService( 2756): callback == null
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
I/qtaguid ( 5075): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5075): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5075): untagSocket(68) failed with errno -22
I/System.out( 5075): Thread-367 calls detatch()
D/LockPatternUtils( 2583): isPcwEnable = 10
D/SurfaceControl( 2424): Excessive delay in blankDisplay() while turning screen off: 225ms
I/libsuspend( 2424): !@[s] autosuspend_autosleep_enable
D/PowerManagerService( 2424): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 226ms
I/libsuspend( 2424): !@[s] autosuspend_autosleep_enable done
D/Finsky  ( 5075): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
D/PowerManagerService( 2424): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2424): [PWL] Off : 0s ago
I/PowerManagerService( 2424): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/SSRMv2:SIOP( 2424): SIOP:: AP = 360, Delta = 0
I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(28)
D/Sensors ( 2424): LightSensor enable = 0
D/Sensors ( 2424): LightSensor enableSensor = 0
D/LightsService( 2424): [SvcLED]  onSensorChanged::light value = 12
D/SensorManager( 2424): unregisterListener ::   
D/lights  ( 2424): led_pattern : 5 +
D/QuickConnect[1.1][2] ( 4642): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 4642): BleHelper.shouldScanBleBg - 
I/dalvikvm( 2424): Jit: resizing JitTable from 8192 to 16384
D/QuickConnect[1.1][2] ( 4642): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
D/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4642): stopLeScan()
D/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - call stopLeScan() complete
D/lights  ( 2424): led_pattern : 5 -
D/LightsService( 2424): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PowerManagerService( 2424): [PWL] sb release: PowerManagerService.Broadcasts
V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5075): Failed write_ctrl(u 68) res=-1 errno=22,
I/qtaguid ( 5075): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5075): untagSocket(68) failed with errno -22
,I/System.out( 5075): Thread-366 calls detatch(),
,D/dalvikvm( 5075): GC_CONCURRENT freed 2065K, 25% free 10482K/13904K, paused 5ms+6ms, total 63ms,
,D/dalvikvm( 5885): GC_EXPLICIT freed 902K, 28% free 10012K/13900K, paused 3ms+8ms, total 47ms,
,D/dalvikvm( 2831): GC_EXPLICIT freed 356K, 27% free 10300K/13992K, paused 5ms+8ms, total 49ms,
,D/dalvikvm( 5075): GC_CONCURRENT freed 741K, 16% free 11788K/13904K, paused 6ms+4ms, total 52ms,
,D/dalvikvm( 5075): WAIT_FOR_CONCURRENT_GC blocked 22ms,
,D/dalvikvm( 5075): GC_FOR_ALLOC freed 932K, 16% free 12604K/14948K, paused 41ms, total 41ms,
,D/dalvikvm( 5075): GC_FOR_ALLOC freed 1008K, 19% free 12908K/15844K, paused 38ms, total 38ms,
,D/dalvikvm( 5075): GC_CONCURRENT freed 2059K, 20% free 14264K/17656K, paused 4ms+4ms, total 54ms,
,D/dalvikvm( 5075): WAIT_FOR_CONCURRENT_GC blocked 27ms,
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/ActivityManager( 2424): Waited long enough for: ServiceRecord{43141b00 u0 com.sec.android.gallery3d/.app.BackgroundCache},
,D/dalvikvm( 2424): GC_EXPLICIT freed 534K, 14% free 24346K/28284K, paused 7ms+12ms, total 166ms,
,D/dalvikvm( 5885): GC_EXPLICIT freed 898K, 28% free 10017K/13900K, paused 3ms+10ms, total 50ms,
,D/dalvikvm( 2831): GC_EXPLICIT freed 346K, 27% free 10301K/13992K, paused 4ms+8ms, total 52ms,
,D/dalvikvm( 2854): GC_EXPLICIT freed 1069K, 23% free 10801K/13876K, paused 6ms+10ms, total 69ms
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5075): Failed write_ctrl(u 68) res=-1 errno=22,
I/qtaguid ( 5075): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5075): untagSocket(68) failed with errno -22,
,I/System.out( 5075): Thread-367 calls detatch(),
,D/AmoledAdjustTimer( 2424): prevTemp = 299, currTemp = 300, prevStep = 4, currStep = 4,
,D/Finsky  ( 5075): [1] DailyHygiene.access$600: Logging device features,
,V/AlarmManager( 2424): waitForAlarm result :4
V/AlarmManager( 2424): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/WearableService( 2738): callingUid 10012, callindPid: 2738
,D/Finsky  ( 5075): [390] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/DeviceConnectionService( 2738): client connected with version: 8296000
,D/Finsky  ( 5075): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5075): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5075): Thread-377(HTTPLog):isShipBuild true
,I/System.out( 5075): Thread-377(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 5885): GC_EXPLICIT freed 883K, 28% free 10008K/13900K, paused 3ms+8ms, total 46ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 348K, 27% free 10301K/13992K, paused 4ms+7ms, total 53ms
,V/AlarmManager( 2424): waitForAlarm result :4
,D/KeyguardViewMediator( 2583): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,V/AlarmManager( 2424): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/LockPatternUtils( 2583): isPcwEnable = 10
D/KeyguardViewMediator( 2583): in doKeyguardLocked mIsRollUp false null
D/PersonaManager( 2583): isKioskContainerExistOnDevice
,D/LockPatternUtils( 2583): isPcwEnable = 10
D/LockPatternUtils( 2583): isPcwEnable = 10
,D/KeyguardViewMediator( 2583): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService( 2424): [PWL] Off : 5s ago
,D/dalvikvm( 5885): GC_EXPLICIT freed 873K, 28% free 10013K/13900K, paused 3ms+9ms, total 45ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 349K, 27% free 10307K/13992K, paused 4ms+7ms, total 51ms
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2424): waitForAlarm result :8
,D/PackageManager( 2424): [MSG] MCS_UNBIND
I/PackageManager( 2424): calling disconnectService()
,D/PackageManager( 2424): Trying to unbind to DefaultContainerService
,I/ActivityManager( 2424): Killing 5342:com.policydm/1000 (adj 15): empty #43
,D/dalvikvm( 2424): GC_EXPLICIT freed 798K, 14% free 24394K/28284K, paused 7ms+16ms, total 210ms
,D/dalvikvm( 5885): GC_EXPLICIT freed 875K, 28% free 10010K/13900K, paused 3ms+9ms, total 45ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 345K, 27% free 10313K/13992K, paused 4ms+7ms, total 46ms
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 5885): GC_EXPLICIT freed 871K, 28% free 10009K/13900K, paused 3ms+9ms, total 45ms
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 350, Delta = -10
,D/dalvikvm( 2831): GC_EXPLICIT freed 355K, 27% free 10319K/13992K, paused 4ms+7ms, total 47ms
,D/dalvikvm( 5885): GC_EXPLICIT freed 872K, 29% free 10006K/13900K, paused 3ms+8ms, total 48ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 359K, 27% free 10329K/13992K, paused 4ms+7ms, total 46ms
,D/dalvikvm( 5885): GC_CONCURRENT freed 1486K, 25% free 10503K/13900K, paused 10ms+11ms, total 49ms
,I/SettingSearch/SearchIntentReceiver( 2831): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2831): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 2831): InitTitleDBThread start --> mDoingInitTitleDB : true
D/AmoledAdjustTimer( 2424): prevTemp = 300, currTemp = 301, prevStep = 4, currStep = 4
,I/SettingSearch/SearchIntentReceiver( 2831): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2831): LOCALE_CHANGED call search setting db finish!!
,I/PowerManagerService( 2424): [PWL] Off : 15s ago,
,V/AlarmManager( 2424): waitForAlarm result :4,
,D/Headlines( 5424): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
V/AlarmManager( 2424): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5424): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5424): Breath 40411 latestRequest time : 1454419080585 current time : 1454419120996,
,D/Finsky  ( 5075): [379] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5075): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.,
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryService( 2424): stay LED for fully charged
V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3370): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 340, Delta = -10,
,E/Watchdog( 2424): !@Sync 3,
,D/AmoledAdjustTimer( 2424): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,D/dalvikvm( 2424): GC_EXPLICIT freed 713K, 14% free 24412K/28284K, paused 14ms+18ms, total 235ms,
,I/Icing   ( 3145): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music,
,I/Icing   ( 3145): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A,
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2424): level:100, scale:100, status:3, health:9, present:true, voltage: 4366, temperature: 299, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 2424): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
,D/LightsService( 2424): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 2424): turn off LED
,D/lights  ( 2424): led_pattern : 0 +
,D/lights  ( 2424): led_pattern : 0 -
D/LightsService( 2424): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2424): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/lights  ( 2424): button : 1 +
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/lights  ( 2424): button : 1 -
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,I/SensorManagerA( 2424): getReportingMode :: sensor.mType = 5
D/PowerManagerService( 2424): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2424): !@[ps] Screen__On :  powered change
D/UsbDeviceManager( 2424): handleMessage -> MSG_POWER_STATE = 0
I/PowerManagerService( 2424): Waking up from sleep...
D/PowerManagerService( 2424): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2424): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2424): [s] WAKEFULNESS_AWAKE
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
D/PowerManagerService( 2424): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 2424): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 2424): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2424): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
I/DisplayPowerController( 2424): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2424): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/DisplayPowerController( 2424): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2424): [DAB] no lux value from sensor manager
,D/DisplayPowerController( 2424): animation target = 26 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/Sensors ( 2424): LightSensor setDelay = 200000000
D/Sensors ( 2424): LightSensor setSensorDelay = 200000000
D/Sensors ( 2424): Light sensor flush: not enabled 0
D/Sensors ( 2424): LightSensor enable = 1
D/Sensors ( 2424): LightSensor enableSensor = 1
,I/libsuspend( 2424): !@[s] autosuspend_autosleep_disable
,I/libsuspend( 2424): !@[s] autosuspend_autosleep_disable done
D/PowerManagerService( 2424): unblankAllDisplays() is called.
,D/PowerManagerService( 2424): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/SensorManager( 2424): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/SurfaceFlinger( 1920): Screen acquired, type=0 flinger=0x40f4b550
,I/SensorManagerA( 2424): getReportingMode :: sensor.mType = 1
,I/Sensors ( 2424): HAL: batch Dry Run is complete
D/PowerManagerService( 2424): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 8ms
D/PowerUI ( 2583): Overvoltage/Undervoltage (recovered) so turn on the screen.
,I/Sensors ( 2424): HAL:resetDataRates mEnabled=4
,I/SensorManagerA( 2424): getReportingMode :: sensor.mType = 65558
D/PowerManagerService( 2424): [api] [s] wakeUp (uid: 10019 pid: 2583) eventTime = 116859
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
D/SensorManager( 2424): registerListener :: 2, MPL Accelerometer, 200000, 0,  
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/SensorService( 2424): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2424): AutoRotationSensor::activate (ident=0x7833a8c8, enabled=1)
D/SensorService( 2424): AutoRotationSensor::AR_init
I/Sensors ( 2424): HAL: batch Dry Run is complete
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/PowerManagerService( 2424): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 15ms
,I/Sensors ( 2424): HAL:resetDataRates mEnabled=4
D/RampAnimator( 2424): Light Animator Finished currentValue=26
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
D/SensorManager( 2424): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,V/KeyguardServiceDelegate( 2424): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@42690338)
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
D/KeyguardViewMediator( 2583): onScreenTurnedOn, seq = 3
D/KeyguardViewMediator( 2583): notifyScreenOnLocked
D/KeyguardViewMediator( 2583): handleNotifyScreenOn
D/KeyguardViewManager( 2583): onScreenTurnedOn()
I/KeyguardEffectViewMain( 2583): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 2583): KeyguardEffectViewParticleSpace : screenTurnedOn
,V/KeyguardViewManager( 2583): send wm null token: host was null
D/VisualEffectParticleEffect( 2583): screenOnAnimationStart
V/KeyguardServiceDelegate( 2424): **** SHOWN CALLED ****
,D/InputDispatcher( 2424): setInputDispatchMode: enabled=1, frozen=0
I/WindowManager( 2424): No lock screen! windowToken=null
D/PowerManagerNotifier( 2424): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2424): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2424): animation target = 26 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2424): !@ElectronBeam exit
I/SurfaceFlinger( 1920): id=16 Removed FlectronBea (8/8)
I/SurfaceFlinger( 1920): id=16 Removed FlectronBea (-2/8)
D/LockPatternUtils( 2583): isPcwEnable = 10
D/lights  ( 2424): lcd : 26 +
D/lights  ( 2424): lcd : 26 -
,I/SELinux ( 6266): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6266):  
D/DisplayPowerController( 2424): animation target = 26 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2424): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/UsbDeviceManager( 2424): sending intent : ACTION_USB_CABLE_STATE : connected = false
,D/STATUSBAR-StatusBarManagerService( 2424): sendNotification(3) - 5
D/NotificationService( 2424): cancelNotificationLocked
D/NotificationService( 2424):  hasClearableItems
D/NotificationService( 2424):  has clearable items no 
D/NotificationService( 2424): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2424): cancelNotificationLocked: cancel alarm
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/LockPatternUtils( 2583): isPcwEnable = 10
,D/BatteryMeterView( 2583): onDraw batteryColor : -1
,I/FPMS_FingerprintManagerService( 2603): onReceive: android.intent.action.USER_PRESENT
,D/SamsungIME( 2980): showDlgMsgBox : false true true
D/LightsService( 2424): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2424) 
D/LightsService( 2424): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
I/SELinux ( 6266): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6266):  
I/SELinux ( 6266):  
,I/SELinux ( 6266): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6266): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6266): >>>>> Normal User
,E/dalvikvm( 6266): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
D/UsbDeviceManager( 2424): received ACTION_POWER_DISCONNECTED = -1
,I/NfcService( 2756): applyRouting return - 2 
,E/SELinux ( 6266): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/LightsService( 2424): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2424): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/LightsService( 2424): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2424) 
,D/LightsService( 2424): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2424): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/PalmMotionService( 2424): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2424): SURFACE_PALM_SWIPE: 1
D/LightsService( 2424): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/MotionRecognitionService( 2424):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/SSRMv2:TSP:AirViewOnOff( 2424): SettingsAirViewInfo:: 000000000
D/SensorService( 2424): AutoRotationSensor::process: Acc  eventTimestamp = 116950970683, previousAccTimestamp = 86647486409, difference = 30303484274 
,D/SensorService( 2424): AutoRotationSensor::reset oldrotation = [100], initState = [1]
D/SSRMv2:SIOP( 2424): SIOP:: AP = 330, Delta = -10
,E/NfcService( 2756): callback == null
,D/Launcher( 2778): onRestart, Launcher: 1113625584
D/Launcher( 2778): onStart, Launcher: 1113625584
,D/Launcher.HomeView( 2778): onStart
,D/TimaKeyStoreProvider( 6266): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6266): Cannot add TimaSignature Service, License check Failed
D/DisplayPowerController( 2424): [api] [DAB] onSensorChanged : 1st lux : 14.0
D/DisplayPowerController( 2424): [DAB] updateAutoBrightnessSEC : 28(28.0)    0.0 < 14.0 < 29.0 (0.0)
,D/DisplayPowerController( 2424): animation target = 28 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/ActivityThread( 6266): Added TimaKesytore provider
,D/RampAnimator( 2424): Light Animator Finished currentValue=28
D/lights  ( 2424): lcd : 28 +
D/SensorService( 2424): AutoRotationSensor::process: Acc  eventTimestamp = 117017633246, previousAccTimestamp = 86647486409, difference = 30370146837 
D/SensorService( 2424):  [AR] 0.2 -0.0 9.9
D/SensorService( 2424): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/SurfaceControl( 2424): Excessive delay in unblankDisplay() while turning screen on: 265ms
,D/lights  ( 2424): lcd : 28 -
D/MISC PowerHAL( 2424): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2424): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2424): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 266ms
,D/FactoryTest( 5151): Not factory mode
,D/FactoryTest( 5151): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 5151): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5151): still no open session command from host, so toast
W/ContextImpl( 5151): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5151): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
D/Launcher( 2778): onResume, Launcher: 1113625584
,D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2424): semi p:2778,o:f
,D/Launcher.HomeView( 2778): onResume
D/MISC PowerHAL( 2424): sysfs_write -: /sys/class/input/input1/enabled: 1
D/MISC PowerHAL( 2424): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2424): sysfs_write +: /sys/class/input/input0/enabled: 1
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2424): tr p:2778,o:f
,D/StatusBarManagerService( 2424): semi p:2778,o:f
D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,V/ApplicationPolicy( 2424): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService( 2424): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2424  pkgName : ACTIVITY_RESUME_BOOSTER@4
,I/SurfaceFlinger( 1920): id=17 createSurf (16x16),-1 flag=20004, EimLayer
,I/SurfaceFlinger( 1920): id=18 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2424): mDVFSHelper.acquire()
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
D/PointerIcon( 2424): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2424): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2424): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2424): setHoveringSpenCustomIcon IconType is same.1
,E/MTPRx   ( 5151): started activity for popup
,D/MenuAppsGridFragment( 2778): onResume
,D/Launcher.HomeView( 2778): onPause
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2424): tr p:2778,o:f
,D/dalvikvm( 6266): GC_CONCURRENT freed 3001K, 32% free 9572K/13908K, paused 4ms+3ms, total 30ms
,D/dalvikvm( 6266): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/WifiTrafficPoller( 2424): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2424): ACTION_SCREEN_ON
D/LightsService( 2424): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2424) 
,D/LightsService( 2424): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2424): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2424): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=on)
I/SecExternalDisplayIntents_Java( 2424): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
D/MISC PowerHAL( 2424): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2424): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2424): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2424): Excessive delay in MISC setInteractive(true) while turning screen on: 166ms
D/SEC PowerHAL( 2424): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2424): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2424): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2424): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2424): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2424): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2424): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2424): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
D/PowerManagerService( 2424): Excessive delay in nativeSetInteractive(true): 168ms
,D/PowerManagerService( 2424): SecHardwareInterface.setBatteryADC : true
E/SettingsReceiverActivity( 5151): PREF_DONT_ASK_AGAIN : true
D/PointerIcon( 2424): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2424): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2424): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2424): setHoveringSpenCustomIcon IconType is same.1
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2424): tr p:2778,o:f
,D/StatusBarManagerService( 2424): semi p:2778,o:f
D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/IpRemoteDisplayController( 2424): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2424): Bridge Server is not available
W/InputMethodManagerService( 2424): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@426cb550 attribute=android.view.inputmethod.EditorInfo@426c4d10, token = android.os.BinderProxy@42e50818
,I/SQLiteSecureOpenHelper( 3543): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3543): getDatabaseLocked(b,b,pwd)...
,D/PersonaManagerService( 2424): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2424): MSG_ACTION_SCREEN_ON called
,I/NfcService( 2756): NFC: Screen On & Cover Open
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 6288): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6288):  
,D/SettingsReceiverActivity( 5151): dev.kiessupport is : TRUE
,I/ActivityManager( 2424): Killing 5380:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43
,D/STATUSBAR-NetworkController( 2583): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,I/SELinux ( 6288): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6288):  
I/SELinux ( 6288):  
,I/SELinux ( 6288): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6288): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6288): >>>>> Normal User
,E/dalvikvm( 6288): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
,E/SELinux ( 6288): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/Launcher( 2778): onResume, Launcher: 1113625584
,D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2424): semi p:2778,o:f
D/Launcher.HomeView( 2778): onResume
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2424): tr p:2778,o:f
,D/StatusBarManagerService( 2424): semi p:2778,o:f
D/TimaKeyStoreProvider( 6288): in addTimaSignatureService
D/MenuAppsGridFragment( 2778): onResume
D/TimaKeyStoreProvider( 6288): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6288): Added TimaKesytore provider
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(16)
,I/SurfaceFlinger( 1920): id=18 Removed EimLayer (5/9)
,I/SurfaceFlinger( 1920): id=18 Removed EimLayer (-2/9)
I/SurfaceFlinger( 1920): id=17 Removed EimLayer (4/8)
,I/SurfaceFlinger( 1920): id=17 Removed EimLayer (-2/8)
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 330, Delta = 0
,D/QuickConnect[1.1][2] ( 4642): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
V/QuickConnect[1.1][2] ( 4642): BleHelper.shouldScanBleBg - 
,D/QuickConnect[1.1][2] ( 4642): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
V/QuickConnect[1.1][2] ( 4642): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
D/QuickConnect[1.1][2] ( 4642): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 4642): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 4642): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 4642): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 4843): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4843): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,D/PowerManagerService( 2424): [PWL] sb release: PowerManagerService.Broadcasts
,D/dalvikvm( 6288): GC_CONCURRENT freed 3003K, 32% free 9566K/13908K, paused 3ms+2ms, total 37ms
,D/dalvikvm( 6288): WAIT_FOR_CONCURRENT_GC blocked 31ms
,I/KIES_RECEIVE( 6288): [APK BnR] Receive KIES_USB_DISCONNECT
W/ContextImpl( 6288): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
,E/TranscodeReceiver( 5844): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,D/videowall-Global( 5844): core_num = 4
,D/dalvikvm( 5844): No JNI_OnLoad found in /system/lib/libsavsff.so 0x42628c00, skipping init
,W/linker  ( 5844): libvwengine.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/videowall-Global( 5844): density : 2.0 width : 720 height : 1280 Raw width : 720 Raw height : 1280
,D/videowall-Global( 5844): dsp : 720, swkey : false, Cores : 4, Clock : 0
,I/SELinux ( 6301): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6301):  
,I/SELinux ( 6301): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6301):  
I/SELinux ( 6301):  
,I/SELinux ( 6301): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6301): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 6301): >>>>> Normal User
,E/dalvikvm( 6301): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 6301): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 6301): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6301): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6301): Added TimaKesytore provider
,D/dalvikvm( 6301): GC_CONCURRENT freed 2995K, 32% free 9573K/13904K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 6301): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/SELinux ( 6316): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6316):  
,I/ActivityManager( 2424): Killing 5441:com.samsung.android.magazine.service/u0a110 (adj 15): empty #43
,D/dalvikvm( 1921): GC_EXPLICIT freed 44K, 13% free 9503K/10884K, paused 2ms+3ms, total 30ms
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,I/SELinux ( 6316): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6316):  
I/SELinux ( 6316):  
,I/SELinux ( 6316): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6316): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6316): >>>>> Normal User
,E/dalvikvm( 6316): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
,E/SELinux ( 6316): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 13% free 9503K/10884K, paused 3ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 6316): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6316): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6316): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 13% free 9503K/10884K, paused 2ms+3ms, total 23ms
,D/dalvikvm( 6316): GC_CONCURRENT freed 3006K, 32% free 9568K/13908K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 6316): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/iu.Environment( 5490): update battery state; isPlugged? false*
,I/iu.SyncManager( 5490): SYNC; picasa accounts
I/ActivityManager( 2424): Killing 5437:com.google.android.apps.magazines/u0a115 (adj 15): empty #43
,I/iu.Environment( 3145): update battery state; isPlugged? false*
,I/GCoreUlr( 2738): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,I/iu.UploadsManager( 5490): num queued entries: 0
,I/iu.UploadsManager( 5490): num updated entries: 0
,I/iu.SyncManager( 5490): NEXT; no task
D/PicasaUploader( 6316):    wifiOnlyPhoto changed to true
D/PicasaUploader( 6316):    wifiOnlyVideo changed to true
,D/PicasaUploader( 6316):    syncOnBattery changed to true
,D/PicasaUploaderSync( 6316): sync account database
,I/iu.UploadsManager( 3145): num queued entries: 0
,I/iu.UploadsManager( 3145): num updated entries: 0
,I/iu.SyncManager( 3145): NEXT; no task
,I/GCoreUlr( 2738): DispatchingService.onCreate()
,D/PicasaUploaderSync( 6316): accounts in DB=1
D/PicasaUploaderSyncManager( 6316): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PicasaUploaderSyncManager( 6316): background data: true
,D/PicasaUploaderSyncManager( 6316): battery info: false
,D/LockPatternUtils( 2583): isPcwEnable = 10
,I/GCoreUlr( 2738): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/Mms/UIEventReceiver( 5234): ui event
,I/GCoreUlr( 2738): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/Mms/UIEventReceiver( 5234): ui event
,I/GCoreUlr( 2738): Unbound from all location providers
,I/GCoreUlr( 2738): Place inference reporting - stopped
,I/GCoreUlr( 2738): DispatchingService.onDestroy()
,I/GCoreUlr( 2738): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2738): Unbound from all location providers
,I/GCoreUlr( 2738): Place inference reporting - stopped
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 4843): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4843): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4843): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4843): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454433900000
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454419135160
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 4843): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 4843): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4843): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4843): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4843): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 4843): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 4843): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:TSP:AirViewOnOff( 2424): SettingsAirViewInfo:: 000000000
,D/lights  ( 2424): button : 0 +
,D/lights  ( 2424): button : 0 -
,D/SensorService( 2424):   0.2 -0.0 9.9
,D/CustomFrequencyManagerService( 2424): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2424  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2424): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2424): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2424  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/AmoledAdjustTimer( 2424): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/CustomFrequencyManagerService( 2424): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2424  tag : ACTIVITY_RESUME_BOOSTER@8
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2424):   0.2 -0.0 9.9
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2424): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2424): <AppSync3 Whitelist>
,V/AlarmManager( 2424): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 4843): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 4843): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4843): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4843): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4843): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 4843): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(8)
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2424):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2424): level:100, scale:100, status:2, health:2, present:true, voltage: 4348, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/PowerManagerService( 2424): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/PowerUI ( 2583): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2424): [api] [s] wakeUp (uid: 10019 pid: 2583) eventTime = 126827
,D/PowerUI ( 2583): playSound : 1
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,V/Vibrator( 2583): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
,V/Vibrator( 2583): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
V/VibratorService( 2424): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2424): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2424): JNI vibratorOff()
D/UsbDeviceManager( 2424): handleMessage -> MSG_POWER_STATE = 1
D/VibratorService( 2424): JNI vibratorOn() : 100
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
D/PowerUI ( 2583): RINGER_MODE_VIBRATE
I/EntropyMixer( 2424): Writing entropy...
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
D/UsbDeviceManager( 2424): sending intent : ACTION_USB_CABLE_STATE : connected = true
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
E/TranscodeReceiver( 5844): onReceive : android.intent.action.ACTION_POWER_CONNECTED
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
D/BatteryMeterView( 2583): onDraw batteryColor : -1
,D/TranscodeService( 5844): onCreate()
,I/SELinux ( 6336): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6336):  
,D/dalvikvm( 5844): No JNI_OnLoad found in /system/lib/libsavsvc.so 0x42628c00, skipping init
,D/dalvikvm( 5844): No JNI_OnLoad found in /system/lib/libsavscmn.so 0x42628c00, skipping init
,D/dalvikvm( 5844): No JNI_OnLoad found in /system/lib/libsthmb.so 0x42628c00, skipping init
,D/TranscodeService( 5844): power? : true / screen off : false
,D/TranscodeService( 5844): releaseTranscodeThread.
,D/VibratorService( 2424): JNI vibratorOff()
,I/SELinux ( 6336): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6336):  
I/SELinux ( 6336):  
,I/SELinux ( 6336): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6336): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6336): >>>>> Normal User
,E/dalvikvm( 6336): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 6336): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6336): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6336): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6336): Added TimaKesytore provider
,D/dalvikvm( 6336): GC_CONCURRENT freed 3007K, 32% free 9564K/13908K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 6336): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/sCloudBackupApp( 6336): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 6336): Other Intent
,D/PicasaUploaderSyncManager( 6316): battery info: true
,I/iu.Environment( 5490): update battery state; isPlugged? true*
,I/iu.UploadsManager( 5490): num queued entries: 0
,I/iu.FingerprintManager( 5490): Start processing all media
,I/iu.FingerprintManager( 5490): Start processing media store URI: content://media/external/images/media
,I/iu.UploadsManager( 5490): num updated entries: 0
,I/iu.SyncManager( 5490): NEXT; no task
,I/iu.FingerprintManager( 5490): Start processing media store URI: content://media/external/video/media
,I/iu.Environment( 3145): update battery state; isPlugged? true*
,I/iu.UploadsManager( 3145): num queued entries: 0
,I/iu.UploadsManager( 3145): num updated entries: 0
,I/iu.SyncManager( 3145): NEXT; no task
,I/iu.FingerprintManager( 5490): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 5490): Start processing media store URI: content://media/phoneStorage/video/media
,E/NetworkScheduler.SchedulerReceiver( 2854): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2854): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/iu.FingerprintManager( 5490): Finished generating fingerprints; 0.054 seconds
,I/iu.FingerprintManager( 5490):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2738): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/GCoreUlr( 2738): DispatchingService.onCreate()
,I/iu.FingerprintManager( 3145): Start processing all media
,I/iu.FingerprintManager( 3145): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 3145): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 3145): Start processing media store URI: content://media/phoneStorage/images/media
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,I/iu.FingerprintManager( 3145): Start processing media store URI: content://media/phoneStorage/video/media
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,I/iu.FingerprintManager( 3145): Finished generating fingerprints; 0.065 seconds
,I/iu.FingerprintManager( 3145):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2738): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/GCoreUlr( 2738): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2738): Unbound from all location providers
,I/GCoreUlr( 2738): Place inference reporting - stopped
,I/GCoreUlr( 2738): DispatchingService.onDestroy()
,I/GCoreUlr( 2738): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2738): Unbound from all location providers
,I/GCoreUlr( 2738): Place inference reporting - stopped
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2424):   0.2 -0.0 9.9
,D/AmoledAdjustTimer( 2424): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2424): Waited long enough for: ServiceRecord{435863e8 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/SensorService( 2424):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2424):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2424): level:100, scale:100, status:2, health:2, present:true, voltage: 4382, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/AlarmManager( 2424): waitForAlarm result :4
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager( 2424): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/Headlines( 5424): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5424): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5424): Breath 73274 latestRequest time : 1454419080585 current time : 1454419153859
,I/VacuumService( 2738): Vacuum at: now=1454419154052 tag=VacuumService
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 330, Delta = 0
,I/PhenotypeConfigurator( 2738): Scheduling Phenotype for one-off execution 290 seconds from now (1454419154546)
,D/GetConfigurationSnapshotOperation( 2738): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2738): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 2738): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2738): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2738): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 2738): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
,W/dalvikvm( 2738): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2738): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2738): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 2738): GC_CONCURRENT freed 1788K, 22% free 11623K/14816K, paused 5ms+5ms, total 55ms
,D/dalvikvm( 2424): GC_EXPLICIT freed 2615K, 15% free 24566K/28612K, paused 10ms+16ms, total 229ms
,D/LocationManagerService( 2424): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 2738): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2738): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2738): VFY: replacing opcode 0x6e at 0x003d
,E/Watchdog( 2424): !@Sync 4
,I/System.out( 2738): Thread-110(HTTPLog):isShipBuild true
,I/System.out( 2738): Thread-110(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/LocationManagerService( 2424): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 2738): GC_CONCURRENT freed 1343K, 19% free 12250K/14996K, paused 8ms+16ms, total 95ms
,D/SensorService( 2424):   0.2 -0.0 9.9
,D/AmoledAdjustTimer( 2424): prevTemp = 299, currTemp = 300, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2424): Waited long enough for: ServiceRecord{42648f98 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2424):   0.2 -0.0 9.8
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2424):   0.2 -0.0 9.9
,D/BatteryService( 2424): level:100, scale:100, status:2, health:2, present:true, voltage: 4385, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2424):   0.2 -0.1 9.9
,D/AmoledAdjustTimer( 2424): prevTemp = 300, currTemp = 301, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/PowerManagerService( 2424): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2424): animation target = 15 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2424): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2424): lcd : 17 +
,D/RampAnimator( 2424): Light Animator Finished currentValue=15
,D/lights  ( 2424): lcd : 17 -
,D/lights  ( 2424): lcd : 15 +
,D/lights  ( 2424): lcd : 15 -
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2424):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2424): waitForAlarm result :8
,D/Headlines( 5424): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5424): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5424): Breath 90012 latestRequest time : 1454419080585 current time : 1454419170597
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2424):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/PowerManagerService( 2424): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2424): Nap time...
,D/PowerManagerService( 2424): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2424): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2424): Going to sleep due to screen timeout...
,D/PowerManagerService( 2424): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController( 2424): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
D/DisplayPowerController( 2424): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,D/Sensors ( 2424): LightSensor enable = 0
,D/Sensors ( 2424): LightSensor enableSensor = 0
I/DisplayPowerController( 2424): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,I/DisplayPowerController( 2424): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
I/SurfaceFlinger( 1920): id=19 createSurf (720x1280),-1 flag=20004, FlectronBea
D/SensorManager( 2424): unregisterListener ::   
,I/Sensors ( 2424): HAL:resetDataRates mEnabled=4
,D/SensorManager( 2424): unregisterListener ::   
D/DisplayPowerController( 2424): !@ElectronBeam entry
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/PowerManagerService( 2424): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2583
,I/PowerManagerService( 2424): !@[ps] Screen__On(wake lock) :  wl: PowerUI
I/PowerManagerService( 2424): Waking up from sleep...
D/PowerManagerService( 2424): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2424): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerNotifier( 2424): mBroadcastInProgress = true , mActualPowerState = 1 , mPendingWakeUpBroadcast = true , mPendingGoToSleepBroadcast = true , mBroadcastedPowerState = 1
,D/lights  ( 2424): button : 1 +
,D/lights  ( 2424): button : 1 -
,I/SensorManagerA( 2424): getReportingMode :: sensor.mType = 5
D/PowerManagerService( 2424): [s] WAKEFULNESS_AWAKE
D/DisplayPowerController( 2424): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2424): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
I/DisplayPowerController( 2424): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2424): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/Sensors ( 2424): LightSensor setDelay = 200000000
D/Sensors ( 2424): LightSensor setSensorDelay = 200000000
D/Sensors ( 2424): Light sensor flush: not enabled 0
D/Sensors ( 2424): LightSensor enable = 1
,D/Sensors ( 2424): LightSensor enableSensor = 1
W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/DisplayPowerController( 2424): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2424): [DAB] no lux value from sensor manager
D/DisplayPowerController( 2424): animation target = 15 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-StatusBarManagerService( 2424): sendNotification(1) - 5
D/SensorManager( 2424): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/NotificationService( 2424): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
,I/SensorManagerA( 2424): getReportingMode :: sensor.mType = 1
I/Sensors ( 2424): HAL: batch Dry Run is complete
D/PowerManagerService( 2424): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 6ms
W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
V/WindowOrientationListener( 2424): WindowOrientationListener disabled
D/SensorService( 2424): AutoRotationSensor::activate (ident=0x7833a8c8, enabled=0)
I/Sensors ( 2424): HAL: batch Dry Run is complete
D/KeyguardViewMediator( 2583): onScreenTurnedOff(3)
I/Sensors ( 2424): HAL:resetDataRates mEnabled=4
D/SensorManager( 2424): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/PowerManagerService( 2424): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 19ms
D/RCPManagerService( 2424): NotificationReceiver onReceive()
D/RCPManagerService( 2424):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
D/RCPManagerService( 2424): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298424
D/LockPatternUtils( 2583): isPcwEnable = 10
D/RCPManagerService( 2424): getPolicy: policy value returned = false
D/RCPManagerService( 2424): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2424): app label == com.android.systemui
D/RCPManagerService( 2424): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298424
D/UserManagerService( 2424): User -1does not exists!!
D/ProgressBar( 2583): setProgressDrawable drawableHeight = 12
D/RCPManagerService( 2424): getPolicy: policy value returned = true
D/RCPManagerService( 2424): Calling User is -1
D/RCPManagerService( 2424): userid of SBN ==-1
D/LockPatternUtils( 2583): isPcwEnable = 10
E/PersonaManagerService( 2424): returning null in  getPersonasForUser
D/SensorManager( 2424): unregisterListener ::   
,D/InputDispatcher( 2424): setInputDispatchMode: enabled=0, frozen=0
D/PhoneStatusBar( 2583): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@425dd6d8
D/Launcher.HomeView( 2778): onPause
D/KeyguardViewMediator( 2583): setting alarm to turn off keyguard, seq = 3
D/lights  ( 2424): lcd : 0 +
D/DisplayPowerController( 2424): animation target = 15 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(52)
D/BatteryMeterView( 2583): onDraw batteryColor : -1
,D/StatusBarManagerService( 2424): tr p:2778,o:f
,D/lights  ( 2424): lcd : 0 -
,D/Launcher.HomeView( 2778): onStop
,I/SensorManagerA( 2424): getReportingMode :: sensor.mType = 5
D/SensorManager( 2424): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/LightsService( 2424): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2424) 
D/LightsService( 2424): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 2424): turn on LED for fully charged
D/VibratorService( 2424): JNI vibratorOff()
,I/WifiTrafficPoller( 2424): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2424): ACTION_SCREEN_OFF
D/LightsService( 2424): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2424) 
,D/LightsService( 2424): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=off)
,I/SecExternalDisplayIntents_Java( 2424): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/Sensors ( 2424): LightSensor sending flush event 16
D/IpRemoteDisplayController( 2424): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2424): Bridge Server is not available
D/Sensors ( 2424): LightSensor setDelay = 200000000
D/Sensors ( 2424): LightSensor setSensorDelay = 200000000
D/SensorManager( 2424): unregisterListener ::   
,D/lights  ( 2424): led_pattern : 5 +
D/LightsService( 2424): [SvcLED]  onSensorChanged::light value = 15
D/DisplayPowerController( 2424): [api] [DAB] onSensorChanged : 1st lux : 15.0
D/DisplayPowerController( 2424): [DAB] updateAutoBrightnessSEC : 30(30.0)    0.0 < 15.0 < 32.0 (0.0)
I/DisplayPowerController( 2424): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 2
I/DisplayPowerController( 2424): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 2
D/DisplayPowerController( 2424): animation target = 15 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 2424): led_pattern : 5 -
D/LightsService( 2424): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PersonaManagerService( 2424): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2424): MSG_ACTION_SCREEN_OFF called
,D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is received!!!! 
,D/STATUSBAR-PhoneStatusBar( 2583): makeExpandedInvisible
D/PhoneStatusBarView( 2583): marqueeStatusBar:123, mClearCover:0
,D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is finished!!!! 
I/NfcService( 2756): applyRouting return - 2 
E/NfcService( 2756): callback == null
,D/LockPatternUtils( 2583): isPcwEnable = 10
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 330, Delta = 0
,D/QuickConnect[1.1][2] ( 4642): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 4642): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4642): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
D/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - force = true
,D/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4642): stopLeScan()
,D/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 5844): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 5844): power? : true / screen off : true
,D/TranscodeService( 5844): Music is = false
,D/TranscodeService( 5844): runvideoplayer is false
,I/SensorManagerA( 2424): getReportingMode :: sensor.mType = 65558
D/SensorService( 2424): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2424): AutoRotationSensor::activate (ident=0x783bd228, enabled=1)
,D/SensorService( 2424): AutoRotationSensor::AR_init
,I/Sensors ( 2424): HAL: batch Dry Run is complete
,I/Sensors ( 2424): HAL:resetDataRates mEnabled=4
,D/TranscodeService( 5844): Thread start
,D/SensorService( 2424): AutoRotationSensor::reset oldrotation = [100], initState = [1]
D/SensorManager( 2424): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,V/KeyguardServiceDelegate( 2424): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@425f7e88)
,D/InputDispatcher( 2424): setInputDispatchMode: enabled=1, frozen=0
D/Launcher( 2778): onRestart, Launcher: 1113625584
D/Launcher( 2778): onStart, Launcher: 1113625584
,D/Launcher.HomeView( 2778): onStart
,D/TranscodeService( 5844): WakeLock.acquire()
D/videowall-FileMgr( 5844): thumbnailDBSync -1
D/KeyguardViewMediator( 2583): onScreenTurnedOn, seq = 4
D/KeyguardViewMediator( 2583): notifyScreenOnLocked
D/KeyguardViewMediator( 2583): handleNotifyScreenOn
D/KeyguardViewManager( 2583): onScreenTurnedOn()
I/KeyguardEffectViewMain( 2583): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 2583): KeyguardEffectViewParticleSpace : screenTurnedOn
,D/VisualEffectParticleEffect( 2583): screenOnAnimationStart
,V/KeyguardServiceDelegate( 2424): **** SHOWN CALLED ****
V/KeyguardViewManager( 2583): send wm null token: host was null
I/WindowManager( 2424): No lock screen! windowToken=null
D/PowerManagerNotifier( 2424): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2424): Screen Readiness Inspection completed: mNestCount=0
,I/SurfaceFlinger( 1920): id=19 Removed FlectronBea (8/8)
D/DisplayPowerController( 2424): animation target = 15 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2424): !@ElectronBeam exit
I/SurfaceFlinger( 1920): id=19 Removed FlectronBea (-2/8)
D/LockPatternUtils( 2583): isPcwEnable = 10
D/lights  ( 2424): lcd : 15 +
,D/Launcher( 2778): onResume, Launcher: 1113625584
,D/StatusBarManagerService( 2424): semi p:2778,o:f
,D/lights  ( 2424): lcd : 15 -
D/DisplayPowerController( 2424): animation target = 15 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2424): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/Launcher.HomeView( 2778): onResume
,D/LockPatternUtils( 2583): isPcwEnable = 10
D/StatusBarManagerService( 2424): tr p:2778,o:f
D/StatusBarManagerService( 2424): semi p:2778,o:f
,I/SensorManagerA( 2424): getReportingMode :: sensor.mType = 5
,D/SensorManager( 2424): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/PalmMotionService( 2424): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
D/LightsService( 2424): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2424) 
,D/LightsService( 2424): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/FPMS_FingerprintManagerService( 2603): onReceive: android.intent.action.USER_PRESENT
,D/PalmMotionService( 2424): SURFACE_PALM_SWIPE: 1
,E/MotionRecognitionService( 2424):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/SamsungIME( 2980): showDlgMsgBox : false true true
D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/SSRMv2:TSP:AirViewOnOff( 2424): SettingsAirViewInfo:: 000000000
D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
,D/MenuAppsGridFragment( 2778): onResume
,D/LockPatternUtils( 2583): isPcwEnable = 10
D/Sensors ( 2424): LightSensor setDelay = 200000000
,D/Sensors ( 2424): LightSensor setSensorDelay = 200000000
D/SensorManager( 2424): unregisterListener ::   
,D/lights  ( 2424): led_pattern : 0 +
D/LightsService( 2424): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 2424) 
D/LightsService( 2424): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 2424): turn off LED
D/LightsService( 2424): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/lights  ( 2424): led_pattern : 0 -
D/SensorService( 2424): AutoRotationSensor::process: Acc  eventTimestamp = 157472033243, previousAccTimestamp = 156982817819, difference = 489215424 
D/SensorService( 2424):  [AR] 0.2 -0.0 9.9
,D/SensorService( 2424): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
D/LightsService( 2424): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onInitialize : 139
,D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onSetOnInfoListener : add 139
I/PrGenericPlugin( 1923): [A] ENTER onInitialize : 0x8b
,I/PrGenericPlugin( 1923): [A] LEAVE onInitialize : 0x8b
,D/TranscodeService( 5844): Thread end
,D/Mms/UIEventReceiver( 5234): ui event
,D/TranscodeService( 5844): WakeLock.release()
D/TranscodeService( 5844): onDestroy()
,D/TranscodeService( 5844): releaseTranscodeThread.
,I/WifiTrafficPoller( 2424): evaluateTrafficStatsPolling
,V/ApplicationPolicy( 2424): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,D/Sensors ( 2424): LightSensor sending flush event 16
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
D/STATUSBAR-NotificationService( 2424): ACTION_SCREEN_ON
D/LightsService( 2424): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2424) 
D/LightsService( 2424): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2424): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2424): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=on)
I/ActivityManager( 2424): Killing 4730:com.android.email/u0a157 (adj 15): empty #43
,I/SecExternalDisplayIntents_Java( 2424): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController( 2424): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2424): Bridge Server is not available
,D/PersonaManagerService( 2424): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2424): MSG_ACTION_SCREEN_ON called
,I/NfcService( 2756): NFC: Screen On & Cover Open
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
,D/STATUSBAR-NetworkController( 2583): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 330, Delta = 0
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/QuickConnect[1.1][2] ( 4642): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
V/QuickConnect[1.1][2] ( 4642): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4642): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
V/QuickConnect[1.1][2] ( 4642): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
D/QuickConnect[1.1][2] ( 4642): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 4642): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 4642): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 4642): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 4843): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4843): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4843): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4843): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454433900000
D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454419174779
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4843): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,D/PowerManagerService( 2424): [PWL] sb release: PowerManagerService.Broadcasts
D/daemonapp( 4843): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 4843): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 4843): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4843): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4843): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4843): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 4843): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4843): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4843): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4843): [MSC_Daemon]>>> WDSM:424 [0:0] today==null,
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(3),
,D/lights  ( 2424): button : 0 +,
,D/lights  ( 2424): button : 0 -
,D/SSRMv2:TSP:AirViewOnOff( 2424): SettingsAirViewInfo:: 000000000
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2424):   0.2 -0.0 9.9
,D/AmoledAdjustTimer( 2424): prevTemp = 301, currTemp = 302, prevStep = 4, currStep = 4
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(60)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,V/AlarmManager( 2424): waitForAlarm result :4
,D/KeyguardViewMediator( 2583): received DELAYED_KEYGUARD_ACTION with seq = 3, mDelayedShowingSequence = 4
V/AlarmManager( 2424): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2424):   0.2 -0.0 9.8
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(60)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/SensorService( 2424):   0.2 -0.0 9.9
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 330, Delta = 0
,E/Watchdog( 2424): !@Sync 5
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2424):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2424): prevTemp = 302, currTemp = 303, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/SensorService( 2424):   0.2 -0.0 9.9,
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2424):   0.2 -0.0 9.9
,D/PowerManagerService( 2424): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2583 (0x0)
I/PowerManagerService( 2424): Nap time...
,D/PowerManagerService( 2424): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2424): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2424): Going to sleep due to screen timeout...
D/PowerManagerService( 2424): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController( 2424): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2424): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/DisplayPowerController( 2424): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,I/DisplayPowerController( 2424): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
D/Sensors ( 2424): LightSensor enable = 0
D/Sensors ( 2424): LightSensor enableSensor = 0
I/SurfaceFlinger( 1920): id=20 createSurf (720x1280),-1 flag=20004, FlectronBea
,D/SensorManager( 2424): unregisterListener ::   
D/DisplayPowerController( 2424): !@ElectronBeam entry
,I/Sensors ( 2424): HAL:resetDataRates mEnabled=4
,D/SensorManager( 2424): unregisterListener ::   
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/lights  ( 2424): lcd : 0 +
,D/lights  ( 2424): lcd : 0 -
D/MISC PowerHAL( 2424): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2424): sysfs_write +: /sys/class/input/input1/enabled: 0
D/PowerManagerService( 2424): blankAllDisplays() is called.
D/PowerManagerService( 2424): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2424): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2424): [PWL] sb release: PowerManagerService.Display
V/WindowOrientationListener( 2424): WindowOrientationListener disabled
,D/SensorService( 2424): AutoRotationSensor::activate (ident=0x783bd228, enabled=0)
I/Sensors ( 2424): HAL: batch Dry Run is complete
D/KeyguardViewMediator( 2583): onScreenTurnedOff(3)
D/MISC PowerHAL( 2424): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2424): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2424): sysfs_write +: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2424): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2424): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2424): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,D/SEC PowerHAL( 2424): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2424): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2424): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2424): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2424): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2424): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2424): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/SEC PowerHAL( 2424): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SensorManager( 2424): unregisterListener ::   
,D/InputDispatcher( 2424): setInputDispatchMode: enabled=0, frozen=0
,D/SurfaceFlinger( 1920): Screen released, type=0 flinger=0x40f4b550
,D/PowerManagerService( 2424): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/LockPatternUtils( 2583): isPcwEnable = 10
D/Launcher.HomeView( 2778): onPause
,D/LockPatternUtils( 2583): isPcwEnable = 10
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/KeyguardViewMediator( 2583): setting alarm to turn off keyguard, seq = 4
D/StatusBarManagerService( 2424): tr p:2778,o:f
D/LightsService( 2424): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2424) 
D/LightsService( 2424): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,I/SensorManagerA( 2424): getReportingMode :: sensor.mType = 5
D/Sensors ( 2424): LightSensor setDelay = 200000000
D/Sensors ( 2424): LightSensor setSensorDelay = 200000000
,D/Sensors ( 2424): Light sensor flush: not enabled 0
D/Sensors ( 2424): LightSensor enable = 1
,D/Sensors ( 2424): LightSensor enableSensor = 1
,D/SensorManager( 2424): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2424): turn on LED for fully charged
,D/Launcher.HomeView( 2778): onStop
D/VibratorService( 2424): JNI vibratorOff()
,I/WifiTrafficPoller( 2424): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2424): ACTION_SCREEN_OFF
D/LightsService( 2424): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2424) 
,D/LightsService( 2424): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2424): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2424): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2424): Bridge Server is not available
,D/PersonaManagerService( 2424): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2424): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2583): makeExpandedInvisible
D/PhoneStatusBarView( 2583): marqueeStatusBar:124, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/LockPatternUtils( 2583): isPcwEnable = 10
,D/SurfaceControl( 2424): Excessive delay in blankDisplay() while turning screen off: 207ms
,I/libsuspend( 2424): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2424): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2424): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 210ms
D/PowerManagerService( 2424): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2424): [PWL] Off : 0s ago
I/PowerManagerService( 2424): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 330, Delta = 0
,D/QuickConnect[1.1][2] ( 4642): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 4642): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4642): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
V/QuickConnect[1.1][2] ( 4642): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ea8b0
D/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4642): stopLeScan()
D/QuickConnect[1.1][2] ( 4642): BleHelper.stopScan - call stopLeScan() complete
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(29)
,D/PowerManagerService( 2424): [PWL] sb release: PowerManagerService.Broadcasts
,D/Sensors ( 2424): LightSensor enable = 0
,D/Sensors ( 2424): LightSensor enableSensor = 0
,D/LightsService( 2424): [SvcLED]  onSensorChanged::light value = 15
D/SensorManager( 2424): unregisterListener ::   
D/lights  ( 2424): led_pattern : 5 +
,D/lights  ( 2424): led_pattern : 5 -
D/LightsService( 2424): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer( 2424): prevTemp = 303, currTemp = 305, prevStep = 4, currStep = 4,
,D/KeyguardViewMediator( 2583): received DELAYED_KEYGUARD_ACTION with seq = 4, mDelayedShowingSequence = 4,
,V/AlarmManager( 2424): waitForAlarm result :4,
D/LockPatternUtils( 2583): isPcwEnable = 10
D/KeyguardViewMediator( 2583): in doKeyguardLocked mIsRollUp false null
D/PersonaManager( 2583): isKioskContainerExistOnDevice
,D/LockPatternUtils( 2583): isPcwEnable = 10
D/LockPatternUtils( 2583): isPcwEnable = 10
,D/KeyguardViewMediator( 2583): doKeyguard: not showing because lockscreen is off,
,V/AlarmManager( 2424): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/PowerManagerService( 2424): [PWL] Off : 5s ago,
,V/AlarmManager( 2424): waitForAlarm result :8,
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,V/AlarmManager( 2424): waitForAlarm result :8,
,D/Headlines( 5424): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
D/Headlines( 5424): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5424): Breath 120015 latestRequest time : 1454419080585 current time : 1454419200600
,D/Headlines( 5424): stop 
,D/Headlines( 5424): Breath.onDestroy : 
,I/ActivityManager( 2424): Killing 4831:com.samsung.android.service.travel/u0a170 (adj 15): empty #43
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2424): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3370): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2424): [PWL] Off : 15s ago,
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): stay LED for fully charged
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 330, Delta = 0,
,E/Watchdog( 2424): !@Sync 6,
,D/AmoledAdjustTimer( 2424): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4,
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged,
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2424): [PWL] Off : 30s ago,
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = -10,
,V/AlarmManager( 2424): waitForAlarm result :4,
,V/AlarmManager( 2424): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/AmoledAdjustTimer( 2424): prevTemp = 303, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2424): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2424): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3370): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2424): [PWL] Off : 50s ago,
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2424): !@Sync 7,
,D/AmoledAdjustTimer( 2424): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2424): stay LED for fully charged,
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3370): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2424): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,V/AlarmManager( 2424): waitForAlarm result :8,
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2424): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2424): [PWL] Off : 75s ago,
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/BatteryService( 2424): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3370): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2424): !@Sync 8,
,D/AmoledAdjustTimer( 2424): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/BatteryService( 2424): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0,
,D/dalvikvm( 2583): GC_CONCURRENT freed 15671K, 34% free 33912K/50912K, paused 16ms+10ms, total 89ms,
,D/AmoledAdjustTimer( 2424): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2424): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2424): [PWL] Off : 105s ago,
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2424): !@Sync 9,
,D/AmoledAdjustTimer( 2424): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2424): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,V/AlarmManager( 2424): waitForAlarm result :8,
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2424): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,D/TimaService( 2424): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2424): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2424): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2424): initializing...,
I/TLC_TIMA_PKM_initialize( 2424): root = 0, root_strlen = 1,
I/TLC_TIMA_PKM_initialize( 2424): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2424): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2424): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2424): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2424): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2424): aligned max_sendmsg_size = 262208,
I/TZ: mc_tlc_communication( 2424): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2424): device_id = 0x0
I/TZ: mc_tlc_communication( 2424): tlc_open() was called,
,I/TZ: mc_tlc_communication( 2424): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2424): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2424): Opening the session,
,I/TZ: mc_tlc_communication( 2424): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2424): Trustlet response is completed,
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2424): [PWL] Off : 140s ago,
I/PowerManagerService( 2424): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2424): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2424): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2424, ws=null) (elapsedTime=5845),
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 2424): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2424): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2424): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2424): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2424): !@Sync 10
,D/AmoledAdjustTimer( 2424): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/BatteryService( 2424): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2424): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,V/AlarmManager( 2424): waitForAlarm result :4,
,V/AlarmManager( 2424): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 6834): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6834):  
,I/SELinux ( 6834): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6834):  
I/SELinux ( 6834):  
I/SELinux ( 6834): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6834): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6834): >>>>> Normal User
,E/dalvikvm( 6834): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 6834): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6834): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6834): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6834): Added TimaKesytore provider
,D/dalvikvm( 6834): GC_CONCURRENT freed 3000K, 32% free 9570K/13908K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 6834): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/ActivityManager( 2424): Killing 5301:com.sec.android.fotaclient/u0a11 (adj 15): empty #43
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2424): !@Sync 11
,D/AmoledAdjustTimer( 2424): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2424): [PWL] Off : 180s ago
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/BatteryService( 2424): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2424): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2424): !@Sync 12
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/BatteryService( 2424): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2424): GC_FOR_ALLOC freed 3368K, 18% free 24628K/29764K, paused 205ms, total 205ms
D/AmoledAdjustTimer( 2424): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :4
,V/AlarmManager( 2424): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5056): [b] __PingReply__
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2424): [PWL] Off : 225s ago
,E/Watchdog( 2424): !@Sync 13
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2424): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2424): !@Sync 14
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2424): [PWL] Off : 275s ago
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): stay LED for fully charged
D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 15
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 290, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2424): !@Sync 16
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2424): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 17
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2424): !@Sync 18
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2424): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2424): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 19
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService( 2424): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2424): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2424): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 2424): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2424): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2424): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2424): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2424): !@Sync 20
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2424): [PWL] Off : 455s ago
,W/ContextImpl( 2424): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2424): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 21
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/GAV2    ( 5167): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5167): Thread[disconnect check,5,main]: Disconnected from service
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 3778): GC_CONCURRENT freed 2882K, 31% free 9691K/13940K, paused 14ms+2ms, total 48ms
,D/dalvikvm( 3778): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/dalvikvm( 2424): GC_FOR_ALLOC freed 2645K, 18% free 24658K/29836K, paused 181ms, total 181ms
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 22
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2424): [PWL] Off : 525s ago
,E/Watchdog( 2424): !@Sync 23
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/BatteryService( 2424): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2424): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2424): <AppSync3 Whitelist>
,V/AlarmManager( 2424): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2424): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 24
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 25
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2424): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 26
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 27
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2424): [PWL] Off : 680s ago
,E/Watchdog( 2424): !@Sync 28
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 29
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2424): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2424): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2424): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2424): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2424): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2424): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2424): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2424): !@Sync 30
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2424): [PWL] Off : 765s ago
,E/Watchdog( 2424): !@Sync 31
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :4
,D/LightsService( 2424): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2424): getReportingMode :: sensor.mType = 5
D/Sensors ( 2424): LightSensor setDelay = 200000000
,D/Sensors ( 2424): LightSensor setSensorDelay = 200000000
,D/Sensors ( 2424): Light sensor flush: not enabled 0
D/Sensors ( 2424): LightSensor enable = 1
,D/Sensors ( 2424): LightSensor enableSensor = 1
,D/SensorManager( 2424): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  ,
,V/AlarmManager( 2424): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 8237): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8237):  
,I/SELinux ( 8237): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8237):  
I/SELinux ( 8237):  
,I/SELinux ( 8237): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8237): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 8237): >>>>> Normal User
,E/dalvikvm( 8237): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux ( 8237): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 8237): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8237): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8237): Added TimaKesytore provider
D/Sensors ( 2424): LightSensor enable = 0
,D/Sensors ( 2424): LightSensor enableSensor = 0
D/LightsService( 2424): [SvcLED]  onSensorChanged::light value = 11
,D/SensorManager( 2424): unregisterListener ::   
D/LightsService( 2424): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 8237): GC_CONCURRENT freed 2997K, 32% free 9571K/13904K, paused 3ms+1ms, total 24ms
,D/dalvikvm( 8237): WAIT_FOR_CONCURRENT_GC blocked 20ms
,E/dalvikvm( 8237): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm( 8237): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 8237): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 8237): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 8237): Link of class 'Lal;' failed
E/dalvikvm( 8237): Could not find class 'al', referenced from method b.a
W/dalvikvm( 8237): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 8237): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 8237): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 8237): Link of class 'Lan;' failed
E/dalvikvm( 8237): Could not find class 'an', referenced from method b.a
W/dalvikvm( 8237): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 8237): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm( 8237): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 8237): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 8237): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 8237): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 8237): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 8237): VFY: replacing opcode 0x6e at 0x0006,
,W/dalvikvm( 8237): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
,E/dalvikvm( 8237): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 8237): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 8237): VFY: replacing opcode 0x23 at 0x0005
,D/dalvikvm( 8237): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
,W/dalvikvm( 8237): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 8237): Link of class 'Lal;' failed
D/dalvikvm( 8237): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm( 8237): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 8237): Link of class 'Lan;' failed
D/dalvikvm( 8237): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm( 8237): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm( 8237): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
W/dalvikvm( 8237): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 8237): VFY: replacing opcode 0x6e at 0x000d
,D/ConnectivityService( 2424): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2583): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2583): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2583): updateDataNetType()
,D/dalvikvm( 8237): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 8237): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 8237): VFY: replacing opcode 0x62 at 0x000a
,D/STATUSBAR-NetworkController( 2583): NoService, mRoamingIconId = 0
D/dalvikvm( 8237): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 8237): VFY: unable to resolve instance field 36
D/dalvikvm( 8237): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 8237): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 8237): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 8237): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 8237): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 8237): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 8237): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42691460
D/dalvikvm( 8237): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42691460
D/dalvikvm( 8237): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42691460, skipping init
D/dalvikvm( 8237): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42691460
D/dalvikvm( 8237): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42691460
V/JNIHelp ( 8237): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/dalvikvm( 8237): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 8237): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 8237): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 8237): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42691460
D/dalvikvm( 8237): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42691460
D/dalvikvm( 8237): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42691460
,D/dalvikvm( 8237): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42691460
,I/dalvikvm( 8237): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 8237): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 8237): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm( 8237): DexOpt: --- BEGIN 'ads-2140194743.jar' (bootstrap=0) ---
,I/ProviderInstaller( 8237): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm( 8265): DexOpt: load 5ms, verify+opt 14ms, 194052 bytes
,D/dalvikvm( 8237): DexOpt: --- END 'ads-2140194743.jar' (success) ---
,D/dalvikvm( 8237): DEX prep '/data/data/com.google.android.youtube/cache/ads-2140194743.jar': unzip in 0ms, rewrite 106ms
,E/YouTube MDX( 8237): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm( 8237): GC_CONCURRENT freed 1915K, 24% free 10690K/13936K, paused 6ms+5ms, total 56ms
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 8237): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/dalvikvm( 8237): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 8237): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 8237): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 8237): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 8237): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 8237): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 8237): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 8237): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 8237): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 8237): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 8237): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 8237): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 8237): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 8237): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 8237): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 8237): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm( 8237): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 8237): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 8237): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm( 8237): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 8237): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 8237): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm( 8237): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 8237): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 8237): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm( 8237): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 8237): VFY: replacing opcode 0x6e at 0x0002
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 8237): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 8237): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 8237): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 8237): Found 10012
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 8237): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/System.out( 8237): Thread-578(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 8237): Thread-578(ApacheHTTPLog):isShipBuild true
,I/System.out( 8237): Thread-578(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 8237): Thread-578 calls detatch()
,D/dalvikvm( 8237): GC_CONCURRENT freed 1315K, 20% free 11329K/14016K, paused 5ms+5ms, total 51ms
,I/System.out( 8237): Thread-569 calls detatch()
,I/ActivityManager( 2424): Killing 5313:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2424): GC_FOR_ALLOC freed 3204K, 18% free 24579K/29868K, paused 195ms, total 195ms
D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 32
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,E/SPPClientService( 5056): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 33
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2424): [PWL] Off : 855s ago
,E/Watchdog( 2424): !@Sync 34
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): stay LED for fully charged
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2424): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2424): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 35
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 36
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2424): waitForAlarm result :4
,V/AlarmManager( 2424): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2424): [PWL] Off : 950s ago
,E/Watchdog( 2424): !@Sync 37
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 38
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 39
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2424): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2424): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2424): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2424): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2424): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2424): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2424): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2424): !@Sync 40
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2424): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 41
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2424): stay LED for fully charged
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2424): GC_FOR_ALLOC freed 2698K, 18% free 24552K/29868K, paused 191ms, total 191ms
D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2424): waitForAlarm result :8
,V/AlarmManager( 2424): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 42
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2424): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2424): waitForAlarm result :4
,V/AlarmManager( 2424): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5056): [b] __PingReply__
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2424): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2424): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2424): mCoverManager.getCoverState() : true
,D/BatteryService( 2424): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3370): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3370): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2424): !@Sync 43
,D/SSRMv2:SIOP( 2424): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2424): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1200000ms)
```
