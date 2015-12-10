#### Test 5065027881383b1_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
I/SELinux ( 7411): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7411): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7411): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
--------- beginning of system
I/ActivityManager(  884): Killing 6100:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
D/TimaKeyStoreProvider( 7411): TimaSignature is unavailable
D/ActivityThread( 7411): Added TimaKeyStore provider
D/ResourcesManager( 7411): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager( 7411): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7411): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/libprocessgroup(  884): failed to open /acct/uid_10167/pid_6100/cgroup.procs: No such file or directory
D/MyFiles ( 7411): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,D/InputManager-JNI(  884): setDeviceInteractive: 0
D/PowerManagerService(  884): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  884): Nap time (uid 1000)...
I/PowerManagerService(  884): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  884): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  884): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  884): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService(  884): handleSandman : startDream()
D/InputManager-JNI(  884): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/InputManager-JNI(  884): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI(  884): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI(  884): sysfs_write -: /sys/class/input/event2/device/enabled: 0
D/SContextService(  884): 	.unregisterCallback : 1, client=
D/SContextService(  884): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@37dc32ec, Service = Auto Rotation, used = 1
W/CAE     (  884): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
V/CAE     (  884): stop(ContextProvider.java:149)
E/PowerManagerService(  884): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  884): Sleeping (uid 1000)...
D/PowerManagerService(  884): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  884): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  884): [input device light] handleInputDeviceLightOff
I/SurfaceFlinger(  257): id=15 createSurf (1080x1920),2 flag=404, ColorFade
V/CAE     (  884): clear(AutoRotationRunner.java:182)
V/CAE     (  884): disable(AutoRotationRunner.java:171)
I/CAE     (  884): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  884): SendSensorHubData: send data = -78, 7, 0, 0
D/Sensorhubs(  305): sendContextData: -78, 7, 0, 0
D/CAE     (  884): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  884): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
I/TactileAssist(  884): enable value -1
I/TactileAssist(  884): internal enable value -1
I/TactileAssist(  884): intensity value -1
I/TactileAssist(  884): saveAppList value true
I/TactileAssist(  884): List of disabled apps :
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
I/Icing   ( 2424): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7432): MountEmulatedStorage()
E/Zygote  ( 7432): v2
I/libpersona( 7432): KNOX_SDCARD checking this for 10057
I/libpersona( 7432): KNOX_SDCARD not a persona
I/ActivityManager(  884): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7432 uid=10057 gids={50057, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 7432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7432): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7432): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/Icing   ( 2424): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
D/CAE     (  884): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
I/CAE     (  884): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  884): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  884): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  884): removeSContextService() : service = Auto Rotation
D/SContextService(  884): ===== SContext Service List =====
D/SContextManager(  884):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@14fd168d, service=Auto Rotation
D/KeyguardViewMediator( 1182): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1182): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1182): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1182): notifyScreenOffLocked
I/DBG_DM  ( 3749): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
D/TimaKeyStoreProvider( 7432): TimaSignature is unavailable
D/ActivityThread( 7432): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/KeyguardViewMediator( 1182): timeout : 5000
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/DisplayPowerController(  884): ColorFade: onAnimationStart
D/DisplayPowerController(  884): getFinalBrightness : 24 -> 0
I/SQLiteSecureOpenHelper( 3526): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3526): getDatabaseLocked(b,b,pwd)...
D/lights  (  884): lcd : 11 +
D/lights  (  884): lcd : 11 -
D/lights  (  884): lcd : 3 +
D/lights  (  884): lcd : 3 -
D/lights  (  884): lcd : 0 +
D/DisplayPowerController(  884): getFinalBrightness : 24 -> 0
E/installd(  302): system dir 0 : /system/app/
E/installd(  302): system dir 1 : /system/priv-app/
E/installd(  302): system dir 2 : /vendor/app/
E/installd(  302): system dir 3 : /oem/app/
D/KeyguardViewMediator( 1182): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1182): handleNotifyScreenOff
D/lights  (  884): lcd : 0 -
D/LightsService(  884): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 884) 
D/LightsService(  884): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/ResourcesManager( 7432): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
D/LightsService(  884): [SvcLED]  onSensorChanged::light value = 12
W/ResourcesManager( 7432): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/SensorManager(  884): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  884): unregisterListener ::   
D/lights  (  884): led_pattern : 5 +
D/BatteryService(  884): turn on LED for fully charged
D/lights  (  884): led_pattern : 5 -
D/LightsService(  884): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/CAE     (  884): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     (  884): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  884): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  884): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  305): sendContextData: -76, 13, -46, 0
D/PackageManager(  884): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
I/CAE     (  884): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 13, 9, 52,
D/SensorHubManager(  884): SendSensorHubData: send data = -63, 14, 13, 9, 52
D/Sensorhubs(  305): sendContextData: -63, 14, 13, 9, 52
D/MotionRecognitionService(  884):   mReceiver.onReceive : ACTION_SCREEN_OFF
E/MotionRecognitionService(  884):  handler : SCREEN_OFF end 
D/Compatibility( 7432): onReceive() it will make start service
D/WifiStateMachine(  884): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  884): handleScreenStateChanged Exit: false
E/WifiStateMachine(  884): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/WifiStateMachine(  884): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  884): do suspend true
D/Compatibility( 7432): onHandleIntent()
D/NotificationService(  884): ACTION_SCREEN_OFF
D/Compatibility( 7432): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10356, android.intent.extra.user_handle=0}]
D/Compatibility( 7432): found: 2
D/LightsService(  884): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 884) 
D/LightsService(  884): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService(  884): [SvcLED]  onSensorChanged::light value = 12
D/Compatibility( 7432): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7432): skipping ResolveInfo{1ce7e7b7 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7432): considering ResolveInfo{25e19b24 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7432): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/SensorManager(  884): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/Compatibility( 7432): enabling receiver ResolveInfo{2c368d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/SensorManager(  884): unregisterListener ::   
D/LightsService(  884): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/UpdateIcingCorporaServi( 1568): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 7432): enabling receiver ResolveInfo{9806042 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
D/Compatibility( 7432): enabling receiver ResolveInfo{1e094853 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7432): enabling receiver ResolveInfo{212f4590 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/AndroidRuntime( 7438): 
D/AndroidRuntime( 7438): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/Compatibility( 7432): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/AndroidRuntime( 7438): CheckJNI is OFF
D/AndroidRuntime( 7438): setted country_code = Poland
I/ActivityManager(  884): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7463 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/AndroidRuntime( 7438): setted countryiso_code = PL
E/Zygote  ( 7463): MountEmulatedStorage()
I/libpersona( 7463): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7463): v2
I/libpersona( 7463): KNOX_SDCARD not a persona
D/AndroidRuntime( 7438): setted sales_code = XEO
D/AndroidRuntime( 7438): readGMSProperty: start
D/AndroidRuntime( 7438): readGMSProperty: already setted!!
D/AndroidRuntime( 7438): readGMSProperty: end
D/AndroidRuntime( 7438): addProductProperty: start
I/SELinux ( 7463): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7463): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7463): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/audio_hw_primary(  299): adev_set_parameters: enter: screen_state=off
V/voice   (  299): voice_set_parameters: enter: screen_state=off
V/voice   (  299): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  299): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  299): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  299): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  299): adev_set_parameters: exit
I/ActivityManager(  884): Killing 6051:com.google.android.gm/u0a113 (adj 15): bgCount ##41
I/SecExternalDisplayIntents_Java(  884): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
D/IpRemoteDisplayController(  884): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  884): Bridge Server is not available
D/VolumePanel( 1182): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1182): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1182): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1182): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/TimaKeyStoreProvider( 7463): TimaSignature is unavailable
D/ResourcesManager( 1568): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/ActivityThread( 7463): Added TimaKeyStore provider
D/DisplayPowerState(  884): !@ ColorFade entry
D/DisplayPowerController(  884): ColorFade: onAnimationEnd
D/PersonaManagerService(  884): ACTION_SCREEN_OFF onReceive
D/AutomaticBrightnessController(  884): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  884): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  884): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController(  884): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  884): Light old sensor_state 513, new sensor_state : 1 en : 0
D/SensorManager(  884): unregisterListener ::   
D/PersonaManagerServiceHandler(  884): MSG_ACTION_SCREEN_OFF called
E/Sensors (  884): Acc old sensor_state 1, new sensor_state : 0 en : 0
D/SensorManager(  884): unregisterListener ::   
D/NfcService( 1464): call the applyRotuiing
D/ResourcesManager( 7463): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
D/DisplayPowerController(  884): getFinalBrightness : 0 -> 0
D/DisplayPowerController(  884): getFinalBrightness : 0 -> 0
I/UpdateIcingCorporaServi( 1568): UpdateCorporaTask done [took 117 ms] updated apps [took 116 ms] 
I/DisplayManagerService(  884): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  884): Display changed displayId=0
D/STATUSBAR-PhoneStatusBar( 1182):      ACTION_SCREEN_OFF is finished!!!! 
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  257): hwc_blank: Blanking display: 0
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
E/AffinityControl( 7438): AffinityControl: registerfunction enter
W/libprocessgroup(  884): failed to open /acct/uid_10113/pid_6051/cgroup.procs: No such file or directory
E/StatusBar( 1182): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1182): dismissHelpPopup 
D/accuweather( 2058): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2058): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/accuweather( 2058): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/StatusBar.NetworkController( 1182): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/AndroidRuntime( 7438): Calling main entry com.android.commands.am.Am
W/ContextImpl( 7463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/PersonaManagerService(  884): inState():  stateMachine is null !!
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
V/ApplicationPolicy(  884): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  884): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  884): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  884): mDVFSHelper.acquire()
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7488): MountEmulatedStorage()
E/Zygote  ( 7488): v2
I/libpersona( 7488): KNOX_SDCARD checking this for 10356
I/libpersona( 7488): KNOX_SDCARD not a persona
D/SSRM:m  (  884): SIOP:: AP = 370, PST = 371, CUR = 450
I/ActivityManager(  884): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7488 uid=10356 gids={50356, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7488): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7488): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7488): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/AndroidRuntime( 7438): Shutting down VM
I/SystemBroadcastReceiver( 6356): [#DCM#] [DCM_Performance] onReceive completed in time  330 microsec. 
I/rmt_storage(  281): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
I/SystemBroadcastReceiver( 6356): [#DCM#] Calling notifyListeners. 
I/rmt_storage(  281): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  281): wakelock acquired: 1, error no: 42
I/DCMPolicyManager( 6356): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 6356): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
I/rmt_storage(  281): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229454592)
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/TimaKeyStoreProvider( 7488): TimaSignature is unavailable
D/LockPatternUtilsCache( 1182): value : false
D/ActivityThread( 7488): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/SQLiteSecureOpenHelper( 3526): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3526): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ResourcesManager( 7488): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  884): getTasks: caller 10085 does not hold GET_TASKS; limiting output
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7504): MountEmulatedStorage()
E/Zygote  ( 7504): v2
I/libpersona( 7504): KNOX_SDCARD checking this for 10097
I/libpersona( 7504): KNOX_SDCARD not a persona
I/ActivityManager(  884): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7504 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/ActivityManager(  884): Killing 6356:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
W/ActivityManager(  884): getTasks: caller 10085 does not hold GET_TASKS; limiting output
I/rmt_storage(  281): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  281): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  281): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229454592) wakelock released: 1, error no: 22
I/rmt_storage(  281): 
I/rmt_storage(  281): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
I/SELinux ( 7504): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7504): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7504): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/PowerManagerService(  884): [PWL] sb release: PowerManagerService.Broadcasts
D/TimaKeyStoreProvider( 7504): TimaSignature is unavailable
D/ActivityThread( 7504): Added TimaKeyStore provider
W/libprocessgroup(  884): failed to open /acct/uid_10004/pid_6356/cgroup.procs: No such file or directory
D/ResourcesManager( 7504): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/qdhwcomposer(  257): hwc_blank: Done blanking display: 0
I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  884): Excessive delay in setPowerMode(): 252ms
D/PowerManagerService(  884): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  884): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  884): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/QCOM PowerHAL(  884): Got set_interactive hint
I/PowerManagerService(  884): [PWL] Off : 0s ago
I/PowerManagerService(  884): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  884): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  884): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=884, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=985)
I/PowerManagerService(  884): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  884): [PWL]     mDisplayReady : false
D/DisplayPowerController(  884): getFinalBrightness : 0 -> 0
D/PowerManagerService(  884): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  884): [PWL] sb release: PowerManagerService.Display
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/WebViewFactory( 7488): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7488): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7488): Loading: webviewchromium
I/LibraryLoader( 7488): Time to load native libraries: 2 ms (timestamps 7313-7315)
I/LibraryLoader( 7488): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7488): Binding Chromium to main looper Looper (main, tid 1) {1e094853}
I/LibraryLoader( 7488): Expected native library version number "",actual native library version number ""
I/chromium( 7488): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/DocsApplication( 7504): Installing DEX configuration.
I/BrowserStartupController( 7488): Initializing chromium process, renderers=0
W/art     ( 7488): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7488): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7488): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7488): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/DexInstaller( 7504): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7504): Provided clientMode=RELEASE, packageInfo=PackageInfo{1aea0eb6 com.google.android.apps.docs}
I/Adreno-EGL( 7488): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7488): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7488): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7488): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7488): Remote Branch: 
I/Adreno-EGL( 7488): Local Patches: 
I/Adreno-EGL( 7488): Reconstruct Branch: 
D/TAG     ( 7504): onCreate()
D/CrossAppStateProvider( 7504): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
W/chromium( 7488): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7488): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7488): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7488): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7488): CordovaWebView is running on device made by: samsung
W/art     ( 7488): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7488): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 7488): performCreate Call secproduct feature valuefalse
D/Activity( 7488): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7488): Render dirty regions requested: true
D/ActivityManager(  884): post active user change for 0
D/KnoxTimeoutHandler(  884): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  884): handleActiveUserChange for user 0
I/SurfaceFlinger(  257): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/StatusBarManagerService(  884): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/StatusBarManagerService(  884): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/OpenGLRenderer( 7488): Initialized EGL, version 1.4
I/OpenGLRenderer( 7488): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7488): Enabling debug mode 0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/InputMethodManagerService(  884): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
W/ContextImpl(  884): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
W/ContextImpl(  884): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
W/ActivityManager(  884): mDVFSHelper.release()
I/Timeline(  884): Timeline: Activity_windows_visible id: ActivityRecord{3416bc20 u0 com.test.thalitest/.MainActivity t4} time:107673
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
W/IInputConnectionWrapper( 7488): showStatusIcon on inactive InputConnection
I/Timeline( 7488): Timeline: Activity_idle id: android.os.BinderProxy@1b755df2 time:107687
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/Atfwd_Sendcmd(  342): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  342): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
D/JsMessageQueue( 7488): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 7488): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7488): 
D/jxcore_app_log( 7488): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358601216
D/JX-Cordova( 7488): jxcore cordova android initializing
D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
W/GAV2    ( 7504): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/Zygote  ( 7577): MountEmulatedStorage()
E/Zygote  ( 7577): v2
I/libpersona( 7577): KNOX_SDCARD checking this for 10098
I/libpersona( 7577): KNOX_SDCARD not a persona
I/ActivityManager(  884): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7577 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
I/SELinux ( 7577): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7577): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7577): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7577): TimaSignature is unavailable
D/ActivityThread( 7577): Added TimaKeyStore provider
D/ResourcesManager( 7577): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
W/ResourcesManager( 7577): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/[CarMode]( 7577): [DLApplication]-onCreate: Applicatino Started!
D/SampleAppCoreManager( 7577): SampleAppCoreManager VACVersion '2.2.0.11867'
I/VlingoAndroidCore( 7577): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7603): MountEmulatedStorage()
E/Zygote  ( 7603): v2
I/libpersona( 7603): KNOX_SDCARD checking this for 10032
I/libpersona( 7603): KNOX_SDCARD not a persona
I/ActivityManager(  884): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7603 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 7603): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7603): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7603): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7603): TimaSignature is unavailable
D/ActivityThread( 7603): Added TimaKeyStore provider
D/ResourcesManager( 7603): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/ResourcesManager( 7603): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/System.out( 7603): Inside onCreate() of WakeupTriggerProvide
I/System.out( 7603): Inside WakeupProvider
W/GAV2    ( 7504): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  884): Killing 5750:com.sec.android.app.samsungapps/u0a39 (adj 15): bgCount ##41
E/DatabaseUtils( 7603): Writing exception to parcel
E/DatabaseUtils( 7603): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7603): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7603): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7603): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7603): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7603): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7603): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7603): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7603): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7603): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7603): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7577): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
I/VlingoApplication( 7603): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
W/System.err( 7577): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7577): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7577): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7577): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7577): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7577): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7577): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7577): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7577): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7577): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7577): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7577): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7577): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7577): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7577): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7577): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7577): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7577): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7577): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7577): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7577): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7577): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7577): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7577): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7577): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7577): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7577): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7577): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7577): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7577): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7577): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/DatabaseUtils( 7603): Writing exception to parcel
E/DatabaseUtils( 7603): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7603): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7603): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7603): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7603): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7603): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7603): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7603): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7603): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7603): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7603): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7577): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
I/VlingoAndroidCore( 7603): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
W/System.err( 7577): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7577): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7577): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7577): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7577): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7577): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7577): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7577): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7577): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7577): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7577): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7577): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7577): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7577): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7577): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 7577): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7577): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7577): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7577): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7577): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7577): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7577): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7577): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7577): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7577): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7577): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7577): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7577): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 7577): [DLApplication]-Init Called!:false
E/[CarMode]( 7577): [DLApplication]-Init Started!:true
I/[CarModeFW]( 7577): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7577): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7577): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7577): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7577): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7577): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7577): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7577): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7577): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7577): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7577): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7577): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7577): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7577): ### com.android.internal.os.ZygoteInit::main(1194)
W/libprocessgroup(  884): failed to open /acct/uid_10039/pid_5750/cgroup.procs: No such file or directory
I/MessageDataHandler( 7577): initialize
D/[CarModeFW]( 7577): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 7577): CDH-initiazlieCaches : after sync
D/[CarModeFW]( 7577): DrivingManager-initialize...
D/[CarModeFW]( 7577): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7577): CDH-ContactDataHandler initiazlieCaches time : 15
D/[CarModeFW]( 7577): CDH-initiazlieCaches : end sync
I/SensorService(  884): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  884): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  884): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
D/VlingoApplication( 7603): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 7603): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
I/MediaPlayer( 7577): Need to enable context aware info
V/MediaPlayer-JNI( 7577): native_setup
V/MediaPlayer( 7577): constructor
V/MediaPlayer( 7577): setListener
E/MediaPlayer-JNI( 7577): QCMediaPlayer mediaplayer NOT present
D/[CarModeFW]( 7577): PushMessageManager-bindPushMessageService
I/[CarModeFW]( 7577): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode]( 7577): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarModeFW]( 7577): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1449752994969
D/[CarModeFW]( 7577): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1449752994969
D/[CarMode]( 7577): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 7577): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1449752994973
D/[CarModeFW]( 7577): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1449752994973
D/[CarModeFW]( 7577): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1449752994974
D/[CarModeFW]( 7577): CDH-buildContactCacheWireFrame : cur len =0
I/[CarMode]( 7577): [LogNotNull]-Package name is: com.google.android.apps.maps
D/[CarModeFW]( 7577): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1449752994979
D/TP/SmsProvider( 1473): query,matched:2, calling pid = 7577
D/TP/SmsProvider( 1473): query,matched:2, calling pid = 7577
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 1473): match 2:Elapsed time : 2.326 ms
D/TP/SmsProvider( 1473): match 2:Elapsed time : 4.053 ms
E/Zygote  ( 7636): MountEmulatedStorage()
E/Zygote  ( 7636): v2
I/libpersona( 7636): KNOX_SDCARD checking this for 10003
I/libpersona( 7636): KNOX_SDCARD not a persona
I/ActivityManager(  884): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7636 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
E/[CarMode]( 7577): [DLApplication]-Init End!:true
,I/SELinux ( 7636): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
I/SELinux ( 7636): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/SELinux ( 7636): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7643): MountEmulatedStorage()
E/Zygote  ( 7643): v2
I/libpersona( 7643): KNOX_SDCARD checking this for 10019
I/libpersona( 7643): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7643 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,I/SELinux ( 7643): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7643): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/TimaKeyStoreProvider( 7636): TimaSignature is unavailable
,D/MessageDataHandler( 7577):  getInboxList smsCursor : 152
E/SELinux ( 7643): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/ActivityThread( 7636): Added TimaKeyStore provider
,D/TP/MmsProvider( 1473): Query uri=content://mms, match=0, calling pid = 7577
,D/TP/MmsProvider( 1473): Query uri=content://mms/inbox, match=2, calling pid = 7577
,D/[CarModeFW]( 7577): CDH-buildContactCacheWireFrame : cur len =0
,D/MessageDataHandler( 7577):  getInboxList mmsCursor : 10
,I/MessageDataHandler( 7577): getUnreadMessageCount :0
D/[CarModeFW]( 7577): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 167
,D/[CarModeFW]( 7577): RecommendHandler-selection = type = '3'
,D/ResourcesManager( 7636): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/[CarModeFW]( 7577): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarMode]( 7577): [DLApplication]-GooglePlayServices SUCCESS.
,D/TimaKeyStoreProvider( 7643): TimaSignature is unavailable
,D/ActivityThread( 7643): Added TimaKeyStore provider
,D/[CarModeFW]( 7577): RecommendHandler-selection = type = '3'
,D/MessageDataHandler( 7577):  getInboxList mms,sms cursor join : 20
,D/TP/MmsSmsProvider( 1473): query,matched:0, calling pid = 7577
,V/TP/MmsSmsProvider( 1473): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1473): match 0:Elapsed time : 2.043 ms
,E/[CarMode]( 7577): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/TP/MmsSmsProvider( 1473): query,matched:13, calling pid = 7577
,D/TP/MmsSmsProvider( 1473): match 13:Elapsed time : 1.040 ms
,D/MessageDataHandler( 7577):  getInboxList address cursor : 5
D/TP/MmsSmsProvider( 1473): query,matched:0, calling pid = 7577
V/TP/MmsSmsProvider( 1473): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1473): match 0:Elapsed time : 0.840 ms
I/UpdateManagerReceiver( 7577): Intent : android.intent.action.PACKAGE_ADDEDThu Dec 10 14:09:55 GMT+01:00 2015
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 7643): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
E/Zygote  ( 7666): MountEmulatedStorage()
I/libpersona( 7666): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7666): v2
I/libpersona( 7666): KNOX_SDCARD not a persona
I/ActivityManager(  884): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7666 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  884): Killing 6420:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
,I/SELinux ( 7666): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7666): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7666): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/[CarModeFW]( 7577): PushMessageService-onCreate
,I/ActivityManager(  884): Killing 6966:com.sec.android.fotaclient/u0a10 (adj 15): bgCount ##41
,D/MessageDataHandler( 7577):  getInboxList thread cursor : 62
,I/ActivityManager(  884): Killing 6803:com.google.android.gms:car/u0a11 (adj 15): bgCount ##42
I/ActivityManager(  884): Killing 6321:com.google.android.music:main/u0a125 (adj 15): bgCount ##43
,D/TimaKeyStoreProvider( 7666): TimaSignature is unavailable
,D/ActivityThread( 7666): Added TimaKeyStore provider
,D/MessageDataHandler( 7577):  thread, addr result: 20
I/[CarModeFW]( 7577): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 285
I/[CarModeFW]( 7577): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7577): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 286
,W/jxcore-log( 7488): Initializing JXcore engine
W/jxcore-log( 7488): JXcore engine is ready
,D/UserAnalysis.PlaceProvider( 7636): PlaceProvider onCreate()
,W/jxcore-log( 7488): Starting JXcore engine
,D/ResourcesManager( 7666): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,W/libprocessgroup(  884): failed to open /acct/uid_10043/pid_6420/cgroup.procs: No such file or directory
,D/[CarModeFW]( 7577): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7577): PushMessageService-registerPushMessageServiceListener
,E/auditd  ( 2184): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  884): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  884): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  884): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,I/art     (  884): Explicit concurrent mark sweep GC freed 239049(15MB) AllocSpace objects, 5(4MB) LOS objects, 31% free, 35MB/51MB, paused 5.355ms total 130.162ms
,D/UserAnalysis.SecureDbManager( 7636): Key for secure DB is newly created
,D/[CarModeFW]( 7577): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 473
,W/ContextImpl( 7666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,D/UserAnalysis.SecurePlaceDbHelper( 7636): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7636): Create SecureDbHelper
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7685): MountEmulatedStorage()
E/Zygote  ( 7685): v2
I/libpersona( 7685): KNOX_SDCARD checking this for 10111
I/libpersona( 7685): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7685 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,W/jxcore-log( 7488): Platform android
W/jxcore-log( 7488): 
,W/jxcore-log( 7488): Process ARCH arm
W/jxcore-log( 7488): 
D/IntelligenceServiceApplication( 7636): onCreate()
,I/art     (  326): Explicit concurrent mark sweep GC freed 8742(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 320us total 12.060ms
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 7.958ms
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 7.660ms
,E/SMD     (  292): DCD ON
,I/SELinux ( 7685): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/[CarModeFW]( 7577): -[snowdeer] Rec : Missed Call : 357
,D/ResourcesManager( 7666): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SELinux ( 7685): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7685): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/[CarModeFW]( 7577): -[snowdeer] Rec : Favorite : 9
,I/SQLiteSecureOpenHelper( 7636): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7636): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7636): Open Place.db in secure mode
I/[CarModeFW]( 7577): -[snowdeer] Rec : CallLog : 9
,D/TimaKeyStoreProvider( 7685): TimaSignature is unavailable
,D/ActivityThread( 7685): Added TimaKeyStore provider
,D/ResourcesManager( 7685): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/SQLiteSecureOpenHelper( 7636): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7636): ...getDatabaseLocked(b,b,pwd)
,E/FilterInstaller( 7666): There is no requred permission
,I/[CarModeFW]( 7577): -[snowdeer] Rec : Schedule : 30
,I/ActivityManager(  884): Killing 6987:com.samsung.klmsagent/u0a18 (adj 15): bgCount ##41
I/[CarModeFW]( 7577): -[snowdeer] Rec : During DL app : 1
,I/[CarModeFW]( 7577): -[snowdeer] Rec : Location Sharing : 1
I/[CarModeFW]( 7577): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 7577): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7577): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7577): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 7577): -[snowdeer] Rec : getContactListFromHashMap : 0
D/[CarModeFW]( 7577): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 595
D/[CarModeFW]( 7577): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 7577): MyPlaceProvider-=============
,D/[CarModeFW]( 7577): MyPlaceProvider-=============
D/[CarModeFW]( 7577): MyPlaceProvider-=============
D/[CarModeFW]( 7577): MyPlaceProvider-=============
D/[CarModeFW]( 7577): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7577): MyPlaceProvider-==============
D/[CarModeFW]( 7577): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7577): MyPlaceProvider-==============
,D/[CarModeFW]( 7577): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7577): MyPlaceProvider-==============
D/[CarModeFW]( 7577): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 7577): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 588
,I/[CarModeFW]( 7577): -[snowdeer] Rec : getContactListFromHashMap - core : 0
,I/[CarModeFW]( 7577): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7577): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7577): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 596
,D/[CarMode]( 7577): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@61449f7e, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@9dd7909c] LOCATIONS
,D/PackageIntentReceiver( 7685): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 7685): Not GearManger package! 
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7700): MountEmulatedStorage()
,E/Zygote  ( 7700): v2
I/libpersona( 7700): KNOX_SDCARD checking this for 10117
I/libpersona( 7700): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7700 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 7011:com.sec.android.soagent/u0a36 (adj 15): bgCount ##41
,I/SELinux ( 7700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  884): failed to open /acct/uid_10010/pid_6966/cgroup.procs: No such file or directory
I/SELinux ( 7700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/libprocessgroup(  884): failed to open /acct/uid_10011/pid_6803/cgroup.procs: No such file or directory
W/libprocessgroup(  884): failed to open /acct/uid_10125/pid_6321/cgroup.procs: No such file or directory
,E/SELinux ( 7700): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7700): TimaSignature is unavailable
,D/ActivityThread( 7700): Added TimaKeyStore provider
,D/ResourcesManager( 7700): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 7700): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  884): failed to open /acct/uid_10018/pid_6987/cgroup.procs: No such file or directory
,D/MagazineService Version( 7700): Magazine-Administrator: 11
,D/MagazineService Version( 7700): Magazine-Provider: 14
D/MagazineService Version( 7700): Magazine-Channel: 14
,D/HeadlinesChannelApplication( 7700): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7700): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7700): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 7716): MountEmulatedStorage()
I/libpersona( 7716): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7716): v2
I/libpersona( 7716): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7716 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7700): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/SELinux ( 7716): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  884): failed to open /acct/uid_10036/pid_7011/cgroup.procs: No such file or directory
,I/SELinux ( 7716): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7716): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  884): Killing 7045:com.samsung.android.scloud.sync/u0a66 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7716): TimaSignature is unavailable
,D/ActivityThread( 7716): Added TimaKeyStore provider
,D/ResourcesManager( 7716): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/libprocessgroup(  884): failed to open /acct/uid_10066/pid_7045/cgroup.procs: No such file or directory
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7731): MountEmulatedStorage()
E/Zygote  ( 7731): v2
I/libpersona( 7731): KNOX_SDCARD checking this for 1000
I/libpersona( 7731): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7731 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 7061:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): bgCount ##41
,I/System.out( 7603): INFO:Resource not found:/Common.properties Using default values
,I/SELinux ( 7731): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7731): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7731): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7731): TimaSignature is unavailable
,D/ActivityThread( 7731): Added TimaKeyStore provider
,D/ResourcesManager( 7731): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,D/AcmsPackageEventListener( 7731): Received: android.intent.action.PACKAGE_ADDED
,W/libprocessgroup(  884): failed to open /acct/uid_10070/pid_7061/cgroup.procs: No such file or directory
,W/ContextImpl( 7731): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService( 7731): Enter Oncreate
,D/AcmsServiceMonitor( 7731): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 7731): creating AcmsCore
D/AcmsCore( 7731): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7731): AcmsCore
,D/AcmsCore( 7731): init
D/AcmsCore( 7731): Looper handler is not null
D/AcmsCore( 7731): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7731): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7731): Incrementing - Counter value: 1
D/AcmsCore( 7731): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 7731): onStartCommand
D/AcmsService( 7731): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 7731): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7731): Incrementing - Counter value: 2
D/AcmsService( 7731): Incremented Counter Value : onStartCommand
D/AcmsCertificateMngr( 7731): AcmsCertificateMngr
D/ActivityThread( 7731): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsRevocationMngr( 7731): AcmsRevocationMngr
,D/AcmsService( 7731): Inside handle Intent
D/AcmsService( 7731): App added - package name: com.test.thalitest
D/AcmsCore( 7731): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7731): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7731): Incrementing - Counter value: 3
D/AcmsCore( 7731): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7731): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7731): Decrementing - Counter value: 2
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7750): MountEmulatedStorage()
E/Zygote  ( 7750): v2
I/libpersona( 7750): KNOX_SDCARD checking this for 10165
I/libpersona( 7750): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7750 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7750): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7750): TimaSignature is unavailable
,I/jxcore-log( 7488): JXcore Cordova bridge is ready!
I/jxcore-log( 7488): 
W/jxcore-log( 7488): JXcore engine is started
,D/ActivityThread( 7750): Added TimaKeyStore provider
,D/ResourcesManager( 7750): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7750): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 7750): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7765): MountEmulatedStorage()
I/libpersona( 7765): KNOX_SDCARD checking this for 10169
E/Zygote  ( 7765): v2
I/libpersona( 7765): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7765 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 7078:com.sec.android.app.clockpackage/u0a90 (adj 15): bgCount ##41
,I/SELinux ( 7765): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7765): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7765): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7765): TimaSignature is unavailable
,D/ActivityThread( 7765): Added TimaKeyStore provider
,D/ResourcesManager( 7765): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_7078/cgroup.procs: No such file or directory
,E/SQLiteLog( 7765): (284) automatic index on shooting_modes(title_id)
,D/Finsky  ( 6579): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/ActivityManager(  884): Killing 7093:com.sec.esdk.elm/u0a103 (adj 15): bgCount ##41
,D/PackageBroadcastService( 2424): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2424): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2424): Loading module APK com.google.android.play.games
,D/ResourcesManager( 2424): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,W/libprocessgroup(  884): failed to open /acct/uid_10103/pid_7093/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2424): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2424): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2424): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 2424): Submit a task: k
,D/ChimeraCfgMgr( 2424): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 2424): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2424): Processing package: com.test.thalitest
,D/GassUtils( 2424): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7790): MountEmulatedStorage()
E/Zygote  ( 7790): v2
I/libpersona( 7790): KNOX_SDCARD checking this for 10039
I/libpersona( 7790): KNOX_SDCARD not a persona
D/k       ( 2424): Found info for package com.test.thalitest in db.
,I/ActivityManager(  884): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7790 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7790): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7790): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7790): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/BaseAppContext( 2424): Using Auth Proxy for data requests.
,D/TimaKeyStoreProvider( 7790): TimaSignature is unavailable
,W/BaseAppContext( 2424): Using Auth Proxy for data requests.
D/ActivityThread( 7790): Added TimaKeyStore provider
,D/ResourcesManager( 7790): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,W/BaseAppContext( 2424): Using Auth Proxy for data requests.
,W/BaseAppContext( 2424): Using Auth Proxy for data requests.
,W/BaseAppContext( 2424): Using Auth Proxy for data requests.
,W/BaseAppContext( 2424): Using Auth Proxy for data requests.
,I/ActivityManager(  884): Killing 6005:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BootupListener( 1473): ACTION_DRIVELINK
,D/SettingsProvider(  884): name = drivelink_navigation
,D/SettingsProvider(  884): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  884): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  884): selectionArgs: false
D/SettingsProvider(  884): selectionArgs: 1001
D/SecContentProvider(  884): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  884): ret = -1
D/BootupListener( 1473): NAVI : com.google.android.apps.maps
,D/SettingsProvider(  884): name = internet_call_settings_visibility
D/SettingsProvider(  884): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  884): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  884): selectionArgs: false
D/SettingsProvider(  884): selectionArgs: 1001
D/SecContentProvider(  884): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  884): ret = -1
,D/SecurityLogAgent( 7112):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7112):  SeDenialReceiver : File path = null
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  884): failed to open /acct/uid_10112/pid_6005/cgroup.procs: No such file or directory
,I/VacuumService( 2256): Vacuum at: now=1449752997002 tag=VacuumService
,V/GLSActivity( 2256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  884): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhenotypeConfigurator( 2256): Scheduling Phenotype for one-off execution 6940 seconds from now (1449752997290)
,D/GetConfigurationSnapshotOperation( 2256): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/jxcore-log( 7488): Toggling radios to true
I/jxcore-log( 7488): 
,D/BluetoothAdapter( 7488): enable()
,D/BluetoothAdapter( 7488): enable(): BT is already enabled..!
,D/WifiService(  884): New client listening to asynchronous messages
,I/WifiManager( 7488): packageName : com.test.thalitest
,D/SecContentProvider(  884): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  884): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2(  884): mCursor = null
,D/WifiService(  884): setWifiEnabled: true pid=7488, uid=10356
,E/WifiService(  884): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  884): Permission Denial: getCurrentUser() from pid=7488, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  884): Failed getting userId using ActivityManagerNative
W/WifiService(  884): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7488, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  884): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  884): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  884): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  884): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  884): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  884): name = wifi_on
,D/ChimeraCfgMgr( 2424): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2424): Module APK com.google.android.play.games already loaded
,I/PhenotypeFlagCommitter( 2256): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/WifiService(  884): disconnect: pid=7488, uid=10356
,I/wpa_supplicant( 1276): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/GoogleURLConnFactory( 2256): Using platform SSLCertificateSocketFactory
,I/jxcore-log( 7488): Radios toggled
I/jxcore-log( 7488): 
,I/jxcore-log( 7488): Got Device Bluetooth address: 7C:F9:0E:34:8A:A0
I/jxcore-log( 7488): 
,I/jxcore-log( 7488): Perf Test app loaded loaded
I/jxcore-log( 7488): 
,I/jxcore-log( 7488): check test folder
I/jxcore-log( 7488): 
,I/jxcore-log( 7488): found test : ./testFindPeers.js
I/jxcore-log( 7488): 
I/wpa_supplicant( 1276): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1276): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1276): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  884): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1276): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1276): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1276): Disconnected - do not scan
I/wpa_supplicant( 1276): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  884): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  884): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  884): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  884): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  884): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  884): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  884): do suspend true
,D/WifiP2pService(  884): InactiveState{ what=143375 }
,D/WifiP2pService(  884): P2pEnabledState{ what=143375 }
,D/CommandListener(  285): Clearing all IP addresses on wlan0
,I/jxcore-log( 7488): found test : ./testSendData.js
I/jxcore-log( 7488): 
,D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NativeCrypto( 2256): Read error: ssl=0x9b33ae00: I/O error during system call, Connection timed out
,E/WifiStateMachine(  884): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  884): updateNetworkInfo()
D/ConnectivityService(  884): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  884): updateNetworkInfo()
D/ConnectivityService(  884): ignoring duplicate network state non-change
D/ConnectivityService(  884): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,V/NativeCrypto( 2256): SSL shutdown failed: ssl=0x9b33ae00: I/O error during system call, Broken pipe
,E/WifiConfigStore(  884): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/LocationManagerService(  884): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/WifiTrafficPoller(  884): evaluateTrafficStatsPolling
,I/CLocInfoService(  884): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1182): applyOpen
E/WifiStateMachine(  884): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1276): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1276): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1276): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1276): First Scan Start
,I/wpa_supplicant( 1276): Scan requested (ret=0) - scan timeout 30 seconds
,D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
,E/WifiStateMachine(  884): ConnectModeState: Network connection lost 
,D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1182): applyOpen
,D/FactoryTest( 6659): Not factory mode
D/FactoryTest( 6659): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6659): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6659): still no open session command from host, so toast
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
W/ContextImpl( 6659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 6659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6659): Timeline: Activity_launch_request id:com.android.settings time:111412
D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,E/PersonaManagerService(  884): inState():  stateMachine is null !!
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Validated
D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/ApplicationPolicy(  884): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  884): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  884): mDVFSHelper.acquire()
,E/WifiStateMachine(  884): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  884): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  884): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  884): do suspend true
,D/WifiP2pService(  884): InactiveState{ what=143375 }
,D/WifiP2pService(  884): P2pEnabledState{ what=143375 }
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/CommandListener(  285): Clearing all IP addresses on wlan0
D/ConnectivityService(  884): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
E/MTPRx   ( 6659): started activity for popup
D/ConnectivityService(  884): calling update connectivity
D/ConnectivityService(  884):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  884): Not allowed due to - mEnabled false
D/ConnectivityService(  884):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  884): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  884): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  884):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524292
D/ConnectivityService(  884): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  884): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  884): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Disconnected - quitting
D/ConnectivityService(  884): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2424): CM callback handler got msg 524292
D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/CSLegacyTypeTracker(  884): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1473): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  884): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/WifiStateMachine(  884): updateConfiguredNetworkExpiration - currTime: 1449752997508
D/ConnectivityService(  884): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/WifiStateMachine(  884): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
I/WifiTrafficPoller(  884): evaluateTrafficStatsPolling
E/WifiStateMachine(  884): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/CLocInfoService(  884): External Intent Received android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/Hs20UtilService( 1313): Starting #6
E/ConnectivityService(  884): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
I/Hs20UtilService( 1313): Message received 5007
E/WifiStateMachine(  884): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  884): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  884): NetworkAgent: NetworkAgent channel lost
V/NetworkStats(  884): updateIfacesLocked()
D/NtpTrustedTime(  884): currentTimeMillis() cache hit
V/NetworkStats(  884): performPollLocked(flags=0x1)
D/SmartBondingService(  884): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  884): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  884): getSBEnabled() enabled =false
D/SmartBondingService(  884): getSBEnabled() enabled =false
D/SmartBondingService(  884): getSBEnabled() enabled =false
,D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): 0
D/NetworkStatsFactory(  884): UpdateStatsForKnox
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1182): updateDataNetType()
D/StatusBar.NetworkController( 1182): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1182): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1182): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/NtpTrustedTime(  884): currentTimeMillis() cache hit
D/NtpTrustedTime(  884): currentTimeMillis() cache hit
D/NtpTrustedTime(  884): currentTimeMillis() cache hit
V/NetworkStats(  884): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  884): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
,E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  884): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  884): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  884): uri = 20 selection = getPromptCredentialsEnabled
D/SmartBondingService(  884): getNetworkEnabled : wifi : true mobile : true
D/SecContentProvider2(  884): mCursor = null
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SQLiteSecureOpenHelper( 3526): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3526): getDatabaseLocked(b,b,pwd)...
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,V/NetworkStats(  884): performPollLocked() took 28ms
,D/SecContentProvider2(  884): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  884): mCursor = null
,D/NtpTrustedTime(  884): currentTimeMillis() cache hit
,D/ResourcesManager( 6659): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/NtpTrustedTime(  884): currentTimeMillis() cache hit
,D/NtpTrustedTime(  884): currentTimeMillis() cache hit
,W/ResourcesManager( 6659): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6659): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6659): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6659): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6659): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6659): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6659): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/Hs20UtilService( 1313): Starting #7
,I/Hs20UtilService( 1313): Message received 5007
,I/Choreographer( 7488): Skipped 84 frames!  The application may be doing too much work on its main thread.
,E/SettingsReceiverActivity( 6659): PREF_DONT_ASK_AGAIN : true
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/InputMethodManagerService(  884): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  884): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@5fe5822 attribute=null, token = android.os.BinderProxy@854ea81
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
,I/chromium( 7488): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,I/chromium( 7488): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,V/BitmapFactory( 6659): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/SettingsReceiverActivity( 6659): dev.kiessupport is : TRUE
,V/GLSActivity( 2256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Activity( 6659): performCreate Call secproduct feature valuefalse
D/Activity( 6659): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ActivityManager(  884): post active user change for 0
D/KnoxTimeoutHandler(  884): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  884): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/Timeline( 7488): Timeline: Activity_idle id: android.os.BinderProxy@1b755df2 time:111660
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/Icing   ( 2424): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,I/System.out( 2256): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 2256): (HTTPLog)-Static: isShipBuild true
I/System.out( 2256): (HTTPLog)-Thread-315-610538873: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/Uploader( 2256): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/ResourcesManager( 2424): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,V/AlarmManager(  884): waitForAlarm result :4
,D/KeyguardViewMediator( 1182): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/KeyguardViewMediator( 1182): doKeyguard: not showing because lockscreen is off
,I/Icing   ( 2424): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,D/LocationManagerService(  884): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/Uploader( 2256): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/LocationManagerService(  884): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/Uploader( 2256): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/LocationManagerService(  884): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/Uploader( 2256): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  884): MasterInitialState.processMessage what=3
,D/SmartBondingService(  884): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  884): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  884): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  884): getSBEnabled() enabled =false
D/SmartBondingService(  884): getSBEnabled() enabled =false
D/SmartBondingService(  884): getSBEnabled() enabled =false
D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  884): CLoinfo wifi false
,I/ApplicationPolicy(  884): updateDataUsageMap
,D/SmartBondingService(  884): getNetworkEnabled : wifi : true mobile : true
,D/accuweather( 2058): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 7322): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7322): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7322): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7322): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3749): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7322): noConnectivity : true
,W/SLocation(  884): No Active Data Connection
,I/ActivityManager(  884): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7847 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7847): MountEmulatedStorage()
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7847): v2
,I/libpersona( 7847): KNOX_SDCARD checking this for 10125
I/libpersona( 7847): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3749): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/SELinux ( 7847): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7847): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7847): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7847): TimaSignature is unavailable
,D/ActivityThread( 7847): Added TimaKeyStore provider
,D/ResourcesManager( 7847): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore( 7847): Database version: 104
,D/ResourcesManager( 7847): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7847): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7847): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/AcmsKeyStoreHelper( 7731):  getKeyStoreForApplication Enter
,V/JNIHelp ( 7847): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AcmsKeyStoreHelper( 7731): Key Store exist
,I/AcmsKeyStoreHelper( 7731): Hence loading the keystore file
,W/ActivityThread( 7847): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7847): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39c1b84d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7847): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7847): GMSCore installation verified
,I/ConfigStore( 7847): Config Database version: 1
,I/PowerManagerService(  884): [PWL] Off : 5s ago
I/PowerManagerService(  884): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  884): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  884): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=884, ws=null) (elapsedTime=803)
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7847): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/AcmsKeyStoreHelper( 7731):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 7731): getKeyStoreForApplication success 
D/AcmsCore( 7731): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7731): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7731): Decrementing - Counter value: 1
D/AcmsCore( 7731): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 7731): This is NOT a valid MirrorLink app
D/AcmsCore( 7731): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7731): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7731): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7731): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7731): getSvcCounter - Counter value: 0
D/AcmsService( 7731): Enter onDestroy
I/AcmsService( 7731): cleanUp(): inside service clean up
D/AcmsCore( 7731): AcmsCore: inside DeInit
D/AcmsCore( 7731): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7731): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 7731): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7731): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7731): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 7731): getSvcCounter - Counter value: 0
D/AcmsService( 7731): killing acms process
I/Process ( 7731): Sending signal. PID: 7731 SIG: 9
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7847): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7847): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/ActivityManager(  884): Process ACMS.Process (pid 7731)(adj 0) has died(59,576)
,D/WifiDisplayAdapter(  884): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  884): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  299): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  884): getStreamVolume 3 index 0
I/MediaRouter( 7847): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7872): MountEmulatedStorage()
,E/Zygote  ( 7872): v2
I/libpersona( 7872): KNOX_SDCARD checking this for 10002
I/libpersona( 7872): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7872 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7872): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7872): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7872): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter(  884): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7847): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider( 7872): TimaSignature is unavailable
,D/ActivityThread( 7872): Added TimaKeyStore provider
I/ActivityManager(  884): Killing 5769:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): bgCount ##41
,D/ResourcesManager( 7872): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  884): Killing 4753:com.android.calendar/u0a149 (adj 15): bgCount ##41
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/SMD     (  292): DCD ON
,E/Zygote  ( 7890): MountEmulatedStorage()
I/libpersona( 7890): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7890): v2
I/libpersona( 7890): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7890 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/wpa_supplicant( 1276): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 1276): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1276): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1276): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
I/art     (  884): Explicit concurrent mark sweep GC freed 47562(2MB) AllocSpace objects, 1(16KB) LOS objects, 31% free, 35MB/51MB, paused 1.192ms total 83.939ms
,E/WifiStateMachine(  884): [1,449,752,998,540 ms] noteScanEnd no scan source
,I/SELinux ( 7890): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,E/WifiStateMachine(  884): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1b0374fe sup_state=SCANNING debouncing=false
,W/libprocessgroup(  884): failed to open /acct/uid_10148/pid_5769/cgroup.procs: No such file or directory
I/SELinux ( 7890): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7890): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  884): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  884): setDetailed state send new extra info0x
,D/SecContentProvider2(  884): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  884): mCursor = null
,I/CLocInfoService(  884): External Intent Received android.net.wifi.SCAN_RESULTS
,W/libprocessgroup(  884): failed to open /acct/uid_10149/pid_4753/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7890): TimaSignature is unavailable
,D/ActivityThread( 7890): Added TimaKeyStore provider
,D/ResourcesManager( 7890): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7890): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/wpa_supplicant( 1276): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  884): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,I/wpa_supplicant( 1276): Associated with C0.AA.48
,D/SecContentProvider2(  884): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  884): mCursor = null
,I/DIAGMON_AGENT( 7890): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/wpa_supplicant( 1276): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  884): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  884): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  884): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  884): mCursor = null
,I/wpa_supplicant( 1276): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1276): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1276): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1276): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1276): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1276): Blacklist: Clear (temp) 
I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  884): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  884): Network connection established
,D/WifiNative-HAL(  884): callSECApiVoid - ID [50]
,E/WifiStateMachine(  884): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  884): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  884): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  884): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  884): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  884): Got NetworkAgent Messenger
D/ConnectivityService(  884): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  884): updateNetworkInfo()
D/ConnectivityService(  884): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  884): NetworkAgent connected
E/WifiStateMachine(  884): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  884): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  884): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  884): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  884): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  884): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  285): Setting iface cfg
,E/WifiStateMachine(  884): Start Dhcp Watchdog 2
,D/SecContentProvider2(  884): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  884): mCursor = null
,E/WifiStateMachine(  884): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  884): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  884): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/DIAGMON_AGENT( 7890): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7890): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7890): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7890): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/WifiStateMachine(  884): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  884): do suspend false
,D/SecContentProvider2(  884): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  884): mCursor = null
,D/WifiP2pService(  884): InactiveState{ what=143375 }
D/WifiP2pService(  884): P2pEnabledState{ what=143375 }
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  884): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7908 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7908): MountEmulatedStorage()
E/Zygote  ( 7908): v2
,I/libpersona( 7908): KNOX_SDCARD checking this for 10010
I/libpersona( 7908): KNOX_SDCARD not a persona
,I/SELinux ( 7908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7908): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7908): TimaSignature is unavailable
,D/ActivityThread( 7908): Added TimaKeyStore provider
,D/ResourcesManager( 7908): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  884): Killing 7128:com.sec.android.app.taskmanager/u0a175 (adj 15): bgCount ##41
,I/FOTA_Client( 7908): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7908): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7908): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7926): MountEmulatedStorage()
E/Zygote  ( 7926): v2
I/libpersona( 7926): KNOX_SDCARD checking this for 10018
I/libpersona( 7926): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7926 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 7143:com.qualcomm.timeservice/1000 (adj 15): bgCount ##41
,I/art     (  326): Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 278us total 14.681ms
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.554ms
,I/SELinux ( 7926): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  884): failed to open /acct/uid_10175/pid_7128/cgroup.procs: No such file or directory
,I/SELinux ( 7926): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7926): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 243us total 8.071ms
,E/dhcpcd  ( 7932): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7932): version 5.5.6 starting
,E/dhcpcd  ( 7932): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/TimaKeyStoreProvider( 7926): TimaSignature is unavailable
,D/ActivityThread( 7926): Added TimaKeyStore provider
,W/libprocessgroup(  884): failed to open /acct/uid_1000/pid_7143/cgroup.procs: No such file or directory
,D/ResourcesManager( 7926): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7926): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7926): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449752999019
,I/KLMS-2.4.503: ( 7926): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7926): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/KLMS-2.4.503: ( 7926): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  884): Killing 4810:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7947): MountEmulatedStorage()
E/Zygote  ( 7947): v2
I/libpersona( 7947): KNOX_SDCARD checking this for 10036
I/libpersona( 7947): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7947 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/dhcpcd  ( 7932): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7932): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7932): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7932): bssid match
,I/dhcpcd  ( 7932): wlan0: rebinding lease of 192.168.1.136
,I/SELinux ( 7947): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7947): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7947): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7947): TimaSignature is unavailable
W/libprocessgroup(  884): failed to open /acct/uid_10045/pid_4810/cgroup.procs: No such file or directory
,D/ActivityThread( 7947): Added TimaKeyStore provider
,D/ResourcesManager( 7947): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7947): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7359): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 7027): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7027): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7027): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7027): [SLFUCHKMGR] constructor called
,E/SPPClientService( 7359): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 7027): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7027): [OR] == isSIMCardReady false ==
,I/SA      ( 7027): [SCU] == networkStateCheck == false
I/SA      ( 7027): [OR] onReceive END
,I/ActivityManager(  884): Killing 7178:com.sec.enterprise.knox.cloudmdm.smdms/u0a178 (adj 15): bgCount ##41
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7966): MountEmulatedStorage()
,E/Zygote  ( 7966): v2
I/libpersona( 7966): KNOX_SDCARD checking this for 10070
I/libpersona( 7966): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7966 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7966): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7966): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7966): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  884): failed to open /acct/uid_10178/pid_7178/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7966): TimaSignature is unavailable
,D/ActivityThread( 7966): Added TimaKeyStore provider
,D/ResourcesManager( 7966): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7966): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7966): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7966): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7966): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7966): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7966): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
,D/comsamsunglog( 7966): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7966): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7966): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7966): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7966): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  884): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  884): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  884): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  884): selectionArgs: false
D/SettingsProvider(  884): selectionArgs: 10070
D/SecContentProvider(  884): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  884): ret = -1
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7966): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7966): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
D/accuweather( 7966): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7966): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7966): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7966): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7966): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7966): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7966): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7966): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 6515): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 6515): premStatus:2
,I/KnoxUsageLogPro( 6515): isEulaShown : false
I/KnoxUsageLogPro( 6515): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7984): MountEmulatedStorage()
E/Zygote  ( 7984): v2
I/libpersona( 7984): KNOX_SDCARD checking this for 10087
I/libpersona( 7984): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7984 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 6491:com.samsung.android.app.FileShareServer/u0a74 (adj 15): bgCount ##41
,I/GAV2    ( 7504): Thread[GAThread,5,main]: No campaign data found.
,I/SELinux ( 7984): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7984): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7984): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7984): TimaSignature is unavailable
,D/ActivityThread( 7984): Added TimaKeyStore provider
,D/ResourcesManager( 7984): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  884): failed to open /acct/uid_10074/pid_6491/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Killing 6563:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,D/Headlines( 5554): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5554): getCountryCode(): countryCode = PL
,D/Headlines( 5554): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5554): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5554): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5554): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5554): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5554): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5554): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8001): MountEmulatedStorage()
E/Zygote  ( 8001): v2
I/libpersona( 8001): KNOX_SDCARD checking this for 10127
I/libpersona( 8001): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8001 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8001): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8001): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8001): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8001): TimaSignature is unavailable
,D/ActivityThread( 8001): Added TimaKeyStore provider
,W/libprocessgroup(  884): failed to open /acct/uid_1000/pid_6563/cgroup.procs: No such file or directory
,D/ResourcesManager( 8001): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8001): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8001): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8001): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8001): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/WebViewFactory( 8001): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 8001): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 8001): Loading: webviewchromium
,I/LibraryLoader( 8001): Time to load native libraries: 4 ms (timestamps 3770-3774)
,I/LibraryLoader( 8001): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8001): Binding Chromium to main looper Looper (main, tid 1) {2e7e8c49}
,I/LibraryLoader( 8001): Expected native library version number "",actual native library version number ""
,I/chromium( 8001): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8001): Initializing chromium process, renderers=0
,W/art     ( 8001): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 8001): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,W/AudioManagerAndroid( 8001): Requires BLUETOOTH permission
,I/chromium( 8001): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium( 8001): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/Adreno-EGL( 8001): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8001): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8001): Build Date: 03/03/15 Tue
I/Adreno-EGL( 8001): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 8001): Remote Branch: 
I/Adreno-EGL( 8001): Local Patches: 
I/Adreno-EGL( 8001): Reconstruct Branch: 
,I/NSApplication( 8001): Starting up...
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8056): MountEmulatedStorage()
E/Zygote  ( 8056): v2
,I/libpersona( 8056): KNOX_SDCARD checking this for 10137
I/libpersona( 8056): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8056 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 7284:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,I/SELinux ( 8056): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8056): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8056): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  884): failed to open /acct/uid_10014/pid_7284/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8056): TimaSignature is unavailable
,D/ActivityThread( 8056): Added TimaKeyStore provider
,V/AlarmManager(  884): waitForAlarm result :8
,D/ResourcesManager( 8056): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 8056): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8056): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8056): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 8056): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8056): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8056): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8071): MountEmulatedStorage()
,E/Zygote  ( 8071): v2
I/libpersona( 8071): KNOX_SDCARD checking this for 10162
I/libpersona( 8071): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8071 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 7305:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,I/SELinux ( 8071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8071): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8071): TimaSignature is unavailable
,D/ActivityThread( 8071): Added TimaKeyStore provider
,D/ResourcesManager( 8071): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8071): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8071): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8071): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8071): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  884): failed to open /acct/uid_10015/pid_7305/cgroup.procs: No such file or directory
,D/RCPManagerService(  884): exchangeData() failure , invalid userId
,D/RCPManagerService(  884): exchangeData() failure , invalid userId
,D/RCPManagerService(  884): exchangeData() failure , invalid userId
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7932): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/RCPManagerService(  884): exchangeData() failure , invalid userId
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,E/Zygote  ( 8094): MountEmulatedStorage()
,E/Zygote  ( 8094): v2
I/libpersona( 8094): KNOX_SDCARD checking this for 10077
I/libpersona( 8094): KNOX_SDCARD not a persona
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,I/ActivityManager(  884): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8094 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,I/dhcpcd  ( 7932): wlan0: leased 192.168.1.136 for 86400 seconds
,E/WifiStateMachine(  884): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  884): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  884): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,I/SELinux ( 8094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8094): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,D/TimaKeyStoreProvider( 8094): TimaSignature is unavailable
,D/ActivityThread( 8094): Added TimaKeyStore provider
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/ResourcesManager( 8094): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/RCPManagerService(  884): exchangeData() failure , invalid userId
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,D/RCPManagerService(  884): exchangeData() failure , invalid userId
,I/ActivityManager(  884): Killing 6467:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,D/BadgeProvider( 8094): onCreate
,D/BadgeProvider( 8094): DatabaseHelper
D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7112): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7112): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7112): StateMachine : Current State = 1
D/SecurityLogAgent( 7112): StateMachine : Changed Current State = 1
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,I/ActivityManager(  884): Killing 4949:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,D/BadgeProvider( 8094): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/BadgeProvider( 8094): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8094): sendNotify, [notify] : null
D/BadgeProvider( 8094): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8094): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8094): update, [UpdateCount] : 1
,E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  884): checkUser: useridlist=null, currentuser=0
,D/Launcher.Model( 1498): reloadBadges entered.
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 8071): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,E/Zygote  ( 8129): MountEmulatedStorage()
,E/Zygote  ( 8129): v2
I/libpersona( 8129): KNOX_SDCARD checking this for 10177
I/libpersona( 8129): KNOX_SDCARD not a persona
,I/ActivityManager(  884): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8129 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8129): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8129): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8129): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  884): failed to open /acct/uid_10033/pid_6467/cgroup.procs: No such file or directory
,W/libprocessgroup(  884): failed to open /acct/uid_10034/pid_4949/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8129): TimaSignature is unavailable
,D/ActivityThread( 8129): Added TimaKeyStore provider
,W/ActivityManager(  884): mDVFSHelper.release()
,D/ResourcesManager( 8129): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  884): Killing 7376:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,I/iu.Environment( 2424): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2424): num queued entries: 0
,I/iu.UploadsManager( 2424): num updated entries: 0
,I/iu.SyncManager( 2424): NEXT; no task
,W/libprocessgroup(  884): failed to open /acct/uid_10041/pid_7376/cgroup.procs: No such file or directory
,I/Hs20UtilService( 1313): Starting #8
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,W/ActivityManager(  884): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/WifiStateMachine(  884): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  884): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  884): do suspend true
,D/WifiP2pService(  884): InactiveState{ what=143375 }
,D/WifiP2pService(  884): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  884): WifiStateMachine DHCP successful
,E/WifiStateMachine(  884): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  884): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  884): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  884): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  884): Not connected state, yet.
,E/WifiStateMachine(  884): VerifyingLinkState enter
D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  884): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  884): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  884): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  884): callSECApiInt - ID [210]
,E/WifiStateMachine(  884): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService(  884): updateNetworkInfo()
,D/ConnectivityService(  884): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  884): Adding iface wlan0 to network 503
,I/CLocInfoService(  884): External Intent Received android.net.wifi.STATE_CHANGE
D/WifiWatchdogStateMachine(  884): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  884): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  884): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  884): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  884): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/Hs20UtilService( 1313): Starting #9
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,E/WifiStateMachine(  884): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  884): Now, connected state.
E/WifiStateMachine(  884): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  884): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  884): evaluateTrafficStatsPolling
,I/CLocInfoService(  884): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  884): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  884): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  884): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  884): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  884): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  884): updateSourceRoutes : add src route for:192.168.1.136
,I/WifiTrafficPoller(  884): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  884): mBoosterFLAG : 0
I/WifiTrafficPoller(  884): current booster mode : FullMode
D/WifiNative-HAL(  884): callSECApiVoid - ID [212]
,V/        (  285): QcRouteController
E/WifiStateMachine(  884): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/CLocInfoService(  884): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
,E/WifiStateMachine(  884): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
I/WifiStateMachine(  884): REQUEST_POWER_SAVE_ON
,I/Hs20UtilService( 1313): Starting #10
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  884): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,V/        (  285): QcRouteController
,I/Hs20UtilService( 1313): Starting #11
,V/        (  285): QcRouteController
I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  884): callSECApi what=220
D/WifiStateMachine(  884): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,I/SurfaceFlinger(  257): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,V/        (  285): QcRouteController
,D/PowerManagerService(  884): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=884
,D/ConnectivityService(  884): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  884): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  884): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  884): updateNetworkInfo()
D/ConnectivityService(  884): calling update connectivity
E/ConnectivityService(  884): updateNetworkInfo()
D/ConnectivityService(  884): ignoring duplicate network state non-change
D/ConnectivityService(  884): ignoring duplicate network state non-change
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  884): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Connected
D/ConnectivityService(  884): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  884): calling update connectivity
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Validated
D/ConnectivityService(  884): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  884):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/ConnectivityService(  884):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/LockPatternUtilsCache( 1182): value : false
D/ConnectivityService(  884):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  884):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/ConnectivityService(  884): currentScore = 0, newScore = 60
D/ConnectivityService(  884):    accepting network in place of null
D/ConnectivityService(  884): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/LockPatternUtilsCache( 1182): value : false
D/TelephonyNetworkFactory( 1473): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,E/CSLegacyTypeTracker(  884): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  884): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  884): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  884): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  884): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  884): getSBEnabled() enabled =false
D/SmartBondingService(  884): getSBEnabled() enabled =false
D/SmartBondingService(  884): getSBEnabled() enabled =false
,D/SmartBondingService(  884): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  884): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,V/NetworkStats(  884): updateIfacesLocked()
V/NetworkStats(  884): performPollLocked(flags=0x1)
D/NtpTrustedTime(  884): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  884): UpdateStatsForKnox
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ConnectivityService(  884): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/EntConnectivity(  884): Not allowed due to - mEnabled false
,D/ConnectivityService(  884): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  884): calling update connectivity
,D/NtpTrustedTime(  884): currentTimeMillis() cache hit
,D/NtpTrustedTime(  884): currentTimeMillis() cache hit
V/NetworkStats(  884): performPollLocked() took 5ms
D/NtpTrustedTime(  884): currentTimeMillis() cache hit
D/NtpTrustedTime(  884): currentTimeMillis() cache hit
V/NetworkStats(  884): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  884): currentTimeMillis() cache hit
D/ConnectivityService(  884):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  884):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  884): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524290
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1182): updateDataNetType()
D/StatusBar.NetworkController( 1182): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1182): updateLTEICONDataNetType:0
D/ConnectivityService(  884):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  884): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  884): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  884): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  884):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 2424): CM callback handler got msg 524290
D/ConnectivityService(  884):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  884):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  884): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  884): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  884): calling update connectivity
D/ConnectivityService(  884):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  884):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  884): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524290
D/NtpTrustedTime(  884): currentTimeMillis() cache hit
D/NtpTrustedTime(  884): currentTimeMillis() cache hit
,D/ConnectivityService(  884):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1182): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/ConnectivityService(  884): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/StatusBar.NetworkController( 1182): applyOpen
,D/ConnectivityManager.CallbackHandler( 2424): CM callback handler got msg 524290
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1182): value : false
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1182): updateDataNetType()
D/StatusBar.NetworkController( 1182): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1182): updateLTEICONDataNetType:0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/StatusBar.NetworkController( 1182): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  884): waitForAlarm result :4
,D/Tethering(  884): MasterInitialState.processMessage what=3
,D/SmartBondingService(  884): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  884): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  884): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  884): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  884): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  884): getSBEnabled() enabled =false
D/SmartBondingService(  884): getSBEnabled() enabled =false
,D/SmartBondingService(  884): getSBEnabled() enabled =false
,D/SmartBondingService(  884): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  884): CLocinfo wifi true 
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2242): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2242): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/accuweather( 2058): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7847): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 7322): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7322): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7322): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7322): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3749): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3749): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  884): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  884): mCursor = null
,I/DIAGMON_AGENT( 7890): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7890): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/SMD     (  292): DCD ON
,I/FOTA_Client( 7908): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7908): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7908): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.503: ( 7926): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7926): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449753001579
,I/KLMS-2.4.503: ( 7926): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7926): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7926): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7926): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7926): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7947): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7359): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7027): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7027): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7027): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7027): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7027): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7027): [SCU] == networkStateCheck == true
,I/SA      ( 7027): [DM] getCountryCodeFromCSC : PL
I/SA      ( 7027): isChinaCountryCode : false
I/SA      ( 7027): [SCU] is ChinestModel Data Restricted   : false
,I/SA      ( 7027): [OR] == networkStateCheck true ==
,I/SA      ( 7027): [OR] GetMyCountryZoneTask
,I/SA      ( 7027): [OR] onReceive END
,I/SA      ( 7027): [SRS] prepareGetMyCountryZone
,I/SA      ( 7027): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7027): [SSP] query invoked
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7027): [TPMU] GetMccFromDB : null
,I/SA      ( 7027): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 7027): [TPM] isNoProxy(default) : true
,D/accuweather( 7966): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7966): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 6515): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 6515): premStatus:2
,I/KnoxUsageLogPro( 6515): isEulaShown : false
I/KnoxUsageLogPro( 6515): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 7027): fail readDirectory() errno=2
,D/Headlines( 5554): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5554): getCountryCode(): countryCode = PL
,D/Headlines( 5554): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5554): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5554): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5554): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5554): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5554): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5554): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 8056): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8056): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8056): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  884): exchangeData() failure , invalid userId
,D/RCPManagerService(  884): exchangeData() failure , invalid userId
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7112): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7112): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7112): StateMachine : Current State = 1
D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7112): StateMachine : Changed Current State = 1
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.Environment( 2424): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2424): num queued entries: 0
,I/iu.UploadsManager( 2424): num updated entries: 0
,I/iu.SyncManager( 2424): NEXT; no task
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7790): notifyNetworkActivated
,W/ContextImpl( 7790): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  884): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/jxcore-log( 7488): BLE supported!!
I/jxcore-log( 7488): 
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7790): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7790): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7790): exit::IDLE
D/InitializeManagerStateMachine( 7790): entry::NETWORK_CHECK
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7790): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7790): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7790): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7790): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7790): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7790): entry::SUCCESS
D/hcjo    ( 7790): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7790): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7790): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7790): exit::SUCCESS
D/InitializeManagerStateMachine( 7790): entry::IDLE
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,D/PackageManager(  884): [MSG] MCS_UNBIND
,I/ActivityManager(  884): Killing 5922:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,W/libprocessgroup(  884): failed to open /acct/uid_10047/pid_5922/cgroup.procs: No such file or directory
,D/SSRM:m  (  884): SIOP:: AP = 410, PST = 368, CUR = 450
,I/SA      ( 7027): [RC New] Execute method=[GET] start
,I/dhcpcd  ( 7932): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 7932): wlan0: sendmsg: Cannot assign requested address
,I/SA      ( 7027): [RC New] Security=[true]
,I/System.out( 7027): Thread-1091(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7027): Thread-1091(ApacheHTTPLog):isShipBuild true
,I/System.out( 7027): Thread-1091(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/WearableService( 2256): callingUid 10011, callindPid: 2256
,D/ResourcesManager( 7847): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7847): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7847): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7847): Using the GMSCore's GoogleHttpClient
,D/WearableClient( 7847): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7847): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7847): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7847): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7847): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7847): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7847): Conditions not met for autocaching.
I/MusicLeanback( 7847): Stop autocaching.
,E/ActivityThread( 7847): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1b56be2f that was originally bound here
E/ActivityThread( 7847): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1b56be2f that was originally bound here
E/ActivityThread( 7847): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7847): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7847): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7847): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7847): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7847): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7847): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7847): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7847): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7847): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7847): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7847): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7847): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7847): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7847): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7847): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7847): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7847): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7847): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7847): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7847): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7847): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7847): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7847): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7847): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/Atfwd_Sendcmd(  342): AtCmdFwd service not published, waiting... retryCnt : 1
,I/WifiStateMachine(  884): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  884): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      ( 7027): [RC New] [v2liruge] api execute + 868
,I/SA      ( 7027): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7027): AsyncTask #1 calls detatch()
,I/SA      ( 7027): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7027): [OCP] update openData : PL
,I/SurfaceFlinger(  257): id=17 Removed Toast (8/9)
,I/SurfaceFlinger(  257): id=17 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/PowerManagerService(  884): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 884) eventTime = 118168
,D/PowerManagerService(  884): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=884 (0x0)
,D/PowerManagerService(  884): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=884, ws=WorkSource{10058}) (elapsedTime=3503)
,I/SA      ( 7027): [TPMU] getNetworkMcc : 
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,I/SA      ( 7027): [SCU] saveMccToPreferece Start
,I/SA      ( 7027): [SCU] RegionMCC : 260
,I/SA      ( 7027): [SSP] query invoked
,I/SA      ( 7027): [TPMU] GetMccFromDB : null
,I/SA      ( 7027): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7027): [SCU] saveMccToPreferece End
,I/SA      ( 7027): [RC New] executeRequest [v2liruge] end. 1041
,I/SA      ( 7027): [RC New] Execute end
,I/SA      ( 7027): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7027): [OR] GetMyCountryZoneTask Success
,E/SMD     (  292): DCD ON
,E/WifiStateMachine(  884): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  884): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  884): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,E/WifiStateMachine(  884): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov,
,D/SmartBondingService(  884): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  884): identical MTU - not setting
,D/ConnectivityService(  884): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  884): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
,D/SmartBondingService(  884): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  884): getSBEnabled() enabled =false
D/SmartBondingService(  884): getSBEnabled() enabled =false
,D/SmartBondingService(  884): getSBEnabled() enabled =false
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,W/NetworkManagementService(  884): route cmd failed: 
W/NetworkManagementService(  884): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  884): '
W/NetworkManagementService(  884): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  884): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  884): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  884): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  884): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  884): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  884): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  884): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  884): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  884): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  884): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  884): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  884): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  884): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  884): calling update connectivity
,D/ConnectivityService(  884):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  884):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  884): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524295
,D/ConnectivityService(  884):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  884): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  884): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  884): calling update connectivity
D/ConnectivityService(  884):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  884):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 2424): CM callback handler got msg 524295
,D/ConnectivityService(  884): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524295
,D/ConnectivityService(  884):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  884): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2424): CM callback handler got msg 524295
,I/GAV4    ( 8001): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7322): mConnectivityHandler : connected
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7322): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7322): [GetString-S]
,I/ReactiveServiceManager( 7322): Supported : 1
,D/QSEECOMAPI: (  884): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: (  884): App is not loaded in QSEE
,D/QSEECOMAPI: (  884): Loaded image: APP id = 2
,D/QSEECOMAPI: (  884): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  884): QSEECom_shutdown_app, app_id = 2
,E/terrier (  884): handleString: Failed to handle string(-4)
E/terrier (  884): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 7322): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7322): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7322): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7322): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7322): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7322): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7932): wlan0: sending IPv6 Router Solicitation,
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  884): [PWL] Off : 15s ago
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 7932): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7932): wlan0: no IPv6 Routers available
,V/AlarmManager(  884): waitForAlarm result :4
,D/BatteryService(  884): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  884): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  884): stay LED for fully charged
,D/BatteryService(  884): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  884):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  884): Plugged
I/MotionRecognitionService(  884): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,D/Finsky  ( 6579): [1065] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6579): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/PreloadUpdateManagerStateMachine( 7790): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7790): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7790): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7790): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7790): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7790): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7790): entry::IDLE
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,D/SSRM:m  (  884): SIOP:: AP = 340, PST = 358, CUR = 450
,E/SMD     (  292): DCD ON
,W/Atfwd_Sendcmd(  342): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  292): DCD ON
,I/ActivityManager(  884): Waited long enough for: ServiceRecord{8668e42 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,W/ContextImpl(  884): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,E/Watchdog(  884): !@Sync 4
,E/SMD     (  292): DCD ON
,V/AlarmManager(  884): waitForAlarm result :4
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  884): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  884): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  884): stay LED for fully charged
D/BatteryService(  884): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  884):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  884): Plugged
I/MotionRecognitionService(  884): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  884): SIOP:: AP = 320, PST = 349, CUR = 450
,I/PowerManagerService(  884): [PWL] Off : 30s ago
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,W/Atfwd_Sendcmd(  342): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  884): SIOP:: AP = 310, PST = 344, CUR = 450
,I/art     (  884): Explicit concurrent mark sweep GC freed 60374(3MB) AllocSpace objects, 14(224KB) LOS objects, 30% free, 35MB/51MB, paused 2.202ms total 245.251ms
,E/SMD     (  292): DCD ON
,W/ContextImpl(  884): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  884): [PWL] Off : 50s ago
,D/BatteryService(  884): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  884): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  884): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  884):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  884): Plugged
,I/MotionRecognitionService(  884): setPowerConnected  = true
,D/BatteryService(  884): stay LED for fully charged
,D/SSRM:m  (  884): SIOP:: AP = 300, PST = 340, CUR = 450
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  342): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  292): DCD ON
,E/Watchdog(  884): !@Sync 5
,E/SMD     (  292): DCD ON
,D/BatteryService(  884): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  884): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  884): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  884):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  884): Plugged
,I/MotionRecognitionService(  884): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  884): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  884): SIOP:: AP = 300, PST = 336, CUR = 450
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON,
,W/ContextImpl(  884): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,V/AlarmManager(  884): waitForAlarm result :8
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  884): SIOP:: AP = 290, PST = 331, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  884): [PWL] Off : 75s ago
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,D/ConnectivityService(  884): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  884): SIOP:: AP = 290, PST = 327, CUR = 450
,W/Atfwd_Sendcmd(  342): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  292): DCD ON
,W/ContextImpl(  884): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,E/Watchdog(  884): !@Sync 6
,E/SMD     (  292): DCD ON
,I/ClearcutLoggerApiImpl( 2256): disconnect managed GoogleApiClient
,D/BatteryService(  884): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  884): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  884): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  884):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  884): Plugged
,I/MotionRecognitionService(  884): setPowerConnected  = true
,D/BatteryService(  884): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/SSRM:m  (  884): SIOP:: AP = 290, PST = 322, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/BatteryService(  884): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  884): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  884): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  884):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  884): Plugged
,I/MotionRecognitionService(  884): setPowerConnected  = true
,D/BatteryService(  884): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/SSRM:m  (  884): SIOP:: AP = 290, PST = 314, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,E/SMD     (  292): DCD ON
,W/ContextImpl(  884): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  884): [PWL] Off : 105s ago
,I/Atfwd_Sendcmd(  342): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  342): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/BatteryService(  884): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  884): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  884): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  884):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  884): Plugged
,I/MotionRecognitionService(  884): setPowerConnected  = true
,D/BatteryService(  884): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/SSRM:m  (  884): SIOP:: AP = 290, PST = 302, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,E/Watchdog(  884): !@Sync 7
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  342): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager(  884): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/SSRM:m  (  884): SIOP:: AP = 290, PST = 297, CUR = 450
,D/BatteryService(  884): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  884): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  884): stay LED for fully charged
,D/BatteryService(  884): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  884):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  884): Plugged
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3237): Disconnected process message: 10
,I/MotionRecognitionService(  884): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  292): DCD ON
,W/ContextImpl(  884): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,V/AlarmManager(  884): waitForAlarm result :8
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  342): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  884): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  884): [PWL] Off : 140s ago
,E/SMD     (  292): DCD ON
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,D/SSRM:m  (  884): SIOP:: AP = 290, PST = 292, CUR = 450
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,W/ContextImpl(  884): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  342): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  342): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  292): DCD ON
,E/Watchdog(  884): !@Sync 8
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  884): SIOP:: AP = 290, PST = 291, CUR = 450

```
