#### Test 5753124374916c2_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
I/Icing   ( 3142): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
I/Icing   ( 3142): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,I/Icing   ( 3142): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
--------- beginning of /dev/log/system
W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/Icing   ( 3142): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
D/AndroidRuntime( 6125): 
D/AndroidRuntime( 6125): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6125): CheckJNI is OFF
D/AndroidRuntime( 6125): setted country_code = Poland
D/AndroidRuntime( 6125): setted countryiso_code = PL
D/AndroidRuntime( 6125): setted sales_code = PLS
D/AndroidRuntime( 6125): readGMSProperty: start
D/AndroidRuntime( 6125): readGMSProperty: already setted!!
D/AndroidRuntime( 6125): readGMSProperty: end
D/AndroidRuntime( 6125): addProductProperty: start
D/dalvikvm( 6125): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6125): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6125): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6125): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6125): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2845): GC_EXPLICIT freed 474K, 26% free 10278K/13756K, paused 4ms+7ms, total 64ms
E/memtrack( 6125): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6125): failed to load memtrack module: -2
D/dalvikvm( 5944): GC_EXPLICIT freed 850K, 27% free 10151K/13748K, paused 3ms+8ms, total 42ms
D/dalvikvm( 6125): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6125): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 6125): Shutting down VM
D/dalvikvm( 6125): GC_CONCURRENT freed 99K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{4328d6a0 u0 com.sec.spp.push/.PushClientService}
,I/ActivityManager( 2422): Killing 5316:com.sec.android.cloudagent/u0a2 (adj 15): empty #43
,D/dalvikvm( 2845): GC_EXPLICIT freed 350K, 26% free 10286K/13756K, paused 5ms+7ms, total 51ms
,E/SPPClientService( 5098): [b] __ProvisionReply__
,E/SPPClientService( 5098): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5098): [d] null
,V/AlarmManager( 2422):  next == MAX_VALUE
,D/dalvikvm( 5944): GC_EXPLICIT freed 1028K, 28% free 10013K/13748K, paused 10ms+9ms, total 58ms
,E/SPPClientService( 5098): [g] getPLMN return empty string
,E/SPPClientService( 5098): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5098): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5098): [a] [ConnectionManager] Connection is already disconnected.
,D/dalvikvm( 5098): GC_CONCURRENT freed 2140K, 25% free 10407K/13740K, paused 4ms+4ms, total 52ms
,E/SPPClientService( 5098): [g] getNetMCC return empty string
,D/BatteryService( 2422): level:100, scale:100, status:2, health:2, present:true, voltage: 4367, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for charging
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3364): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/dalvikvm( 2422): GC_EXPLICIT freed 952K, 14% free 24415K/28124K, paused 11ms+18ms, total 263ms
,V/AlarmManager( 2422): waitForAlarm result :4
,D/Finsky  ( 5121): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/dalvikvm( 5121): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5121): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5121): VFY: replacing opcode 0x62 at 0x0038
V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/dalvikvm( 2422): Jit: resizing JitTable from 8192 to 16384
,V/GLSActivity( 2862): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2862): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5121): Thread-369(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5121): Thread-369(ApacheHTTPLog):isShipBuild true
,I/System.out( 5121): Thread-369(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/IcingInternalCorpora( 3142): getNumBytesRead when not calculated.
,I/System.out( 5121): Thread-369 calls detatch()
,V/GLSActivity( 2862): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2862): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5121): Failed write_ctrl(u 68) res=-1 errno=22
,I/qtaguid ( 5121): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5121): untagSocket(68) failed with errno -22
,I/System.out( 5121): Thread-370 calls detatch()
,D/Finsky  ( 5121): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,E/SPPClientService( 5098): [b] __InitReply__
,V/GLSActivity( 2862): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2862): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2845): GC_EXPLICIT freed 346K, 26% free 10295K/13756K, paused 5ms+8ms, total 55ms
,D/dalvikvm( 5944): GC_EXPLICIT freed 898K, 28% free 10007K/13748K, paused 4ms+8ms, total 51ms
I/qtaguid ( 5121): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5121): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5121): untagSocket(68) failed with errno -22
,I/System.out( 5121): Thread-369 calls detatch()
,D/dalvikvm( 5121): GC_CONCURRENT freed 2067K, 24% free 10481K/13744K, paused 3ms+7ms, total 53ms
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5121): GC_CONCURRENT freed 760K, 15% free 11768K/13744K, paused 6ms+4ms, total 55ms
,D/dalvikvm( 5121): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 5121): GC_FOR_ALLOC freed 927K, 15% free 12606K/14788K, paused 42ms, total 43ms
,I/PowerManagerService( 2422): [PWL] Off : 30s ago
,D/dalvikvm( 5121): GC_FOR_ALLOC freed 1008K, 18% free 12910K/15684K, paused 39ms, total 40ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 350, Delta = -10
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 5121): GC_CONCURRENT freed 2060K, 19% free 14266K/17496K, paused 4ms+5ms, total 58ms
,D/dalvikvm( 5121): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 5944): GC_EXPLICIT freed 895K, 28% free 10022K/13748K, paused 3ms+7ms, total 36ms
,D/dalvikvm( 2845): GC_EXPLICIT freed 343K, 26% free 10304K/13756K, paused 3ms+12ms, total 47ms
,D/AmoledAdjustTimer( 2422): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,V/GLSActivity( 2862): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2862): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PackageManager( 2422): [MSG] MCS_UNBIND
I/PackageManager( 2422): calling disconnectService()
,D/PackageManager( 2422): Trying to unbind to DefaultContainerService
,I/ActivityManager( 2422): Killing 5245:com.vlingo.midas/u0a34 (adj 15): empty #43
,I/qtaguid ( 5121): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5121): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5121): untagSocket(68) failed with errno -22
,I/System.out( 5121): Thread-370 calls detatch()
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{43070178 u0 com.sec.android.gallery3d/.app.BackgroundCache}
,D/Finsky  ( 5121): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 2422): GC_EXPLICIT freed 921K, 14% free 24439K/28124K, paused 8ms+19ms, total 240ms
,D/WearableService( 2748): callingUid 10012, callindPid: 2748
,D/DeviceConnectionService( 2748): client connected with version: 8296000
,D/Finsky  ( 5121): [392] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5121): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5121): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2862): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2862): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5121): Thread-380(HTTPLog):isShipBuild true
,I/System.out( 5121): Thread-380(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 5944): GC_EXPLICIT freed 906K, 28% free 10021K/13748K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 2845): GC_EXPLICIT freed 365K, 26% free 10297K/13756K, paused 4ms+7ms, total 51ms
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5944): GC_EXPLICIT freed 883K, 28% free 10011K/13748K, paused 3ms+9ms, total 49ms
,D/dalvikvm( 2845): GC_EXPLICIT freed 350K, 26% free 10300K/13756K, paused 3ms+7ms, total 47ms
,V/AlarmManager( 2422): waitForAlarm result :8
,D/dalvikvm( 5944): null clazz in OP_INSTANCE_OF, single-stepping
,D/dalvikvm( 5944): GC_EXPLICIT freed 873K, 28% free 10016K/13748K, paused 4ms+9ms, total 52ms
,D/dalvikvm( 2845): GC_EXPLICIT freed 350K, 26% free 10307K/13756K, paused 4ms+7ms, total 48ms
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/LightsService( 2422): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 0 pid: 0) 
,I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
D/Sensors ( 2422): LightSensor setDelay = 200000000
,D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/Sensors ( 2422): Light sensor flush: not enabled 0
D/Sensors ( 2422): LightSensor enable = 1
,D/Sensors ( 2422): LightSensor enableSensor = 1
D/LightsService( 2422): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2422): turn on LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/PowerManagerService( 2422): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2594
I/PowerManagerService( 2422): !@[ps] Screen__On(wake lock) :  wl: PowerUI
I/PowerManagerService( 2422): Waking up from sleep...
D/PowerManagerService( 2422): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2422): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/lights  ( 2422): button : 1 +
,D/lights  ( 2422): button : 1 -
,I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
D/PowerManagerService( 2422): [s] WAKEFULNESS_AWAKE
D/PowerManagerService( 2422): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 2422): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2422): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/DisplayPowerController( 2422): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 1
,I/Sensors ( 2422): HAL: batch Dry Run is complete
D/PowerManagerService( 2422): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 2ms
D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/DisplayPowerController( 2422): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
,I/Sensors ( 2422): HAL:resetDataRates mEnabled=4
,I/libsuspend( 2422): !@[s] autosuspend_autosleep_disable
,I/libsuspend( 2422): !@[s] autosuspend_autosleep_disable done
D/DisplayPowerController( 2422): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2422): [DAB] no lux value from sensor manager
D/DisplayPowerController( 2422): animation target = 7 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2422): unblankAllDisplays() is called.
D/PowerManagerService( 2422): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/SurfaceFlinger( 1922): Screen acquired, type=0 flinger=0x411ef550
,D/SensorManager( 2422): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/STATUSBAR-StatusBarManagerService( 2422): sendNotification(1) - 5
,D/PowerManagerService( 2422): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 17ms
D/NotificationService( 2422): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 65558
D/SensorService( 2422): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2422): AutoRotationSensor::activate (ident=0x7a8c9400, enabled=1)
D/SensorService( 2422): AutoRotationSensor::AR_init
I/Sensors ( 2422): HAL: batch Dry Run is complete
I/Sensors ( 2422): HAL:resetDataRates mEnabled=4
,D/RCPManagerService( 2422): NotificationReceiver onReceive()
,D/RCPManagerService( 2422):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
,D/RCPManagerService( 2422): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298422
,D/SensorManager( 2422): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
D/RCPManagerService( 2422): getPolicy: policy value returned = false
,D/RCPManagerService( 2422): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2422): app label == com.android.systemui
,D/UserManagerService( 2422): User -1does not exists!!
D/RCPManagerService( 2422): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298422
D/RCPManagerService( 2422): getPolicy: policy value returned = true
D/RCPManagerService( 2422): Calling User is -1
,V/KeyguardServiceDelegate( 2422): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@42f4b978)
,D/RCPManagerService( 2422): userid of SBN ==-1
,E/PersonaManagerService( 2422): returning null in  getPersonasForUser
D/InputDispatcher( 2422): setInputDispatchMode: enabled=1, frozen=0
D/ProgressBar( 2594): setProgressDrawable drawableHeight = 12
D/KeyguardViewMediator( 2594): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 2594): notifyScreenOnLocked
D/LockPatternUtils( 2594): isPcwEnable = 10
,D/PhoneStatusBar( 2594): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422c37f8
,D/KeyguardViewMediator( 2594): handleNotifyScreenOn
D/KeyguardViewManager( 2594): onScreenTurnedOn()
,I/KeyguardEffectViewMain( 2594): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 2594): KeyguardEffectViewParticleSpace : screenTurnedOn
V/KeyguardServiceDelegate( 2422): **** SHOWN CALLED ****
,D/VisualEffectParticleEffect( 2594): screenOnAnimationStart
V/KeyguardViewManager( 2594): send wm null token: host was null
I/WindowManager( 2422): No lock screen! windowToken=null
,D/BatteryMeterView( 2594): onDraw batteryColor : -1
,D/Sensors ( 2422): LightSensor sending flush event 16
D/SensorService( 2422): AutoRotationSensor::process: Acc  eventTimestamp = 101922050383, previousAccTimestamp = 63793362754, difference = 38128687629 
,D/SensorService( 2422): AutoRotationSensor::reset oldrotation = [100], initState = [1]
D/DisplayPowerController( 2422): [api] [DAB] onSensorChanged : 1st lux : 8.0
D/DisplayPowerController( 2422): [DAB] updateAutoBrightnessSEC : 14(14.0)    0.0 < 8.0 < 15.0 (0.0)
D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 8
,D/DisplayPowerController( 2422): animation target = 4 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/Sensors ( 2422): LightSensor setDelay = 200000000
D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/SensorManager( 2422): unregisterListener ::   
D/lights  ( 2422): led_pattern : 5 +
D/lights  ( 2422): led_pattern : 5 -
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
V/AlarmManager( 2422): waitForAlarm result :8
D/RampAnimator( 2422): Light Animator Finished currentValue=4
,D/SensorService( 2422): AutoRotationSensor::process: Acc  eventTimestamp = 101988712772, previousAccTimestamp = 63793362754, difference = 38195350018 
,D/SensorService( 2422):  [AR] 0.2 -0.0 9.8
,D/SensorService( 2422): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/SurfaceControl( 2422): Excessive delay in unblankDisplay() while turning screen on: 242ms
,D/MISC PowerHAL( 2422): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2422): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2422): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 243ms
D/PowerManagerNotifier( 2422): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2422): Screen Readiness Inspection completed: mNestCount=0
,I/SurfaceFlinger( 1922): id=14 Removed FlectronBea (10/10)
,I/SurfaceFlinger( 1922): id=14 Removed FlectronBea (-2/10)
D/DisplayPowerController( 2422): animation target = 4 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2422): !@ElectronBeam exit
D/lights  ( 2422): lcd : 4 +
,I/display ( 1922): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
D/MISC PowerHAL( 2422): sysfs_write -: /sys/class/input/input1/enabled: 1
D/MISC PowerHAL( 2422): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2422): sysfs_write +: /sys/class/input/input0/enabled: 1
,D/lights  ( 2422): lcd : 4 -
D/DisplayPowerController( 2422): animation target = 4 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2422): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/LockPatternUtils( 2594): isPcwEnable = 10
,I/FPMS_FingerprintManagerService( 2614): onReceive: android.intent.action.USER_PRESENT
,I/DBG_DM  ( 4261): [3.19.140541][Line:408][onResume] 
D/LightsService( 2422): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2422) 
,D/LightsService( 2422): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/NfcService( 2770): applyRouting return - 2 
D/SamsungIME( 2977): showDlgMsgBox : false true true
I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/PalmMotionService( 2422): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2422): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService( 2422):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,E/NfcService( 2770): callback == null
,I/DBG_DM  ( 4261): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 41
D/SSRMv2:TSP:AirViewOnOff( 2422): SettingsAirViewInfo:: 000000000
,D/Sensors ( 2422): LightSensor sending flush event 16
D/Sensors ( 2422): LightSensor setDelay = 200000000
,D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/SensorManager( 2422): unregisterListener ::   
,D/lights  ( 2422): led_pattern : 0 +
D/LightsService( 2422): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 2422) 
D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 8
D/LightsService( 2422): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 2422): turn off LED
,D/lights  ( 2422): led_pattern : 0 -
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/DBG_DM  ( 4261): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/LockPatternUtils( 2594): isPcwEnable = 10
,I/DBG_DM  ( 4261): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4261): [3.19.140541][Line:418][onResume] Postpone Count : 41
D/MISC PowerHAL( 2422): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2422): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2422): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2422): Excessive delay in MISC setInteractive(true) while turning screen on: 176ms
,D/SEC PowerHAL( 2422): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2422): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2422): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2422): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2422): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2422): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2422): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2422): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
D/PowerManagerService( 2422): Excessive delay in nativeSetInteractive(true): 181ms
D/PowerManagerService( 2422): SecHardwareInterface.setBatteryADC : true
,I/DBG_DM  ( 4261): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2422): ACTION_SCREEN_ON
D/LightsService( 2422): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2422) 
D/LightsService( 2422): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/STATUSBAR-NetworkController( 2594): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster: data=-1 bt=false
D/LightsService( 2422): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=on)
I/SecExternalDisplayIntents_Java( 2422): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
I/DBG_DM  ( 4261): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/IpRemoteDisplayController( 2422): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2422): Bridge Server is not available
,D/PersonaManagerService( 2422): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2422): MSG_ACTION_SCREEN_ON called
,I/DBG_DM  ( 4261): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/display ( 1922): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(56)
,I/NfcService( 2770): NFC: Screen On & Cover Open
,I/NfcService( 2770): applyRouting return - 2 
,E/NfcService( 2770): callback == null
,D/STATUSBAR-NetworkController( 2594): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,D/dalvikvm( 2422): GC_EXPLICIT freed 580K, 13% free 24470K/28124K, paused 6ms+15ms, total 193ms
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2422): sendNotification(2) - 4
,I/DBG_DM  ( 4261): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 41
,I/DBG_DM  ( 4261): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4261): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4261): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4261): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4261): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4261): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/Activity( 4261): setTransGradationMode to true
,D/PhoneStatusBar( 2594): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2422): semi p:4261,o:t
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 340, Delta = -10
,D/daemonapp( 4890): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4890): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4890): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/QuickConnect[1.1][2] ( 4691): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
,V/QuickConnect[1.1][2] ( 4691): BleHelper.shouldScanBleBg - 
,D/QuickConnect[1.1][2] ( 4691): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4691): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422882b8
V/QuickConnect[1.1][2] ( 4691): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422882b8
V/QuickConnect[1.1][2] ( 4691): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 4691): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422882b8
V/QuickConnect[1.1][2] ( 4691): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422882b8
V/QuickConnect[1.1][2] ( 4691): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422882b8
D/QuickConnect[1.1][2] ( 4691): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 4691): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 4691): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 4691): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 4890): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4890): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 4890): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4890): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4890): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4890): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4890): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4890): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 4890): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4890): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/dalvikvm( 4890): GC_CONCURRENT freed 2604K, 28% free 10043K/13784K, paused 2ms+3ms, total 45ms
,D/daemonapp( 4890): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454703000000
,D/daemonapp( 4890): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454681738943
,D/daemonapp( 4890): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 4890): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 4890): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4890): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4890): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 4890): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 4890): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4890): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4890): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,D/PowerManagerService( 2422): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 4890): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,I/display ( 1922): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(6)
,D/daemonapp( 4890): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4890): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4890): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4890): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 4890): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4890): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4890): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4890): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4890): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4890): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 4890): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4890): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4890): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4890): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4890): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/dalvikvm( 5944): GC_EXPLICIT freed 875K, 28% free 10013K/13748K, paused 3ms+9ms, total 48ms
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster: data=-1 bt=false
,D/lights  ( 2422): button : 0 +
,D/lights  ( 2422): button : 0 -
,D/dalvikvm( 2845): GC_EXPLICIT freed 344K, 26% free 10313K/13756K, paused 4ms+7ms, total 51ms
,D/SSRMv2:TSP:AirViewOnOff( 2422): SettingsAirViewInfo:: 000000000
,D/SensorService( 2422):   0.2 -0.0 9.9
,D/dalvikvm( 5944): GC_EXPLICIT freed 871K, 28% free 10012K/13748K, paused 4ms+10ms, total 48ms
,I/display ( 1922): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(59)
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster - setNWBoosterIndicators(false)
,D/dalvikvm( 2845): GC_EXPLICIT freed 356K, 25% free 10319K/13756K, paused 5ms+8ms, total 56ms
D/STATUSBAR-NetworkController( 2594): refreshSignalCluster: data=-1 bt=false
,D/AmoledAdjustTimer( 2422): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,I/display ( 1922): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(7)
,D/dalvikvm( 5944): GC_EXPLICIT freed 872K, 28% free 10010K/13748K, paused 3ms+10ms, total 48ms
,D/dalvikvm( 2845): GC_EXPLICIT freed 359K, 25% free 10330K/13756K, paused 4ms+7ms, total 49ms
D/STATUSBAR-NetworkController( 2594): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2594): refreshSignalCluster: data=-1 bt=false
D/dalvikvm( 2422): GC_EXPLICIT freed 643K, 14% free 24459K/28124K, paused 8ms+17ms, total 200ms
D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
D/SensorService( 2422):   0.2 -0.0 9.9
,I/display ( 1922): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(60)
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 5944): GC_CONCURRENT freed 1473K, 24% free 10496K/13748K, paused 2ms+10ms, total 33ms
,I/SettingSearch/SearchIntentReceiver( 2845): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2845): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 2845): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/display ( 1922): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(7)
,I/SettingSearch/SearchIntentReceiver( 2845): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2845): LOCALE_CHANGED call search setting db finish!!
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2422): waitForAlarm result :4
,D/Headlines( 5465): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5465): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5465): Breath 40577 latestRequest time : 1454681705727 current time : 1454681746304
V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Finsky  ( 5121): [382] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5121): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/SensorService( 2422):   0.2 -0.1 9.8
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3364): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 340, Delta = 0
,E/Watchdog( 2422): !@Sync 3
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2422):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster: data=-1 bt=false
,D/AmoledAdjustTimer( 2422): prevTemp = 299, currTemp = 300, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2422):   0.2 -0.1 9.9
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,I/Icing   ( 3142): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/Icing   ( 3142): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2422):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2594): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2422): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2594 (0x0)
,I/PowerManagerService( 2422): Nap time...
,D/PowerManagerService( 2422): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2422): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2422): Going to sleep due to screen timeout...
,D/PowerManagerService( 2422): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2422): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2422): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/Sensors ( 2422): LightSensor enable = 0
,D/Sensors ( 2422): LightSensor enableSensor = 0
,D/SensorManager( 2422): unregisterListener ::   
D/DisplayPowerController( 2422): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,I/DisplayPowerController( 2422): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
I/SurfaceFlinger( 1922): id=19 createSurf (720x1280),-1 flag=20004, FlectronBea
I/Sensors ( 2422): HAL:resetDataRates mEnabled=4
,D/DisplayPowerController( 2422): !@ElectronBeam entry
D/SensorManager( 2422): unregisterListener ::   
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2422): lcd : 0 +
,D/lights  ( 2422): lcd : 0 -
D/PowerManagerService( 2422): blankAllDisplays() is called.
D/MISC PowerHAL( 2422): miscpower_set_interactive: /sys/class/input/input1/enabled
V/WindowOrientationListener( 2422): WindowOrientationListener disabled
,D/SensorService( 2422): AutoRotationSensor::activate (ident=0x7a8c9400, enabled=0)
I/Sensors ( 2422): HAL: batch Dry Run is complete
,D/MISC PowerHAL( 2422): sysfs_write +: /sys/class/input/input1/enabled: 0
,D/KeyguardViewMediator( 2594): onScreenTurnedOff(3),
D/MISC PowerHAL( 2422): sysfs_write -: /sys/class/input/input1/enabled: 0
D/PowerManagerService( 2422): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2422): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2422): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2422): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2422): sysfs_write +: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2422): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2422): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2422): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2422): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2422): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2422): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2422): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SensorManager( 2422): unregisterListener ::   
D/InputDispatcher( 2422): setInputDispatchMode: enabled=0, frozen=0
D/SEC PowerHAL( 2422): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2422): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2422): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2422): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SurfaceFlinger( 1922): Screen released, type=0 flinger=0x411ef550
,D/PowerManagerService( 2422): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/LockPatternUtils( 2594): isPcwEnable = 10
D/LockPatternUtils( 2594): isPcwEnable = 10
,D/SurfaceControl( 2422): Excessive delay in blankDisplay() while turning screen off: 189ms
,I/libsuspend( 2422): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2422): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2422): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 192ms
D/PowerManagerService( 2422): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2422): [PWL] Off : 0s ago
I/PowerManagerService( 2422): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2422): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2422): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=2422, ws=null) (elapsedTime=193)
I/PowerManagerService( 2422): [PWL]   PowerManagerService.Broadcasts: ref count=1
,I/display ( 1922): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(29)
,I/DBG_DM  ( 4261): [3.19.140541][Line:400][onPause] 
,I/SQLiteSecureOpenHelper( 3550): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3550): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 2594): setting alarm to turn off keyguard, seq = 2
,D/LightsService( 2422): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2422) 
,I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
D/Sensors ( 2422): LightSensor setDelay = 200000000
D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/Sensors ( 2422): Light sensor flush: not enabled 0
,D/Sensors ( 2422): LightSensor enable = 1
,D/Sensors ( 2422): LightSensor enableSensor = 1
D/LightsService( 2422): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2422): turn on LED for fully charged
D/VibratorService( 2422): JNI vibratorOff()
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2422): ACTION_SCREEN_OFF
D/LightsService( 2422): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2422) 
,D/LightsService( 2422): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2422): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2422): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2422): Bridge Server is not available
,D/PersonaManagerService( 2422): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2422): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2594):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2594): makeExpandedInvisible
D/PhoneStatusBarView( 2594): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2594):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2770): applyRouting return - 2 
,E/NfcService( 2770): callback == null
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/LockPatternUtils( 2594): isPcwEnable = 10
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 340, Delta = 0
,D/QuickConnect[1.1][2] ( 4691): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 4691): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4691): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4691): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422882b8
V/QuickConnect[1.1][2] ( 4691): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422882b8
D/QuickConnect[1.1][2] ( 4691): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4691): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4691): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4691): stopLeScan()
,D/QuickConnect[1.1][2] ( 4691): BleHelper.stopScan - call stopLeScan() complete
,D/PowerManagerService( 2422): [PWL] sb release: PowerManagerService.Broadcasts
,D/Sensors ( 2422): LightSensor enable = 0
,D/Sensors ( 2422): LightSensor enableSensor = 0
,D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 8
D/SensorManager( 2422): unregisterListener ::   
D/lights  ( 2422): led_pattern : 5 +
,D/lights  ( 2422): led_pattern : 5 -
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/FactoryTest( 5197): Not factory mode
,D/FactoryTest( 5197): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 5197): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5197): still no open session command from host, so toast
W/ContextImpl( 5197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy( 2422): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2422): mDVFSHelper.acquire()
,D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
I/SQLiteSecureOpenHelper( 3550): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3550): getDatabaseLocked(b,b,pwd)...
,E/MTPRx   ( 5197): started activity for popup
,E/SettingsReceiverActivity( 5197): PREF_DONT_ASK_AGAIN : true
D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
W/InputMethodManagerService( 2422): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@432e19c0 attribute=android.view.inputmethod.EditorInfo@42dcbf28, token = android.os.BinderProxy@422ae578
,D/SettingsReceiverActivity( 5197): dev.kiessupport is : TRUE
,I/DBG_DM  ( 4261): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4261): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 41
,I/DBG_DM  ( 4261): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4261): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4261): [3.19.140541][Line:418][onResume] Postpone Count : 41
,I/DBG_DM  ( 4261): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4261): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4261): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2422): sendNotification(2) - 4
I/DBG_DM  ( 4261): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 41
,I/DBG_DM  ( 4261): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4261): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4261): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4261): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4261): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4261): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4261): setTransGradationMode to true
,D/PhoneStatusBar( 2594): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2422): semi p:4261,o:t
I/DBG_DM  ( 4261): [3.19.140541][Line:400][onPause] 
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2422): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
V/AlarmManager( 2422): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2422): prevTemp = 300, currTemp = 301, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2422): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@8
,V/AlarmManager( 2422): waitForAlarm result :4
,D/KeyguardViewMediator( 2594): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/LockPatternUtils( 2594): isPcwEnable = 10
,D/KeyguardViewMediator( 2594): in doKeyguardLocked mIsRollUp false null
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/PersonaManager( 2594): isKioskContainerExistOnDevice
D/LockPatternUtils( 2594): isPcwEnable = 10
D/LockPatternUtils( 2594): isPcwEnable = 10
D/KeyguardViewMediator( 2594): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService( 2422): [PWL] Off : 5s ago
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@8
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 330, Delta = -10
,D/AmoledAdjustTimer( 2422): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2422): [PWL] Off : 15s ago,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2422): stay LED for fully charged,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3364): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 330, Delta = 0,
,E/Watchdog( 2422): !@Sync 4,
,V/AlarmManager( 2422): waitForAlarm result :4,
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5465): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5465): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5465): Breath 74689 latestRequest time : 1454681705727 current time : 1454681780416,
,D/dalvikvm( 3142): GC_CONCURRENT freed 2093K, 22% free 11935K/15200K, paused 9ms+7ms, total 62ms,
,I/VacuumService( 2748): Vacuum at: now=1454681780692 tag=VacuumService,
,I/PhenotypeConfigurator( 2748): Scheduling Phenotype for one-off execution 8999 seconds from now (1454681781189),
,D/GetConfigurationSnapshotOperation( 2748): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, ,
,I/PhenotypeFlagCommitter( 2748): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader,
,W/dalvikvm( 2748): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2748): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2748): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 2748): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
,W/dalvikvm( 2748): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2748): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2748): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 2748): GC_CONCURRENT freed 1795K, 21% free 11672K/14708K, paused 4ms+7ms, total 69ms
,D/LocationManagerService( 2422): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 2748): Thread-117(HTTPLog):isShipBuild true
,I/System.out( 2748): Thread-117(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/AmoledAdjustTimer( 2422): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/LocationManagerService( 2422): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 2748): GC_CONCURRENT freed 1378K, 18% free 12229K/14848K, paused 5ms+11ms, total 57ms
,D/LocationManagerService( 2422): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2422): [PWL] Off : 30s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 330, Delta = 0
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/AmoledAdjustTimer( 2422): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2422): waitForAlarm result :8,
,D/Headlines( 5465): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5465): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5465): Breath 90024 latestRequest time : 1454681705727 current time : 1454681795751,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2422): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2422): stay LED for fully charged,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3364): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2422): [PWL] Off : 50s ago,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2422): !@Sync 5,
,D/AmoledAdjustTimer( 2422): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2422): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3364): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3,
D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2422): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,V/AlarmManager( 2422): waitForAlarm result :8,
,D/Headlines( 5465): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5465): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5465): Breath 120028 latestRequest time : 1454681705727 current time : 1454681825755,
,D/Headlines( 5465): stop ,
,D/Headlines( 5465): Breath.onDestroy : ,
I/ActivityManager( 2422): Killing 5383:com.policydm/1000 (adj 15): empty #43
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2422): stay LED for fully charged,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3364): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2422): [PWL] Off : 75s ago,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2422): !@Sync 6,
,D/AmoledAdjustTimer( 2422): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
,D/BatteryService( 2422): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2422): [PWL] Off : 105s ago,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2422): !@Sync 7,
,D/AmoledAdjustTimer( 2422): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3364): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2422): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2422): [PWL] Off : 140s ago,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2422): !@Sync 8
,D/AmoledAdjustTimer( 2422): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2422): !@Sync 9,
,D/AmoledAdjustTimer( 2422): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2422): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2422): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3364): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = -10,
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2422): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4,
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2422): initializing...,
I/TLC_TIMA_PKM_initialize( 2422): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2422): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2422): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2422): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2422): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2422): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2422): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2422): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2422): device_id = 0x0
I/TZ: mc_tlc_communication( 2422): tlc_open() was called,
,I/TZ: mc_tlc_communication( 2422): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2422): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2422): Opening the session
,I/TZ: mc_tlc_communication( 2422): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2422): Trustlet response is completed,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;,
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 10,
,E/Watchdog( 2422): !@Sync 10,
,D/AmoledAdjustTimer( 2422): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = -10,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3364): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2422): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 10,
,D/AmoledAdjustTimer( 2422): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2422): [PWL] Off : 225s ago,
,V/AlarmManager( 2422): waitForAlarm result :4,
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 6857): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 6857):  
,I/SELinux ( 6857): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6857):  
I/SELinux ( 6857):  
,I/SELinux ( 6857): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6857): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6857): >>>>> Normal User
,E/dalvikvm( 6857): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 6857): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 6857): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 6857): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6857): Added TimaKesytore provider
,D/dalvikvm( 6857): GC_CONCURRENT freed 3004K, 31% free 9572K/13748K, paused 4ms+2ms, total 30ms,
,D/dalvikvm( 6857): WAIT_FOR_CONCURRENT_GC blocked 22ms,
,I/ActivityManager( 2422): Killing 5421:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43,
,E/Watchdog( 2422): !@Sync 11,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = -10,
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2422): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2422): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 12
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5098): [b] __PingReply__
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2422): GC_CONCURRENT freed 5032K, 20% free 25383K/31712K, paused 15ms+18ms, total 248ms
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 275s ago
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 13
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 14
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 15
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3364): Disconnected process message: 10
V/AlarmManager( 2422): waitForAlarm result :8
V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 16
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 17
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 18
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2594): GC_CONCURRENT freed 15702K, 34% free 33879K/50748K, paused 10ms+9ms, total 75ms
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 455s ago
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 19
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2422): !@Sync 20
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 525s ago
,E/Watchdog( 2422): !@Sync 21
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3364): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/GAV2    ( 5212): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5212): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 22
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 23
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 600s ago
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2422): <AppSync3 Whitelist>
,V/AlarmManager( 2422): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 3691): GC_CONCURRENT freed 2892K, 30% free 9728K/13812K, paused 3ms+3ms, total 38ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 24
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 25
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2422): GC_FOR_ALLOC freed 3455K, 21% free 25359K/31704K, paused 183ms, total 183ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 680s ago
,E/Watchdog( 2422): !@Sync 26
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 27
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 28
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 765s ago
,E/Watchdog( 2422): !@Sync 29
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2422): !@Sync 30
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 31
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :4
,D/LightsService( 2422): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
D/Sensors ( 2422): LightSensor setDelay = 200000000
D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/Sensors ( 2422): Light sensor flush: not enabled 0
,D/Sensors ( 2422): LightSensor enable = 1
,D/Sensors ( 2422): LightSensor enableSensor = 1
,D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors ( 2422): LightSensor enable = 0
D/Sensors ( 2422): LightSensor enableSensor = 0
,D/SensorManager( 2422): unregisterListener ::   
D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 5
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/ConnectivityService( 2422): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2594): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2594): getUpdateDataNetType() - mDataNetType:0
,D/STATUSBAR-NetworkController( 2594): updateDataNetType()
,D/STATUSBAR-NetworkController( 2594): NoService, mRoamingIconId = 0
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 855s ago
,E/Watchdog( 2422): !@Sync 32
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3364): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2422): waitForAlarm result :8
,E/SPPClientService( 5098): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 33
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 34
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 950s ago
,E/Watchdog( 2422): !@Sync 35
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 36
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 37
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 38
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2422): GC_FOR_ALLOC freed 3494K, 21% free 25277K/31704K, paused 204ms, total 204ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2594): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2594):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3364): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3364): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2594): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 39
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2594): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 8924
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2422): !@Sync 40
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 41
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2594): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2594): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2594): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 9045
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 9050
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 9055
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 9060
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 9063
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 9066
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1155s ago
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3142): Aggregate from 1454681065985 (log), 1454681065985 (data)
,E/Watchdog( 2422): !@Sync 42
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5098): [b] __PingReply__
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 43
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1200000ms)
```
