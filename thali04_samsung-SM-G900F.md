#### Test 5038801913f4183_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
I/ServiceManager(  339): Waiting for service AtCmdFwd...
I/wpa_supplicant( 1304): nl80211: Received scan results (6 BSSes)
E/WifiStateMachine(  868): [1,450,199,091,795 ms] noteScanEnd no scan source
--------- beginning of system
D/WifiP2pService(  868): InactiveState{ what=147461 }
D/WifiP2pService(  868): P2pEnabledState{ what=147461 }
D/WifiP2pService(  868): DefaultState{ what=147461 }
E/WifiStateMachine(  868): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@7c85a3f sup_state=COMPLETED debouncing=false
I/CLocInfoService(  868): External Intent Received android.net.wifi.SCAN_RESULTS
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
D/AndroidRuntime( 7783): 
D/AndroidRuntime( 7783): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7783): CheckJNI is OFF
D/AndroidRuntime( 7783): setted country_code = Poland
D/AndroidRuntime( 7783): setted countryiso_code = PL
D/AndroidRuntime( 7783): setted sales_code = XEO
D/AndroidRuntime( 7783): readGMSProperty: start
D/AndroidRuntime( 7783): readGMSProperty: already setted!!
D/AndroidRuntime( 7783): readGMSProperty: end
D/AndroidRuntime( 7783): addProductProperty: start
E/AffinityControl( 7783): AffinityControl: registerfunction enter
D/AndroidRuntime( 7783): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  868): inState():  stateMachine is null !!
V/ApplicationPolicy(  868): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  868): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  868): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager(  868): mDVFSHelper.acquire()
D/FocusedStackFrame(  868): Set to : 0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  868): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=7794 uid=10357 gids={50357, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
E/Zygote  ( 7794): MountEmulatedStorage()
D/LockPatternUtilsCache( 1181): value : false
E/Zygote  ( 7794): v2
I/libpersona( 7794): KNOX_SDCARD checking this for 10357
I/libpersona( 7794): KNOX_SDCARD not a persona
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SELinux ( 7794): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7794): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7794): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 7783): Shutting down VM
V/AlarmManager(  868): waitForAlarm result :4
E/SMD     (  291): DCD ON
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/KeyguardViewMediator( 1181): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/KeyguardViewMediator( 1181): doKeyguard: not showing because lockscreen is off
D/TimaKeyStoreProvider( 7794): TimaSignature is unavailable
D/ActivityThread( 7794): Added TimaKeyStore provider
V/WindowOrientationListener(  868): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  868): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  868): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  868): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  868): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  868): Display changed displayId=0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/BatteryService(  868): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  868): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/LightsService(  868): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 868) 
D/LightsService(  868): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
E/LightSensor(  868): Light old sensor_state 0, new sensor_state : 512 en : 1
D/BatteryService(  868): Sending ACTION_BATTERY_CHANGED.
D/SurfaceWidgetView( 1487): destroyHardwareResources():656101123
D/SensorManager(  868): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService(  868): turn on LED for fully charged
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2204): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SurfaceFlinger(  257): id=6 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (6/8)
I/SurfaceFlinger(  257): id=6 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/8)
D/Launcher( 1487): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/MotionRecognitionService(  868):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  868): Plugged
I/MotionRecognitionService(  868): setPowerConnected  = true
D/ConnectivityService(  868): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/SecContentProvider2(  868): uri = 14 selection = getSealedState
D/SecContentProvider2(  868): mCursor = null
D/SecContentProvider2(  868): KnoxCustomManagerService offline: service is not available
D/ResourcesManager( 7794): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3247): Disconnected process message: 10
I/SQLiteSecureOpenHelper( 3531): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3531): getDatabaseLocked(b,b,pwd)...
D/ApplicationPolicy(  868): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
V/ApplicationPolicy(  868): isApplicationStateBlocked userId -2 pkgname com.android.systemui
D/WindowManager(  868): showStatusBarByNotification() mOpenByNotification=false
D/PowerManagerService(  868): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10058 pid=1181
I/PowerManagerService(  868): !@[ps] Screen__On wl: PowerUI.Notification
I/PowerManagerService(  868): Waking up from sleep (uid 10058)...
D/PowerManagerService(  868): [PWL] sb acquire: PowerManagerService.Broadcasts
V/KeyguardServiceDelegate(  868): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@df2c6ec)
D/PowerManagerService(  868): [s] UserActivityState : 0 -> 1
D/PowerManagerService(  868): [PWL] sb acquire: PowerManagerService.Display
D/KeyguardViewMediator( 1181): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1181): notifyScreenOnLocked
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/DisplayPowerController(  868): Blocking screen on until initial contents have been drawn.
D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SContextService(  868): 	.registerCallback : 1, client=
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/CAE     (  868): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/InputManager-JNI(  868): setDeviceInteractive: 1
D/KeyguardViewMediator( 1181): handleNotifyScreenOn
D/AutomaticBrightnessController(  868): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/StatusBarKeyguardViewManager( 1181): onScreenTurnedOn()
D/DisplayPowerController(  868): getFinalBrightness : 0 -> 0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/AutomaticBrightnessController(  868): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/InputManager-JNI(  868): sysfs_write +: /sys/class/input/event2/device/enabled: 1
D/StatusBarKeyguardViewManager( 1181): callback.onShown()
I/CAE     (  868): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
D/AutomaticBrightnessController(  868): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
D/PowerManagerService(  868): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
V/KeyguardServiceDelegate(  868): **** SHOWN CALLED ****
D/MISC PowerHAL(  868): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
I/AutomaticBrightnessController(  868): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
D/MISC PowerHAL(  868): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
I/AutomaticBrightnessController(  868): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
I/CAE     (  868): setCAProperty(ContextAwareService.java:469) - result : true
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
W/CAE     (  868): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
I/QCOM PowerHAL(  868): Got set_interactive hint
V/BitmapFactory( 1181): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_battery_full.png
D/InputManager-JNI(  868): sysfs_write +: /sys/class/input/event1/device/enabled: 1
I/DisplayManagerService(  868): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SContextService(  868): sendProperty() : service = Auto Rotation
W/CAE     (  868): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
V/CAE     (  868): start(ContextProvider.java:126)
D/SurfaceFlinger(  257): Set power mode=2, type=0 flinger=0xb6962000
D/qdhwcomposer(  257): hwc_blank: Unblanking display: 0
,V/CAE     (  868): clear(AutoRotationRunner.java:182)
,V/CAE     (  868): enable(AutoRotationRunner.java:158)
,I/CAE     (  868): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager(  868): SendSensorHubData: send data = -79, 7, 0, 0
,D/SensorManager(  868): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/PowerManagerService(  868): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 49ms
,E/Sensors (  868): Acc old sensor_state 512, new sensor_state : 513 en : 1
,D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
D/Sensorhubs(  304): sendContextData: -79, 7, 0, 0
,D/NfcService( 1467): call the applyRotuiing
,D/SensorManager(  868): registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
D/PowerManagerService(  868): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 13ms
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/CAE     (  868): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  868): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/SamsungIME( 1859): showDlgMsgBox : false true true
,V/BitmapFactory( 1181): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_battery_full.png
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,V/UserPresentBroadcastReceiver( 2104): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/KnoxNotification( 1181): ----- inflateViews : modified publicViewLocal -----
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/KnoxNotification( 1181): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1181): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1181): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@2d8e1889
,D/SecContentProvider2(  868): uri = 14 selection = getSealedState
D/SecContentProvider2(  868): mCursor = null
D/SecContentProvider2(  868): KnoxCustomManagerService offline: service is not available
,D/InputManager-JNI(  868): sysfs_write -: /sys/class/input/event2/device/enabled: 1
,I/PhoneStatusBar( 1181): Icon Only
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/CAE     (  868): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): There is/are notification(s) 
I/CAE     (  868): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,D/CAE     (  868): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
I/CAE     (  868): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@31192e11, Service : AUTO_ROTATION(1)
,W/CAE     (  868): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  868): addSContextService() : service = Auto Rotation
D/SContextService(  868): ===== SContext Service List =====
D/SContextService(  868): Listener : android.hardware.scontext.SContextService$Listener@5e7fb76, Service : Auto Rotation
D/SContextManager(  868):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@2f82cab5, service=Auto Rotation
,D/DisplayPowerController(  868): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
I/DisplayPowerController(  868): Unblocked screen on after 139 ms
D/DisplayPowerState(  868): !@ ColorFade exit
,D/StatusBar.NetworkController( 1181): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/SurfaceFlinger(  257): id=13 Removed ColorFade (7/7)
I/WebViewFactory( 7794): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7794): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/SurfaceFlinger(  257): id=13 Removed ColorFade (-2/7)
E/libEGL  (  868): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
I/LibraryLoader( 7794): Loading: webviewchromium
I/LibraryLoader( 7794): Time to load native libraries: 2 ms (timestamps 9915-9917)
I/LibraryLoader( 7794): Expected native library version number "",actual native library version number ""
D/BatteryMeterView( 1181): onDraw batteryColor : -1
,V/WebViewChromiumFactoryProvider( 7794): Binding Chromium to main looper Looper (main, tid 1) {104233a2}
,I/LibraryLoader( 7794): Expected native library version number "",actual native library version number ""
I/chromium( 7794): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7794): Initializing chromium process, renderers=0
,W/art     ( 7794): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7794): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7794): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 7794): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/Adreno-EGL( 7794): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7794): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7794): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7794): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7794): Remote Branch: 
I/Adreno-EGL( 7794): Local Patches: 
I/Adreno-EGL( 7794): Reconstruct Branch: 
,D/InputManager-JNI(  868): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/PalmMotion(  868): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
D/PalmMotion(  868): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService(  868):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService(  868): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 868) 
D/LightsService(  868): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
V/ActivityManager(  868): Display changed displayId=0
,D/SSRM:a  (  868): DeviceInfo:: 000000000000
D/SSRM:a  (  868): SettingsAirViewInfo:: 000000000
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/LightsService(  868): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager(  868): unregisterListener ::   
D/lights  (  868): led_pattern : 5 +
,D/SLocation(  868): handleMessage got exceptionjava.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
,D/LightsService(  868): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 868) 
W/System.err(  868): java.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
,W/System.err(  868): 	at com.samsung.location.lib.h.handleMessage(Unknown Source)
W/System.err(  868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  868): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  868): 	at com.samsung.location.SLocationService.run(Unknown Source)
W/System.err(  868): 	at java.lang.Thread.run(Thread.java:818)
,D/lights  (  868): led_pattern : 5 -
D/LightsService(  868): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/LightsService(  868): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,D/BatteryService(  868): turn off LED
,D/LightsService(  868): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/lights  (  868): led_pattern : 0 +
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/CAE     (  868): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  868): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
D/lights  (  868): led_pattern : 0 -
D/LightsService(  868): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  868): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  868): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs(  304): sendContextData: -76, 13, -47, 0
,D/InputMethodManagerService(  868): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  257): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  257): hwc_blank: Done unblanking display: 0
,D/SurfaceControl(  868): Excessive delay in setPowerMode(): 269ms
D/lights  (  868): lcd : 8 +
,D/MotionRecognitionService(  868):   mReceiver.onReceive : ACTION_SCREEN_ON
D/lights  (  868): lcd : 8 -
E/MotionRecognitionService(  868):  handler : SCREEN_ON end
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
D/PowerManagerService(  868): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  868): SecHardwareInterface.setBatteryADC : true
,D/PowerManagerService(  868): [input device light] setInputDeviceLightOn is called : 1
D/PowerManagerService(  868): [input device light] handleInputDeviceLightOn
D/lights  (  868): button : 1 +
,W/chromium( 7794): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7794): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,D/WifiStateMachine(  868): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  868): handleScreenStateChanged Exit: true
,D/NotificationService(  868): ACTION_SCREEN_ON
D/LightsService(  868): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 868) 
D/LightsService(  868): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService(  868): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  868): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  298): adev_set_parameters: enter: screen_state=on
V/voice   (  298): voice_set_parameters: enter: screen_state=on
V/voice   (  298): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  298): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  298): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  298): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  298): adev_set_parameters: exit
,W/art     ( 7794): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7794): onDetachedFromWindow called when already detached. Ignoring
,I/SecExternalDisplayIntents_Java(  868): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController(  868): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  868): Bridge Server is not available
,E/WifiStateMachine(  868): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  868): do suspend false
,D/lights  (  868): button : 1 -
,I/wpa_supplicant( 1304): reset timer : RESET_TIMER 1
I/wpa_supplicant( 1304): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1304): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 1304): Scan requested (ret=0) - scan timeout 30 seconds
D/PersonaManagerService(  868): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler(  868): MSG_ACTION_SCREEN_ON called
,I/NfcService( 1467): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1467): call the applyRotuiing
,D/SystemWebViewEngine( 7794): CordovaWebView is running on device made by: samsung
,W/art     ( 7794): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 7794): Attempt to remove local handle scope entry from IRT, ignoring
,I/SamsungIME( 1859): getNextShiftState() cursorCapsMode : 0
,D/accuweather( 2204): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
D/accuweather( 2204): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
,D/accuweather( 2204): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/accuweather( 2204): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
D/accuweather( 2204): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/accuweather( 2204): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/SurfaceWidget.Renderer( 2204): [237392/6] SurfaceWidget drawing first frame
,W/ActivityManager(  868): Activity pause timeout for ActivityRecord{13f094c u0 com.example.hello/.MainActivity t3}
,V/ActivityManager(  868): Display changed displayId=0
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/Activity( 7794): performCreate Call secproduct feature valuefalse
,D/Activity( 7794): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/OpenGLRenderer( 7794): Render dirty regions requested: true
,D/ActivityManager(  868): post active user change for 0
D/KnoxTimeoutHandler(  868): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  868): handleActiveUserChange for user 0
,D/SurfaceWidget.Renderer( 2204): [237392/6] SurfaceWidget drawing first frame
,D/ConnectivityService(  868): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ActivityManager(  868): post active user change for 0
D/KnoxTimeoutHandler(  868): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  868): handleActiveUserChange for user 0
,I/SystemBroadcastReceiver( 7363): [#DCM#] [DCM_Performance] onReceive completed in time  2099 microsec. 
,I/SystemBroadcastReceiver( 7363): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7363): [#DCM#] onReceive action = EVENT_SCREEN_ON
I/DCMController( 7363): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
D/PowerManagerService(  868): [PWL] sb release: PowerManagerService.Broadcasts
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=404, com.example.hello/com.example.hello.MainActivity
,D/StatusBarManagerService(  868): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/StatusBarManagerService(  868): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/SSRM:m  (  868): SIOP:: AP = 350, PST = 405, CUR = 450
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/OpenGLRenderer( 7794): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7794): HWUI protection enabled for context ,  &this =0xa1853060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7794): Enabling debug mode 0
,D/daemonapp( 1338): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1338): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1338): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/daemonapp( 1338): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1338): [MSC_Daemon]>>> WDSM:41 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1338): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1338): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
,D/comsamsunglog( 1338): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1338): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1338): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,D/daemonapp( 1338): [MSC_Daemon]>>> WDSM:418 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1338): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/daemonapp( 1338): [MSC_Daemon]>>> WDSM:421 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1338): [MSC_Daemon]>>> WDSM:422 [0:0] [ASO][NUT] = 1450220580000
,D/daemonapp( 1338): [MSC_Daemon]>>> WDSM:423 [0:0] [ASO][CT] = 1450199093728
,D/daemonapp( 1338): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1338): [MSC_Daemon]>>> WU:1622 [0:0] PakNme size = 5
,D/daemonapp( 1338): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1338): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1338): [MSC_Daemon]>>> WU:1626 [0:0] CP Name cp_eng
,D/daemonapp( 1338): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/InputMethodManagerService(  868): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/daemonapp( 1338): [MSC_Daemon]>>> WU:1606 [0:0] [NameNotFoundException] !!
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,W/ContextImpl(  868): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  868): mDVFSHelper.release()
I/Timeline(  868): Timeline: Activity_windows_visible id: ActivityRecord{13f094c u0 com.example.hello/.MainActivity t3} time:80391
,D/CustomFrequencyManagerService(  868): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 868  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/ContextImpl(  868): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/Timeline( 7794): Timeline: Activity_idle id: android.os.BinderProxy@1a2159dd time:80408
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/Timeline( 7794): Timeline: Activity_idle id: android.os.BinderProxy@1a2159dd time:80410
,E/Adreno-ES20( 7794): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7794): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/chromium( 7794): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 7794): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/art     (  868): Explicit concurrent mark sweep GC freed 55808(3MB) AllocSpace objects, 11(176KB) LOS objects, 30% free, 35MB/51MB, paused 1.172ms total 110.040ms
,D/JsMessageQueue( 7794): Set native->JS mode to OnlineEventsBridgeMode
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,I/chromium( 7794): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7794): 
,D/CustomFrequencyManagerService(  868): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 868  tag : ACTIVITY_RESUME_BOOSTER@10
,D/jxcore_app_log( 7794): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359649792
,D/JX-Cordova( 7794): jxcore cordova android initializing
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,W/jxcore-log( 7794): Initializing JXcore engine
,W/jxcore-log( 7794): JXcore engine is ready
,W/jxcore-log( 7794): Starting JXcore engine
,E/auditd  ( 2026): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  868): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  868): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  868): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7871): MountEmulatedStorage()
I/libpersona( 7871): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7871): v2
I/libpersona( 7871): KNOX_SDCARD not a persona
,I/ActivityManager(  868): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7871 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/SELinux ( 7871): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7871): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7871): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 7794): Platform android
W/jxcore-log( 7794): 
,W/jxcore-log( 7794): Process ARCH arm
W/jxcore-log( 7794): 
,D/TimaKeyStoreProvider( 7871): TimaSignature is unavailable
,D/ActivityThread( 7871): Added TimaKeyStore provider
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,V/AlarmManager(  868): waitForAlarm result :4
,I/jxcore-log( 7794): JXcore Cordova bridge is ready!
I/jxcore-log( 7794): 
,W/jxcore-log( 7794): JXcore engine is started
,D/ResourcesManager( 7871): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,E/jxcore-log( 7794): >> samsung-SM-G900F
E/jxcore-log( 7794): 
,I/jxcore-log( 7794): Total memory 1787449344
I/jxcore-log( 7794): 
,I/jxcore-log( 7794): Free memory 46620672
I/jxcore-log( 7794): 
I/jxcore-log( 7794): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7794): 
I/jxcore-log( 7794): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7794): 
,I/jxcore-log( 7794): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 7794): 
,I/jxcore-log( 7794): Size 1080 1920
I/jxcore-log( 7794): 
,I/jxcore-log( 7794): Screen Brightness 134
I/jxcore-log( 7794): 
,E/jxcore-log( 7794): Dummy Error Log.
E/jxcore-log( 7794): 
,D/SecurityLogAgent( 7871):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7871):  SeDenialReceiver : File path = null
,D/SSRM:a  (  868): DeviceInfo:: 000000000000
D/SSRM:a  (  868): SettingsAirViewInfo:: 000000000
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/Finsky  ( 7036): [1180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7036): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  868): Killing 6753:com.google.android.apps.docs/u0a97 (adj 15): bgCount ##41
,W/libprocessgroup(  868): failed to open /acct/uid_10097/pid_6753/cgroup.procs: No such file or directory
,W/ContextImpl(  868): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,I/jxcore-log( 7794): getBuffer is called!!!!
I/jxcore-log( 7794): 
,D/PowerManagerService(  868): [input device light] handleInputDeviceLightOff
,D/lights  (  868): button : 0 +
,D/lights  (  868): button : 0 -
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/ConnectivityService(  868): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,E/SMD     (  291): DCD ON
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 5
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
,D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
,D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  868): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  868): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  868): CMD_RSSI_POLL : out!
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
,D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,I/wpa_supplicant( 1304): nl80211: Received scan results (6 BSSes)
,D/WifiP2pService(  868): InactiveState{ what=147461 }
,D/WifiP2pService(  868): P2pEnabledState{ what=147461 }
,D/WifiP2pService(  868): DefaultState{ what=147461 }
,E/WifiStateMachine(  868): [1,450,199,097,306 ms] noteScanEnd no scan source
,E/WifiStateMachine(  868): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@7c85a3f sup_state=COMPLETED debouncing=false
,I/CLocInfoService(  868): External Intent Received android.net.wifi.SCAN_RESULTS
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
,D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
,D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
,D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,V/AlarmManager(  868): waitForAlarm result :8
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,V/GLSActivity( 2104): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2104): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  868): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
,D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,E/SMD     (  291): DCD ON
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
,D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
,D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,D/BluetoothAdapter( 7794): disable()
,D/SettingsProvider(  868): name = bluetooth_on
,D/BluetoothAdapterState( 3247): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 3247): Setting state to 13
I/BluetoothAdapterState( 3247): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 3247): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3247): updateAdapterState state is 13
,D/WifiService(  868): New client listening to asynchronous messages
,I/WifiManager( 7794): packageName : com.example.hello
,D/SecContentProvider(  868): uri = 18 selection = isWifiEnabled
,I/BluetoothPbapService( 3247): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/SecContentProvider2(  868): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  868): mCursor = null
,D/BluetoothAdapterService( 3247): Autoconnection is available 
D/BluetoothAdapterService( 3247): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 3247): terminating service from this receiver
,D/WifiService(  868): setWifiEnabled: false pid=7794, uid=10357
E/WifiService(  868): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothSocket( 3247): close() in, this: android.bluetooth.BluetoothSocket@3ca55262, channel: 19, state: LISTENING
D/SettingsProvider(  868): name = wifi_on
,D/BluetoothSocket( 3247): close() this: android.bluetooth.BluetoothSocket@3ca55262, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@195a9c7b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@b4a1ff3mSocket: android.net.LocalSocket@d3dd4b0 impl:android.net.LocalSocketImpl@2a415f29 fd:FileDescriptor[74]
D/BluetoothSocket( 3247): Closing mSocket: android.net.LocalSocket@d3dd4b0 impl:android.net.LocalSocketImpl@2a415f29 fd:FileDescriptor[74]
,W/InputMethodManagerService(  868): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  868): [BT Setting State] State =13
,I/SamsungIME( 1859): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,V/BluetoothEventManager( 1314): Received android.bluetooth.adapter.action.STATE_CHANGED
,I/jxcore-log( 7794): ****TEST TOOK:  5097  ms ****
I/jxcore-log( 7794): 
,I/jxcore-log( 7794): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7794): 
,E/WifiStateMachine(  868): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1304): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1304): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1304): P2P: Current p2p state = IDLE
E/WifiStateMachine(  868): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
D/BluetoothAdapterProperties( 3247): onBluetoothDisable()
E/WifiStateMachine(  868): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  868): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  868): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/SecContentProvider(  868): uri = 3 selection = isDiscoverableEnabled
I/BluetoothAdapterState( 3247): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/wpa_supplicant( 1304): Scan requested (ret=0) - scan timeout 30 seconds
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): proc btwrite assertion
,D/BluetoothTile( 1181): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterProperties( 3247): Scan Mode:20
,D/BluetoothAdapterState( 3247): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 3247): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 3247): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/bt-btif ( 3247): cmd socket is not created
,E/BtOppRfcommListener( 3247): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/STATUSBAR-QSTileView( 1181): onStateChanged: Bluetooth
,D/btif_config_util( 3247): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
,D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
D/BluetoothSocket( 3247): close() in, this: android.bluetooth.BluetoothSocket@2b8a32ae, channel: 5, state: LISTENING
D/BluetoothSocket( 3247): close() this: android.bluetooth.BluetoothSocket@2b8a32ae, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19bf4c0a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@5dcc84fmSocket: android.net.LocalSocket@238bdc impl:android.net.LocalSocketImpl@2be7c4e5 fd:FileDescriptor[72]
D/BluetoothSocket( 3247): Closing mSocket: android.net.LocalSocket@238bdc impl:android.net.LocalSocketImpl@2be7c4e5 fd:FileDescriptor[72]
I/BtOppRfcommListener( 3247): stopping Accept Thread
D/BluetoothSocket( 3247): close() in, this: android.bluetooth.BluetoothSocket@3dcacbba, channel: 12, state: LISTENING
D/BluetoothSocket( 3247): close() this: android.bluetooth.BluetoothSocket@3dcacbba, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11231d2d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@25479a6bmSocket: android.net.LocalSocket@a4b89c8 impl:android.net.LocalSocketImpl@3ed4ca61 fd:FileDescriptor[77]
D/BluetoothSocket( 3247): Closing mSocket: android.net.LocalSocket@a4b89c8 impl:android.net.LocalSocketImpl@3ed4ca61 fd:FileDescriptor[77]
I/BtOppRfcommListener( 3247): BluetoothSocket listen thread finished
,E/WifiStateMachine(  868): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  868): InactiveState{ what=143375 }
D/WifiP2pService(  868): P2pEnabledState{ what=143375 }
,E/ActivityThread( 3247): Service com.samsung.ble.BleAutoConnectService has leaked IntentReceiver com.samsung.ble.BleAutoConnectService$4@172c95b9 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3247): android.app.IntentReceiverLeaked: Service com.samsung.ble.BleAutoConnectService has leaked IntentReceiver com.samsung.ble.BleAutoConnectService$4@172c95b9 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3247): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:960)
E/ActivityThread( 3247): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:761)
E/ActivityThread( 3247): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1945)
E/ActivityThread( 3247): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1925)
E/ActivityThread( 3247): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1919)
E/ActivityThread( 3247): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
E/ActivityThread( 3247): 	at com.samsung.ble.BleAutoConnectService.onCreate(BleAutoConnectService.java:139)
E/ActivityThread( 3247): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 3247): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 3247): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 3247): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3247): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3247): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 3247): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3247): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3247): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 3247): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/CommandListener(  283): Clearing all IP addresses on wlan0
E/bt-btm  ( 3247): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 3247): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 3247): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3247): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3247): L2CAP - PSM: 0x001b not found for deregistration
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
V/NativeCrypto( 2104): Read error: ssl=0xad368600: I/O error during system call, Connection timed out
V/NativeCrypto( 2104): SSL shutdown failed: ssl=0xad368600: I/O error during system call, Broken pipe
W/ContextImpl( 1314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,E/WifiStateMachine(  868): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService(  868): updateNetworkInfo()
D/ConnectivityService(  868): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  868): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/ConnectivityService(  868): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiConfigStore(  868): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller(  868): evaluateTrafficStatsPolling
,I/CLocInfoService(  868): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  868): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/BluetoothPbap( 1314): Proxy object disconnected
D/PbapServerProfile( 1314): Bluetooth service disconnected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  868): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  868): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  868): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  868): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  868): Validated
,D/ConnectivityService(  868): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  868): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  868): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/DockEventReceiver( 1314): finishStartingService: stopping service
,W/ContextImpl(  868): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/WifiStateMachine(  868): scanCount==0 - aborting
D/WifiScanningService(  868): SCAN_AVAILABLE : 1
,D/WifiScanningService(  868): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  868): SCAN_AVAILABLE : 1
D/RttService(  868): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  868): [1,450,199,099,605 ms] noteScanEnd no scan source
,D/BluetoothNotiBroadcastReceiver( 1314): onReceive
,D/WifiP2pService(  868): InactiveState{ what=131204 }
D/WifiP2pService(  868): P2pEnabledState{ what=131204 }
,D/WifiP2pService(  868): sending p2p connection changed broadcast: FAILED
,E/WifiStateMachine(  868): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  868): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  868): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  868): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  868): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/AuthorizationBluetoothService( 2104): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/ConnectivityService(  868): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  868): calling update connectivity
,D/ConnectivityService(  868):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  868):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  868): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  868):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  868): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  868): Not allowed due to - mEnabled false
D/Nat464Xlat(  868): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  868): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  868): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 1474): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiDisplayController(  868): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter(  868): onP2pDisconnected
,D/IpRemoteDisplayController(  868): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  868): WfdBridgeServer is already null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  868): ValidatedState{ when=-8ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  868): DefaultState{ when=-8ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  868): Disconnected - quitting
,D/CSLegacyTypeTracker(  868): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  868): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  868): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  868): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  868): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  868): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  868): getSBEnabled() enabled =false
V/NetworkStats(  868): updateIfacesLocked()
V/NetworkStats(  868): performPollLocked(flags=0x1)
D/NtpTrustedTime(  868): currentTimeMillis() cache hit
,D/SmartBondingService(  868): getSBEnabled() enabled =false
D/ConnectivityManager.CallbackHandler( 2538): CM callback handler got msg 524292
D/SmartBondingService(  868): getSBEnabled() enabled =false
,D/NetworkStatsFactory(  868): UpdateStatsForKnox
D/ConnectivityService(  868): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityService(  868): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/SmartBondingService(  868): getNetworkEnabled : wifi : true mobile : true
,E/ConnectivityService(  868): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/ConnectivityService(  868): updateNetworkInfo()
,D/ConnectivityService(  868): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NtpTrustedTime(  868): currentTimeMillis() cache hit
D/WifiP2pService(  868): sending p2p connection changed broadcast: DISCONNECTED
,D/NtpTrustedTime(  868): currentTimeMillis() cache hit
,D/NtpTrustedTime(  868): currentTimeMillis() cache hit
D/WifiP2pService(  868): P2pDisablingState
V/NetworkStats(  868): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/WifiP2pService(  868): P2pDisablingState{ what=147458 }
D/NtpTrustedTime(  868): currentTimeMillis() cache hit
D/WifiP2pService(  868): p2p socket connection lost
,E/ConnectivityService(  868): updateNetworkInfo()
D/ConnectivityService(  868): ignoring duplicate network state non-change
,E/WifiStateMachine(  868): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,E/WifiStateMachine(  868): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - enter - invokeEnterMethods
,E/WifiStateMachine(  868): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiDisplayController(  868): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,D/WifiDisplayController(  868): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiP2pService(  868): P2pDisabledState
D/WifiDisplayController(  868): disconnect
V/NetworkStats(  868): performPollLocked() took 12ms
D/WifiDisplayController(  868): updateConnection
D/WifiDisplayController(  868): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  868): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService(  868): P2pDisabledState{ what=143375 }
,D/WifiP2pService(  868): DefaultState{ what=143375 }
D/NtpTrustedTime(  868): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/WifiDisplayController(  868): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter(  868): onP2pDisconnected
D/IpRemoteDisplayController(  868): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  868): WfdBridgeServer is already null
,D/CommandListener(  283): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/WifiStateMachine(  868): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/NtpTrustedTime(  868): currentTimeMillis() cache hit
D/NtpTrustedTime(  868): currentTimeMillis() cache hit
,E/WifiStateMachine(  868): stopping supplicant
,I/Hs20UtilService( 1314): Starting #6
,I/Hs20UtilService( 1314): Message received 5007
I/WifiTrafficPoller(  868): evaluateTrafficStatsPolling
,I/wpa_supplicant( 1304): p2p0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  868): setWifiState: disabling
I/CLocInfoService(  868): External Intent Received android.net.wifi.STATE_CHANGE
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  868): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/AllShareCastTile( 1181): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter(  868): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1181): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
D/ConnectivityService(  868): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1314): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1314): MountReceiver.mPrefHandler - 7002
D/SmartBondingService(  868): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/SmartBondingService(  868): getNetworkEnabled : wifi : false mobile : true
D/SecContentProvider2(  868): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  868): mCursor = null
D/SLocation(  868): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/WifiCredService( 1314): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1181): Wifi onReceive(0)
D/HotspotTile( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1181): onStateChanged: Wi-Fi
E/WifiStateMachine(  868): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  868): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/HotspotTile( 1181): onReceive : 0, 0
W/bt-l2cap( 3247): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3247): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3247): L2CAP - PSM: 0x001b not found for deregistration
D/bt_vendor( 3247): op for 6
W/bt-l2cap( 3247): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3247): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3247): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3247): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3247): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3247): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 3247): ag scb idx 1 not allocated
W/bt-btif ( 3247): ag scb idx 2 not allocated
E/bt-btif ( 3247): BTA AG is already disabled, ignoring ...
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_userial( 3247): RX termination
W/bt_userial( 3247): select_read return size <=0:-1, exiting userial_read_thread
V/BitmapFactory( 1181): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_wifi_dim.png
D/bt_userial( 3247): Leaving userial_read_thread()
D/bt_userial( 3247): userial_close_reader Joined userial reader thread: 0
D/bt_vendor( 3247): op for 9
D/bt_hwcfg( 3247): hw_epilog_process
D/bt_vendor( 3247): op for 4
I/bt_userial_vendor( 3247): device fd = 65 close
D/bt_vendor( 3247): op for 0
D/bt_upio ( 3247): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 3247): is_emulator_context : 0
D/bt_upio ( 3247): is_rfkill_disabled ? [0]
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  868): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/bt_vendor( 3247): cleanup
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/GKI_LINUX( 3247): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3247): GKI_exit_task 0 done
I/GKI_LINUX( 3247): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3247): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 3247): isSecureModeOn:false
D/BluetoothAdapterService( 3247): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 3247): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/ConnectivityService(  868): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 3247): Not skipping com.android.bluetooth.gatt.GattService
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1314): MountReceiver.onReceive - Set preference state off
W/BluetoothAdapterService( 3247): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 3247): handleDebugAction() action=null
W/BluetoothAdapterService( 3247): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.GattService( 3247): Received stop request...Stopping profile...
D/BtGatt.GattService( 3247): stop()
D/BtGatt.AdvertiseManager( 3247): advertise clients cleared
W/BluetoothAdapterService( 3247): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 3247): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39d7a169
W/BluetoothAdapterService( 3247): Not skipping com.android.bluetooth.a2dp.A2dpService
V/NearbySettings( 1314): MountReceiver.mPrefHandler - 7002
D/HeadsetService( 3247): Received stop request...Stopping profile...
W/BluetoothAdapterService( 3247): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 3247): Not skipping com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 3247): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3247): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39d7a169
W/BluetoothAdapterService( 3247): Not skipping com.android.bluetooth.hdp.HealthService
D/FileShare-Server( 7214): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/HeadsetProfile( 1314): Bluetooth service disconnected
W/BluetoothAdapterService( 3247): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/AudioService(  868): onServiceDisconnected: Bluetooth profile: 1
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/AndroidRuntime( 7937): 
D/AndroidRuntime( 7937): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/BluetoothAdapterService( 3247): Not skipping com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 3247): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3247): Not skipping com.android.bluetooth.map.BluetoothMapService
D/AndroidRuntime( 7937): CheckJNI is OFF
W/BluetoothAdapterService( 3247): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 3247): Not skipping com.broadcom.bt.service.sap.SapService
D/AndroidRuntime( 7937): setted country_code = Poland
D/AndroidRuntime( 7937): setted countryiso_code = PL
W/BluetoothAdapterService( 3247): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 3247): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 3247): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/AndroidRuntime( 7937): setted sales_code = XEO
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
D/AndroidRuntime( 7937): readGMSProperty: start
D/AndroidRuntime( 7937): readGMSProperty: already setted!!
W/BluetoothAdapterService( 3247): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 3247): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
D/AndroidRuntime( 7937): readGMSProperty: end
D/AndroidRuntime( 7937): addProductProperty: start
W/BluetoothAdapterService( 3247): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 3247): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 3247): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 3247): Stopping profile services that were post enabled
E/BluetoothAdapterService(970432873)( 3247): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/A2dpService( 3247): Received stop request...Stopping profile...
V/Avrcp   ( 3247): doQuit
D/A2dpStateMachine( 3247): Exit Disconnected: -1
D/Avrcp   ( 3247): Unregistering previous receiver
D/BluetoothAdapterService( 3247): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39d7a169
D/BluetoothA2dp(  868): Proxy object disconnected
D/AudioService(  868): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 3247): Received stop request...Stopping profile...
D/HidService( 3247): Stopping Bluetooth HidService
D/BluetoothAdapterService( 3247): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39d7a169
D/BluetoothA2dp( 3531): Proxy object disconnected
D/BluetoothA2dp( 1314): Proxy object disconnected
D/A2dpProfile( 1314): Bluetooth service disconnected
D/BluetoothInputDevice( 1314): Proxy object disconnected
D/HidProfile( 1314): Bluetooth service disconnected
E/BluetoothAdapterService(970432873)( 3247): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 3247): Profile still running: com.android.bluetooth.hid.HidService
W/BluetoothHeadsetServiceJni( 3247): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3247): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 3247): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3247): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39d7a169
,D/PanService( 3247): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3247): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39d7a169
D/BluetoothPan(  868): BluetoothPAN Proxy object disconnected
D/BluetoothMapService( 3247): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3247): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39d7a169
D/SapService( 3247): Received stop request...Stopping profile...
D/SapService( 3247): Stopping Bluetooth SapService
D/BluetoothAdapterService( 3247): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39d7a169
D/BluetoothPan( 1314): BluetoothPAN Proxy object disconnected
D/PanProfile( 1314): Bluetooth service disconnected
I/Hs20UtilService( 1314): Starting #7
I/Hs20UtilService( 1314): Message received 5007
D/BluetoothMap( 1314): Proxy object disconnected
D/MapProfile( 1314): Bluetooth service disconnected
D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
E/BluetoothAdapterService(970432873)( 3247): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 3247): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 3247): Proxy object disconnected
D/BluetoothAdapterService( 3247): Bluetooth A2dp source service disconnected
V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
I/GKI_LINUX( 3247): gki_task task_id=2 [A2DP-MEDIA] terminating
I/wpa_supplicant( 1304): Blacklist: Clear (all) 
I/GKI_LINUX( 3247): GKI_exit_task 2 done
I/GKI_LINUX( 3247): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   ( 3247): cleanup
E/BluetoothAdapterService(970432873)( 3247): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/ConnectivityService(  868): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3247): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHidServiceJni( 3247): Cleaning up Bluetooth HID Interface...
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
W/bt-btif ( 3247): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3247): Cleaning up Bluetooth GID callback object
E/BluetoothAdapterService(970432873)( 3247): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3247): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 3247): Cleaning up Bluetooth Health Interface...
D/ConnectivityService(  868): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1314): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1314): MountReceiver.mPrefHandler - 7002
W/BluetoothHealthServiceJni( 3247): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(970432873)( 3247): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3247): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3247): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3247): Cleaning up Bluetooth PAN callback object
D/Bluetoothsap( 1314): BluetoothSAP Proxy object disconnected
D/SapProfile( 1314): Bluetooth service disconnected
E/BluetoothAdapterService(970432873)( 3247): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3247): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 3247): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(970432873)( 3247): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 3247): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3247): Setting state to 10
I/BluetoothAdapterState( 3247): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3247): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3247): updateAdapterState state is 10
W/BluetoothSAPServiceJni( 3247): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 3247): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService( 3247): Autoconnection is available 
D/BluetoothAdapterService( 3247): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 3247): Entering OffState
D/BluetoothA2dp( 3531): onBluetoothStateChange: up=false
D/BluetoothA2dp(  868): onBluetoothStateChange: up=false
D/BluetoothPbap( 1314): onBluetoothStateChange: up=false
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/Bluetoothsap( 1314): onBluetoothStateChange: up=false
D/Bluetoothsap( 1314): Unbinding service...
,D/BluetoothMap( 1314): onBluetoothStateChange: up=false
,D/ConnectivityService(  868): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7871): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7871): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7871): StateMachine : Current State = 1
D/BluetoothInputDevice( 1314): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3247): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,I/wpa_supplicant( 1304): p2p0: CTRL-EVENT-TERMINATING 
,D/BluetoothA2dp( 1314): onBluetoothStateChange: up=false
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,I/wpa_supplicant( 1304): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1304): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1304): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1304): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/SecurityLogAgent( 7871): StateMachine : Changed Current State = 1
,D/BluetoothManagerService(  868): Broadcasting onBluetoothServiceDown() to 14 receivers.
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/BluetoothManagerService(  868): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,E/AffinityControl( 7937): AffinityControl: registerfunction enter
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,I/GKI_LINUX( 3247): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3247): GKI_exit_task 1 done
I/GKI_LINUX( 3247): GKI_shutdown(): task [BTIF] terminated
W/InputMethodManagerService(  868): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  868): [BT Setting State] State =10
I/InputMethodManagerService(  868): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/BluetoothServiceJni( 3247): cleanupNative: return from cleanup
,D/BluetoothAdapter( 1181): 1064264016: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1181): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/STATUSBAR-QSTileView( 1181): onStateChanged: Bluetooth
D/BluetoothAdapter( 1181): 1064264016: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1181): 1064264016: getState() :  mService = null. Returning STATE_OFF
,I/SamsungIME( 1859): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,V/BluetoothEventManager( 1314): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/AndroidRuntime( 7937): Calling main entry com.android.commands.pm.Pm
,I/art     ( 3247): System.exit called, status: 0
I/AndroidRuntime( 3247): VM exiting with result code 0, cleanup skipped.
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/[CarModeFW]( 6824): ConnectivityManager-handleMessage INITIAL_STATE_OFF
,D/BluetoothAdapter( 2104): 134761843: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 2104): 134761843: getState() :  mService = null. Returning STATE_OFF
,W/ContextImpl( 1314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/PackageManager(  868): START PACKAGE DELETE: observer{259107557}
D/PackageManager(  868): pkg{<packageName>}
D/PackageManager(  868): user{0}
D/PackageManager(  868): caller{2000}
D/PackageManager(  868): flags{3}
,D/PersonaManagerService(  868): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  868): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  868): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  868): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  868): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  868): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  868): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  868): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy(  868): getApplicationUninstallationEnabled
D/ApplicationPolicy(  868): getApplicationUninstallationEnabled :  enabled true
D/DockEventReceiver( 1314): finishStartingService: stopping service
,D/PackageManager(  868): !@killApplicatoin: 10357, uninstall pkg
,I/ActivityManager(  868): Force stopping com.example.hello appid=10357 user=-1: uninstall pkg
,I/ActivityManager(  868): Killing 7794:com.example.hello/u0a357 (adj 0): stop com.example.hello
,W/ActivityManager(  868): Force removing ActivityRecord{13f094c u0 com.example.hello/.MainActivity t3}: app died, no saved state
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/BluetoothNotiBroadcastReceiver( 1314): onReceive
,I/SurfaceFlinger(  257): id=14 Removed com.example.hello/com.example.hello.MainActivity (6/7)
,I/SurfaceFlinger(  257): id=14 Removed com.example.hello/com.example.hello.MainActivity (-2/7)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/wpa_supplicant( 1304): Blacklist: Clear (all) 
,D/FocusedStackFrame(  868): Set to : 0
,I/SQLiteSecureOpenHelper( 3531): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3531): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/CustomFrequencyManagerService(  868): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 868  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  868): mDVFSHelper.acquire()
,D/WifiService(  868): Client connection lost with reason: 4
,W/PackageSettings(  868): Skipping PackageSetting{103883f8 com.test.thalitest/10356} due to missing metadata
,V/WindowOrientationListener(  868): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  868): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  868): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  868): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  868): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/SurfaceWidgetView( 1487): destroyHardwareResources():656101123
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/Launcher( 1487): onRestart, Launcher: 927425308
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/ActivityManager(  868): Process com.android.bluetooth (pid 3247)(adj 0) has died(113,614)
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
,V/AlarmManager(  868): waitForAlarm result :8
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/Zygote  ( 7973): MountEmulatedStorage()
E/Zygote  ( 7973): v2
,I/libpersona( 7973): KNOX_SDCARD checking this for 1002
I/libpersona( 7973): KNOX_SDCARD not a persona
,I/ActivityManager(  868): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7973 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/ActivityManager(  868): Force stopping com.example.hello appid=10357 user=0: pkg removed
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
I/SELinux ( 7973): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7973): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7973): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LightSensor(  868): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/TimaKeyStoreProvider( 7973): TimaSignature is unavailable
,D/ActivityThread( 7973): Added TimaKeyStore provider
,I/wpa_supplicant( 1304): wlan0: CTRL-EVENT-TERMINATING 
,E/WifiStateMachine(  868): Supplicant connection lost
,D/ConnectivityService(  868): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  868): InitialState.processMessage what=4
,D/Launcher( 1487): onStart, Launcher: 927425308
D/Launcher.HomeView( 1487): onStart
,D/Launcher( 1487): onResume, Launcher: 927425308
,D/SettingsProvider(  868): name = kids_home_mode
D/SettingsProvider(  868): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  868): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  868): selectionArgs: false
D/SettingsProvider(  868): selectionArgs: 10008
D/SecContentProvider(  868): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  868): ret = -1
,D/Launcher.HomeView( 1487): onResume
,I/art     ( 6641): Explicit concurrent mark sweep GC freed 30765(1684KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 341us total 27.625ms
,E/Tethering(  868): No numeric data
,D/Launcher( 1487): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2204): [237392/6] Surface widget resume on instance = 1
,D/Launcher( 1487): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,E/WifiStateMachine(  868): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-HAL(  868): callSECApiBoolean - ID [21]
E/WifiStateMachine(  868): setWifiState: disabled
D/accuweather( 2204): [KK AccuPhone]>>> SWW:209 [0:0] [SWW] onResume : instance = 1
,D/Tethering(  868): sendTetherStateChangedBroadcast 0, 0, 0
,D/MenuAppsGridFragment( 1487): onResume
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2204): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2204): [237392/6] SurfaceWidget drawing first frame
,D/ActivityManager(  868): handle home activity for 0
I/WallpaperManagerService(  868): switchPersonaWallpaper is called for personaId-0
D/ActivityManager(  868): post active user change for 0
D/KnoxTimeoutHandler(  868): postActiveUserChange for user 0
,D/daemonapp( 1338): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/SurfaceFlinger(  257): id=15 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  868): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 7973): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,I/InputReader(  868): Reconfiguring input devices.  changes=0x00000010
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/Launcher( 1487): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1487): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/InputMethodManagerService(  868): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ResourcesManager( 7973): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 7973): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,W/ContextImpl(  868): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService(  868): Got RemoteException sending setActive(false) notification to pid 7794 uid 10357
,E/SamsungIME( 1859): mOCRHelper is null
,D/ConnectivityService(  868): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/GeofencerStateMachine( 2104): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager( 1487): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 1487): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1487): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1487): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,W/Settings( 6497): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ResourcesManager( 1487): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1487): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1487): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1181): Wifi onReceive(1)
D/HotspotTile( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1181): onStateChanged: Wi-Fi
,D/HotspotTile( 1181): onReceive : 1, 0
,V/BitmapFactory( 1181): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_wifi_off.png
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,V/NetworkStats(  868): performPollLocked(flags=0x1)
D/NtpTrustedTime(  868): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  868): UpdateStatsForKnox
D/ConnectivityService(  868): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/HotspotTile( 1181): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1181): updateTetherState():false, false
,V/NetworkStats(  868): performPollLocked() took 3ms
D/NtpTrustedTime(  868): currentTimeMillis() cache hit
,W/Settings( 2104): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiCredService( 1314): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  868): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  868): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/MicrophoneInputStream( 1579): mic_starting gfk@1c2a5a6
,I/HotwordRecognitionRnr( 1579): Starting hotword detection.
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,V/AudioPolicyManager(  298): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager(  298): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  298): adev_open_input_stream: enter
,E/audio_hw_primary(  298): adev_open_input_stream : jack_config 0
E/audio_hw_primary(  298): can not make /data/snd/hal_input.pcm 
,E/audio_hw_primary(  298): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  298): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  298): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  298): adev_open_input_stream: exit
,I/AudioFlinger(  298): AudioFlinger's thread 0xafc56000 ready to run
V/audio_hw_primary(  298): in_standby: enter
V/audio_hw_primary(  298): in_standby: exit:  status(0)
,V/audio_hw_primary(  298): in_standby: enter
,V/audio_hw_primary(  298): in_standby: exit:  status(0)
,D/ConnectivityService(  868): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/EDMNativeHelperService(  868): isMicrophoneEnabled
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,E/LightSensor(  868): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/ConnectivityService(  868): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/AudioPolicyManager(  298): startInput() input 30
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
V/AudioPolicyManager(  298): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  298): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  298): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  298): DeviceVector::getDevicesFromType() for type 80000004 found 0xb295b3c0
,V/audio_hw_primary(  298): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  298): in_set_parameters: exit: status(11)
V/AudioPolicyManager(  298): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  298): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1579): mic_started gfk@1c2a5a6
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/WallpaperManager( 1487): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1487): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1487): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,V/msm8974_platform(  298): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  298): start_input_stream: enter: usecase(7)
V/voice   (  298): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  298): start_input_stream: usecase(7)
D/PreProcess(  298): new SamsungRecord
D/PreProcess(  298): new NS
I/samsungRecord(  298): [samsungrecord] SamsungRecInit 
,I/samsungRecord(  298): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  298): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  298): 1
D/SamsungRecord_NS(  298): [SamsungRecord_NS] Init SR 16000
D/SamsungRecord_NS(  298): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  298): select_devices: ENTER
V/audio_hw_primary(  298): select_devices: usecase(normal)
V/audio_hw_primary(  298): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  298): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  298): get_INPUT_snd_device: check by Input_source(6)
V/msm8974_platform(  298): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  298): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  298): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  298): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  298): select_devices: in_snd_device(122: vr-main-mic)
D/ACDB-LOADER(  298): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  298): ACDB -> send_adm_topology
D/ACDB-LOADER(  298): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  298): ACDB -> send_asm_topology
D/ACDB-LOADER(  298): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  298): ACDB -> send_audtable
D/ACDB-LOADER(  298): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/        (  298): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/ACDB-LOADER(  298): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  298): ACDB -> send_audvoltable
D/ACDB-LOADER(  298): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  298): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/        (  298): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  298): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  298): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  298): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  298): enable_snd_device: snd_device(122: vr-main-mic, vr-main-mic)
D/audio_route(  298): ++++ audio_route_update_mixer ==============
D/audio_route(  298): Setting mixer control: DEC2 Volume
D/audio_route(  298): Setting mixer control: value: 106
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  868): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/audio_route(  298): Setting mixer control: SLIM TX7 MUX, value: 9
,D/audio_route(  298): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  298): Setting mixer control: value: 1
,D/audio_route(  298): Setting mixer control: DEC2 MUX, value: 1
,D/audio_route(  298): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  298): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  298): enable_audio_route: apply mixer path: audio-record
D/audio_route(  298): ++++ audio_route_update_mixer ==============
D/audio_route(  298): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  298): Setting mixer control: value: 1
,D/audio_route(  298): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  298): enable_audio_route: exit
V/audio_hw_primary(  298): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,I/SystemBroadcastReceiver( 7363): [#DCM#] [DCM_Performance] onReceive completed in time  650 microsec. 
V/audio_hw_primary(  298): start_input_stream: exit
,D/ConnectivityService(  868): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7363): [#DCM#] Calling notifyListeners. 
I/art     (  868): Explicit concurrent mark sweep GC freed 41894(2MB) AllocSpace objects, 5(80KB) LOS objects, 30% free, 35MB/51MB, paused 7.025ms total 190.353ms
I/NetworkMonitor( 7325): type=WIFI subType= reason=null isConnected=false
,D/WallpaperManagerService(  868):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler(  868): handleActiveUserChange for user 0
,D/ResourcesManager(  868): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/NtpTrustedTime(  868): currentTimeMillis() cache hit
D/NtpTrustedTime(  868): currentTimeMillis() cache hit
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/art     (  868): WaitForGcToComplete blocked for 159.356ms for cause Explicit
,D/StatusBarManagerService(  868): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/DCMController( 7363): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 7363): [#DCM#] setIsConnectedForExtractors 
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/daemonapp( 1338): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
I/Timeline( 1487): Timeline: Activity_idle id: android.os.BinderProxy@255afcd7 time:86901
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/DBG_DM  ( 3770): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  868): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  868): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/WifiStateMachine(  868): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,E/WifiStateMachine(  868): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  868): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/accuweather( 2204): [KK AccuPhone]>>> RM:150 [0:0]  onFirstUpdate :: mFU = false
,D/accuweather( 2204): [KK AccuPhone]>>> SWW:223 [0:0]  onResume :: isFirst = false, cnt = 0
D/accuweather( 2204): [KK AccuPhone]>>> SWW:230 [0:0] onResume : size = 1
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/accuweather( 2204): [KK AccuPhone]>>> SWW:512 [0:0]  registerTTReceiver ! 
,D/BluetoothAdapterApp( 7973): Load D/L JNI Library
,I/BluetoothA2dpSinkServiceJni( 7973): register_com_android_bluetooth_a2dp_sink
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/BluetoothAdapterApp( 7973): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@e6f7d31 Instance Count = 1
,D/ConnectivityService(  868): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3770): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/accuweather( 2204): [KK AccuPhone]>>> WR:139 [0:0] onResume orientation = 1, from res = Port fHD
,D/accuweather( 2204): [KK AccuPhone]>>> SM:523 [0:0] onResume : false, rsStep = 2
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/daemonapp( 1338): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/HotwordWorker( 1579): onReady
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/BluetoothAdapterApp( 7973): onCreate
,D/BtSettings.ProfileConfig( 7973): Adding GattService
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/SecContentProvider2(  868): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  868): mCursor = null
,E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
,D/BtSettings.ProfileConfig( 7973): Adding HeadsetService
D/BtSettings.ProfileConfig( 7973): Adding A2dpService
D/BtSettings.ProfileConfig( 7973): Adding HidService
,D/BtSettings.ProfileConfig( 7973): Adding HealthService
D/BtSettings.ProfileConfig( 7973): Adding PanService
D/BtSettings.ProfileConfig( 7973): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 7973): Adding SapService
,D/BtSettings.ProfileConfig( 7973): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 7973): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 7973): Adding SapClientService
D/BtSettings.ProfileConfig( 7973): Adding HidDevService
,I/BtSettings.ProfileConfig( 7973): *********Initializing Bluetooth Profile Settings*******
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,E/Zygote  ( 8000): MountEmulatedStorage()
E/Zygote  ( 8000): v2
I/libpersona( 8000): KNOX_SDCARD checking this for 10070
I/libpersona( 8000): KNOX_SDCARD not a persona
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/ActivityManager(  868): Start proc com.sec.android.widgetapp.ap.hero.accuweather for content provider com.sec.android.widgetapp.ap.hero.accuweather/.provider.accuweather.AccuContentProvider: pid=8000 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/SELinux ( 8000): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,I/SELinux ( 8000): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ResourcesManager(  868): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,E/SELinux ( 8000): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RegisteredServicesCache( 1467): empty dynamic service
,D/SettingsProvider(  868): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider(  868): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  868): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  868): selectionArgs: false
D/SettingsProvider(  868): selectionArgs: 1002
D/SecContentProvider(  868): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  868): ret = -1
,D/SettingsProvider(  868): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,D/SettingsProvider(  868): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  868): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  868): selectionArgs: false
D/SettingsProvider(  868): selectionArgs: 1002
D/SecContentProvider(  868): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  868): ret = -1
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/SettingsProvider(  868): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider(  868): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  868): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  868): selectionArgs: false
D/SettingsProvider(  868): selectionArgs: 1002
D/SecContentProvider(  868): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  868): ret = -1
,D/SettingsProvider(  868): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider(  868): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  868): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  868): selectionArgs: false
D/SettingsProvider(  868): selectionArgs: 1002
D/SecContentProvider(  868): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  868): ret = -1
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/LightSensor(  868): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/SettingsProvider(  868): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider(  868): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  868): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  868): selectionArgs: false
D/SettingsProvider(  868): selectionArgs: 1002
D/SecContentProvider(  868): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  868): ret = -1
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SettingsProvider(  868): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider(  868): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  868): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  868): selectionArgs: false
D/SettingsProvider(  868): selectionArgs: 1002
D/SecContentProvider(  868): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  868): ret = -1
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/SettingsProvider(  868): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/TimaKeyStoreProvider( 8000): TimaSignature is unavailable
,D/CustomFrequencyManagerService(  868): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 868  tag : ACTIVITY_RESUME_BOOSTER@6
D/SettingsProvider(  868): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  868): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  868): selectionArgs: false
D/ActivityThread( 8000): Added TimaKeyStore provider
D/SettingsProvider(  868): selectionArgs: 1002
,D/SecContentProvider(  868): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  868): ret = -1
,W/ActivityManager(  868): mDVFSHelper.release()
D/SettingsProvider(  868): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/CustomFrequencyManagerService(  868): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 868  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/SettingsProvider(  868): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  868): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  868): selectionArgs: false
D/SettingsProvider(  868): selectionArgs: 1002
D/SecContentProvider(  868): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  868): ret = -1
,D/SettingsProvider(  868): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider(  868): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  868): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  868): selectionArgs: false
D/SettingsProvider(  868): selectionArgs: 1002
D/SecContentProvider(  868): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  868): ret = -1
,D/SettingsProvider(  868): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,D/SettingsProvider(  868): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  868): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  868): selectionArgs: false
D/SettingsProvider(  868): selectionArgs: 1002
D/SecContentProvider(  868): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  868): ret = -1
,D/SettingsProvider(  868): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider(  868): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  868): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  868): selectionArgs: false
D/SettingsProvider(  868): selectionArgs: 1002
D/SecContentProvider(  868): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  868): ret = -1
,D/SettingsProvider(  868): name = bt_svcst_com.android.bluetooth.hid.HidDevService
,D/SettingsProvider(  868): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  868): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  868): selectionArgs: false
D/SettingsProvider(  868): selectionArgs: 1002
D/ResourcesManager(  868): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/SecContentProvider(  868): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  868): ret = -1
D/ResourcesManager( 8000): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
D/BluetoothAdapterApp( 7973): checkSWUpdate
,D/BluetoothAdapterApp( 7973): sw version in prop is 1431675920
,W/ResourcesManager( 8000): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8000): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8000): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/BluetoothAdapterApp( 7973): sw version in file is 1431675920
,D/BluetoothAdapterApp( 7973): sw version is same
,I/ActivityManager(  868): Killing 6845:com.vlingo.midas/u0a32 (adj 15): bgCount ##41
,D/AuthorizationBluetoothService( 2104): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
E/Zygote  ( 8016): MountEmulatedStorage()
E/Zygote  ( 8016): v2
I/libpersona( 8016): KNOX_SDCARD checking this for 10018
I/libpersona( 8016): KNOX_SDCARD not a persona
,D/RCPManagerService(  868): PackageReceiver onReceive()
I/HarmonyEASService(  868): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/ActivityManager(  868): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8016 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,D/KnoxMUMContainerPolicy(  868): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/BackupManagerService(  868): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  868): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  868): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  868): uID is 10357
V/EnterpriseBillingPolicy(  868): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  868): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  868): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  868): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  868): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  868): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  868): getBillingProfileForVpnEngine - end - null
,D/TaskPersister(  868): removeObsoleteFile: deleting file=3_task.xml
D/SmartBondingService(  868): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation(  868): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/Tethering(  868): MasterInitialState.processMessage what=3
D/SmartBondingService(  868): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  868): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  868): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  868): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  868): CLoinfo wifi false
,W/SLocation(  868): No Active Data Connection
,I/SELinux ( 8016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/SELinux ( 8016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ApplicationPolicy(  868): updateDataUsageMap
E/SELinux ( 8016): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 1487): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_mic.png
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/EnterpriseDeviceManagerService(  868): Package has changed for user 0
D/EnterpriseDeviceManagerService(  868): Admin package name: com.google.android.gms
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/comsamsunglog( 8000): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 8000): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 8000): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 8000): [KK AccuPhone]>>> ==============================================================================================
,D/SmartBondingService(  868): getNetworkEnabled : wifi : false mobile : true
,D/SmartBondingService(  868): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  868): getSBEnabled() enabled =false
D/SmartBondingService(  868): getSBEnabled() enabled =false
,D/SmartBondingService(  868): getSBEnabled() enabled =false
,D/SmartBondingService(  868): getNetworkEnabled : wifi : false mobile : true
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/Timeline(  868): Timeline: Activity_windows_visible id: ActivityRecord{33ac5ca8 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:87161
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/comsamsunglog( 8000): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 8000): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 8000): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 8000): [KK AccuPhone]>>> ==============================================================================================
,D/TimaKeyStoreProvider( 8016): TimaSignature is unavailable
W/libprocessgroup(  868): failed to open /acct/uid_10032/pid_6845/cgroup.procs: No such file or directory
,D/ActivityThread( 8016): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/SettingsProvider(  868): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  868): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  868): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  868): selectionArgs: false
D/SettingsProvider(  868): selectionArgs: 10070
D/SecContentProvider(  868): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  868): ret = -1
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/daemonapp( 1338): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/ResourcesManager(  868): creating new AssetManager and set to /system/app/Books/Books.apk
,I/art     (  868): Explicit concurrent mark sweep GC freed 17110(1064KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 35MB/51MB, paused 6.561ms total 319.259ms
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,E/LightSensor(  868): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/daemonapp( 1338): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/ResourcesManager( 8016): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/accuweather( 2204): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/daemonapp( 1338): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/accuweather( 2204): [KK AccuPhone]>>> SM:442 [0:0] updateView iSA = false, mCI = 0, mSL = null , cls = 0 , cls = 1
,D/accuweather( 2204): [KK AccuPhone]>>> SM:447 [0:0] bg transparency val = 0
,D/accuweather( 2204): [KK AccuPhone]>>> SM:679 [0:0] [sCCTZ] set default tZ
,D/accuweather( 2204): [KK AccuPhone]>>> SM:1044 [0:0] setLayoutContentEmptyMsg = 2131558522
,D/accuweather( 2204): [KK AccuPhone]>>> U:1012 [0:0] icon = 99, isDay = true, type = 261
D/accuweather( 2204): [KK AccuPhone]>>> U:1187 [0:0] resID = 2130837848
,D/accuweather( 2204): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/KLMS-2.4.503: ( 8016): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 8016): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450199100612
,I/KLMS-2.4.503: ( 8016): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 8016): MainReciver(): REPLACING: false | pkgName: com.example.hello
,D/PackageManager(  868): delete codoeFile: 
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/SurfaceWidget.Renderer( 2204): [237392/6] SurfaceWidget drawing first frame
,D/accuweather( 2204): [KK AccuPhone]>>> SM:1072 [0:0] complete setLayoutContentEmptyMsg Content
D/PackageManager(  868): result of delete: 1{259107557}
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/AndroidRuntime( 7937): Shutting down VM
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/accuweather( 2204): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/ActivityManager(  868): Killing 6824:com.sec.android.automotive.drivelink/u0a98 (adj 15): bgCount ##41
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/SurfaceWidget.Renderer( 2204): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2204): [237392/6] SurfaceWidget drawing first frame
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/CustomFrequencyManagerService(  868): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 868  tag : ACTIVITY_RESUME_BOOSTER@10
D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  868): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager(  868): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  868): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  868): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  868): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,E/Zygote  ( 8033): MountEmulatedStorage()
I/libpersona( 8033): KNOX_SDCARD checking this for 10103
E/Zygote  ( 8033): v2
I/libpersona( 8033): KNOX_SDCARD not a persona
,I/ActivityManager(  868): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8033 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  868): Killing 6878:com.sec.android.provider.logsprovider/u0a19 (adj 15): bgCount ##41
,D/ResourcesManager(  868): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,E/LightSensor(  868): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  868): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  868): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 8033): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  868): failed to open /acct/uid_10098/pid_6824/cgroup.procs: No such file or directory
,I/SELinux ( 8033): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8033): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UsbSettingsManager(  868): clearDefaults: com.example.hello
,I/CrashAnrDetector(  868): onPackageRemoved : com.example.hello
,D/ConnectivityService(  868): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 8033): TimaSignature is unavailable
,D/ActivityThread( 8033): Added TimaKeyStore provider
,W/libprocessgroup(  868): failed to open /acct/uid_10019/pid_6878/cgroup.procs: No such file or directory
D/ResourcesManager( 8033): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/elm:14451( 8033): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8033): ELMEngine.ELMEngine( context ).
D/elm:14451( 8033): MDMBridge.setEnterpriseBridge()
,D/elm:14451( 8033): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
,D/elm:14451( 8033): ElmAgentService : onCreate()
,D/elm:14451( 8033): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8033): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8033): MDMBridge.getInstance()
,D/elm:14451( 8033): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14451( 8033): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 8049): MountEmulatedStorage()
E/Zygote  ( 8049): v2
I/libpersona( 8049): KNOX_SDCARD checking this for 10016
I/libpersona( 8049): KNOX_SDCARD not a persona
,I/ActivityManager(  868): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8049 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,I/SELinux ( 8049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/elm:14451( 8033): ElmAgentService : onDestroy().
,I/SELinux ( 8049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8049): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  868): Killing 6889:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 8049): TimaSignature is unavailable
,D/ActivityThread( 8049): Added TimaKeyStore provider
,D/ResourcesManager( 8049): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8049): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8049): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8049): onReceive() : package name is not s health. Return !!!
,E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  868): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  868): failed to open /acct/uid_10003/pid_6889/cgroup.procs: No such file or directory
,E/Zygote  ( 8065): MountEmulatedStorage()
,E/Zygote  ( 8065): v2
I/libpersona( 8065): KNOX_SDCARD checking this for 1000
I/libpersona( 8065): KNOX_SDCARD not a persona
,I/ActivityManager(  868): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8065 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  868): Killing 6913:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/SELinux ( 8065): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8065): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8065): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LightSensor(  868): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  868): mCallbacks.updateBrightness()
D/DisplayPowerController(  868): getFinalBrightness : 8 -> 8
,W/libprocessgroup(  868): failed to open /acct/uid_1000/pid_6913/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8065): TimaSignature is unavailable
,D/ActivityThread( 8065): Added TimaKeyStore provider
,D/ResourcesManager( 8065): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 8065): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8065): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8065): new DMDBOpenHelper instance
,E/SQLiteDatabase( 8065): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase( 8065): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8065): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 8065): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8065): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase( 8065): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 8065): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 8065): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/SQLiteDatabase( 8065): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/SQLiteDatabase( 8065): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/SQLiteDatabase( 8065): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8065): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/SQLiteDatabase( 8065): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8065): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 8065): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/SQLiteDatabase( 8065): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8065): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8065): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 8065): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 8065): Shutting down VM
,E/AndroidRuntime( 8065): FATAL EXCEPTION: main
E/AndroidRuntime( 8065): Process: com.sec.pcw.device, PID: 8065
E/AndroidRuntime( 8065): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8065): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5456)
E/AndroidRuntime( 8065): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/AndroidRuntime( 8065): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/AndroidRuntime( 8065): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8065): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8065): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8065): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8065): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8065): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8065): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8065): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8065): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8065): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8065): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/AndroidRuntime( 8065): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8065): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime( 8065): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 8065): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 8065): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/AndroidRuntime( 8065): 	... 11 more
,V/ApplicationPolicy(  868): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,E/DropBoxManagerService(  868): Can't write: system_app_crash
E/DropBoxManagerService(  868): java.io.FileNotFoundException: /data/system/dropbox/drop183.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  868): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  868): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  868): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  868): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  868): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  868): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:14540)
E/DropBoxManagerService(  868): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  868): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  868): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  868): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  868): 	... 5 more
,D/ResourcesManager(  868): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/StatusBarManagerService(  868): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/EventHub(  868): Removing device '/dev/input/event4' due to inotify event
,F/libc    ( 6599): Fatal signal 7 (SIGBUS), code 2, fault addr 0x774ce6ef in tid 6599 (pp.galaxyfinder)
,E/audit_log( 2026): File locking failed. error= Bad file number
,F/libc    ( 6599): Failed while talking to debuggerd: Broken pipe
E/audit_log( 2026): File locking failed. error= Bad file number
,I/ActivityManager(  868): Process com.samsung.android.app.galaxyfinder (pid 6599)(adj 9) has died(150,601)
,I/EventHub(  868): Removing device '/dev/input/event5' due to inotify event
,I/Zygote  (  317): Process 6599 exited due to signal (7)
,I/EventHub(  868): Removing device '/dev/input/event6' due to inotify event
,I/EventHub(  868): Removing device '/dev/input/event7' due to inotify event
,I/EventHub(  868): Removing device '/dev/input/event8' due to inotify event
,I/EventHub(  868): Removing device '/dev/input/event9' due to inotify event
,I/EventHub(  868): Removing device '/dev/input/event10' due to inotify event
,I/EventHub(  868): Removing device '/dev/input/event11' due to inotify event
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,E/android.os.Debug(  868): !@Dumpstate > dumpstate -k -t -z -d -o /data/log/dumpstate_app_error
,E/audit_log( 2026): File locking failed. error= Bad file number

```
