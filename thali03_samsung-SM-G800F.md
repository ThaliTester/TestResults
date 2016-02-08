#### Test 581356550b07fff_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
I/Icing   ( 3143): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
,I/Icing   ( 3143): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
D/dalvikvm( 2831): GC_EXPLICIT freed 528K, 26% free 10267K/13728K, paused 4ms+8ms, total 60ms
D/dalvikvm( 5849): GC_EXPLICIT freed 892K, 26% free 10149K/13688K, paused 3ms+6ms, total 37ms
D/AndroidRuntime( 6067): 
D/AndroidRuntime( 6067): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6067): CheckJNI is OFF
D/AndroidRuntime( 6067): setted country_code = Poland
D/AndroidRuntime( 6067): setted countryiso_code = PL
D/AndroidRuntime( 6067): setted sales_code = PLS
D/AndroidRuntime( 6067): readGMSProperty: start
D/AndroidRuntime( 6067): readGMSProperty: already setted!!
D/AndroidRuntime( 6067): readGMSProperty: end
D/AndroidRuntime( 6067): addProductProperty: start
D/dalvikvm( 6067): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6067): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6067): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6067): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6067): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6067): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6067): failed to load memtrack module: -2
D/dalvikvm( 6067): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6067): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 6067): Shutting down VM
D/dalvikvm( 6067): GC_CONCURRENT freed 99K, 13% free 714K/816K, paused 1ms+1ms, total 6ms
--------- beginning of /dev/log/system
W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SPPClientService( 5048): [b] __ProvisionReply__
E/SPPClientService( 5048): [a] [ConnectionManager] Connection is already disconnected.
E/SPPClientService( 5048): [d] null
V/AlarmManager( 2412):  next == MAX_VALUE
E/SPPClientService( 5048): [g] getPLMN return empty string
E/SPPClientService( 5048): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
E/SPPClientService( 5048): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
E/SPPClientService( 5048): [a] [ConnectionManager] Connection is already disconnected.
E/SPPClientService( 5048): [g] getNetMCC return empty string
D/dalvikvm( 5048): GC_CONCURRENT freed 2124K, 24% free 10423K/13684K, paused 4ms+4ms, total 60ms
I/ActivityManager( 2412): Waited long enough for: ServiceRecord{434abf00 u0 com.sec.spp.push/.PushClientService}
,D/dalvikvm( 2831): GC_EXPLICIT freed 345K, 26% free 10283K/13728K, paused 5ms+7ms, total 49ms
,I/ActivityManager( 2412): Killing 5191:com.vlingo.midas/u0a34 (adj 15): empty #43
,D/dalvikvm( 5849): GC_EXPLICIT freed 1024K, 27% free 10014K/13688K, paused 3ms+10ms, total 51ms
,D/SensorService( 2412):   0.2 -0.0 9.9
,D/PowerManagerService( 2412): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2583 (0x0)
I/PowerManagerService( 2412): Nap time...
,D/PowerManagerService( 2412): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2412): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2412): Going to sleep due to screen timeout...
,D/PowerManagerService( 2412): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2412): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/DisplayPowerController( 2412): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/Sensors ( 2412): LightSensor enable = 0
D/Sensors ( 2412): LightSensor enableSensor = 0
D/SensorManager( 2412): unregisterListener ::   
D/DisplayPowerController( 2412): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/DisplayPowerController( 2412): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
I/SurfaceFlinger( 1920): id=16 createSurf (720x1280),-1 flag=20004, FlectronBea
I/Sensors ( 2412): HAL:resetDataRates mEnabled=4
D/DisplayPowerController( 2412): !@ElectronBeam entry
,D/SensorManager( 2412): unregisterListener ::   
,D/BatteryService( 2412): level:100, scale:100, status:3, health:9, present:true, voltage: 4355, temperature: 311, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
D/PowerManagerService( 2412): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2412): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2412): Waking up from sleep...
,D/PowerManagerService( 2412): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2412): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerNotifier( 2412): mBroadcastInProgress = true , mActualPowerState = 1 , mPendingWakeUpBroadcast = true , mPendingGoToSleepBroadcast = true , mBroadcastedPowerState = 1
,D/PowerManagerService( 2412): [s] WAKEFULNESS_AWAKE
,D/PowerManagerService( 2412): [s] UserActivityState : 0 -> 1
,D/DisplayPowerController( 2412): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/lights  ( 2412): button : 1 +
D/lights  ( 2412): button : 1 -
I/DisplayPowerController( 2412): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
,D/DisplayPowerController( 2412): [DAB] setLightSensorEnabled : registerListener mLightSensor
V/WindowOrientationListener( 2412): WindowOrientationListener disabled
D/SensorService( 2412): AutoRotationSensor::activate (ident=0x89ae9230, enabled=0)
I/SensorManagerA( 2412): getReportingMode :: sensor.mType = 5
I/Sensors ( 2412): HAL: batch Dry Run is complete
,D/KeyguardViewMediator( 2583): onScreenTurnedOff(3)
D/PowerUI ( 2583): Overvoltage/Undervoltage (recovered) so turn on the screen.
I/DisplayPowerController( 2412): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/PowerManagerService( 2412): [api] [s] wakeUp (uid: 10019 pid: 2583) eventTime = 86123
D/DisplayPowerController( 2412): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2412): [DAB] no lux value from sensor manager
,D/DisplayPowerController( 2412): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 2412): lcd : 238 +
,D/Sensors ( 2412): LightSensor setDelay = 200000000
D/Sensors ( 2412): LightSensor setSensorDelay = 200000000
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/RampAnimator( 2412): Light Animator Finished currentValue=8
D/Sensors ( 2412): Light sensor flush: not enabled 0
D/Sensors ( 2412): LightSensor enable = 1
D/Sensors ( 2412): LightSensor enableSensor = 1
,D/SensorManager( 2412): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
I/SensorManagerA( 2412): getReportingMode :: sensor.mType = 1
,D/SensorManager( 2412): unregisterListener ::   
,D/PowerManagerService( 2412): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 19ms
I/Sensors ( 2412): HAL: batch Dry Run is complete
D/LockPatternUtils( 2583): isPcwEnable = 10
,D/LockPatternUtils( 2583): isPcwEnable = 10
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
I/Sensors ( 2412): HAL:resetDataRates mEnabled=4
D/lights  ( 2412): lcd : 238 -
D/lights  ( 2412): lcd : 8 +
D/InputDispatcher( 2412): setInputDispatchMode: enabled=0, frozen=0
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/UsbDeviceManager( 2412): handleMessage -> MSG_POWER_STATE = 0
D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/BatteryMeterView( 2583): onDraw batteryColor : -1
D/Launcher.HomeView( 2785): onPause
,D/lights  ( 2412): lcd : 8 -
,D/DisplayPowerController( 2412): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 2412): lcd : 0 +
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
D/KeyguardViewMediator( 2583): setting alarm to turn off keyguard, seq = 2
,D/SensorManager( 2412): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/PowerManagerService( 2412): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 62ms
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(52)
,I/SELinux ( 6088): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6088):  
,D/lights  ( 2412): lcd : 0 -
D/UsbDeviceManager( 2412): sending intent : ACTION_USB_CABLE_STATE : connected = false
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/NotificationService( 2412): cancelNotificationLocked
D/NotificationService( 2412):  hasClearableItems
D/NotificationService( 2412):  has clearable items no 
D/NotificationService( 2412): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2412): cancelNotificationLocked: cancel alarm
D/STATUSBAR-StatusBarManagerService( 2412): sendNotification(3) - 5
D/StatusBarManagerService( 2412): tr p:2785,o:f
D/LightsService( 2412): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2412) 
D/LightsService( 2412): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/UsbDeviceManager( 2412): received ACTION_POWER_DISCONNECTED = -1
D/LightsService( 2412): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2412): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/Launcher.HomeView( 2785): onStop
,D/VibratorService( 2412): JNI vibratorOff()
I/dalvikvm( 2412): Jit: resizing JitTable from 8192 to 16384
,I/SELinux ( 6088): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6088):  
I/SELinux ( 6088):  
,I/SELinux ( 6088): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6088): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6088): >>>>> Normal User
,E/dalvikvm( 6088): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 6088): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6088): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6088): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6088): Added TimaKesytore provider
,D/dalvikvm( 2412): GC_EXPLICIT freed 993K, 17% free 24354K/29232K, paused 30ms+27ms, total 334ms
,I/WifiTrafficPoller( 2412): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2412): ACTION_SCREEN_OFF
,D/LightsService( 2412): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2412) 
D/LightsService( 2412): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/DisplayPowerController( 2412): [api] [DAB] onSensorChanged : 1st lux : 0.0
D/DisplayPowerController( 2412): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,D/LightsService( 2412): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2412): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=off)
,I/SecExternalDisplayIntents_Java( 2412): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2412): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2412): Bridge Server is not available
,D/PersonaManagerService( 2412): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2412): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2583): makeExpandedInvisible
D/PhoneStatusBarView( 2583): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2759): applyRouting return - 2 
,E/NfcService( 2759): callback == null
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
D/dalvikvm( 6088): GC_CONCURRENT freed 3000K, 31% free 9572K/13688K, paused 4ms+3ms, total 37ms
D/dalvikvm( 6088): WAIT_FOR_CONCURRENT_GC blocked 31ms
,V/AlarmManager( 2412): waitForAlarm result :4
,D/Finsky  ( 5068): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager( 2412): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 5068): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5068): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5068): VFY: replacing opcode 0x62 at 0x0038
,D/LockPatternUtils( 2583): isPcwEnable = 10
,I/SELinux ( 6104): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6104):  
,I/ActivityManager( 2412): Killing 5332:com.policydm/1000 (adj 15): empty #43
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 370, Delta = 0
,D/QuickConnect[1.1][2] ( 4632): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 4632): BleHelper.shouldScanBleBg - 
,D/QuickConnect[1.1][2] ( 4632): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50
,V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50
,D/QuickConnect[1.1][2] ( 4632): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4632): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4632): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4632): stopLeScan()
D/QuickConnect[1.1][2] ( 4632): BleHelper.stopScan - call stopLeScan() complete
I/SELinux ( 6104): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6104):  
I/SELinux ( 6104):  
I/SELinux ( 6104): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6104): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6104): >>>>> Normal User
E/dalvikvm( 6104): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
,E/SELinux ( 6104): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6104): in addTimaSignatureService
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 6104): Cannot add TimaSignature Service, License check Failed
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(3)
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityThread( 6104): Added TimaKesytore provider
I/SensorManagerA( 2412): getReportingMode :: sensor.mType = 65558
,D/SensorService( 2412): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2412): AutoRotationSensor::activate (ident=0x7a2e3a08, enabled=1)
D/SensorService( 2412): AutoRotationSensor::AR_init
I/Sensors ( 2412): HAL: batch Dry Run is complete
,I/Sensors ( 2412): HAL:resetDataRates mEnabled=4,
,D/SensorService( 2412): AutoRotationSensor::process: Acc  eventTimestamp = 86370150210, previousAccTimestamp = 86034535626, difference = 335614584 ,
D/SensorService( 2412): AutoRotationSensor::reset oldrotation = [100], initState = [1],
D/SensorManager( 2412): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  ,
,V/KeyguardServiceDelegate( 2412): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@43198790)
,D/InputDispatcher( 2412): setInputDispatchMode: enabled=1, frozen=0,
D/KeyguardViewMediator( 2583): onScreenTurnedOn, seq = 3
,D/KeyguardViewMediator( 2583): notifyScreenOnLocked,
D/KeyguardViewMediator( 2583): handleNotifyScreenOn
D/KeyguardViewManager( 2583): onScreenTurnedOn()
I/KeyguardEffectViewMain( 2583): *** KeyguardEffectView getInstance ***
,D/VisualEffectParticleEffect( 2583): KeyguardEffectViewParticleSpace : screenTurnedOn
D/VisualEffectParticleEffect( 2583): screenOnAnimationStart
V/KeyguardViewManager( 2583): send wm null token: host was null,
,V/KeyguardServiceDelegate( 2412): **** SHOWN CALLED ****
,D/LockPatternUtils( 2583): isPcwEnable = 10
,I/SurfaceFlinger( 1920): id=16 Removed FlectronBea (8/8)
D/Launcher( 2785): onRestart, Launcher: 1114775344
D/Launcher( 2785): onStart, Launcher: 1114775344
,D/Launcher.HomeView( 2785): onStart
I/WindowManager( 2412): No lock screen! windowToken=null
D/PowerManagerNotifier( 2412): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2412): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2412): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2412): !@ElectronBeam exit
D/lights  ( 2412): lcd : 8 +
,D/lights  ( 2412): lcd : 8 -
,D/LockPatternUtils( 2583): isPcwEnable = 10
D/DisplayPowerController( 2412): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2412): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/LightsService( 2412): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2412) 
,D/LightsService( 2412): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2412): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,I/FPMS_FingerprintManagerService( 2603): onReceive: android.intent.action.USER_PRESENT
D/PalmMotionService( 2412): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2412): SURFACE_PALM_SWIPE: 1
D/LightsService( 2412): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/MotionRecognitionService( 2412):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/SamsungIME( 2973): showDlgMsgBox : false true true
,I/NfcService( 2759): applyRouting return - 2 
,E/NfcService( 2759): callback == null
,D/SSRMv2:TSP:AirViewOnOff( 2412): SettingsAirViewInfo:: 000000000
,D/Launcher( 2785): onResume, Launcher: 1114775344
,D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/Launcher.HomeView( 2785): onResume
D/StatusBarManagerService( 2412): semi p:2785,o:f
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2412): tr p:2785,o:f
D/StatusBarManagerService( 2412): semi p:2785,o:f
,D/MenuAppsGridFragment( 2785): onResume
,I/WifiTrafficPoller( 2412): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2412): ACTION_SCREEN_ON
D/LightsService( 2412): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2412) 
D/LightsService( 2412): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2412): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2412): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=on)
I/SecExternalDisplayIntents_Java( 2412): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
I/dalvikvm( 2847): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
W/dalvikvm( 2847): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/dalvikvm( 2847): VFY: replacing opcode 0x6e at 0x0046
D/dalvikvm( 6104): GC_CONCURRENT freed 3003K, 31% free 9566K/13684K, paused 3ms+4ms, total 27ms
D/dalvikvm( 6104): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/SensorService( 2412): AutoRotationSensor::process: Acc  eventTimestamp = 86633599668, previousAccTimestamp = 86034535626, difference = 599064042 
D/SensorService( 2412):  [AR] 0.2 -0.0 9.9
D/SensorService( 2412): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,I/KIES_RECEIVE( 6104): [APK BnR] Receive KIES_USB_DISCONNECT
D/IpRemoteDisplayController( 2412): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2412): Bridge Server is not available
,W/ContextImpl( 6104): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
D/PersonaManagerService( 2412): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 2412): MSG_ACTION_SCREEN_ON called
I/NfcService( 2759): NFC: Screen On & Cover Open
I/NfcService( 2759): applyRouting return - 2 
,E/NfcService( 2759): callback == null
,E/TranscodeReceiver( 5871): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
D/STATUSBAR-NetworkController( 2583): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,D/videowall-Global( 5871): core_num = 4
,D/dalvikvm( 5871): No JNI_OnLoad found in /system/lib/libsavsff.so 0x4235e5d8, skipping init
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,W/linker  ( 5871): libvwengine.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/videowall-Global( 5871): density : 2.0 width : 720 height : 1280 Raw width : 720 Raw height : 1280
,D/videowall-Global( 5871): dsp : 720, swkey : false, Cores : 4, Clock : 0
,I/SELinux ( 6120): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6120):  
,I/SELinux ( 6120): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6120):  
I/SELinux ( 6120):  
,I/SELinux ( 6120): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6120): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 6120): >>>>> Normal User
,E/dalvikvm( 6120): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 6120): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 6120): in addTimaSignatureService
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 370, Delta = 0
D/TimaKeyStoreProvider( 6120): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6120): Added TimaKesytore provider
,D/QuickConnect[1.1][2] ( 4632): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
,V/QuickConnect[1.1][2] ( 4632): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4632): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50
V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50
V/QuickConnect[1.1][2] ( 4632): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50
V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50
V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50
D/QuickConnect[1.1][2] ( 4632): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 4632): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 4632): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 4632): BleHelper.startScan - shouldScanBleFg = false
,E/SPPClientService( 5048): [b] __InitReply__
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 4835): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,I/System.out( 5068): Thread-366(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/PowerManagerService( 2412): [PWL] sb release: PowerManagerService.Broadcasts
,W/IcingInternalCorpora( 3143): getNumBytesRead when not calculated.
,I/System.out( 5068): Thread-366(ApacheHTTPLog):isShipBuild true
,I/System.out( 5068): Thread-366(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 6120): GC_CONCURRENT freed 2995K, 31% free 9581K/13688K, paused 5ms+2ms, total 28ms
,D/dalvikvm( 6120): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 334K, 26% free 10295K/13728K, paused 3ms+7ms, total 40ms
,I/SELinux ( 6138): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6138):  
,I/ActivityManager( 2412): Killing 5370:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 11% free 9504K/10664K, paused 4ms+4ms, total 44ms
,I/SELinux ( 6138): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6138):  
I/SELinux ( 6138):  
,I/SELinux ( 6138): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6138): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 6138): >>>>> Normal User
,E/dalvikvm( 6138): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
,E/SELinux ( 6138): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9504K/10664K, paused 4ms+4ms, total 33ms
,D/TimaKeyStoreProvider( 6138): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6138): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6138): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9504K/10664K, paused 3ms+3ms, total 30ms
,D/dalvikvm( 5849): GC_EXPLICIT freed 897K, 27% free 10009K/13688K, paused 3ms+6ms, total 41ms
,D/dalvikvm( 6138): GC_CONCURRENT freed 2999K, 31% free 9575K/13688K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 6138): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/iu.Environment( 5480): update battery state; isPlugged? false*
,I/iu.SyncManager( 5480): SYNC; picasa accounts
,I/ActivityManager( 2412): Killing 5427:com.google.android.apps.magazines/u0a115 (adj 15): empty #43
,I/iu.Environment( 3143): update battery state; isPlugged? false*
,I/iu.UploadsManager( 5480): num queued entries: 0
,I/iu.UploadsManager( 5480): num updated entries: 0
,I/iu.SyncManager( 5480): NEXT; no task
,I/GCoreUlr( 2737): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,I/iu.UploadsManager( 3143): num queued entries: 0
,I/iu.UploadsManager( 3143): num updated entries: 0
,I/iu.SyncManager( 3143): NEXT; no task
,D/PicasaUploader( 6138):    wifiOnlyPhoto changed to true
,D/PicasaUploader( 6138):    wifiOnlyVideo changed to true
,D/PicasaUploader( 6138):    syncOnBattery changed to true
,I/GCoreUlr( 2737): DispatchingService.onCreate()
,D/PicasaUploaderSync( 6138): sync account database
,D/PicasaUploaderSync( 6138): accounts in DB=1
,D/PicasaUploaderSyncManager( 6138): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PicasaUploaderSyncManager( 6138): background data: true
,D/PicasaUploaderSyncManager( 6138): battery info: false
,D/LockPatternUtils( 2583): isPcwEnable = 10
,I/GCoreUlr( 2737): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/Mms/UIEventReceiver( 5229): ui event
,D/lights  ( 2412): button : 0 +
,D/lights  ( 2412): button : 0 -
,I/GCoreUlr( 2737): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2737): Unbound from all location providers
,I/GCoreUlr( 2737): Place inference reporting - stopped
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 4835): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4835): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4835): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4835): [MSC_Daemon]>>> ====================================================================================================================
I/GCoreUlr( 2737): DispatchingService.onDestroy()
,I/GCoreUlr( 2737): Stopping handler for UlrDispSvcFast
D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
I/GCoreUlr( 2737): Unbound from all location providers
,I/GCoreUlr( 2737): Place inference reporting - stopped
,D/SSRMv2:TSP:AirViewOnOff( 2412): SettingsAirViewInfo:: 000000000
D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454951100000
D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454950401861
D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 4835): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 4835): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4835): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 4835): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4835): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,I/System.out( 5068): Thread-366 calls detatch()
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5068): Failed write_ctrl(u 68) res=-1 errno=22
,I/qtaguid ( 5068): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5068): untagSocket(68) failed with errno -22
,I/System.out( 5068): Thread-367 calls detatch()
,D/Finsky  ( 5068): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5068): Failed write_ctrl(u 68) res=-1 errno=22
,I/qtaguid ( 5068): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5068): untagSocket(68) failed with errno -22
,I/System.out( 5068): Thread-366 calls detatch()
,D/dalvikvm( 5068): GC_CONCURRENT freed 1960K, 23% free 10676K/13748K, paused 3ms+5ms, total 54ms
,D/dalvikvm( 5068): WAIT_FOR_CONCURRENT_GC blocked 27ms
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5068): GC_CONCURRENT freed 689K, 14% free 12026K/13836K, paused 3ms+3ms, total 48ms
,D/dalvikvm( 5068): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/SensorService( 2412):   0.2 -0.0 9.9
,D/dalvikvm( 5068): GC_FOR_ALLOC freed 1351K, 19% free 12397K/15168K, paused 26ms, total 26ms
,D/dalvikvm( 5068): GC_FOR_ALLOC freed 1491K, 21% free 13195K/16576K, paused 24ms, total 25ms
,D/dalvikvm( 2412): GC_EXPLICIT freed 1210K, 17% free 24416K/29232K, paused 6ms+13ms, total 165ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 356K, 25% free 10298K/13728K, paused 4ms+7ms, total 44ms
,D/dalvikvm( 5849): GC_EXPLICIT freed 901K, 27% free 10017K/13688K, paused 3ms+7ms, total 38ms
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2412): prevTemp = 310, currTemp = 311, prevStep = 4, currStep = 4
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PackageManager( 2412): [MSG] MCS_UNBIND
I/PackageManager( 2412): calling disconnectService()
,D/PackageManager( 2412): Trying to unbind to DefaultContainerService
,I/ActivityManager( 2412): Killing 5433:com.samsung.android.magazine.service/u0a110 (adj 15): empty #43
,I/ActivityManager( 2412): Waited long enough for: ServiceRecord{432a6710 u0 com.sec.android.gallery3d/.app.BackgroundCache}
,I/qtaguid ( 5068): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5068): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5068): untagSocket(68) failed with errno -22
,I/System.out( 5068): Thread-367 calls detatch()
,D/KeyguardViewMediator( 2583): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 3
V/AlarmManager( 2412): waitForAlarm result :4
V/AlarmManager( 2412): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 2831): GC_EXPLICIT freed 361K, 25% free 10303K/13728K, paused 4ms+6ms, total 45ms
,D/dalvikvm( 5849): GC_EXPLICIT freed 905K, 27% free 10015K/13688K, paused 3ms+8ms, total 41ms
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 5068): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 2412): waitForAlarm result :4
,V/AlarmManager( 2412): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/WearableService( 2737): callingUid 10012, callindPid: 2737
,D/DeviceConnectionService( 2737): client connected with version: 8296000
,D/Finsky  ( 5068): [390] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5068): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5068): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5068): Thread-377(HTTPLog):isShipBuild true
,I/System.out( 5068): Thread-377(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/SensorService( 2412):   0.2 -0.0 9.9
,D/dalvikvm( 5849): GC_EXPLICIT freed 886K, 27% free 10004K/13688K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 351K, 25% free 10306K/13728K, paused 5ms+7ms, total 48ms
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 2412): GC_EXPLICIT freed 825K, 17% free 24437K/29232K, paused 9ms+14ms, total 195ms
,D/dalvikvm( 5849): GC_EXPLICIT freed 865K, 27% free 10017K/13688K, paused 3ms+10ms, total 49ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 357K, 25% free 10306K/13728K, paused 4ms+7ms, total 42ms
,D/SensorService( 2412):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2412): level:100, scale:100, status:2, health:2, present:true, voltage: 4346, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UsbDeviceManager( 2412): handleMessage -> MSG_POWER_STATE = 1
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/PowerManagerService( 2412): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/PowerUI ( 2583): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2412): [api] [s] wakeUp (uid: 10019 pid: 2583) eventTime = 96133
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/PowerUI ( 2583): playSound : 1
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
I/EntropyMixer( 2412): Writing entropy...
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,V/Vibrator( 2583): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
,V/Vibrator( 2583): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
D/UsbDeviceManager( 2412): sending intent : ACTION_USB_CABLE_STATE : connected = true
V/VibratorService( 2412): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2412): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2412): JNI vibratorOff()
D/VibratorService( 2412): JNI vibratorOn() : 100
D/PowerUI ( 2583): RINGER_MODE_VIBRATE
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,E/TranscodeReceiver( 5871): onReceive : android.intent.action.ACTION_POWER_CONNECTED
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,D/BatteryMeterView( 2583): onDraw batteryColor : -1
,D/TranscodeService( 5871): onCreate()
,I/SELinux ( 6166): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6166):  
,D/dalvikvm( 5871): No JNI_OnLoad found in /system/lib/libsavsvc.so 0x4235e5d8, skipping init
,D/dalvikvm( 5871): No JNI_OnLoad found in /system/lib/libsavscmn.so 0x4235e5d8, skipping init
,D/dalvikvm( 5871): No JNI_OnLoad found in /system/lib/libsthmb.so 0x4235e5d8, skipping init
,D/TranscodeService( 5871): power? : true / screen off : false
,D/TranscodeService( 5871): releaseTranscodeThread.
,D/VibratorService( 2412): JNI vibratorOff()
,I/SELinux ( 6166): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6166):  
I/SELinux ( 6166):  
,I/SELinux ( 6166): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6166): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6166): >>>>> Normal User
,E/dalvikvm( 6166): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 6166): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6166): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6166): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6166): Added TimaKesytore provider
,D/dalvikvm( 6166): GC_CONCURRENT freed 2997K, 31% free 9575K/13688K, paused 3ms+3ms, total 29ms
,D/dalvikvm( 6166): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/sCloudBackupApp( 6166): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 6166): Other Intent
,D/PicasaUploaderSyncManager( 6138): battery info: true
,I/iu.Environment( 5480): update battery state; isPlugged? true*
,I/iu.UploadsManager( 5480): num queued entries: 0
,I/iu.UploadsManager( 5480): num updated entries: 0
,I/iu.FingerprintManager( 5480): Start processing all media
,I/iu.FingerprintManager( 5480): Start processing media store URI: content://media/external/images/media
,I/iu.SyncManager( 5480): NEXT; no task
,I/iu.Environment( 3143): update battery state; isPlugged? true*
,I/iu.UploadsManager( 3143): num queued entries: 0
,I/iu.UploadsManager( 3143): num updated entries: 0
,I/iu.SyncManager( 3143): NEXT; no task
,I/iu.FingerprintManager( 5480): Start processing media store URI: content://media/external/video/media
,E/NetworkScheduler.SchedulerReceiver( 2847): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2847): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/iu.FingerprintManager( 3143): Start processing all media,
,I/GCoreUlr( 2737): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}],
,I/iu.FingerprintManager( 3143): Start processing media store URI: content://media/external/images/media,
,I/GCoreUlr( 2737): DispatchingService.onCreate(),
,I/iu.FingerprintManager( 5480): Start processing media store URI: content://media/phoneStorage/images/media,
,I/iu.FingerprintManager( 5480): Start processing media store URI: content://media/phoneStorage/video/media,
,I/iu.FingerprintManager( 3143): Start processing media store URI: content://media/external/video/media,
I/iu.FingerprintManager( 5480): Finished generating fingerprints; 0.093 seconds
,I/iu.FingerprintManager( 5480):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0,
,I/iu.FingerprintManager( 3143): Start processing media store URI: content://media/phoneStorage/images/media,
,I/iu.FingerprintManager( 3143): Start processing media store URI: content://media/phoneStorage/video/media,
,I/iu.FingerprintManager( 3143): Finished generating fingerprints; 0.087 seconds
,I/iu.FingerprintManager( 3143):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,I/GCoreUlr( 2737): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/GCoreUlr( 2737): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2737): Unbound from all location providers
,I/GCoreUlr( 2737): Place inference reporting - stopped
,I/GCoreUlr( 2737): DispatchingService.onDestroy()
,I/GCoreUlr( 2737): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2737): Unbound from all location providers
,I/GCoreUlr( 2737): Place inference reporting - stopped
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 360, Delta = -10
,D/dalvikvm( 5849): GC_EXPLICIT freed 873K, 27% free 10015K/13688K, paused 4ms+9ms, total 46ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 345K, 25% free 10311K/13728K, paused 4ms+7ms, total 50ms
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 2412): GC_EXPLICIT freed 537K, 17% free 24466K/29232K, paused 8ms+15ms, total 207ms
,D/SensorService( 2412):   0.2 -0.0 9.9
,D/dalvikvm( 5849): GC_EXPLICIT freed 871K, 27% free 10014K/13688K, paused 3ms+9ms, total 45ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 351K, 25% free 10316K/13728K, paused 4ms+7ms, total 48ms
,D/AmoledAdjustTimer( 2412): prevTemp = 311, currTemp = 312, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 5849): GC_EXPLICIT freed 872K, 27% free 10012K/13688K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 2831): GC_EXPLICIT freed 357K, 25% free 10327K/13728K, paused 5ms+7ms, total 49ms
,I/ActivityManager( 2412): Waited long enough for: ServiceRecord{434a6bc0 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/SensorService( 2412):   0.2 -0.0 9.9
,D/dalvikvm( 5849): GC_CONCURRENT freed 1496K, 24% free 10511K/13688K, paused 8ms+8ms, total 38ms
,I/SettingSearch/SearchIntentReceiver( 2831): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2831): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 2831): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 2831): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2831): LOCALE_CHANGED call search setting db finish!!
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager( 2412): waitForAlarm result :4
,D/Headlines( 5415): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,V/AlarmManager( 2412): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/Headlines( 5415): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 5415): Breath 41077 latestRequest time : 1454950378155 current time : 1454950419232
,D/Finsky  ( 5068): [379] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5068): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/SensorService( 2412):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2412): level:100, scale:100, status:2, health:2, present:true, voltage: 4368, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 350, Delta = -10
,E/Watchdog( 2412): !@Sync 3
,D/SensorService( 2412):   0.2 -0.1 9.9
,D/AmoledAdjustTimer( 2412): prevTemp = 312, currTemp = 313, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2412): Waited long enough for: ServiceRecord{434ac8a8 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2412):   0.2 -0.0 9.8
,I/Icing   ( 3143): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music
,I/Icing   ( 3143): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SensorService( 2412):   0.2 -0.1 9.8
,D/BatteryService( 2412): level:100, scale:100, status:2, health:2, present:true, voltage: 4381, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 350, Delta = 0
,D/FactoryTest( 5143): Not factory mode
,D/FactoryTest( 5143): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 5143): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5143): still no open session command from host, so toast
W/ContextImpl( 5143): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5143): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy( 2412): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService( 2412): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2412  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2412): mDVFSHelper.acquire()
I/SurfaceFlinger( 1920): id=17 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1920): id=18 createSurf (16x16),-1 flag=20004, EimLayer
,D/Launcher.HomeView( 2785): onPause
D/PointerIcon( 2412): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2412): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2412): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2412): setHoveringSpenCustomIcon IconType is same.1
E/MTPRx   ( 5143): started activity for popup
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2412): tr p:2785,o:f
,E/SettingsReceiverActivity( 5143): PREF_DONT_ASK_AGAIN : true
D/PointerIcon( 2412): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2412): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2412): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2412): setHoveringSpenCustomIcon IconType is same.1
D/StatusBarManagerService( 2412): tr p:2785,o:f
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2412): semi p:2785,o:f
,W/InputMethodManagerService( 2412): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@423856e8 attribute=android.view.inputmethod.EditorInfo@43456da8, token = android.os.BinderProxy@42cbcdf0
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,I/SQLiteSecureOpenHelper( 3541): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3541): getDatabaseLocked(b,b,pwd)...
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SettingsReceiverActivity( 5143): dev.kiessupport is : TRUE
,D/Launcher( 2785): onResume, Launcher: 1114775344
,D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2412): semi p:2785,o:f
,D/Launcher.HomeView( 2785): onResume
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/MenuAppsGridFragment( 2785): onResume
D/StatusBarManagerService( 2412): tr p:2785,o:f
D/StatusBarManagerService( 2412): semi p:2785,o:f
,D/Mms/UIEventReceiver( 5229): ui event
,I/SurfaceFlinger( 1920): id=18 Removed EimLayer (5/9)
I/SurfaceFlinger( 1920): id=17 Removed EimLayer (4/8)
I/SurfaceFlinger( 1920): id=18 Removed EimLayer (-2/8)
,I/SurfaceFlinger( 1920): id=17 Removed EimLayer (-2/8)
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(15)
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/SensorService( 2412):   0.2 -0.1 9.9
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/PowerManagerService( 2412): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2412): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2412): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2412): lcd : 2 +
D/RampAnimator( 2412): Light Animator Finished currentValue=2
,D/lights  ( 2412): lcd : 2 -
,D/AmoledAdjustTimer( 2412): prevTemp = 313, currTemp = 313, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService( 2412): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2412  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2412): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2412): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2412  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/CustomFrequencyManagerService( 2412): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2412  tag : ACTIVITY_RESUME_BOOSTER@8
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2412):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2412):   0.2 -0.1 9.9
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2412): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2412): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
V/AlarmManager( 2412): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4835): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 4835): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4835): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4835): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4835): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 4835): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/PowerManagerService( 2412): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2412): Nap time...
,D/PowerManagerService( 2412): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2412): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2412): Going to sleep due to screen timeout...
,D/PowerManagerService( 2412): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController( 2412): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,D/DisplayPowerController( 2412): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
D/Sensors ( 2412): LightSensor enable = 0
,D/Sensors ( 2412): LightSensor enableSensor = 0
,I/SurfaceFlinger( 1920): id=19 createSurf (720x1280),-1 flag=20004, FlectronBea
,I/DisplayPowerController( 2412): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,I/DisplayPowerController( 2412): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,D/SensorManager( 2412): unregisterListener ::   
I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(10)
,I/Sensors ( 2412): HAL:resetDataRates mEnabled=4
,D/DisplayPowerController( 2412): !@ElectronBeam entry
D/SensorManager( 2412): unregisterListener ::   
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/PowerManagerService( 2412): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2583
I/PowerManagerService( 2412): !@[ps] Screen__On(wake lock) :  wl: PowerUI
I/PowerManagerService( 2412): Waking up from sleep...
D/PowerManagerService( 2412): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2412): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerNotifier( 2412): mBroadcastInProgress = true , mActualPowerState = 1 , mPendingWakeUpBroadcast = true , mPendingGoToSleepBroadcast = true , mBroadcastedPowerState = 1
,D/lights  ( 2412): button : 1 +
,D/lights  ( 2412): button : 1 -
D/PowerManagerService( 2412): [s] WAKEFULNESS_AWAKE
D/DisplayPowerController( 2412): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
,I/DisplayPowerController( 2412): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/WindowOrientationListener( 2412): WindowOrientationListener disabled
D/SensorService( 2412): AutoRotationSensor::activate (ident=0x7a2e3a08, enabled=0)
I/Sensors ( 2412): HAL: batch Dry Run is complete
,I/SensorManagerA( 2412): getReportingMode :: sensor.mType = 5
,D/KeyguardViewMediator( 2583): onScreenTurnedOff(3)
D/DisplayPowerController( 2412): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/DisplayPowerController( 2412): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2412): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2412): [DAB] no lux value from sensor manager
D/DisplayPowerController( 2412): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/SensorManager( 2412): unregisterListener ::   
D/Sensors ( 2412): LightSensor setDelay = 200000000
D/Sensors ( 2412): LightSensor setSensorDelay = 200000000
D/Sensors ( 2412): Light sensor flush: not enabled 0
D/Sensors ( 2412): LightSensor enable = 1
,D/Sensors ( 2412): LightSensor enableSensor = 1
,D/InputDispatcher( 2412): setInputDispatchMode: enabled=0, frozen=0
,D/NotificationService( 2412): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
,D/STATUSBAR-StatusBarManagerService( 2412): sendNotification(1) - 5
D/LockPatternUtils( 2583): isPcwEnable = 10
,D/SensorManager( 2412): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SensorManagerA( 2412): getReportingMode :: sensor.mType = 1
W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
,D/PowerManagerService( 2412): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 17ms
,D/LockPatternUtils( 2583): isPcwEnable = 10
,I/Sensors ( 2412): HAL: batch Dry Run is complete
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
D/Launcher.HomeView( 2785): onPause
I/Sensors ( 2412): HAL:resetDataRates mEnabled=4
,D/StatusBarManagerService( 2412): tr p:2785,o:f
D/RCPManagerService( 2412): NotificationReceiver onReceive()
D/RCPManagerService( 2412):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
D/RCPManagerService( 2412): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298412
D/RCPManagerService( 2412): getPolicy: policy value returned = false
D/RCPManagerService( 2412): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2412): app label == com.android.systemui
,D/RCPManagerService( 2412): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298412
,D/KeyguardViewMediator( 2583): setting alarm to turn off keyguard, seq = 3
,D/UserManagerService( 2412): User -1does not exists!!
D/RCPManagerService( 2412): getPolicy: policy value returned = true
,D/RCPManagerService( 2412): Calling User is -1
,D/RCPManagerService( 2412): userid of SBN ==-1
E/PersonaManagerService( 2412): returning null in  getPersonasForUser
,D/SensorManager( 2412): registerListener :: 2, MPL Accelerometer, 200000, 0,  
,D/PowerManagerService( 2412): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 39ms
D/ProgressBar( 2583): setProgressDrawable drawableHeight = 12
,D/Launcher.HomeView( 2785): onStop
D/PhoneStatusBar( 2583): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@42376be8
,D/LightsService( 2412): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2412) 
,I/SensorManagerA( 2412): getReportingMode :: sensor.mType = 5
,D/SensorManager( 2412): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/LightsService( 2412): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 2412): turn on LED for fully charged
D/VibratorService( 2412): JNI vibratorOff()
,D/BatteryMeterView( 2583): onDraw batteryColor : -1
,D/lights  ( 2412): lcd : 0 +
,D/DisplayPowerController( 2412): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  ( 2412): lcd : 0 -
,I/WifiTrafficPoller( 2412): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2412): ACTION_SCREEN_OFF,
D/LightsService( 2412): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2412) 
,D/LightsService( 2412): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2412): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2412): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2412): Bridge Server is not available
,D/PersonaManagerService( 2412): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2412): MSG_ACTION_SCREEN_OFF called
,D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is received!!!! 
,D/STATUSBAR-PhoneStatusBar( 2583): makeExpandedInvisible
D/PhoneStatusBarView( 2583): marqueeStatusBar:123, mClearCover:0
,D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2759): applyRouting return - 2 
,E/NfcService( 2759): callback == null
,D/Sensors ( 2412): LightSensor sending flush event 16
D/Sensors ( 2412): LightSensor setDelay = 200000000
,D/Sensors ( 2412): LightSensor setSensorDelay = 200000000
D/LightsService( 2412): [SvcLED]  onSensorChanged::light value = 0
D/DisplayPowerController( 2412): [api] [DAB] onSensorChanged : 1st lux : 0.0
,D/DisplayPowerController( 2412): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
D/SensorManager( 2412): unregisterListener ::   
D/lights  ( 2412): led_pattern : 5 +
,D/lights  ( 2412): led_pattern : 5 -
D/LightsService( 2412): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/LockPatternUtils( 2583): isPcwEnable = 10
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 350, Delta = 0
,D/QuickConnect[1.1][2] ( 4632): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 4632): BleHelper.shouldScanBleBg - 
,D/QuickConnect[1.1][2] ( 4632): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50
,V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50
D/QuickConnect[1.1][2] ( 4632): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4632): BleHelper.stopScan - shouldScanBleBg = false
,I/QuickConnect[1.1][2] ( 4632): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4632): stopLeScan()
,D/QuickConnect[1.1][2] ( 4632): BleHelper.stopScan - call stopLeScan() complete,
,E/TranscodeReceiver( 5871): onReceive : android.intent.action.SCREEN_OFF,
,D/TranscodeService( 5871): power? : true / screen off : true,
D/TranscodeService( 5871): Music is = false
,D/TranscodeService( 5871): runvideoplayer is false
,I/SensorManagerA( 2412): getReportingMode :: sensor.mType = 65558
D/SensorService( 2412): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2412): AutoRotationSensor::activate (ident=0x729bbd40, enabled=1)
D/SensorService( 2412): AutoRotationSensor::AR_init
,I/Sensors ( 2412): HAL: batch Dry Run is complete
,D/TranscodeService( 5871): Thread start
,I/Sensors ( 2412): HAL:resetDataRates mEnabled=4
D/TranscodeService( 5871): WakeLock.acquire()
,D/videowall-FileMgr( 5871): thumbnailDBSync -1
,D/SensorService( 2412): AutoRotationSensor::process: Acc  eventTimestamp = 126510320355, previousAccTimestamp = 126127471144, difference = 382849211 
D/SensorManager( 2412): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
D/SensorService( 2412): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,V/KeyguardServiceDelegate( 2412): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@4302c340)
,D/InputDispatcher( 2412): setInputDispatchMode: enabled=1, frozen=0
D/Launcher( 2785): onRestart, Launcher: 1114775344
D/Launcher( 2785): onStart, Launcher: 1114775344
,D/Launcher.HomeView( 2785): onStart
D/KeyguardViewMediator( 2583): onScreenTurnedOn, seq = 4
,D/KeyguardViewMediator( 2583): notifyScreenOnLocked
,D/LockPatternUtils( 2583): isPcwEnable = 10
D/KeyguardViewMediator( 2583): handleNotifyScreenOn
,D/KeyguardViewManager( 2583): onScreenTurnedOn()
I/KeyguardEffectViewMain( 2583): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 2583): KeyguardEffectViewParticleSpace : screenTurnedOn
,D/VisualEffectParticleEffect( 2583): screenOnAnimationStart
V/KeyguardViewManager( 2583): send wm null token: host was null
,V/KeyguardServiceDelegate( 2412): **** SHOWN CALLED ****
I/WindowManager( 2412): No lock screen! windowToken=null
D/PowerManagerNotifier( 2412): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,I/SurfaceFlinger( 1920): id=19 Removed FlectronBea (8/8)
,I/SurfaceFlinger( 1920): id=19 Removed FlectronBea (-2/8)
,D/lights  ( 2412): lcd : 2 +
D/PowerManagerService( 2412): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2412): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2412): !@ElectronBeam exit
,D/lights  ( 2412): lcd : 2 -
D/DisplayPowerController( 2412): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2412): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/Launcher( 2785): onResume, Launcher: 1114775344
,D/StatusBarManagerService( 2412): semi p:2785,o:f
D/LockPatternUtils( 2583): isPcwEnable = 10
,D/Launcher.HomeView( 2785): onResume
,I/FPMS_FingerprintManagerService( 2603): onReceive: android.intent.action.USER_PRESENT
D/LightsService( 2412): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2412) 
D/LightsService( 2412): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/StatusBarManagerService( 2412): tr p:2785,o:f
,I/SensorManagerA( 2412): getReportingMode :: sensor.mType = 5
,D/SensorManager( 2412): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/PalmMotionService( 2412): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2412): SURFACE_PALM_SWIPE: 1
D/StatusBarManagerService( 2412): semi p:2785,o:f
,I/NfcService( 2759): applyRouting return - 2 
,D/SamsungIME( 2973): showDlgMsgBox : false true true
E/MotionRecognitionService( 2412):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/SSRMv2:TSP:AirViewOnOff( 2412): SettingsAirViewInfo:: 000000000
,E/NfcService( 2759): callback == null
,D/Sensors ( 2412): LightSensor sending flush event 16
D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/Sensors ( 2412): LightSensor setDelay = 200000000
,D/Sensors ( 2412): LightSensor setSensorDelay = 200000000
,D/SensorManager( 2412): unregisterListener ::   
D/LightsService( 2412): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2412): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/LockPatternUtils( 2583): isPcwEnable = 10
,D/MenuAppsGridFragment( 2785): onResume
D/LightsService( 2412): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 2412) 
D/LightsService( 2412): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 2412): turn off LED
,D/SensorService( 2412): AutoRotationSensor::process: Acc  eventTimestamp = 126668019146, previousAccTimestamp = 126127471144, difference = 540548002 
,D/SensorService( 2412):  [AR] 0.2 -0.1 9.9
,D/SensorService( 2412): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/lights  ( 2412): led_pattern : 0 +
D/LightsService( 2412): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/lights  ( 2412): led_pattern : 0 -
,D/LightsService( 2412): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/Mms/UIEventReceiver( 5229): ui event
,I/WifiTrafficPoller( 2412): evaluateTrafficStatsPolling
D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onInitialize : 751
,D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onSetOnInfoListener : add 751
,I/PrGenericPlugin( 1923): [A] ENTER onInitialize : 0x2ef
,I/PrGenericPlugin( 1923): [A] LEAVE onInitialize : 0x2ef
,D/TranscodeService( 5871): Thread end
,D/TranscodeService( 5871): WakeLock.release()
,D/TranscodeService( 5871): onDestroy()
D/TranscodeService( 5871): releaseTranscodeThread.
,D/TranscodeService( 5871): Thread isAlive
D/STATUSBAR-NotificationService( 2412): ACTION_SCREEN_ON
D/LightsService( 2412): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2412) 
D/LightsService( 2412): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2412): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2412): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=on)
I/SecExternalDisplayIntents_Java( 2412): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController( 2412): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2412): Bridge Server is not available
,D/PersonaManagerService( 2412): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2412): MSG_ACTION_SCREEN_ON called
,I/NfcService( 2759): NFC: Screen On & Cover Open
,I/NfcService( 2759): applyRouting return - 2 ,
,E/NfcService( 2759): callback == null,
,D/STATUSBAR-NetworkController( 2583): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 350, Delta = 0,
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR,
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng,
,D/QuickConnect[1.1][2] ( 4632): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0,
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
V/QuickConnect[1.1][2] ( 4632): BleHelper.shouldScanBleBg - ,
D/QuickConnect[1.1][2] ( 4632): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50
V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50
,V/QuickConnect[1.1][2] ( 4632): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50
V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50,
V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50
D/QuickConnect[1.1][2] ( 4632): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 4632): BleHelper.startScan - bluetoothActionState = 0,
D/QuickConnect[1.1][2] ( 4632): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 4632): BleHelper.startScan - shouldScanBleFg = false,
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo,
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true,
D/comsamsunglog( 4835): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4835): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 4835): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4835): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454951100000
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454950441206
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4835): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/vwengine( 5871): stopTranscoding
D/TranscodeService( 5871): transThread.join();
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/PowerManagerService( 2412): [PWL] sb release: PowerManagerService.Broadcasts
,V/ApplicationPolicy( 2412): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,I/ActivityManager( 2412): Killing 4721:com.android.email/u0a157 (adj 15): empty #43
,D/dalvikvm( 2412): GC_EXPLICIT freed 1646K, 16% free 24578K/29232K, paused 9ms+14ms, total 213ms
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 4835): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4835): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 4835): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4835): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 4835): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(3)
,D/SSRMv2:TSP:AirViewOnOff( 2412): SettingsAirViewInfo:: 000000000
D/lights  ( 2412): button : 0 +
D/lights  ( 2412): button : 0 -
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2412):   0.2 -0.0 9.9
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(60)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/AmoledAdjustTimer( 2412): prevTemp = 313, currTemp = 314, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :4
,D/KeyguardViewMediator( 2583): received DELAYED_KEYGUARD_ACTION with seq = 3, mDelayedShowingSequence = 4
V/AlarmManager( 2412): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5415): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5415): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5415): Breath 67339 latestRequest time : 1454950378155 current time : 1454950445494
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2412):   0.2 -0.0 9.9
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(56)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2412):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 350, Delta = 0
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2412): !@Sync 4
,V/AlarmManager( 2412): waitForAlarm result :4
,V/AlarmManager( 2412): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/VacuumService( 2737): Vacuum at: now=1454950453137 tag=VacuumService
,D/SensorService( 2412):   0.2 -0.0 9.9
,D/dalvikvm( 2847): GC_EXPLICIT freed 1575K, 21% free 10813K/13656K, paused 4ms+5ms, total 52ms
,I/PhenotypeConfigurator( 2737): Scheduling Phenotype for one-off execution 920 seconds from now (1454950453632)
,D/dalvikvm( 2737): GC_CONCURRENT freed 1804K, 21% free 11695K/14688K, paused 6ms+6ms, total 65ms
,D/dalvikvm( 2737): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/GetConfigurationSnapshotOperation( 2737): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2737): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 2737): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2737): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2737): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2737): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2737): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2737): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2737): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 2412): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 2737): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2737): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2737): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 2737): Thread-113(HTTPLog):isShipBuild true
,I/System.out( 2737): Thread-113(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/LocationManagerService( 2412): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/AmoledAdjustTimer( 2412): prevTemp = 314, currTemp = 315, prevStep = 4, currStep = 4
,D/dalvikvm( 2737): GC_CONCURRENT freed 1482K, 18% free 12177K/14840K, paused 3ms+11ms, total 57ms
,D/LocationManagerService( 2412): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2412):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2412):   0.2 -0.0 9.9
,D/PowerManagerService( 2412): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2583 (0x0)
I/PowerManagerService( 2412): Nap time...
,D/PowerManagerService( 2412): [s] WAKEFULNESS_NAPPING
,I/PowerManagerService( 2412): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2412): Going to sleep due to screen timeout...
,D/PowerManagerService( 2412): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController( 2412): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,D/DisplayPowerController( 2412): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
D/Sensors ( 2412): LightSensor enable = 0
,D/Sensors ( 2412): LightSensor enableSensor = 0
,I/SurfaceFlinger( 1920): id=20 createSurf (720x1280),-1 flag=20004, FlectronBea
,D/SensorManager( 2412): unregisterListener ::   
I/DisplayPowerController( 2412): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,I/DisplayPowerController( 2412): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
I/Sensors ( 2412): HAL:resetDataRates mEnabled=4
,D/DisplayPowerController( 2412): !@ElectronBeam entry
,D/SensorManager( 2412): unregisterListener ::   
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2412): lcd : 0 +
,D/lights  ( 2412): lcd : 0 -
D/MISC PowerHAL( 2412): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2412): sysfs_write +: /sys/class/input/input1/enabled: 0
D/PowerManagerService( 2412): blankAllDisplays() is called.
D/PowerManagerService( 2412): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/PowerManagerService( 2412): [PWL] sb acquire: PowerManagerService.Broadcasts
V/WindowOrientationListener( 2412): WindowOrientationListener disabled
D/SensorService( 2412): AutoRotationSensor::activate (ident=0x729bbd40, enabled=0)
D/MISC PowerHAL( 2412): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2412): miscpower_set_interactive: /sys/class/input/input0/enabled
D/KeyguardViewMediator( 2583): onScreenTurnedOff(3)
I/Sensors ( 2412): HAL: batch Dry Run is complete
,D/MISC PowerHAL( 2412): sysfs_write +: /sys/class/input/input0/enabled: 0
,D/PowerManagerService( 2412): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2412): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2412): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2412): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2412): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2412): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2412): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2412): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2412): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2412): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2412): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2412): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/PowerManagerService( 2412): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SurfaceFlinger( 1920): Screen released, type=0 flinger=0x410d3550
D/SensorManager( 2412): unregisterListener ::   
D/InputDispatcher( 2412): setInputDispatchMode: enabled=0, frozen=0
,D/LockPatternUtils( 2583): isPcwEnable = 10
,D/Launcher.HomeView( 2785): onPause
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/LockPatternUtils( 2583): isPcwEnable = 10
D/StatusBarManagerService( 2412): tr p:2785,o:f
,D/LightsService( 2412): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2412) 
,D/LightsService( 2412): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
I/SensorManagerA( 2412): getReportingMode :: sensor.mType = 5
D/Sensors ( 2412): LightSensor setDelay = 200000000
D/Sensors ( 2412): LightSensor setSensorDelay = 200000000
D/Sensors ( 2412): Light sensor flush: not enabled 0
D/Sensors ( 2412): LightSensor enable = 1
D/Sensors ( 2412): LightSensor enableSensor = 1
D/SensorManager( 2412): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Launcher.HomeView( 2785): onStop
D/BatteryService( 2412): turn on LED for fully charged
,D/KeyguardViewMediator( 2583): setting alarm to turn off keyguard, seq = 4
D/VibratorService( 2412): JNI vibratorOff()
,I/WifiTrafficPoller( 2412): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2412): ACTION_SCREEN_OFF
D/LightsService( 2412): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2412) 
,D/LightsService( 2412): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2412): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2412): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2412): Bridge Server is not available
,D/PersonaManagerService( 2412): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2412): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2583): makeExpandedInvisible
D/PhoneStatusBarView( 2583): marqueeStatusBar:124, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2583):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2759): applyRouting return - 2 
,E/NfcService( 2759): callback == null
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/LockPatternUtils( 2583): isPcwEnable = 10
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 350, Delta = 0
,D/QuickConnect[1.1][2] ( 4632): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 4632): BleHelper.shouldScanBleBg - 
,D/QuickConnect[1.1][2] ( 4632): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50
V/QuickConnect[1.1][2] ( 4632): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42368a50
D/QuickConnect[1.1][2] ( 4632): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4632): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4632): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4632): stopLeScan()
,D/QuickConnect[1.1][2] ( 4632): BleHelper.stopScan - call stopLeScan() complete
,D/PowerManagerService( 2412): [PWL] sb release: PowerManagerService.Broadcasts
,D/SurfaceControl( 2412): Excessive delay in blankDisplay() while turning screen off: 218ms
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(29)
,I/libsuspend( 2412): !@[s] autosuspend_autosleep_enable
,D/PowerManagerService( 2412): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 221ms
,I/libsuspend( 2412): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2412): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2412): [PWL] Off : 0s ago
,D/Sensors ( 2412): LightSensor enable = 0
,D/Sensors ( 2412): LightSensor enableSensor = 0
D/SensorManager( 2412): unregisterListener ::   
,D/lights  ( 2412): led_pattern : 5 +
D/LightsService( 2412): [SvcLED]  onSensorChanged::light value = 0
,D/lights  ( 2412): led_pattern : 5 -
D/LightsService( 2412): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer( 2412): prevTemp = 315, currTemp = 316, prevStep = 4, currStep = 4,
,V/AlarmManager( 2412): waitForAlarm result :4,
,V/AlarmManager( 2412): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
D/KeyguardViewMediator( 2583): received DELAYED_KEYGUARD_ACTION with seq = 4, mDelayedShowingSequence = 4
,D/LockPatternUtils( 2583): isPcwEnable = 10,
,D/KeyguardViewMediator( 2583): in doKeyguardLocked mIsRollUp false null
,D/PersonaManager( 2583): isKioskContainerExistOnDevice,
,D/LockPatternUtils( 2583): isPcwEnable = 10,
D/LockPatternUtils( 2583): isPcwEnable = 10
,D/KeyguardViewMediator( 2583): doKeyguard: not showing because lockscreen is off,
,I/PowerManagerService( 2412): [PWL] Off : 5s ago,
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2412): waitForAlarm result :8,
,D/Headlines( 5415): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5415): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5415): Breath 90029 latestRequest time : 1454950378155 current time : 1454950468184,
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/BatteryService( 2412): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 340, Delta = -10,
,D/AmoledAdjustTimer( 2412): prevTemp = 316, currTemp = 315, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2412): [PWL] Off : 15s ago,
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/BatteryService( 2412): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 340, Delta = 0,
,E/Watchdog( 2412): !@Sync 5,
,D/AmoledAdjustTimer( 2412): prevTemp = 315, currTemp = 314, prevStep = 4, currStep = 4,
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
D/BatteryService( 2412): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 340, Delta = 0
,V/AlarmManager( 2412): waitForAlarm result :4
,V/AlarmManager( 2412): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/PowerManagerService( 2412): [PWL] Off : 30s ago
,D/AmoledAdjustTimer( 2412): prevTemp = 314, currTemp = 313, prevStep = 4, currStep = 4,
,V/AlarmManager( 2412): waitForAlarm result :8,
,D/Headlines( 5415): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5415): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5415): Breath 120030 latestRequest time : 1454950378155 current time : 1454950498185
,D/Headlines( 5415): stop ,
,D/Headlines( 5415): Breath.onDestroy : ,
I/ActivityManager( 2412): Killing 4822:com.samsung.android.service.travel/u0a170 (adj 15): empty #43
,V/AlarmManager( 2412): waitForAlarm result :8,
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true,
,D/BatteryService( 2412): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = -10,
,D/AmoledAdjustTimer( 2412): prevTemp = 313, currTemp = 312, prevStep = 4, currStep = 4,
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2412): stay LED for fully charged
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0,
,I/PowerManagerService( 2412): [PWL] Off : 50s ago,
,E/Watchdog( 2412): !@Sync 6,
,D/AmoledAdjustTimer( 2412): prevTemp = 312, currTemp = 311, prevStep = 4, currStep = 4,
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2412): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 311, currTemp = 310, prevStep = 4, currStep = 4,
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2412): stay LED for fully charged
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 310, currTemp = 309, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2412): [PWL] Off : 75s ago,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0,
,E/Watchdog( 2412): !@Sync 7,
,D/AmoledAdjustTimer( 2412): prevTemp = 309, currTemp = 309, prevStep = 4, currStep = 4,
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/BatteryService( 2412): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0,
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2412): prevTemp = 309, currTemp = 308, prevStep = 4, currStep = 4,
,V/AlarmManager( 2412): waitForAlarm result :8,
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2412): prevTemp = 308, currTemp = 308, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2412): [PWL] Off : 105s ago,
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2412): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2412): !@Sync 8,
,D/AmoledAdjustTimer( 2412): prevTemp = 308, currTemp = 306, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2412): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2412): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2412): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2412): stay LED for fully charged,
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2412): !@Sync 9,
,D/AmoledAdjustTimer( 2412): prevTemp = 306, currTemp = 305, prevStep = 4, currStep = 4,
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2412): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,V/AlarmManager( 2412): waitForAlarm result :8,
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 2583): GC_CONCURRENT freed 15686K, 34% free 33910K/50708K, paused 18ms+12ms, total 137ms,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2412): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,D/TimaService( 2412): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2412): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 2412): TimaServiceHandler.handleMessage what =1
I/TLC_TIMA_PKM_initialize( 2412): initializing...,
I/TLC_TIMA_PKM_initialize( 2412): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2412): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2412): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2412): input max_recvmsg_size = 262196,
I/TZ: mc_tlc_communication( 2412): root = 0, root_len = 1,
I/TZ: mc_tlc_communication( 2412): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2412): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2412): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2412): device_id = 0x0
I/TZ: mc_tlc_communication( 2412): tlc_open() was called,
I/TZ: mc_tlc_communication( 2412): Opening MobiCore device,
I/TZ: mc_tlc_communication( 2412): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2412): Opening the session
,I/TZ: mc_tlc_communication( 2412): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2412): Trustlet response is completed,
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0,
,E/Watchdog( 2412): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2412): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2412): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2412): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2412): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/AmoledAdjustTimer( 2412): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2412): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2412): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2412): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4,
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2412): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2412): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,V/AlarmManager( 2412): waitForAlarm result :4,
,V/AlarmManager( 2412): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 6880): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 6880):  
,I/SELinux ( 6880): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6880):  
I/SELinux ( 6880):  
,I/SELinux ( 6880): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6880): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6880): >>>>> Normal User,
,E/dalvikvm( 6880): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 6880): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 6880): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 6880): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 6880): Added TimaKesytore provider,
,D/dalvikvm( 6880): GC_CONCURRENT freed 3000K, 31% free 9570K/13688K, paused 3ms+2ms, total 26ms,
,D/dalvikvm( 6880): WAIT_FOR_CONCURRENT_GC blocked 24ms,
,I/ActivityManager( 2412): Killing 5291:com.sec.android.fotaclient/u0a11 (adj 15): empty #43,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2412): stay LED for fully charged,
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2412): !@Sync 11,
,D/AmoledAdjustTimer( 2412): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4,
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2412): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4,
,V/AlarmManager( 2412): waitForAlarm result :8,
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 2412): GC_FOR_ALLOC freed 3266K, 17% free 24669K/29556K, paused 185ms, total 185ms,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = -10,
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true,
,D/BatteryService( 2412): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2412): [PWL] Off : 225s ago,
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2412): !@Sync 12,
,D/AmoledAdjustTimer( 2412): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,V/AlarmManager( 2412): waitForAlarm result :4,
,V/AlarmManager( 2412): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,E/SPPClientService( 5048): [b] __PingReply__,
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2412): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2412): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2412): !@Sync 13
,D/AmoledAdjustTimer( 2412): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,I/PowerManagerService( 2412): [PWL] Off : 275s ago
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2412): !@Sync 14
,D/AmoledAdjustTimer( 2412): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2412): stay LED for fully charged
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2412): !@Sync 15
,D/AmoledAdjustTimer( 2412): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2412): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/BatteryService( 2412): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2412): stay LED for fully charged
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 299, currTemp = 300, prevStep = 4, currStep = 4
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2412): !@Sync 16
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2412): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2412): stay LED for fully charged
D/UiModeManager( 2412): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 299, currTemp = 300, prevStep = 4, currStep = 4
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/BatteryService( 2412): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2412): !@Sync 17
,D/AmoledAdjustTimer( 2412): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2412): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2412): !@Sync 18
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2412): stay LED for fully charged
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 299, currTemp = 300, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2412): stay LED for fully charged
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2412): !@Sync 19
,D/AmoledAdjustTimer( 2412): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,I/PowerManagerService( 2412): [PWL] Off : 455s ago
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2412): GC_FOR_ALLOC freed 2392K, 18% free 24582K/29672K, paused 187ms, total 187ms
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2412): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,D/TimaService( 2412): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2412): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2412): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2412): !@Sync 20
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2412): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2412): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2412): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2412): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2412): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 21
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2412): mCoverManager.getCoverState() : true
D/BatteryService( 2412): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,I/GAV2    ( 5159): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5159): Thread[disconnect check,5,main]: Disconnected from service
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 3762): GC_CONCURRENT freed 2882K, 30% free 9692K/13716K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 3762): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2412): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2412): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,I/PowerManagerService( 2412): [PWL] Off : 525s ago
,E/Watchdog( 2412): !@Sync 22
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2412): stay LED for fully charged
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 23
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2412): stay LED for fully charged
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2412): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2412): <AppSync3 Whitelist>
,V/AlarmManager( 2412): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2412): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 24
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,I/PowerManagerService( 2412): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/BatteryService( 2412): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2412): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 296, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 25
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2412): stay LED for fully charged
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,I/SensorManagerA( 2412): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2412): LightSensor setDelay = 200000000
,D/Sensors ( 2412): LightSensor setSensorDelay = 200000000
D/Sensors ( 2412): Light sensor flush: not enabled 0
D/Sensors ( 2412): LightSensor enable = 1
,D/Sensors ( 2412): LightSensor enableSensor = 1
,D/LightsService( 2412): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/SensorManager( 2412): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4835): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionAUTOREFRESH, run:true
,D/comsamsunglog( 4835): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4835): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 4835): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4835): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:441 [0:0] == executeAutofresh ==
,D/daemonapp( 4835): [MSC_Daemon]>>> WU:551 [0:0] Cncl30MinRftAl
,D/daemonapp( 4835): [MSC_Daemon]>>> WDSM:447 [0:0] !!!! isScreenOn = false
,D/Sensors ( 2412): LightSensor enable = 0
,D/Sensors ( 2412): LightSensor enableSensor = 0
D/LightsService( 2412): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2412): unregisterListener ::   
D/LightsService( 2412): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 26
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/BatteryService( 2412): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,I/PowerManagerService( 2412): [PWL] Off : 680s ago
,E/Watchdog( 2412): !@Sync 27
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2412): stay LED for fully charged
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 295, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2412): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2412): GC_FOR_ALLOC freed 2258K, 18% free 24595K/29672K, paused 187ms, total 188ms
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 28
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 29
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2412): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/TimaService( 2412): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2412): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2412): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2412): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2412): [PWL] Off : 765s ago
I/PowerManagerService( 2412): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2412): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2412): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2412, ws=null) (elapsedTime=189)
,E/Watchdog( 2412): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2412): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2412): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2412): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2412): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/BatteryService( 2412): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 294, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2412): mCoverManager.getCoverState() : true
D/BatteryService( 2412): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 31
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :4
,V/AlarmManager( 2412): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/ConnectivityService( 2412): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2583): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2583): getUpdateDataNetType() - mDataNetType:0
,D/STATUSBAR-NetworkController( 2583): updateDataNetType()
,D/STATUSBAR-NetworkController( 2583): NoService, mRoamingIconId = 0
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2785): GC_CONCURRENT freed 6022K, 36% free 20002K/31008K, paused 10ms+7ms, total 87ms
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 32
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/BatteryService( 2412): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :8
,E/SPPClientService( 5048): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2412): [PWL] Off : 855s ago
,D/AmoledAdjustTimer( 2412): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 33
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 34
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/BatteryService( 2412): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2412): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 35
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2412): GC_FOR_ALLOC freed 2145K, 18% free 24598K/29672K, paused 177ms, total 177ms
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService( 2412): [PWL] Off : 950s ago
,E/Watchdog( 2412): !@Sync 36
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/BatteryService( 2412): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 37
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/BatteryService( 2412): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 38
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/BatteryService( 2412): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 39
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2412): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/TimaService( 2412): TIMA: TimaService scheduler is intialized. 
D/TimaService( 2412): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2412): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 40,
,I/TLC_TIMA_PKM_measure_kernel( 2412): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2412): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2412): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2412): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 41
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2412): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
,D/BatteryService( 2412): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :8
,V/AlarmManager( 2412): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2412): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2412): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2412): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService( 2412): stay LED for fully charged
V/HeadsetService( 3366): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3366): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2412): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 42
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2412): waitForAlarm result :4
,V/AlarmManager( 2412): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2412): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3143): Aggregate from 1454949589915 (log), 1454949589915 (data)
,E/SPPClientService( 5048): [b] __PingReply__
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2412): [PWL] Off : 1155s ago
,D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2412): !@Sync 43
,D/SSRMv2:SIOP( 2412): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1200000ms),D/SSRMv2:SIOP( 2412): SIOP:: AP = 310, Delta = 0
D/AndroidRuntime( 9384): 
D/AndroidRuntime( 9384): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 9384): CheckJNI is OFF
D/AndroidRuntime( 9384): setted country_code = Poland
D/AndroidRuntime( 9384): setted countryiso_code = PL
D/AndroidRuntime( 9384): setted sales_code = PLS
D/AndroidRuntime( 9384): readGMSProperty: start
D/AndroidRuntime( 9384): readGMSProperty: already setted!!
D/AndroidRuntime( 9384): readGMSProperty: end
D/AndroidRuntime( 9384): addProductProperty: start
D/dalvikvm( 9384): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 9384): Added shared lib libjavacore.so 0x0
D/dalvikvm( 9384): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 9384): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 9384): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 9384): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 9384): failed to load memtrack module: -2
D/dalvikvm( 9384): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 9384): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2412): START PACKAGE DELETE: observer{1127649704}
D/PackageManager( 2412): pkg{<packageName>}
D/PackageManager( 2412): user{0}
D/PackageManager( 2412): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2412): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2412): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2412): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2412): [MSG] DELETE_PACKAGE_AS_USER
D/dalvikvm( 2412): GC_EXPLICIT freed 2205K, 18% free 24582K/29672K, paused 7ms+16ms, total 208ms
D/AndroidRuntime( 9384): Shutting down VM
D/PackageManager( 2412): return delete result to caller: 1127649704
D/PackageManager( 2412): returnCode: -1
D/dalvikvm( 9384): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+0ms, total 4ms
I/PackageManager( 2412):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2412):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2412):   Scheme: "sms"
I/PackageManager( 2412): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2412):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2412):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2412): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2412):   Scheme: "smsto"
I/PackageManager( 2412): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2412):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2412):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2412):   Scheme: "mms"
I/PackageManager( 2412):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2412):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2412):   Scheme: "mmsto"
I/PackageManager( 2412): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/AmoledAdjustTimer( 2412): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4

```
