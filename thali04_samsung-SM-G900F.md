#### Test 549702617cfd775_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
D/Compatibility( 7305): onReceive() it will make start service
D/Compatibility( 7305): onHandleIntent()
D/Compatibility( 7305): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10356, android.intent.extra.user_handle=0}]
D/Compatibility( 7305): found: 2
I/UpdateIcingCorporaServi( 1561): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
--------- beginning of system
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
D/Compatibility( 7305): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7305): skipping ResolveInfo{23155485 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7305): considering ResolveInfo{13b3b2da com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
E/Zygote  ( 7325): MountEmulatedStorage()
E/Zygote  ( 7325): v2
D/Compatibility( 7305): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7305): enabling receiver ResolveInfo{129dc30b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/libpersona( 7325): KNOX_SDCARD checking this for 1000
I/libpersona( 7325): KNOX_SDCARD not a persona
I/ActivityManager(  925): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7325 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7325): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7325): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7325): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 7305): enabling receiver ResolveInfo{241b95e8 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7305): enabling receiver ResolveInfo{20dbb401 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7305): enabling receiver ResolveInfo{282a22a6 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7305): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 7325): TimaSignature is unavailable
D/ActivityThread( 7325): Added TimaKeyStore provider
I/ActivityManager(  925): Killing 6423:com.samsung.android.app.FileShareServer/u0a74 (adj 15): bgCount ##41
D/ResourcesManager( 7325): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
D/ResourcesManager( 1561): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/UpdateIcingCorporaServi( 1561): UpdateCorporaTask done [took 80 ms] updated apps [took 80 ms] 
W/ContextImpl( 7325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
W/libprocessgroup(  925): failed to open /acct/uid_10074/pid_6423/cgroup.procs: No such file or directory
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7343): MountEmulatedStorage()
E/Zygote  ( 7343): v2
I/libpersona( 7343): KNOX_SDCARD checking this for 10097
I/libpersona( 7343): KNOX_SDCARD not a persona
I/ActivityManager(  925): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7343 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  321): Explicit concurrent mark sweep GC freed 8748(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 284us total 10.762ms
I/SELinux ( 7343): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7343): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7343): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 261us total 8.271ms
I/ActivityManager(  925): Killing 6446:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 8.301ms
D/TimaKeyStoreProvider( 7343): TimaSignature is unavailable
D/ActivityThread( 7343): Added TimaKeyStore provider
D/ResourcesManager( 7343): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/libprocessgroup(  925): failed to open /acct/uid_1000/pid_6446/cgroup.procs: No such file or directory
D/DocsApplication( 7343): Installing DEX configuration.
D/DexInstaller( 7343): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7343): Provided clientMode=RELEASE, packageInfo=PackageInfo{229515fc com.google.android.apps.docs}
D/TAG     ( 7343): onCreate()
D/CrossAppStateProvider( 7343): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/AndroidRuntime( 7350): 
D/AndroidRuntime( 7350): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7350): CheckJNI is OFF
D/AndroidRuntime( 7350): setted country_code = Poland
D/AndroidRuntime( 7350): setted countryiso_code = PL
D/AndroidRuntime( 7350): setted sales_code = XEO
D/AndroidRuntime( 7350): readGMSProperty: start
D/AndroidRuntime( 7350): readGMSProperty: already setted!!
D/AndroidRuntime( 7350): readGMSProperty: end
D/AndroidRuntime( 7350): addProductProperty: start
E/AffinityControl( 7350): AffinityControl: registerfunction enter
D/AndroidRuntime( 7350): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  925): inState():  stateMachine is null !!
V/ApplicationPolicy(  925): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  925): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  925): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  925): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 925  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  925): mDVFSHelper.acquire()
I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
I/DBG_DM  ( 3685): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
I/SQLiteSecureOpenHelper( 3485): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3485): getDatabaseLocked(b,b,pwd)...
I/DBG_DM  ( 3685): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 29
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
I/DBG_DM  ( 3685): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/AndroidRuntime( 7350): Shutting down VM
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
I/DBG_DM  ( 3685): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3685): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
I/DBG_DM  ( 3685): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
I/DBG_DM  ( 3685): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
I/DBG_DM  ( 3685): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
V/AlarmManager(  925): waitForAlarm result :4
I/DBG_DM  ( 3685): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 3685): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/LightsService(  925): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 925) 
D/LightsService(  925): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  925): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  925): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SecContentProvider2(  925): uri = 14 selection = getSealedState
D/SecContentProvider2(  925): mCursor = null
D/SecContentProvider2(  925): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1186): Icon Only
D/ApplicationPolicy(  925): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  925): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager(  925): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 3685): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
D/PowerManagerService(  925): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  925): Nap time (uid 1000)...
I/PowerManagerService(  925): !@[ps] Screen__Off(2) : 
D/InputManager-JNI(  925): setDeviceInteractive: 0
I/PowerManagerService(  925): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  925): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  925): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService(  925): handleSandman : startDream()
E/PowerManagerService(  925): handleSandman : startDreaming, but isDreaming false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
I/PowerManagerService(  925): Sleeping (uid 1000)...
D/PanelView( 1186): There is/are notification(s) 
D/PowerManagerService(  925): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  925): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  925): [input device light] handleInputDeviceLightOff
D/PanelView( 1186): There is/are notification(s) 
I/SurfaceFlinger(  257): id=16 createSurf (1080x1920),2 flag=404, ColorFade
D/InputManager-JNI(  925): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI(  925): sysfs_write +: /sys/class/input/event2/device/enabled: 0
V/BitmapFactory( 1186): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
D/InputManager-JNI(  925): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI(  925): sysfs_write -: /sys/class/input/event2/device/enabled: 0
I/DBG_DM  ( 3685): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
D/SContextService(  925): 	.unregisterCallback : 1, client=
D/SContextService(  925): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3a3bb6d1, Service = Auto Rotation, used = 1
W/CAE     (  925): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
I/DBG_DM  ( 3685): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
V/CAE     (  925): stop(ContextProvider.java:149)
V/CAE     (  925): clear(AutoRotationRunner.java:182)
V/CAE     (  925): disable(AutoRotationRunner.java:171)
I/CAE     (  925): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  925): SendSensorHubData: send data = -78, 7, 0, 0
D/Sensorhubs(  305): sendContextData: -78, 7, 0, 0
I/DBG_DM  ( 3685): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
V/BitmapFactory( 1186): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
D/KnoxNotification( 1186): ----- inflateViews : modified publicViewLocal -----
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
D/CAE     (  925): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  925): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
D/KnoxNotification( 1186): ----- inflateViews : modified KnoxViewLocal -----
I/libpersona( 7376): KNOX_SDCARD checking this for 10356
E/Zygote  ( 7376): MountEmulatedStorage()
I/libpersona( 7376): KNOX_SDCARD not a persona
E/Zygote  ( 7376): v2
I/ActivityManager(  925): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7376 uid=10356 gids={50356, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/CAE     (  925): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
I/CAE     (  925): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  925): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  925): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  925): removeSContextService() : service = Auto Rotation
D/SContextService(  925): ===== SContext Service List =====
D/SContextManager(  925):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@27fd86ef, service=Auto Rotation
I/SELinux ( 7376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/PersonaManager( 1186): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1186): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@20358634
D/SecContentProvider2(  925): uri = 14 selection = getSealedState
D/SecContentProvider2(  925): mCursor = null
I/SELinux ( 7376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/SecContentProvider2(  925): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1186): Icon Only
E/SELinux ( 7376): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/KeyguardViewMediator( 1186): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1186): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1186): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1186): notifyScreenOffLocked
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/KeyguardViewMediator( 1186): timeout : 5000
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/BatteryService(  925): level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  925): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  925): Sending ACTION_BATTERY_CHANGED.
D/LightsService(  925): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 925) 
D/LightsService(  925): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/LightsService(  925): [SvcLED]  onSensorChanged::light value = 3
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/PanelView( 1186): There is/are notification(s) 
D/PanelView( 1186): There is/are notification(s) 
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/SensorManager(  925): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  925): unregisterListener ::   
,D/lights  (  925): led_pattern : 5 +
,D/BatteryService(  925): turn on LED for fully charged
,D/lights  (  925): led_pattern : 5 -
,D/LightsService(  925): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/MotionRecognitionService(  925):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  925): Plugged
,I/MotionRecognitionService(  925): setPowerConnected  = true
,D/DisplayPowerController(  925): ColorFade: onAnimationStart
,D/DisplayPowerController(  925): getFinalBrightness : 8 -> 0
,D/TimaKeyStoreProvider( 7376): TimaSignature is unavailable
,D/ActivityThread( 7376): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,D/DisplayPowerController(  925): getFinalBrightness : 8 -> 0
D/lights  (  925): lcd : 0 +
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/StatusBarManagerService(  925): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/lights  (  925): lcd : 0 -
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,I/CAE     (  925): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  925): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CAE     (  925): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  925): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  305): sendContextData: -76, 13, -46, 0
,D/ResourcesManager( 7376): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/CAE     (  925): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 14, 2, 53,
D/SensorHubManager(  925): SendSensorHubData: send data = -63, 14, 14, 2, 53
,D/Sensorhubs(  305): sendContextData: -63, 14, 14, 2, 53
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,V/ActivityManager(  925): Display changed displayId=0
,D/MotionRecognitionService(  925):   mReceiver.onReceive : ACTION_SCREEN_OFF
E/MotionRecognitionService(  925):  handler : SCREEN_OFF end 
D/WifiStateMachine(  925): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  925): handleScreenStateChanged Exit: false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
E/WifiStateMachine(  925): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
E/WifiStateMachine(  925): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  925): do suspend true
D/NotificationService(  925): ACTION_SCREEN_OFF
D/LightsService(  925): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 925) 
D/LightsService(  925): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService(  925): [SvcLED]  onSensorChanged::light value = 3
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,I/art     ( 1186): Explicit concurrent mark sweep GC freed 57002(3MB) AllocSpace objects, 4(268KB) LOS objects, 30% free, 36MB/52MB, paused 576us total 139.057ms
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/KeyguardViewMediator( 1186): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1186): handleNotifyScreenOff
D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SensorManager(  925): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  925): unregisterListener ::   
D/LightsService(  925): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,I/SQLiteSecureOpenHelper( 3485): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3485): getDatabaseLocked(b,b,pwd)...
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=off
V/voice   (  295): voice_set_parameters: enter: screen_state=off
V/voice   (  295): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  295): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  295): adev_set_parameters: exit
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,I/SecExternalDisplayIntents_Java(  925): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,D/IpRemoteDisplayController(  925): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  925): Bridge Server is not available
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,I/WebViewFactory( 7376): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7376): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/VolumePanel( 1186): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1186): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1186): mCoverBroadcastReceiver: Screen OFF end
,D/VolumePanel( 1186): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/DisplayPowerState(  925): !@ ColorFade entry
D/DisplayPowerController(  925): ColorFade: onAnimationEnd
,I/LibraryLoader( 7376): Loading: webviewchromium
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,I/LibraryLoader( 7376): Time to load native libraries: 4 ms (timestamps 5881-5885)
,I/LibraryLoader( 7376): Expected native library version number "",actual native library version number ""
,D/AutomaticBrightnessController(  925): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  925): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  925): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/AutomaticBrightnessController(  925): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  925): Light old sensor_state 513, new sensor_state : 1 en : 0
,D/PersonaManagerService(  925): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  925): MSG_ACTION_SCREEN_OFF called
,D/SensorManager(  925): unregisterListener ::   
,E/Sensors (  925): Acc old sensor_state 1, new sensor_state : 0 en : 0
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/SensorManager(  925): unregisterListener ::   
,D/NfcService( 1468): call the applyRotuiing
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/9)
,V/WebViewChromiumFactoryProvider( 7376): Binding Chromium to main looper Looper (main, tid 1) {20dbb401}
,I/LibraryLoader( 7376): Expected native library version number "",actual native library version number ""
I/chromium( 7376): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,I/BrowserStartupController( 7376): Initializing chromium process, renderers=0
,W/art     ( 7376): Attempt to remove local handle scope entry from IRT, ignoring
,D/DisplayPowerController(  925): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  925): getFinalBrightness : 0 -> 0
I/DisplayManagerService(  925): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  257): hwc_blank: Blanking display: 0
,V/ActivityManager(  925): Display changed displayId=0
,W/chromium( 7376): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7376): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 7376): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/STATUSBAR-PhoneStatusBar( 1186):      ACTION_SCREEN_OFF is finished!!!! 
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,E/StatusBar( 1186): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1186): dismissHelpPopup 
,D/StatusBar.NetworkController( 1186): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/Adreno-EGL( 7376): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7376): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7376): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7376): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7376): Remote Branch: 
I/Adreno-EGL( 7376): Local Patches: 
I/Adreno-EGL( 7376): Reconstruct Branch: 
D/accuweather( 2217): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2217): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2217): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,W/chromium( 7376): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7376): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/SystemBroadcastReceiver( 6217): [#DCM#] [DCM_Performance] onReceive completed in time  333 microsec. 
,I/SystemBroadcastReceiver( 6217): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 6217): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 6217): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,W/art     ( 7376): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  925): getTasks: caller 10085 does not hold GET_TASKS; limiting output
,W/AwContents( 7376): onDetachedFromWindow called when already detached. Ignoring
,D/SSRM:m  (  925): SIOP:: AP = 340, PST = 350, CUR = 450
,W/ActivityManager(  925): getTasks: caller 10085 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  925): [PWL] sb release: PowerManagerService.Broadcasts
,I/rmt_storage(  277): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
,I/rmt_storage(  277): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  277): wakelock acquired: 1, error no: 42
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
,D/SystemWebViewEngine( 7376): CordovaWebView is running on device made by: samsung
,W/art     ( 7376): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7376): Attempt to remove local handle scope entry from IRT, ignoring
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  277): 
I/rmt_storage(  277): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
D/Activity( 7376): performCreate Call secproduct feature valuefalse
D/Activity( 7376): performCreate Call debug elastic valuetrue
W/ActivityManager(  925): Activity pause timeout for ActivityRecord{1e1c749b u0 com.test.thalitest/.MainActivity t4}
I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  257): hwc_blank: Done blanking display: 0
D/SurfaceControl(  925): Excessive delay in setPowerMode(): 288ms
D/PowerManagerService(  925): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  925): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  925): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL(  925): Got set_interactive hint
I/PowerManagerService(  925): [PWL] Off : 0s ago
I/PowerManagerService(  925): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  925): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  925): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=925, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=747)
I/PowerManagerService(  925): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=925, ws=null) (elapsedTime=651)
I/PowerManagerService(  925): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  925): [PWL]     mDisplayReady : false
D/DisplayPowerController(  925): getFinalBrightness : 0 -> 0
D/PowerManagerService(  925): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  925): [PWL] sb release: PowerManagerService.Display
D/OpenGLRenderer( 7376): Render dirty regions requested: true
D/ActivityManager(  925): post active user change for 0
D/KnoxTimeoutHandler(  925): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  925): handleActiveUserChange for user 0
I/SurfaceFlinger(  257): id=17 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
I/OpenGLRenderer( 7376): Initialized EGL, version 1.4
I/OpenGLRenderer( 7376): HWUI protection enabled for context ,  &this =0xaf34fb28 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7376): Enabling debug mode 0
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/InputMethodManagerService(  925): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  925): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/CustomFrequencyManagerService(  925): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 925  tag : ACTIVITY_RESUME_BOOSTER@6
W/IInputConnectionWrapper( 7376): showStatusIcon on inactive InputConnection
W/ActivityManager(  925): mDVFSHelper.release()
I/Timeline(  925): Timeline: Activity_windows_visible id: ActivityRecord{1e1c749b u0 com.test.thalitest/.MainActivity t4} time:106340
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
I/Timeline( 7376): Timeline: Activity_idle id: android.os.BinderProxy@17544918 time:106340
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
I/SurfaceFlinger(  257): id=15 Removed Starting com.test.thalitest (7/9)
I/SurfaceFlinger(  257): id=15 Removed Starting com.test.thalitest (-2/9)
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/JsMessageQueue( 7376): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 7376): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7376): 
E/SMD     (  287): DCD ON
D/jxcore_app_log( 7376): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1645930496
D/JX-Cordova( 7376): jxcore cordova android initializing
D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7437): MountEmulatedStorage()
E/Zygote  ( 7437): v2
I/libpersona( 7437): KNOX_SDCARD checking this for 10098
I/libpersona( 7437): KNOX_SDCARD not a persona
I/ActivityManager(  925): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7437 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  925): Killing 6486:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
I/SELinux ( 7437): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7437): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7437): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/GAV2    ( 7343): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/TimaKeyStoreProvider( 7437): TimaSignature is unavailable
D/ActivityThread( 7437): Added TimaKeyStore provider
W/libprocessgroup(  925): failed to open /acct/uid_1000/pid_6486/cgroup.procs: No such file or directory
D/ResourcesManager( 7437): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
W/ResourcesManager( 7437): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/[CarMode]( 7437): [DLApplication]-onCreate: Applicatino Started!
D/SampleAppCoreManager( 7437): SampleAppCoreManager VACVersion '2.2.0.11867'
I/VlingoAndroidCore( 7437): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7461): MountEmulatedStorage()
E/Zygote  ( 7461): v2
I/libpersona( 7461): KNOX_SDCARD checking this for 10032
I/libpersona( 7461): KNOX_SDCARD not a persona
I/ActivityManager(  925): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7461 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7461): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7461): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7461): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7461): TimaSignature is unavailable
D/ActivityThread( 7461): Added TimaKeyStore provider
D/ResourcesManager( 7461): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/ResourcesManager( 7461): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/System.out( 7461): Inside onCreate() of WakeupTriggerProvide
I/System.out( 7461): Inside WakeupProvider
E/DatabaseUtils( 7461): Writing exception to parcel
E/DatabaseUtils( 7461): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7461): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7461): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7461): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7461): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7461): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7461): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7461): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7461): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7461): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7461): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7437): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
I/VlingoApplication( 7461): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
W/System.err( 7437): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7437): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7437): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7437): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7437): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7437): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7437): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7437): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7437): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7437): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7437): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7437): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7437): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7437): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7437): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7437): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7437): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7437): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7437): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7437): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7437): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7437): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7437): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7437): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7437): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7437): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7437): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7437): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7437): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7437): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/GAV2    ( 7343): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
E/DatabaseUtils( 7461): Writing exception to parcel
E/DatabaseUtils( 7461): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7461): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7461): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7461): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7461): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7461): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7461): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7461): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7461): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7461): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7461): 	at android.os.Binder.execTransact(Binder.java:446)
I/VlingoAndroidCore( 7461): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
W/System.err( 7437): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 7437): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7437): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7437): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7437): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7437): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7437): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7437): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7437): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7437): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7437): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7437): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7437): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7437): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7437): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7437): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 7437): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7437): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7437): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7437): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7437): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7437): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7437): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7437): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7437): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7437): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7437): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7437): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 7437): [DLApplication]-Init Called!:false
E/[CarMode]( 7437): [DLApplication]-Init Started!:true
I/[CarModeFW]( 7437): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7437): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7437): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7437): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7437): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7437): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7437): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7437): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7437): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7437): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7437): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7437): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7437): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7437): ### com.android.internal.os.ZygoteInit::main(1194)
I/MessageDataHandler( 7437): initialize
D/[CarModeFW]( 7437): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 7437): CDH-initiazlieCaches : after sync
D/[CarModeFW]( 7437): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7437): CDH-ContactDataHandler initiazlieCaches time : 29
D/[CarModeFW]( 7437): CDH-initiazlieCaches : end sync
D/[CarModeFW]( 7437): DrivingManager-initialize...
I/SensorService(  925): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  925): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  925): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
D/VlingoApplication( 7461): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 7461): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
I/MediaPlayer( 7437): Need to enable context aware info
V/MediaPlayer-JNI( 7437): native_setup
V/MediaPlayer( 7437): constructor
V/MediaPlayer( 7437): setListener
E/MediaPlayer-JNI( 7437): QCMediaPlayer mediaplayer NOT present
D/[CarModeFW]( 7437): PushMessageManager-bindPushMessageService
I/[CarModeFW]( 7437): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode]( 7437): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarModeFW]( 7437): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1452520974992
D/[CarMode]( 7437): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 7437): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1452520974992
D/[CarModeFW]( 7437): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1452520974993
D/[CarModeFW]( 7437): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1452520974993
D/[CarModeFW]( 7437): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1452520974993
D/[CarModeFW]( 7437): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1452520974992
I/[CarMode]( 7437): [LogNotNull]-Package name is: com.google.android.apps.maps
D/TP/SmsProvider( 1483): query,matched:2, calling pid = 7437
D/TP/SmsProvider( 1483): query,matched:2, calling pid = 7437
D/TP/SmsProvider( 1483): match 2:Elapsed time : 1.896 ms
D/TP/SmsProvider( 1483): match 2:Elapsed time : 1.876 ms
D/[CarModeFW]( 7437): CDH-buildContactCacheWireFrame : cur len =0
E/[CarMode]( 7437): [DLApplication]-Init End!:true
D/[CarModeFW]( 7437): RecommendHandler-selection = type = '3'
D/MessageDataHandler( 7437):  getInboxList smsCursor : 16
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
D/TP/MmsProvider( 1483): Query uri=content://mms/inbox, match=2, calling pid = 7437
E/Zygote  ( 7495): MountEmulatedStorage()
I/libpersona( 7495): KNOX_SDCARD checking this for 10019
E/Zygote  ( 7495): v2
I/libpersona( 7495): KNOX_SDCARD not a persona
I/ActivityManager(  925): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7495 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
I/SELinux ( 7495): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/MessageDataHandler( 7437):  getInboxList mmsCursor : 79
I/SELinux ( 7495): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7495): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/TP/MmsProvider( 1483): Query uri=content://mms, match=0, calling pid = 7437
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
D/[CarMode]( 7437): [DLApplication]-GooglePlayServices SUCCESS.
E/Zygote  ( 7509): MountEmulatedStorage()
E/Zygote  ( 7509): v2
I/libpersona( 7509): KNOX_SDCARD checking this for 10003
I/libpersona( 7509): KNOX_SDCARD not a persona
I/ActivityManager(  925): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7509 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
E/[CarMode]( 7437): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
I/UpdateManagerReceiver( 7437): Intent : android.intent.action.PACKAGE_ADDEDMon Jan 11 15:02:55 GMT+01:00 2016
I/SELinux ( 7509): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
I/SELinux ( 7509): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/SELinux ( 7509): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 7495): TimaSignature is unavailable
D/ActivityThread( 7495): Added TimaKeyStore provider
E/Zygote  ( 7519): MountEmulatedStorage()
E/Zygote  ( 7519): v2
I/libpersona( 7519): KNOX_SDCARD checking this for 1000
I/libpersona( 7519): KNOX_SDCARD not a persona
I/ActivityManager(  925): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7519 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7519): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7519): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7519): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7509): TimaSignature is unavailable
D/ActivityThread( 7509): Added TimaKeyStore provider
D/MessageDataHandler( 7437):  getInboxList mms,sms cursor join : 140
I/ActivityManager(  925): Killing 5605:com.sec.android.app.samsungapps/u0a39 (adj 15): bgCount ##41
D/[CarModeFW]( 7437): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7437): RecommendHandler-selection = type = '3'
D/[CarModeFW]( 7437): PushMessageService-onCreate
D/TP/MmsSmsProvider( 1483): query,matched:0, calling pid = 7437
V/TP/MmsSmsProvider( 1483): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1483): match 0:Elapsed time : 2.301 ms
D/TimaKeyStoreProvider( 7519): TimaSignature is unavailable
I/MessageDataHandler( 7437): getUnreadMessageCount :0
D/ActivityThread( 7519): Added TimaKeyStore provider
D/[CarModeFW]( 7437): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 270
D/ResourcesManager( 7509): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
I/ActivityManager(  925): Killing 6275:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
I/ActivityManager(  925): Killing 6217:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##42
I/ActivityManager(  925): Killing 5968:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##43
D/TP/MmsSmsProvider( 1483): query,matched:13, calling pid = 7437
D/TP/MmsSmsProvider( 1483): match 13:Elapsed time : 1.277 ms
D/[CarModeFW]( 7437): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7437): PushMessageService-registerPushMessageServiceListener
D/[CarModeFW]( 7437): CDH-buildContactCacheWireFrame : cur len =0
D/MessageDataHandler( 7437):  getInboxList address cursor : 9
D/TP/MmsSmsProvider( 1483): query,matched:0, calling pid = 7437
V/TP/MmsSmsProvider( 1483): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1483): match 0:Elapsed time : 1.110 ms
D/MessageDataHandler( 7437):  getInboxList thread cursor : 6
D/MessageDataHandler( 7437):  thread, addr result: 3
I/[CarModeFW]( 7437): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 308
I/[CarModeFW]( 7437): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7437): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 308
D/ResourcesManager( 7519): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
D/ResourcesManager( 7495): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
D/UserAnalysis.PlaceProvider( 7509): PlaceProvider onCreate()
W/ContextImpl( 7519): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
D/UserAnalysis.SecureDbManager( 7509): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 7509): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7509): Create SecureDbHelper
I/art     (  925): Explicit concurrent mark sweep GC freed 229858(15MB) AllocSpace objects, 5(5MB) LOS objects, 30% free, 36MB/52MB, paused 1.392ms total 108.895ms
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7542): MountEmulatedStorage()
I/libpersona( 7542): KNOX_SDCARD checking this for 10111
E/Zygote  ( 7542): v2
I/libpersona( 7542): KNOX_SDCARD not a persona
D/IntelligenceServiceApplication( 7509): onCreate()
I/ActivityManager(  925): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7542 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7542): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7542): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7542): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SQLiteSecureOpenHelper( 7509): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7509): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7509): Open Place.db in secure mode
,D/ResourcesManager( 7519): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/TimaKeyStoreProvider( 7542): TimaSignature is unavailable
,D/ActivityThread( 7542): Added TimaKeyStore provider
,D/ResourcesManager( 7542): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,E/FilterInstaller( 7519): There is no requred permission
,I/ActivityManager(  925): Killing 5926:com.google.android.gm/u0a113 (adj 15): bgCount ##41
,I/SQLiteSecureOpenHelper( 7509): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7509): ...getDatabaseLocked(b,b,pwd)
,I/[CarModeFW]( 7437): -[snowdeer] Rec : Missed Call : 602
,D/[CarModeFW]( 7437): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 7437): MyPlaceProvider-=============
D/[CarModeFW]( 7437): MyPlaceProvider-=============
D/[CarModeFW]( 7437): MyPlaceProvider-=============
,D/[CarModeFW]( 7437): MyPlaceProvider-=============
D/[CarModeFW]( 7437): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7437): MyPlaceProvider-==============
D/[CarModeFW]( 7437): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7437): MyPlaceProvider-==============
D/[CarModeFW]( 7437): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7437): MyPlaceProvider-==============
D/[CarModeFW]( 7437): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 7437): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 623
,D/[CarModeFW]( 7437): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 626
,D/[CarMode]( 7437): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@92caf809, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@69879dcb] LOCATIONS
,I/[CarModeFW]( 7437): -[snowdeer] Rec : Favorite : 13
,I/[CarModeFW]( 7437): -[snowdeer] Rec : CallLog : 6
,D/PackageIntentReceiver( 7542): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7542): Not GearManger package! 
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  925): failed to open /acct/uid_10039/pid_5605/cgroup.procs: No such file or directory
W/libprocessgroup(  925): failed to open /acct/uid_10167/pid_5968/cgroup.procs: No such file or directory
W/libprocessgroup(  925): failed to open /acct/uid_10004/pid_6217/cgroup.procs: No such file or directory
W/libprocessgroup(  925): failed to open /acct/uid_10043/pid_6275/cgroup.procs: No such file or directory
,E/Zygote  ( 7557): MountEmulatedStorage()
,E/Zygote  ( 7557): v2
I/libpersona( 7557): KNOX_SDCARD checking this for 10117
I/libpersona( 7557): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7557 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  925): Killing 6179:com.google.android.music:main/u0a125 (adj 15): bgCount ##41
,W/jxcore-log( 7376): Initializing JXcore engine
W/jxcore-log( 7376): JXcore engine is ready
,W/jxcore-log( 7376): Starting JXcore engine
,I/SELinux ( 7557): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7557): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7557): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/Atfwd_Sendcmd(  348): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  348): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/[CarModeFW]( 7437): -[snowdeer] Rec : Schedule : 122
,I/[CarModeFW]( 7437): -[snowdeer] Rec : During DL app : 7
,D/TimaKeyStoreProvider( 7557): TimaSignature is unavailable
,D/ActivityThread( 7557): Added TimaKeyStore provider
,I/[CarModeFW]( 7437): -[snowdeer] Rec : Location Sharing : 9
,I/[CarModeFW]( 7437): -[snowdeer] Rec : POI : 0
,I/[CarModeFW]( 7437): -[snowdeer] Rec : getContactListFromHashMap - core : 0
,I/[CarModeFW]( 7437): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7437): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7437): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
,I/[CarModeFW]( 7437): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 7437): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 787
,I/[CarModeFW]( 7437): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7437): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7437): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 788
,D/ResourcesManager( 7557): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 7557): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/auditd  ( 2182): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  925): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  925): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  925): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,W/libprocessgroup(  925): failed to open /acct/uid_10113/pid_5926/cgroup.procs: No such file or directory
,W/libprocessgroup(  925): failed to open /acct/uid_10125/pid_6179/cgroup.procs: No such file or directory
,D/MagazineService Version( 7557): Magazine-Administrator: 11
,D/MagazineService Version( 7557): Magazine-Provider: 14
,D/MagazineService Version( 7557): Magazine-Channel: 14
,D/HeadlinesChannelApplication( 7557): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7557): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7557): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 7573): MountEmulatedStorage()
E/Zygote  ( 7573): v2
I/libpersona( 7573): KNOX_SDCARD checking this for 1000
I/libpersona( 7573): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7573 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7557): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/System.out( 7461): INFO:Resource not found:/Common.properties Using default values
,I/SELinux ( 7573): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7573): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7573): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 7376): Platform android
W/jxcore-log( 7376): 
,W/jxcore-log( 7376): Process ARCH arm
W/jxcore-log( 7376): 
,I/ActivityManager(  925): Killing 5496:com.google.android.apps.plus/u0a134 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7573): TimaSignature is unavailable
,D/ActivityThread( 7573): Added TimaKeyStore provider
,D/ResourcesManager( 7573): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/libprocessgroup(  925): failed to open /acct/uid_10134/pid_5496/cgroup.procs: No such file or directory
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7589): MountEmulatedStorage()
E/Zygote  ( 7589): v2
I/libpersona( 7589): KNOX_SDCARD checking this for 1000
I/libpersona( 7589): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7589 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  925): Killing 6656:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
,I/SELinux ( 7589): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7589): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7589): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7589): TimaSignature is unavailable
,D/ActivityThread( 7589): Added TimaKeyStore provider
,D/ResourcesManager( 7589): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,W/libprocessgroup(  925): failed to open /acct/uid_10011/pid_6656/cgroup.procs: No such file or directory
,D/AcmsPackageEventListener( 7589): Received: android.intent.action.PACKAGE_ADDED
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 7589): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,E/Zygote  ( 7607): MountEmulatedStorage()
E/Zygote  ( 7607): v2
I/libpersona( 7607): KNOX_SDCARD checking this for 10134
I/libpersona( 7607): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7607 uid=10134 gids={50134, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  925): Killing 6507:com.android.vending/u0a29 (adj 15): bgCount ##41
,I/art     (  321): Explicit concurrent mark sweep GC freed 8758(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 274us total 13.777ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.449ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 8.234ms
,I/SELinux ( 7607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7607): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/AcmsService( 7589): Enter Oncreate
,D/AcmsServiceMonitor( 7589): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 7589): creating AcmsCore
,D/AcmsCore( 7589): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7589): AcmsCore
,D/AcmsCore( 7589): init
,D/AcmsCore( 7589): Looper handler is not null
D/AcmsCore( 7589): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7589): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7589): Incrementing - Counter value: 1
,D/AcmsCore( 7589): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 7589): onStartCommand
D/AcmsService( 7589): Action: android.intent.action.PACKAGE_ADDED
,D/AcmsServiceMonitor( 7589): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7589): Incrementing - Counter value: 2
D/AcmsService( 7589): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr( 7589): AcmsCertificateMngr
,D/AcmsRevocationMngr( 7589): AcmsRevocationMngr
D/ActivityThread( 7589): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/TimaKeyStoreProvider( 7607): TimaSignature is unavailable
,D/ActivityThread( 7607): Added TimaKeyStore provider
,W/libprocessgroup(  925): failed to open /acct/uid_10029/pid_6507/cgroup.procs: No such file or directory
,D/ResourcesManager( 7607): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager( 7607): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsService( 7589): Inside handle Intent
D/AcmsService( 7589): App added - package name: com.test.thalitest
D/AcmsCore( 7589): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7589): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7589): Incrementing - Counter value: 3
D/AcmsCore( 7589): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7589): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7589): Decrementing - Counter value: 2
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 7376): JXcore Cordova bridge is ready!
I/jxcore-log( 7376): 
,W/jxcore-log( 7376): JXcore engine is started
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 7376): Toggling radios to true
I/jxcore-log( 7376): 
,D/BluetoothAdapter( 7376): enable()
,E/Zygote  ( 7638): MountEmulatedStorage()
E/Zygote  ( 7638): v2
I/libpersona( 7638): KNOX_SDCARD checking this for 10165
I/libpersona( 7638): KNOX_SDCARD not a persona
D/BluetoothAdapter( 7376): enable(): BT is already enabled..!
,I/ActivityManager(  925): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7638 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7638): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7638): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/WifiService(  925): New client listening to asynchronous messages
E/SELinux ( 7638): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/WifiManager( 7376): packageName : com.test.thalitest
,D/SecContentProvider(  925): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  925): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  925): mCursor = null
,D/WifiService(  925): setWifiEnabled: true pid=7376, uid=10356
E/WifiService(  925): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  925): Permission Denial: getCurrentUser() from pid=7376, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  925): Failed getting userId using ActivityManagerNative
W/WifiService(  925): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7376, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  925): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  925): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  925): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  925): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  925): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  925): name = wifi_on
,I/WifiService(  925): disconnect: pid=7376, uid=10356
,I/jxcore-log( 7376): Radios toggled
I/jxcore-log( 7376): 
,I/wpa_supplicant( 1314): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7376): My device name is: samsung-SM-G900F
I/jxcore-log( 7376): 
,I/wpa_supplicant( 1314): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1314): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1314): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1314): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  925): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1314): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1314): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1314): Disconnected - do not scan
I/wpa_supplicant( 1314): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/TimaKeyStoreProvider( 7638): TimaSignature is unavailable
,E/WifiStateMachine(  925): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  925): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  925): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  925): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ActivityThread( 7638): Added TimaKeyStore provider
,D/ResourcesManager( 7638): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,E/WifiStateMachine(  925): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  925): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  925): do suspend true
,W/ResourcesManager( 7638): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/WifiP2pService(  925): InactiveState{ what=143375 }
,D/WifiP2pService(  925): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,V/NativeCrypto( 2264): Read error: ssl=0x9b433e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2264): SSL shutdown failed: ssl=0x9b433e00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  925): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService(  925): updateNetworkInfo()
,D/ConnectivityService(  925): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  925): updateNetworkInfo()
D/ConnectivityService(  925): ignoring duplicate network state non-change
D/ConnectivityService(  925): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  925): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/KidsPlatformStub( 7638): Package not found : com.sec.android.app.kidshome
,I/WifiTrafficPoller(  925): evaluateTrafficStatsPolling
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  925): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  925): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,E/WifiStateMachine(  925): Start Disconnecting Watchdog 1
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
,I/wpa_supplicant( 1314): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1314): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1314): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1314): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1314): First Scan Start
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  925): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  925): DefaultState{ when=-4ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  925): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  925): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1314): Scan requested (ret=0) - scan timeout 30 seconds
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  925): Validated
,D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  925): ConnectModeState: Network connection lost 
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  925): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  925): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  925): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  925): do suspend true
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiP2pService(  925): InactiveState{ what=143375 }
D/WifiP2pService(  925): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7657): MountEmulatedStorage()
I/libpersona( 7657): KNOX_SDCARD checking this for 10169
E/Zygote  ( 7657): v2
I/libpersona( 7657): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7657 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
,D/ConnectivityService(  925): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  925): calling update connectivity
D/ConnectivityService(  925):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  925):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  925): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  925):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  925): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,I/SELinux ( 7657): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine(  925): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiStateMachine(  925): updateConfiguredNetworkExpiration - currTime: 1452520976818
D/WifiStateMachine(  925): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/ConnectivityManager.CallbackHandler( 1186): CM callback handler got msg 524292
E/WifiStateMachine(  925): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  925): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/SELinux ( 7657): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/WifiNetworkAgent(  925): NetworkAgent: NetworkAgent channel lost
,E/SELinux ( 7657): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  925): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  925): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/EntConnectivity(  925): Not allowed due to - mEnabled false
E/WifiStateMachine(  925): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  925): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  925): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  925): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  925): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  925): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  925): mCursor = null
,D/Nat464Xlat(  925): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  925): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  925): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  925): Disconnected - quitting
D/ConnectivityService(  925): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  925): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WifiTrafficPoller(  925): evaluateTrafficStatsPolling
,D/TelephonyNetworkFactory( 1483): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/CLocInfoService(  925): External Intent Received android.net.wifi.STATE_CHANGE
D/CSLegacyTypeTracker(  925): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  925): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  925): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SecContentProvider2(  925): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  925): mCursor = null
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  925): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  925): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  925): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  925): getSBEnabled() enabled =false
D/SmartBondingService(  925): getSBEnabled() enabled =false
D/SmartBondingService(  925): getSBEnabled() enabled =false
,V/NetworkStats(  925): updateIfacesLocked()
D/NtpTrustedTime(  925): currentTimeMillis() cache hit
V/NetworkStats(  925): performPollLocked(flags=0x1)
D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1186): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1186): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1186): updateDataNetType()
D/StatusBar.NetworkController( 1186): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1186): updateLTEICONDataNetType:0
,D/NetworkStatsFactory(  925): UpdateStatsForKnox
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityService(  925): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/StatusBar.NetworkController( 1186): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/SmartBondingService(  925): getNetworkEnabled : wifi : true mobile : true
D/NtpTrustedTime(  925): currentTimeMillis() cache hit
D/NtpTrustedTime(  925): currentTimeMillis() cache hit
D/NtpTrustedTime(  925): currentTimeMillis() cache hit
V/NetworkStats(  925): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  925): currentTimeMillis() cache hit
V/NetworkStats(  925): performPollLocked() took 22ms
D/NtpTrustedTime(  925): currentTimeMillis() cache hit
D/TaskPersister(  925): removeObsoleteFile: deleting file=3_task_thumbnail.png
D/NtpTrustedTime(  925): currentTimeMillis() cache hit
D/NtpTrustedTime(  925): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 2473): CM callback handler got msg 524292
,D/TimaKeyStoreProvider( 7657): TimaSignature is unavailable
,D/ActivityThread( 7657): Added TimaKeyStore provider
,D/ResourcesManager( 7657): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/FileWriteThread_Telephony( 1483): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1483): FileWriteThread : threadType = 3
,E/SQLiteLog( 7657): (284) automatic index on shooting_modes(title_id)
,D/FileWriteThread_Telephony( 1483): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1483): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1483): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1483): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1483): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1483): FileWriteThread : threadType = 3
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,D/FileWriteThread_Telephony( 1483): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1483): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1483): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1483): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1483): FileWriteThread : threadType = 3
,I/ActivityManager(  925): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7688 uid=10029 gids={50029, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7688): MountEmulatedStorage()
E/Zygote  ( 7688): v2
I/libpersona( 7688): KNOX_SDCARD checking this for 10029
I/libpersona( 7688): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Killing 6862:com.sec.android.fotaclient/u0a10 (adj 15): bgCount ##41
,I/SELinux ( 7688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/FileWriteThread_Telephony( 1483): FileWriteThread : threadType = 3
,I/SELinux ( 7688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7688): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7688): TimaSignature is unavailable
,D/ActivityThread( 7688): Added TimaKeyStore provider
,D/ResourcesManager( 7688): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/libprocessgroup(  925): failed to open /acct/uid_10010/pid_6862/cgroup.procs: No such file or directory
,D/Finsky  ( 7688): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7688): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7688): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7688): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7688): Skipping gmscore version check
,D/Finsky  ( 7688): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7688): [1] Libraries$2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 2473): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2473): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2473): Loading module APK com.google.android.play.games
,D/Finsky  ( 7688): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7688): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ResourcesManager( 2473): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ConnectivityService(  925): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  925): updateDataUsageMap
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2217): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3685): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/Tethering(  925): MasterInitialState.processMessage what=3
D/SmartBondingService(  925): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  925): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  925): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  925): getSBEnabled() enabled =false
D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  925): CLoinfo wifi false
D/SmartBondingService(  925): getSBEnabled() enabled =false
,D/SmartBondingService(  925): getSBEnabled() enabled =false
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3685): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
D/SmartBondingService(  925): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Finsky  ( 7688): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/FactoryTest( 6359): Not factory mode
D/FactoryTest( 6359): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6359): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6359): still no open session command from host, so toast
,W/SLocation(  925): No Active Data Connection
,I/ActivityManager(  925): Killing 6878:com.samsung.klmsagent/u0a18 (adj 15): bgCount ##41
,W/ContextImpl( 6359): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6359): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6359): Timeline: Activity_launch_request id:com.android.settings time:109506
,E/PersonaManagerService(  925): inState():  stateMachine is null !!
,V/ApplicationPolicy(  925): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  925): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  925): mDVFSHelper.acquire()
,V/ActivityManager(  925): Display changed displayId=0
,I/art     ( 2264): Explicit concurrent mark sweep GC freed 32606(2031KB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 20MB/33MB, paused 1.279ms total 65.643ms
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,W/DisplayManagerService(  925): Failed to notify process 6878 that displays changed, assuming it died.
W/DisplayManagerService(  925): android.os.DeadObjectException
W/DisplayManagerService(  925): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService(  925): 	at android.os.BinderProxy.transact(Binder.java:496)
W/DisplayManagerService(  925): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService(  925): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1257)
W/DisplayManagerService(  925): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1063)
W/DisplayManagerService(  925): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:131)
W/DisplayManagerService(  925): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1190)
W/DisplayManagerService(  925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService(  925): 	at android.os.Looper.loop(Looper.java:145)
W/DisplayManagerService(  925): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService(  925): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,I/SQLiteSecureOpenHelper( 3485): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3485): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,E/MTPRx   ( 6359): started activity for popup
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,W/libprocessgroup(  925): failed to open /acct/uid_10018/pid_6878/cgroup.procs: No such file or directory
,D/ResourcesManager( 6359): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6359): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6359): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6359): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 6359): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6359): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6359): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6359): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6359): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6359): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6359): dev.kiessupport is : TRUE
,D/Activity( 6359): performCreate Call secproduct feature valuefalse
D/Activity( 6359): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/ChimeraCfgMgr( 2473): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2473): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2473): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/AsyncTaskServiceImpl( 2473): Submit a task: k
,D/ChimeraCfgMgr( 2473): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 2473): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2473): Processing package: com.test.thalitest
,D/GassUtils( 2473): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
D/k       ( 2473): Found info for package com.test.thalitest in db.
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7740): MountEmulatedStorage()
E/Zygote  ( 7740): v2
I/libpersona( 7740): KNOX_SDCARD checking this for 10039
I/libpersona( 7740): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7740 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7740): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7740): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7740): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/BaseAppContext( 2473): Using Auth Proxy for data requests.
W/BaseAppContext( 2473): Using Auth Proxy for data requests.
,D/TimaKeyStoreProvider( 7740): TimaSignature is unavailable
,D/ActivityThread( 7740): Added TimaKeyStore provider
,D/ResourcesManager( 7740): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,I/PeopleDatabaseHelper( 2473): cleanUpNonGplusAccounts done.
,W/BaseAppContext( 2473): Using Auth Proxy for data requests.
,I/wpa_supplicant( 1314): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant( 1314): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1314): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1314): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1314): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  925): [1,452,520,977,845 ms] noteScanEnd no scan source
,E/WifiStateMachine(  925): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3541126d sup_state=SCANNING debouncing=false
,I/CLocInfoService(  925): External Intent Received android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine(  925): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  925): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  925): setDetailed state send new extra info0x
,D/SecContentProvider2(  925): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  925): mCursor = null
,D/BootupListener( 1483): ACTION_DRIVELINK
,D/SettingsProvider(  925): name = drivelink_navigation
D/SettingsProvider(  925): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  925): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  925): selectionArgs: false
D/SettingsProvider(  925): selectionArgs: 1001
D/SecContentProvider(  925): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  925): ret = -1
D/BootupListener( 1483): NAVI : com.google.android.apps.maps
,D/SettingsProvider(  925): name = internet_call_settings_visibility
D/SettingsProvider(  925): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  925): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  925): selectionArgs: false
D/SettingsProvider(  925): selectionArgs: 1001
,D/SecContentProvider(  925): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  925): ret = -1
,I/wpa_supplicant( 1314): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1314): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1314): Associated with C0.AA.48
,E/WifiStateMachine(  925): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  925): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  925): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  925): mCursor = null
,I/art     (  925): Explicit concurrent mark sweep GC freed 41351(2MB) AllocSpace objects, 2(32KB) LOS objects, 30% free, 36MB/52MB, paused 3.321ms total 102.803ms
,D/SecurityLogAgent( 7024):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7024):  SeDenialReceiver : File path = null
,I/ActivityManager(  925): Killing 6893:com.sec.android.soagent/u0a36 (adj 15): bgCount ##41
,I/wpa_supplicant( 1314): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1314): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  925): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  925): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  925): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  925): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  925): mCursor = null
,I/wpa_supplicant( 1314): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/Hs20UtilService( 1321): Starting #6
I/Hs20UtilService( 1321): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1321): MountReceiver.mPrefHandler - 7002
,I/wpa_supplicant( 1314): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1314): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1314): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine(  925): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
I/wpa_supplicant( 1314): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1314): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1314): Blacklist: Clear (temp) 
I/wpa_supplicant( 1314): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  925): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  925): Network connection established
,D/WifiNative-HAL(  925): callSECApiVoid - ID [50]
,E/WifiStateMachine(  925): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  925): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  925): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/BaseAppContext( 2473): Using Auth Proxy for data requests.
,I/Hs20UtilService( 1321): Starting #7
,W/libprocessgroup(  925): failed to open /acct/uid_10036/pid_6893/cgroup.procs: No such file or directory
I/Hs20UtilService( 1321): Message received 5007
D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1321): MountReceiver.mPrefHandler - 7002
W/BaseAppContext( 2473): Using Auth Proxy for data requests.
W/BaseAppContext( 2473): Using Auth Proxy for data requests.
,D/ConnectivityService(  925): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  925): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  925): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  925): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  925): Got NetworkAgent Messenger
D/ConnectivityService(  925): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  925): updateNetworkInfo()
D/ConnectivityService(  925): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  925): NetworkAgent connected
,E/WifiStateMachine(  925): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  925): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  925): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  925): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/PCWCLIENTTRACE_PushUtil( 7200): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7200): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 7200): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7200): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,D/CommandListener(  282): Setting iface cfg
E/WifiStateMachine(  925): Start Dhcp Watchdog 2
,D/SecContentProvider2(  925): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  925): mCursor = null
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7200): noConnectivity : true
,E/Zygote  ( 7760): MountEmulatedStorage()
I/libpersona( 7760): KNOX_SDCARD checking this for 10125
E/Zygote  ( 7760): v2
I/libpersona( 7760): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7760 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7760): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/BaseAppContext( 2473): Using Auth Proxy for data requests.
,I/SELinux ( 7760): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7760): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager(  925): Activity pause timeout for ActivityRecord{1e1c749b u0 com.test.thalitest/.MainActivity t4}
,D/TimaKeyStoreProvider( 7760): TimaSignature is unavailable
D/ActivityThread( 7760): Added TimaKeyStore provider
,D/ResourcesManager( 7760): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/WifiStateMachine(  925): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  925): do suspend false
,D/WifiP2pService(  925): InactiveState{ what=143375 }
,D/WifiP2pService(  925): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  925): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  925): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/SecContentProvider2(  925): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  925): mCursor = null
D/ConnectivityService(  925): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/MusicStore( 7760): Database version: 104
,D/ResourcesManager( 7760): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7760): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7760): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7760): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/dhcpcd  ( 7783): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7783): version 5.5.6 starting
,E/dhcpcd  ( 7783): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityThread( 7760): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7760): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@32d2f2cb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7760): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7760): GMSCore installation verified
,I/dhcpcd  ( 7783): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7783): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7783): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7783): bssid match
,I/dhcpcd  ( 7783): wlan0: rebinding lease of 192.168.1.136
,I/ConfigStore( 7760): Config Database version: 1
,W/art     ( 2473): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 141.249ms
,V/AlarmManager(  925): waitForAlarm result :4
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  925): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  925): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  295): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  925): getStreamVolume 3 index 0
I/MediaRouter( 7760): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7793): MountEmulatedStorage()
I/libpersona( 7793): KNOX_SDCARD checking this for 10002
E/Zygote  ( 7793): v2
I/libpersona( 7793): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7793 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7793): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7793): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7793): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter(  925): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7760): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider( 7793): TimaSignature is unavailable
,D/ActivityThread( 7793): Added TimaKeyStore provider
,I/ActivityManager(  925): Killing 6930:com.samsung.android.scloud.sync/u0a66 (adj 15): bgCount ##41
,D/ChimeraCfgMgr( 2473): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2473): Module APK com.google.android.play.games already loaded
,D/ResourcesManager( 7793): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  925): Killing 6946:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): bgCount ##41
,W/libprocessgroup(  925): failed to open /acct/uid_10066/pid_6930/cgroup.procs: No such file or directory
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7815): MountEmulatedStorage()
I/libpersona( 7815): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7815): v2
I/libpersona( 7815): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7815 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/AcmsKeyStoreHelper( 7589):  getKeyStoreForApplication Enter
,I/SELinux ( 7815): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7815): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7815): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AcmsKeyStoreHelper( 7589): Key Store exist
I/AcmsKeyStoreHelper( 7589): Hence loading the keystore file
,I/Icing   ( 2473): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,D/TimaKeyStoreProvider( 7815): TimaSignature is unavailable
,D/ActivityThread( 7815): Added TimaKeyStore provider
,D/ResourcesManager( 7815): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  925): failed to open /acct/uid_10070/pid_6946/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7815): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,D/AcmsKeyStoreHelper( 7589):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 7589): getKeyStoreForApplication success 
D/AcmsCore( 7589): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7589): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7589): Decrementing - Counter value: 1
D/AcmsCore( 7589): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 7589): This is NOT a valid MirrorLink app
D/AcmsCore( 7589): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7589): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7589): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7589): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7589): getSvcCounter - Counter value: 0
D/AcmsService( 7589): Enter onDestroy
I/AcmsService( 7589): cleanUp(): inside service clean up
D/AcmsCore( 7589): AcmsCore: inside DeInit
D/AcmsCore( 7589): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7589): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 7589): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7589): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7589): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7589): getSvcCounter - Counter value: 0
D/AcmsService( 7589): killing acms process
I/Process ( 7589): Sending signal. PID: 7589 SIG: 9
,I/DIAGMON_AGENT( 7815): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/ActivityManager(  925): Process ACMS.Process (pid 7589)(adj 0) has died(49,575)
,D/ResourcesManager( 2473): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/Icing   ( 2473): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,I/DIAGMON_AGENT( 7815): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7815): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7815): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7815): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7831): MountEmulatedStorage()
E/Zygote  ( 7831): v2
I/libpersona( 7831): KNOX_SDCARD checking this for 10010
I/libpersona( 7831): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7831 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PowerManagerService(  925): [PWL] Off : 5s ago
I/PowerManagerService(  925): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  925): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  925): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=925, ws=null) (elapsedTime=2246)
I/PowerManagerService(  925): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=925, ws=WorkSource{10058}) (elapsedTime=634)
,I/SELinux ( 7831): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7831): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7831): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7831): TimaSignature is unavailable
,D/ActivityThread( 7831): Added TimaKeyStore provider
,D/ResourcesManager( 7831): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,W/ContextImpl(  925): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  ( 7783): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,I/ActivityManager(  925): Killing 6963:com.sec.android.app.clockpackage/u0a90 (adj 15): bgCount ##41
,I/FOTA_Client( 7831): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7831): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7831): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7846): MountEmulatedStorage()
E/Zygote  ( 7846): v2
I/libpersona( 7846): KNOX_SDCARD checking this for 10018
I/libpersona( 7846): KNOX_SDCARD not a persona
,I/dhcpcd  ( 7783): wlan0: leased 192.168.1.136 for 86400 seconds
,E/WifiStateMachine(  925): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  925): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  925): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/ActivityManager(  925): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7846 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  925): Killing 6983:com.sec.esdk.elm/u0a103 (adj 15): bgCount ##41
,I/SELinux ( 7846): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7846): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7846): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  925): failed to open /acct/uid_10090/pid_6963/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7846): TimaSignature is unavailable
,D/ActivityThread( 7846): Added TimaKeyStore provider
,D/ResourcesManager( 7846): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7846): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7846): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452520979284
,I/KLMS-2.4.503: ( 7846): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7846): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/KLMS-2.4.503: ( 7846): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  925): Killing 7000:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
W/libprocessgroup(  925): failed to open /acct/uid_10103/pid_6983/cgroup.procs: No such file or directory
,E/Zygote  ( 7872): MountEmulatedStorage()
E/Zygote  ( 7872): v2
I/libpersona( 7872): KNOX_SDCARD checking this for 10036
I/libpersona( 7872): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7872 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7872): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7872): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7872): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7872): TimaSignature is unavailable
,D/ActivityThread( 7872): Added TimaKeyStore provider
,D/ResourcesManager( 7872): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7872): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,W/libprocessgroup(  925): failed to open /acct/uid_10112/pid_7000/cgroup.procs: No such file or directory
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7238): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
I/GAV2    ( 7343): Thread[GAThread,5,main]: No campaign data found.
,I/SA      ( 6909): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6909): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6909): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 6909): [SLFUCHKMGR] constructor called
,I/SA      ( 6909): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6909): [OR] == isSIMCardReady false ==
,I/SA      ( 6909): [SCU] == networkStateCheck == false
I/SA      ( 6909): [OR] onReceive END
,E/SPPClientService( 7238): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7902): MountEmulatedStorage()
,E/Zygote  ( 7902): v2
I/libpersona( 7902): KNOX_SDCARD checking this for 10070
I/libpersona( 7902): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7902 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  321): Explicit concurrent mark sweep GC freed 8715(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 274us total 11.267ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 8.328ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 8.380ms
,I/SELinux ( 7902): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7902): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7902): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  925): Killing 5634:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7902): TimaSignature is unavailable
,D/ActivityThread( 7902): Added TimaKeyStore provider
,D/ResourcesManager( 7902): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7902): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7902): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7902): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/WifiStateMachine(  925): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  925): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  925): do suspend true
,D/comsamsunglog( 7902): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7902): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7902): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7902): [KK AccuPhone]>>> ==============================================================================================
,D/WifiP2pService(  925): InactiveState{ what=143375 }
,D/WifiP2pService(  925): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  925): WifiStateMachine DHCP successful
,E/WifiStateMachine(  925): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  925): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  925): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  925): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  925): Not connected state, yet.
E/WifiStateMachine(  925): VerifyingLinkState enter
,W/libprocessgroup(  925): failed to open /acct/uid_10148/pid_5634/cgroup.procs: No such file or directory
,D/WifiStateMachine(  925): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  925): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  925): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  925): callSECApiInt - ID [210]
,E/WifiStateMachine(  925): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
D/comsamsunglog( 7902): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7902): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7902): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7902): [KK AccuPhone]>>> ==============================================================================================
,E/ConnectivityService(  925): updateNetworkInfo()
,D/ConnectivityService(  925): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  925): Adding iface wlan0 to network 503
,I/CLocInfoService(  925): External Intent Received android.net.wifi.STATE_CHANGE
D/WifiWatchdogStateMachine(  925): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger(  925): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  925): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  925): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  925): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/SettingsProvider(  925): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  925): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  925): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  925): selectionArgs: false
D/SettingsProvider(  925): selectionArgs: 10070
D/SecContentProvider(  925): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  925): ret = -1
,D/daemonapp( 1349): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ConnectivityService(  925): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  925): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  925): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  925): Unexpected mtu value: 0, wlan0
,E/WifiStateMachine(  925): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  925): Now, connected state.
E/WifiStateMachine(  925): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  925): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  925): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  925): updateSourceRoutes : add src route for:192.168.1.136
,I/WifiTrafficPoller(  925): evaluateTrafficStatsPolling
V/        (  282): QcRouteController
,I/CLocInfoService(  925): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  925): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  925): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  925): mBoosterFLAG : 0
I/WifiTrafficPoller(  925): current booster mode : FullMode
D/WifiNative-HAL(  925): callSECApiVoid - ID [212]
,I/CLocInfoService(  925): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  925): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/        (  282): QcRouteController
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1186): applyOpen
,D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
I/WifiStateMachine(  925): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
,D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1186): applyOpen
,D/accuweather( 7902): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7902): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7902): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7902): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7902): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7902): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1349): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
V/        (  282): QcRouteController
,D/accuweather( 7902): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1349): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7902): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1349): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,V/        (  282): QcRouteController
,D/accuweather( 7902): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7902): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,V/        (  282): QcRouteController
,E/Zygote  ( 7931): MountEmulatedStorage()
,E/Zygote  ( 7931): v2
I/libpersona( 7931): KNOX_SDCARD checking this for 1000
I/libpersona( 7931): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7931 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  925): Killing 4716:com.android.calendar/u0a149 (adj 15): bgCount ##41
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,D/ConnectivityService(  925): Setting Dns servers for network 503 to [/192.168.1.1]
,E/ConnectivityService(  925): updateNetworkInfo()
D/Nat464Xlat(  925): requiresClat: netType=1, connected=false, hasIPv4Address=true
E/ConnectivityService(  925): updateNetworkInfo()
D/ConnectivityService(  925): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  925): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  925): calling update connectivity
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  925): Connected
D/ConnectivityService(  925): ignoring duplicate network state non-change
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  925): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  925): ignoring duplicate network state non-change
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  925): Validated
D/ConnectivityService(  925): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  925): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  925): calling update connectivity
D/ConnectivityService(  925): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  925):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  925):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  925):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  925):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SELinux ( 7931): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7931): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ConnectivityService(  925): currentScore = 0, newScore = 60
D/ConnectivityService(  925):    accepting network in place of null
D/ConnectivityService(  925): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/ActivityManager(  925): Failed to clear dns cache for: com.android.calendar
,D/TelephonyNetworkFactory( 1483): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/SELinux ( 7931): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/CSLegacyTypeTracker(  925): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  925): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  925): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/libprocessgroup(  925): failed to open /acct/uid_10149/pid_4716/cgroup.procs: No such file or directory
,D/ConnectivityService(  925): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  925): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  925): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  925): getSBEnabled() enabled =false
,D/SmartBondingService(  925): getSBEnabled() enabled =false
D/NtpTrustedTime(  925): currentTimeMillis() cache hit
V/NetworkStats(  925): updateIfacesLocked()
V/NetworkStats(  925): performPollLocked(flags=0x1)
D/SmartBondingService(  925): getSBEnabled() enabled =false
,D/NetworkStatsFactory(  925): UpdateStatsForKnox
D/ConnectivityService(  925): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  925): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  925): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1186): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1186): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1186): updateDataNetType()
D/StatusBar.NetworkController( 1186): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1186): updateLTEICONDataNetType:0
D/NtpTrustedTime(  925): currentTimeMillis() cache hit
D/NtpTrustedTime(  925): currentTimeMillis() cache hit
D/NtpTrustedTime(  925): currentTimeMillis() cache hit
D/NtpTrustedTime(  925): currentTimeMillis() cache hit
V/NetworkStats(  925): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,V/NetworkStats(  925): performPollLocked() took 5ms
D/NtpTrustedTime(  925): currentTimeMillis() cache hit
,D/EntConnectivity(  925): Not allowed due to - mEnabled false
D/ConnectivityService(  925): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  925): calling update connectivity
D/StatusBar.NetworkController( 1186): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
,D/NtpTrustedTime(  925): currentTimeMillis() cache hit
D/NtpTrustedTime(  925): currentTimeMillis() cache hit
,D/ConnectivityService(  925):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  925):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  925): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  925):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1186): CM callback handler got msg 524290
D/ConnectivityService(  925): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  925): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  925): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  925):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 2473): CM callback handler got msg 524290
D/ConnectivityService(  925):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  925):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  925): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  925): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  925): calling update connectivity
D/ConnectivityService(  925):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  925):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  925): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1186): CM callback handler got msg 524290
D/ConnectivityService(  925):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  925): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  925): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1186): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1186): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1186): updateDataNetType()
D/StatusBar.NetworkController( 1186): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1186): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1186): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/ConnectivityManager.CallbackHandler( 2473): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/TimaKeyStoreProvider( 7931): TimaSignature is unavailable
,D/ActivityThread( 7931): Added TimaKeyStore provider
,D/ResourcesManager( 7931): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7931): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7931): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7931): premStatus:2
,I/KnoxUsageLogPro( 7931): isEulaShown : false
I/KnoxUsageLogPro( 7931): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7951): MountEmulatedStorage()
E/Zygote  ( 7951): v2
I/libpersona( 7951): KNOX_SDCARD checking this for 10087
I/libpersona( 7951): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7951 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  925): Killing 7046:com.sec.android.app.taskmanager/u0a175 (adj 15): bgCount ##41
,I/SELinux ( 7951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7951): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7951): TimaSignature is unavailable
,D/ActivityThread( 7951): Added TimaKeyStore provider
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  925): failed to open /acct/uid_10175/pid_7046/cgroup.procs: No such file or directory
,I/ActivityManager(  925): Killing 7061:com.qualcomm.timeservice/1000 (adj 15): bgCount ##41
,D/Headlines( 5409): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5409): getCountryCode(): countryCode = PL
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,D/Headlines( 5409): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5409): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5409): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5409): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5409): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5409): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5409): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7967): MountEmulatedStorage()
E/Zygote  ( 7967): v2
I/libpersona( 7967): KNOX_SDCARD checking this for 10127
I/libpersona( 7967): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7967 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  925): waitForAlarm result :8
,I/SELinux ( 7967): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7967): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7967): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7967): TimaSignature is unavailable
,D/ActivityThread( 7967): Added TimaKeyStore provider
,D/ResourcesManager( 7967): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  925): failed to open /acct/uid_1000/pid_7061/cgroup.procs: No such file or directory
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7967): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7967): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  925): MasterInitialState.processMessage what=3
,D/SmartBondingService(  925): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  925): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  925): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  925): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,I/CLocInfoService(  925): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  925): CLocinfo wifi true 
D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  925): getSBEnabled() enabled =false
D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  925): getSBEnabled() enabled =false
,D/SmartBondingService(  925): getSBEnabled() enabled =false
D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  925): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2232): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2232): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2217): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,W/ContextImpl( 7967): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 7760): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3685): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3685): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7967): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/SecContentProvider2(  925): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  925): mCursor = null
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  925): mDVFSHelper.release()
,V/GLSActivity( 2264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WebViewFactory( 7967): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7967): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/VacuumService( 2264): Vacuum at: now=1452520980407 tag=VacuumService
,I/LibraryLoader( 7967): Loading: webviewchromium
,I/LibraryLoader( 7967): Time to load native libraries: 6 ms (timestamps 2543-2549)
,I/LibraryLoader( 7967): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7967): Binding Chromium to main looper Looper (main, tid 1) {194440fd}
,I/LibraryLoader( 7967): Expected native library version number "",actual native library version number ""
,I/chromium( 7967): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
E/SMD     (  287): DCD ON
,I/BrowserStartupController( 7967): Initializing chromium process, renderers=0
,W/art     ( 7967): Attempt to remove local handle scope entry from IRT, ignoring
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/chromium( 7967): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7967): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7967): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7967): Requires BLUETOOTH permission
,I/Adreno-EGL( 7967): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7967): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7967): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7967): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7967): Remote Branch: 
I/Adreno-EGL( 7967): Local Patches: 
I/Adreno-EGL( 7967): Reconstruct Branch: 
,I/NSApplication( 7967): Starting up...
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  925): Killing 6070:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8035): MountEmulatedStorage()
E/Zygote  ( 8035): v2
I/libpersona( 8035): KNOX_SDCARD checking this for 10137
I/libpersona( 8035): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8035 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 8035): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8035): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8035): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  925): failed to open /acct/uid_10045/pid_6070/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8035): TimaSignature is unavailable
,D/ActivityThread( 8035): Added TimaKeyStore provider
,D/ResourcesManager( 8035): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 8035): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8035): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8035): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 8035): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8035): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8035): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8051): MountEmulatedStorage()
E/Zygote  ( 8051): v2
I/libpersona( 8051): KNOX_SDCARD checking this for 10162
I/libpersona( 8051): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8051 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  925): Killing 7156:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,D/ConnectivityService(  925): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SELinux ( 8051): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8051): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8051): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/TimaKeyStoreProvider( 8051): TimaSignature is unavailable
,D/ActivityThread( 8051): Added TimaKeyStore provider
,D/ResourcesManager( 8051): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8051): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8051): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8051): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8051): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  925): failed to open /acct/uid_10014/pid_7156/cgroup.procs: No such file or directory
,D/RCPManagerService(  925): exchangeData() failure , invalid userId
,D/RCPManagerService(  925): exchangeData() failure , invalid userId
,D/RCPManagerService(  925): exchangeData() failure , invalid userId
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,D/RCPManagerService(  925): exchangeData() failure , invalid userId
,E/Zygote  ( 8074): MountEmulatedStorage()
I/libpersona( 8074): KNOX_SDCARD checking this for 10077
E/Zygote  ( 8074): v2
I/libpersona( 8074): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8074 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
I/SELinux ( 8074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,I/SELinux ( 8074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,E/SELinux ( 8074): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,D/RCPManagerService(  925): exchangeData() failure , invalid userId
,D/RCPManagerService(  925): exchangeData() failure , invalid userId
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,D/TimaKeyStoreProvider( 8074): TimaSignature is unavailable
V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/ActivityThread( 8074): Added TimaKeyStore provider
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  925): Killing 7182:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,D/SecurityLogAgent( 7024): KnoxConfiguration : Current State = 1
V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
D/SecurityLogAgent( 7024): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7024): StateMachine : Current State = 1
,V/BitmapFactory( 8051): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7024): StateMachine : Changed Current State = 1
,I/ActivityManager(  925): Killing 6381:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,D/ResourcesManager( 8074): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 8074): onCreate
D/BadgeProvider( 8074): DatabaseHelper
,E/Zygote  ( 8089): MountEmulatedStorage()
,E/Zygote  ( 8089): v2
I/libpersona( 8089): KNOX_SDCARD checking this for 10177
I/libpersona( 8089): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8089 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8089): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8089): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8089): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8089): TimaSignature is unavailable
,D/ActivityThread( 8089): Added TimaKeyStore provider
,W/ActivityManager(  925): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ResourcesManager( 8089): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  925): Killing 4781:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,W/libprocessgroup(  925): failed to open /acct/uid_10015/pid_7182/cgroup.procs: No such file or directory
,W/libprocessgroup(  925): failed to open /acct/uid_10033/pid_6381/cgroup.procs: No such file or directory
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7740): notifyNetworkActivated
,I/art     (  925): Explicit concurrent mark sweep GC freed 47103(2MB) AllocSpace objects, 2(32KB) LOS objects, 30% free, 36MB/52MB, paused 1.567ms total 89.017ms
,D/BadgeProvider( 8074): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 8074): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8074): sendNotify, [notify] : null
D/BadgeProvider( 8074): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8074): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8074): update, [UpdateCount] : 1
,D/Launcher.Model( 1503): reloadBadges entered.
W/libprocessgroup(  925): failed to open /acct/uid_10034/pid_4781/cgroup.procs: No such file or directory
,W/ContextImpl( 7740): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  925): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/Hs20UtilService( 1321): Starting #8
,I/Hs20UtilService( 1321): Message received 5007
,D/hcjo    ( 7740): AutoUpdateManager:IDLE:execute
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,D/KeyguardViewMediator( 1186): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/InitializeManagerStateMachine( 7740): execute::IDLE:EXECUTE
D/PersonaManager( 1186): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
D/InitializeManagerStateMachine( 7740): exit::IDLE
D/InitializeManagerStateMachine( 7740): entry::NETWORK_CHECK
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/KeyguardViewMediator( 1186): doKeyguard: not showing because lockscreen is off
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7740): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7740): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7740): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7740): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7740): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7740): entry::SUCCESS
D/hcjo    ( 7740): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1321): Starting #9
,I/Hs20UtilService( 1321): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,D/hcjo    ( 7740): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7740): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7740): exit::SUCCESS
,D/InitializeManagerStateMachine( 7740): entry::IDLE
,I/Hs20UtilService( 1321): Starting #10
,I/Hs20UtilService( 1321): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  925): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1321): Starting #11
,I/Hs20UtilService( 1321): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  925): callSECApi what=220
,D/WifiStateMachine(  925): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7200): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7200): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7200): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7200): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7815): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7815): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SurfaceFlinger(  257): id=18 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/PowerManagerService(  925): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=925
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,I/FOTA_Client( 7831): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7831): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
I/FOTA_Client( 7831): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.503: ( 7846): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,I/KLMS-2.4.503: ( 7846): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452520981466
,I/KLMS-2.4.503: ( 7846): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7846): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7846): StateImplV2(): networkChangeListener().START
,I/GAV2    ( 7607): Thread[GAThread,5,main]: No campaign data found.
I/KLMS-2.4.503: ( 7846): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7846): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,I/SO_AGENT( 7872): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7238): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6909): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6909): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 6909): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6909): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6909): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6909): [SCU] == networkStateCheck == true
I/SA      ( 6909): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 6909): isChinaCountryCode : false
I/SA      ( 6909): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6909): [OR] == networkStateCheck true ==
,I/SA      ( 6909): [OR] GetMyCountryZoneTask
,I/SA      ( 6909): [OR] onReceive END
,I/ActivityManager(  925): Killing 7255:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,I/SA      ( 6909): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6909): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6909): [SSP] query invoked
,D/accuweather( 7902): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7902): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 6909): [TPMU] GetMccFromDB : null
I/SA      ( 6909): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6909): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7931): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7931): premStatus:2
,I/KnoxUsageLogPro( 7931): isEulaShown : false
I/KnoxUsageLogPro( 7931): KnoxUsageReceiver onReceive : not Processible, just return
,D/Headlines( 5409): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5409): getCountryCode(): countryCode = PL
,D/Headlines( 5409): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5409): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5409): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5409): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5409): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5409): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5409): requestUpdateNewsWelcomeCard !!! no welcome card
E/File    ( 6909): fail readDirectory() errno=2
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 8035): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8035): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8035): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  925): exchangeData() failure , invalid userId
,D/RCPManagerService(  925): exchangeData() failure , invalid userId
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7024): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7024): KnoxConfiguration : Current State Mapping Found 
W/libprocessgroup(  925): failed to open /acct/uid_10041/pid_7255/cgroup.procs: No such file or directory
D/SecurityLogAgent( 7024): StateMachine : Current State = 1
D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7024): StateMachine : Changed Current State = 1
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7740): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7740): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7740): exit::IDLE
D/InitializeManagerStateMachine( 7740): entry::NETWORK_CHECK
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7740): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7740): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 7740): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7740): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7740): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7740): entry::SUCCESS
D/hcjo    ( 7740): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7740): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7740): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7740): exit::SUCCESS
D/InitializeManagerStateMachine( 7740): entry::IDLE
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/SA      ( 6909): [RC New] Execute method=[GET] start
,I/SA      ( 6909): [RC New] Security=[true]
,I/System.out( 6909): Thread-1070(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6909): Thread-1070(ApacheHTTPLog):isShipBuild true
,I/System.out( 6909): Thread-1070(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,W/ProcessCpuTracker(  925): Skipping unknown process pid 8125
,I/dhcpcd  ( 7783): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7783): wlan0: sendmsg: Cannot assign requested address
,E/WifiStateMachine(  925): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  925): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  925): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  925): identical MTU - not setting
D/ConnectivityService(  925): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  925): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
V/        (  282): QcRouteController
,E/WifiStateMachine(  925): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  925): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  925): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  925): getSBEnabled() enabled =false
D/SmartBondingService(  925): getSBEnabled() enabled =false
,D/SmartBondingService(  925): getSBEnabled() enabled =false
,V/        (  282): QcRouteController
,W/NetworkManagementService(  925): route cmd failed: 
W/NetworkManagementService(  925): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  925): '
W/NetworkManagementService(  925): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  925): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  925): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  925): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  925): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  925): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  925): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  925): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  925): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  925): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  925): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  925): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  925): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  925): calling update connectivity
D/ConnectivityService(  925):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  925):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  925): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1186): CM callback handler got msg 524295
,D/ConnectivityService(  925):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  925): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  925): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  925): calling update connectivity
,D/ConnectivityService(  925):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  925):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  925): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 2473): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1186): CM callback handler got msg 524295
,D/ConnectivityService(  925):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  925): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2473): CM callback handler got msg 524295
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/PackageManager(  925): [MSG] MCS_UNBIND
,I/ActivityManager(  925): Killing 5796:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,I/SA      ( 6909): [RC New] [v2liruge] api execute + 716
I/SA      ( 6909): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6909): AsyncTask #1 calls detatch()
,I/SA      ( 6909): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6909): [OCP] update openData : PL
,I/SA      ( 6909): [TPMU] getNetworkMcc : 
,I/SA      ( 6909): [SCU] saveMccToPreferece Start
,I/SA      ( 6909): [SCU] RegionMCC : 260
I/SA      ( 6909): [SSP] query invoked
,I/SA      ( 6909): [TPMU] GetMccFromDB : null
,I/SA      ( 6909): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6909): [SCU] saveMccToPreferece End
,I/SA      ( 6909): [RC New] executeRequest [v2liruge] end. 784
I/SA      ( 6909): [RC New] Execute end
,I/SA      ( 6909): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6909): [OR] GetMyCountryZoneTask Success
,W/libprocessgroup(  925): failed to open /acct/uid_10047/pid_5796/cgroup.procs: No such file or directory
,I/WifiStateMachine(  925): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  925): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SMD     (  287): DCD ON
,D/WearableService( 2264): callingUid 10011, callindPid: 2264
,D/ResourcesManager( 7760): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7760): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7760): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7760): Using the GMSCore's GoogleHttpClient
,D/WearableClient( 7760): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7760): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7760): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7760): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7760): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7760): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7760): Conditions not met for autocaching.
,I/MusicLeanback( 7760): Stop autocaching.
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/ActivityThread( 7760): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@f21b2bd that was originally bound here
E/ActivityThread( 7760): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@f21b2bd that was originally bound here
E/ActivityThread( 7760): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7760): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7760): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7760): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7760): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7760): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7760): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7760): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7760): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7760): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7760): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7760): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7760): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7760): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7760): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7760): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7760): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7760): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7760): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7760): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7760): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7760): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7760): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7760): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/jxcore-log( 7376): Test app app.js loaded
I/jxcore-log( 7376): 
,I/Choreographer( 7376): Skipped 434 frames!  The application may be doing too much work on its main thread.
,D/InputMethodManagerService(  925): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  925): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@c490baa attribute=null, token = android.os.BinderProxy@15555a6b
,D/ActivityManager(  925): post active user change for 0
,D/KnoxTimeoutHandler(  925): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  925): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,I/Timeline( 7376): Timeline: Activity_idle id: android.os.BinderProxy@17544918 time:116004
,I/chromium( 7376): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7376): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/SSRM:m  (  925): SIOP:: AP = 410, PST = 348, CUR = 450
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/SurfaceFlinger(  257): id=18 Removed Toast (8/9)
,I/SurfaceFlinger(  257): id=18 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,D/PowerManagerService(  925): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 925) eventTime = 117059
,D/PowerManagerService(  925): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=925 (0x0)
,D/PowerManagerService(  925): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=925, ws=WorkSource{10058}) (elapsedTime=3524)
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,I/GAV4    ( 7967): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 1
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7200): mConnectivityHandler : connected
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7200): [hasSamungAccount] - No Samsung Account
,E/SMD     (  287): DCD ON
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7200): [GetString-S]
,I/ReactiveServiceManager( 7200): Supported : 1
,D/QSEECOMAPI: (  925): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: (  925): App is not loaded in QSEE
,D/QSEECOMAPI: (  925): Loaded image: APP id = 2
,D/QSEECOMAPI: (  925): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  925): QSEECom_shutdown_app, app_id = 2
,E/terrier (  925): handleString: Failed to handle string(-4)
E/terrier (  925): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 7200): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7200): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7200): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7200): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7200): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7200): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7783): wlan0: sending IPv6 Router Solicitation
,I/PowerManagerService(  925): [PWL] Off : 15s ago
,E/SMD     (  287): DCD ON
,I/dhcpcd  ( 7783): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7783): wlan0: no IPv6 Routers available
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7740): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7740): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7740): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7740): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7740): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7740): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7740): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 7740): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7740): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7740): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7740): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7740): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7740): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7740): entry::IDLE
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,V/AlarmManager(  925): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1186): handleTimeUpdate
,D/KeyguardEffectViewController( 1186): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1186): *** don't update sliding image ***
,D/BatteryService(  925): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  925): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  925): stay LED for fully charged
D/BatteryService(  925): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  925):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  925): Plugged
I/MotionRecognitionService(  925): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/Finsky  ( 7688): [1250] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7688): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/SSRM:m  (  925): SIOP:: AP = 330, PST = 339, CUR = 450
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD ON
,W/ContextImpl(  925): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/Watchdog(  925): !@Sync 4
,V/AlarmManager(  925): waitForAlarm result :4
,D/BatteryService(  925): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  925): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  925): stay LED for fully charged
,D/BatteryService(  925): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  925):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  925): Plugged
,I/MotionRecognitionService(  925): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  925): SIOP:: AP = 310, PST = 331, CUR = 450
,I/PowerManagerService(  925): [PWL] Off : 30s ago
,E/SMD     (  287): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD ON
,D/BatteryService(  925): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  925): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  925): stay LED for fully charged
D/BatteryService(  925): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  925):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  925): Plugged
I/MotionRecognitionService(  925): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  925): SIOP:: AP = 300, PST = 328, CUR = 450
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,W/ContextImpl(  925): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  925): SIOP:: AP = 290, PST = 325, CUR = 450
,I/PowerManagerService(  925): [PWL] Off : 50s ago
,E/SMD     (  287): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD ON
,E/Watchdog(  925): !@Sync 5
,V/AlarmManager(  925): waitForAlarm result :4
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhenotypeConfigurator( 2264): Scheduling Phenotype for one-off execution 13636 seconds from now (1452521034099)
,D/GetConfigurationSnapshotOperation( 2264): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/SSRM:m  (  925): SIOP:: AP = 290, PST = 322, CUR = 450
,I/PhenotypeFlagCommitter( 2264): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2264): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  925): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SMD     (  287): DCD ON
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 2264): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 2264): (HTTPLog)-Static: isShipBuild true
I/System.out( 2264): (HTTPLog)-Thread-302-861841666: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 2264): Tagging socket 74 with tag 1000120100000000{268440065,0} uid -1, pid: 2264, getuid(): 10011
,I/qtaguid ( 2264): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 2264, getuid(): 10011
,D/LocationManagerService(  925): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2264): Tagging socket 74 with tag 1000120100000000{268440065,0} uid -1, pid: 2264, getuid(): 10011
,D/LocationManagerService(  925): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2264): Tagging socket 74 with tag 1000120100000000{268440065,0} uid -1, pid: 2264, getuid(): 10011,
,D/ConnectivityService(  925): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,W/ContextImpl(  925): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  925): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  925): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  925): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  925): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  925):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  925): Plugged
,I/MotionRecognitionService(  925): setPowerConnected  = true
,D/BatteryService(  925): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  925): SIOP:: AP = 280, PST = 318, CUR = 450
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  925): [PWL] Off : 75s ago
,E/SMD     (  287): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/BatteryService(  925): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  925): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  925): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  925):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  925): Plugged,
,I/MotionRecognitionService(  925): setPowerConnected  = true
,D/BatteryService(  925): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/SSRM:m  (  925): SIOP:: AP = 270, PST = 314, CUR = 450
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD ON
,W/ContextImpl(  925): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/Watchdog(  925): !@Sync 6
,D/BatteryService(  925): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  925): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  925): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  925):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  925): Plugged
,I/MotionRecognitionService(  925): setPowerConnected  = true
,D/BatteryService(  925): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 2264): disconnect managed GoogleApiClient
,D/SSRM:m  (  925): SIOP:: AP = 260, PST = 308, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  925): SIOP:: AP = 260, PST = 300, CUR = 450
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  925): [PWL] Off : 105s ago
,W/ContextImpl(  925): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/Atfwd_Sendcmd(  348): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  348): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD ON
,D/BatteryService(  925): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  925): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  925): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  925):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  925): Plugged
,I/MotionRecognitionService(  925): setPowerConnected  = true
,D/BatteryService(  925): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  925): SIOP:: AP = 260, PST = 285, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,E/Watchdog(  925): !@Sync 7
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,V/AlarmManager(  925): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1186): handleTimeUpdate
,D/KeyguardEffectViewController( 1186): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1186): *** don't update sliding image ***
,D/BatteryService(  925): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  925): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  925): stay LED for fully charged
D/BatteryService(  925): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  925):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  925): Plugged
I/MotionRecognitionService(  925): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:m  (  925): SIOP:: AP = 260, PST = 278, CUR = 450
,E/SMD     (  287): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD ON
,W/ContextImpl(  925): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  925): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/SSRM:m  (  925): SIOP:: AP = 260, PST = 273, CUR = 450
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  925): [PWL] Off : 140s ago
,I/jxcore-log( 7376): --= Surplus to requirements =--
I/jxcore-log( 7376): 
,I/jxcore-log( 7376): ****TEST TOOK:  ms ****
I/jxcore-log( 7376): 
I/jxcore-log( 7376): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7376): 
,D/BatteryService(  925): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0,
,D/BatteryService(  925): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  925): stay LED for fully charged
,D/BatteryService(  925): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  925):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  925): Plugged
I/MotionRecognitionService(  925): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/SSRM:m  (  925): SIOP:: AP = 260, PST = 269, CUR = 450
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AndroidRuntime( 8283): 
D/AndroidRuntime( 8283): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8283): CheckJNI is OFF
,D/AndroidRuntime( 8283): setted country_code = Poland
,D/AndroidRuntime( 8283): setted countryiso_code = PL
,D/AndroidRuntime( 8283): setted sales_code = XEO
,D/AndroidRuntime( 8283): readGMSProperty: start
D/AndroidRuntime( 8283): readGMSProperty: already setted!!
,D/AndroidRuntime( 8283): readGMSProperty: end
D/AndroidRuntime( 8283): addProductProperty: start
,E/AffinityControl( 8283): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8283): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  925): START PACKAGE DELETE: observer{982135895}
D/PackageManager(  925): pkg{<packageName>}
D/PackageManager(  925): user{0}
D/PackageManager(  925): caller{2000}
D/PackageManager(  925): flags{3}
D/PersonaManagerService(  925): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  925): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  925): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager(  925): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  925): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  925): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  925): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  925): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  925): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  925): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  925): !@killApplicatoin: 10356, uninstall pkg
,I/ActivityManager(  925): Force stopping com.test.thalitest appid=10356 user=-1: uninstall pkg
,I/ActivityManager(  925): Killing 7376:com.test.thalitest/u0a356 (adj 0): stop com.test.thalitest
,I/ActivityManager(  925):   Force finishing activity ActivityRecord{1e1c749b u0 com.test.thalitest/.MainActivity t4}
,D/FocusedStackFrame(  925): Set to : 0
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,I/SurfaceFlinger(  257): id=17 Removed com.test.thalitest/com.test.thalitest.MainActivity (6/8)
,I/SurfaceFlinger(  257): id=17 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,W/PackageSettings(  925): Skipping PackageSetting{5b6ef0 com.example.hello/10357} due to missing metadata
,D/ConnectivityService(  925): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  925): Force stopping com.test.thalitest appid=10356 user=0: pkg removed
,D/WifiService(  925): Client connection lost with reason: 4
,I/art     ( 6252): Explicit concurrent mark sweep GC freed 34188(1826KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 353us total 31.090ms
,I/art     ( 2473): Explicit concurrent mark sweep GC freed 38852(2MB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 21MB/35MB, paused 626us total 86.017ms
,I/art     ( 1561): Explicit concurrent mark sweep GC freed 33759(2012KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/27MB, paused 867us total 90.985ms
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  925): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1875): mOCRHelper is null
,W/GeofencerStateMachine( 2264): Ignoring removeGeofence because network location is disabled.
,E/libprocessgroup(  925): failed to kill 1 processes for processgroup 7376
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/KLMS-2.4.503: ( 7846): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7846): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1452521115291
,I/KLMS-2.4.503: ( 7846): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7846): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/SecContentProvider2(  925): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  925): mCursor = null
,I/art     (  925): Explicit concurrent mark sweep GC freed 50178(3MB) AllocSpace objects, 46(736KB) LOS objects, 30% free, 36MB/52MB, paused 9.037ms total 173.903ms
,D/ResourcesManager(  925): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  925): WaitForGcToComplete blocked for 168.878ms for cause Explicit
,D/EnterpriseDeviceManagerService(  925): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  925): Admin package name: com.google.android.gms
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/RegisteredServicesCache( 1468): empty dynamic service
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,E/SMD     (  287): DCD ON
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,E/Zygote  ( 8313): MountEmulatedStorage()
E/Zygote  ( 8313): v2
I/libpersona( 8313): KNOX_SDCARD checking this for 10103
I/libpersona( 8313): KNOX_SDCARD not a persona
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,I/ActivityManager(  925): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8313 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/art     (  925): Explicit concurrent mark sweep GC freed 10498(544KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 3.166ms total 163.328ms
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/SELinux ( 8313): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 8313): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8313): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  925): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/TimaKeyStoreProvider( 8313): TimaSignature is unavailable
,D/ActivityThread( 8313): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/PackageManager(  925): delete codoeFile: 
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  925): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  925): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/PackageManager(  925): result of delete: 1{982135895}
,D/AndroidRuntime( 8283): Shutting down VM
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1186): value : false
,D/SurfaceWidgetView( 1503): destroyHardwareResources():386648237
,V/WindowOrientationListener(  925): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  925): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  925): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  925): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  925): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/Launcher( 1503): onRestart, Launcher: 635013251
,D/Launcher( 1503): onStart, Launcher: 635013251
D/Launcher.HomeView( 1503): onStart
,D/elm:14451( 8313): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8313): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8313): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2217): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2217): [237392/6] SurfaceWidget drawing first frame
D/elm:14451( 8313): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/SurfaceFlinger(  257): id=19 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,E/Zygote  ( 8330): MountEmulatedStorage()
I/libpersona( 8330): KNOX_SDCARD checking this for 10016
E/Zygote  ( 8330): v2
I/libpersona( 8330): KNOX_SDCARD not a persona
,D/elm:14451( 8313): ElmAgentService : onCreate()
,D/StatusBarManagerService(  925): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/ActivityManager(  925): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8330 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,D/elm:14451( 8313): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14451( 8313): MainReceiver.listeningToPackageRemoved()
,D/elm:14451( 8313): MDMBridge.getInstance()
D/elm:14451( 8313): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/SELinux ( 8330): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,I/SELinux ( 8330): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/StatusBarManagerService(  925): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,E/SELinux ( 8330): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14451( 8313): MDMBridge.getAllLicenseInfoFromSDK()
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/TimaKeyStoreProvider( 8330): TimaSignature is unavailable
D/ActivityThread( 8330): Added TimaKeyStore provider
,D/elm:14451( 8313): ElmAgentService : onDestroy().
,I/ActivityManager(  925): Killing 5718:com.android.mms/u0a49 (adj 15): bgCount ##41
,D/ResourcesManager(  925): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/InputMethodManagerService(  925): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  925): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService(  925): Got RemoteException sending setActive(false) notification to pid 7376 uid 10356
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 8330): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  925): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  925): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  925): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  925): PackageReceiver onReceive()
I/HarmonyEASService(  925): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  925): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  925): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/BackupManagerService(  925): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  925): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  925): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  925): uID is 10356
V/EnterpriseBillingPolicy(  925): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  925): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  925): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  925): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  925): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  925): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  925): getBillingProfileForVpnEngine - end - null
,D/TaskPersister(  925): removeObsoleteFile: deleting file=4_task.xml
,D/ResourcesManager(  925): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  925): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8330): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8330): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8330): onReceive() : package name is not s health. Return !!!
,D/CountryDetector(  925): No listener is left
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,I/PCWCLIENTTRACE_PushUtil( 7200): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7200): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7200): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7200): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
E/Zygote  ( 8349): MountEmulatedStorage()
E/Zygote  ( 8349): v2
I/libpersona( 8349): KNOX_SDCARD checking this for 10033
I/libpersona( 8349): KNOX_SDCARD not a persona
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  925): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager(  925): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8349 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/ActivityManager(  925): Killing 7288:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,W/Resources(  925): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Timeline(  925): Timeline: Activity_windows_visible id: ActivityRecord{2da3ddd2 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:247958
,D/UsbSettingsManager(  925): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  925): onPackageRemoved : com.test.thalitest
,I/SELinux ( 8349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
I/SELinux ( 8349): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/libprocessgroup(  925): failed to open /acct/uid_10049/pid_5718/cgroup.procs: No such file or directory
,E/SELinux ( 8349): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1186): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1186): value : false
,W/libprocessgroup(  925): failed to open /acct/uid_10050/pid_7288/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8349): TimaSignature is unavailable
,D/ActivityThread( 8349): Added TimaKeyStore provider
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/FeatureConfig( 8349): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8349): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8349): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8349): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8349): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8349): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8349): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8349): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8349): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8349): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8349): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8349): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8349): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SharedPreferencesImpl( 8349): Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,I/EventHub(  925): Removing device '/dev/input/event4' due to inotify event
,E/SharedPreferencesImpl( 8349): Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,I/EventHub(  925): Removing device '/dev/input/event5' due to inotify event
,E/SharedPreferencesImpl( 8349): Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/com.samsung.android.app.galaxyfinder_preferences.xml
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  925): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8371 uid=10034 gids={50034, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
E/Zygote  ( 8371): MountEmulatedStorage()
I/libpersona( 8371): KNOX_SDCARD checking this for 10034
E/Zygote  ( 8371): v2
I/libpersona( 8371): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Killing 7305:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
,I/EventHub(  925): Removing device '/dev/input/event6' due to inotify event
,I/art     (  321): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 429us total 23.925ms
,I/SELinux ( 8371): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
,I/EventHub(  925): Removing device '/dev/input/event7' due to inotify event
,E/SELinux ( 8371): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 487us total 12.596ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 383us total 11.935ms
,D/TimaKeyStoreProvider( 8371): TimaSignature is unavailable
,D/ActivityThread( 8371): Added TimaKeyStore provider
,D/ResourcesManager( 8371): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/ContextImpl( 8371): Unable to create files subdir /data/data/com.sec.android.app.shealth/cache
E/ActivityThread( 8371): Unable to setupGraphicsSupport due to missing cache directory
,W/libprocessgroup(  925): failed to open /acct/uid_10057/pid_7305/cgroup.procs: No such file or directory
,W/        ( 8371): Zip: failed reading lfh name from offset 418254
,F/libc    ( 8371): Fatal signal 7 (SIGBUS), code 2, fault addr 0x73706aae in tid 8371 (oid.app.shealth)
,E/audit_log( 2182): File locking failed. error= Bad file number
F/libc    ( 8371): Failed while talking to debuggerd: Broken pipe
,I/EventHub(  925): Removing device '/dev/input/event8' due to inotify event
E/audit_log( 2182): File locking failed. error= Bad file number
,I/ActivityManager(  925): Process com.sec.android.app.shealth (pid 8371)(adj 0) has died(165,591)
,F/libc    ( 7238): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7764ea00 in tid 7238 (om.sec.spp.push)
,F/libc    ( 7238): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2182): File locking failed. error= Bad file number
,I/EventHub(  925): Removing device '/dev/input/event9' due to inotify event
,E/SharedPreferencesImpl( 8349): Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,I/Zygote  (  321): Process 8371 exited due to signal (7)
,I/ActivityManager(  925): Process com.sec.spp.push (pid 7238)(adj 0) has died(169,591)
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8390): MountEmulatedStorage()
I/libpersona( 8390): KNOX_SDCARD checking this for 10037
E/Zygote  ( 8390): v2
I/libpersona( 8390): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8390 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/EventHub(  925): Removing device '/dev/input/event10' due to inotify event
,I/Zygote  (  321): Process 7238 exited due to signal (7)
,I/SELinux ( 8390): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
E/SELinux ( 8390): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/EventHub(  925): Removing device '/dev/input/event11' due to inotify event
,D/TimaKeyStoreProvider( 8390): TimaSignature is unavailable
,D/ActivityThread( 8390): Added TimaKeyStore provider
,D/ResourcesManager( 8390): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/ContextImpl( 8390): Unable to create files subdir /data/data/com.sec.spp.push/cache
,E/ActivityThread( 8390): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8390): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa1609756 in tid 8390 (moteNotiProcess)
,F/libc    ( 8390): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2182): File locking failed. error= Bad file number
,I/ActivityManager(  925): Process com.sec.spp.push:RemoteNotiProcess (pid 8390)(adj 0) has died(169,592)
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  925): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8406): MountEmulatedStorage()
,E/Zygote  ( 8406): v2
I/libpersona( 8406): KNOX_SDCARD checking this for 10041
I/libpersona( 8406): KNOX_SDCARD not a persona
,I/ActivityManager(  925): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8406 uid=10041 gids={50041, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/Zygote  (  321): Process 8390 exited due to signal (7)
,I/SELinux ( 8406): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
E/SELinux ( 8406): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8406): TimaSignature is unavailable
,D/ActivityThread( 8406): Added TimaKeyStore provider

```
