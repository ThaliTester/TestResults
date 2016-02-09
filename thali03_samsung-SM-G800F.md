#### Test 58135655e9e7eb8_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
I/ActivityManager( 2419): Waited long enough for: ServiceRecord{438ff070 u0 com.sec.spp.push/.PushClientService}
,--------- beginning of /dev/log/main
D/dalvikvm( 5886): GC_EXPLICIT freed 1027K, 27% free 10008K/13624K, paused 4ms+8ms, total 48ms
D/AndroidRuntime( 6108): 
D/AndroidRuntime( 6108): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6108): CheckJNI is OFF
D/AndroidRuntime( 6108): setted country_code = Poland
D/AndroidRuntime( 6108): setted countryiso_code = PL
D/AndroidRuntime( 6108): setted sales_code = PLS
D/AndroidRuntime( 6108): readGMSProperty: start
D/AndroidRuntime( 6108): readGMSProperty: already setted!!
D/AndroidRuntime( 6108): readGMSProperty: end
D/AndroidRuntime( 6108): addProductProperty: start
D/dalvikvm( 6108): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6108): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6108): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6108): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6108): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6108): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6108): failed to load memtrack module: -2
D/dalvikvm( 6108): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6108): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 6108): Shutting down VM
D/dalvikvm( 6108): GC_CONCURRENT freed 98K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
,D/dalvikvm( 2829): GC_EXPLICIT freed 357K, 26% free 10286K/13716K, paused 5ms+8ms, total 49ms
D/dalvikvm( 5886): GC_EXPLICIT freed 898K, 27% free 10003K/13624K, paused 3ms+9ms, total 47ms
,E/SPPClientService( 5080): [b] __InitReply__
,V/AlarmManager( 2419): waitForAlarm result :4
,D/Finsky  ( 5100): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/dalvikvm( 5100): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5100): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5100): VFY: replacing opcode 0x62 at 0x0038
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/dalvikvm( 2845): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
W/dalvikvm( 2845): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 2845): VFY: replacing opcode 0x6e at 0x0046
,D/SensorService( 2419):   0.2 -0.0 9.9
,I/System.out( 5100): Thread-369(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5100): Thread-369(ApacheHTTPLog):isShipBuild true
,I/System.out( 5100): Thread-369(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/PowerManagerService( 2419): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2579 (0x0)
I/PowerManagerService( 2419): Nap time...
,D/PowerManagerService( 2419): [s] WAKEFULNESS_NAPPING
,I/PowerManagerService( 2419): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2419): Going to sleep due to screen timeout...
,D/PowerManagerService( 2419): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController( 2419): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
D/DisplayPowerController( 2419): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/SensorManager( 2419): unregisterListener ::   
I/DisplayPowerController( 2419): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,I/DisplayPowerController( 2419): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
I/SurfaceFlinger( 1919): id=16 createSurf (720x1280),-1 flag=20004, FlectronBea
,I/Sensors ( 2419): HAL:resetDataRates mEnabled=4
D/DisplayPowerController( 2419): !@ElectronBeam entry
,D/SensorManager( 2419): unregisterListener ::   
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/IcingInternalCorpora( 3143): getNumBytesRead when not calculated.
,D/lights  ( 2419): lcd : 0 +
,D/lights  ( 2419): lcd : 0 -
D/MISC PowerHAL( 2419): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2419): sysfs_write +: /sys/class/input/input1/enabled: 0
D/PowerManagerService( 2419): blankAllDisplays() is called.
D/PowerManagerService( 2419): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2419): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2419): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2419): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2419): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2419): sysfs_write +: /sys/class/input/input0/enabled: 0
V/WindowOrientationListener( 2419): WindowOrientationListener disabled
D/SensorService( 2419): AutoRotationSensor::activate (ident=0x879258a8, enabled=0)
D/KeyguardViewMediator( 2579): onScreenTurnedOff(3)
D/MISC PowerHAL( 2419): sysfs_write -: /sys/class/input/input0/enabled: 0
I/Sensors ( 2419): HAL: batch Dry Run is complete
D/MISC PowerHAL( 2419): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2419): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2419): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2419): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2419): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2419): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2419): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2419): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2419): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2419): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SurfaceFlinger( 1919): Screen released, type=0 flinger=0x40af5550
,D/PowerManagerService( 2419): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SensorManager( 2419): unregisterListener ::   
,D/InputDispatcher( 2419): setInputDispatchMode: enabled=0, frozen=0
,D/LockPatternUtils( 2579): isPcwEnable = 10,
,D/Launcher.HomeView( 2774): onPause,
,D/LockPatternUtils( 2579): isPcwEnable = 10,
,D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false,
,D/StatusBarManagerService( 2419): tr p:2774,o:f,
D/KeyguardViewMediator( 2579): setting alarm to turn off keyguard, seq = 2
,D/LightsService( 2419): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2419) ,
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
,D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
,D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/System.out( 5100): Thread-369 calls detatch()
D/BatteryService( 2419): turn on LED for fully charged
,D/VibratorService( 2419): JNI vibratorOff()
D/Launcher.HomeView( 2774): onStop
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2419): ACTION_SCREEN_OFF
D/LightsService( 2419): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2419) 
,D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,I/AudioHardwareTinyALSA( 1923): setParameters(screen_state=off)
,I/SecExternalDisplayIntents_Java( 2419): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2419): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2419): Bridge Server is not available
,D/PersonaManagerService( 2419): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2419): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2579):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2579): makeExpandedInvisible
D/PhoneStatusBarView( 2579): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2579):      ACTION_SCREEN_OFF is finished!!!! 
,D/SurfaceControl( 2419): Excessive delay in blankDisplay() while turning screen off: 195ms
I/libsuspend( 2419): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2419): !@[s] autosuspend_autosleep_enable done
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
D/PowerManagerService( 2419): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 196ms
D/PowerManagerService( 2419): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2419): [PWL] Off : 0s ago
I/PowerManagerService( 2419): [PWL]   PowerManagerService.Broadcasts: ref count=1
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
,I/display ( 1919): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(28)
,D/LockPatternUtils( 2579): isPcwEnable = 10
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 370, Delta = 0
D/QuickConnect[1.1][2] ( 4664): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 4664): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4664): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4664): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4290d000
V/QuickConnect[1.1][2] ( 4664): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4290d000
D/QuickConnect[1.1][2] ( 4664): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4664): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4664): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4664): stopLeScan()
D/QuickConnect[1.1][2] ( 4664): BleHelper.stopScan - call stopLeScan() complete
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
D/SensorManager( 2419): unregisterListener ::   
,D/lights  ( 2419): led_pattern : 5 +
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 14
,D/lights  ( 2419): led_pattern : 5 -
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PowerManagerService( 2419): [PWL] sb release: PowerManagerService.Broadcasts
V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5100): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5100): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5100): untagSocket(68) failed with errno -22
,I/System.out( 5100): Thread-370 calls detatch()
,D/Finsky  ( 5100): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2419): GC_EXPLICIT freed 611K, 12% free 24369K/27688K, paused 9ms+15ms, total 207ms
,I/qtaguid ( 5100): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5100): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5100): untagSocket(68) failed with errno -22
,I/System.out( 5100): Thread-369 calls detatch()
,D/dalvikvm( 5100): GC_CONCURRENT freed 1961K, 23% free 10673K/13692K, paused 4ms+5ms, total 61ms
,D/dalvikvm( 5100): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2829): GC_EXPLICIT freed 341K, 25% free 10299K/13716K, paused 4ms+8ms, total 49ms
,D/dalvikvm( 5886): GC_EXPLICIT freed 901K, 27% free 10012K/13624K, paused 3ms+10ms, total 47ms
,D/dalvikvm( 5100): GC_CONCURRENT freed 693K, 13% free 12020K/13780K, paused 3ms+4ms, total 48ms
,D/dalvikvm( 5100): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 5100): GC_FOR_ALLOC freed 1351K, 19% free 12390K/15112K, paused 39ms, total 40ms
,D/dalvikvm( 5100): GC_FOR_ALLOC freed 1491K, 21% free 13188K/16520K, paused 36ms, total 37ms
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{43752510 u0 com.sec.android.gallery3d/.app.BackgroundCache}
D/dalvikvm( 5886): null clazz in OP_INSTANCE_OF, single-stepping
D/dalvikvm( 2829): GC_EXPLICIT freed 365K, 25% free 10300K/13716K, paused 6ms+8ms, total 57ms
D/dalvikvm( 5886): GC_EXPLICIT freed 905K, 27% free 10010K/13624K, paused 4ms+10ms, total 51ms
,D/AmoledAdjustTimer( 2419): prevTemp = 310, currTemp = 311, prevStep = 4, currStep = 4
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5100): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5100): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5100): untagSocket(68) failed with errno -22
,I/System.out( 5100): Thread-370 calls detatch()
,D/Finsky  ( 5100): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/DeviceConnectionService( 2734): client connected with version: 8296000
,D/WearableService( 2734): callingUid 10012, callindPid: 2734
,D/Finsky  ( 5100): [392] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5100): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5100): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5100): Thread-380(HTTPLog):isShipBuild true
,I/System.out( 5100): Thread-380(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,V/AlarmManager( 2419): waitForAlarm result :4
,D/KeyguardViewMediator( 2579): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/LockPatternUtils( 2579): isPcwEnable = 10
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/KeyguardViewMediator( 2579): in doKeyguardLocked mIsRollUp false null
D/PersonaManager( 2579): isKioskContainerExistOnDevice
D/LockPatternUtils( 2579): isPcwEnable = 10
D/LockPatternUtils( 2579): isPcwEnable = 10
D/KeyguardViewMediator( 2579): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService( 2419): [PWL] Off : 5s ago
I/PowerManagerService( 2419): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2419): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2419): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService' (uid=10031, pid=5100, ws=null) (elapsedTime=491)
,D/dalvikvm( 5886): GC_EXPLICIT freed 882K, 27% free 10003K/13624K, paused 3ms+10ms, total 49ms
,D/dalvikvm( 2829): GC_EXPLICIT freed 338K, 25% free 10308K/13716K, paused 4ms+7ms, total 46ms
,D/PackageManager( 2419): [MSG] MCS_UNBIND
,I/PackageManager( 2419): calling disconnectService()
,D/PackageManager( 2419): Trying to unbind to DefaultContainerService
,I/ActivityManager( 2419): Killing 5362:com.policydm/1000 (adj 15): empty #43
,D/dalvikvm( 2419): GC_EXPLICIT freed 807K, 12% free 24412K/27688K, paused 8ms+16ms, total 206ms
,V/AlarmManager( 2419): waitForAlarm result :8
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5886): GC_EXPLICIT freed 867K, 27% free 10013K/13624K, paused 4ms+8ms, total 45ms
,D/dalvikvm( 2829): GC_EXPLICIT freed 363K, 25% free 10301K/13716K, paused 4ms+6ms, total 47ms
,I/dalvikvm( 2419): Jit: resizing JitTable from 8192 to 16384
,D/dalvikvm( 5886): GC_EXPLICIT freed 874K, 27% free 10011K/13624K, paused 4ms+9ms, total 45ms
,D/dalvikvm( 2829): GC_EXPLICIT freed 349K, 25% free 10307K/13716K, paused 5ms+7ms, total 46ms
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 360, Delta = -10
,D/dalvikvm( 5886): GC_EXPLICIT freed 872K, 27% free 10010K/13624K, paused 3ms+9ms, total 45ms
,D/dalvikvm( 2829): GC_EXPLICIT freed 353K, 25% free 10314K/13716K, paused 4ms+7ms, total 48ms
,D/dalvikvm( 2419): GC_EXPLICIT freed 348K, 12% free 24402K/27688K, paused 8ms+14ms, total 203ms
,D/dalvikvm( 5886): GC_EXPLICIT freed 872K, 27% free 10008K/13624K, paused 3ms+8ms, total 44ms
,D/dalvikvm( 2829): GC_EXPLICIT freed 352K, 25% free 10323K/13716K, paused 4ms+7ms, total 48ms
,D/AmoledAdjustTimer( 2419): prevTemp = 311, currTemp = 312, prevStep = 4, currStep = 4
,D/dalvikvm( 5886): GC_CONCURRENT freed 1471K, 23% free 10493K/13624K, paused 2ms+9ms, total 35ms
,I/SettingSearch/SearchIntentReceiver( 2829): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2829): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 2829): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 2829): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2829): LOCALE_CHANGED call search setting db finish!!
,I/PowerManagerService( 2419): [PWL] Off : 15s ago
,V/AlarmManager( 2419): waitForAlarm result :4,
,D/Headlines( 5444): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5444): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5444): Breath 40986 latestRequest time : 1455021487742 current time : 1455021528729,
,D/Finsky  ( 5100): [382] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5100): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 350, Delta = -10,
,E/Watchdog( 2419): !@Sync 3,
,D/AmoledAdjustTimer( 2419): prevTemp = 312, currTemp = 312, prevStep = 4, currStep = 4,
,I/Icing   ( 3143): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music,
,I/Icing   ( 3143): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK,
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___,
,V/AlarmManager( 2419): <AppSync3 Whitelist>,
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 6245
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2419): stay LED for fully charged,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2419): [PWL] Off : 30s ago,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 340, Delta = -10,
,V/AlarmManager( 2419): waitForAlarm result :4,
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/FactoryTest( 5175): Not factory mode,
,D/FactoryTest( 5175): Not factory mode. isFactoryMode() returend false,
D/MTPRx   ( 5175): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5175): still no open session command from host, so toast,
W/ContextImpl( 5175): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5175): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4,
,W/ActivityManager( 2419): mDVFSHelper.acquire(),
I/SurfaceFlinger( 1919): id=17 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1919): id=18 createSurf (16x16),-1 flag=20004, EimLayer
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1,
I/SQLiteSecureOpenHelper( 3540): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3540): getDatabaseLocked(b,b,pwd)...
,E/MTPRx   ( 5175): started activity for popup,
,E/SettingsReceiverActivity( 5175): PREF_DONT_ASK_AGAIN : true,
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false,
D/StatusBarManagerService( 2419): tr p:2774,o:f
D/StatusBarManagerService( 2419): semi p:2774,o:f
,W/InputMethodManagerService( 2419): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@437c6668 attribute=android.view.inputmethod.EditorInfo@4341ae80, token = android.os.BinderProxy@42ad4fe8
,D/SettingsReceiverActivity( 5175): dev.kiessupport is : TRUE
,D/AmoledAdjustTimer( 2419): prevTemp = 312, currTemp = 310, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2419): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 340, Delta = 0,
,I/SurfaceFlinger( 1919): id=18 Removed EimLayer (5/10),
I/SurfaceFlinger( 1919): id=18 Removed EimLayer (-2/10)
I/SurfaceFlinger( 1919): id=17 Removed EimLayer (4/9),
,I/SurfaceFlinger( 1919): id=17 Removed EimLayer (-2/9),
,D/AmoledAdjustTimer( 2419): prevTemp = 310, currTemp = 310, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 50s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = -10
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5444): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5444): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5444): Breath 73933 latestRequest time : 1455021487742 current time : 1455021561675
,I/VacuumService( 2734): Vacuum at: now=1455021561895 tag=VacuumService
,E/Watchdog( 2419): !@Sync 4
,D/AmoledAdjustTimer( 2419): prevTemp = 310, currTemp = 310, prevStep = 4, currStep = 4,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 310, currTemp = 309, prevStep = 4, currStep = 4,
,V/AlarmManager( 2419): waitForAlarm result :8,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/Headlines( 5444): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5444): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5444): Breath 90037 latestRequest time : 1455021487742 current time : 1455021577779,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2419): stay LED for fully charged,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 309, currTemp = 308, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2419): [PWL] Off : 75s ago,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0,
,E/Watchdog( 2419): !@Sync 5,
,D/AmoledAdjustTimer( 2419): prevTemp = 308, currTemp = 307, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 307, currTemp = 307, prevStep = 4, currStep = 4,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 307, currTemp = 306, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2419): [PWL] Off : 105s ago,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/AlarmManager( 2419): waitForAlarm result :4,
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5444): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
D/Headlines( 5444): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 5444): Breath 133959 latestRequest time : 1455021487742 current time : 1455021621701
,D/Headlines( 5444): stop ,
,D/Headlines( 5444): Breath.onDestroy : ,
,I/ActivityManager( 2419): Killing 5400:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43,
,I/PhenotypeConfigurator( 2734): Scheduling Phenotype for one-off execution 12204 seconds from now (1455021622052),
,D/GetConfigurationSnapshotOperation( 2734): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, ,
,I/PhenotypeFlagCommitter( 2734): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 2734): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2734): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2734): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2734): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 2419): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 2734): Thread-115(HTTPLog):isShipBuild true
,I/System.out( 2734): Thread-115(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 2734): GC_CONCURRENT freed 1656K, 20% free 11838K/14624K, paused 8ms+7ms, total 70ms
,E/Watchdog( 2419): !@Sync 6
,D/LocationManagerService( 2419): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2419): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/AmoledAdjustTimer( 2419): prevTemp = 306, currTemp = 305, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2419): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 7,
,D/AmoledAdjustTimer( 2419): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = -10,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2419): !@Sync 8,
,D/AmoledAdjustTimer( 2419): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2419): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2419): !@Sync 9,
,D/AmoledAdjustTimer( 2419): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/dalvikvm( 2419): GC_CONCURRENT freed 3488K, 17% free 24559K/29240K, paused 15ms+16ms, total 238ms,
,D/AmoledAdjustTimer( 2419): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2419): [PWL] Off : 225s ago,
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2419): initializing...,
I/TLC_TIMA_PKM_initialize( 2419): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2419): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2419): input max_recvmsg_size = 262196,
,I/TZ: mc_tlc_communication( 2419): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2419): aligned max_sendmsg_size = 262208,
I/TZ: mc_tlc_communication( 2419): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2419): device_id = 0x0
I/TZ: mc_tlc_communication( 2419): tlc_open() was called,
,I/TZ: mc_tlc_communication( 2419): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2419): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2419): Opening the session
,I/TZ: mc_tlc_communication( 2419): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2419): Trustlet response is completed,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 6906,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2419): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;,
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/AmoledAdjustTimer( 2419): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,V/AlarmManager( 2419): waitForAlarm result :4,
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 6987): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6987):  
,I/SELinux ( 6987): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6987):  
I/SELinux ( 6987):  
,I/SELinux ( 6987): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6987): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6987): >>>>> Normal User
,E/dalvikvm( 6987): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 6987): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6987): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 6987): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 6987): Added TimaKesytore provider,
,D/dalvikvm( 6987): GC_CONCURRENT freed 3004K, 30% free 9567K/13632K, paused 4ms+2ms, total 29ms,
,D/dalvikvm( 6987): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/ActivityManager( 2419): Killing 5457:com.google.android.apps.magazines/u0a115 (adj 15): empty #43,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2419): !@Sync 11,
,D/AmoledAdjustTimer( 2419): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 275s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2419): !@Sync 12
,D/AmoledAdjustTimer( 2419): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/DBG_DM  ( 4270): [3.19.140541][Line:666][onReceive] FotaPostpone callback received
,I/DBG_DM  ( 4270): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 3
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
,D/NotificationService( 2419): cancelNotificationLocked
,D/NotificationService( 2419):  hasClearableItems
,D/STATUSBAR-StatusBarManagerService( 2419): sendNotification(3) - 3
D/NotificationService( 2419):  has clearable items no 
D/NotificationService( 2419): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2419): cancelNotificationLocked: cancel alarm
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/LightsService( 2419): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2419) 
D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/Sensors ( 2419): LightSensor setDelay = 200000000
,D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
,D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,I/DBG_DM  ( 4270): [3.19.140541][Line:5174][xdbSetDownloadPostponeStatus] Set Download Postpone status : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4270): [3.19.140541][Line:369][handleMessage] event ->214
,I/DBG_DM  ( 4270): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.android.launcher2.Launcher
,I/DBG_DM  ( 4270): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,I/DBG_DM  ( 4270): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 4270): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,W/ContextImpl( 4270): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
E/DBG_DM  ( 4270): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
E/DBG_DM  ( 4270): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@42a0a800
,I/DBG_DM  ( 4270): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : true
,I/DBG_DM  ( 4270): [3.19.140541][Line:2047][xdmCallUiDialogActivity] UI_id:219
,W/ContextImpl( 4270): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 com.wssyncmldm.XDMService.xdmCallUiDialogActivity:2053 com.wssyncmldm.XDMService.access$300:81 com.wssyncmldm.XDMService$1.handleMessage:349 
,W/ContextImpl( 4270): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 com.wssyncmldm.XDMService.xdmCallUiDialogActivity:2053 com.wssyncmldm.XDMService.access$300:81 
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2419): mDVFSHelper.acquire()
I/SurfaceFlinger( 1919): id=19 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1919): id=20 createSurf (16x16),-1 flag=20004, EimLayer
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
I/SQLiteSecureOpenHelper( 3540): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3540): getDatabaseLocked(b,b,pwd)...
,I/DBG_DM  ( 4270): [3.19.140541][Line:2096][onResume] 
,I/DBG_DM  ( 4270): [3.19.140541][Line:2137][xuiDlgShow] id 219
,I/dalvikvm( 4270): Total arena pages for JIT: 18
,I/DBG_DM  ( 4270): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 49
,I/DBG_DM  ( 4270): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.acquire()
,I/DBG_DM  ( 4270): [3.19.140541][Line:250][xuiDownloadProgressInit] 
,D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2419): semi p:4270,o:f
I/DBG_DM  ( 4270): [3.19.140541][Line:2088][onPause] 
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 12
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
V/WindowManager( 2419): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,I/DBG_DM  ( 4270): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 49
,I/DBG_DM  ( 4270): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/SurfaceFlinger( 1919): id=9 Removed Mauncher (8/10)
,I/SurfaceFlinger( 1919): id=9 Removed Mauncher (-2/10)
,D/Launcher( 2774): onTrimMemory. Level: 20
,I/DBG_DM  ( 4270): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:76][onCreate] Postpone Count : 49
,E/MoreInfoHPW_ViewGroup( 4270): Parent view is not a TextView
,D/checkbox( 4270): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4270): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4270): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4270): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,I/DBG_DM  ( 4270): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4270): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2419): sendNotification(1) - 4
,I/DBG_DM  ( 4270): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 49
,D/ProgressBar( 2579): setProgressDrawable drawableHeight = 12
,I/DBG_DM  ( 4270): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,D/ProgressBar( 2579): setProgressDrawable drawableHeight = 12
,I/DBG_DM  ( 4270): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/PhoneStatusBar( 2579): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@42922ca8
,I/DBG_DM  ( 4270): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 49
,I/DBG_DM  ( 4270): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/DBG_DM  ( 4270): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 49
,I/DBG_DM  ( 4270): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,I/DBG_DM  ( 4270): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4270): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 49
,I/DBG_DM  ( 4270): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:418][onResume] Postpone Count : 49
,I/DBG_DM  ( 4270): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4270): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2419): sendNotification(2) - 4
,I/DBG_DM  ( 4270): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 49
,I/DBG_DM  ( 4270): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4270): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,I/DBG_DM  ( 4270): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4270): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4270): setTransGradationMode to true
,D/PhoneStatusBar( 2579): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2419): semi p:4270,o:t
E/SPPClientService( 5080): [b] __PingReply__
,I/DBG_DM  ( 4270): [3.19.140541][Line:400][onPause] 
,I/DBG_DM  ( 4270): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4270): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 49
,I/DBG_DM  ( 4270): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:418][onResume] Postpone Count : 49
,I/DBG_DM  ( 4270): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4270): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2419): sendNotification(2) - 4
,I/DBG_DM  ( 4270): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 49
,I/DBG_DM  ( 4270): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4270): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4270): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,I/DBG_DM  ( 4270): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4270): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4270): setTransGradationMode to true
D/PhoneStatusBar( 2579): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4270): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2419): semi p:4270,o:t
,D/checkbox( 4270): TwCheckBox.onAttachedToWindow()
,D/PhoneStatusBar( 2579): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2419): semi p:4270,o:t
,I/SurfaceFlinger( 1919): id=21 createSurf (1x1),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2419): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/IInputConnectionWrapper( 4270): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2419): !@Sync 13
,D/AmoledAdjustTimer( 2419): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2419): !@Sync 14
,D/AmoledAdjustTimer( 2419): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2419): !@Sync 15
,D/AmoledAdjustTimer( 2419): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2579): GC_CONCURRENT freed 15673K, 34% free 33911K/50640K, paused 13ms+9ms, total 104ms
,I/PowerManagerService( 2419): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2419): !@Sync 16
,D/AmoledAdjustTimer( 2419): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2419): !@Sync 17
,D/AmoledAdjustTimer( 2419): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 455s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2419): !@Sync 18
,D/AmoledAdjustTimer( 2419): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_FOR_ALLOC freed 2900K, 17% free 24567K/29468K, paused 200ms, total 200ms
E/Watchdog( 2419): !@Sync 19
D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 525s ago
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 20
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 21
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,I/GAV2    ( 5191): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5191): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 22
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 23
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 24
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 680s ago
,E/Watchdog( 2419): !@Sync 25
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 3797): GC_CONCURRENT freed 2886K, 30% free 9689K/13668K, paused 8ms+7ms, total 48ms
,D/dalvikvm( 3797): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 26
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 27
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2774): GC_CONCURRENT freed 5831K, 26% free 19845K/26736K, paused 9ms+8ms, total 81ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 765s ago
,E/Watchdog( 2419): !@Sync 28
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/dalvikvm( 2419): GC_FOR_ALLOC freed 2518K, 17% free 24553K/29488K, paused 199ms, total 199ms
D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 29
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 30
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 855s ago
,E/Watchdog( 2419): !@Sync 31
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/ConnectivityService( 2419): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2579): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2579): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2579): updateDataNetType()
,D/STATUSBAR-NetworkController( 2579): NoService, mRoamingIconId = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 32
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,E/SPPClientService( 5080): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,V/AlarmManager( 2419): waitForAlarm result :8
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 8
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 33
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 950s ago
,E/Watchdog( 2419): !@Sync 34
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 35
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 36
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 37
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_FOR_ALLOC freed 2564K, 17% free 24556K/29488K, paused 198ms, total 199ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 38
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 39
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 40
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1155s ago
,E/Watchdog( 2419): !@Sync 41
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 42
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5080): [b] __PingReply__
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1200000ms),D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
D/AndroidRuntime( 9308): 
D/AndroidRuntime( 9308): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 9308): CheckJNI is OFF
D/AndroidRuntime( 9308): setted country_code = Poland
D/AndroidRuntime( 9308): setted countryiso_code = PL
D/AndroidRuntime( 9308): setted sales_code = PLS
D/AndroidRuntime( 9308): readGMSProperty: start
D/AndroidRuntime( 9308): readGMSProperty: already setted!!
D/AndroidRuntime( 9308): readGMSProperty: end
D/AndroidRuntime( 9308): addProductProperty: start
D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
D/dalvikvm( 9308): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 9308): Added shared lib libjavacore.so 0x0
D/dalvikvm( 9308): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 9308): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 9308): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 9308): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 9308): failed to load memtrack module: -2
D/dalvikvm( 9308): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 9308): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2419): START PACKAGE DELETE: observer{1128529920}
D/PackageManager( 2419): pkg{<packageName>}
D/PackageManager( 2419): user{0}
D/PackageManager( 2419): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2419): getApplicationUninstallationEnabled
D/PackageManager( 2419): [MSG] DELETE_PACKAGE_AS_USER
D/ApplicationPolicy( 2419): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2419): deletePackageX- pkg:com.test.thalitest, userId:0
D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 1ms
D/dalvikvm( 2419): GC_EXPLICIT freed 1352K, 17% free 24551K/29488K, paused 7ms+14ms, total 175ms
D/AndroidRuntime( 9308): Shutting down VM
D/PackageManager( 2419): return delete result to caller: 1128529920
D/PackageManager( 2419): returnCode: -1
D/dalvikvm( 9308): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 4ms
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :

```
