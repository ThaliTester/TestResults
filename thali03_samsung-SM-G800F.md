#### Test 583805004f2b042_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
I/Icing   ( 3261): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
D/dalvikvm( 5890): GC_EXPLICIT freed 906K, 27% free 10148K/13748K, paused 3ms+9ms, total 51ms
,--------- beginning of /dev/log/system
I/ActivityManager( 2421): Waited long enough for: ServiceRecord{42fd32b8 u0 com.sec.spp.push/.PushClientService}
D/BatteryService( 2421): level:100, scale:100, status:3, health:9, present:true, voltage: 4358, temperature: 304, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 2421): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
D/LightsService( 2421): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 2421): turn off LED
D/lights  ( 2421): led_pattern : 0 +
D/LightsService( 2421): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/lights  ( 2421): led_pattern : 0 -
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PowerManagerService( 2421): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2421): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2421): Waking up from sleep...
D/PowerManagerService( 2421): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2421): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2421): [s] WAKEFULNESS_AWAKE
D/PowerManagerService( 2421): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 2421): [PWL] sb acquire: PowerManagerService.Display
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/lights  ( 2421): button : 1 +
D/lights  ( 2421): button : 1 -
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
D/Sensors ( 2421): LightSensor setDelay = 200000000
D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/Sensors ( 2421): Light sensor flush: not enabled 0
D/Sensors ( 2421): LightSensor enable = 1
D/Sensors ( 2421): LightSensor enableSensor = 1
D/DisplayPowerController( 2421): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController( 2421): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/PowerUI ( 2580): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2421): [api] [s] wakeUp (uid: 10019 pid: 2580) eventTime = 86112
D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 1
I/Sensors ( 2421): HAL: batch Dry Run is complete
I/DisplayPowerController( 2421): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
I/DisplayPowerController( 2421): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2421): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/PowerManagerService( 2421): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 7ms
D/DisplayPowerController( 2421): [DAB] no lux value from sensor manager
D/AndroidRuntime( 6086): 
D/AndroidRuntime( 6086): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/DisplayPowerController( 2421): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/Sensors ( 2421): HAL:resetDataRates mEnabled=4
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3379): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
D/PowerManagerService( 2421): unblankAllDisplays() is called.
I/libsuspend( 2421): !@[s] autosuspend_autosleep_disable
I/libsuspend( 2421): !@[s] autosuspend_autosleep_disable done
D/SurfaceFlinger( 1922): Screen acquired, type=0 flinger=0x402f7008
D/AndroidRuntime( 6086): CheckJNI is OFF
D/PowerManagerService( 2421): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/UsbDeviceManager( 2421): handleMessage -> MSG_POWER_STATE = 0
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/SensorManager( 2421): registerListener :: 2, MPL Accelerometer, 200000, 0,  
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
D/PowerManagerService( 2421): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 22ms
D/RampAnimator( 2421): Light Animator Finished currentValue=8
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
I/SELinux ( 6092): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6092):  
D/AndroidRuntime( 6086): setted country_code = Poland
D/AndroidRuntime( 6086): setted countryiso_code = PL
I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 65558
D/AndroidRuntime( 6086): setted sales_code = PLS
D/AndroidRuntime( 6086): readGMSProperty: start
D/AndroidRuntime( 6086): readGMSProperty: already setted!!
D/AndroidRuntime( 6086): readGMSProperty: end
D/AndroidRuntime( 6086): addProductProperty: start
D/UsbDeviceManager( 2421): sending intent : ACTION_USB_CABLE_STATE : connected = false
D/NotificationService( 2421): cancelNotificationLocked
D/NotificationService( 2421):  hasClearableItems
D/NotificationService( 2421):  has clearable items no 
D/NotificationService( 2421): cancelNotificationLocked: cancel alarm
D/NotificationService( 2421): cancelNotificationLocked: cancel alarm
D/STATUSBAR-StatusBarManagerService( 2421): sendNotification(3) - 5
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
D/LightsService( 2421): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2421) 
D/LightsService( 2421): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/UsbDeviceManager( 2421): received ACTION_POWER_DISCONNECTED = -1
D/LightsService( 2421): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SensorService( 2421): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2421): AutoRotationSensor::activate (ident=0x7a2d9db0, enabled=1)
D/SensorService( 2421): AutoRotationSensor::AR_init
I/Sensors ( 2421): HAL: batch Dry Run is complete
I/Sensors ( 2421): HAL:resetDataRates mEnabled=4
D/dalvikvm( 6086): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6086): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6086): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6086): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6086): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 6092): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6092):  
I/SELinux ( 6092):  
I/SELinux ( 6092): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6092): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6092): >>>>> Normal User
E/dalvikvm( 6092): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
D/SensorManager( 2421): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
E/SELinux ( 6092): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/KeyguardServiceDelegate( 2421): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@431199a8)
D/InputDispatcher( 2421): setInputDispatchMode: enabled=1, frozen=0
D/KeyguardViewMediator( 2580): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 2580): notifyScreenOnLocked
D/KeyguardViewMediator( 2580): handleNotifyScreenOn
D/KeyguardViewManager( 2580): onScreenTurnedOn()
V/KeyguardServiceDelegate( 2421): **** SHOWN CALLED ****
I/KeyguardEffectViewMain( 2580): *** KeyguardEffectView getInstance ***
D/Launcher( 2774): onRestart, Launcher: 1113866144
D/VisualEffectParticleEffect( 2580): KeyguardEffectViewParticleSpace : screenTurnedOn
V/KeyguardViewManager( 2580): send wm null token: host was null
D/Launcher( 2774): onStart, Launcher: 1113866144
D/VisualEffectParticleEffect( 2580): screenOnAnimationStart
D/Launcher.HomeView( 2774): onStart
I/WindowManager( 2421): No lock screen! windowToken=null
D/PowerManagerNotifier( 2421): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2421): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2421): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 2421): !@ElectronBeam exit
D/LockPatternUtils( 2580): isPcwEnable = 10
I/SurfaceFlinger( 1922): id=14 Removed FlectronBea (8/8)
D/BatteryMeterView( 2580): onDraw batteryColor : -1
I/SurfaceFlinger( 1922): id=14 Removed FlectronBea (-2/8)
D/lights  ( 2421): lcd : 8 +
D/PowerManagerService( 2421): Excessive delay in ElectronBeam exit: 13ms
D/lights  ( 2421): lcd : 8 -
D/DisplayPowerController( 2421): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2421): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/TimaKeyStoreProvider( 6092): in addTimaSignatureService
E/SPPClientService( 5072): [b] __ProvisionReply__
D/DisplayPowerController( 2421): [api] [DAB] onSensorChanged : 1st lux : 0.0
D/DisplayPowerController( 2421): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
D/SensorService( 2421): AutoRotationSensor::process: Acc  eventTimestamp = 86259361542, previousAccTimestamp = 59846764648, difference = 26412596894 
D/SensorService( 2421): AutoRotationSensor::reset oldrotation = [100], initState = [1]
D/TimaKeyStoreProvider( 6092): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6092): Added TimaKesytore provider
D/SensorService( 2421): AutoRotationSensor::process: Acc  eventTimestamp = 86326024105, previousAccTimestamp = 59846764648, difference = 26479259457 
D/SensorService( 2421):  [AR] 0.2 -0.0 9.9
D/SensorService( 2421): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
D/SurfaceControl( 2421): Excessive delay in unblankDisplay() while turning screen on: 266ms
D/MISC PowerHAL( 2421): miscpower_set_interactive: /sys/class/input/input1/enabled
D/PowerManagerService( 2421): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 267ms
D/MISC PowerHAL( 2421): sysfs_write +: /sys/class/input/input1/enabled: 1
I/display ( 1922): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
D/LockPatternUtils( 2580): isPcwEnable = 10
D/MISC PowerHAL( 2421): sysfs_write -: /sys/class/input/input1/enabled: 1
D/MISC PowerHAL( 2421): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2421): sysfs_write +: /sys/class/input/input0/enabled: 1
D/Launcher( 2774): onResume, Launcher: 1113866144
D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2421): semi p:2774,o:f
D/Launcher.HomeView( 2774): onResume
E/SPPClientService( 5072): [a] [ConnectionManager] Connection is already disconnected.
E/SPPClientService( 5072): [d] null
D/StatusBarManagerService( 2421): tr p:2774,o:f
D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/PalmMotionService( 2421): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
D/LightsService( 2421): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2421) 
D/LightsService( 2421): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2421): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PalmMotionService( 2421): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService( 2421):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
I/FPMS_FingerprintManagerService( 2600): onReceive: android.intent.action.USER_PRESENT
D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2421): semi p:2774,o:f
D/SSRMv2:TSP:AirViewOnOff( 2421): SettingsAirViewInfo:: 000000000
E/memtrack( 6086): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6086): failed to load memtrack module: -2
D/SamsungIME( 2984): showDlgMsgBox : false true true
D/MenuAppsGridFragment( 2774): onResume
I/NfcService( 2759): applyRouting return - 2 
E/NfcService( 2759): callback == null
D/WallpaperManager( 2774): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
D/WallpaperManager( 2774): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
D/WallpaperManager( 2774): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
V/AlarmManager( 2421):  next == MAX_VALUE
I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
D/dalvikvm( 6086): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/dalvikvm( 2421): Jit: resizing JitTable from 8192 to 16384
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
D/STATUSBAR-NotificationService( 2421): ACTION_SCREEN_ON
D/LightsService( 2421): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2421) 
D/LightsService( 2421): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2421): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/MISC PowerHAL( 2421): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2421): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2421): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2421): Excessive delay in MISC setInteractive(true) while turning screen on: 163ms
D/SEC PowerHAL( 2421): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2421): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2421): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2421): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2421): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2421): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2421): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
D/SEC PowerHAL( 2421): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
D/PowerManagerService( 2421): Excessive delay in nativeSetInteractive(true): 166ms
I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=on)
D/PowerManagerService( 2421): SecHardwareInterface.setBatteryADC : true
I/SecExternalDisplayIntents_Java( 2421): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
D/IpRemoteDisplayController( 2421): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 2421): Bridge Server is not available
E/SPPClientService( 5072): [g] getPLMN return empty string
D/PersonaManagerService( 2421): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 2421): MSG_ACTION_SCREEN_ON called
E/SPPClientService( 5072): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
E/SPPClientService( 5072): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
I/NfcService( 2759): NFC: Screen On & Cover Open
D/AndroidRuntime( 6086): Calling main entry com.android.commands.am.Am
I/NfcService( 2759): applyRouting return - 2 
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
D/STATUSBAR-NetworkController( 2580): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
E/NfcService( 2759): callback == null
E/SPPClientService( 5072): [a] [ConnectionManager] Connection is already disconnected.
I/display ( 1922): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(11)
E/SPPClientService( 5072): [g] getNetMCC return empty string
D/dalvikvm( 6092): GC_CONCURRENT freed 2998K, 31% free 9567K/13744K, paused 14ms+1ms, total 71ms
D/dalvikvm( 6092): WAIT_FOR_CONCURRENT_GC blocked 45ms
D/AndroidRuntime( 6086): Shutting down VM
D/dalvikvm( 6086): GC_CONCURRENT freed 99K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
D/SSRMv2:SIOP( 2421): SIOP:: AP = 360, Delta = 0
D/dalvikvm( 5072): GC_CONCURRENT freed 2121K, 25% free 10422K/13752K, paused 5ms+9ms, total 87ms
I/SELinux ( 6120): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6120):  
I/ActivityManager( 2421): Killing 5214:com.vlingo.midas/u0a34 (adj 15): empty #43
D/QuickConnect[1.1][2] ( 4658): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
I/ActivityManager( 2421): Killing 5357:com.policydm/1000 (adj 15): empty #43
V/QuickConnect[1.1][2] ( 4658): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4658): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4658): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42288cf8
V/QuickConnect[1.1][2] ( 4658): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42288cf8
V/QuickConnect[1.1][2] ( 4658): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 4658): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42288cf8
V/QuickConnect[1.1][2] ( 4658): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42288cf8
V/QuickConnect[1.1][2] ( 4658): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42288cf8
D/QuickConnect[1.1][2] ( 4658): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 4658): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 4658): BleHelper.startScan - shouldScanBleBg = false
D/QuickConnect[1.1][2] ( 4658): BleHelper.startScan - shouldScanBleFg = false
D/daemonapp( 4857): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 4857): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 4857): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
I/SELinux ( 6120): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6120):  
I/SELinux ( 6120):  
I/SELinux ( 6120): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6120): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6120): >>>>> Normal User
E/dalvikvm( 6120): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
E/SELinux ( 6120): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PowerManagerService( 2421): [PWL] sb release: PowerManagerService.Broadcasts
D/TimaKeyStoreProvider( 6120): in addTimaSignatureService
D/TimaKeyStoreProvider( 6120): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6120): Added TimaKesytore provider
D/dalvikvm( 6120): GC_CONCURRENT freed 3001K, 31% free 9564K/13748K, paused 3ms+2ms, total 26ms
D/dalvikvm( 6120): WAIT_FOR_CONCURRENT_GC blocked 22ms
I/KIES_RECEIVE( 6120): [APK BnR] Receive KIES_USB_DISCONNECT
W/ContextImpl( 6120): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
,E/TranscodeReceiver( 5874): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,D/videowall-Global( 5874): core_num = 4
,D/dalvikvm( 5874): No JNI_OnLoad found in /system/lib/libsavsff.so 0x422cf338, skipping init
,W/linker  ( 5874): libvwengine.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/videowall-Global( 5874): density : 2.0 width : 720 height : 1280 Raw width : 720 Raw height : 1280
,D/videowall-Global( 5874): dsp : 720, swkey : false, Cores : 4, Clock : 0
,I/SELinux ( 6132): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6132):  
,I/display ( 1922): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(6)
,D/dalvikvm( 1923): GC_EXPLICIT freed 44K, 12% free 9502K/10728K, paused 2ms+4ms, total 39ms
,I/SELinux ( 6132): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6132):  
I/SELinux ( 6132):  
,I/SELinux ( 6132): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6132): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 6132): >>>>> Normal User
,E/dalvikvm( 6132): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 6132): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 12% free 9502K/10728K, paused 2ms+3ms, total 29ms
,D/TimaKeyStoreProvider( 6132): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6132): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6132): Added TimaKesytore provider
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 12% free 9502K/10728K, paused 3ms+4ms, total 28ms
D/dalvikvm( 6132): GC_CONCURRENT freed 2999K, 31% free 9572K/13752K, paused 3ms+2ms, total 23ms
D/dalvikvm( 6132): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 2823): GC_EXPLICIT freed 336K, 26% free 10282K/13784K, paused 3ms+6ms, total 35ms
I/SELinux ( 6149): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6149):  
I/ActivityManager( 2421): Killing 5395:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43
I/SELinux ( 6149): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6149):  
I/SELinux ( 6149):  
I/SELinux ( 6149): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6149): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6149): >>>>> Normal User
E/dalvikvm( 6149): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
E/SELinux ( 6149): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 6149): in addTimaSignatureService
D/TimaKeyStoreProvider( 6149): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6149): Added TimaKesytore provider
D/dalvikvm( 6149): GC_CONCURRENT freed 2997K, 31% free 9570K/13748K, paused 1ms+1ms, total 19ms
D/dalvikvm( 6149): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 5890): GC_EXPLICIT freed 1027K, 28% free 10010K/13748K, paused 2ms+6ms, total 34ms
I/iu.Environment( 5505): update battery state; isPlugged? false*
I/iu.SyncManager( 5505): SYNC; picasa accounts
D/SSRMv2:TSP:AirViewOnOff( 2421): SettingsAirViewInfo:: 000000000
I/ActivityManager( 2421): Killing 5452:com.google.android.apps.magazines/u0a115 (adj 15): empty #43
I/iu.UploadsManager( 5505): num queued entries: 0
I/iu.Environment( 3261): update battery state; isPlugged? false*
I/iu.UploadsManager( 5505): num updated entries: 0
I/iu.SyncManager( 5505): NEXT; no task
D/PicasaUploader( 6149):    wifiOnlyPhoto changed to true
D/PicasaUploader( 6149):    wifiOnlyVideo changed to true
D/PicasaUploader( 6149):    syncOnBattery changed to true
I/iu.UploadsManager( 3261): num queued entries: 0
I/GCoreUlr( 2737): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
I/iu.UploadsManager( 3261): num updated entries: 0
I/iu.SyncManager( 3261): NEXT; no task
D/lights  ( 2421): button : 0 +
D/lights  ( 2421): button : 0 -
D/PicasaUploaderSync( 6149): sync account database
I/GCoreUlr( 2737): DispatchingService.onCreate()
D/PicasaUploaderSync( 6149): accounts in DB=1
D/PicasaUploaderSyncManager( 6149): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PicasaUploaderSyncManager( 6149): background data: true
D/PicasaUploaderSyncManager( 6149): battery info: false
D/LockPatternUtils( 2580): isPcwEnable = 10
I/GCoreUlr( 2737): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
D/Mms/UIEventReceiver( 5254): ui event
D/daemonapp( 4857): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 4857): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
I/GCoreUlr( 2737): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 4857): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4857): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4857): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4857): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
I/GCoreUlr( 2737): Unbound from all location providers
D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
I/GCoreUlr( 2737): Place inference reporting - stopped
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1455055560000
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1455035806635
D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 4857): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
I/GCoreUlr( 2737): DispatchingService.onDestroy()
I/GCoreUlr( 2737): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 2737): Unbound from all location providers
I/GCoreUlr( 2737): Place inference reporting - stopped
D/daemonapp( 4857): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 4857): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 4857): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/dalvikvm( 4857): GC_CONCURRENT freed 2590K, 28% free 10014K/13784K, paused 7ms+9ms, total 50ms
D/daemonapp( 4857): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 4857): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 4857): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4857): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4857): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4857): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 4857): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 4857): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
V/AlarmManager( 2421): waitForAlarm result :4
D/Finsky  ( 5091): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/dalvikvm( 5091): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5091): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5091): VFY: replacing opcode 0x62 at 0x0038
D/SensorService( 2421):   0.2 -0.0 9.9
,D/dalvikvm( 2421): GC_EXPLICIT freed 1361K, 13% free 24413K/27952K, paused 12ms+14ms, total 219ms
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 2848): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
W/dalvikvm( 2848): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 2848): VFY: replacing opcode 0x6e at 0x0046
,W/IcingInternalCorpora( 3261): getNumBytesRead when not calculated.
,I/System.out( 5091): Thread-369(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5091): Thread-369(ApacheHTTPLog):isShipBuild true
,I/System.out( 5091): Thread-369(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/SPPClientService( 5072): [b] __InitReply__
,I/System.out( 5091): Thread-369 calls detatch()
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5091): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5091): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5091): untagSocket(68) failed with errno -22
,I/System.out( 5091): Thread-370 calls detatch()
,D/Finsky  ( 5091): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/dalvikvm( 2848): GC_EXPLICIT freed 1013K, 22% free 10807K/13744K, paused 5ms+9ms, total 73ms
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2823): GC_EXPLICIT freed 334K, 26% free 10294K/13784K, paused 5ms+7ms, total 54ms
,I/qtaguid ( 5091): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5091): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5091): untagSocket(68) failed with errno -22
,I/System.out( 5091): Thread-369 calls detatch()
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5890): GC_EXPLICIT freed 899K, 28% free 10003K/13748K, paused 5ms+11ms, total 61ms
,D/dalvikvm( 5091): GC_CONCURRENT freed 2109K, 24% free 10482K/13772K, paused 4ms+7ms, total 63ms
,D/dalvikvm( 5091): GC_CONCURRENT freed 741K, 15% free 11788K/13772K, paused 4ms+2ms, total 35ms
,D/dalvikvm( 5091): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 5091): GC_FOR_ALLOC freed 924K, 15% free 12601K/14800K, paused 32ms, total 33ms
,D/dalvikvm( 5091): GC_FOR_ALLOC freed 1759K, 22% free 12952K/16448K, paused 32ms, total 32ms
,D/dalvikvm( 2823): GC_EXPLICIT freed 358K, 26% free 10295K/13784K, paused 4ms+7ms, total 56ms
,D/dalvikvm( 5890): GC_EXPLICIT freed 901K, 28% free 10012K/13748K, paused 2ms+8ms, total 40ms
,D/AmoledAdjustTimer( 2421): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4
,D/SensorService( 2421):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 2421): Waited long enough for: ServiceRecord{43049740 u0 com.sec.android.gallery3d/.app.BackgroundCache}
,I/qtaguid ( 5091): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5091): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5091): untagSocket(68) failed with errno -22
,I/System.out( 5091): Thread-370 calls detatch()
,D/dalvikvm( 2421): GC_EXPLICIT freed 753K, 13% free 24479K/27952K, paused 7ms+15ms, total 212ms
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 5091): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/WearableService( 2737): callingUid 10012, callindPid: 2737
,D/DeviceConnectionService( 2737): client connected with version: 8296000
,D/Finsky  ( 5091): [392] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/PackageManager( 2421): [MSG] MCS_UNBIND
I/PackageManager( 2421): calling disconnectService()
,D/PackageManager( 2421): Trying to unbind to DefaultContainerService
,D/Finsky  ( 5091): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/ActivityManager( 2421): Killing 5456:com.samsung.android.magazine.service/u0a110 (adj 15): empty #43
D/Finsky  ( 5091): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5091): Thread-380(HTTPLog):isShipBuild true
,I/System.out( 5091): Thread-380(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 5890): GC_EXPLICIT freed 905K, 28% free 10011K/13748K, paused 3ms+9ms, total 45ms
,D/dalvikvm( 2823): GC_EXPLICIT freed 349K, 26% free 10304K/13784K, paused 3ms+8ms, total 53ms
,D/dalvikvm( 5890): null clazz in OP_INSTANCE_OF, single-stepping
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
D/SensorService( 2421):   0.2 -0.0 9.9
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5890): GC_EXPLICIT freed 875K, 28% free 10009K/13748K, paused 4ms+8ms, total 47ms
,D/dalvikvm( 2823): GC_EXPLICIT freed 365K, 26% free 10296K/13784K, paused 4ms+8ms, total 47ms
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2421): level:100, scale:100, status:2, health:2, present:true, voltage: 4346, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/PowerManagerService( 2421): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/PowerUI ( 2580): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2421): [api] [s] wakeUp (uid: 10019 pid: 2580) eventTime = 96079
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,D/PowerUI ( 2580): playSound : 1
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3379): Disconnected process message: 10
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
V/Vibrator( 2580): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
,V/Vibrator( 2580): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
V/VibratorService( 2421): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2421): vibrate - package: com.android.keyguard, ms: 100, token: null
,D/VibratorService( 2421): JNI vibratorOff()
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UsbDeviceManager( 2421): handleMessage -> MSG_POWER_STATE = 1
D/VibratorService( 2421): JNI vibratorOn() : 100
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/PowerUI ( 2580): RINGER_MODE_VIBRATE
I/EntropyMixer( 2421): Writing entropy...
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/UsbDeviceManager( 2421): sending intent : ACTION_USB_CABLE_STATE : connected = true
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,E/TranscodeReceiver( 5874): onReceive : android.intent.action.ACTION_POWER_CONNECTED
,D/BatteryMeterView( 2580): onDraw batteryColor : -1
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,D/TranscodeService( 5874): onCreate()
,I/SELinux ( 6188): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6188):  
,D/dalvikvm( 5874): No JNI_OnLoad found in /system/lib/libsavsvc.so 0x422cf338, skipping init
,D/dalvikvm( 5874): No JNI_OnLoad found in /system/lib/libsavscmn.so 0x422cf338, skipping init
,D/dalvikvm( 5874): No JNI_OnLoad found in /system/lib/libsthmb.so 0x422cf338, skipping init
,D/TranscodeService( 5874): power? : true / screen off : false
,D/TranscodeService( 5874): releaseTranscodeThread.
,D/VibratorService( 2421): JNI vibratorOff()
,I/SELinux ( 6188): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6188):  
I/SELinux ( 6188):  
,I/SELinux ( 6188): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6188): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6188): >>>>> Normal User
,E/dalvikvm( 6188): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 6188): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6188): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6188): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6188): Added TimaKesytore provider
,D/dalvikvm( 6188): GC_CONCURRENT freed 2994K, 31% free 9570K/13748K, paused 4ms+2ms, total 26ms
,D/dalvikvm( 6188): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/sCloudBackupApp( 6188): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 6188): Other Intent
,D/PicasaUploaderSyncManager( 6149): battery info: true
,I/iu.Environment( 5505): update battery state; isPlugged? true*
,I/iu.UploadsManager( 5505): num queued entries: 0
,I/iu.UploadsManager( 5505): num updated entries: 0
,I/iu.SyncManager( 5505): NEXT; no task
,I/iu.FingerprintManager( 5505): Start processing all media
,I/iu.FingerprintManager( 5505): Start processing media store URI: content://media/external/images/media
,I/iu.Environment( 3261): update battery state; isPlugged? true*
,I/iu.FingerprintManager( 5505): Start processing media store URI: content://media/external/video/media
I/iu.UploadsManager( 3261): num queued entries: 0
,I/iu.UploadsManager( 3261): num updated entries: 0
,I/iu.SyncManager( 3261): NEXT; no task
,E/NetworkScheduler.SchedulerReceiver( 2848): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2848): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/GCoreUlr( 2737): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/iu.FingerprintManager( 3261): Start processing all media
,I/iu.FingerprintManager( 5505): Start processing media store URI: content://media/phoneStorage/images/media
I/GCoreUlr( 2737): DispatchingService.onCreate()
,I/iu.FingerprintManager( 3261): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5505): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 5505): Finished generating fingerprints; 0.093 seconds
,I/iu.FingerprintManager( 5505):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/iu.FingerprintManager( 3261): Start processing media store URI: content://media/external/video/media
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
I/iu.FingerprintManager( 3261): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3261): Start processing media store URI: content://media/phoneStorage/video/media
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
I/iu.FingerprintManager( 3261): Finished generating fingerprints; 0.070 seconds
I/iu.FingerprintManager( 3261):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2737): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/GCoreUlr( 2737): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2737): Unbound from all location providers
,I/GCoreUlr( 2737): Place inference reporting - stopped
,I/GCoreUlr( 2737): DispatchingService.onDestroy()
,I/GCoreUlr( 2737): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2737): Unbound from all location providers
,I/GCoreUlr( 2737): Place inference reporting - stopped
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 350, Delta = -10
,D/dalvikvm( 2421): GC_EXPLICIT freed 743K, 13% free 24518K/27952K, paused 9ms+17ms, total 228ms
,D/dalvikvm( 5890): GC_EXPLICIT freed 875K, 28% free 10013K/13748K, paused 3ms+9ms, total 50ms
,D/dalvikvm( 2823): GC_EXPLICIT freed 348K, 26% free 10303K/13784K, paused 4ms+8ms, total 48ms
,D/SensorService( 2421):   0.2 -0.1 9.9
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 5890): GC_EXPLICIT freed 874K, 28% free 10011K/13748K, paused 3ms+8ms, total 46ms
,D/dalvikvm( 2823): GC_EXPLICIT freed 348K, 26% free 10307K/13784K, paused 4ms+7ms, total 47ms
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 5890): GC_EXPLICIT freed 872K, 28% free 10009K/13748K, paused 4ms+9ms, total 47ms
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager( 2421): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2421): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
V/AlarmManager( 2421): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2421): prevTemp = 304, currTemp = 305, prevStep = 4, currStep = 4
,D/SensorService( 2421):   0.2 -0.0 9.9
,D/daemonapp( 4857): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4857): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4857): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
,D/daemonapp( 4857): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4857): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 4857): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4857): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4857): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4857): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 4857): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 4857): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/dalvikvm( 2823): GC_EXPLICIT freed 351K, 26% free 10316K/13784K, paused 5ms+12ms, total 63ms
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2421): Waited long enough for: ServiceRecord{43093e50 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/dalvikvm( 2421): GC_EXPLICIT freed 496K, 13% free 24515K/27952K, paused 8ms+16ms, total 204ms
,D/dalvikvm( 5890): GC_EXPLICIT freed 871K, 28% free 10007K/13748K, paused 3ms+8ms, total 45ms
,D/dalvikvm( 2823): GC_EXPLICIT freed 355K, 26% free 10322K/13784K, paused 4ms+8ms, total 49ms
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2421):   0.2 -0.0 9.9
,D/dalvikvm( 5890): GC_CONCURRENT freed 1473K, 24% free 10492K/13748K, paused 1ms+7ms, total 35ms
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,I/SettingSearch/SearchIntentReceiver( 2823): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2823): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 2823): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 2823): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2823): LOCALE_CHANGED call search setting db finish!!
,V/AlarmManager( 2421): waitForAlarm result :4
,D/Headlines( 5439): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5439): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5439): Breath 40496 latestRequest time : 1455035784412 current time : 1455035824908
V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService( 2421): level:100, scale:100, status:2, health:2, present:true, voltage: 4381, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/dalvikvm( 5091): GC_CONCURRENT freed 7130K, 34% free 16204K/24512K, paused 3ms+6ms, total 94ms
,D/dalvikvm( 5091): WAIT_FOR_CONCURRENT_GC blocked 83ms
,D/Finsky  ( 5091): [382] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5091): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 350, Delta = 0
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2421):   0.2 -0.0 9.9
,E/Watchdog( 2421): !@Sync 3
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2421):   0.2 -0.0 9.9
,I/ActivityManager( 2421): Waited long enough for: ServiceRecord{430a6f60 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/AmoledAdjustTimer( 2421): prevTemp = 305, currTemp = 306, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,I/Icing   ( 3261): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music
,I/Icing   ( 3261): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A
,D/SensorService( 2421):   0.2 -0.1 9.9
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2421): level:100, scale:100, status:2, health:2, present:true, voltage: 4383, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 340, Delta = -10
,D/SensorService( 2421):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/FactoryTest( 5168): Not factory mode
,D/FactoryTest( 5168): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5168): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5168): still no open session command from host, so toast
W/ContextImpl( 5168): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5168): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy( 2421): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4
,I/SurfaceFlinger( 1922): id=16 createSurf (16x16),-1 flag=20004, EimLayer
,W/ActivityManager( 2421): mDVFSHelper.acquire()
I/SurfaceFlinger( 1922): id=17 createSurf (16x16),-1 flag=20004, EimLayer
,D/Launcher.HomeView( 2774): onPause
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,E/MTPRx   ( 5168): started activity for popup
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2421): tr p:2774,o:f
,E/SettingsReceiverActivity( 5168): PREF_DONT_ASK_AGAIN : true
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2421): tr p:2774,o:f
D/StatusBarManagerService( 2421): semi p:2774,o:f
,I/SQLiteSecureOpenHelper( 3558): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3558): getDatabaseLocked(b,b,pwd)...
,W/InputMethodManagerService( 2421): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@430fe900 attribute=android.view.inputmethod.EditorInfo@42eb11d8, token = android.os.BinderProxy@42e7a928
,D/SettingsReceiverActivity( 5168): dev.kiessupport is : TRUE
,D/Launcher( 2774): onResume, Launcher: 1113866144
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/Launcher.HomeView( 2774): onResume
D/StatusBarManagerService( 2421): semi p:2774,o:f
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2421): tr p:2774,o:f
,D/StatusBarManagerService( 2421): semi p:2774,o:f
D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/MenuAppsGridFragment( 2774): onResume
,D/Mms/UIEventReceiver( 5254): ui event
,I/SurfaceFlinger( 1922): id=17 Removed EimLayer (5/9)
I/SurfaceFlinger( 1922): id=17 Removed EimLayer (-2/9)
,I/SurfaceFlinger( 1922): id=16 Removed EimLayer (4/8)
,I/SurfaceFlinger( 1922): id=16 Removed EimLayer (-2/8)
,I/display ( 1922): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(9)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,I/display ( 1922): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(3)
,D/PowerManagerService( 2421): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2421): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2421): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2421): lcd : 2 +
D/RampAnimator( 2421): Light Animator Finished currentValue=2
,D/lights  ( 2421): lcd : 2 -
,D/SensorService( 2421):   0.1 -0.0 9.9
,D/AmoledAdjustTimer( 2421): prevTemp = 306, currTemp = 307, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2421): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2421):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/PowerManagerService( 2421): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2421): Nap time...
,D/PowerManagerService( 2421): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2421): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2421): Going to sleep due to screen timeout...
D/PowerManagerService( 2421): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2421): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/DisplayPowerController( 2421): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/DisplayPowerController( 2421): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
D/Sensors ( 2421): LightSensor enable = 0
,D/Sensors ( 2421): LightSensor enableSensor = 0
,I/SurfaceFlinger( 1922): id=18 createSurf (720x1280),-1 flag=20004, FlectronBea
,I/DisplayPowerController( 2421): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
D/SensorManager( 2421): unregisterListener ::   
,I/Sensors ( 2421): HAL:resetDataRates mEnabled=4
,D/SensorManager( 2421): unregisterListener ::   
D/DisplayPowerController( 2421): !@ElectronBeam entry
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/PowerManagerService( 2421): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2580
I/PowerManagerService( 2421): !@[ps] Screen__On(wake lock) :  wl: PowerUI
I/PowerManagerService( 2421): Waking up from sleep...
D/PowerManagerService( 2421): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2421): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerNotifier( 2421): mBroadcastInProgress = true , mActualPowerState = 1 , mPendingWakeUpBroadcast = true , mPendingGoToSleepBroadcast = true , mBroadcastedPowerState = 1
,D/PowerManagerService( 2421): [s] WAKEFULNESS_AWAKE
D/lights  ( 2421): button : 1 +
,D/lights  ( 2421): button : 1 -
I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
D/Sensors ( 2421): LightSensor setDelay = 200000000
D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/Sensors ( 2421): Light sensor flush: not enabled 0
D/Sensors ( 2421): LightSensor enable = 1
,D/Sensors ( 2421): LightSensor enableSensor = 1
D/DisplayPowerController( 2421): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2421): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/DisplayPowerController( 2421): [DAB] setLightSensorEnabled : registerListener mLightSensor
I/DisplayPowerController( 2421): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2421): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2421): [DAB] no lux value from sensor manager
D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 1
V/WindowOrientationListener( 2421): WindowOrientationListener disabled
D/SensorService( 2421): AutoRotationSensor::activate (ident=0x7a2d9db0, enabled=0)
,I/Sensors ( 2421): HAL: batch Dry Run is complete
,D/NotificationService( 2421): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/PowerManagerService( 2421): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 4ms
D/DisplayPowerController( 2421): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-StatusBarManagerService( 2421): sendNotification(1) - 5
,D/KeyguardViewMediator( 2580): onScreenTurnedOff(3)
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
,I/Sensors ( 2421): HAL: batch Dry Run is complete
,I/Sensors ( 2421): HAL:resetDataRates mEnabled=4
D/RCPManagerService( 2421): NotificationReceiver onReceive()
,D/RCPManagerService( 2421):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
,D/RCPManagerService( 2421): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298421
D/RCPManagerService( 2421): getPolicy: policy value returned = false
D/RCPManagerService( 2421): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2421): app label == com.android.systemui
D/LockPatternUtils( 2580): isPcwEnable = 10
,D/RCPManagerService( 2421): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298421
,D/UserManagerService( 2421): User -1does not exists!!
D/RCPManagerService( 2421): getPolicy: policy value returned = true
D/RCPManagerService( 2421): Calling User is -1
,D/LockPatternUtils( 2580): isPcwEnable = 10
,E/PersonaManagerService( 2421): returning null in  getPersonasForUser
D/RCPManagerService( 2421): userid of SBN ==-1
D/ProgressBar( 2580): setProgressDrawable drawableHeight = 12
,D/SensorManager( 2421): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/SensorManager( 2421): unregisterListener ::   
,D/InputDispatcher( 2421): setInputDispatchMode: enabled=0, frozen=0
,D/PowerManagerService( 2421): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 41ms
D/KeyguardViewMediator( 2580): setting alarm to turn off keyguard, seq = 2
,D/Launcher.HomeView( 2774): onPause
D/PhoneStatusBar( 2580): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@42299748
,D/StatusBarManagerService( 2421): tr p:2774,o:f
D/lights  ( 2421): lcd : 0 +
,D/lights  ( 2421): lcd : 0 -
D/DisplayPowerController( 2421): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LightsService( 2421): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2421) 
,D/LightsService( 2421): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
,D/Launcher.HomeView( 2774): onStop
,D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/display ( 1922): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(56)
D/BatteryService( 2421): turn on LED for fully charged
D/VibratorService( 2421): JNI vibratorOff()
,D/BatteryMeterView( 2580): onDraw batteryColor : -1
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2421): ACTION_SCREEN_OFF
,D/LightsService( 2421): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2421) 
,D/LightsService( 2421): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=off)
,I/SecExternalDisplayIntents_Java( 2421): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2421): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2421): Bridge Server is not available
,D/PersonaManagerService( 2421): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2421): MSG_ACTION_SCREEN_OFF called
,D/STATUSBAR-PhoneStatusBar( 2580):      ACTION_SCREEN_OFF is received!!!! 
,D/STATUSBAR-PhoneStatusBar( 2580): makeExpandedInvisible
D/PhoneStatusBarView( 2580): marqueeStatusBar:122, mClearCover:0
,D/STATUSBAR-PhoneStatusBar( 2580):      ACTION_SCREEN_OFF is finished!!!! 
,D/Sensors ( 2421): LightSensor sending flush event 16
D/Sensors ( 2421): LightSensor setDelay = 200000000
,D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/DisplayPowerController( 2421): [api] [DAB] onSensorChanged : 1st lux : 0.0
D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 0
,D/DisplayPowerController( 2421): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
D/SensorManager( 2421): unregisterListener ::   
D/lights  ( 2421): led_pattern : 5 +
,D/lights  ( 2421): led_pattern : 5 -
,I/NfcService( 2759): applyRouting return - 2 ,
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/NfcService( 2759): callback == null
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 340, Delta = 0
,D/QuickConnect[1.1][2] ( 4658): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 4658): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4658): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4658): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42288cf8
,V/QuickConnect[1.1][2] ( 4658): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42288cf8
,D/QuickConnect[1.1][2] ( 4658): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4658): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4658): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4658): stopLeScan()
,D/QuickConnect[1.1][2] ( 4658): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 5874): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 5874): power? : true / screen off : true
,I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 65558
D/TranscodeService( 5874): Music is = false
,D/TranscodeService( 5874): runvideoplayer is false
D/SensorService( 2421): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2421): AutoRotationSensor::activate (ident=0x793e20e0, enabled=1)
D/SensorService( 2421): AutoRotationSensor::AR_init
,I/Sensors ( 2421): HAL: batch Dry Run is complete
,D/TranscodeService( 5874): Thread start
,D/TranscodeService( 5874): WakeLock.acquire()
D/videowall-FileMgr( 5874): thumbnailDBSync -1
,I/Sensors ( 2421): HAL:resetDataRates mEnabled=4
,D/SensorService( 2421): AutoRotationSensor::process: Acc  eventTimestamp = 126498542145, previousAccTimestamp = 126164125562, difference = 334416583 
D/SensorService( 2421): AutoRotationSensor::reset oldrotation = [100], initState = [1]
D/SensorManager( 2421): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,V/KeyguardServiceDelegate( 2421): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@42ff4488)
,D/InputDispatcher( 2421): setInputDispatchMode: enabled=1, frozen=0
D/Launcher( 2774): onRestart, Launcher: 1113866144
,D/Launcher( 2774): onStart, Launcher: 1113866144
D/KeyguardViewMediator( 2580): onScreenTurnedOn, seq = 3
,D/KeyguardViewMediator( 2580): notifyScreenOnLocked
,D/Launcher.HomeView( 2774): onStart
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/KeyguardViewMediator( 2580): handleNotifyScreenOn
D/KeyguardViewManager( 2580): onScreenTurnedOn()
I/KeyguardEffectViewMain( 2580): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 2580): KeyguardEffectViewParticleSpace : screenTurnedOn
,D/VisualEffectParticleEffect( 2580): screenOnAnimationStart
,V/KeyguardServiceDelegate( 2421): **** SHOWN CALLED ****
V/KeyguardViewManager( 2580): send wm null token: host was null
I/WindowManager( 2421): No lock screen! windowToken=null
,I/SurfaceFlinger( 1922): id=18 Removed FlectronBea (8/8)
D/PowerManagerNotifier( 2421): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2421): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2421): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2421): !@ElectronBeam exit
I/SurfaceFlinger( 1922): id=18 Removed FlectronBea (-2/8)
D/lights  ( 2421): lcd : 2 +
,D/lights  ( 2421): lcd : 2 -
D/DisplayPowerController( 2421): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2421): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/Launcher( 2774): onResume, Launcher: 1113866144
D/StatusBarManagerService( 2421): semi p:2774,o:f
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/Launcher.HomeView( 2774): onResume
D/StatusBarManagerService( 2421): tr p:2774,o:f
D/StatusBarManagerService( 2421): semi p:2774,o:f
D/LightsService( 2421): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2421) 
,D/LightsService( 2421): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
I/FPMS_FingerprintManagerService( 2600): onReceive: android.intent.action.USER_PRESENT
D/PalmMotionService( 2421): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2421): SURFACE_PALM_SWIPE: 1
,D/SamsungIME( 2984): showDlgMsgBox : false true true
,E/MotionRecognitionService( 2421):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/SSRMv2:TSP:AirViewOnOff( 2421): SettingsAirViewInfo:: 000000000
,I/NfcService( 2759): applyRouting return - 2 
,E/NfcService( 2759): callback == null
D/LightsService( 2421): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 2421) 
,D/LightsService( 2421): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 2421): turn off LED
,D/Sensors ( 2421): LightSensor setDelay = 200000000
,D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
,D/LightsService( 2421): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/SensorManager( 2421): unregisterListener ::   
D/lights  ( 2421): led_pattern : 0 +
D/MenuAppsGridFragment( 2774): onResume
,D/lights  ( 2421): led_pattern : 0 -
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/LockPatternUtils( 2580): isPcwEnable = 10
D/WVMDrmPlugIn( 1925): WVMDrmPlugin::onInitialize : 3746
,D/WVMDrmPlugIn( 1925): WVMDrmPlugin::onSetOnInfoListener : add 3746
I/PrGenericPlugin( 1925): [A] ENTER onInitialize : 0xea2
,I/PrGenericPlugin( 1925): [A] LEAVE onInitialize : 0xea2
D/SensorService( 2421): AutoRotationSensor::process: Acc  eventTimestamp = 126692013770, previousAccTimestamp = 126164125562, difference = 527888208 
D/SensorService( 2421):  [AR] 0.2 -0.0 9.8
,D/SensorService( 2421): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/TranscodeService( 5874): Thread end
,D/TranscodeService( 5874): WakeLock.release()
,D/TranscodeService( 5874): onDestroy()
,D/TranscodeService( 5874): releaseTranscodeThread.
,V/ApplicationPolicy( 2421): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,D/Mms/UIEventReceiver( 5254): ui event
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
,I/ActivityManager( 2421): Killing 4745:com.android.email/u0a157 (adj 15): empty #43
,D/STATUSBAR-NotificationService( 2421): ACTION_SCREEN_ON
,D/LightsService( 2421): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2421) 
D/LightsService( 2421): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2421): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=on)
,I/SecExternalDisplayIntents_Java( 2421): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/dalvikvm( 2737): GC_CONCURRENT freed 1880K, 22% free 11582K/14712K, paused 18ms+19ms, total 129ms
,D/IpRemoteDisplayController( 2421): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2421): Bridge Server is not available
,D/Sensors ( 2421): LightSensor sending flush event 16
,D/PersonaManagerService( 2421): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2421): MSG_ACTION_SCREEN_ON called
,I/NfcService( 2759): NFC: Screen On & Cover Open
,I/NfcService( 2759): applyRouting return - 2 
,E/NfcService( 2759): callback == null
,D/STATUSBAR-NetworkController( 2580): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 340, Delta = 0
,D/daemonapp( 4857): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4857): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/QuickConnect[1.1][2] ( 4658): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
,V/QuickConnect[1.1][2] ( 4658): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4658): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4658): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42288cf8
V/QuickConnect[1.1][2] ( 4658): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42288cf8
V/QuickConnect[1.1][2] ( 4658): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 4658): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42288cf8
V/QuickConnect[1.1][2] ( 4658): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42288cf8
V/QuickConnect[1.1][2] ( 4658): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42288cf8
D/QuickConnect[1.1][2] ( 4658): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 4658): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 4658): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 4658): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 4857): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4857): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4857): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4857): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1455055560000
,D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1455035845891
,D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 4857): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 4857): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4857): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4857): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 4857): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4857): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4857): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON,
,D/daemonapp( 4857): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR,
D/daemonapp( 4857): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings,
,D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/PowerManagerService( 2421): [PWL] sb release: PowerManagerService.Broadcasts
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 4857): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4857): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4857): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4857): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 4857): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 4857): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
D/daemonapp( 4857): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4857): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,I/display ( 1922): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/lights  ( 2421): button : 0 +
,D/lights  ( 2421): button : 0 -
,D/SSRMv2:TSP:AirViewOnOff( 2421): SettingsAirViewInfo:: 000000000
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2421):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,I/display ( 1922): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(60)
,I/display ( 1922): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/AmoledAdjustTimer( 2421): prevTemp = 307, currTemp = 308, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/KeyguardViewMediator( 2580): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 3
,D/Headlines( 5439): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5439): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5439): Breath 65759 latestRequest time : 1455035784412 current time : 1455035850171
,D/SensorService( 2421):   0.2 -0.1 9.9
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/display ( 1922): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(60)
,I/display ( 1922): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2421):   0.2 -0.0 9.9
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 340, Delta = 0
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2421):   0.2 -0.0 9.9
,E/Watchdog( 2421): !@Sync 4
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/VacuumService( 2737): Vacuum at: now=1455035859293 tag=VacuumService
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PhenotypeConfigurator( 2737): Scheduling Phenotype for one-off execution 3118 seconds from now (1455035859782)
,D/GetConfigurationSnapshotOperation( 2737): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2737): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 2737): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2737): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2737): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2737): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2737): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2737): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2737): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 2737): Thread-117(HTTPLog):isShipBuild true
,I/System.out( 2737): Thread-117(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/AmoledAdjustTimer( 2421): prevTemp = 308, currTemp = 309, prevStep = 4, currStep = 4
,D/SensorService( 2421):   0.2 -0.0 9.8
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2737): GC_CONCURRENT freed 1433K, 19% free 12114K/14796K, paused 4ms+8ms, total 55ms
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2421):   0.1 -0.0 9.9
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2421): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2580 (0x0)
I/PowerManagerService( 2421): Nap time...
,D/PowerManagerService( 2421): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2421): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2421): Going to sleep due to screen timeout...
,D/PowerManagerService( 2421): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2421): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,D/Sensors ( 2421): LightSensor enable = 0
,D/Sensors ( 2421): LightSensor enableSensor = 0
D/DisplayPowerController( 2421): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/DisplayPowerController( 2421): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,I/DisplayPowerController( 2421): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
D/SensorManager( 2421): unregisterListener ::   
I/SurfaceFlinger( 1922): id=19 createSurf (720x1280),-1 flag=20004, FlectronBea
,D/DisplayPowerController( 2421): !@ElectronBeam entry
I/Sensors ( 2421): HAL:resetDataRates mEnabled=4
,D/SensorManager( 2421): unregisterListener ::   
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2421): lcd : 0 +
,D/lights  ( 2421): lcd : 0 -
,D/PowerManagerService( 2421): blankAllDisplays() is called.
D/MISC PowerHAL( 2421): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2421): sysfs_write +: /sys/class/input/input1/enabled: 0
,V/WindowOrientationListener( 2421): WindowOrientationListener disabled
D/SensorService( 2421): AutoRotationSensor::activate (ident=0x793e20e0, enabled=0)
D/PowerManagerService( 2421): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2421): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2421): [PWL] sb release: PowerManagerService.Display
I/Sensors ( 2421): HAL: batch Dry Run is complete
D/KeyguardViewMediator( 2580): onScreenTurnedOff(3)
D/MISC PowerHAL( 2421): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2421): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2421): sysfs_write +: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2421): sysfs_write -: /sys/class/input/input0/enabled: 0
D/SensorManager( 2421): unregisterListener ::   
D/InputDispatcher( 2421): setInputDispatchMode: enabled=0, frozen=0
D/MISC PowerHAL( 2421): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2421): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2421): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2421): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2421): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2421): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2421): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2421): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2421): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2421): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/PowerManagerService( 2421): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SurfaceFlinger( 1922): Screen released, type=0 flinger=0x402f7008
D/LockPatternUtils( 2580): isPcwEnable = 10
D/Launcher.HomeView( 2774): onPause
D/LockPatternUtils( 2580): isPcwEnable = 10
D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2421): tr p:2774,o:f
D/KeyguardViewMediator( 2580): setting alarm to turn off keyguard, seq = 3
,D/LightsService( 2421): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2421) 
,I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2421): LightSensor setDelay = 200000000
,D/LightsService( 2421): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/Sensors ( 2421): Light sensor flush: not enabled 0
D/Sensors ( 2421): LightSensor enable = 1
D/Sensors ( 2421): LightSensor enableSensor = 1
,D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Launcher.HomeView( 2774): onStop
D/BatteryService( 2421): turn on LED for fully charged
D/VibratorService( 2421): JNI vibratorOff()
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2421): ACTION_SCREEN_OFF
D/LightsService( 2421): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2421) 
,D/LightsService( 2421): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2421): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2421): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2421): Bridge Server is not available
,D/PersonaManagerService( 2421): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2421): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2580):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2580): makeExpandedInvisible
D/PhoneStatusBarView( 2580): marqueeStatusBar:123, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2580):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2759): applyRouting return - 2 
,E/NfcService( 2759): callback == null
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 340, Delta = 0
D/QuickConnect[1.1][2] ( 4658): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 4658): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 4658): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 4658): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42288cf8
V/QuickConnect[1.1][2] ( 4658): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42288cf8
D/QuickConnect[1.1][2] ( 4658): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 4658): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 4658): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 4658): stopLeScan()
D/QuickConnect[1.1][2] ( 4658): BleHelper.stopScan - call stopLeScan() complete
,D/PowerManagerService( 2421): [PWL] sb release: PowerManagerService.Broadcasts
,D/SurfaceControl( 2421): Excessive delay in blankDisplay() while turning screen off: 227ms
,I/libsuspend( 2421): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2421): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2421): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 229ms
D/PowerManagerService( 2421): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2421): [PWL] Off : 0s ago
,D/Sensors ( 2421): LightSensor enable = 0
,D/Sensors ( 2421): LightSensor enableSensor = 0
,D/SensorManager( 2421): unregisterListener ::   
,D/lights  ( 2421): led_pattern : 5 +
,I/display ( 1922): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(29)
D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 0
,D/lights  ( 2421): led_pattern : 5 -
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer( 2421): prevTemp = 309, currTemp = 310, prevStep = 4, currStep = 4,
,D/KeyguardViewMediator( 2580): received DELAYED_KEYGUARD_ACTION with seq = 3, mDelayedShowingSequence = 3,
V/AlarmManager( 2421): waitForAlarm result :4
V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/LockPatternUtils( 2580): isPcwEnable = 10,
,D/KeyguardViewMediator( 2580): in doKeyguardLocked mIsRollUp false null,
,D/PersonaManager( 2580): isKioskContainerExistOnDevice
,D/dalvikvm( 2421): GC_EXPLICIT freed 2535K, 14% free 24669K/28496K, paused 11ms+18ms, total 237ms,
,D/LockPatternUtils( 2580): isPcwEnable = 10
D/LockPatternUtils( 2580): isPcwEnable = 10
,D/KeyguardViewMediator( 2580): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService( 2421): [PWL] Off : 5s ago
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 340, Delta = 0,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2421): prevTemp = 310, currTemp = 309, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2421): [PWL] Off : 15s ago,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = -10,
,E/Watchdog( 2421): !@Sync 5,
,D/AmoledAdjustTimer( 2421): prevTemp = 309, currTemp = 308, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5439): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5439): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5439): Breath 111175 latestRequest time : 1455035784412 current time : 1455035895587
,I/PowerManagerService( 2421): [PWL] Off : 30s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 308, currTemp = 307, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :8,
,D/Headlines( 5439): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5439): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5439): Breath 120027 latestRequest time : 1455035784412 current time : 1455035904439
,D/Headlines( 5439): stop ,
,D/Headlines( 5439): Breath.onDestroy : ,
I/ActivityManager( 2421): Killing 4845:com.samsung.android.service.travel/u0a170 (adj 15): empty #43
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 307, currTemp = 306, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,I/PowerManagerService( 2421): [PWL] Off : 50s ago,
,E/Watchdog( 2421): !@Sync 6,
,D/AmoledAdjustTimer( 2421): prevTemp = 306, currTemp = 305, prevStep = 4, currStep = 4,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4,
,I/ClearcutLoggerApiImpl( 2848): disconnect managed GoogleApiClient,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2421): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2421): [PWL] Off : 75s ago,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = -10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2421): !@Sync 7,
,D/AmoledAdjustTimer( 2421): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2421): [PWL] Off : 105s ago,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 8,
,D/AmoledAdjustTimer( 2421): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3379): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2421): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2421): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2421): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2580): GC_CONCURRENT freed 15673K, 34% free 33906K/50756K, paused 11ms+10ms, total 84ms,
,E/Watchdog( 2421): !@Sync 9,
,D/AmoledAdjustTimer( 2421): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 2421): initializing...
,I/TLC_TIMA_PKM_initialize( 2421): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2421): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2421): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2421): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2421): root = 0, root_len = 1
,I/TZ: mc_tlc_communication( 2421): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2421): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2421): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2421): device_id = 0x0
I/TZ: mc_tlc_communication( 2421): tlc_open() was called
,I/TZ: mc_tlc_communication( 2421): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2421): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2421): Opening the session
,I/TZ: mc_tlc_communication( 2421): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2421): Trustlet response is completed
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 10
,D/AmoledAdjustTimer( 2421): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 180s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 6956): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6956):  
,I/SELinux ( 6956): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6956):  
I/SELinux ( 6956):  
,I/SELinux ( 6956): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6956): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 6956): >>>>> Normal User
,E/dalvikvm( 6956): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 6956): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6956): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6956): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6956): Added TimaKesytore provider
,D/dalvikvm( 6956): GC_CONCURRENT freed 3015K, 31% free 9558K/13752K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 6956): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/ActivityManager( 2421): Killing 5316:com.sec.android.fotaclient/u0a11 (adj 15): empty #43
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 11
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 225s ago
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 12
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/SPPClientService( 5072): [b] __PingReply__
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2421): GC_FOR_ALLOC freed 2790K, 18% free 24585K/29732K, paused 188ms, total 188ms
D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 13
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2421): [PWL] Off : 275s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 14
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 15
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2421): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 16
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 17
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2421): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 18
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 19
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2421): [PWL] Off : 455s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 21
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/GAV2    ( 5184): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5184): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2421): [PWL] Off : 525s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = -10
,E/Watchdog( 2421): !@Sync 22
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2421): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2421): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2421): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 3793): GC_CONCURRENT freed 2886K, 30% free 9689K/13788K, paused 7ms+2ms, total 46ms
,D/dalvikvm( 3793): WAIT_FOR_CONCURRENT_GC blocked 40ms
,D/dalvikvm( 2421): GC_FOR_ALLOC freed 2536K, 18% free 24550K/29732K, paused 163ms, total 164ms
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 10
,E/Watchdog( 2421): !@Sync 23
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 24
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 25
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 26
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 680s ago
,E/Watchdog( 2421): !@Sync 27
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 28
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 29
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,I/PowerManagerService( 2421): [PWL] Off : 765s ago
I/PowerManagerService( 2421): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2421): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2421): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2421, ws=null) (elapsedTime=185)
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 30
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 31
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :4
,D/LightsService( 2421): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
D/Sensors ( 2421): LightSensor setDelay = 200000000
D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/Sensors ( 2421): Light sensor flush: not enabled 0
,D/Sensors ( 2421): LightSensor enable = 1
,D/Sensors ( 2421): LightSensor enableSensor = 1
,D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3261): Aggregate from 1455034597131 (log), 1455034597131 (data)
,D/Sensors ( 2421): LightSensor enable = 0
,D/Sensors ( 2421): LightSensor enableSensor = 0
,D/SensorManager( 2421): unregisterListener ::   
D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 3261): GC_CONCURRENT freed 1831K, 20% free 12106K/15116K, paused 6ms+8ms, total 59ms
,W/SQLiteConnectionPool( 3261): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ConnectivityService( 2421): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 32
,D/dalvikvm( 2421): GC_FOR_ALLOC freed 2500K, 18% free 24580K/29732K, paused 197ms, total 197ms
D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,E/SPPClientService( 5072): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2421): [PWL] Off : 855s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 33
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 34
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2774): GC_CONCURRENT freed 6016K, 36% free 20104K/31072K, paused 9ms+7ms, total 79ms
,D/dalvikvm( 2774): WAIT_FOR_CONCURRENT_GC blocked 70ms
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 35
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 950s ago
,E/Watchdog( 2421): !@Sync 36
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 37
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 38
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 3379): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3379): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 39
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 40
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 41
,D/dalvikvm( 2421): GC_FOR_ALLOC freed 2467K, 18% free 24524K/29732K, paused 209ms, total 209ms
D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 42
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5072): [b] __PingReply__
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1200000ms)
```
