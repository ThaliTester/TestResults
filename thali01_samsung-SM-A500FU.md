#### Test 62509094ffd3875_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
I/KLMS-2.5.183: ( 3434): KLMSAbstractReciever(): onReceive().END.
--------- beginning of system
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.183: ( 3434): KLMSIntentService(): onCreate()
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/KLMS-2.5.183: ( 3434): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.183: ( 3434): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/CountryDetector( 1016): No listener is left
I/KLMS-2.5.183: ( 3434): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/CameraApp( 3452): CameraApp.onCreate()... mFeature : null
I/testFeature( 3452): Feature.Feature(context)
I/testFeature( 3452): Feature.readInternalDefaultXml()
I/testFeature( 3452): ResetFeatureValue
E/Zygote  ( 3481): MountEmulatedStorage()
E/Zygote  ( 3481): v2
I/SELinux ( 3481): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3481): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/System.out( 3135): YouTube MDX: MDX video stage moved to NEW
E/SELinux ( 3481): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/System.out( 3135): YouTube MDX: MDX video player state moved to UNSTARTED
I/System.out( 3135): YouTube MDX: MDX ad player state moved to UNSTARTED
I/libpersona( 3481): KNOX_SDCARD checking this for 10022
I/libpersona( 3481): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3481 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
I/CameraFirmware_broadcast( 3452): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3452): CameraApp.getAppFeature()...
I/KLMS-2.5.183: ( 3434): KLMSIntentService(): BOOT_COMPLETED
I/CrashAnrDetector( 1016): onPackageAdded : com.test.thalitest
W/art     ( 3135): Suspending all threads took: 13.530ms
D/TimaKeyStoreProvider( 3481): TimaSignature is unavailable
D/ActivityThread( 3481): Added TimaKeyStore provider
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
W/libprocessgroup( 1016): failed to open /acct/uid_10099/pid_2668/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2686/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10098/pid_2138/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10152/pid_2695/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2299/cgroup.procs: No such file or directory
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
W/libprocessgroup( 1016): failed to open /acct/uid_1101/pid_2755/cgroup.procs: No such file or directory
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2739/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10046/pid_2267/cgroup.procs: No such file or directory
E/Zygote  ( 3500): MountEmulatedStorage()
I/libpersona( 3500): KNOX_SDCARD checking this for 10100,
E/Zygote  ( 3500): v2
I/libpersona( 3500): KNOX_SDCARD not a persona
I/SELinux ( 3500): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3500): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3500 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 3500): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3434): KLMSIntentService(): onDestroy()
I/ActivityManager( 1016): Killing 2774:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
W/ContextImpl( 1312): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 3500): TimaSignature is unavailable
D/ActivityThread( 3500): Added TimaKeyStore provider
W/ContextImpl( 1312): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
I/ActivityManager( 1016): Killing 2794:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
I/GCoreNlp( 1812): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/SettingSearch/SearchIntentReceiver( 1312): InitSerachDBThread thread end!
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
D/LocationProviderProxy( 1016): applying state to connected service
D/PackageIntentReceiver( 3500): ACTION_BOOT_COMPLETED
D/PackageIntentReceiver( 3500): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1016): failed to open /acct/uid_10048/pid_2774/cgroup.procs: No such file or directory
I/ActivityManager( 1016): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3530 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 3530): MountEmulatedStorage()
E/Zygote  ( 3530): v2
I/libpersona( 3530): KNOX_SDCARD checking this for 10101
I/libpersona( 3530): KNOX_SDCARD not a persona
I/SELinux ( 3530): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3530): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3530): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
W/libprocessgroup( 1016): failed to open /acct/uid_10157/pid_2794/cgroup.procs: No such file or directory
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3530): TimaSignature is unavailable
E/Zygote  ( 3544): MountEmulatedStorage()
I/libpersona( 3544): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3544): v2
I/libpersona( 3544): KNOX_SDCARD not a persona
I/SELinux ( 3544): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3544 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3544): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Killing 2841:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
E/SELinux ( 3544): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 3530): Added TimaKeyStore provider
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3544): TimaSignature is unavailable
D/ActivityThread( 3544): Added TimaKeyStore provider
E/Zygote  ( 3559): MountEmulatedStorage()
I/libpersona( 3559): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3559): v2
I/libpersona( 3559): KNOX_SDCARD not a persona
I/SELinux ( 3559): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3559): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3559): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3559 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2877:com.sec.usbsettings/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 3559): TimaSignature is unavailable
D/ActivityThread( 3559): Added TimaKeyStore provider
D/AndroidRuntime( 3517): 
D/AndroidRuntime( 3517): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3517): CheckJNI is OFF
D/AndroidRuntime( 3517): readGMSProperty: start
D/AndroidRuntime( 3517): readGMSProperty: already setted!!
D/AndroidRuntime( 3517): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3517): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3517): readGMSProperty: end
D/AndroidRuntime( 3517): addProductProperty: start
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
E/MTPRx   ( 3544): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
D/SecContentProvider2( 1016): mCursor = null
D/SecContentProvider2( 1016): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1016): mCursor = null
V/MTPRx   ( 3544): sealedState: false
V/MTPRx   ( 3544): sealedUsbMassStorageState: false
D/SettingsProvider( 1016): name = mtp_usb_connection_status
D/SettingsProvider( 1016): name = access_control_enabled
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1016): failed to open /acct/uid_10159/pid_2841/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2877/cgroup.procs: No such file or directory
E/Zygote  ( 3585): MountEmulatedStorage()
E/Zygote  ( 3585): v2
I/libpersona( 3585): KNOX_SDCARD checking this for 10069
I/libpersona( 3585): KNOX_SDCARD not a persona
I/SELinux ( 3585): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3585): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3585 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2807:com.sec.dsm.system/1000 (adj 15): empty #31
E/SELinux ( 3585): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SettingsProvider( 1016): name = media_player_mode
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
D/SettingsProvider( 1016): name = mtp_usb_conditions_met
D/TimaKeyStoreProvider( 3585): TimaSignature is unavailable
D/ActivityThread( 3585): Added TimaKeyStore provider
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
D/SettingsProvider( 1016): name = mtp_running_status
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/SettingsProvider( 1016): name = media_mount_count
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
E/AffinityControl( 3517): AffinityControl: registerfunction enter
D/AndroidRuntime( 3517): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
D/FileShare-Server( 3585): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/FocusedStackFrame( 1016): Set to : 0
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/Launcher.HomeView( 1497): onPause
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 1497
D/Launcher( 1497): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/AndroidRuntime( 3517): Shutting down VM
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : -2122120936
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=10 createSurf (1x1),1 flag=404, uhalitest
I/DBG_DM  ( 2944): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
D/SettingsProvider( 1016): name = mtp_sync_alive
E/Zygote  ( 3603): MountEmulatedStorage()
E/Zygote  ( 3603): v2
I/libpersona( 3603): KNOX_SDCARD checking this for 10155
I/libpersona( 3603): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3603 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3603): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
I/SELinux ( 3603): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3603): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/ActivityThread( 1497): updateVisibility : ActivityRecord{ae2a38 token=android.os.BinderProxy@1a206283 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/SettingsProvider( 1016): name = sdcard_launch
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
D/TimaKeyStoreProvider( 3603): TimaSignature is unavailable
D/ActivityThread( 3603): Added TimaKeyStore provider
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2807/cgroup.procs: No such file or directory
W/ContextImpl( 3135): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1497): onStop
V/ActivityThread( 1497): updateVisibility : ActivityRecord{ae2a38 token=android.os.BinderProxy@1a206283 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/SettingsProvider( 1016): name = boot_time_connected
D/PersonaManager( 1016): isKioskContainerExistOnDevice
D/SensorService( 1016): [SO] activate (ident=0xb95875f8, enabled=0)
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
D/Launcher( 1497): onTrimMemory. Level: 20
D/SensorManager( 1016): unregisterListener ::   
I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1016): [SO] changed settle time [1]
D/SensorService( 1016): [SO] setDelay [66000000]
D/SensorService( 1016): [SO] activate (ident=0xb987a4e8, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/SettingsProvider( 1016): name = mtp_open_session
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
I/PCWCLIENTTRACE_PushUtil( 3199): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3199): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3199): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3199): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3199): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3199): ACTION_BOOTUP - Push type: [SPP, GCM]
W/PCWCLIENTTRACE_PCWHandler( 3199): [ensureRegistration] - netwrok is not available. action ignored
D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
W/art     ( 3517): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3629): MountEmulatedStorage()
E/Zygote  ( 3629): v2
I/libpersona( 3629): KNOX_SDCARD checking this for 10031
I/libpersona( 3629): KNOX_SDCARD not a persona
,I/SELinux ( 3629): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3629): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3629 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 2892:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,E/SELinux ( 3629): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3629): TimaSignature is unavailable
I/WebViewFactory( 3603): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/SensorService( 1016): [SO] 0.134 0.383 10.132
D/SensorService( 1016): [SO] [100 -> 255]
,D/ActivityThread( 3629): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/LibraryLoader( 3603): Time to load native libraries: 3 ms (timestamps 52-55)
,I/LibraryLoader( 3603): Expected native library version number "",actual native library version number ""
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ResourcesManager( 3629): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2892/cgroup.procs: No such file or directory
,V/WebViewChromiumFactoryProvider( 3603): Binding Chromium to main looper Looper (main, tid 1) {24e14753}
,I/LibraryLoader( 3603): Expected native library version number "",actual native library version number ""
I/chromium( 3603): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ActivityManager( 1016): Killing 2927:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1016): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3648 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 3648): MountEmulatedStorage(),
,I/BrowserStartupController( 3603): Initializing chromium process, singleProcess=true,
,W/art     ( 3603): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 3603): ApplicationContext is null in ApplicationStatus,
,E/Zygote  ( 3648): v2,
,I/libpersona( 3648): KNOX_SDCARD checking this for 1000,
I/libpersona( 3648): KNOX_SDCARD not a persona,
,I/SELinux ( 3648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3648): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/chromium( 3603): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,W/chromium( 3603): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 3603): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 3603): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
D/TimaKeyStoreProvider( 3648): TimaSignature is unavailable
,D/ActivityThread( 3648): Added TimaKeyStore provider
,I/Adreno-EGL( 3603): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3603): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3603): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3603): Local Branch: 
I/Adreno-EGL( 3603): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3603): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3603):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2927/cgroup.procs: No such file or directory
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1016): getStreamVolume 3 index 0
,D/BluetoothAdapter( 3603): 1067118012: getState() :  mService = null. Returning STATE_OFF
,I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/8)
,I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/8)
,W/ContextImpl( 3648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
I/Gmail   ( 3530): getAccountsCursor
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3688): MountEmulatedStorage(),
I/VlingoApplication( 3629): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
E/Zygote  ( 3688): v2
I/libpersona( 3688): KNOX_SDCARD checking this for 1000
I/libpersona( 3688): KNOX_SDCARD not a persona
,I/SELinux ( 3688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3688 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3688): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BluetoothAdapter( 3629): 733922301: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3629): 733922301: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3629): 733922301: getState() :  mService = null. Returning STATE_OFF
,I/art     (  304): Explicit concurrent mark sweep GC freed 8753(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 653us total 28.769ms
,I/VlingoAndroidCore( 3629): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,D/TimaKeyStoreProvider( 3688): TimaSignature is unavailable
,D/ActivityThread( 3688): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 19.978ms
,W/chromium( 3603): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/ResourcesManager( 3688): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 18.493ms
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3135): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3135): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3135): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/GAV2    ( 3530): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/art     ( 3603): Attempt to remove local handle scope entry from IRT, ignoring
,D/VlingoApplication( 3629): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3629): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/DialogFlow( 3629): initQueue()
,W/AwContents( 3603): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 3603): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3603): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 3603): CordovaWebView is running on device made by: samsung
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,W/art     ( 3603): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3603): Attempt to remove local handle scope entry from IRT, ignoring
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3735): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3735 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
E/Zygote  ( 3735): v2
I/libpersona( 3735): KNOX_SDCARD checking this for 10032
I/libpersona( 3735): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Killing 2960:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
I/SELinux ( 3735): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/SELinux ( 3735): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3735): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/TimaKeyStoreProvider( 3735): TimaSignature is unavailable
,D/ActivityThread( 3735): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/OpenGLRenderer( 3603): Render dirty regions requested: true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,D/PhoneWindow( 3603): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3603): *FMB* isFloatingMenuEnabled return false
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 38682(1976KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 26MB/39MB, paused 2.712ms total 181.226ms
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/InputDispatcher( 1016): Focus entered window: 3603
,I/Gmail   ( 3530): Observing account changes for notifications
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3603): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 3603): Initialized EGL, version 1.4
,W/libprocessgroup( 1016): failed to open /acct/uid_10150/pid_2960/cgroup.procs: No such file or directory
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
D/OpenGLRenderer( 3603): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3603): Enabling debug mode 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/Gmail   ( 3530): Error finding the version of the Email provider.....
E/Gmail   ( 3530): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3530): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3530): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3530): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3530): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3530): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3530): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager( 1016): Killing 2860:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,W/EmailMigration( 3530): We do not support migrating this version of the Email provider.
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/DBG_DM  ( 2944): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,I/Gmail   ( 3530): getAccountsCursor
,D/PanelView( 1177): There is/are notification(s) 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/Timeline( 3603): Timeline: Activity_idle id: android.os.BinderProxy@21d775b5 time:40804
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1016): Displayed Component not be shown by security: +1s59ms
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
,I/SamsungIME( 1911): getCurrentCandidateView
,I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{14520360 u0 com.test.thalitest/.MainActivity t12} time:40821
W/ActivityManager( 1016): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,D/FactoryTestApp( 2548): [DummyFtClient$onDestroy](2548) Destroy DummyFtClient service
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,D/FactoryTestApp( 2548): [Support$Values.getString](2548) id=MODEL_COMMUNICATION_MODE, value=gsm
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/FactoryTestApp( 2548): [ModuleCommon$isConnectionModeNone](2548) mConnectionMode = gsm
,I/FactoryTestApp( 2548): [ModuleCommon$isRunningFtClient](2548) RUNNING_FTCLIENT : false
,D/FactoryTestApp( 2548): [DummyFtClient$onDestroy](2548) kill process
,I/Process ( 2548): Sending signal. PID: 2548 SIG: 9
,E/Zygote  ( 3773): MountEmulatedStorage()
,E/Zygote  ( 3773): v2
I/libpersona( 3773): KNOX_SDCARD checking this for 10104
,I/libpersona( 3773): KNOX_SDCARD not a persona
,I/SELinux ( 3773): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3773 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 3773): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3773): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_2860/cgroup.procs: No such file or directory
,I/GoogleHttpClient( 1667): GMS http client unavailable, use old client
,D/TimaKeyStoreProvider( 3773): TimaSignature is unavailable
,D/ActivityThread( 3773): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 3530): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@1797fa1c that was originally bound here
E/ActivityThread( 3530): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@1797fa1c that was originally bound here
E/ActivityThread( 3530): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3530): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3530): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3530): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3530): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3530): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3530): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3530): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3530): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3530): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3530): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3530): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3530): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3530): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3530): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1016): Unbind failed: could not find connection for android.os.BinderProxy@3a43dae
,W/ResourcesManager( 3773): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Process com.sec.factory (pid 2548)(adj 0) has died(201,1074)
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3794): MountEmulatedStorage()
,E/Zygote  ( 3794): v2
I/libpersona( 3794): KNOX_SDCARD checking this for 10033
I/libpersona( 3794): KNOX_SDCARD not a persona
,I/SELinux ( 3794): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3794): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3794 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SurfaceFlinger(  258): id=10 Removed uhalitest (7/8)
I/ActivityManager( 1016): Killing 2822:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
I/SurfaceFlinger(  258): id=10 Removed uhalitest (-2/8)
,E/SELinux ( 3794): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3794): TimaSignature is unavailable
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3648): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 3648): Resource data:2131165186
D/ActivityThread( 3794): Added TimaKeyStore provider
,W/ResourcesManager( 3648): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3648): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3648): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/libprocessgroup( 1016): failed to open /acct/uid_10085/pid_2822/cgroup.procs: No such file or directory
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/AMMetaDataParserService( 3648): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,W/ContextImpl( 1928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/SecUISvc( 1928): Service started flags 0 startId 1
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,D/SecUISvc( 1928): Thread created.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3815): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3815 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 3815): v2
I/libpersona( 3815): KNOX_SDCARD checking this for 10028
I/SELinux ( 3815): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3815): KNOX_SDCARD not a persona
,I/SELinux ( 3815): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3815): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3815): TimaSignature is unavailable
,D/ActivityThread( 3815): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 3000:com.policydm/1000 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 2984:com.samsung.android.app.colorblind/1000 (adj 15): empty #32
,W/BindingManager( 3603): Cannot call determinedVisibility() - never saw a connection for the pid: 3603
,D/SamsungIME( 1911): Dismiss ExpandCandiate
,I/AMMetaDataParserService( 3648): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,D/TimaService( 1016): TIMA: in getTimaVersion
,D/TimaService( 1016): TIMA3: KeyStore3_init
E/TLC_TZ_KEYSTORE: ( 1016): Inside TZ_KEYSTORE_initialize()
D/TimaService( 1016): TIMA: in getTimaVersion
I/TLC_TZ_KEYSTORE: ( 1016): creating new keystore context...
I/TLC_TZ_KEYSTORE: ( 1016): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 1016): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1016): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1016): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x880
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 8
,I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
,I/TLC_TZ_KEYSTORE: ( 1016): ctx = 0xb968a808, comm = 0xb9761fd0, sendmsg = 0xa0dfc000, recvmsg = 0xa0dfc440
,I/TZ_init: ( 1016): TZ_init: sending initialization request...
,E/TZ_init: ( 1016): TZ_init Process: Secure memory is not initialized!
,E/TZ_init: ( 1016): trustlet initialization failed
I/TZ_init: ( 1016): TZ_init_START...
,I/TZ_init: ( 1016): TZ_init_with_data: sending initialization request...
,I/TZ_init: ( 1016): TZ_init: successful initialization
,D/QSEECOMAPI: ( 1016): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1016): QSEECom_shutdown_app, app_id = 8
,E/TLC_TZ_KEYSTORE: ( 1016): Count : 1, Ret : 0
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2984/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3000/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3648): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,E/SQLiteLog( 3530): (283) recovered 166 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/ResourcesManager( 3794): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3794): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3794): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 3794): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3794): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3794): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3794): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3794): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3794): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
W/ContextImpl( 3648): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserSer,vice( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,D/JsMessageQueue( 3603): Set native->JS mode to OnlineEventsBridgeMode
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3648): Resource data:2131034113
,W/ContextImpl( 3688): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,W/ResourcesManager( 3648): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3648): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3648): took 2.280364ms for 0*0 texture 0
,E/Zygote  ( 3840): MountEmulatedStorage()
I/libpersona( 3840): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3840): v2
I/libpersona( 3840): KNOX_SDCARD not a persona
,I/SELinux ( 3840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3840): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3840 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/GFX generate_partition_tables( 3648): took 6.568335ms for 0*0 texture 0
,I/GFX raster( 3648): took 10.339115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a97e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb91a97a8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3840): TimaSignature is unavailable
,D/ActivityThread( 3840): Added TimaKeyStore provider
,I/SamsungIME( 1911): getDebugLevel  : 0x4f4c
,E/File    ( 3530): fail readDirectory() errno=2
,I/AMMetaDataParserService( 3648): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/ResourcesManager( 3840): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/SEAMService( 1016):  hashset_to_int_array returning null
,W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,I/DBG_DM  ( 2944): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,I/F_PHONE ( 3840): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,D/ActivityManager( 1016): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.810677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a97e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb91a97a8 counterpartCT=4 counterpartW=96 counterparth=96
,W/SEAMService( 1016):  hashset_to_int_array returning null
,E/SQLiteLog( 3688): (284) automatic index on seams_container_info(seams_container_id)
,I/AMMetaDataParserService( 3648): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/SQLiteLog( 3688): (284) automatic index on seams_container_info(sp_id)
,W/SEAMService( 1016):  hashset_to_int_array returning null
,I/SamsungIME( 1911): getDebugLevel  : 0x4f4c
,D/jxcore_app_log( 3603): JniHelper::setJavaVM(0xb8dd1450), pthread_self() = -1187842712
,I/SamsungIME( 1911): KeybaordView init() : load resources
,D/F_PHONE ( 3840): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 3840): default registerAction()
I/F_PHONE ( 3840): [[com.sec.bcservice]] sendPendingMessage()
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3603): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3603):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3603):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3603):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3603):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3603): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31389c08 added. We now have 1 listener(s)
,D/Finsky  ( 3815): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Gmail   ( 3530): notifyAccountChanged
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3603): setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3603): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3603): setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3603): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3603):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3603):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3603):     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3603):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3603):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3603):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3603):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3603):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3603):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3603): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bf70b4 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3603): addListener: New listener added - the number of listeners is now 1
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3648): took 2.558021ms for 0*0 texture 0
,I/Gmail   ( 3530): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3603): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3603): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3603): setDiscoveryMode: Discovery mode BLE is supported
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3603): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,I/GFX generate_partition_tables( 3648): took 7.475833ms for 0*0 texture 0
,I/GFX raster( 3648): took 11.100625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a97a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91ae298 counterpartCT=4 counterpartW=96 counterparth=96
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3603): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/Gmail   ( 3530): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/SamsungIME( 1911): getCurrentKeyboard
I/SamsungIME( 1911): getTextKeyboard
,I/chromium( 3603): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SamsungIME( 1911): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 3773): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3773): MmsConfig.loadMmsSettings
I/Babel   ( 3773): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 3773): MmsConfig.loadFromDatabase
,I/AMMetaDataParserService( 3648): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.591979ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91b2e40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91b2f98 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/Gmail   ( 3530): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.817031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91af848 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91af9a0 counterpartCT=4 counterpartW=96 counterparth=96
,E/Babel   ( 3773): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3773): MmsConfig.loadFromResources
,E/Babel   ( 3773): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3773): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/AMMetaDataParserService( 3648): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/art     ( 3815): Verification of android.content.Intent com.google.android.finsky.utils.NotificationManager.createDefaultClickIntent(android.content.Context, java.lang.String, java.lang.String, java.lang.String, java.lang.String) took 190.886ms
,I/Process ( 3794): Sending signal. PID: 3794 SIG: 9
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Gmail   ( 3530): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.629011ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a9c30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91ae328 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Process com.sec.android.app.sns3 (pid 3794)(adj 0) has died(122,1110)
,W/Settings( 3773): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3735): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,E/Zygote  ( 3891): MountEmulatedStorage(),
I/libpersona( 3891): KNOX_SDCARD checking this for 10034
E/Zygote  ( 3891): v2
,I/libpersona( 3891): KNOX_SDCARD not a persona
I/SELinux ( 3891): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3891): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3891): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528,
,I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3891 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a,
,D/TimaKeyStoreProvider( 3891): TimaSignature is unavailable
,D/ActivityThread( 3891): Added TimaKeyStore provider
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.690781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91ae328 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91ab9d8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3735): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3735): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3735): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3648): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.641718ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a9f58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91abac0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131034113
,I/AMMetaDataParserService( 3648): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.960208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9171878 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb91b1bf8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.981250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9171878 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9174e60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.725104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb90ec198 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9191750 counterpartCT=4 counterpartW=96 counterparth=96
,I/Babel_StickerModule( 3773): App launched.
,I/Babel_StickerModule( 3773): Sticker update initiated. last:1456825783062 empty:false
,I/AMMetaDataParserService( 3648): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.594687ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91b1bf8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91a9f08 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,V/Babel   ( 3773): babel boot account: SMS
,W/Babel   ( 3773): EsDatabaseHelper.static should not be called on main thread [called on main thread]
,W/Babel   ( 3773): java.lang.Exception
W/Babel   ( 3773): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3773): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 3773): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3773): 	at ckh.a(SourceFile:67)
W/Babel   ( 3773): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3773): 	at bhn.a(SourceFile:301)
W/Babel   ( 3773): 	at bhn.a(SourceFile:137)
W/Babel   ( 3773): 	at bhn.a(SourceFile:126)
W/Babel   ( 3773): 	at bhn.a(SourceFile:159)
W/Babel   ( 3773): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3773): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3773): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3773): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3773): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3773): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3773): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3773): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3773): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3773): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3773): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/Babel   ( 3773): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3773): java.lang.Exception
W/Babel   ( 3773): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3773): 	at aes.a(SourceFile:145)
W/Babel   ( 3773): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3773): 	at ckh.a(SourceFile:67)
W/Babel   ( 3773): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3773): 	at bhn.a(SourceFile:301)
W/Babel   ( 3773): 	at bhn.a(SourceFile:137)
W/Babel   ( 3773): 	at bhn.a(SourceFile:126)
W/Babel   ( 3773): 	at bhn.a(SourceFile:159)
W/Babel   ( 3773): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3773): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3773): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3773): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3773): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3773): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3773): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3773): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3773): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3773): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3773): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.854219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9174e60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91720c8 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3648): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3919): MountEmulatedStorage(),
E/Zygote  ( 3919): v2
I/libpersona( 3919): KNOX_SDCARD checking this for 1000
I/libpersona( 3919): KNOX_SDCARD not a persona
,I/SELinux ( 3919): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3919): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3919): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=3919 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.630625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a9c30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91a9f08 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Killing 3009:com.google.android.configupdater/u0a86 (adj 15): empty #31
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2944): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,V/Babel   ( 3773): babel boot account: thalitester@gmail.com,
,D/Finsky  ( 3815): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Babel   ( 3773): EsDatabaseHelper.getDatabaseHelper() [called on main thread],
W/Babel   ( 3773): java.lang.Exception
,W/Babel   ( 3773): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3773): 	at aes.a(SourceFile:145)
W/Babel   ( 3773): 	at ckh.<init>(SourceFile:103),
W/Babel   ( 3773): 	at ckh.a(SourceFile:67)
W/Babel   ( 3773): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3773): 	at bhn.a(SourceFile:301)
,W/Babel   ( 3773): 	at bhn.a(SourceFile:137)
W/Babel   ( 3773): 	at bhn.a(SourceFile:126)
W/Babel   ( 3773): 	at bhn.a(SourceFile:159)
W/Babel   ( 3773): 	,at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3773): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3773): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3773): 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3773): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3773): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3773): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
,W/Babel   ( 3773): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3773): ,	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3773): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3773): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/TimaKeyStoreProvider( 3919): TimaSignature is unavailable
D/ActivityThread( 3919): Added TimaKeyStore provider
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.691041ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91ae328 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91720c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/Gmail   ( 3530): getAccountsCursor
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.625157ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a9f58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91a9f08 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3648): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/Settings( 3815): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Zygote  ( 3939): MountEmulatedStorage()
E/Zygote  ( 3939): v2
I/libpersona( 3939): KNOX_SDCARD checking this for 1000
I/libpersona( 3939): KNOX_SDCARD not a persona
,I/SELinux ( 3939): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/Settings( 3815): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SELinux ( 3939): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3939): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3939 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  283): getCameraInfo: X
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3648): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3648): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131034112
,I/AMMetaDataParserService( 3648): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.809739ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91b1bf8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91a9f08 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3939): TimaSignature is unavailable
,D/ActivityThread( 3939): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3648): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,I/DBG_POLICYDM( 3919): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 3919): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/ActivityManager( 1016): Killing 3111:com.dropbox.android/u0a92 (adj 15): empty #31
,D/Volley  ( 3815): [581] DiskBasedCache.clear: Cache cleared.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Volley  ( 3815): [588] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 3815): Skipping gmscore version check
,W/VideoCapabilities( 3773): Unrecognized profile 2130706433 for video/avc
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/DBG_POLICYDM( 3919): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 3919): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.606927ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91b1bf8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91720c8 counterpartCT=4 counterpartW=96 counterparth=96
,W/AudioCapabilities( 3773): Unsupported mime audio/evrc
,I/AMMetaDataParserService( 3648): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,W/AudioCapabilities( 3773): Unsupported mime audio/qcelp
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3919): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,D/Finsky  ( 3815): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3815): [1] Libraries$2.run: Finished loading 1 libraries.
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.641302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a9f08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9191750 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 3919): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,W/AudioCapabilities( 3773): Unsupported mime audio/mpeg-L1
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
W/AudioCapabilities( 3773): Unsupported mime audio/mpeg-L2
I/AMMetaDataParserService( 3648): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3919): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,I/ActivityManager( 1016): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3963 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3036:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,E/Zygote  ( 3963): MountEmulatedStorage()
I/libpersona( 3963): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3963): v2
I/libpersona( 3963): KNOX_SDCARD not a persona
,I/SELinux ( 3963): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3963): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3963): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.642865ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a9c30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91720c8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3963): TimaSignature is unavailable
,D/ActivityThread( 3963): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,W/AudioCapabilities( 3773): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3773): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3773): Unsupported mime audio/qcelp
,I/DBG_POLICYDM( 3919): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3919): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,W/AudioCapabilities( 3773): Unsupported mime audio/evrc
,I/DBG_POLICYDM( 3919): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3919): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,W/VideoCapabilities( 3773): Unsupported mime video/wvc1
,W/VideoCapabilities( 3773): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3773): Unrecognized profile/level 32768/2 for video/mp4v-es
,I/DBG_POLICYDM( 3919): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,D/KnoxSetupWizardDbHelper( 3963): dbMigrationFlag : false
,W/VideoCapabilities( 3773): Unsupported mime video/wvc1
,W/VideoCapabilities( 3773): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3773): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 3773): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 3773): Unsupported mime video/mp43
,D/ShortcutReceiver( 3963):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/KnoxShortcutUtil( 3963): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 3963):  KnoxContainerVersion 2.4.0
,D/ShortcutReceiver( 3963):  shortcut migration not required 
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131034113
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,I/AMMetaDataParserService( 3648): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/VideoCapabilities( 3773): Unsupported mime video/sorenson
,I/GFX raster( 3648): took 1.033853ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9171878 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb91720c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/DBG_POLICYDM( 3919): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3919): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 3919): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
I/GFX raster( 3648): took 0.847604ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9171878 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9191750 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/DBG_POLICYDM( 3919): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,E/Zygote  ( 3980): MountEmulatedStorage()
I/libpersona( 3980): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3980): v2
I/libpersona( 3980): KNOX_SDCARD not a persona
I/SELinux ( 3980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3980 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3980): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 3159:com.fmm.dm/1000 (adj 15): empty #31
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.606198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb90ec198 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91720c8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
I/AMMetaDataParserService( 3648): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 3773): Unsupported mime video/mp4v-esdp
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3980): TimaSignature is unavailable,
,D/ActivityThread( 3980): Added TimaKeyStore provider
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.655157ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91b1bf8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9191750 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=3995 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3178:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,E/Zygote  ( 3995): MountEmulatedStorage()
,E/Zygote  ( 3995): v2
I/libpersona( 3995): KNOX_SDCARD checking this for 10035
I/libpersona( 3995): KNOX_SDCARD not a persona
,I/SELinux ( 3995): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3995): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3995): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/art     (  304): Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 668us total 31.196ms
,I/AMMetaDataParserService( 3648): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 17.540ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 16.934ms
,D/TimaKeyStoreProvider( 3995): TimaSignature is unavailable
,D/ActivityThread( 3995): Added TimaKeyStore provider
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.819792ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9174e60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91720c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/KnoxSetupWizardClient( 3980): isShipMode : 1
I/KnoxSetupWizardClient( 3980): onReceive : android.intent.action.BOOT_COMPLETED
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.643958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a9c30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9191750 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/VideoCapabilities( 3773): Unsupported profile 4 for video/mp4v-es
,D/FileApkUtils( 2039): Spent 138ms computing apk sha1.
,D/FileApkUtils( 2039): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 2039): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-ca8b2a9144773fc3650c54ed299f2d4558171b12@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.712552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91ae328 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91720c8 counterpartCT=4 counterpartW=96 counterparth=96
,D/DexOptUtils( 2039): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 2039): Lollipop platform, using <isa> directory.
,D/DexOptUtils( 2039): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 2039): Primary ABI of odexing process is armeabi-v7a
,I/AMMetaDataParserService( 3648): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/jxcore-log( 3603): Initializing JXcore engine
W/jxcore-log( 3603): JXcore engine is ready
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4013): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4013 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/Zygote  ( 4013): v2
I/ActivityManager( 1016): Killing 3216:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
I/libpersona( 4013): KNOX_SDCARD checking this for 10107
I/libpersona( 4013): KNOX_SDCARD not a persona
I/SELinux ( 4013): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4013): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4013): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4013): TimaSignature is unavailable
,D/ActivityThread( 4013): Added TimaKeyStore provider
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.552603ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a9f58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9191750 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/audit   ( 1909): type=1400 msg=audit(1457690682.261:203): avc:  denied  { ioctl } for  pid=3874 comm="Thread-563" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1909):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1909): type=1300 msg=audit(1457690682.261:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9e8048f8 items=0 ppid=304 ppcomm=main pid=3874 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-563" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1909): type=1320 msg=audit(1457690682.261:203): 
,I/DBG_DM  ( 2944): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
W/ContextImpl( 3648): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,W/jxcore-log( 3603): Starting JXcore engine
,D/Finsky  ( 3815): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131165203
,W/ResourcesManager( 3648): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3648): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/System.err( 3980): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 3980): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3980): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3980): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 3980): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 3980): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3980): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,I/AMMetaDataParserService( 3648): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3648): took 2.630572ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3648): took 10.128855ms for 0*0 texture 0
,I/GFX raster( 3648): took 13.623176ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9361f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb91af400 counterpartCT=4 counterpartW=96 counterparth=96
,I/Babel   ( 3773): Creating RTCS
,D/Finsky  ( 3815): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/AMMetaDataParserService( 3648): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,E/SMD     (  288): DCD OFF
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/GFX raster( 3648): took 0.808437ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb917e098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb917e140 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,W/InstanceID/Rpc( 2039): Found 10012
,W/jxcore-log( 3603): Platform android
W/jxcore-log( 3603): 
W/jxcore-log( 3603): Process ARCH arm
W/jxcore-log( 3603): 
,E/SPPClientService( 3995): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,E/SPPClientService( 3995): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 3995): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 3995): PushLog.txt file is not deleted.
D/SPPClientService( 3995): PushLog.txt file is not deleted.
D/SPPClientService( 3995): ============PushLog. stop!
,D/SSRM:n  ( 1016): SIOP:: AP = 380
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.847656ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb917e098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb91ae088 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.768177ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb917e098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9174e60 counterpartCT=4 counterpartW=96 counterparth=96
,I/System.out( 3815): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 3815): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3815): (HTTPLog)-Static: isShipBuild true
I/System.out( 3815): (HTTPLog)-Thread-593-1010637975: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3815): (HTTPLog)-Static: isSBSettingEnabled false
,I/AMMetaDataParserService( 3648): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10028
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/dex2oat ( 4029): ----------------------------------------------------
I/dex2oat ( 4029): <SS>: S T A R T I N G . . .
I/dex2oat ( 4029): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 4029): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk --oat-fd=41 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m,
E/SQLiteLog( 3773): (284) automatic index on conversation_participants_view(conversation_id)
I/libpersona( 4047): KNOX_SDCARD checking this for 10041
E/Zygote  ( 4047): MountEmulatedStorage()
I/libpersona( 4047): KNOX_SDCARD not a persona
E/Zygote  ( 4047): v2
I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4047 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4047): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4047): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4047): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 3231:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10086/pid_3009/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_3111/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_3036/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3159/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10003/pid_3178/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_3216/cgroup.procs: No such file or directory
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3648): took 0.598646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb90ec198 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91721d8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.649271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb90ec198 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91ae088 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,D/TimaKeyStoreProvider( 4047): TimaSignature is unavailable
,D/ActivityThread( 4047): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
W/ContextImpl( 3648): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 32558(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 26MB/39MB, paused 3.822ms total 168.228ms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
,D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
,W/libprocessgroup( 1016): failed to open /acct/uid_10060/pid_3231/cgroup.procs: No such file or directory
,E/SQLiteLog( 3773): (284) automatic index on conversation_participants_view(conversation_id)
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131099648
,E/SQLiteLog( 3773): (284) automatic index on conversation_participants_view(conversation_id)
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 3648): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3648): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.685104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a94e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91a8ff0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3648): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/SQLiteLog( 3773): (284) automatic index on conversation_participants_view(conversation_id)
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2039): Reading stored module config
,D/ChimeraCfgMgr( 2039): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 3773): (284) automatic index on conversation_participants_view(conversation_id)
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3648): took 2.408072ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3648): took 8.782293ms for 0*0 texture 0
,I/GFX raster( 3648): took 12.141980ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9198300 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb91a8ff0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,D/BootCompletedReceiver( 2039): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 2039): Got an BootCompleted event.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 3603): JXcore Cordova bridge is ready!
I/jxcore-log( 3603): 
,W/jxcore-log( 3603): JXcore engine is started
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.640521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a8ff0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb96ba310 counterpartCT=4 counterpartW=96 counterparth=96
,I/org.thaliproject.p2p.ThaliPermissions( 3603): execute: REQUEST_ACCESS_COARSE_LOCATION
,D/BootCompletedReceiver( 2039): Will NOT schedule AdAttestation signal task because it's disabled.
,D/GCM     ( 2039): COMPAT: Multi user not supported
,E/jxcore  ( 3603): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3603): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3648): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/chromium( 3603): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/SA      ( 4047): [SSP] onCreated
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/FocusedStackFrame( 1016): Set to : 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/GCM     ( 1812): COMPAT: Multi user not supported
,D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 3603
,W/ResourcesManager( 3773): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3773): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (171 us)
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.746979ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb919d8c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb919db10 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,I/AMMetaDataParserService( 3648): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/PluginManager( 3603): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 53ms. Plugin should use CordovaInterface.getThreadPool().
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1016): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1016): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1016): [SO] activate (ident=0xb987a4e8, enabled=0)
,I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/GCoreUlr( 2039): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Launcher( 1497): onRestart, Launcher: 1067118012
,D/Launcher( 1497): onStart, Launcher: 1067118012
,D/Launcher.HomeView( 1497): onStart
D/Launcher( 1497): onResume, Launcher: 1067118012
,I/SA      ( 4047): [TPM] There is no property file
,D/SettingsProvider( 1016): name = kids_home_mode
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10007
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/Launcher.HomeView( 1497): onResume
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.651303ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9196cb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9196f48 counterpartCT=4 counterpartW=96 counterparth=96
,D/SensorManager( 1016): unregisterListener ::   
,I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1016): [SO] changed settle time [0]
,D/SensorService( 1016): [SO] setDelay [200000000]
,D/SensorService( 1016): [SO] activate (ident=0xb960ddf8, enabled=1)
V/JNIHelp ( 3773): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/SensorService( 1016): [SO] AR_init
,I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/SA      ( 4047): [SCU] isHaveSA() - false
,I/SA      ( 4047): [TPM] getModelProperty : null
,I/SA      ( 4047): [TPM] getCSCProperty : null
,I/SA      ( 4047): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4047): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4047): [DM] TFT FEATURE: false
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/Launcher( 1497): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1497): onResume
,D/ActivityManager( 1016): handle home activity for 0
,I/WallpaperManagerService( 1016): switchPersonaWallpaper is called for personaId-0
,D/KnoxTimeoutHandler( 1016): post home show event for user 0
,D/WallpaperManagerService( 1016):  force update = false; persona id = 0; current user =0; current persona = 0
,D/KnoxTimeoutHandler( 1016): handleHomeShow for 0 and current 0
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,I/SA      ( 4047): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4047): [DM] init START
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,I/SA      ( 4047): [DM] This device is not a Vodafone
,I/SurfaceFlinger(  258): id=12 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ResourceType( 4047): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4047): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 4047): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 4047): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 4047): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4047): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4047): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1016): Focus entered window: 1497
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1497): log_dcs ThreadedRenderer::initialize entered! 
,I/CheckinService( 2039): Checkin interval check for package: unspecified last checkin: 1456600236354 min interval config: 0 actual interval: 1090446935,
,W/ResourceType( 4047): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4047): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4047): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4047): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 4047): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4047): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,I/DBG_DM  ( 2944): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,W/ResourceType( 4047): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4047): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4047): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4047): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4047): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4047): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75),
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.727031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9198520 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb918fcf8 counterpartCT=4 counterpartW=96 counterparth=96
,D/Launcher( 1497): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityThread( 3773): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3773): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@193b2e91: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3773): Installed default security provider GmsCore_OpenSSL
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1177): There is/are notification(s) 
,W/IInputConnectionWrapper( 3603): showStatusIcon on inactive InputConnection
,W/ResourceType( 4047): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4047): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4047): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4047): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4047): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4047): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/Babel   ( 3773): Destroying RTCS
,I/AMMetaDataParserService( 3648): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/SamsungIME( 1911): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/SystemUpdateService( 2039): onCreate
,I/SA      ( 4047): [SCU] isHaveSA() - false
I/SA      ( 4047): support phone number id : false
I/SA      ( 4047): [DM] Supports Ref Jpn : true
,I/SA      ( 4047): [DM] init END
,I/Timeline( 1497): Timeline: Activity_idle id: android.os.BinderProxy@1a206283 time:44934
,I/SA      ( 4047): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 4047): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,D/ActivityManager( 1016): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4047): [OR] onReceive END
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131099648
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
I/AMMetaDataParserService( 3648): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.730052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a94e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb918fcf8 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/CheckinService( 2039): Disabling old GoogleServicesFramework version,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3648): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,E/Zygote  ( 4089): MountEmulatedStorage(),
,E/Zygote  ( 4089): v2
,I/libpersona( 4089): KNOX_SDCARD checking this for 10042,
,I/ActivityManager( 1016): Displayed Component not be shown by security: +282ms,
,I/ActivityManager( 1016): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4089 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/libpersona( 4089): KNOX_SDCARD not a persona,
,I/SELinux ( 4089): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4089): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4089): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/SystemUpdateService( 2039): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/TimaKeyStoreProvider( 4089): TimaSignature is unavailable
,D/ActivityThread( 4089): Added TimaKeyStore provider
,I/SA      ( 4047): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4047): [ODM] queryOpenData(key= GEO_IP )
,W/ResourcesManager( 4089): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.636666ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9198300 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb916ea30 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3648): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/SA      ( 4047): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4047): [LBE] REF_JPN : true
,I/SA      ( 4047): [BDC] create
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,V/AuthZen ( 2039): Handling intent: android.intent.action.BOOT_COMPLETED
,D/SamsungIME( 1911): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.631198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a8ff0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb918fcf8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/SensorService( 1016): [SO] currT = 45170140971, prevT = 44720097222, diff = 450043749, [0.134 0.364 10.132]
D/SensorService( 1016): [SO] 0.134 0.364 10.132
D/SensorService( 1016): [SO] [100 -> 255]
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,D/AuthZenEventHandler( 2039): Handling event: android.intent.action.BOOT_COMPLETED
,I/CalendarProvider2( 4089): CalendarProvider2.onCreate() called
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SystemUpdateService( 2039): cancelUpdate (empty URL)
I/SystemUpdateService( 2039): active receiver: disabled
,I/SA      ( 4047): [DBMV2] getEmailID
,I/SA      ( 4047): [DBMV2] getDataV02ForItems
I/SA      ( 4047): [SSP] query invoked
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1016): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/SA      ( 4047): [SCU] get signed id from samsung account2.0 DB.
,I/SA      ( 4047): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4047): [BDC] destroy
,W/BaseAppContext( 2039): Using Auth Proxy for data requests.
,I/CheckinService( 2039): Checking schedule, now: 1457690683699 next: 1457139499243
I/CheckinService( 2039): active receiver: enabled
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.874583ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb916ea30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb918fcf8 counterpartCT=4 counterpartW=96 counterparth=96
,I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{6b8a17e u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:45380
,I/AMMetaDataParserService( 3648): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/ActivityManager( 1016): Killing 3249:com.fmm.ds/1000 (adj 15): empty #31
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (7/8)
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/8)
,V/AlarmManager( 1016): waitForAlarm result :4,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,E/BaseAppContext( 2039): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.860417ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb919d8c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91abda8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/GAV2    ( 3530): Thread[GAThread,5,main]: No campaign data found.
,I/AuthZen ( 2039): Fetching signing key...
,D/SystemUpdateService( 2039): onDestroy
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.900833ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9190820 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb914cfd0 counterpartCT=4 counterpartW=96 counterparth=96
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,I/AMMetaDataParserService( 3648): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131099648
,I/AMMetaDataParserService( 3648): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3249/cgroup.procs: No such file or directory
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 1.005156ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb90ec198 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9163500 counterpartCT=4 counterpartW=96 counterparth=96
,W/BindingManager( 3603): Cannot call determinedVisibility() - never saw a connection for the pid: 3603
,I/AuthZen ( 2039): Signing key fetched successfully!
,I/AMMetaDataParserService( 3648): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/BaseAppContext( 2039): Using Auth Proxy for data requests.
,I/art     ( 1667): Explicit concurrent mark sweep GC freed 5069(206KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 11.169ms total 36.010ms
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.752395ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91ab8e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9173be8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/SQLiteConnectionPool( 1667): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/a       ( 2039): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 2039): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2039): Clearing transaction cache
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.644689ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a8ff0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb91ac1f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/ActivityManager( 1016): Killing 3282:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4315, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1433): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1433): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.677760ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb916ea30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9173be8 counterpartCT=4 counterpartW=96 counterparth=96
,I/System.out( 3629): INFO:Resource not found:/Common.properties Using default values
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10062/pid_3282/cgroup.procs: No such file or directory
,I/SecDataIO(  257): Write to block
,W/ContextImpl( 2530): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/AMMetaDataParserService( 3648): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/Process ( 2530): Sending signal. PID: 2530 SIG: 9
,I/GCoreUlr( 1812): DispatchingService.onCreate()
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.637343ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb919d8c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91ac1f8 counterpartCT=4 counterpartW=96 counterparth=96
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
I/DBG_DM  ( 2944): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/DBG_DM  ( 2944): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,D/GCM     ( 1812): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,E/DBG_DM  ( 2944): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/DBG_DM  ( 2944): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,D/StrictMode( 4013): StrictMode policy violation; ~duration=1797 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4013): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4013): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4013): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4013): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4013): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4013): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4013): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4013): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4013): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4013): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4013): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4013): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4013): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4013): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4013): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4013): StrictMode policy violation; ~duration=1775 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4013): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4013): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4013): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4013): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4013): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4013): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4013): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4013): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4013): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4013): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4013): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4013): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4013): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4013),: 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4013): StrictMode policy violation; ~duration=1561 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4013): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4013): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4013): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4013): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4013): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4013): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4013): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4013): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4013): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4013): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4013): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4013): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4013): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4013): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4013): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4013): StrictMode policy violation; ~duration=1559 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4013): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4013): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4013): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4013): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4013): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4013): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4013): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4013): 	at android.app.Instrumentation.callApplicationOnCreate(Inst,rumentation.java:1020)
D/StrictMode( 4013): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4013): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4013): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4013): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4013): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4013): StrictMode policy violation; ~duration=1557 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4013): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4013): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4013): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4013): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4013): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4013): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4013): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4013): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4013): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4013): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4013): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4013): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4013): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4013): StrictMode policy violation; ~duration=1555 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4013): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4013): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4013): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4013): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4013): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4013): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4013): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4013): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4013): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4013): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4013): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4013): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4013): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4013): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4013): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4013): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4013): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4013): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4013): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4013): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4013): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4013): StrictMode policy violation; ~duration=1553 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4013): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4013): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4013): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4013): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4013): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4013): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4013): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4013): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4013): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4013): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4013): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4013): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4013): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4013): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4013): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4013): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4013): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4013): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4013): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4013): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4013): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4013): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4013): StrictMode policy violation; ~duration=1520 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4013): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4013): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4013): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4013): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4013): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4013): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4013): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4013): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4013): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4013): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4013): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4013): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4013): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4013): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4013): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
D/StrictMode( 4013): StrictMode policy violation; ~duration=1520 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4013): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4013): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4013): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4013): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4013): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4013): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4013): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4013): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4013): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4013): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4013): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4013): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4013): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4013): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4139): MountEmulatedStorage()
E/Zygote  ( 4139): v2
I/libpersona( 4139): KNOX_SDCARD checking this for 1000
I/libpersona( 4139): KNOX_SDCARD not a persona
I/SELinux ( 4139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4139): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 2944): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
I/ActivityManager( 1016): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4139 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/DBG_DM  ( 2944): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
I/DBG_DM  ( 2944): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
I/ActivityManager( 1016): Process com.sec.android.app.sysscope (pid 2530)(adj 0) has died(60,1136)
I/iu.UploadsManager( 2039): End new media; added: 0, uploading: 0, time: 374 ms
E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3648): took 0.730417ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9190820 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91af230 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/TimaKeyStoreProvider( 4139): TimaSignature is unavailable
,E/DBG_DM  ( 2944): [IlIIlIIlIllllIlllIII(226/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
,D/ActivityThread( 4139): Added TimaKeyStore provider
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2944): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,I/ActivityManager( 1016): Killing 3057:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,W/Auth    ( 1812): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusChecker( 4139): onReceive : android.intent.action.BOOT_COMPLETED
,I/StatusChecker( 4139): onReceive : net.mt.init : DONE
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131099648
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3648): getResourceName:com.android.mms:xml/assistant_messaging,
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.705781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb90ec198 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9191750 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3648): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/Zygote  ( 4163): MountEmulatedStorage()
,E/Zygote  ( 4163): v2
I/libpersona( 4163): KNOX_SDCARD checking this for 10116
,I/libpersona( 4163): KNOX_SDCARD not a persona
I/SELinux ( 4163): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SELinux ( 4163): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4163): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4163 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 1277:com.android.defcontainer/u0a4 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4163): TimaSignature is unavailable
,W/GCoreFlp( 1812): No location to return for getLastLocation()
D/ActivityThread( 4163): Added TimaKeyStore provider
,W/FusedLocationProvider( 1812): location=null
,W/GCoreFlp( 1812): No location to return for getLastLocation()
,W/FusedLocationProvider( 1812): location=null
,I/PageBuddyNotiSvc( 4163): Intent received : action=android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4163): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/PageBuddyNotiSvc( 4163): onCreate mCpBitFlag=0
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.758596ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91ab8e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb918fcf8 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4179): MountEmulatedStorage()
,E/Zygote  ( 4179): v2
I/libpersona( 4179): KNOX_SDCARD checking this for 10125
I/libpersona( 4179): KNOX_SDCARD not a persona
,I/SELinux ( 4179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4179 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/AMMetaDataParserService( 3648): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/SELinux ( 4179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4179): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1016): failed to open /acct/uid_10009/pid_3057/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10004/pid_1277/cgroup.procs: No such file or directory
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.689479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a8ff0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb91ac1f8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4179): TimaSignature is unavailable
,I/AMMetaDataParserService( 3648): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ActivityThread( 4179): Added TimaKeyStore provider
,D/PersistentNotificationBroadcastReceiver( 1812): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/ResourcesManager( 4179): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4179): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4179): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/art     ( 3629): Suspending all threads took: 20.597ms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.820677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb916ea30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb91abda8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3648): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/QuickConnect( 4179): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 4179): Util.setSCRunningSetting - [value]0
,D/SettingsProvider( 1016): name = scon_is_running
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10125
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.627188ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb919d8c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91363b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520,
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10125,
,I/QuickConnect( 4179): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/QuickConnect( 4179): PeriphStartReceiver.onReceive - no need to start
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3648): took 0.783333ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9190820 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91af230 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524,
E/Zygote  ( 4200): MountEmulatedStorage()
E/Zygote  ( 4200): v2
,I/libpersona( 4200): KNOX_SDCARD checking this for 10131
I/libpersona( 4200): KNOX_SDCARD not a persona
,I/SELinux ( 4200): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1016): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4200 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 3325:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,I/SELinux ( 4200): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4200): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131099648
,I/AMMetaDataParserService( 3648): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
I/art     ( 1812): Explicit concurrent mark sweep GC freed 26960(1996KB) AllocSpace objects, 32(512KB) LOS objects, 40% free, 12MB/20MB, paused 1.332ms total 515.442ms
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3648): took 0.717032ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb90ec198 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9198300 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4200): TimaSignature is unavailable
,D/ActivityThread( 4200): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3648): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/GCoreUlr( 1812): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/ResourcesManager( 4200): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4200): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4200): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4200): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.643750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91ab8e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9173be8 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3325/cgroup.procs: No such file or directory
,W/com.google.a.a.b.d.a( 4013): Application name is not set. Call Builder#setApplicationName.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/AMMetaDataParserService( 3648): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.635886ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a8ff0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb91915c0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SBrowserFeatureFlag( 4200): initialized in static block : loadCscFeatureValue() succeed! 
,I/AMMetaDataParserService( 3648): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.679167ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb916ea30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9191750 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ManifestProvider( 4200): onCreate()
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.627396ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb919d8c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91a3d98 counterpartCT=4 counterpartW=96 counterparth=96
,E/NetworkSettingsReceiver( 4200): onReceive: android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.803907ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9190820 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9190788 counterpartCT=4 counterpartW=96 counterparth=96
,E/SBrowserFeatureFlag( 4200): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@3f9aedbc
,D/SBrowserFeatureFlag( 4200): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4200): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/AMMetaDataParserService( 3648): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4220): MountEmulatedStorage(),
I/libpersona( 4220): KNOX_SDCARD checking this for 10135
E/Zygote  ( 4220): v2
I/libpersona( 4220): KNOX_SDCARD not a persona
I/SELinux ( 4220): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4220): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4220): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant,
I/AMMetaDataParserService( 3648): Resource data:2131099648
,I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4220 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3308:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,I/AMMetaDataParserService( 3648): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 4220): TimaSignature is unavailable
D/ActivityThread( 4220): Added TimaKeyStore provider
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.878386ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb90ec198 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9173be8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ResourcesManager( 4220): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4220): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4220): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/GCoreUlr( 1812): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.651146ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91ab8e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb91ac1f8 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1016): failed to open /acct/uid_10014/pid_3308/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3648): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/GCoreUlr( 1812): Unbound from all location providers
I/GCoreUlr( 1812): Place inference reporting - stopped
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.830469ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb91a8ff0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9163500 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/CalendarProvider2( 4089): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
I/GCoreUlr( 1812): DispatchingService.onDestroy()
I/GCoreUlr( 1812): Stopping handler for UlrDispSvcFast
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.638437ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb916ea30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb91a3d98 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Killing 3342:com.wssnps/1000 (adj 15): empty #31
,I/GCoreUlr( 1812): Unbound from all location providers
,I/GCoreUlr( 1812): Place inference reporting - stopped
,I/AMMetaDataParserService( 3648): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.625677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb919d8c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91a94e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4241 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,E/Zygote  ( 4241): MountEmulatedStorage()
I/libpersona( 4241): KNOX_SDCARD checking this for 10139
E/Zygote  ( 4241): v2
I/libpersona( 4241): KNOX_SDCARD not a persona
E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/SELinux ( 4241): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/GFX raster( 3648): took 0.748230ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb9190820 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb91720c8 counterpartCT=4 counterpartW=96 counterparth=96
I/SELinux ( 4241): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/AMMetaDataParserService( 3648): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3342/cgroup.procs: No such file or directory
E/SELinux ( 4241): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4241): TimaSignature is unavailable
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
W/ContextImpl( 3648): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataPa,rserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android,.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
D/ActivityThread( 4241): Added TimaKeyStore provider
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131165197
W/ResourcesManager( 4241): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4241): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4241): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4241): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4241): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3648): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,I/AMMetaDataParserService( 3648): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3648): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,E/Zygote  ( 4257): MountEmulatedStorage(),
E/Zygote  ( 4257): v2
I/libpersona( 4257): KNOX_SDCARD checking this for 10145,
I/libpersona( 4257): KNOX_SDCARD not a persona
,I/SELinux ( 4257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4257 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/SMD     (  288): DCD OFF
,I/SELinux ( 4257): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4257): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 33537(1903KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 29MB/44MB, paused 3.049ms total 155.959ms
,I/AMMetaDataParserService( 3648): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/TimaKeyStoreProvider( 4257): TimaSignature is unavailable
,D/ActivityThread( 4257): Added TimaKeyStore provider
,W/ResourcesManager( 4257): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4257): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4257): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4257): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4257): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Killing 3365:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 3095:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/libprocessgroup( 1016): failed to open /acct/uid_10094/pid_3365/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_3095/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3648): Resource data:2131165197
,I/AMMetaDataParserService( 3648): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,I/AMMetaDataParserService( 3648): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3648): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3648): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.cooliris.media.Gallery
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131165197
,I/AMMetaDataParserService( 3648): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,I/AMMetaDataParserService( 3648): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3648): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3648): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/dex2oat ( 4029): dex2oat took 3.179s (threads: 4)
I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/DexOptUtils( 2039): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.dex
D/DexOptUtils( 2039): Set odex to world readable.
,D/DexOptUtils( 2039): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.odex
,D/FileApkUtils( 2039): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
W/ContextImpl( 3648): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartM,msSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,D/GmsModuleFndr( 2039): Beginning GMS chimera module scan
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131099648
,W/ResourcesManager( 3648): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 3648): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3648): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 3648): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3648): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,D/GmsModuleFndr( 2039): Module pkg com.google.android.apps.kids.familylink not installed, skipping
,D/ChimeraCfgMgr( 2039): Beginning module configuration check
,D/ChimeraCfgMgr( 2039): Module APKs unchanged, check complete
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3648): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,I/ActivityManager( 1016): Killing 3452:com.sec.factory.camera/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3648): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,W/ContextImpl( 3648): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4283): MountEmulatedStorage(),
,I/libpersona( 4283): KNOX_SDCARD checking this for 10072
E/Zygote  ( 4283): v2
I/libpersona( 4283): KNOX_SDCARD not a persona
,I/SELinux ( 4283): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4283 uid=10072 gids={50072, 9997} abi=armeabi-v7a,
I/SELinux ( 4283): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4283): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3452/cgroup.procs: No such file or directory
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/art     (  304): Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 24.204ms
,D/TimaKeyStoreProvider( 4283): TimaSignature is unavailable
,D/ActivityThread( 4283): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131165220
,W/ResourcesManager( 3648): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3648): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3648): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.704271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb98ac2c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb98abff0 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 730us total 17.146ms
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/ActivityManager( 1016): startService callerProcessName:com.android.email, calleePkgName: com.android.email
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3648): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 608us total 16.966ms
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.707604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb98ac110 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb98bf410 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,D/BadgeProvider( 4283): onCreate
,D/BadgeProvider( 4283): DatabaseHelper
,D/BadgeProvider( 4283): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity,
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.TetherSettings,
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
,I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ContextImpl( 3648): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
,I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
,I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/libpersona( 4304): KNOX_SDCARD checking this for 10146
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/libpersona( 4304): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
,I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.RunningServices
,I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
,I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/ActivityManager( 1016): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4304 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/ActivityManager( 1016): Killing 3500:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/ActivityManager( 1016): Killing 3481:com.android.managedprovisioning/u0a22 (adj 15): empty #32
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRA,GMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.and,roid.settings.ChooseLockSignature
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/ActivityManager( 1016): Killing 3544:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
W/ResourcesManager( 4304): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3648): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
E/Zygote  ( 4304): MountEmulatedStorage()
W/ActivityManager( 1016): getTasks: caller 10145 does not hold GET_TASKS; limiting output
E/Zygote  ( 4304): v2
I/SELinux ( 4304): Function: selinux_compare_spd_ram, S,PD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4304): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4304): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4304): TimaSignature is unavailable
D/BadgeProvider( 4283): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4283): sendNotify, [notify] : null
D/BadgeProvider( 4283): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4283): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4283): update, [UpdateCount] : 1
D/ActivityThread( 4304): Added TimaKeyStore provider
D/Launcher.Model( 1497): reloadBadges entered.
I/Process ( 4257): Sending signal. PID: 4257 SIG: 9
W/libprocessgroup( 1016): failed to open /acct/uid_10022/pid_3481/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10100/pid_3500/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3544/cgroup.procs: No such file or directory
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/ActivityManager( 1016): startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4322 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Process com.android.email (pid 4257)(adj 9) has died(43,1158),
E/Zygote  ( 4322): MountEmulatedStorage()
I/libpersona( 4322): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4322): v2
I/libpersona( 4322): KNOX_SDCARD not a persona
I/SELinux ( 4322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.exchange, calleePkgName: com.android.email
,I/SELinux ( 4322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4322): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4331): MountEmulatedStorage(),
E/Zygote  ( 4331): v2
I/libpersona( 4331): KNOX_SDCARD checking this for 10145
I/libpersona( 4331): KNOX_SDCARD not a persona
I/SELinux ( 4331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4331 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 4331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4331): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4322): TimaSignature is unavailable
,D/TimaKeyStoreProvider( 4331): TimaSignature is unavailable
D/ActivityThread( 4322): Added TimaKeyStore provider
D/ActivityThread( 4331): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 3559:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,W/ResourcesManager( 4331): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4331): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4331): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 4331): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4331): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4353): MountEmulatedStorage()
,E/Zygote  ( 4353): v2
I/libpersona( 4353): KNOX_SDCARD checking this for 1000
I/libpersona( 4353): KNOX_SDCARD not a persona,
,I/SELinux ( 4353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4353 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 4353): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 3585:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4353): TimaSignature is unavailable
,D/ActivityThread( 4353): Added TimaKeyStore provider
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 4353): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4353): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4353): StateMachine : Current State = 1
,D/SecurityLogAgent( 4353): BootReceiver : completed task. Failed to return wakelock . 
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1016): Killing 3199:com.sec.pcw.device/1000 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3559/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_3585/cgroup.procs: No such file or directory
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1341): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1341): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1341): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1341): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1341): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1341): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1341): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1341): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,W/art     ( 1341): Suspending all threads took: 7.226ms
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/daemonapp( 1341): [MSC_Daemon]>>> WDSM:165 [0:0] app on 
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/BadgeProvider( 4283): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Launcher.Model( 1497): reloadBadges entered.
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
,D/BadgeProvider( 4283): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4283): sendNotify, [notify] : null
D/BadgeProvider( 4283): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4283): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4283): update, [UpdateCount] : 1
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/ActivityManager( 1016): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,I/Process ( 4304): Sending signal. PID: 4304 SIG: 9
D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/AdaptiveEventManager( 1177): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
D/daemonapp( 1341): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover,
D/AdaptiveEventManager( 1177): currentCityId is null
D/AdaptiveEventManager( 1177): NetWork disabled : Don't refresh weather info : 205
D/AdaptiveEventManager( 1177): WeatherInfo [icon, temp, scale] = [0, 0.0, 1],
D/AdaptiveEventManager( 1177): Weather Visibility: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1177): Widget Count: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1177): mWeatherInfo is not reliable
E/daemonapp( 1341): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
D/daemonapp( 1341): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
D/daemonapp( 1341): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,E/daemonapp( 1341): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/daemonapp( 1341): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/daemonapp( 1341): [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1457690686549
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1457712286542
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
D/daemonapp( 1341): [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1457712240000
,D/daemonapp( 1341): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1457712240000
,I/ActivityManager( 1016): Process com.android.exchange (pid 4304)(adj 13) has died(43,1159)
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1457712240000
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
,I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1812): callingUid 10012, callindPid: 1812
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1812): [235] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/PowerManagerService( 1016): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1016): lcd : 45 +
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2039): Restart initialization of location
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3199/cgroup.procs: No such file or directory
,D/lights  ( 1016): lcd : 45 -
D/lights  ( 1016): lcd : 19 +
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1812): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/lights  ( 1016): lcd : 19 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/GCoreFlp( 1812): No location to return for getLastLocation()
,W/FusedLocationProvider( 1812): location=null
,D/ActivityManager( 1016): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4384 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,E/Zygote  ( 4384): MountEmulatedStorage()
E/Zygote  ( 4384): v2
I/libpersona( 4384): KNOX_SDCARD checking this for 1000
I/libpersona( 4384): KNOX_SDCARD not a persona
,I/SELinux ( 4384): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/SELinux ( 4384): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4384): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4384): TimaSignature is unavailable
,D/ActivityThread( 4384): Added TimaKeyStore provider
,E/MTPRx   ( 4384): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1016): mCursor = null
,V/MTPRx   ( 4384): sealedState: false
V/MTPRx   ( 4384): sealedUsbMassStorageState: false
,E/MTPRx   ( 4384): check value of boot_completed is1
E/MTPRx   ( 4384): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4384): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4384): Status for mount/Unmount :removed
E/MTPRx   ( 4384): SDcard is not available
,W/MTPRx   ( 4384): value of connected istrue
W/MTPRx   ( 4384): value of configured istrue
W/MTPRx   ( 4384): value of mtpEnabled istrue
W/MTPRx   ( 4384): value of ptpEnabled isfalse
,E/MTPRx   ( 4384): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4384): mFirstTime: false
,D/        ( 4384): MTP: reading debug level property
,E/MTPJNIInterface( 4384): Getting CryptionKey from JAVA
,E/MTPRx   ( 4384): currentUserId is 0
,I/ValidateNoPeople( 1016): mEvictionCount: 0
,E/MTPRx   ( 4384): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4384): cannot open file : /sys/class/android_usb/android0/bcdUSB
,E/MTPRx   ( 4384): is_Privatemode is NOT 1
,D/SettingsProvider( 1016): name = boot_time_connected
,E/MTPRx   ( 4384): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4384): noti = 17
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,D/SecContentProvider( 1016): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4384): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,E/MTPRx   ( 4384): else part ... so first time!!!
,E/MTPPlaObsrvr( 4384): inside setContext()
E/MTPPlaObsrvr( 4384):  inside createplafiles
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 4384): playlist count is0
,E/MTPPlaObsrvr( 4384):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4384):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4384): Inside registerContentObserver
,E/MtpAdbObserver( 4384): inside setContext()
E/MtpAdbObserver( 4384): Inside registerContentObserver
W/Settings( 4384): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,E/MtpService( 4384): onCreate.
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/MtpService( 1238): updating state; isCurrentUser=true, mMtpLocked=false
,V/MtpMediaDBManager( 4384): inside deleteAllDB
,E/MtpService( 4384): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4384): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,E/MtpService( 4384): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MtpService( 4384): onStartCommand.
W/MTPRx   ( 4384): calling native method
E/MTPJNIInterface( 4384): < MTP > Registering BroadCast receiver :::::
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MtpService( 4384): handleMessage. msg= { when=-6ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,V/UserPresentBroadcastReceiver( 1812): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,V/MtpMediaDBManager( 4384): inside Thread updateDB
,E/MTPJNIInterface( 4384): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 4384): noti = 10
E/MtpService( 4384): onStartCommand.
W/MTPRx   ( 4384): calling native method
,E/MTPRx   ( 4384): Checking the driver time out
E/MTPJNIInterface( 4384): noti = 2
D/        ( 4384): deleting sockets before message queue initialization
,D/        ( 4384): event handler thread is created, so set the flag
,E/MTPRx   ( 4384): called native method
E/MTPJNIInterface( 4384): setting Media scanner status0
E/MTPJNIInterface( 4384): After setting Media scanner status0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/        ( 4384): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4384): Getting media scanner status0
,W/MTPRx   ( 4384): notification from stack 1
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MTPJNIInterface( 4384): DeviceName is A5-1
,E/MtpService( 4384): handleMessage. msg= { when=-18ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MtpMediaDBManager( 4384): count : 27
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/MtpMediaDBManager( 4384): sending db update complete noti to stack
E/MTPJNIInterface( 4384): noti = 29
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1341): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1341): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1341): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1341): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1341): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1341): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1341): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1341): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1341): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1457712240000
D/daemonapp( 1341): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1457690687019
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/MTPJNIInterface( 4384): Status for mount/Unmount :removed
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
E/MTPJNIInterface( 4384): SDcard is not available
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1341): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1341): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1341): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 4384): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,E/        ( 4384): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/Zygote  ( 4406): MountEmulatedStorage()
I/libpersona( 4406): KNOX_SDCARD checking this for 10111
E/Zygote  ( 4406): v2
I/libpersona( 4406): KNOX_SDCARD not a persona
E/MTPJNIInterface( 4384): Status for mount/Unmount :removed
E/MTPJNIInterface( 4384): SDcard is not available
I/ActivityManager( 1016): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4406 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4406): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/SQLiteLog( 4384): (21) API call with NULL database connection pointer
E/SQLiteLog( 4384): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4384): (21) API call with NULL database connection pointer
E/SQLiteLog( 4384): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4384): (21) API call with NULL database connection pointer
E/SQLiteLog( 4384): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4384): (21) API call with NULL database connection pointer
E/SQLiteLog( 4384): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 4384): notification from stack 2
,D/        ( 4384): [mtp_init_device] Library open with 32 bits.
,D/        ( 4384): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4384): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 4384): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4384):  [sua_support_present:1287] returning false 
D/        ( 4384): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
I/SELinux ( 4406): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4406): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,

```
