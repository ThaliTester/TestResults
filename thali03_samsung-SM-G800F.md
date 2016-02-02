#### Test 575312438097721_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 2831): GC_EXPLICIT freed 358K, 25% free 10300K/13688K, paused 4ms+8ms, total 51ms
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/qtaguid ( 5084): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5084): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5084): untagSocket(68) failed with errno -22
I/System.out( 5084): Thread-367 calls detatch()
--------- beginning of /dev/log/system
D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
D/AndroidRuntime( 6100): 
D/AndroidRuntime( 6100): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6100): CheckJNI is OFF
D/AndroidRuntime( 6100): setted country_code = Poland
D/AndroidRuntime( 6100): setted countryiso_code = PL
D/AndroidRuntime( 6100): setted sales_code = PLS
D/AndroidRuntime( 6100): readGMSProperty: start
D/AndroidRuntime( 6100): readGMSProperty: already setted!!
D/AndroidRuntime( 6100): readGMSProperty: end
D/AndroidRuntime( 6100): addProductProperty: start
D/dalvikvm( 6100): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6100): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6100): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6100): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6100): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6100): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6100): failed to load memtrack module: -2
D/dalvikvm( 6100): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6100): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 6100): Shutting down VM
D/dalvikvm( 6100): GC_CONCURRENT freed 99K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
D/Finsky  ( 5084): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager( 2419): waitForAlarm result :4
V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/WearableService( 2734): callingUid 10012, callindPid: 2734
,D/Finsky  ( 5084): [390] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 2734): client connected with version: 8296000
,D/Finsky  ( 5084): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5084): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/dalvikvm( 2850): GC_EXPLICIT freed 958K, 21% free 10803K/13616K, paused 5ms+8ms, total 72ms
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5084): Thread-377(HTTPLog):isShipBuild true
,I/System.out( 5084): Thread-377(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 5878): GC_EXPLICIT freed 885K, 27% free 10008K/13640K, paused 3ms+9ms, total 45ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 355K, 25% free 10298K/13688K, paused 4ms+7ms, total 47ms
,D/dalvikvm( 5878): GC_EXPLICIT freed 873K, 27% free 10012K/13640K, paused 3ms+9ms, total 45ms
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 2831): GC_EXPLICIT freed 345K, 25% free 10306K/13688K, paused 5ms+7ms, total 49ms
,V/AlarmManager( 2419): waitForAlarm result :8
,D/dalvikvm( 2419): GC_EXPLICIT freed 800K, 13% free 24403K/27804K, paused 8ms+14ms, total 211ms
,D/dalvikvm( 5878): null clazz in OP_INSTANCE_OF, single-stepping
,D/dalvikvm( 5878): GC_EXPLICIT freed 875K, 27% free 10009K/13640K, paused 3ms+9ms, total 44ms
D/dalvikvm( 2831): GC_EXPLICIT freed 343K, 25% free 10310K/13688K, paused 4ms+8ms, total 46ms
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4355, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 5878): GC_EXPLICIT freed 871K, 27% free 10008K/13640K, paused 3ms+9ms, total 45ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 356K, 25% free 10316K/13688K, paused 4ms+7ms, total 46ms
,D/PackageManager( 2419): [MSG] MCS_UNBIND
,I/PackageManager( 2419): calling disconnectService()
,D/PackageManager( 2419): Trying to unbind to DefaultContainerService
,I/ActivityManager( 2419): Killing 5207:com.vlingo.midas/u0a34 (adj 15): empty #43
,D/dalvikvm( 5878): GC_EXPLICIT freed 874K, 27% free 10005K/13640K, paused 4ms+8ms, total 45ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 340, Delta = -10
,D/dalvikvm( 2831): GC_EXPLICIT freed 362K, 25% free 10325K/13688K, paused 5ms+7ms, total 47ms
,D/dalvikvm( 2419): GC_EXPLICIT freed 357K, 13% free 24385K/27804K, paused 7ms+16ms, total 207ms
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 295, prevStep = 4, currStep = 4
,D/dalvikvm( 5878): GC_CONCURRENT freed 1476K, 24% free 10493K/13640K, paused 3ms+10ms, total 40ms
,I/SettingSearch/SearchIntentReceiver( 2831): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2831): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 2831): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 2831): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2831): LOCALE_CHANGED call search setting db finish!!
,V/AlarmManager( 2419): waitForAlarm result :4,
,D/Headlines( 5435): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5435): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5435): Breath 40305 latestRequest time : 1454429695146 current time : 1454429735451,
,D/Finsky  ( 5084): [379] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5084): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 3
,I/PowerManagerService( 2419): [PWL] Off : 50s ago,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = -10,
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,I/Icing   ( 3139): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music
,I/Icing   ( 3139): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2419): level:100, scale:100, status:3, health:9, present:true, voltage: 4362, temperature: 294, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/lights  ( 2419): led_pattern : 0 +,
D/LightsService( 2419): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 2419): turn off LED
D/LightsService( 2419): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK,
,D/lights  ( 2419): led_pattern : 0 -,
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/UsbDeviceManager( 2419): handleMessage -> MSG_POWER_STATE = 0,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/PowerManagerService( 2419): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2419): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2419): Waking up from sleep...
,D/PowerManagerService( 2419): Screen Readiness Inspection requested: mNestCount=1
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/PowerManagerService( 2419): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2419): [s] WAKEFULNESS_AWAKE
,D/PowerManagerService( 2419): [s] UserActivityState : 0 -> 1
,D/lights  ( 2419): button : 1 +
D/PowerUI ( 2579): Overvoltage/Undervoltage (recovered) so turn on the screen.
I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
,D/lights  ( 2419): button : 1 -
D/PowerManagerService( 2419): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 2419): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2419): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/PowerManagerService( 2419): [api] [s] wakeUp (uid: 10019 pid: 2579) eventTime = 116336
D/DisplayPowerController( 2419): [DAB] setLightSensorEnabled : registerListener mLightSensor
I/DisplayPowerController( 2419): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2419): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2419): [DAB] no lux value from sensor manager
,D/DisplayPowerController( 2419): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 1
,D/PowerManagerService( 2419): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 11ms
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
D/PowerManagerService( 2419): unblankAllDisplays() is called.
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
,I/libsuspend( 2419): !@[s] autosuspend_autosleep_disable
I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 65558
I/libsuspend( 2419): !@[s] autosuspend_autosleep_disable done
,I/Sensors ( 2419): HAL: batch Dry Run is complete
,D/SurfaceFlinger( 1920): Screen acquired, type=0 flinger=0x408d1550
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
,D/PowerManagerService( 2419): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
I/Sensors ( 2419): HAL:resetDataRates mEnabled=4
,D/SensorManager( 2419): registerListener :: 2, MPL Accelerometer, 200000, 0,  
,D/SensorService( 2419): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2419): AutoRotationSensor::activate (ident=0x7b23e7b0, enabled=1)
D/SensorService( 2419): AutoRotationSensor::AR_init
,I/Sensors ( 2419): HAL: batch Dry Run is complete
D/RampAnimator( 2419): Light Animator Finished currentValue=8
D/PowerManagerService( 2419): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 23ms
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
I/Sensors ( 2419): HAL:resetDataRates mEnabled=4
I/SELinux ( 6252): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6252):  
,D/UsbDeviceManager( 2419): sending intent : ACTION_USB_CABLE_STATE : connected = false
,D/SensorManager( 2419): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
D/NotificationService( 2419): cancelNotificationLocked
D/NotificationService( 2419):  hasClearableItems
D/NotificationService( 2419):  has clearable items no 
D/NotificationService( 2419): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2419): cancelNotificationLocked: cancel alarm
D/STATUSBAR-StatusBarManagerService( 2419): sendNotification(3) - 5
,V/KeyguardServiceDelegate( 2419): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@42febc80)
D/LightsService( 2419): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2419) 
D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/UsbDeviceManager( 2419): received ACTION_POWER_DISCONNECTED = -1
D/LightsService( 2419): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/InputDispatcher( 2419): setInputDispatchMode: enabled=1, frozen=0
D/KeyguardViewMediator( 2579): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 2579): notifyScreenOnLocked
D/KeyguardViewMediator( 2579): handleNotifyScreenOn
,D/KeyguardViewManager( 2579): onScreenTurnedOn()
,I/KeyguardEffectViewMain( 2579): *** KeyguardEffectView getInstance ***
V/KeyguardServiceDelegate( 2419): **** SHOWN CALLED ****
V/KeyguardViewManager( 2579): send wm null token: host was null
,D/VisualEffectParticleEffect( 2579): KeyguardEffectViewParticleSpace : screenTurnedOn
,D/VisualEffectParticleEffect( 2579): screenOnAnimationStart
,D/LockPatternUtils( 2579): isPcwEnable = 10
I/WindowManager( 2419): No lock screen! windowToken=null
D/PowerManagerNotifier( 2419): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2419): Screen Readiness Inspection completed: mNestCount=0
,I/SurfaceFlinger( 1920): id=14 Removed FlectronBea (10/10)
,I/SurfaceFlinger( 1920): id=14 Removed FlectronBea (-2/10)
D/DisplayPowerController( 2419): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2419): !@ElectronBeam exit
D/lights  ( 2419): lcd : 8 +
,D/lights  ( 2419): lcd : 8 -
D/DisplayPowerController( 2419): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2419): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/BatteryMeterView( 2579): onDraw batteryColor : -1
,I/SELinux ( 6252): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6252):  
I/SELinux ( 6252):  
,I/SELinux ( 6252): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6252): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6252): >>>>> Normal User
,E/dalvikvm( 6252): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 6252): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6252): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6252): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6252): Added TimaKesytore provider
,D/SensorService( 2419): AutoRotationSensor::process: Acc  eventTimestamp = 116450456224, previousAccTimestamp = 58790887746, difference = 57659568478 
,D/SensorService( 2419): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/DisplayPowerController( 2419): [api] [DAB] onSensorChanged : 1st lux : 0.0
,D/DisplayPowerController( 2419): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,D/SensorService( 2419): AutoRotationSensor::process: Acc  eventTimestamp = 116517119105, previousAccTimestamp = 58790887746, difference = 57726231359 
D/SensorService( 2419):  [AR] 0.2 -0.0 9.8
,D/SensorService( 2419): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/SurfaceControl( 2419): Excessive delay in unblankDisplay() while turning screen on: 245ms
,D/MISC PowerHAL( 2419): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2419): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2419): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 246ms
,D/LockPatternUtils( 2579): isPcwEnable = 10
,D/MISC PowerHAL( 2419): sysfs_write -: /sys/class/input/input1/enabled: 1
,D/MISC PowerHAL( 2419): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2419): sysfs_write +: /sys/class/input/input0/enabled: 1
,I/DBG_DM  ( 4232): [3.19.140541][Line:408][onResume] 
,D/LightsService( 2419): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2419) 
,D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2419): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/SamsungIME( 2947): showDlgMsgBox : false true true
D/PalmMotionService( 2419): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PalmMotionService( 2419): SURFACE_PALM_SWIPE: 1
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
E/MotionRecognitionService( 2419):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/SSRMv2:TSP:AirViewOnOff( 2419): SettingsAirViewInfo:: 000000000
,I/FPMS_FingerprintManagerService( 2599): onReceive: android.intent.action.USER_PRESENT
,I/NfcService( 2755): applyRouting return - 2 
,E/NfcService( 2755): callback == null
,I/DBG_DM  ( 4232): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 35
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,I/DBG_DM  ( 4232): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
D/STATUSBAR-NotificationService( 2419): ACTION_SCREEN_ON
D/LightsService( 2419): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2419) 
D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2419): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=on)
,I/SecExternalDisplayIntents_Java( 2419): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,I/DBG_DM  ( 4232): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4232): [3.19.140541][Line:418][onResume] Postpone Count : 35
,D/IpRemoteDisplayController( 2419): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2419): Bridge Server is not available
,D/MISC PowerHAL( 2419): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2419): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2419): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2419): Excessive delay in MISC setInteractive(true) while turning screen on: 163ms
D/SEC PowerHAL( 2419): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2419): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2419): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2419): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2419): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2419): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2419): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2419): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/PersonaManagerService( 2419): ACTION_SCREEN_ON onReceive
D/PowerManagerService( 2419): Excessive delay in nativeSetInteractive(true): 164ms
,D/PowerManagerService( 2419): SecHardwareInterface.setBatteryADC : true
D/PersonaManagerServiceHandler( 2419): MSG_ACTION_SCREEN_ON called
I/DBG_DM  ( 4232): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
I/NfcService( 2755): NFC: Screen On & Cover Open
I/NfcService( 2755): applyRouting return - 2 
,E/NfcService( 2755): callback == null
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 6252): GC_CONCURRENT freed 2994K, 30% free 9566K/13640K, paused 6ms+7ms, total 52ms
,D/dalvikvm( 6252): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/STATUSBAR-NetworkController( 2579): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,I/DBG_DM  ( 4232): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4232): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/SELinux ( 6269): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6269):  
I/ActivityManager( 2419): Killing 5349:com.policydm/1000 (adj 15): empty #43
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2419): sendNotification(2) - 4
,I/DBG_DM  ( 4232): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 35
,I/DBG_DM  ( 4232): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/SELinux ( 6269): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6269):  
I/SELinux ( 6269):  
,I/SELinux ( 6269): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6269): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6269): >>>>> Normal User
,E/dalvikvm( 6269): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
,I/DBG_DM  ( 4232): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,E/SELinux ( 6269): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/DBG_DM  ( 4232): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4232): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4232): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4232): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4232): setTransGradationMode to true
,D/PhoneStatusBar( 2579): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2419): semi p:4232,o:t
,D/TimaKeyStoreProvider( 6269): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6269): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6269): Added TimaKesytore provider
,D/dalvikvm( 6269): GC_CONCURRENT freed 3003K, 30% free 9564K/13644K, paused 2ms+1ms, total 23ms
,D/dalvikvm( 6269): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/KIES_RECEIVE( 6269): [APK BnR] Receive KIES_USB_DISCONNECT
W/ContextImpl( 6269): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
,E/TranscodeReceiver( 5874): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,D/videowall-Global( 5874): core_num = 4
,D/dalvikvm( 5874): No JNI_OnLoad found in /system/lib/libsavsff.so 0x42277c88, skipping init
,W/linker  ( 5874): libvwengine.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/videowall-Global( 5874): density : 2.0 width : 720 height : 1280 Raw width : 720 Raw height : 1280
,D/videowall-Global( 5874): dsp : 720, swkey : false, Cores : 4, Clock : 0
,I/SELinux ( 6281): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6281):  
,I/SELinux ( 6281): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6281):  
I/SELinux ( 6281):  
,I/SELinux ( 6281): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6281): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 6281): >>>>> Normal User
,E/dalvikvm( 6281): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 6281): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0
,D/TimaKeyStoreProvider( 6281): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6281): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6281): Added TimaKesytore provider
,D/QuickConnect[1.1][2] ( 4649): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
,V/QuickConnect[1.1][2] ( 4649): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4649): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4649): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228a1b0
V/QuickConnect[1.1][2] ( 4649): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228a1b0
V/QuickConnect[1.1][2] ( 4649): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 4649): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228a1b0
V/QuickConnect[1.1][2] ( 4649): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228a1b0
V/QuickConnect[1.1][2] ( 4649): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228a1b0
,D/QuickConnect[1.1][2] ( 4649): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 4649): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 4649): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 4649): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4851): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,D/PowerManagerService( 2419): [PWL] sb release: PowerManagerService.Broadcasts
,D/dalvikvm( 6281): GC_CONCURRENT freed 3001K, 30% free 9564K/13644K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 6281): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/SELinux ( 6297): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6297):  
I/ActivityManager( 2419): Killing 5387:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43
,D/dalvikvm( 1921): GC_EXPLICIT freed 44K, 11% free 9501K/10624K, paused 3ms+3ms, total 29ms
I/SELinux ( 6297): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6297):  
I/SELinux ( 6297):  
,I/SELinux ( 6297): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6297): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6297): >>>>> Normal User
,E/dalvikvm( 6297): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
,E/SELinux ( 6297): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 6297): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6297): Cannot add TimaSignature Service, License check Failed
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9501K/10624K, paused 4ms+3ms, total 26ms
,D/ActivityThread( 6297): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9501K/10624K, paused 3ms+3ms, total 24ms
,D/dalvikvm( 6297): GC_CONCURRENT freed 3016K, 30% free 9556K/13648K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 6297): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/FactoryTest( 5159): Not factory mode
,D/FactoryTest( 5159): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 5159): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5159): still no open session command from host, so toast
W/ContextImpl( 5159): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5159): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2419): mDVFSHelper.acquire()
,I/DBG_DM  ( 4232): [3.19.140541][Line:359][onUserLeaveHint] 
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
I/SQLiteSecureOpenHelper( 3539): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3539): getDatabaseLocked(b,b,pwd)...
,E/MTPRx   ( 5159): started activity for popup
,I/DBG_DM  ( 4232): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 35
,I/iu.Environment( 5499): update battery state; isPlugged? false*
,I/DBG_DM  ( 4232): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/iu.SyncManager( 5499): SYNC; picasa accounts
,I/ActivityManager( 2419): Killing 5447:com.google.android.apps.magazines/u0a115 (adj 15): empty #43
,I/iu.Environment( 3139): update battery state; isPlugged? false*
,I/DBG_DM  ( 4232): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4232): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,I/DBG_DM  ( 4232): [3.19.140541][Line:362][onUserLeaveHint] Home Key!!
,I/DBG_DM  ( 4232): [3.19.140541][Line:315][xuiFotaPostponeDefault] 
,I/iu.UploadsManager( 3139): num queued entries: 0
,I/iu.UploadsManager( 3139): num updated entries: 0
,I/iu.SyncManager( 3139): NEXT; no task
,I/GCoreUlr( 2734): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,D/PicasaUploader( 6297):    wifiOnlyPhoto changed to true
D/PicasaUploader( 6297):    wifiOnlyVideo changed to true
,D/PicasaUploader( 6297):    syncOnBattery changed to true
,I/iu.UploadsManager( 5499): num queued entries: 0
,I/GCoreUlr( 2734): DispatchingService.onCreate()
,I/iu.UploadsManager( 5499): num updated entries: 0
,I/DBG_DM  ( 4232): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/iu.SyncManager( 5499): NEXT; no task
,D/PicasaUploaderSync( 6297): sync account database
,D/PicasaUploaderSync( 6297): accounts in DB=1
,D/PicasaUploaderSyncManager( 6297): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PicasaUploaderSyncManager( 6297): background data: true
,D/PicasaUploaderSyncManager( 6297): battery info: false
,I/DBG_DM  ( 4232): [3.19.140541][Line:5174][xdbSetDownloadPostponeStatus] Set Download Postpone status : 3
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,I/DBG_DM  ( 4232): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 3 / Notification IndicatorState : 3
,D/NotificationService( 2419): cancelNotificationLocked
D/NotificationService( 2419):  hasClearableItems
D/NotificationService( 2419):  has clearable items no 
,D/NotificationService( 2419): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2419): cancelNotificationLocked: cancel alarm
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
D/STATUSBAR-StatusBarManagerService( 2419): sendNotification(3) - 4
D/LightsService( 2419): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2419) 
D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2419): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,I/DBG_DM  ( 4232): [3.19.140541][Line:3638][xdbSetFUMOStatus] FUMO_Status : 220
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2419): sendNotification(1) - 3
,I/DBG_DM  ( 4232): [3.19.140541][Line:368][xuiFotaPostponeDefault] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
,I/DBG_DM  ( 4232): [3.19.140541][Line:503][xuiFotaPostponeStartTimer] 
,I/DBG_DM  ( 4232): [3.19.140541][Line:400][onPause] 
,D/LockPatternUtils( 2579): isPcwEnable = 10
,D/ProgressBar( 2579): setProgressDrawable drawableHeight = 12
,I/GCoreUlr( 2734): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/PhoneStatusBar( 2579): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@4229aca0
D/Launcher( 2773): onRestart, Launcher: 1113874168
D/Launcher( 2773): onStart, Launcher: 1113874168
D/Launcher.HomeView( 2773): onStart
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/SurfaceFlinger( 1920): id=19 createSurf (720x1280),1 flag=4, Mauncher
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/lights  ( 2419): button : 0 +
,D/lights  ( 2419): button : 0 -
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
V/WindowOrientationListener( 2419): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowOrientationListener( 2419): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/comsamsunglog( 4851): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4851): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4851): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4851): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,V/WindowManager( 2419): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/SettingsReceiverActivity( 5159): PREF_DONT_ASK_AGAIN : true
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454433900000
,D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,I/SQLiteSecureOpenHelper( 3539): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3539): getDatabaseLocked(b,b,pwd)...
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454429749010
,D/StatusBarManagerService( 2419): tr p:2773,o:f
D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): semi p:2773,o:f
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,I/GCoreUlr( 2734): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/SettingsReceiverActivity( 5159): dev.kiessupport is : TRUE
,I/GCoreUlr( 2734): Unbound from all location providers
,I/GCoreUlr( 2734): Place inference reporting - stopped
,D/SSRMv2:TSP:AirViewOnOff( 2419): SettingsAirViewInfo:: 000000000
,D/Launcher( 2773): onResume, Launcher: 1113874168
,D/StatusBarManagerService( 2419): semi p:2773,o:f
,D/Launcher.HomeView( 2773): onResume
D/StatusBarManagerService( 2419): tr p:2773,o:f
D/StatusBarManagerService( 2419): semi p:2773,o:f
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(47)
,D/dalvikvm( 4851): GC_CONCURRENT freed 2591K, 27% free 10082K/13672K, paused 10ms+13ms, total 90ms
D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
I/GCoreUlr( 2734): DispatchingService.onDestroy()
,I/GCoreUlr( 2734): Stopping handler for UlrDispSvcFast
,D/MenuAppsGridFragment( 2773): onResume
D/daemonapp( 4851): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/WallpaperManager( 2773): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 2773): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
,I/GCoreUlr( 2734): Unbound from all location providers
I/GCoreUlr( 2734): Place inference reporting - stopped
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/WallpaperManager( 2773): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 4851): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4851): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4851): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4851): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/Mms/UIEventReceiver( 5246): ui event
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2419): mDVFSHelper.release()
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (9/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
,D/checkbox( 4232): TwCheckBox.onDetachedToWindow()
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,I/SurfaceFlinger( 1920): id=17 Removed EimLayer (5/9)
,I/SurfaceFlinger( 1920): id=17 Removed EimLayer (-2/9)
I/SurfaceFlinger( 1920): id=16 Removed EimLayer (4/8)
,I/SurfaceFlinger( 1920): id=16 Removed EimLayer (-2/8)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(3)
,D/SensorService( 2419):   0.2 -0.0 9.9
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2419):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2419):   0.2 -0.0 9.9
,D/BatteryService( 2419): level:100, scale:100, status:2, health:2, present:true, voltage: 4347, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/PowerManagerService( 2419): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/PowerUI ( 2579): Overvoltage/Undervoltage (recovered) so turn on the screen.
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
D/PowerManagerService( 2419): [api] [s] wakeUp (uid: 10019 pid: 2579) eventTime = 126269
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
I/EntropyMixer( 2419): Writing entropy...
D/UsbDeviceManager( 2419): handleMessage -> MSG_POWER_STATE = 1
D/PowerUI ( 2579): playSound : 1
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,D/UsbDeviceManager( 2419): sending intent : ACTION_USB_CABLE_STATE : connected = true
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
V/Vibrator( 2579): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
,V/Vibrator( 2579): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,E/TranscodeReceiver( 5874): onReceive : android.intent.action.ACTION_POWER_CONNECTED
V/VibratorService( 2419): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
V/VibratorService( 2419): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2419): JNI vibratorOff()
D/VibratorService( 2419): JNI vibratorOn() : 100
D/PowerUI ( 2579): RINGER_MODE_VIBRATE
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
D/TranscodeService( 5874): onCreate()
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,D/BatteryMeterView( 2579): onDraw batteryColor : -1
I/SELinux ( 6325): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6325):  
,D/dalvikvm( 5874): No JNI_OnLoad found in /system/lib/libsavsvc.so 0x42277c88, skipping init
,D/dalvikvm( 5874): No JNI_OnLoad found in /system/lib/libsavscmn.so 0x42277c88, skipping init
,D/dalvikvm( 5874): No JNI_OnLoad found in /system/lib/libsthmb.so 0x42277c88, skipping init
D/TranscodeService( 5874): power? : true / screen off : false
,D/TranscodeService( 5874): releaseTranscodeThread.
,I/SELinux ( 6325): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6325):  
I/SELinux ( 6325):  
,I/SELinux ( 6325): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6325): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6325): >>>>> Normal User
,E/dalvikvm( 6325): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,D/VibratorService( 2419): JNI vibratorOff()
E/SELinux ( 6325): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6325): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6325): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6325): Added TimaKesytore provider
,D/dalvikvm( 6325): GC_CONCURRENT freed 2997K, 30% free 9572K/13648K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 6325): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/sCloudBackupApp( 6325): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 6325): Other Intent
,D/PicasaUploaderSyncManager( 6297): battery info: true
,I/iu.Environment( 5499): update battery state; isPlugged? true*
,I/iu.UploadsManager( 5499): num queued entries: 0
,I/iu.UploadsManager( 5499): num updated entries: 0
,I/iu.FingerprintManager( 5499): Start processing all media
,I/iu.SyncManager( 5499): NEXT; no task
,I/iu.FingerprintManager( 5499): Start processing media store URI: content://media/external/images/media
,I/iu.Environment( 3139): update battery state; isPlugged? true*
,I/iu.FingerprintManager( 5499): Start processing media store URI: content://media/external/video/media
,I/iu.UploadsManager( 3139): num queued entries: 0
,I/iu.UploadsManager( 3139): num updated entries: 0
,I/iu.SyncManager( 3139): NEXT; no task
,E/NetworkScheduler.SchedulerReceiver( 2850): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2850): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/iu.FingerprintManager( 3139): Start processing all media
I/iu.FingerprintManager( 3139): Start processing media store URI: content://media/external/images/media
,I/GCoreUlr( 2734): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/iu.FingerprintManager( 5499): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3139): Start processing media store URI: content://media/external/video/media
,I/GCoreUlr( 2734): DispatchingService.onCreate(),
,I/iu.FingerprintManager( 5499): Start processing media store URI: content://media/phoneStorage/video/media,
,I/iu.FingerprintManager( 3139): Start processing media store URI: content://media/phoneStorage/images/media,
I/iu.FingerprintManager( 5499): Finished generating fingerprints; 0.092 seconds
,I/iu.FingerprintManager( 5499):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0,
,I/iu.FingerprintManager( 3139): Start processing media store URI: content://media/phoneStorage/video/media,
I/iu.FingerprintManager( 3139): Finished generating fingerprints; 0.052 seconds
,I/iu.FingerprintManager( 3139):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0,
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,I/GCoreUlr( 2734): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/GCoreUlr( 2734): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2734): Unbound from all location providers
,I/GCoreUlr( 2734): Place inference reporting - stopped
,I/GCoreUlr( 2734): DispatchingService.onDestroy()
,I/GCoreUlr( 2734): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2734): Unbound from all location providers
,I/GCoreUlr( 2734): Place inference reporting - stopped
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4851): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 4851): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4851): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4851): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4851): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 4851): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 4851): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/SensorService( 2419):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{43287380 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/SensorService( 2419):   0.2 -0.0 9.9
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SensorService( 2419):   0.2 -0.0 9.9
,D/BatteryService( 2419): level:100, scale:100, status:2, health:2, present:true, voltage: 4372, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5435): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5435): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5435): Breath 72601 latestRequest time : 1454429695146 current time : 1454429767747
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,I/VacuumService( 2734): Vacuum at: now=1454429767997 tag=VacuumService
,D/dalvikvm( 2419): GC_CONCURRENT freed 3123K, 15% free 24988K/29284K, paused 16ms+15ms, total 224ms
,D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 127ms
,D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 128ms
,D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 111ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0
,I/PhenotypeConfigurator( 2734): Scheduling Phenotype for one-off execution 14139 seconds from now (1454429768628)
,D/GetConfigurationSnapshotOperation( 2734): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2734): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 2734): GC_CONCURRENT freed 1861K, 21% free 11619K/14628K, paused 7ms+7ms, total 76ms
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2734): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2734): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2734): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2734): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 2419): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 2734): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2734): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2734): VFY: replacing opcode 0x6e at 0x003d
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,I/System.out( 2734): Thread-113(HTTPLog):isShipBuild true
,I/System.out( 2734): Thread-113(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/Watchdog( 2419): !@Sync 4
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2419):   0.2 -0.0 9.9
,D/LocationManagerService( 2419): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 2734): GC_CONCURRENT freed 1374K, 18% free 12206K/14724K, paused 4ms+10ms, total 50ms
,D/LocationManagerService( 2419): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 295, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{42f38f38 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2419):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2419):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2419): level:100, scale:100, status:2, health:2, present:true, voltage: 4373, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2419):   0.2 -0.0 9.9
,D/PowerManagerService( 2419): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2419): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2419): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2419): lcd : 2 +
D/RampAnimator( 2419): Light Animator Finished currentValue=2
,D/lights  ( 2419): lcd : 2 -
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 297, prevStep = 4, currStep = 4
,D/SensorService( 2419):   0.2 -0.0 9.9
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5435): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5435): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5435): Breath 90016 latestRequest time : 1454429695146 current time : 1454429785162
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2419):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/PowerManagerService( 2419): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2419): Nap time...
D/PowerManagerService( 2419): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2419): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2419): Going to sleep due to screen timeout...
,D/PowerManagerService( 2419): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2419): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/DisplayPowerController( 2419): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,D/SensorManager( 2419): unregisterListener ::   
,I/DisplayPowerController( 2419): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,I/DisplayPowerController( 2419): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,I/SurfaceFlinger( 1920): id=20 createSurf (720x1280),-1 flag=20004, FlectronBea
I/Sensors ( 2419): HAL:resetDataRates mEnabled=4
,D/DisplayPowerController( 2419): !@ElectronBeam entry
D/SensorManager( 2419): unregisterListener ::   
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/PowerManagerService( 2419): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2579
I/PowerManagerService( 2419): !@[ps] Screen__On(wake lock) :  wl: PowerUI
I/PowerManagerService( 2419): Waking up from sleep...
D/PowerManagerService( 2419): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2419): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerNotifier( 2419): mBroadcastInProgress = true , mActualPowerState = 1 , mPendingWakeUpBroadcast = true , mPendingGoToSleepBroadcast = true , mBroadcastedPowerState = 1
,D/PowerManagerService( 2419): [s] WAKEFULNESS_AWAKE
D/lights  ( 2419): button : 1 +
D/lights  ( 2419): button : 1 -
,V/WindowOrientationListener( 2419): WindowOrientationListener disabled
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/SensorService( 2419): AutoRotationSensor::activate (ident=0x7b23e7b0, enabled=0)
,I/Sensors ( 2419): HAL: batch Dry Run is complete
,D/KeyguardViewMediator( 2579): onScreenTurnedOff(3)
,D/NotificationService( 2419): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService( 2419): sendNotification(1) - 5
,D/SensorManager( 2419): unregisterListener ::   
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000,
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
,D/Sensors ( 2419): LightSensor enableSensor = 1,
D/DisplayPowerController( 2419): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController( 2419): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,I/DisplayPowerController( 2419): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1,
D/LockPatternUtils( 2579): isPcwEnable = 10
D/InputDispatcher( 2419): setInputDispatchMode: enabled=0, frozen=0
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 1
D/PowerManagerService( 2419): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 13ms
D/LockPatternUtils( 2579): isPcwEnable = 10
,I/Sensors ( 2419): HAL: batch Dry Run is complete
I/DisplayPowerController( 2419): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2419): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2419): [DAB] no lux value from sensor manager
,D/DisplayPowerController( 2419): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/Sensors ( 2419): HAL:resetDataRates mEnabled=4
D/Launcher.HomeView( 2773): onPause
,D/SensorManager( 2419): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/PowerManagerService( 2419): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 18ms
,D/ProgressBar( 2579): setProgressDrawable drawableHeight = 12
,D/lights  ( 2419): lcd : 0 +
,D/lights  ( 2419): lcd : 0 -
D/DisplayPowerController( 2419): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PhoneStatusBar( 2579): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@4229aca0
,D/RCPManagerService( 2419): NotificationReceiver onReceive()
,D/RCPManagerService( 2419):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
,D/RCPManagerService( 2419): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298419
,D/StatusBarManagerService( 2419): tr p:2773,o:f
D/KeyguardViewMediator( 2579): setting alarm to turn off keyguard, seq = 2
D/RCPManagerService( 2419): getPolicy: policy value returned = false
D/RCPManagerService( 2419): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2419): app label == com.android.systemui
,D/RCPManagerService( 2419): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298419
,D/UserManagerService( 2419): User -1does not exists!!
D/RCPManagerService( 2419): getPolicy: policy value returned = true
D/RCPManagerService( 2419): Calling User is -1
,D/RCPManagerService( 2419): userid of SBN ==-1
,D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
E/PersonaManagerService( 2419): returning null in  getPersonasForUser
D/BatteryMeterView( 2579): onDraw batteryColor : -1
,D/LightsService( 2419): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2419) 
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(52)
D/BatteryService( 2419): turn on LED for fully charged
D/VibratorService( 2419): JNI vibratorOff()
,D/Launcher.HomeView( 2773): onStop
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2419): ACTION_SCREEN_OFF
,D/LightsService( 2419): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2419) 
,D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=off)
,I/SecExternalDisplayIntents_Java( 2419): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2419): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2419): Bridge Server is not available
,D/PersonaManagerService( 2419): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2419): MSG_ACTION_SCREEN_OFF called
,D/STATUSBAR-PhoneStatusBar( 2579):      ACTION_SCREEN_OFF is received!!!! 
,D/STATUSBAR-PhoneStatusBar( 2579): makeExpandedInvisible
D/PhoneStatusBarView( 2579): marqueeStatusBar:122, mClearCover:0
,D/STATUSBAR-PhoneStatusBar( 2579):      ACTION_SCREEN_OFF is finished!!!! 
,D/Sensors ( 2419): LightSensor sending flush event 16
D/Sensors ( 2419): LightSensor setDelay = 200000000
,D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/SensorManager( 2419): unregisterListener ::   
,D/lights  ( 2419): led_pattern : 5 +
D/DisplayPowerController( 2419): [api] [DAB] onSensorChanged : 1st lux : 0.0
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
D/DisplayPowerController( 2419): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,I/NfcService( 2755): applyRouting return - 2 
,D/lights  ( 2419): led_pattern : 5 -
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/NfcService( 2755): callback == null
,D/LockPatternUtils( 2579): isPcwEnable = 10
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0
,D/QuickConnect[1.1][2] ( 4649): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 4649): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4649): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4649): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228a1b0
V/QuickConnect[1.1][2] ( 4649): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228a1b0
D/QuickConnect[1.1][2] ( 4649): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4649): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4649): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4649): stopLeScan()
,D/QuickConnect[1.1][2] ( 4649): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 5874): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 5874): power? : true / screen off : true
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 65558
D/SensorService( 2419): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2419): AutoRotationSensor::activate (ident=0x7f72c4c0, enabled=1)
D/SensorService( 2419): AutoRotationSensor::AR_init
,I/Sensors ( 2419): HAL: batch Dry Run is complete
D/TranscodeService( 5874): Music is = false
,D/TranscodeService( 5874): runvideoplayer is false
,I/Sensors ( 2419): HAL:resetDataRates mEnabled=4
,D/TranscodeService( 5874): Thread start
,D/TranscodeService( 5874): WakeLock.acquire()
,D/videowall-FileMgr( 5874): thumbnailDBSync -1
,D/SensorService( 2419): AutoRotationSensor::process: Acc  eventTimestamp = 156683345618, previousAccTimestamp = 156350536785, difference = 332808833 
,D/SensorService( 2419): AutoRotationSensor::reset oldrotation = [100], initState = [1]
D/SensorManager( 2419): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,V/KeyguardServiceDelegate( 2419): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@43246c50)
,D/InputDispatcher( 2419): setInputDispatchMode: enabled=1, frozen=0
D/Launcher( 2773): onRestart, Launcher: 1113874168
D/Launcher( 2773): onStart, Launcher: 1113874168
,D/Launcher.HomeView( 2773): onStart
D/KeyguardViewMediator( 2579): onScreenTurnedOn, seq = 3
,D/KeyguardViewMediator( 2579): notifyScreenOnLocked
,D/LockPatternUtils( 2579): isPcwEnable = 10
,D/KeyguardViewMediator( 2579): handleNotifyScreenOn
,D/KeyguardViewManager( 2579): onScreenTurnedOn()
I/KeyguardEffectViewMain( 2579): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 2579): KeyguardEffectViewParticleSpace : screenTurnedOn
D/VisualEffectParticleEffect( 2579): screenOnAnimationStart
V/KeyguardServiceDelegate( 2419): **** SHOWN CALLED ****
,D/Launcher( 2773): onResume, Launcher: 1113874168
V/KeyguardViewManager( 2579): send wm null token: host was null
I/WindowManager( 2419): No lock screen! windowToken=null
D/StatusBarManagerService( 2419): semi p:2773,o:f
D/PowerManagerNotifier( 2419): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,I/SurfaceFlinger( 1920): id=20 Removed FlectronBea (8/8)
D/PowerManagerService( 2419): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2419): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2419): !@ElectronBeam exit
D/LockPatternUtils( 2579): isPcwEnable = 10
I/SurfaceFlinger( 1920): id=20 Removed FlectronBea (-2/8)
,D/lights  ( 2419): lcd : 2 +
D/lights  ( 2419): lcd : 2 -
,D/Launcher.HomeView( 2773): onResume
,D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/lights  ( 2419): led_pattern : 0 +
D/DisplayPowerController( 2419): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2419): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/LightsService( 2419): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 2419) 
D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 2419): turn off LED
D/LightsService( 2419): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/lights  ( 2419): led_pattern : 0 -
D/StatusBarManagerService( 2419): tr p:2773,o:f
D/StatusBarManagerService( 2419): semi p:2773,o:f
,I/FPMS_FingerprintManagerService( 2599): onReceive: android.intent.action.USER_PRESENT
,D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SamsungIME( 2947): showDlgMsgBox : false true true
,I/NfcService( 2755): applyRouting return - 2 
,E/NfcService( 2755): callback == null
D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/MenuAppsGridFragment( 2773): onResume
,D/LockPatternUtils( 2579): isPcwEnable = 10
,D/LightsService( 2419): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2419) 
,D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2419): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PalmMotionService( 2419): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2419): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService( 2419):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/SSRMv2:TSP:AirViewOnOff( 2419): SettingsAirViewInfo:: 000000000
,D/Mms/UIEventReceiver( 5246): ui event
,D/SensorService( 2419): AutoRotationSensor::process: Acc  eventTimestamp = 156934439910, previousAccTimestamp = 156350536785, difference = 583903125 
,D/SensorService( 2419):  [AR] 0.2 -0.0 9.9
,D/SensorService( 2419): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onInitialize : 3902
D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onSetOnInfoListener : add 3902
I/PrGenericPlugin( 1923): [A] ENTER onInitialize : 0xf3e
,I/PrGenericPlugin( 1923): [A] LEAVE onInitialize : 0xf3e
,D/TranscodeService( 5874): Thread end
,D/TranscodeService( 5874): WakeLock.release()
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,D/TranscodeService( 5874): onDestroy()
D/TranscodeService( 5874): releaseTranscodeThread.
,D/TranscodeService( 5874): Thread isAlive
D/STATUSBAR-NotificationService( 2419): ACTION_SCREEN_ON
D/LightsService( 2419): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2419) 
D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2419): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=on)
,I/SecExternalDisplayIntents_Java( 2419): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController( 2419): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2419): Bridge Server is not available
,D/PersonaManagerService( 2419): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2419): MSG_ACTION_SCREEN_ON called
,I/NfcService( 2755): NFC: Screen On & Cover Open
,I/NfcService( 2755): applyRouting return - 2 
,E/NfcService( 2755): callback == null
,D/STATUSBAR-NetworkController( 2579): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/QuickConnect[1.1][2] ( 4649): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
V/QuickConnect[1.1][2] ( 4649): BleHelper.shouldScanBleBg - 
,D/QuickConnect[1.1][2] ( 4649): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4649): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228a1b0
V/QuickConnect[1.1][2] ( 4649): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228a1b0
V/QuickConnect[1.1][2] ( 4649): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 4649): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228a1b0
,V/QuickConnect[1.1][2] ( 4649): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228a1b0
V/QuickConnect[1.1][2] ( 4649): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228a1b0
D/QuickConnect[1.1][2] ( 4649): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 4649): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 4649): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 4649): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 4851): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4851): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4851): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4851): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454433900000
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454429788385
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4851): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON,
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo,
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 4851): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4851): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4851): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4851): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 4851): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4851): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4851): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4851): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/vwengine( 5874): stopTranscoding
,D/TranscodeService( 5874): transThread.join();
,V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
D/PowerManagerService( 2419): [PWL] sb release: PowerManagerService.Broadcasts
,I/ActivityManager( 2419): Killing 5451:com.samsung.android.magazine.service/u0a110 (adj 15): empty #43
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/lights  ( 2419): button : 0 +
,D/lights  ( 2419): button : 0 -
,D/SSRMv2:TSP:AirViewOnOff( 2419): SettingsAirViewInfo:: 000000000
,D/SensorService( 2419):   0.2 -0.0 9.9
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(60)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/AmoledAdjustTimer( 2419): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,V/AlarmManager( 2419): waitForAlarm result :4
,D/KeyguardViewMediator( 2579): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 3
V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2419):   0.2 -0.0 9.9
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(59)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2419):   0.2 -0.0 9.9
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2419): !@Sync 5
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2419):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2419):   0.2 -0.0 9.8
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SensorService( 2419):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2419): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2579 (0x0)
,I/PowerManagerService( 2419): Nap time...
,D/PowerManagerService( 2419): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2419): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2419): Going to sleep due to screen timeout...
,D/PowerManagerService( 2419): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2419): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2419): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/DisplayPowerController( 2419): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/SensorManager( 2419): unregisterListener ::   
,I/SurfaceFlinger( 1920): id=21 createSurf (720x1280),-1 flag=20004, FlectronBea
,I/DisplayPowerController( 2419): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
I/Sensors ( 2419): HAL:resetDataRates mEnabled=4
,D/DisplayPowerController( 2419): !@ElectronBeam entry
D/SensorManager( 2419): unregisterListener ::   
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/lights  ( 2419): lcd : 0 +
,D/lights  ( 2419): lcd : 0 -
,D/MISC PowerHAL( 2419): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2419): sysfs_write +: /sys/class/input/input1/enabled: 0
D/PowerManagerService( 2419): blankAllDisplays() is called.
D/PowerManagerService( 2419): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2419): [PWL] sb acquire: PowerManagerService.Broadcasts
V/WindowOrientationListener( 2419): WindowOrientationListener disabled
D/SensorService( 2419): AutoRotationSensor::activate (ident=0x7f72c4c0, enabled=0)
,I/Sensors ( 2419): HAL: batch Dry Run is complete
,D/KeyguardViewMediator( 2579): onScreenTurnedOff(3)
,D/PowerManagerService( 2419): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2419): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2419): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2419): sysfs_write +: /sys/class/input/input0/enabled: 0
D/SensorManager( 2419): unregisterListener ::   
D/InputDispatcher( 2419): setInputDispatchMode: enabled=0, frozen=0
D/MISC PowerHAL( 2419): sysfs_write -: /sys/class/input/input0/enabled: 0
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
,D/PowerManagerService( 2419): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SurfaceFlinger( 1920): Screen released, type=0 flinger=0x408d1550
D/Launcher.HomeView( 2773): onPause
D/LockPatternUtils( 2579): isPcwEnable = 10
,D/LockPatternUtils( 2579): isPcwEnable = 10
,D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/KeyguardViewMediator( 2579): setting alarm to turn off keyguard, seq = 3
D/StatusBarManagerService( 2419): tr p:2773,o:f
,D/Launcher.HomeView( 2773): onStop
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/LightsService( 2419): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2419) 
,D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
,D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2419): turn on LED for fully charged
D/VibratorService( 2419): JNI vibratorOff()
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(38)
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2419): ACTION_SCREEN_OFF
,D/LightsService( 2419): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2419) 
,D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2419): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2419): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2419): Bridge Server is not available
,D/PersonaManagerService( 2419): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2419): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2579):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2579): makeExpandedInvisible
D/PhoneStatusBarView( 2579): marqueeStatusBar:123, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2579):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2755): applyRouting return - 2 
,E/NfcService( 2755): callback == null
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/LockPatternUtils( 2579): isPcwEnable = 10
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0
,D/QuickConnect[1.1][2] ( 4649): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 4649): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4649): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,V/QuickConnect[1.1][2] ( 4649): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228a1b0
V/QuickConnect[1.1][2] ( 4649): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228a1b0
D/QuickConnect[1.1][2] ( 4649): BleHelper.stopScan - force = true
,D/QuickConnect[1.1][2] ( 4649): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4649): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4649): stopLeScan()
,D/QuickConnect[1.1][2] ( 4649): BleHelper.stopScan - call stopLeScan() complete
,D/SurfaceControl( 2419): Excessive delay in blankDisplay() while turning screen off: 230ms
D/PowerManagerService( 2419): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 231ms
I/libsuspend( 2419): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2419): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2419): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2419): [PWL] Off : 0s ago
I/PowerManagerService( 2419): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/PowerManagerService( 2419): [PWL] sb release: PowerManagerService.Broadcasts
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager( 2419): unregisterListener ::   
D/lights  ( 2419): led_pattern : 5 +
,D/lights  ( 2419): led_pattern : 5 -
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer( 2419): prevTemp = 298, currTemp = 299, prevStep = 4, currStep = 4,
,V/AlarmManager( 2419): waitForAlarm result :4,
,D/KeyguardViewMediator( 2579): received DELAYED_KEYGUARD_ACTION with seq = 3, mDelayedShowingSequence = 3,
,D/LockPatternUtils( 2579): isPcwEnable = 10,
,D/KeyguardViewMediator( 2579): in doKeyguardLocked mIsRollUp false null,
,D/PersonaManager( 2579): isKioskContainerExistOnDevice,
,D/LockPatternUtils( 2579): isPcwEnable = 10,
D/LockPatternUtils( 2579): isPcwEnable = 10
,D/KeyguardViewMediator( 2579): doKeyguard: not showing because lockscreen is off,
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/PowerManagerService( 2419): [PWL] Off : 5s ago,
,V/AlarmManager( 2419): waitForAlarm result :8,
,D/Headlines( 5435): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5435): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5435): Breath 120027 latestRequest time : 1454429695146 current time : 1454429815173
,D/Headlines( 5435): stop ,
,D/Headlines( 5435): Breath.onDestroy : ,
I/ActivityManager( 2419): Killing 4737:com.android.email/u0a157 (adj 15): empty #43
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3365): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = -10,
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2419): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2419): [PWL] Off : 15s ago,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2419): !@Sync 6,
,D/AmoledAdjustTimer( 2419): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,I/PowerManagerService( 2419): [PWL] Off : 30s ago
,V/AlarmManager( 2419): waitForAlarm result :4,
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/AmoledAdjustTimer( 2419): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,I/PowerManagerService( 2419): [PWL] Off : 50s ago
,E/Watchdog( 2419): !@Sync 7,
,D/AmoledAdjustTimer( 2419): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3365): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2419): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2419): [PWL] Off : 75s ago,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2419): !@Sync 8,
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2419): stay LED for fully charged,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3365): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2419): [PWL] Off : 105s ago,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 9,
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0,
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4,
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2419): initializing...,
I/TLC_TIMA_PKM_initialize( 2419): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2419): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2419): input max_recvmsg_size = 262196,
I/TZ: mc_tlc_communication( 2419): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2419): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2419): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2419): device_id = 0x0
I/TZ: mc_tlc_communication( 2419): tlc_open() was called
,I/TZ: mc_tlc_communication( 2419): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2419): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2419): Opening the session
,I/TZ: mc_tlc_communication( 2419): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2419): Trustlet response is completed,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2419): [PWL] Off : 140s ago,
I/PowerManagerService( 2419): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2419): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2419): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2419, ws=null) (elapsedTime=5208),
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0,
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 10,
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4,
,V/AlarmManager( 2419): waitForAlarm result :4,
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 6814): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 6814):  
,I/SELinux ( 6814): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6814):  
I/SELinux ( 6814):  
,I/SELinux ( 6814): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6814): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6814): >>>>> Normal User
,E/dalvikvm( 6814): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 6814): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 6814): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 6814): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 6814): Added TimaKesytore provider,
,D/dalvikvm( 6814): GC_CONCURRENT freed 3000K, 30% free 9567K/13648K, paused 3ms+2ms, total 27ms,
,D/dalvikvm( 6814): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/ActivityManager( 2419): Killing 4839:com.samsung.android.service.travel/u0a170 (adj 15): empty #43,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 11,
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2419): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 2419): GC_FOR_ALLOC freed 3703K, 17% free 25053K/30036K, paused 222ms, total 224ms
D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 12
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5061): [b] __PingReply__
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 225s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 13
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 14
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 275s ago
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 15
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 16
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 17
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3365): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 18
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 19
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 20
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 455s ago
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 21
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/GAV2    ( 5175): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5175): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2419): GC_FOR_ALLOC freed 2630K, 17% free 24996K/30092K, paused 208ms, total 209ms
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 22
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 525s ago
,E/Watchdog( 2419): !@Sync 23
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 3747): GC_CONCURRENT freed 2879K, 30% free 9689K/13680K, paused 3ms+2ms, total 39ms
,D/dalvikvm( 3747): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 24
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 25
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 26
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/BatteryService( 2419): stay LED for fully charged
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3365): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 27
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 680s ago
,E/Watchdog( 2419): !@Sync 28
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 29
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 30
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 765s ago
,E/Watchdog( 2419): !@Sync 31
,D/dalvikvm( 2419): GC_FOR_ALLOC freed 2485K, 18% free 24967K/30092K, paused 202ms, total 203ms
D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3139): Aggregate from 1454428246298 (log), 1454428246298 (data)
,D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2419): LightSensor enable = 0
D/Sensors ( 2419): LightSensor enableSensor = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 3139): GC_CONCURRENT freed 1804K, 20% free 12110K/14992K, paused 6ms+7ms, total 59ms
,D/ConnectivityService( 2419): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2579): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2579): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2579): updateDataNetType()
,D/STATUSBAR-NetworkController( 2579): NoService, mRoamingIconId = 0
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 32
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,E/SPPClientService( 5061): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 33
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2773): GC_CONCURRENT freed 6070K, 36% free 19999K/30924K, paused 5ms+7ms, total 96ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 855s ago
,E/Watchdog( 2419): !@Sync 34
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 35
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 36
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 950s ago
,E/Watchdog( 2419): !@Sync 37
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 38
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 39
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 282, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 40
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2419): [PWL] Off : 1050s ago
,D/dalvikvm( 2419): GC_FOR_ALLOC freed 2609K, 17% free 24988K/30092K, paused 199ms, total 200ms
D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 41
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 42
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5061): [b] __PingReply__
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3365): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3365): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 43
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,TIME-OUT KILL (timeout was 1200000ms)
```
