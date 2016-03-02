#### Test 613623660556c10_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
D/MyFiles ( 6117): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
E/installd(  295): system dir 0 : /system/app/
E/installd(  295): system dir 1 : /system/priv-app/
E/installd(  295): system dir 2 : /vendor/app/
E/installd(  295): system dir 3 : /oem/app/
--------- beginning of system
I/ActivityManager(  892): Killing 5264:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##41
I/TactileAssist(  892): enable value -1
I/TactileAssist(  892): internal enable value -1
I/TactileAssist(  892): intensity value -1
I/TactileAssist(  892): saveAppList value true
I/TactileAssist(  892): List of disabled apps :
I/TactileAssist(  892): de.zalando.mobile
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
D/PackageManager(  892): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 6138): MountEmulatedStorage()
E/Zygote  ( 6138): v2
I/libpersona( 6138): KNOX_SDCARD checking this for 10058
I/libpersona( 6138): KNOX_SDCARD not a persona
I/ActivityManager(  892): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6138 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 6138): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6138): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6138): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 4261): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/libprocessgroup(  892): failed to open /acct/uid_10002/pid_5264/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 6138): TimaSignature is unavailable
D/ActivityThread( 6138): Added TimaKeyStore provider
D/ResourcesManager( 6138): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/ResourcesManager( 6138): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 6138): onReceive() it will make start service
I/UpdateIcingCorporaServi( 1578): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 6138): onHandleIntent()
D/Compatibility( 6138): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10200, android.intent.extra.user_handle=0}]
D/Compatibility( 6138): found: 2
W/ContextImpl( 5460): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
D/Compatibility( 6138): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6138): skipping ResolveInfo{9227c5d com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6138): considering ResolveInfo{328179d2 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6138): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6138): enabling receiver ResolveInfo{3eab0aa3 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6138): enabling receiver ResolveInfo{292361a0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6138): enabling receiver ResolveInfo{2d8f8159 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6138): enabling receiver ResolveInfo{359611e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6138): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 1578): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
E/Zygote  ( 6163): MountEmulatedStorage()
E/Zygote  ( 6163): v2
I/libpersona( 6163): KNOX_SDCARD checking this for 10098
I/libpersona( 6163): KNOX_SDCARD not a persona
I/ActivityManager(  892): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6163 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  892): Killing 5392:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
I/UpdateIcingCorporaServi( 1578): UpdateCorporaTask done [took 71 ms] updated apps [took 70 ms] 
I/SELinux ( 6163): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6163): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6163): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6163): TimaSignature is unavailable
D/ActivityThread( 6163): Added TimaKeyStore provider
D/ResourcesManager( 6163): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/libprocessgroup(  892): failed to open /acct/uid_10094/pid_5392/cgroup.procs: No such file or directory
D/DocsApplication( 6163): Installing DEX configuration.
D/DexInstaller( 6163): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 6163): Provided clientMode=RELEASE, packageInfo=PackageInfo{14711634 com.google.android.apps.docs}
D/TAG     ( 6163): onCreate()
D/CrossAppStateProvider( 6163): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
I/PowerManagerService(  892): [PWL] Off : 15s ago
I/PowerManagerService(  892): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  892): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  892): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1981, ws=null) (elapsedTime=29991)
V/AlarmManager(  892): waitForAlarm result :4
,D/BatteryService(  892): level:100, scale:100, status:2, health:2, present:true, voltage: 4345, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  892): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  892): stay LED for charging
D/BatteryService(  892): Sending ACTION_BATTERY_CHANGED.
D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  892): Plugged
I/MotionRecognitionService(  892): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
W/NetworkUtils( 1578): OkHttp exception
W/EventLoggerService( 1578): Unable to send logs Error code: 262146
I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1685): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/WindowManager(  892): showStatusBarByNotification() mOpenByNotification=false
W/Search.LoginHelper( 1578): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
D/ResourcesManager( 1168): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
W/ResourcesManager( 1168): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1168): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_warning.png
V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_warning.png
D/KnoxNotification( 1168): ----- inflateViews : modified publicViewLocal -----
D/KnoxNotification( 1168): ----- inflateViews : modified KnoxViewLocal -----
D/PersonaManager( 1168): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1168): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@37bec079
D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
D/AndroidRuntime( 6195): 
D/AndroidRuntime( 6195): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6195): CheckJNI is OFF
D/AndroidRuntime( 6195): setted country_code = Germany
D/AndroidRuntime( 6195): setted countryiso_code = DE
D/AndroidRuntime( 6195): setted sales_code = DBT
D/AndroidRuntime( 6195): readGMSProperty: start
D/AndroidRuntime( 6195): readGMSProperty: already setted!!
D/AndroidRuntime( 6195): readGMSProperty: end
D/AndroidRuntime( 6195): addProductProperty: start
E/AffinityControl( 6195): AffinityControl: registerfunction enter
D/AndroidRuntime( 6195): Calling main entry com.android.commands.am.Am
V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/PersonaManagerService(  892): inState():  stateMachine is null !!
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  892): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  892): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  892): mDVFSHelper.acquire()
D/FocusedStackFrame(  892): Set to : 0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6210): MountEmulatedStorage()
E/Zygote  ( 6210): v2
I/libpersona( 6210): KNOX_SDCARD checking this for 10200
I/libpersona( 6210): KNOX_SDCARD not a persona
I/ActivityManager(  892): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6210 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6210): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
I/SELinux ( 6210): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1168): value : false
E/SELinux ( 6210): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 6195): Shutting down VM
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6210): TimaSignature is unavailable
D/ActivityThread( 6210): Added TimaKeyStore provider
W/GAV2    ( 6163): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/Zygote  ( 6227): MountEmulatedStorage()
I/libpersona( 6227): KNOX_SDCARD checking this for 10099
E/Zygote  ( 6227): v2
I/libpersona( 6227): KNOX_SDCARD not a persona
I/ActivityManager(  892): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=6227 uid=10099 gids={50099, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
V/WindowOrientationListener(  892): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  892): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  892): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  892): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  892): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  892): Display changed displayId=0
I/SELinux ( 6227): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6227): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6227): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/TimaKeyStoreProvider( 6227): TimaSignature is unavailable
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ActivityThread( 6227): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/SurfaceWidgetView( 1504): destroyHardwareResources():414938670
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
I/SQLiteSecureOpenHelper( 3302): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3302): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1168): value : false
V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (6/8)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/8)
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager( 6210): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2092): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/ResourcesManager( 6227): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
D/Launcher( 1504): onTrimMemory. Level: 20
D/Finsky  ( 5804): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5804): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5804): [1] 5.onFinished: Scheduling replication attempt 1.
W/ResourcesManager( 6227): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/WebViewFactory( 6210): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 6210): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,E/[CarMode]( 6227): [DLApplication]-onCreate: Applicatino Started!
,I/LibraryLoader( 6210): Loading: webviewchromium
,I/LibraryLoader( 6210): Time to load native libraries: 2 ms (timestamps 3949-3951)
,I/LibraryLoader( 6210): Expected native library version number "",actual native library version number ""
,D/SampleAppCoreManager( 6227): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 6227): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,V/WebViewChromiumFactoryProvider( 6210): Binding Chromium to main looper Looper (main, tid 1) {359611e}
,I/LibraryLoader( 6210): Expected native library version number "",actual native library version number ""
I/chromium( 6210): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6210): Initializing chromium process, renderers=0
,W/art     ( 6210): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6210): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6210): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6210): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 6210): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/BluetoothAdapter( 6210): 601468415: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6210): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6210): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6210): Build Date: 03/03/15 Tue
I/Adreno-EGL( 6210): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 6210): Remote Branch: 
I/Adreno-EGL( 6210): Local Patches: 
I/Adreno-EGL( 6210): Reconstruct Branch: 
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6264): MountEmulatedStorage()
,E/Zygote  ( 6264): v2
I/libpersona( 6264): KNOX_SDCARD checking this for 10033
I/libpersona( 6264): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=6264 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 6264): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6264): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6264): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6264): TimaSignature is unavailable
,D/ActivityThread( 6264): Added TimaKeyStore provider
,W/GAV2    ( 6163): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager(  892): Killing 5408:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): bgCount ##41
,D/ResourcesManager( 6264): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 6264): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/chromium( 6210): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6210): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6210): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6210): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6210): CordovaWebView is running on device made by: samsung
W/libprocessgroup(  892): failed to open /acct/uid_10103/pid_5408/cgroup.procs: No such file or directory
W/art     ( 6210): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6210): Attempt to remove local handle scope entry from IRT, ignoring
,I/System.out( 6264): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 6264): Inside WakeupProvider
,E/DatabaseUtils( 6264): Writing exception to parcel
E/DatabaseUtils( 6264): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 6264): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 6264): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 6264): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 6264): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 6264): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 6264): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 6264): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 6264): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 6264): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 6264): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 6227): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,I/VlingoApplication( 6264): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=DBT
,W/System.err( 6227): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 6227): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 6227): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 6227): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 6227): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 6227): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 6227): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 6227): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 6227): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 6227): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 6227): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 6227): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 6227): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 6227): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 6227): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 6227): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 6227): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 6227): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 6227): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 6227): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 6227): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 6227): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 6227): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6227): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 6227): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6227): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6227): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 6227): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6227): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6227): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6227): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/DatabaseUtils( 6264): Writing exception to parcel
E/DatabaseUtils( 6264): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 6264): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 6264): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 6264): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 6264): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 6264): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 6264): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 6264): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 6264): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 6264): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 6264): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 6227): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 6227): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 6227): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 6227): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 6227): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 6227): 	at android.content.ContentResolver.query(ContentResolver.java:484)
D/Activity( 6210): performCreate Call secproduct feature valuefalse
D/Activity( 6210): performCreate Call debug elastic valuetrue
W/System.err( 6227): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 6227): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 6227): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 6227): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 6227): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 6227): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 6227): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 6227): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 6227): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 6227): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 6227): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 6227): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 6227): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 6227): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 6227): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6227): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 6227): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6227): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6227): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 6227): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6227): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6227): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6227): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 6227): [DLApplication]-Init Called!:false
E/[CarMode]( 6227): [DLApplication]-Init Started!:true
I/[CarModeFW]( 6227): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 6227): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 6227): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 6227): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 6227): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 6227): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 6227): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 6227): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 6227): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 6227): ### android.os.Looper::loop(145)
I/[CarModeFW]( 6227): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 6227): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 6227): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 6227): ### com.android.internal.os.ZygoteInit::main(1194)
D/OpenGLRenderer( 6210): Render dirty regions requested: true
D/BluetoothAdapter( 6264): 95309262: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 6264): 95309262: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 6264): 95309262: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 6264): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
D/ActivityManager(  892): post active user change for 0
D/KnoxTimeoutHandler(  892): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  892): handleActiveUserChange for user 0
,I/SurfaceFlinger(  249): id=13 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/StatusBarManagerService(  892): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/StatusBarManagerService(  892): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/MessageDataHandler( 6227): initialize
D/[CarModeFW]( 6227): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 6227): CDH-initiazlieCaches : after sync
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/[CarModeFW]( 6227): CDH-buildContactCacheWireFrame : cur len =0
,I/OpenGLRenderer( 6210): Initialized EGL, version 1.4
D/[CarModeFW]( 6227): CDH-ContactDataHandler initiazlieCaches time : 19
D/[CarModeFW]( 6227): CDH-initiazlieCaches : end sync
,I/OpenGLRenderer( 6210): HWUI protection enabled for context ,  &this =0xa1753060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6210): Enabling debug mode 0
,D/BluetoothAdapter( 6227): 3915412: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 6227): 3915412: getState() :  mService = null. Returning STATE_OFF
D/[CarModeFW]( 6227): DrivingManager-initialize...
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SensorService(  892): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
,I/SensorService(  892): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  892): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,D/VlingoApplication( 6264): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 6264): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/InputMethodManagerService(  892): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/ActivityManager(  892): mDVFSHelper.release()
I/Timeline(  892): Timeline: Activity_windows_visible id: ActivityRecord{764612c u0 com.test.thalitest/.MainActivity t27} time:64330
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/IInputConnectionWrapper( 6210): showStatusIcon on inactive InputConnection
,I/Timeline( 6210): Timeline: Activity_idle id: android.os.BinderProxy@29fa7285 time:64334
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/MediaPlayer( 6227): Need to enable context aware info
,V/MediaPlayer-JNI( 6227): native_setup
V/MediaPlayer( 6227): constructor
,V/MediaPlayer( 6227): setListener
E/MediaPlayer-JNI( 6227): QCMediaPlayer mediaplayer NOT present
,D/[CarModeFW]( 6227): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 6227): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 6227): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW]( 6227): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1456908860448
,D/[CarMode]( 6227): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 6227): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1456908860448
,I/[CarMode]( 6227): [LogNotNull]-Package name is: com.google.android.apps.maps
,D/[CarModeFW]( 6227): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1456908860452
D/[CarModeFW]( 6227): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1456908860452
,D/[CarModeFW]( 6227): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1456908860454
,D/[CarModeFW]( 6227): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1456908860454
,E/[CarMode]( 6227): [DLApplication]-Init End!:true
,D/TP/SmsProvider( 1487): query,matched:2, calling pid = 6227
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/TP/SmsProvider( 1487): match 2:Elapsed time : 3.002 ms
,E/Zygote  ( 6318): MountEmulatedStorage()
E/Zygote  ( 6318): v2
I/libpersona( 6318): KNOX_SDCARD checking this for 10003
I/libpersona( 6318): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=6318 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,D/JsMessageQueue( 6210): Set native->JS mode to OnlineEventsBridgeMode
,I/SELinux ( 6318): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/[CarModeFW]( 6227): CDH-buildContactCacheWireFrame : cur len =0
D/TP/SmsProvider( 1487): query,matched:2, calling pid = 6227
I/SELinux ( 6318): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/[CarModeFW]( 6227): RecommendHandler-selection = type = '3'
,D/TP/SmsProvider( 1487): match 2:Elapsed time : 1.636 ms
E/SELinux ( 6318): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/MessageDataHandler( 6227):  getInboxList smsCursor : 54
,D/[CarModeFW]( 6227): CDH-buildContactCacheWireFrame : cur len =0
,D/TP/MmsProvider( 1487): Query uri=content://mms, match=0, calling pid = 6227
,D/TP/MmsProvider( 1487): Query uri=content://mms/inbox, match=2, calling pid = 6227
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6318): TimaSignature is unavailable
,D/ActivityThread( 6318): Added TimaKeyStore provider
,E/Zygote  ( 6334): MountEmulatedStorage()
I/libpersona( 6334): KNOX_SDCARD checking this for 10020
E/Zygote  ( 6334): v2
I/libpersona( 6334): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=6334 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,I/SELinux ( 6334): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6334): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6334): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/MessageDataHandler( 6227):  getInboxList mmsCursor : 78
D/[CarModeFW]( 6227): CDH-buildContactCacheWireFrame : cur len =0
D/[CarMode]( 6227): [DLApplication]-GooglePlayServices SUCCESS.
I/MessageDataHandler( 6227): getUnreadMessageCount :0
D/[CarModeFW]( 6227): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 135
D/[CarModeFW]( 6227): RecommendHandler-selection = type = '3'
D/MessageDataHandler( 6227):  getInboxList mms,sms cursor join : 10
,D/TP/MmsSmsProvider( 1487): query,matched:0, calling pid = 6227
V/TP/MmsSmsProvider( 1487): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1487): match 0:Elapsed time : 1.278 ms
,D/ResourcesManager( 6318): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,E/[CarMode]( 6227): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,I/UpdateManagerReceiver( 6227): Intent : android.intent.action.PACKAGE_ADDEDWed Mar 02 09:54:20 GMT+01:00 2016
,D/TimaKeyStoreProvider( 6334): TimaSignature is unavailable
,D/ActivityThread( 6334): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 1487): query,matched:13, calling pid = 6227
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1487): match 13:Elapsed time : 1.520 ms
,E/Zygote  ( 6349): MountEmulatedStorage()
E/Zygote  ( 6349): v2
I/libpersona( 6349): KNOX_SDCARD checking this for 1000
I/libpersona( 6349): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6349 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 8744(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 294us total 14.471ms
,D/UserAnalysis.PlaceProvider( 6318): PlaceProvider onCreate()
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 254us total 9.178ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 9.859ms
,I/SELinux ( 6349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6349): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6349): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  892): Killing 5426:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
,D/jxcore_app_log( 6210): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361282048
,D/MessageDataHandler( 6227):  getInboxList address cursor : 85
,D/TP/MmsSmsProvider( 1487): query,matched:0, calling pid = 6227
V/TP/MmsSmsProvider( 1487): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1487): match 0:Elapsed time : 1.552 ms
,E/SMD     (  287): DCD ON
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6210): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6210):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6210):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6210):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6210):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6210): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@211e52fb added. We now have 1 listener(s)
,D/[CarModeFW]( 6227): PushMessageService-onCreate
,D/MessageDataHandler( 6227):  getInboxList thread cursor : 9
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6210): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6210):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6210):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6210):     - Bluetooth MAC address: B0:C5:59:3F:75:69
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6210):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6210):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6210):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6210):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6210):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6210):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6210): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1af42756 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6210): addListener: New listener added - the number of listeners is now 1
I/ActivityManager(  892): Killing 4973:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): bgCount ##41
,I/ActivityManager(  892): Killing 5445:com.sec.providers.settingsearch/u0a168 (adj 15): bgCount ##42
,I/ActivityManager(  892): Killing 4578:com.sec.android.app.camera/u0a154 (adj 15): bgCount ##43
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6210): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6210): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 6210): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6210): 
,D/MessageDataHandler( 6227):  thread, addr result: 24
I/[CarModeFW]( 6227): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 280
,I/[CarModeFW]( 6227): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 6227): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 283
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6210): setDiscoveryMode: Discovery mode BLE is supported
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6210): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6210): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,D/TimaKeyStoreProvider( 6349): TimaSignature is unavailable
,D/ActivityThread( 6349): Added TimaKeyStore provider
,I/chromium( 6210): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/[CarModeFW]( 6227): PushMessageManager-onServiceConnected
D/[CarModeFW]( 6227): PushMessageService-registerPushMessageServiceListener
,D/ResourcesManager( 6334): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,D/UserAnalysis.SecureDbManager( 6318): Key for secure DB is newly created
,I/art     (  892): Explicit concurrent mark sweep GC freed 31671(1748KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 1.664ms total 114.746ms
,D/UserAnalysis.SecurePlaceDbHelper( 6318): SecurePlaceDbHelper() 
,D/UserAnalysis.PlaceProvider( 6318): Create SecureDbHelper
,D/WifiService(  892): New client listening to asynchronous messages
,D/ResourcesManager( 6349): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/IntelligenceServiceApplication( 6318): onCreate()
,I/SQLiteSecureOpenHelper( 6318): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 6318): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 6318): Open Place.db in secure mode
,D/[CarModeFW]( 6227): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 447
,W/ContextImpl( 6349): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
I/[CarModeFW]( 6227): -[snowdeer] Rec : Missed Call : 398
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 6349): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/SQLiteSecureOpenHelper( 6318): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 6318): ...getDatabaseLocked(b,b,pwd)
,E/Zygote  ( 6371): MountEmulatedStorage()
I/libpersona( 6371): KNOX_SDCARD checking this for 10112
E/Zygote  ( 6371): v2
I/libpersona( 6371): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6371 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 6371): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6371): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6371): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/[CarModeFW]( 6227): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 6227): MyPlaceProvider-=============
,D/[CarModeFW]( 6227): MyPlaceProvider-=============
D/[CarModeFW]( 6227): MyPlaceProvider-=============
D/[CarModeFW]( 6227): MyPlaceProvider-=============
D/[CarModeFW]( 6227): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 6227): MyPlaceProvider-==============
E/FilterInstaller( 6349): There is no requred permission
,I/[CarModeFW]( 6227): -[snowdeer] Rec : Favorite : 71
,D/[CarModeFW]( 6227): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 6227): MyPlaceProvider-==============
D/[CarModeFW]( 6227): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 6227): MyPlaceProvider-==============
D/[CarModeFW]( 6227): MyPlaceProvider-latitude is not valid
,I/ActivityManager(  892): Killing 4536:com.android.calendar/u0a150 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 6371): TimaSignature is unavailable
,D/ActivityThread( 6371): Added TimaKeyStore provider
,D/[CarModeFW]( 6227): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 542
,D/ResourcesManager( 6371): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,D/[CarMode]( 6227): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@ad12a838, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@e515f3ce] LOCATIONS
,I/[CarModeFW]( 6227): -[snowdeer] Rec : CallLog : 26
,I/[CarModeFW]( 6227): -[snowdeer] Rec : Schedule : 17
,I/[CarModeFW]( 6227): -[snowdeer] Rec : During DL app : 1
,D/PackageIntentReceiver( 6371): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6371): Not GearManger package! 
,I/[CarModeFW]( 6227): -[snowdeer] Rec : Location Sharing : 3
I/[CarModeFW]( 6227): -[snowdeer] Rec : POI : 0
,I/[CarModeFW]( 6227): -[snowdeer] Rec : getContactListFromHashMap - core : 0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
I/[CarModeFW]( 6227): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
,I/[CarModeFW]( 6227): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 6227): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 6227): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 576
,I/[CarModeFW]( 6227): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 6227): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 6227): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
,D/[CarModeFW]( 6227): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 573
,E/Zygote  ( 6386): MountEmulatedStorage()
E/Zygote  ( 6386): v2
I/libpersona( 6386): KNOX_SDCARD checking this for 10118
I/libpersona( 6386): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=6386 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5521:com.sec.android.app.sns3/u0a36 (adj 15): bgCount ##41
,I/SELinux ( 6386): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6386): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6386): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6386): TimaSignature is unavailable
,D/ActivityThread( 6386): Added TimaKeyStore provider
,W/libprocessgroup(  892): failed to open /acct/uid_10113/pid_5426/cgroup.procs: No such file or directory
,W/libprocessgroup(  892): failed to open /acct/uid_10149/pid_4973/cgroup.procs: No such file or directory
,W/libprocessgroup(  892): failed to open /acct/uid_10154/pid_4578/cgroup.procs: No such file or directory
W/libprocessgroup(  892): failed to open /acct/uid_10168/pid_5445/cgroup.procs: No such file or directory
,D/ResourcesManager( 6386): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 6386): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  892): failed to open /acct/uid_10150/pid_4536/cgroup.procs: No such file or directory
,D/MagazineService Version( 6386): Magazine-Administrator: 11
,D/MagazineService Version( 6386): Magazine-Provider: 14
,D/MagazineService Version( 6386): Magazine-Channel: 14
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6401): MountEmulatedStorage()
E/Zygote  ( 6401): v2
I/libpersona( 6401): KNOX_SDCARD checking this for 10118
I/libpersona( 6401): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.samsung.android.internal.headlines for service com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService: pid=6401 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/HeadlinesChannelApplication( 6386): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 6386): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,I/SELinux ( 6401): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  892): failed to open /acct/uid_10036/pid_5521/cgroup.procs: No such file or directory
,I/SELinux ( 6401): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6401): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
I/MagazineService::MagazineService( 6386): [onHandleIntent] ACTION_PACKAGE_INSTALLED
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6413): MountEmulatedStorage()
E/Zygote  ( 6413): v2
I/libpersona( 6413): KNOX_SDCARD checking this for 1000
I/libpersona( 6413): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6413 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 6386): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/SELinux ( 6413): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6413): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6413): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  892): Killing 5557:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 6401): TimaSignature is unavailable
,D/ActivityThread( 6401): Added TimaKeyStore provider
,D/ResourcesManager( 6401): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 6401): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaKeyStoreProvider( 6413): TimaSignature is unavailable
,D/ActivityThread( 6413): Added TimaKeyStore provider
,D/ResourcesManager( 6413): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/HeadlinesChannelApplication( 6401): [onCreate]
,D/Headlines( 6401): Breath.onCreate
,D/HeadlinesCardManager( 6401): HeadlinesCardManager : constructor
E/HeadlinesCardManager( 6401): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 6401): CardProvider Library : 14
,D/MagazineService::CardProviderContentProvider( 6386): insertProvider: provider already exists.: com.samsung.android.app.headlines
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/MagazineService::CardProviderContentProvider( 6386): insertProvider: provider is updated.: com.samsung.android.app.headlines
,W/libprocessgroup(  892): failed to open /acct/uid_10038/pid_5557/cgroup.procs: No such file or directory
,E/Zygote  ( 6432): MountEmulatedStorage()
I/libpersona( 6432): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6432): v2
I/libpersona( 6432): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6432 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 6401): registerCardProvider: provider already exists.
,D/Headlines( 6401): HeadlinesDataCenter ctor
,D/Headlines( 6401): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 6401): getCountryCode(): countryCode = DE
,D/HeadlinesCardManager( 6401): HeadlinesCardManager : constructor welcome :YES
,I/SELinux ( 6432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6432): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6432): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6432): TimaSignature is unavailable
,D/ActivityThread( 6432): Added TimaKeyStore provider
,I/ActivityManager(  892): Killing 5576:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): bgCount ##41
,D/ResourcesManager( 6432): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,D/AcmsPackageEventListener( 6432): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 6432): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,W/libprocessgroup(  892): failed to open /acct/uid_10038/pid_5576/cgroup.procs: No such file or directory
,D/AcmsService( 6432): Enter Oncreate
,D/AcmsServiceMonitor( 6432): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6432): creating AcmsCore
D/AcmsCore( 6432): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6432): AcmsCore
,D/AcmsCore( 6432): init
,D/AcmsCore( 6432): Looper handler is not null
D/AcmsCore( 6432): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6432): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6432): Incrementing - Counter value: 1
D/AcmsCertificateMngr( 6432): AcmsCertificateMngr
,D/AcmsCore( 6432): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsRevocationMngr( 6432): AcmsRevocationMngr
D/AcmsService( 6432): onStartCommand
,D/AcmsService( 6432): Action: android.intent.action.PACKAGE_ADDED
,D/AcmsServiceMonitor( 6432): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6432): Incrementing - Counter value: 2
D/AcmsService( 6432): Incremented Counter Value : onStartCommand
,D/ActivityThread( 6432): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsService( 6432): Inside handle Intent
D/AcmsService( 6432): App added - package name: com.test.thalitest
D/AcmsCore( 6432): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6432): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6432): Incrementing - Counter value: 3
D/AcmsCore( 6432): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6432): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6432): Decrementing - Counter value: 2
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,I/System.out( 6264): INFO:Resource not found:/Common.properties Using default values
,E/Zygote  ( 6453): MountEmulatedStorage()
E/Zygote  ( 6453): v2
I/libpersona( 6453): KNOX_SDCARD checking this for 10166
I/libpersona( 6453): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=6453 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6453): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6453): TimaSignature is unavailable
,D/ActivityThread( 6453): Added TimaKeyStore provider
,D/ResourcesManager( 6453): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 6453): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 6453): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6468): MountEmulatedStorage()
I/libpersona( 6468): KNOX_SDCARD checking this for 10170
E/Zygote  ( 6468): v2
I/libpersona( 6468): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6468 uid=10170 gids={50170, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5012:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,I/SELinux ( 6468): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6468): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6468): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6468): TimaSignature is unavailable
,D/ActivityThread( 6468): Added TimaKeyStore provider
,D/ResourcesManager( 6468): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 6468): (284) automatic index on shooting_modes(title_id)
,W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_5012/cgroup.procs: No such file or directory
,I/ActivityManager(  892): Killing 4596:com.android.providers.calendar/u0a46 (adj 15): bgCount ##41
,I/art     ( 1981): Explicit concurrent mark sweep GC freed 19191(1323KB) AllocSpace objects, 11(176KB) LOS objects, 24% free, 18MB/24MB, paused 502us total 50.097ms
,D/PackageBroadcastService( 1981): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.games from APK com.google.android.gms
,D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.vision from APK com.google.android.gms
,W/libprocessgroup(  892): failed to open /acct/uid_10046/pid_4596/cgroup.procs: No such file or directory
,D/Vision  ( 1981): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 1981): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1981): No vision deps
,I/ConfigFetchService( 1981): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,I/ConfigFetchService( 1981): launchTask
,E/Zygote  ( 6487): MountEmulatedStorage()
I/libpersona( 6487): KNOX_SDCARD checking this for 10040
E/Zygote  ( 6487): v2
I/libpersona( 6487): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6487 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6487): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6487): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/PeopleContactsSync( 1981): CP2 sync disabled
E/SELinux ( 6487): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6487): TimaSignature is unavailable
,D/ActivityThread( 6487): Added TimaKeyStore provider
,D/ResourcesManager( 1981): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 6487): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,V/ConfigFetchTask( 1981): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WcniZpQ_JrGHGvHfHMp4PZBHHKxjP2AxRF573XnZddoY0zqQH4dIOwHpcvoXWkKWWGj_-LW0pKFV2rGjnDIz9Ckmp4Avx31PTnbK4F49ayXCOM1DsOn4jLf5KX7ccCzvBodjO5fMBkgwNDaDIeBDxPY0vtBSmIUlEp3YPXMG-5_EkXrYnDQBWDASesdJMeJyyEp366Q7a3hSZV-JPiBtufS5cQFKuOTlFTxXmH_-sDZk7W7YA
,W/jxcore-log( 6210): Initializing JXcore engine
W/jxcore-log( 6210): JXcore engine is ready
,I/GoogleURLConnFactory( 1981): Using platform SSLCertificateSocketFactory
,D/SecurityLogAgent:SEDenialService(  892): Got Modify Event and sending Denial Intent foraudit.log
E/auditd  ( 2123): In denial and Property audit_ondenial is set to 1 
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  892): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,W/jxcore-log( 6210): Starting JXcore engine
,I/ActivityManager(  892): Killing 5637:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,D/BootupListener( 1487): ACTION_DRIVELINK
,D/SettingsProvider(  892): name = drivelink_navigation
D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1001
,D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
D/BootupListener( 1487): NAVI : com.google.android.apps.maps
,D/SettingsProvider(  892): name = internet_call_settings_visibility
D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1001
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6503): MountEmulatedStorage()
I/libpersona( 6503): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6503): v2
I/libpersona( 6503): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6503 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6503): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6503): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6503): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6503): TimaSignature is unavailable
,D/ActivityThread( 6503): Added TimaKeyStore provider
,D/ResourcesManager( 6503): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/jxcore-log( 6210): Platform android
W/jxcore-log( 6210): 
W/jxcore-log( 6210): Process ARCH arm
W/jxcore-log( 6210): 
,D/SecurityLogAgent( 6503):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6503):  SeDenialReceiver : File path = null
,W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_5637/cgroup.procs: No such file or directory
,I/ActivityManager(  892): Killing 5701:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,I/System.out( 1981): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1981): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1981): (HTTPLog)-Thread-259-389750083: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,W/ConfigFetchTask( 1981): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 1981): fetch service done; releasing wakelock
,I/ConfigFetchService( 1981): stopping self
,W/libprocessgroup(  892): failed to open /acct/uid_10075/pid_5701/cgroup.procs: No such file or directory
,I/jxcore-log( 6210): JXcore Cordova bridge is ready!
I/jxcore-log( 6210): 
,W/jxcore-log( 6210): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6210): execute: REQUEST_ACCESS_COARSE_LOCATION
,D/AcmsKeyStoreHelper( 6432):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6432): Key Store exist
,I/AcmsKeyStoreHelper( 6432): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6432):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 6432): getKeyStoreForApplication success 
D/AcmsCore( 6432): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6432): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6432): Decrementing - Counter value: 1
D/AcmsCore( 6432): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6432): This is NOT a valid MirrorLink app
D/AcmsCore( 6432): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6432): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6432): Decrementing - Counter value: 0
,D/AcmsServiceMonitor( 6432): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6432): getSvcCounter - Counter value: 0
,D/AcmsService( 6432): Enter onDestroy
I/AcmsService( 6432): cleanUp(): inside service clean up
D/AcmsCore( 6432): AcmsCore: inside DeInit
D/AcmsCore( 6432): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6432): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6432): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6432): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6432): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 6432): getSvcCounter - Counter value: 0
D/AcmsService( 6432): killing acms process
,I/Process ( 6432): Sending signal. PID: 6432 SIG: 9
,I/ActivityManager(  892): Process ACMS.Process (pid 6432)(adj 0) has died(52,580)
,E/SMD     (  287): DCD ON,
,D/SSRM:m  (  892): SIOP:: AP = 430, PST = 429, CUR = 300
,I/GAV2    ( 6163): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6210): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,V/io.jxcore.node.JXcoreExtension( 6210): isBleMultipleAdvertisementSupported: NOT_RESOLVED
,I/jxcore-log( 6210): BLE multiple advertisement supported
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): INFO testUtils Toggling radios to: true
I/jxcore-log( 6210): 
,D/BluetoothAdapter( 6210): enable()
,W/ActivityManager(  892): Permission Denial: getCurrentUser() from pid=6210, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  892): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  892): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6210, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  892): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/BluetoothManagerService(  892): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2141)
W/BluetoothManagerService(  892): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService(  892): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  892): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DevicePolicyManagerService(  892): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  892): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider(  892): name = bluetooth_on
,E/DevicePolicyManagerService(  892): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  892): getAllowBluetoothMode - value retunrs : 2
,I/jxcore-log( 6210): Unit Test app is loaded
I/jxcore-log( 6210): 
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,I/WifiManager( 6210): packageName : com.test.thalitest
,I/chromium( 6210): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,E/Zygote  ( 6543): MountEmulatedStorage()
E/Zygote  ( 6543): v2
,I/libpersona( 6543): KNOX_SDCARD checking this for 1002
I/libpersona( 6543): KNOX_SDCARD not a persona
,D/SecContentProvider(  892): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  892): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  892): mCursor = null
,I/ActivityManager(  892): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6543 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/WifiService(  892): setWifiEnabled: true pid=6210, uid=10200
,E/WifiService(  892): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  892): Permission Denial: getCurrentUser() from pid=6210, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  892): Failed getting userId using ActivityManagerNative
W/WifiService(  892): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6210, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  892): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  892): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  892): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  892): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  892): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  892): name = wifi_on
,I/SELinux ( 6543): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6543): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/WifiStateMachine(  892): setting operational mode to 1
E/WifiHW  (  892): ##################### set firmware type 0 #####################
E/SELinux ( 6543): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/WifiService(  892): disconnect: pid=6210, uid=10200
I/WifiHW  (  281): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,I/WifiHW  (  281): module is semco 3RD
E/WifiHW  (  281): ==========[WIFI] SEMCO 3RD MODULE ===========
I/WifiHW  (  281): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_semco3rd
E/WifiHW  (  281): TEMP_FAILURE_RETRY complete
D/SoftapController(  281): Softap fwReload - Ok
,D/CommandListener(  281): Setting iface cfg
D/CommandListener(  281): Trying to bring down wlan0
,D/CommandListener(  281): Clearing all IP addresses on wlan0
,E/WifiHW  (  892): supplicant_name : p2p_supplicant
,E/WifiStateMachine(  892): setWifiState: enabling
,E/WifiStateMachine(  892): Supplicant start successful
,D/WifiMonitor(  892): startMonitoring(wlan0) with mConnected = false
,D/SmartBondingService(  892): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation(  892): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/TimaKeyStoreProvider( 6543): TimaSignature is unavailable
D/ActivityThread( 6543): Added TimaKeyStore provider
D/SmartBondingService(  892): getNetworkEnabled : wifi : false mobile : true
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1168): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1168): Wifi onReceive(2)
,D/HotspotTile( 1168): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1168): onStateChanged: Wi-Fi
,D/HotspotTile( 1168): onReceive : 2, 0
,D/ResourcesManager( 6543): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
D/WifiCredService( 1294): Action received :android.net.wifi.WIFI_STATE_CHANGED
,V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_wifi_dim.png
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6503): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6503): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6503): StateMachine : Current State = 1
,I/ConfigService( 1685): onDestroy
,D/SecurityLogAgent( 6503): StateMachine : Changed Current State = 1
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6543): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 6543): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/wpa_supplicant( 6558): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 6558): Successfully initialized wpa_supplicant
,E/Zygote  ( 6573): MountEmulatedStorage()
E/Zygote  ( 6573): v2
I/libpersona( 6573): KNOX_SDCARD checking this for 10171
I/libpersona( 6573): KNOX_SDCARD not a persona
,I/SecureStorage( 6558): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6558): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  335): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 6558
I/SecureStorage(  335): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,I/SecureStorage( 6558): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6558): ssSupport state is = 1
,I/wpa_supplicant( 6558): >>>>> GET KEY, IV <<<<<
,I/SecureStorage( 6558): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  335): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 6558
I/SecureStorage(  335): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
I/ActivityManager(  892): Start proc tv.peel.smartremote for broadcast tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver: pid=6573 uid=10171 gids={50171, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 14.343ms
,I/SELinux ( 6573): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6573): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6573): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 295us total 10.727ms
,D/BluetoothAdapterApp( 6543): Load D/L JNI Library
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 9.333ms
,I/BluetoothA2dpSinkServiceJni( 6543): register_com_android_bluetooth_a2dp_sink
,D/BluetoothAdapterApp( 6543): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@14711634 Instance Count = 1
,D/TimaKeyStoreProvider( 6573): TimaSignature is unavailable
,D/ActivityThread( 6573): Added TimaKeyStore provider
,D/BluetoothAdapterApp( 6543): onCreate
,D/BtSettings.ProfileConfig( 6543): Adding GattService
,D/BtSettings.ProfileConfig( 6543): Adding HeadsetService
,D/BtSettings.ProfileConfig( 6543): Adding A2dpService
D/BtSettings.ProfileConfig( 6543): Adding HidService
,D/BtSettings.ProfileConfig( 6543): Adding HealthService
D/BtSettings.ProfileConfig( 6543): Adding PanService
,D/BtSettings.ProfileConfig( 6543): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 6543): Adding SapService
D/BtSettings.ProfileConfig( 6543): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 6543): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 6543): Adding SapClientService
,D/BtSettings.ProfileConfig( 6543): Adding HidDevService
I/BtSettings.ProfileConfig( 6543): *********Initializing Bluetooth Profile Settings*******
,D/ResourcesManager( 6573): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/SettingsProvider(  892): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1002
,D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,W/BackupManagerService(  892): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  892): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1002
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,W/ResourcesManager( 6573): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/BackupManagerService(  892): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  892): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1002
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,W/BackupManagerService(  892): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  892): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1002
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,W/BackupManagerService(  892): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  892): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1002
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  892): ret = -1
,W/BackupManagerService(  892): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  892): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1002
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,W/BackupManagerService(  892): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  892): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1002
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  892): ret = -1
,W/BackupManagerService(  892): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  892): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1002
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,W/BackupManagerService(  892): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  892): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1002
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,W/BackupManagerService(  892): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  892): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1002
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,W/BackupManagerService(  892): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  892): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1002
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,W/BackupManagerService(  892): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  892): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1002
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,W/BackupManagerService(  892): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterApp( 6543): checkSWUpdate
D/BluetoothAdapterApp( 6543): sw version in prop is 1428568983
,D/BluetoothAdapterApp( 6543): sw version in file is 1428568983
D/BluetoothAdapterApp( 6543): sw version is same
,D/BluetoothAdapterState( 6543): make
,I/bluedroid( 6543): init
,I/BluetoothAdapterState( 6543): Entering OffState
,I/bte_conf( 6543): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6543): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6543): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6543): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 6543): btif_fetch_local_ble_random_bdaddr
I/bluedroid( 6543): get_profile_interface socket
I/bluedroid( 6543): get_profile_interface map_client
I/GKI_LINUX( 6543): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterService( 6543): checkAddrForIOP: Loading from conf
,D/BluetoothAdapterProperties( 6543): Address is:B0:C5:59:3F:75:69
E/BluetoothServiceJni( 6543): populateRssiValuesNative
I/bluedroid( 6543): getModelRssiValues
E/BluetoothServiceJni( 6543): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 6543): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 6543): Name is: Thali Test (Galaxy S5)
,D/SettingsProvider(  892): name = bluetooth_name
,D/BluetoothAdapterService( 6543): Inband Ring is supported
,I/bluedroid( 6543): config_hci_snoop_log
,D/BluetoothManagerService(  892): Broadcasting onBluetoothServiceUp() to 12 receivers.
,E/DevicePolicyManagerService(  892): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  892): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider(  892): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState( 6543): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,D/BluetoothAdapterProperties( 6543): Setting state to 11
I/BluetoothAdapterState( 6543): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 6543): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6543): updateAdapterState state is 11
,D/BluetoothAdapterService( 6543): Autoconnection is available 
D/BluetoothAdapterService( 6543): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager( 6543): getInstant: null
,D/BluetoothSecureManager( 6543): calling getMethod for getService
D/BluetoothSecureManager( 6543): calling getService
,D/BluetoothSecureManager( 6543): getService return binder: android.os.BinderProxy@30e15df7
,W/InputMethodManagerService(  892): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  892): [BT Setting State] State =11
,D/BluetoothSecureManagerService(  892): isSecureModeEnabled
D/BluetoothSecureManagerService(  892): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode( 6543): isSecureModeOn:false
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,D/BluetoothTile( 1168): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,W/BluetoothAdapterService( 6543): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/STATUSBAR-QSTileView( 1168): onStateChanged: Bluetooth
,W/BluetoothAdapterService( 6543): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,I/SamsungIME( 1832): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,W/BluetoothAdapterService( 6543): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6543): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_bluetooth_dim.png
W/BluetoothAdapterService( 6543): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 6543): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6543): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6543): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6543): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6543): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6543): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 6543): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine( 6543): make
,I/BluetoothBondStateMachine( 6543): StableState(): Entering Off State
W/BluetoothAdapterService( 6543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 6543): Not skipping com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 6543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 6543): Not skipping com.android.bluetooth.hfp.HeadsetService
,I/BtGatt.JNI( 6543): classInitNative(L890): classInitNative: Success!
,D/BtGatt.DebugUtils( 6543): handleDebugAction() action=null
W/BluetoothAdapterService( 6543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 6543): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BtGatt.GattService( 6543): Received start request. Starting profile...
D/BtGatt.GattService( 6543): start()
,I/bluedroid( 6543): get_profile_interface gatt
D/BluetoothAdapterService( 6543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28ecf7cc
D/BtGatt.AdvertiseManager( 6543): advertise manager created
,W/BluetoothAdapterService( 6543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6543): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 6543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 6543): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 6543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6543): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 6543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6543): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 6543): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6543): Not skipping com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 6543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6543): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6543): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6543): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 6543): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 6543): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 6543): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 6543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28ecf7cc
,D/HeadsetService( 6543): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 6543): classInitNative: succeeds
,D/HeadsetStateMachine( 6543): make
,E/HeadsetStateMachine( 6543): # of Max HF connection is 2
,I/bluedroid( 6543): get_profile_interface handsfree
,I/DualScoManager( 6543): Instantiating Dual Sco Manager
I/DualScoManager( 6543): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 6543): createCMTIContentObservers
,D/SettingsProvider(  892): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1002
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,W/BackupManagerService(  892): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecureStorage(  335): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  335): [INFO]: SPID(0x00000005)PID: 6558, TID: 6558
,D/HeadsetStateMachine( 6543): Enter Disconnected: -2
,D/BluetoothAdapterService( 6543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28ecf7cc
,D/A2dpService( 6543): Received start request. Starting profile...
,D/BluetoothA2dp(  892): Proxy object connected
,I/BluetoothAvrcpServiceJni( 6543): classInitNative: succeeds
V/Avrcp   ( 6543): make
V/Avrcp   ( 6543): Avrcp
I/bluedroid( 6543): get_profile_interface avrcp
E/HeadsetStateMachine( 6543): set to mRemoteBrsf = 0
,D/BluetoothA2dp( 3302): Proxy object connected
,V/Avrcp   ( 6543): start
,I/WebViewFactory( 6573): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 6573): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/HeadsetStateMachine( 6543): map size, before remove : 0
,D/HeadsetStateMachine( 6543): map size, after remove: 0
D/HeadsetStateMachine( 6543): mNextConnectingDevice : null
,E/RemoteController( 6543): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   ( 6543): ++registerMediaPlayers++
,I/Avrcp   ( 6543): No of Audio players :: 2
I/Avrcp   ( 6543): App Package name is com.google.android.music
,I/LibraryLoader( 6573): Loading: webviewchromium
,D/ResourcesManager( 6543): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   ( 6543): App pkg name is Google Play Music
,I/Avrcp   ( 6543): Name::Google Play Music
V/Avrcp   ( 6543): MediaPlayerInfo: mPlayerId=1
I/Avrcp   ( 6543): App Package name is com.sec.android.app.music
,D/ResourcesManager( 6543): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   ( 6543): App pkg name is Music
,I/Avrcp   ( 6543): Name::Music
V/Avrcp   ( 6543): MediaPlayerInfo: mPlayerId=2
I/Avrcp   ( 6543):  set player publishabilty with player id::2 toBePublished ::true
,I/Avrcp   ( 6543): No of Video players :: 1
,I/Avrcp   ( 6543): Video App Package name is com.sec.android.app.videoplayer
D/ResourcesManager( 6543): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/LibraryLoader( 6573): Time to load native libraries: 12 ms (timestamps 1559-1571)
I/LibraryLoader( 6573): Expected native library version number "",actual native library version number ""
,I/Avrcp   ( 6543): Video App pkg name is Video Player
I/Avrcp   ( 6543): Name::Video Player
V/Avrcp   ( 6543): MediaPlayerInfo: mPlayerId=3
I/Avrcp   ( 6543): Add tempPlayer
V/Avrcp   ( 6543): MediaPlayerInfo: mPlayerId=4
I/Avrcp   ( 6543): Total no of players: 4
V/Avrcp   ( 6543): swapping the samsung player with 1st player
I/Avrcp   ( 6543):  Updating now playing list upon AVRCP Start
,V/Avrcp   ( 6543): handleMessage, msg=207
D/BluetoothMediaBrowser( 6543):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 6543): classInitNative: succeeds
D/A2dpStateMachine( 6543): make
,I/bluedroid( 6543): get_profile_interface a2dp
,I/GKI_LINUX( 6543): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 6543): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService( 6543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28ecf7cc
,I/BluetoothHidServiceJni( 6543): classInitNative: succeeds
,D/A2dpStateMachine( 6543): Enter Disconnected: -2
,D/HidService( 6543): Received start request. Starting profile...
,I/bluedroid( 6543): get_profile_interface hidhost
D/HidService( 6543): setHidService(): set to: null
D/BluetoothAdapterService( 6543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28ecf7cc
,I/BluetoothHealthServiceJni( 6543): classInitNative: succeeds
,D/HealthService( 6543): Received start request. Starting profile...
,I/bluedroid( 6543): get_profile_interface health
,D/BluetoothAdapterService( 6543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28ecf7cc
,I/BluetoothPanServiceJni( 6543): classInitNative(L105): succeeds
,D/BluetoothPan(  892): BluetoothPAN Proxy object connected
,D/BluetoothMediaBrowser( 6543): no now playing list
D/BluetoothMediaBrowser( 6543):  getNowPlayingId now playing id : -1
D/Avrcp   ( 6543):  checkNowPlayingList start
D/PanService( 6543): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 6543): initializeNative(L110): pan
I/bluedroid( 6543): get_profile_interface pan
,D/BluetoothAdapterService( 6543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28ecf7cc
,D/BluetoothMapService( 6543): Received start request. Starting profile...
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6604): MountEmulatedStorage()
E/Zygote  ( 6604): v2
I/libpersona( 6604): KNOX_SDCARD checking this for 10163
I/libpersona( 6604): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6604 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 6604): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6604): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6604): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/WebViewChromiumFactoryProvider( 6573): Binding Chromium to main looper Looper (main, tid 1) {2d8f8159}
,I/LibraryLoader( 6573): Expected native library version number "",actual native library version number ""
,I/chromium( 6573): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/TimaKeyStoreProvider( 6604): TimaSignature is unavailable
,D/ActivityThread( 6604): Added TimaKeyStore provider
,D/ResourcesManager( 6604): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 6604): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6604): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6604): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6604): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/BrowserStartupController( 6573): Initializing chromium process, renderers=0
,W/art     ( 6573): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6573): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6573): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6573): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46768 len=2953
,I/chromium( 6573): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229524 len:643667
,I/Adreno-EGL( 6573): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6573): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6573): Build Date: 03/03/15 Tue
I/Adreno-EGL( 6573): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 6573): Remote Branch: 
I/Adreno-EGL( 6573): Local Patches: 
I/Adreno-EGL( 6573): Reconstruct Branch: 
,D/RCPManagerService(  892): exchangeData() failure , invalid userId
,D/RCPManagerService(  892): exchangeData() failure , invalid userId
,D/RCPManagerService(  892): exchangeData() failure , invalid userId
,D/RCPManagerService(  892): exchangeData() failure , invalid userId
,D/BluetoothAdapterService( 6543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28ecf7cc
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6644): MountEmulatedStorage()
,E/Zygote  ( 6644): v2
I/libpersona( 6644): KNOX_SDCARD checking this for 10078
I/libpersona( 6644): KNOX_SDCARD not a persona
,I/BluetoothSAPServiceJni( 6543): classInitNative(L204): succeeds
,I/ActivityManager(  892): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6644 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,W/chromium( 6573): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6573): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/SELinux ( 6644): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/SapService( 6543): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 6543): initializeNative(L209): sap
I/bluedroid( 6543): get_profile_interface sap
D/BluetoothAdapterService( 6543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28ecf7cc
E/BluetoothAdapterService(686618572)( 6543): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
D/HeadsetStateMachine( 6543): Proxy object connected
D/HeadsetStateMachine( 6543): Try to query the phonestate on bind
I/SELinux ( 6644): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6644): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/Telecom ( 1466): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1466): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1466): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,I/SecureStorage( 6558): [INFO]: SPID(0x00000000)Processing data has been completed
,W/BluetoothHeadset( 1466): Proxy not attached to service
I/Telecom ( 1466): BluetoothPhoneService: Result of Message : true
E/BluetoothAdapterService(686618572)( 6543): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService( 6543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp( 6543): Proxy object connected
D/BluetoothAdapterService( 6543): Bluetooth A2dp source service connected
E/BluetoothAdapterService(686618572)( 6543): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(686618572)( 6543): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(686618572)( 6543): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/HeadsetStateMachine( 6543): Disconnected process message: 10
D/HeadsetPhoneState( 6543): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6543): Disconnected process message: 11
,E/BluetoothAdapterService(686618572)( 6543): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,I/ActivityManager(  892): Killing 5719:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,E/BluetoothAdapterService(686618572)( 6543): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(686618572)( 6543): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/BluetoothAdapterState( 6543): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 6543): enable
,I/bt_hci_bdroid( 6543): init
I/GKI_LINUX( 6543): gki_task_entry task_id=0 [BTU] starting
,I/bt_vendor( 6543): init
I/bt_vnd_conf( 6543): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 6543): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 6543): userial_init
D/bt_vendor( 6543): op for 5
,D/TimaKeyStoreProvider( 6644): TimaSignature is unavailable
D/bt_vendor( 6543): op for 0
D/ActivityThread( 6644): Added TimaKeyStore provider
D/bt_upio ( 6543): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6543): is_emulator_context : 0
D/bt_upio ( 6543): is_rfkill_disabled ? [0]
D/bt_upio ( 6543): is_rfkill_disabled ? [0]
D/bt_vendor( 6543): op for 0
D/bt_upio ( 6543): upio_set_bluetooth_power(on: 1)
D/bt_upio ( 6543): is_emulator_context : 0
D/bt_upio ( 6543): is_rfkill_disabled ? [0]
D/bt_vendor( 6543): op for 3
I/bt_userial_vendor( 6543): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 6543): userial_vendor_open():UART is setup
I/bt_userial_vendor( 6543): device fd = 65 open
I/SecureStorage( 6558): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6558): [INFO]: SPID(0x00000000)This device supports Secure Storage
D/bt_vendor( 6543): op for 1
E/bt_hwcfg( 6543): Start CFG HW, HCI reset
,D/bt_userial( 6543): Entering userial_read_thread()
I/SecureStorage(  335): [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6558
I/SecureStorage(  335): [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C
I/SecureStorage( 6558): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6558): ssSupport state is = 1
,I/wpa_supplicant( 6558): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6558): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6558): SIM READ ERROR
I/wpa_supplicant( 6558): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6558): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6558): SIM READ ERROR
I/wpa_supplicant( 6558): Blacklist: Clear (all) 
,I/wpa_supplicant( 6558): wpa_default_ap_write_once
I/wpa_supplicant( 6558): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 6558): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6558): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 6558): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6558): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/ActivityManager(  892): Killing 5759:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/wpa_supplicant( 6558): rfkill: Cannot open RFKILL control device
,W/art     ( 6573): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6573): onDetachedFromWindow called when already detached. Ignoring
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,D/com.peel.util.a.e( 6573): ***************************** InsightsJournal version: 1
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_5719/cgroup.procs: No such file or directory
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,E/bt_hwcfg( 6543): Read Local Name after HCI reset
,W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_5759/cgroup.procs: No such file or directory
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,D/com.peel.e.c( 6573): ***************************** DB version: 19
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,D/com.peel.receiver.ConnectivityActionReceiver( 6573): ConnectivityActionReceiver onReceive
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
D/com.peel.receiver.ConnectivityActionReceiver( 6573): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
,D/com.peel.receiver.ConnectivityActionReceiver( 6573): NO active network... no services...
V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
D/com.peel.receiver.ConnectivityActionReceiver( 6573): last run: 1456825742357 -- System.currentTimeMillis()-last_run: 83125614
V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
D/bt_hwcfg( 6543): Chipset BCM4350C0
D/bt_hwcfg( 6543): Target name = [BCM4350C0]
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
I/bt_hwcfg( 6543): module_type[semco3rd] is invalid.
E/bt_hwcfg( 6543): finish scan emr path. reset chip id to BCM4350C0
E/bt_hwcfg( 6543): patchram path ORG . BCM4350C0
D/com.peel.data.m( 6573): 
D/com.peel.data.m( 6573): 
D/com.peel.data.m( 6573):  ######### Clean Up Bad Data ########
D/com.peel.data.m( 6573): 
D/com.peel.data.m( 6573): 
D/com.peel.data.m( 6573): 
D/com.peel.data.m( 6573):  ######### restoreControlDevice ########
D/com.peel.data.m( 6573): 
,E/bt_hwcfg( 6543): patchram path ORG .. BCM4350C0
E/bt_hwcfg( 6543): patchram path ORG bcm4350_V0301.0561.hcd BCM4350C0
E/bt_hwcfg( 6543): patchram path ORG libpn547_fw.so BCM4350C0
E/bt_hwcfg( 6543): fw ver (emr)0.0 // (org)0.0
E/bt_hwcfg( 6543): vendor lib preload failed to locate firmware patch file
E/bt_hwcfg( 6543): Remove module rev, try again BCM4350
,D/bt_hwcfg( 6543): Target name = [BCM4350]
I/bt_hwcfg( 6543): module_type[semco3rd] is invalid.
V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
E/bt_hwcfg( 6543): finish scan emr path. reset chip id to BCM4350
E/bt_hwcfg( 6543): patchram path ORG . BCM4350
E/bt_hwcfg( 6543): patchram path ORG .. BCM4350
,E/bt_hwcfg( 6543): patchram path ORG bcm4350_V0301.0561.hcd BCM4350
I/bt_hwcfg( 6543): patch(org) : bcm4350_V0301.0561.hcd
I/bt_hwcfg( 6543): Found patchfile: /vendor/firmware/bcm4350_V0301.0561.hcd
E/bt_hwcfg( 6543): ORG patchram base 0301
E/bt_hwcfg( 6543): ORG patchram minor 0561
E/bt_hwcfg( 6543): fw ver (emr)0.0 // (org)301.561
E/bt_hwcfg( 6543): Final Patchram is /vendor/firmware/bcm4350_V0301.0561.hcd
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,I/art     (  892): Explicit concurrent mark sweep GC freed 21229(1258KB) AllocSpace objects, 4(64KB) LOS objects, 30% free, 36MB/52MB, paused 1.946ms total 107.298ms
,I/ActivityManager(  892): Killing 5343:com.google.android.gm/u0a114 (adj 15): bgCount ##41
,I/bt_hwcfg( 6543): Axi patch failure or not include AXI patching
,D/ResourcesManager( 6644): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/com.peel.control.ar( 6573): 
D/com.peel.control.ar( 6573): *************Loader.load()
,D/com.peel.util.i( 6573): NON-UI THREAD notify observers (0ms)
D/com.peel.control.ar( 6573): load +
I/bt_hwcfg( 6543): bt vendor lib: set UART baud 3000000
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/BadgeProvider( 6644): onCreate
,D/BadgeProvider( 6644): DatabaseHelper
,D/com.peel.control.ar( 6573): load -
,D/c       ( 6573): ControlEvents.LOADED received
,D/com.peel.util.i( 6573): NON-UI THREAD notify observers (0ms)
D/com.peel.util.i( 6573): NON-UI THREAD notify observers (0ms)
D/com.peel.util.i( 6573): DB THREAD load stuff from the database (84ms)
,D/BadgeProvider( 6644): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BluetoothNotiBroadcastReceiver( 1294): onReceive
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 6604): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/com.peel.util.i( 6573): NON-UI THREAD notify observers (0ms)
,D/c       ( 6573): ContentEvents.LOADED received
,D/AuthorizationBluetoothService( 1685): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/com.peel.util.i( 6573): DB THREAD loading room null (18ms)
,D/BadgeProvider( 6644): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6644): sendNotify, [notify] : null
D/BadgeProvider( 6644): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6644): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6644): update, [UpdateCount] : 1
,D/Launcher.Model( 1504): reloadBadges entered.
,W/libprocessgroup(  892): failed to open /acct/uid_10114/pid_5343/cgroup.procs: No such file or directory
,D/com.peel.util.i( 6573): UI THREAD load ui from app (0ms)
,D/com.peel.util.i( 6573): NON-UI THREAD notify observers (14ms)
,W/ActivityManager(  892): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/wpa_supplicant( 6558): wlan0: Setting scan request: 0 sec 100000 usec
,E/Tethering(  892): No numeric data
,D/Tethering(  892): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  892): forceRefresh() from cache miss
D/HotspotTile( 1168): onReceive : android.net.conn.TETHER_STATE_CHANGED
,I/wpa_supplicant( 6558): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage( 6558): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6558): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  335): [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6558
I/SecureStorage(  335): [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C
I/SecureStorage( 6558): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6558): ssSupport state is = 1
,D/HotspotTile( 1168): updateTetherState():false, false
,I/SecureStorage( 6558): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6558): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  335): [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6558
I/SecureStorage(  335): [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C
I/SecureStorage( 6558): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6558): ssSupport state is = 1
I/wpa_supplicant( 6558): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6558): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6558): SIM READ ERROR
I/wpa_supplicant( 6558): wpa_default_ap_write_once
I/wpa_supplicant( 6558): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 6558): rfkill: Cannot open RFKILL control device
,D/NtpTrustedTime(  892): forceRefresh Fail.
,V/NetworkStats(  892): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  892): UpdateStatsForKnox
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  892): performPollLocked() took 7ms
,I/wpa_supplicant( 6558): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 6558): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6558): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 6558): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  892): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,E/WifiStateMachine(  892): setSuspendOptimizations: 2 true
E/WifiStateMachine(  892): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine(  892): Supplicant connection established
,D/WifiNative-HAL(  892): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 6558): HOTSPOT20_ENABLE called
I/wpa_supplicant( 6558): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6558): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6558): SIM READ ERROR
I/wpa_supplicant( 6558): Blacklist: Clear (all) 
,W/ProcessCpuTracker(  892): Skipping unknown process pid 6561
,W/ProcessCpuTracker(  892): Skipping unknown process pid 6562
,W/ProcessCpuTracker(  892): Skipping unknown process pid 6569
W/ProcessCpuTracker(  892): Skipping unknown process pid 6571
,W/ProcessCpuTracker(  892): Skipping unknown process pid 6677
,D/NtpTrustedTime(  892): forceRefresh() from cache miss
,D/NtpTrustedTime(  892): forceRefresh Fail.
I/wpa_supplicant( 6558): Skip scan - bUseNetwork false
,E/WifiStateMachine(  892): setWifiState: enabled
,D/WifiNative-HAL(  892): callSECApiInt - ID [210]
,D/WifiConfigStore(  892): Loading config and enabling all networks 
,D/SmartBondingService(  892): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SmartBondingService(  892): getNetworkEnabled : wifi : true mobile : true
,D/SLocation(  892): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/STATUSBAR-WifiQuickSettingButton( 1168): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1168): Wifi onReceive(3)
D/STATUSBAR-QSTileView( 1168): onStateChanged: Wi-Fi
,V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_wifi_on.png
,E/WifiConfigStore(  892): Not a HS20
D/HotspotTile( 1168): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1168): onReceive : 3, 0
,D/WifiCredService( 1294): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/WifiStateMachine(  892): callSECApi what=207
,D/SecurityLogAgent( 6503): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6503): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6503): StateMachine : Current State = 1
D/SecurityLogAgent( 6503): StateMachine : Changed Current State = 1
,E/WifiConfigStore(  892): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/com.peel.receiver.ConnectivityActionReceiver( 6573): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
D/com.peel.receiver.ConnectivityActionReceiver( 6573): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
,D/com.peel.receiver.ConnectivityActionReceiver( 6573): NO active network... no services...
D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
D/com.peel.receiver.ConnectivityActionReceiver( 6573): last run: 1456908867971 -- System.currentTimeMillis()-last_run: 576
D/com.peel.receiver.ConnectivityActionReceiver( 6573): ... skip 
,I/WifiStateMachine(  892): update LTECoexState:0
D/WifiNative-HAL(  892): callSECApiInt - ID [65]
,D/PackageManager(  892): [MSG] MCS_UNBIND
,D/WifiNative-HAL(  892): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 6558): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6558): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 6558): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6558): P2P: Current p2p state = IDLE
I/wpa_supplicant( 6558): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 6558): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6558): First Scan Start
,I/wpa_supplicant( 6558): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-HAL(  892): Setting external_sim to 1
,D/WifiStateMachine(  892): Setting OUI to DA-A1-19
I/WifiNative-HAL(  892): startHal
,E/wifi    (  892): getStaticLongField sWifiHalHandle 0x95ce185c
D/wifi    (  892): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x602252
I/WifiNative-HAL(  892): Could not start hal
,E/WifiStateMachine(  892): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,E/native  (  892): do suspend true
,W/Settings( 4195): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiP2pService(  892): P2pDisabledState{ what=131203 }
,I/ActivityManager(  892): Killing 5189:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,D/CommandListener(  281): Setting iface cfg
D/CommandListener(  281): Trying to bring up p2p0
,D/WifiMonitor(  892): startMonitoring(p2p0) with mConnected = true
,D/WifiP2pService(  892): P2pEnablingState
I/bt_hwcfg( 6543): bt vendor lib: set UART baud 115200
I/bt_hwcfg( 6543): FW Download delta = 623983
,D/bt_hwcfg( 6543): Settlement delay -- 100 ms
I/bt_hwcfg( 6543): Setting fw settlement delay to 100 
D/WifiScanningService(  892): SCAN_AVAILABLE : 3
D/WifiScanningService(  892): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  892): startHal
E/wifi    (  892): getStaticLongField sWifiHalHandle 0x98c6a98c
D/wifi    (  892): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x202206
I/WifiNative-HAL(  892): Could not start hal
E/WifiScanningService(  892): could not start HAL
,D/RttService(  892): SCAN_AVAILABLE : 3
E/WifiStateMachine(  892): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/RttService(  892): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  892): updateConfiguredNetworkExpiration - currTime: 1456908868577
D/WifiStateMachine(  892): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/WifiP2pService(  892): P2pEnablingState{ what=147457 }
D/WifiP2pService(  892): P2p socket connection successful
D/WifiP2pService(  892): P2pEnabledState
,E/WifiStateMachine(  892): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL(  892): callSECStringApiVoid - ID [215]
E/WifiNative-HAL(  892): invaild command id : 215
,D/WifiP2pService(  892): sending p2p connection changed broadcast: IDLE
E/WifiStateMachine(  892): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController(  892): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/WifiDisplayController(  892): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
E/WifiStateMachine(  892): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/WifiDisplayController(  892): disconnect
D/WifiDisplayController(  892): updateConnection
D/WifiDisplayController(  892): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  892): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService(  892): create mNetworkAgent
,D/AllShareCastTile( 1168): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter(  892): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1168): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
D/WifiDisplayController(  892): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  892): set country code pl
,D/NearbySettings( 1294): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1294): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1294): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1294): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1294): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1294): MountReceiver.onReceive - Set preference state off
,D/ConnectivityService(  892): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
V/NearbySettings( 1294): MountReceiver.mPrefHandler - 7002
D/ConnectivityService(  892): Got NetworkAgent Messenger
,D/ConnectivityService(  892): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ConnectivityService(  892): updateNetworkInfo()
,D/ConnectivityService(  892): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  892): NetworkAgent connected
E/CSLegacyTypeTracker(  892): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,I/wpa_supplicant( 6558): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/WifiStateMachine(  892): set frequency band 0
,E/Zygote  ( 6698): MountEmulatedStorage()
E/Zygote  ( 6698): v2
I/libpersona( 6698): KNOX_SDCARD checking this for 10075
I/libpersona( 6698): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6698 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6698): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6698): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6698): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  892): failed to open /acct/uid_10004/pid_5189/cgroup.procs: No such file or directory
,I/wpa_supplicant( 6558): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/TimaKeyStoreProvider( 6698): TimaSignature is unavailable
,D/ActivityThread( 6698): Added TimaKeyStore provider
,D/WifiNative-HAL(  892): p2pGetDeviceAddress
,E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  892): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine(  892): setDetailed state send new extra info0x
,D/WifiNative-HAL(  892): p2pGetDeviceAddress returning ee:1f:72:18:8b:78
,D/SecContentProvider2(  892): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  892): mCursor = null
,D/WifiDisplayController(  892): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy S5)
D/WifiDisplayController(  892):  deviceAddress: ee:1f:72:18:8b:78
D/WifiDisplayController(  892):  primary type: 10-0050F204-5
D/WifiDisplayController(  892):  secondary type: null
D/WifiDisplayController(  892):  wps: 0
D/WifiDisplayController(  892):  grpcapab: 0
D/WifiDisplayController(  892):  devcapab: 0
D/WifiDisplayController(  892):  status: 3
D/WifiDisplayController(  892):  wfdInfo: null
D/WifiDisplayController(  892):  groupownerAddress: null
D/WifiDisplayController(  892):  GOdeviceName: null
D/WifiDisplayController(  892):  interfaceAddress: 
D/WifiDisplayController(  892):  SConnectInfo : null
,D/WifiP2pService(  892): DeviceAddress: ee:8b:78
,D/SecContentProvider2(  892): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  892): mCursor = null
,D/ResourcesManager( 6698): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/WifiP2pService(  892): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  892): InactiveState
,E/ConnectivityService(  892): updateNetworkInfo()
D/ConnectivityService(  892): ignoring duplicate network state non-change
,D/WifiP2pService(  892): InactiveState{ what=143376 }
D/WifiP2pService(  892): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 6558): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/WifiP2pService(  892): InactiveState{ what=143376 }
,D/WifiP2pService(  892): P2pEnabledState{ what=143376 }
,D/FileShare-Server( 6698): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager(  892): Killing 5225:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,I/bt_hwcfg( 6543): bt vendor lib: set UART baud 3000000
,W/libprocessgroup(  892): failed to open /acct/uid_10044/pid_5225/cgroup.procs: No such file or directory
,I/bt_hwcfg( 6543): vendor lib fwcfg completed
,I/        ( 6543): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 6543): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6543): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6543): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6543): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6543): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6543): BTE_InitTraceLevels -- TRC_BNEP
,I/        ( 6543): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6543): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6543): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6543): BTE_InitTraceLevels -- TRC_SAP
I/        ( 6543): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6543): BTE_InitTraceLevels -- TRC_GATT
,I/        ( 6543): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6543): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6543): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 6543): BTE_InitTraceLevels -- TRC_PROTOCOL
,W/bt-l2cap( 6543): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  ( 6543): BTM_SecRegister:p_cb_info->p_le_callback == 0xb3b2c231 
,E/bt-btm  ( 6543): BTM_SecRegister: btm_cb.api.p_le_callback = 0xb3b2c231 
,I/wpa_supplicant( 6558): nl80211: Received scan results (14 BSSes)
I/wpa_supplicant( 6558): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 6558): Trying to associate with F4.99.3E (SSID='4E47373030' freq=2437 MHz)
,I/wpa_supplicant( 6558): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 6558): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,I/WifiNative-HAL(  892): startHal
,E/wifi    (  892): getStaticLongField sWifiHalHandle 0x95ce187c
,D/wifi    (  892): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x202026
I/WifiNative-HAL(  892): Could not start hal
,E/WifiStateMachine(  892): [1,456,908,869,163 ms] noteScanEnd no scan source
,D/BluetoothAdapterProperties( 6543): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 6543): Calling BTA_HhEnable
,E/bt-btif ( 6543): btif_storage_get_adapter_property service_mask:0x2120048
,D/BluetoothAdapterProperties( 6543): Address is:B0:C5:59:3F:75:69
E/BluetoothServiceJni( 6543): populateRssiValuesNative
I/bluedroid( 6543): getModelRssiValues
,E/BluetoothServiceJni( 6543): model_rssi_values_callback: low = -70, mid = -60, high = 127
,D/BluetoothAdapterProperties( 6543): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 6543): Name is: Thali Test (Galaxy S5)
,D/SettingsProvider(  892): name = bluetooth_name
,D/BluetoothAdapterProperties( 6543): Scan Mode:20
D/BluetoothAdapterProperties( 6543): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 6543): LE Address is:F0:8B:B2:7E:EA:D2
,D/bt_vendor( 6543): op for 2
D/bt_vendor( 6543): op for 6
,D/bt_vendor( 6543): op for 7
,E/bt-btif ( 6543): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
D/bt_upio ( 6543): proc btwrite assertion
,E/bt-btif ( 6543): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,D/bt_vendor( 6543): op for 7
D/bt_upio ( 6543): BT_WAKE is asserted already
E/bt-btif ( 6543): btif_sock_init: !radio_req && !rfc_init
,E/bt-btif ( 6543): btif_sock_init: !vhci_init
D/IOP_DB_BT( 6543): db_open: file /etc/bluetooth/iop_bt.db
,D/bt_vendor( 6543): op for 7
D/bt_upio ( 6543): BT_WAKE is asserted already
,D/IOP_DB_BT( 6543): db_open: db_open : handle 3025690640l, read 13774 bytes onto local cache
D/IOP_DB_BT( 6543): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/IOP_DB_BT( 6543): db_query: result 1
I/        ( 6543): iop_db_open: iop_db_open status 0
,D/bte_conf( 6543): Device ID record 1 : primary
,D/bte_conf( 6543):   vendorId            = 0075
D/bte_conf( 6543):   vendorIdSource      = 0001
D/bte_conf( 6543):   product             = 0100
D/bte_conf( 6543):   version             = 0200
D/bte_conf( 6543):   clientExecutableURL = 
,D/bte_conf( 6543):   serviceDescription  = 
D/bte_conf( 6543):   documentationURL    = 
D/bte_conf( 6543): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 6543): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 6543): ScanMode =  20
D/BluetoothAdapterProperties( 6543): State =  11
,D/BluetoothPanServiceJni( 6543): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/SecContentProvider(  892): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties( 6543): Setting state to 12
I/BluetoothAdapterState( 6543): Bluetooth adapter state changed: 11-> 12
,D/SettingsProvider(  892): name = bluetooth_a2dp_sink_mode
,D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 1002
,D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,W/BackupManagerService(  892): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 6543): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 6543): updateAdapterState state is 12
,D/BluetoothAdapterService( 6543): Autoconnection is available 
,D/BluetoothAdapterService( 6543): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 6543): starting service from this receiver
,D/bt_vendor( 6543): op for 7
,D/bt_upio ( 6543): BT_WAKE is asserted already
,E/bt_h4   ( 6543): vendor lib postload completed
,D/bt_vendor( 6543): op for 7
D/bt_upio ( 6543): BT_WAKE is asserted already
,D/bt_vendor( 6543): op for 7
,D/bt_upio ( 6543): BT_WAKE is asserted already
,D/bt_vendor( 6543): op for 7
,D/bt_upio ( 6543): BT_WAKE is asserted already
,I/BluetoothAdapterState( 6543): Entering On State from state = 11
,D/bt_vendor( 6543): op for 7
,D/bt_upio ( 6543): BT_WAKE is asserted already
D/BluetoothAdapterProperties( 6543): Scan Mode:21
D/BluetoothAdapterProperties( 6543): Discoverable Timeout:120
,D/bt_vendor( 6543): op for 7
,D/bt_upio ( 6543): BT_WAKE is asserted already
,D/bt_vendor( 6543): op for 7
,D/bt_upio ( 6543): BT_WAKE is asserted already
,D/bt_vendor( 6543): op for 7
,D/bt_upio ( 6543): BT_WAKE is asserted already
,D/bt_vendor( 6543): op for 7
,D/bt_upio ( 6543): BT_WAKE is asserted already
,D/BluetoothA2dp( 3302): onBluetoothStateChange: up=true
,D/bt_vendor( 6543): op for 7
,D/bt_upio ( 6543): BT_WAKE is asserted already
,D/bt_vendor( 6543): op for 7
D/bt_upio ( 6543): BT_WAKE is asserted already
,D/bt_vendor( 6543): op for 7
,D/bt_upio ( 6543): BT_WAKE is asserted already
,I/BluetoothPbapService( 6543): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/bt_vendor( 6543): op for 7
D/bt_upio ( 6543): BT_WAKE is asserted already
,D/BluetoothA2dp( 6543): onBluetoothStateChange: up=true
,D/bt_vendor( 6543): op for 7
,D/bt_upio ( 6543): BT_WAKE is asserted already
D/BluetoothA2dp(  892): onBluetoothStateChange: up=true
I/wpa_supplicant( 6558): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 6558): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,D/bt_vendor( 6543): op for 7
,I/wpa_supplicant( 6558): Associated with F4.99.3E
D/bt_upio ( 6543): BT_WAKE is asserted already
I/wpa_supplicant( 6558): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 6558): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,D/bt_vendor( 6543): op for 7
,D/bt_upio ( 6543): BT_WAKE is asserted already
E/WifiStateMachine(  892): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1512a8a9 sup_state=SCANNING debouncing=false
,W/InputMethodManagerService(  892): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,D/bt_vendor( 6543): op for 7
D/bt_upio ( 6543): BT_WAKE is asserted already
I/InputMethodManagerService(  892): [BT Setting State] State =12
,I/InputMethodManagerService(  892): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,D/bt_vendor( 6543): op for 7
D/bt_upio ( 6543): BT_WAKE is asserted already
E/WifiStateMachine(  892): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,D/bt_vendor( 6543): op for 7
D/bt_upio ( 6543): BT_WAKE is asserted already
E/WifiStateMachine(  892): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/bt_vendor( 6543): op for 7
,D/bt_upio ( 6543): BT_WAKE is asserted already
,I/wpa_supplicant( 6558): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/bt_vendor( 6543): op for 7
D/bt_upio ( 6543): BT_WAKE is asserted already
,I/wpa_supplicant( 6558): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 6558): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,I/wpa_supplicant( 6558): wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6558): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 6558): CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 6558): Blacklist: Clear (temp) 
I/wpa_supplicant( 6558): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,D/BluetoothHeadset( 1466): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@34fdcc8a, true
,D/BluetoothHeadset( 1466): registerMessageListener
,E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  892): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  892): setDetailed state send new extra info"NG700"
,I/SamsungIME( 1832): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/SecContentProvider2(  892): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  892): mCursor = null
,D/[CarModeFW]( 6227): ConnectivityManager-handleMessage INITIAL_STATE_ON
,I/CLocInfoService(  892): External Intent Received android.net.wifi.SCAN_RESULTS
,D/BluetoothTile( 1168): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/STATUSBAR-QSTileView( 1168): onStateChanged: Bluetooth
,D/HeadsetService( 6543): registerMessageListener
,D/HeadsetService( 6543): registerMessageListener
D/HeadsetStateMachine( 6543): Disconnected process message: 70
I/Telecom ( 1466): BluetoothPhoneService: updateHeadsetWithCallState
D/HeadsetStateMachine( 6543): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@32a5f0eb
I/Telecom ( 1466): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/SecContentProvider2(  892): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  892): mCursor = null
I/BluetoothPbapService( 6543): Handler(): got msg=1
,D/HeadsetStateMachine( 6543): Disconnected process message: 9
D/SecContentProvider(  892): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/HeadsetStateMachine( 6543): mNumActive: 0 mNumHeld: 0 mCallState: 6
,E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  892): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_bluetooth_on.png
,D/audio_hw_primary(  292): adev_set_parameters: enter: A2dpSuspended=false
,V/voice   (  292): voice_set_parameters: enter: A2dpSuspended=false
,V/voice   (  292): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  292): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  292): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  292): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  292): adev_set_parameters: exit
,E/HeadsetStateMachine( 6543): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,V/BluetoothPbapService( 6543): PBAP Service initSocket try: 0
E/WifiStateMachine(  892): Network connection established
,D/WifiNative-HAL(  892): callSECApiVoid - ID [50]
,E/WifiStateMachine(  892): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,D/BluetoothManagerService(  892): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/BluetoothMapMasInstance( 6543): set MAP SDP message type : 1
,W/BluetoothAdapter( 6543): getBluetoothService() called with no BluetoothManagerCallback
,E/WifiStateMachine(  892): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,W/BluetoothAdapter( 6543): getBluetoothService() called with no BluetoothManagerCallback
D/bt_vendor( 6543): op for 7
D/bt_upio ( 6543): BT_WAKE is asserted already
I/CLocInfoService(  892): External Intent Received android.net.wifi.STATE_CHANGE
D/BluetoothSocket( 6543): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
,D/BluetoothSocket( 6543): bindListen(), new LocalSocket 
D/BluetoothSocket( 6543): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6543): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@378f44e1
,D/BluetoothSocket( 6543): channel: 19
D/BluetoothPbapService( 6543): PBAP Socket is BluetoothServerSocket
D/LocalBluetoothProfileManager( 1294): Adding local A2DP profile
,D/ConnectivityService(  892): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  892): L2ConnectedState f4:f2:6d:22:99:3e config "NG700"WPA_PSK config.bssid null
,E/WifiStateMachine(  892): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  892): Got NetworkAgent Messenger
D/ConnectivityService(  892): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  892): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiConfigStore(  892): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  892): NetworkAgent connected
E/ConnectivityService(  892): updateNetworkInfo()
,D/BluetoothSocket( 6543): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 6543): bindListen(), new LocalSocket 
D/BluetoothSocket( 6543): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6543): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36031206
,D/bt_vendor( 6543): op for 7
D/bt_upio ( 6543): BT_WAKE is asserted already
D/BluetoothSocket( 6543): channel: 5
D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  892): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine(  892): ObtainingIpAddress f4:f2:6d:22:99:3e config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  892): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  892): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/LocalBluetoothProfileManager( 1294): Adding local HEADSET profile
,E/BluetoothHeadset( 1294): BTStateChangeCB is registed
,E/BluetoothHeadset( 1294): BluetoothHeadset service is binded
,D/CommandListener(  281): Setting iface cfg
,E/WifiStateMachine(  892): Start Dhcp Watchdog 1
,D/SecContentProvider2(  892): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  892): mCursor = null
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2067 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/Bluetoothsap( 1294): bindService called to Bluetooth SAP Service
,I/WifiStateMachine(  892): REQUEST_POWER_SAVE_ON
,D/SecContentProvider2(  892): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  892): mCursor = null
,D/LocalBluetoothProfileManager( 1294): PANU : true
D/LocalBluetoothProfileManager( 1294): Adding local MAP profile
,D/BluetoothMap( 1294): Create BluetoothMap proxy object
,E/WifiStateMachine(  892): Force RSSI Broadcast 1/3
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/LocalBluetoothProfileManager( 1294): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1294): LocalBluetoothProfileManager construction complete
,E/WifiStateMachine(  892): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  892): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  892): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/DockEventReceiver( 1294): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1294): onReceive
,D/BluetoothA2dp( 1294): Proxy object connected
,D/A2dpProfile( 1294): Bluetooth service connected
,D/BluetoothAdapterService( 6543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28ecf7cc
D/BtConfig.SecureMode( 6543): isSecureModeOn:false
,D/HeadsetProfile( 1294): Bluetooth service connected
,D/AuthorizationBluetoothService( 1685): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/Bluetoothsap( 1294): BluetoothSAP Proxy object connected
,D/SapProfile( 1294): Bluetooth service connected
D/Bluetoothsap( 1294): getConnectedDevices()
,D/BluetoothInputDevice( 1294): Proxy object connected
,D/HidProfile( 1294): Bluetooth service connected
,D/BluetoothPan( 1294): BluetoothPAN Proxy object connected
,D/PanProfile( 1294): Bluetooth service connected
,D/BluetoothMap( 1294): Proxy object connected
,D/MapProfile( 1294): Bluetooth service connected
D/BluetoothPbap( 1294): Proxy object connected
D/PbapServerProfile( 1294): Bluetooth service connected
,D/SecContentProvider(  892): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/Hs20UtilService( 1294): Starting #2
,I/Hs20UtilService( 1294): Message received 5007
,D/NearbySettings( 1294): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1294): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1294): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1294): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1294): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1294): MountReceiver.onReceive - Set preference state off
,W/BluetoothAdapter( 6543): getBluetoothService() called with no BluetoothManagerCallback
V/NearbySettings( 1294): MountReceiver.mPrefHandler - 7002
,D/bt_vendor( 6543): op for 7
D/BluetoothSocket( 6543): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
D/bt_upio ( 6543): BT_WAKE is asserted already
D/BluetoothSocket( 6543): bindListen(), new LocalSocket 
,D/BluetoothSocket( 6543): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6543): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@563ae60
D/BluetoothSocket( 6543): channel: 12
I/BtOppRfcommListener( 6543): Accept thread started.
,E/WifiStateMachine(  892): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  892): do suspend false
,D/WifiP2pService(  892): InactiveState{ what=143375 }
,D/WifiP2pService(  892): P2pEnabledState{ what=143375 }
,D/SecContentProvider2(  892): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  892): mCursor = null
,V/AlarmManager(  892): waitForAlarm result :8
,E/dhcpcd  ( 6758): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6758): version 5.5.6 starting
,E/dhcpcd  ( 6758): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/BatteryService(  892): level:100, scale:100, status:2, health:2, present:true, voltage: 4312, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  892): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  892): stay LED for charging
D/BatteryService(  892): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  892): Plugged
I/MotionRecognitionService(  892): setPowerConnected  = true
,E/SMD     (  287): DCD ON
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
I/dhcpcd  ( 6758): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 6758): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6758): if(wlan0) info get Success. (MAC : F4.99.3E)
D/HeadsetStateMachine( 6543): Disconnected process message: 10
,I/dhcpcd  ( 6758): bssid match
,I/dhcpcd  ( 6758): wlan0: rebinding lease of 192.168.1.105
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/dhcpcd  ( 6758): wlan0: acknowledged 192.168.1.105 from 192.168.1.1
,I/dhcpcd  ( 6758): wlan0: leased 192.168.1.105 for 172800 seconds
,E/WifiStateMachine(  892): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  892): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,E/WifiStateMachine(  892): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/Watchdog(  892): !@Sync 2
,V/AlarmManager(  892): waitForAlarm result :8
,E/WifiStateMachine(  892): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  892): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  (  892): do suspend true
,D/NtpTrustedTime(  892): forceRefresh() from cache miss
,D/NtpTrustedTime(  892): forceRefresh Fail.
,D/WifiP2pService(  892): InactiveState{ what=143375 }
,D/WifiP2pService(  892): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  892): WifiStateMachine DHCP successful
,E/WifiStateMachine(  892): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  892): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  892): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,E/WifiStateMachine(  892): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine(  892): Not connected state, yet.
E/WifiStateMachine(  892): VerifyingLinkState enter
D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  892): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine(  892): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  892): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  892): callSECApiInt - ID [210]
,E/WifiStateMachine(  892): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  892): updateNetworkInfo()
,D/ConnectivityService(  892): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  892): Adding iface wlan0 to network 502
,I/CLocInfoService(  892): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  892): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  892): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  892): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  892): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  892): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  892): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  892): Now, connected state.
E/WifiStateMachine(  892): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/ConnectivityService(  892): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService(  892): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
E/WifiStateMachine(  892): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  892): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
E/WifiStateMachine(  892): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  892): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  892): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  892): updateSourceRoutes : add src route for:192.168.1.105
,E/WifiStateMachine(  892): ConnectedState Enter  mScreenOn=false scanperiod=20000
,V/        (  281): QcRouteController
,I/WifiTrafficPoller(  892): evaluateTrafficStatsPolling
,I/CLocInfoService(  892): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  892): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  892): mBoosterFLAG : 0
,I/WifiTrafficPoller(  892): current booster mode : FullMode
,D/WifiNative-HAL(  892): callSECApiVoid - ID [212]
,I/CLocInfoService(  892): External Intent Received android.net.wifi.STATE_CHANGE
,V/        (  281): QcRouteController
I/WifiStateMachine(  892): REQUEST_POWER_SAVE_ON
,I/Hs20UtilService( 1294): Starting #3
,I/Hs20UtilService( 1294): Message received 5007
,D/NearbySettings( 1294): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,I/NearbySettings( 1294): MountReceiver.onReceive - Keep current state
,V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_wifi_signal_4.png
,D/StatusBar.NetworkController( 1168): applyOpen
,V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_no_inout.png
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
V/        (  281): QcRouteController
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,V/        (  281): QcRouteController
,V/        (  281): QcRouteController
,I/Hs20UtilService( 1294): Starting #4
,I/Hs20UtilService( 1294): Message received 5007
,D/NearbySettings( 1294): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1294): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1294): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1294): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1294): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1294): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1294): MountReceiver.mPrefHandler - 7002
V/        (  281): QcRouteController
,I/Hs20UtilService( 1294): Starting #5
,I/Hs20UtilService( 1294): Message received 5007
,D/NearbySettings( 1294): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1294): MountReceiver.onReceive - Keep current state
,V/        (  281): QcRouteController
,V/        (  281): QcRouteController
,I/WifiStateMachine(  892): callSECApi what=220
D/WifiStateMachine(  892): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  281): QcRouteController
,D/ConnectivityService(  892): Setting Dns servers for network 502 to [/192.168.1.1]
,D/Nat464Xlat(  892): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  892): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  892): calling update connectivity
E/ConnectivityService(  892): updateNetworkInfo()
D/ConnectivityService(  892): ignoring duplicate network state non-change
E/ConnectivityService(  892): updateNetworkInfo()
D/ConnectivityService(  892): ignoring duplicate network state non-change
D/ConnectivityService(  892): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  892): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  892): calling update connectivity
D/ConnectivityService(  892): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  892):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  892):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Validated
D/ConnectivityService(  892):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  892): currentScore = 0, newScore = 60
D/ConnectivityService(  892):    accepting network in place of null
D/ConnectivityService(  892): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  892): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/TelephonyNetworkFactory( 1487): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  892): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  892): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  892): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  892): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  892): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  892): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  892): getSBEnabled() enabled =false
D/SmartBondingService(  892): getSBEnabled() enabled =false
D/NtpTrustedTime(  892): forceRefresh() from cache miss
,D/SmartBondingService(  892): getSBEnabled() enabled =false
V/NetworkStats(  892): updateIfacesLocked()
V/NetworkStats(  892): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  892): UpdateStatsForKnox
D/ConnectivityService(  892): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  892): getNetworkEnabled : wifi : true mobile : true
,V/NetworkStats(  892): performPollLocked() took 3ms
D/EntConnectivity(  892): Not allowed due to - mEnabled false
,D/ConnectivityService(  892): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  892): calling update connectivity
,I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ConnectivityService(  892):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  892):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  892): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  892): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  892): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524290
D/ConnectivityService(  892):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  892):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  892): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  892): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  892): calling update connectivity
D/ConnectivityService(  892):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  892):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  892): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/PowerManagerService(  892): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=892
D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524290
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1168): updateDataNetType()
D/StatusBar.NetworkController( 1168): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1168): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1168): updateDataNetType()
D/StatusBar.NetworkController( 1168): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1168): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  892): MasterInitialState.processMessage what=3
,D/SmartBondingService(  892): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  892): SmartBondingReceiver: wifi is connected
,D/SmartBondingService(  892): SmartBondingReceiver: wifi ap is changed, init speed ratio
,D/accuweather( 2092): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  892): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  892): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  892): getSBEnabled() enabled =false
,D/SmartBondingService(  892): getSBEnabled() enabled =false
D/SmartBondingService(  892): getSBEnabled() enabled =false
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  892): CLocinfo wifi true 
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  892): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  892): forceRefresh() from cache miss
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2181): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2181): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 6057): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6057): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6057): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6057): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3453): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3453): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3453): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3453): [llIlIIIIlllIlllllIll(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_DM  ( 3453): [IIllIIllIIIlllIlIIll(403/llllllIllIlIlllIIlIl)] Check completed.
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3453): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3453): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 3453): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/NetworkMonitor( 5064): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 3453): [IIIlllIlIIlllIIIIllI(73/llllIIIllIlIIIIllllI)] 
,D/bt_vendor( 6543): op for 7
,I/DBG_DM  ( 3453): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6850): MountEmulatedStorage()
E/Zygote  ( 6850): v2
I/libpersona( 6850): KNOX_SDCARD checking this for 10088
I/libpersona( 6850): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6850 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6850): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6850): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6850): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3453): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6859): MountEmulatedStorage()
E/Zygote  ( 6859): v2
I/libpersona( 6859): KNOX_SDCARD checking this for 10002
I/libpersona( 6859): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6859 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 3453): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 3453): [IIllIIllIIIlllIlIIll(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/DBG_DM  ( 3453): [IIllIIllIIIlllIlIIll(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 3453): [llIlIIIIlllIlllllIll(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 3453): [IIllIlIIlIlllIIllIII(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 3453): [llIlIIIIlllIlllllIll(1907/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 3453): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,I/SELinux ( 6859): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/DBG_DM  ( 3453): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/SELinux ( 6859): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/DBG_DM  ( 3453): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(501/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
E/SELinux ( 6859): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GoogleURLConnFactory( 1685): Using platform SSLCertificateSocketFactory
,D/TimaKeyStoreProvider( 6850): TimaSignature is unavailable
,D/ActivityThread( 6850): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 6859): TimaSignature is unavailable
,I/DBG_DM  ( 3453): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3453): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,D/ActivityThread( 6859): Added TimaKeyStore provider
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3453): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/DBG_DM  ( 3453): [IIllIlIIlIlllIIllIII(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 3453): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,D/ResourcesManager( 6850): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/DBG_DM  ( 3453): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,E/DBG_DM  ( 3453): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,D/ResourcesManager( 6859): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/DBG_DM  ( 3453): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@378f44e1
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3453): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3453): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,E/GpsLocationProvider(  892): No APN found to select.
,D/bt_upio ( 6543): ..proc_btwrite_timeout..
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager(  892): showStatusBarByNotification() mOpenByNotification=false
,D/ResourcesManager( 1168): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,I/DBG_DM  ( 3453): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_completion.qmg
,I/DBG_DM  ( 3453): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6898): MountEmulatedStorage()
I/libpersona( 6898): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6898): v2
I/libpersona( 6898): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6898 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_completion.qmg
,I/SELinux ( 6898): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6898): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6898): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/System.out( 1685): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1685): (HTTPLog)-Static: isShipBuild true
,D/KnoxNotification( 1168): ----- inflateViews : modified publicViewLocal -----
,I/System.out( 1685): (HTTPLog)-Thread-186-499095876: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/TimaKeyStoreProvider( 6898): TimaSignature is unavailable
,D/KnoxNotification( 1168): ----- inflateViews : modified KnoxViewLocal -----
D/ActivityThread( 6898): Added TimaKeyStore provider
,D/PersonaManager( 1168): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1168): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@37bec079
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,I/DBG_DM  ( 3453): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3453): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 3453): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,D/ResourcesManager( 6898): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/System.out( 3995): Thread-600(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/NtpTrustedTime(  892): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1456908871372 mCachedNtpElapsedRealtime : 75346 mCachedNtpCertainty : 27
D/NtpTrustedTime(  892): currentTimeMillis() cache hit
D/NtpTrustedTime(  892): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1456908871234 mCachedNtpElapsedRealtime : 75347 mCachedNtpCertainty : 27
,D/AlarmManagerService(  892): Setting time of day to sec=1456908871
D/AlarmManagerService(  892): Trying to open a file
,D/AlarmManagerService(  892): File Open Success
D/AlarmManagerService(  892): File Close Success
I/AlarmManagerService(  892): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager(  892): waitForAlarm result :65536
W/AlarmManagerService(  892): Unable to set rtc to 1456908871: Invalid argument
D/NtpTrustedTime(  892): currentTimeMillis() cache hit
,D/NtpTrustedTime(  892): currentTimeMillis() cache hit
D/NtpTrustedTime(  892): currentTimeMillis() cache hit
D/NtpTrustedTime(  892): currentTimeMillis() cache hit
D/NtpTrustedTime(  892): currentTimeMillis() cache hit
,V/NetworkStats(  892): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  892): currentTimeMillis() cache hit
,E/Auth.Api.Credentials( 1981): [CredentialSyncAdapter] Unknown sync event.
,I/System.out( 3995): Thread-600(ApacheHTTPLog):isShipBuild true
,I/System.out( 3995): Thread-600(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/WifiStateMachine(  892): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/WifiStateMachine(  892): updateConfiguredNetworkExpiration - currTime: 1456908871401
D/WifiStateMachine(  892): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_SET
,D/StatusBar-DoNotDistrub( 1168): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 1168): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DowntimeConditions(  892): android.intent.action.TIME_SET ignored because schedule turned off.
,D/accuweather( 2092): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 2092): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
D/accuweather( 2092): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 2092): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
W/Settings(  892): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/accuweather( 2092): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar-DoNotDistrub( 1168): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,V/AudioPolicyManager(  292): getOutputsForDevice device 0002 -> 0002
,I/qtaguid ( 1685): Tagging socket 54 with tag 120300000000{4611,0} uid -1, pid: 1685, getuid(): 10012
I/AudioService(  892): getStreamVolume 5 index 110
,D/StatusBar-DoNotDistrub( 1168): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService(  892): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,D/accuweather( 2092): [KK AccuPhone]>>> SM:679 [0:0] [sCCTZ] set default tZ
D/accuweather( 2092): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
I/DIAGMON_AGENT( 6898): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DrmEventService(  892):  no response from SecureClock 
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/DIAGMON_AGENT( 6898): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/art     ( 1685): Explicit concurrent mark sweep GC freed 22938(1375KB) AllocSpace objects, 5(275KB) LOS objects, 40% free, 18MB/30MB, paused 688us total 63.448ms
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SurfaceWidget.Renderer( 2092): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2092): [237392/6] SurfaceWidget drawing first frame
D/SurfaceWidget.Renderer( 2092): [237392/6] SurfaceWidget drawing first frame
D/SurfaceWidget.Renderer( 2092): [237392/6] SurfaceWidget drawing first frame
I/qtaguid ( 1685): Tagging socket 57 with tag 120300000000{4611,0} uid -1, pid: 1685, getuid(): 10012
,D/DelayedSyncController( 6850): Delaying sync.
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/DriveInitializer( 1981): Background init thread started
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  892): Killing 5029:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): bgCount ##41
,W/DriveInitializer( 1981): Awaiting to be initialized
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/qtaguid ( 3995): Tagging socket 26 with tag ff44265f00000000{4282656351,0} uid -1, pid: 3995, getuid(): 10185
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 1981): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  892): failed to open /acct/uid_10158/pid_5029/cgroup.procs: No such file or directory
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/DriveInitializer( 1981): Background init thread ended
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 6898): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,I/DIAGMON_AGENT( 6898): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/DIAGMON_AGENT( 6898): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6898): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,E/HttpOperation( 5774): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5774): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5774): 	at kfv.a(PG:65)
E/HttpOperation( 5774): 	at kff.u(PG:385)
E/HttpOperation( 5774): 	at kfb.a(PG:29)
E/HttpOperation( 5774): 	at kff.l(PG:132)
E/HttpOperation( 5774): 	at dsf.a(PG:807)
E/HttpOperation( 5774): 	at fhk.a(PG:1126)
E/HttpOperation( 5774): 	at fhk.a(PG:908)
E/HttpOperation( 5774): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5774): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5774): 	at ihi.a(PG:22)
E/HttpOperation( 5774): 	at kft.a(PG:91)
E/HttpOperation( 5774): 	at kfv.a(PG:62)
E/HttpOperation( 5774): 	... 8 more
E/HttpOperation( 5774): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5774): 	at gde.c(Unknown Source)
E/HttpOperation( 5774): 	at gde.b(Unknown Source)
E/HttpOperation( 5774): 	at ihi.a(PG:19)
E/HttpOperation( 5774): 	... 10 more
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6936): MountEmulatedStorage()
,E/Zygote  ( 6936): v2
I/libpersona( 6936): KNOX_SDCARD checking this for 10082
I/libpersona( 6936): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6936 uid=10082 gids={50082, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6936): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6936): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6936): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6946): MountEmulatedStorage()
E/Zygote  ( 6946): v2
I/libpersona( 6946): KNOX_SDCARD checking this for 10011
I/libpersona( 6946): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=6946 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6946): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6936): TimaSignature is unavailable
,D/ActivityThread( 6936): Added TimaKeyStore provider
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 6936): creating new AssetManager and set to /system/app/Books/Books.apk
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 6946): TimaSignature is unavailable
,I/PhenotypeFlagCommitter( 1685): Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,D/ActivityThread( 6946): Added TimaKeyStore provider
,E/Ads     ( 1981): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/qtaguid ( 3995): Untagging socket 26
,I/System.out( 3995): Thread-600 calls detatch()
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6946): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1685): Vacuum at: now=1456908871962 tag=VacuumService
,I/ActivityManager(  892): Killing 5852:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,I/FOTA_Client( 6946): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ReaderUtils( 6936): PortraitW 1080 LandscapeW 1920 SmallestSize 1005 LargestSize 1920 textZoom 3.3749998 isTablet false Memory 128
,I/FOTA_Client( 6946): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/FOTA_Client( 6946): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 6946): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/FOTA_Client( 6946): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/HttpOperation( 5774): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5774): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5774): 	at kfv.a(PG:65)
E/HttpOperation( 5774): 	at kff.u(PG:385)
E/HttpOperation( 5774): 	at kfb.a(PG:29)
E/HttpOperation( 5774): 	at kff.l(PG:132)
E/HttpOperation( 5774): 	at ieo.a(PG:43)
E/HttpOperation( 5774): 	at iep.a(PG:93)
E/HttpOperation( 5774): 	at fhn.a(PG:59)
E/HttpOperation( 5774): 	at lex.a(PG:85)
E/HttpOperation( 5774): 	at lex.b(PG:132)
E/HttpOperation( 5774): 	at fhk.a(PG:1146)
E/HttpOperation( 5774): 	at fhk.a(PG:908)
E/HttpOperation( 5774): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5774): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5774): 	at ihi.a(PG:22)
E/HttpOperation( 5774): 	at kft.a(PG:91)
E/HttpOperation( 5774): 	at kfv.a(PG:62)
E/HttpOperation( 5774): 	... 12 more
E/HttpOperation( 5774): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5774): 	at gde.c(Unknown Source)
E/HttpOperation( 5774): 	at gde.b(Unknown Source)
E/HttpOperation( 5774): 	at ihi.a(PG:19)
E/HttpOperation( 5774): 	... 14 more
,E/ExperimentLoader( 5774): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5774): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5774): 	at kfv.a(PG:65)
E/ExperimentLoader( 5774): 	at kff.u(PG:385)
E/ExperimentLoader( 5774): 	at kfb.a(PG:29)
E/ExperimentLoader( 5774): 	at kff.l(PG:132)
E/ExperimentLoader( 5774): 	at ieo.a(PG:43)
E/ExperimentLoader( 5774): 	at iep.a(PG:93)
E/ExperimentLoader( 5774): 	at fhn.a(PG:59)
E/ExperimentLoader( 5774): 	at lex.a(PG:85)
E/ExperimentLoader( 5774): 	at lex.b(PG:132)
E/ExperimentLoader( 5774): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5774): 	at fhk.a(PG:908)
E/ExperimentLoader( 5774): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5774): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5774): 	at ihi.a(PG:22)
E/ExperimentLoader( 5774): 	at kft.a(PG:91)
E/ExperimentLoader( 5774): 	at kfv.a(PG:62)
E/ExperimentLoader( 5774): 	... 12 more
E/ExperimentLoader( 5774): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5774): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5774): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5774): 	at ihi.a(PG:19)
E/ExperimentLoader( 5774): 	... 14 more
,E/Zygote  ( 6972): MountEmulatedStorage()
,E/Zygote  ( 6972): v2
I/libpersona( 6972): KNOX_SDCARD checking this for 10019
I/libpersona( 6972): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6972 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 4195:com.google.android.talk/u0a117 (adj 15): bgCount ##41
,W/libprocessgroup(  892): failed to open /acct/uid_10012/pid_5852/cgroup.procs: No such file or directory
,I/SELinux ( 6972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6972): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GAV2    ( 6936): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 6972): TimaSignature is unavailable
,D/ActivityThread( 6972): Added TimaKeyStore provider
,D/ResourcesManager( 6972): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/libprocessgroup(  892): failed to open /acct/uid_10117/pid_4195/cgroup.procs: No such file or directory
,I/BooksApp( 6936): Created application version: 3.3.11 (30311)
,I/jxcore-log( 6210): My device name is: samsung-SM-G900F
I/jxcore-log( 6210): 
,I/KLMS-2.4.503: ( 6972): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 6972): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1456908872159
,I/KLMS-2.4.503: ( 6972): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 6972): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/KLMS-2.4.503: ( 6972): StateImplV2(): networkChangeListener().START
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/KLMS-2.4.503: ( 6972): NetworkChangeOperations(): uploadRequestLog().START 
,D/ResourcesManager( 1981): creating new AssetManager and set to /system/app/Books/Books.apk
,I/BooksSync( 6936): Starting books sync, d
,I/KLMS-2.4.503: ( 6972): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  892): Killing 6023:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/Zygote  ( 6994): MountEmulatedStorage()
E/Zygote  ( 6994): v2
I/libpersona( 6994): KNOX_SDCARD checking this for 10037
I/libpersona( 6994): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6994 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6994): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6994): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6994): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/HttpOperation( 5774): [getaccountstatus] Unexpected exception
E/HttpOperation( 5774): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5774): 	at kfv.a(PG:65)
E/HttpOperation( 5774): 	at kff.u(PG:385)
E/HttpOperation( 5774): 	at kfb.a(PG:29)
E/HttpOperation( 5774): 	at ixd.a(PG:248)
E/HttpOperation( 5774): 	at ixd.b(PG:206)
E/HttpOperation( 5774): 	at ixd.a(PG:175)
E/HttpOperation( 5774): 	at fig.a(PG:78)
E/HttpOperation( 5774): 	at lex.a(PG:85)
E/HttpOperation( 5774): 	at lex.b(PG:132)
E/HttpOperation( 5774): 	at fhk.a(PG:1146)
E/HttpOperation( 5774): 	at fhk.a(PG:908)
E/HttpOperation( 5774): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5774): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5774): 	at ihi.a(PG:22)
E/HttpOperation( 5774): 	at kft.a(PG:91)
E/HttpOperation( 5774): 	at kfv.a(PG:62)
E/HttpOperation( 5774): 	... 12 more
E/HttpOperation( 5774): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5774): 	at gde.c(Unknown Source)
E/HttpOperation( 5774): 	at gde.b(Unknown Source)
E/HttpOperation( 5774): 	at ihi.a(PG:19)
E/HttpOperation( 5774): 	... 14 more
,E/EsSyncAdapterService( 5774): Sync failure
E/EsSyncAdapterService( 5774): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5774): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5774): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5774): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5774): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5774): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5774): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5774): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5774): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5774): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5774): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5774): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5774): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5774): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5774): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5774): 	... 10 more
E/EsSyncAdapterService( 5774): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5774): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5774): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5774): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5774): 	... 12 more
E/EsSyncAdapterService( 5774): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5774): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5774): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5774): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5774): 	... 14 more
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,D/TimaKeyStoreProvider( 6994): TimaSignature is unavailable
,D/ActivityThread( 6994): Added TimaKeyStore provider
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6994): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,W/libprocessgroup(  892): failed to open /acct/uid_10015/pid_6023/cgroup.procs: No such file or directory
,D/SyncManager(  892): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 18247, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,I/ActivityManager(  892): Killing 6040:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,I/SO_AGENT( 6994): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  892): failed to open /acct/uid_10016/pid_6040/cgroup.procs: No such file or directory
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 4920): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 6936): (284) automatic index on view_volumes(volume_id)
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PicasaService( 5244): start picasa sync
,D/PicasaService( 5244): end picasa sync
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  892): Explicit concurrent mark sweep GC freed 91345(4MB) AllocSpace objects, 11(371KB) LOS objects, 30% free, 36MB/52MB, paused 1.493ms total 96.233ms
,D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  892): mCursor = null
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6097): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6097): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 6097): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6097): [SLFUCHKMGR] constructor called
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6097): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6097): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6097): [SCU] == networkStateCheck == true
I/SA      ( 6097): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6097): isChinaCountryCode : false
I/SA      ( 6097): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6097): [OR] == networkStateCheck true ==
,I/SA      ( 6097): [OR] GetMyCountryZoneTask
,I/SA      ( 6097): [OR] onReceive END
,I/ActivityManager(  892): Killing 5673:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,I/SA      ( 6097): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,I/SA      ( 6097): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6097): [SSP] query invoked
,I/SA      ( 6097): [TPMU] GetMccFromDB : null
,E/Zygote  ( 7026): MountEmulatedStorage()
,E/Zygote  ( 7026): v2
I/libpersona( 7026): KNOX_SDCARD checking this for 10071
I/libpersona( 7026): KNOX_SDCARD not a persona
,I/SA      ( 6097): [SCU] getMccFromPreferece mcc = 260
,I/ActivityManager(  892): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7026 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
I/SA      ( 6097): [TPM] isNoProxy(default) : true
,I/art     (  311): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 320us total 11.007ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 254us total 8.210ms
,E/File    ( 6097): fail readDirectory() errno=2
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 246us total 7.750ms
,I/SELinux ( 7026): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7026): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7026): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  892): failed to open /acct/uid_10034/pid_5673/cgroup.procs: No such file or directory
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 7026): TimaSignature is unavailable
,D/ActivityThread( 7026): Added TimaKeyStore provider
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 7026): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7026): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7026): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7026): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
E/SMD     (  287): DCD ON
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6936): Authentication error
E/BooksAccountManager( 6936): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6936): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 6936): null auth token
,I/System.out( 6936): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6936): (HTTPLog)-Static: isShipBuild true
I/System.out( 6936): (HTTPLog)-Thread-1097-329341367: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/comsamsunglog( 7026): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7026): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7026): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
,D/comsamsunglog( 7026): [KK AccuPhone]>>> ==============================================================================================
,I/qtaguid ( 6936): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 6936, getuid(): 10082
,D/comsamsunglog( 7026): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7026): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7026): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7026): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  892): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 10071
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7026): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7026): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7026): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7026): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7026): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7026): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7026): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7026): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7026): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7026): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7045): MountEmulatedStorage()
I/libpersona( 7045): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7045): v2
I/libpersona( 7045): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7045 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 4411:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,I/SELinux ( 7045): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7045): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7045): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1685): (10) POSIX Error : 11 SQLite Error : 3850
,D/TimaKeyStoreProvider( 7045): TimaSignature is unavailable
,D/ActivityThread( 7045): Added TimaKeyStore provider
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  892): failed to open /acct/uid_10035/pid_4411/cgroup.procs: No such file or directory
,D/ResourcesManager( 7045): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7045): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DelayedSyncController( 6850): Delaying sync.
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KnoxUsageLogPro( 7045): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7045): premStatus:2
,I/KnoxUsageLogPro( 7045): isEulaShown : false
,I/KnoxUsageLogPro( 7045): KnoxUsageReceiver onReceive : not Processible, just return
,I/ActivityManager(  892): Killing 5288:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,D/Headlines( 6401): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 6401): getCountryCode(): countryCode = DE
,D/Headlines( 6401): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 6401): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 6401): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 6401): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 6401): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 6401): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 6401): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7062): MountEmulatedStorage()
I/libpersona( 7062): KNOX_SDCARD checking this for 10114
E/Zygote  ( 7062): v2
I/libpersona( 7062): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=7062 uid=10114 gids={50114, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7068): MountEmulatedStorage()
E/Zygote  ( 7068): v2
I/libpersona( 7068): KNOX_SDCARD checking this for 10128
I/libpersona( 7068): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7068 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7062): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7062): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7062): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/qtaguid ( 6936): Untagging socket 34
I/SELinux ( 7068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/TimaKeyStoreProvider( 7062): TimaSignature is unavailable
I/SELinux ( 7068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ActivityThread( 7062): Added TimaKeyStore provider
E/SELinux ( 7068): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  892): failed to open /acct/uid_10042/pid_5288/cgroup.procs: No such file or directory
,W/ApiaryClient( 6936): Error response from books API: {
W/ApiaryClient( 6936):  "error": {
W/ApiaryClient( 6936):   "errors": [
W/ApiaryClient( 6936):    {
W/ApiaryClient( 6936):     "domain": "global",
W/ApiaryClient( 6936):     "reason": "required",
W/ApiaryClient( 6936):     "message": "Login Required",
W/ApiaryClient( 6936):     "locationType": "header",
W/ApiaryClient( 6936):     "location": "Authorization"
W/ApiaryClient( 6936):    }
W/ApiaryClient( 6936):   ],
W/ApiaryClient( 6936):   "code": 401,
W/ApiaryClient( 6936):   "message": "Login Required"
W/ApiaryClient( 6936):  }
W/ApiaryClient( 6936): }
,W/ApiaryClient( 6936): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6936): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7532787961161565543&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6936): Headers suppressed
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7062): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/TimaKeyStoreProvider( 7068): TimaSignature is unavailable
,D/ActivityThread( 7068): Added TimaKeyStore provider
,D/ResourcesManager( 7068): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/ActivityManager(  892): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread( 7062): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager(  892): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7062): getAccountsCursor
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 7062): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  892): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  892): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  892): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  892): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7062): Error finding the version of the Email provider.....
E/Gmail   ( 7062): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7062): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:135)
E/Gmail   ( 7062): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 7062): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 7062): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7062): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7062): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 7062): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 7062): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7062): getAccountsCursor
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  892): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7062): Observing account changes for notifications
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Gmail   ( 7062): Sync started for account: account:61035162
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7068): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7068): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7068): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7068): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/SQLiteLog( 7062): (283) recovered 758 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/ResourcesManager( 1981): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 7062): fail readDirectory() errno=2
,I/Gmail   ( 7062): notifyAccountChanged
,I/WifiStateMachine(  892): REQUEST_POWER_SAVE_ON
,I/Gmail   ( 7062): notifyAccountChanged
,I/Gmail   ( 7062): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,E/WifiStateMachine(  892): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/Gmail   ( 7062): getAccountsCursor
,I/Gmail   ( 7062): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/WebViewFactory( 7068): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7068): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/LibraryLoader( 7068): Loading: webviewchromium
,I/Gmail   ( 7062): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7062): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/LibraryLoader( 7068): Time to load native libraries: 6 ms (timestamps 7537-7543)
I/LibraryLoader( 7068): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7068): Binding Chromium to main looper Looper (main, tid 1) {29d623d5}
,I/LibraryLoader( 7068): Expected native library version number "",actual native library version number ""
,I/chromium( 7068): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7068): Initializing chromium process, renderers=0
,W/art     ( 7068): Attempt to remove local handle scope entry from IRT, ignoring
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Gmail   ( 7062): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5345, normalSync: true
,I/Gmail   ( 7062): getAccountsCursor
,W/AudioManagerAndroid( 7068): Requires BLUETOOTH permission
,W/chromium( 7068): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7068): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7068): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/art     ( 1685): Explicit concurrent mark sweep GC freed 36997(2013KB) AllocSpace objects, 14(993KB) LOS objects, 40% free, 18MB/30MB, paused 3.994ms total 31.833ms
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Adreno-EGL( 7068): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7068): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7068): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7068): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7068): Remote Branch: 
I/Adreno-EGL( 7068): Local Patches: 
I/Adreno-EGL( 7068): Reconstruct Branch: 
,I/SurfaceFlinger(  249): id=14 Removed Toast (8/9)
,I/SurfaceFlinger(  249): id=14 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PowerManagerService(  892): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 892) eventTime = 77686
,D/PowerManagerService(  892): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=892 (0x0)
,D/PowerManagerService(  892): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=892, ws=WorkSource{10059}) (elapsedTime=3471)
,I/NSApplication( 7068): Starting up...
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OpenGLRenderer( 3453): Render dirty regions requested: true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PowerManagerService(  892): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=892
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Adreno-EGL( 3453): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3453): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 3453): Build Date: 03/03/15 Tue
I/Adreno-EGL( 3453): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 3453): Remote Branch: 
I/Adreno-EGL( 3453): Local Patches: 
I/Adreno-EGL( 3453): Reconstruct Branch: 
,I/OpenGLRenderer( 3453): Initialized EGL, version 1.4
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/OpenGLRenderer( 3453): HWUI protection enabled for context ,  &this =0xaec22088 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 3453): Enabling debug mode 0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7158): MountEmulatedStorage()
I/libpersona( 7158): KNOX_SDCARD checking this for 10138
E/Zygote  ( 7158): v2
I/libpersona( 7158): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7158 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5101:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 6758): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 6758): wlan0: sendmsg: Cannot assign requested address
,I/SA      ( 6097): [RC New] Execute method=[GET] start
,I/SELinux ( 7158): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7158): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7158): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CountryDetector(  892): No listener is left
,D/ResourcesManager( 7062): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/TimaKeyStoreProvider( 7158): TimaSignature is unavailable
,W/ResourcesManager( 7062): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/ActivityThread( 7158): Added TimaKeyStore provider
W/ResourcesManager( 7062): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ResourcesManager( 7158): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7158): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7158): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7158): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/SA      ( 6097): [RC New] Security=[true]
,W/libprocessgroup(  892): failed to open /acct/uid_10050/pid_5101/cgroup.procs: No such file or directory
,I/System.out( 6097): Thread-955(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6097): Thread-955(ApacheHTTPLog):isShipBuild true
,I/System.out( 6097): Thread-955(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,V/JNIHelp ( 7062): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/QuickConnect( 7158): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7158): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/art     (  892): Explicit concurrent mark sweep GC freed 30744(1557KB) AllocSpace objects, 4(129KB) LOS objects, 30% free, 36MB/52MB, paused 1.737ms total 94.527ms
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/QuickConnect( 7158): PeriphStartReceiver.onReceive - no need to start
,V/AlarmManager(  892): waitForAlarm result :4
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/RCPManagerService(  892): exchangeData() failure , invalid userId
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/ActivityThread( 7062): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7062): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b83e2fa: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7062): Installed default security provider GmsCore_OpenSSL
,D/RCPManagerService(  892): exchangeData() failure , invalid userId
,I/PowerManagerService(  892): [PWL] Off : 30s ago
,I/PowerManagerService(  892): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  892): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  892): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1981, ws=null) (elapsedTime=44991)
,I/PowerManagerService(  892): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=892, ws=WorkSource{10082}) (elapsedTime=2311)
I/PowerManagerService(  892): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/gmail-ls/com.google/eM_ADDR' (uid=1000, pid=892, ws=WorkSource{10114}) (elapsedTime=1090)
I/PowerManagerService(  892): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=892, ws=WorkSource{10012}) (elapsedTime=30)
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6503): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6503): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6503): StateMachine : Current State = 1
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6503): StateMachine : Changed Current State = 1
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/com.peel.receiver.ConnectivityActionReceiver( 6573): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
D/com.peel.receiver.ConnectivityActionReceiver( 6573): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
D/com.peel.receiver.ConnectivityActionReceiver( 6573):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
D/com.peel.receiver.ConnectivityActionReceiver( 6573): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
D/com.peel.receiver.ConnectivityActionReceiver( 6573): 
D/com.peel.receiver.ConnectivityActionReceiver( 6573): last run: 1456908867971 -- System.currentTimeMillis()-last_run: 6095
D/com.peel.receiver.ConnectivityActionReceiver( 6573): ... skip 
,D/com.peel.util.b.a( 6573): url after encodeURL: https://devices.peel.com/registerdevice
,D/com.peel.util.b.a( 6573): ######## url: https://devices.peel.com/registerdevice
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Zygote  ( 7179): MountEmulatedStorage()
E/Zygote  ( 7179): v2
I/libpersona( 7179): KNOX_SDCARD checking this for 10178
I/libpersona( 7179): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7179 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 6117:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7179): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRM:m  (  892): SIOP:: AP = 430, PST = 431, CUR = 300
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/app/Books/Books.apk
,D/TimaKeyStoreProvider( 7179): TimaSignature is unavailable
,D/ActivityThread( 7179): Added TimaKeyStore provider
V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/ResourcesManager( 7179): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 6936): Authentication error
E/BooksAccountManager( 6936): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6936): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 6936): null auth token
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/libprocessgroup(  892): failed to open /acct/uid_10051/pid_6117/cgroup.procs: No such file or directory
,I/qtaguid ( 6936): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 6936, getuid(): 10082
,I/qtaguid ( 6936): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 6936, getuid(): 10082
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/ActivityManager(  892): Killing 6138:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_mail.png
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  892): failed to open /acct/uid_10058/pid_6138/cgroup.procs: No such file or directory
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/qtaguid ( 6936): Untagging socket 34
,W/ApiaryClient( 6936): Error response from books API: {
W/ApiaryClient( 6936):  "error": {
W/ApiaryClient( 6936):   "errors": [
W/ApiaryClient( 6936):    {
W/ApiaryClient( 6936):     "domain": "global",
W/ApiaryClient( 6936):     "reason": "required",
W/ApiaryClient( 6936):     "message": "Login Required",
W/ApiaryClient( 6936):     "locationType": "header",
W/ApiaryClient( 6936):     "location": "Authorization"
W/ApiaryClient( 6936):    }
W/ApiaryClient( 6936):   ],
W/ApiaryClient( 6936):   "code": 401,
W/ApiaryClient( 6936):   "message": "Login Required"
W/ApiaryClient( 6936):  }
W/ApiaryClient( 6936): }
W/ApiaryClient( 6936): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6936): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7532787961161565543&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6936): Headers suppressed
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/iu.SyncManager( 1981): SYNC; picasa accounts
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,I/GcmGroups( 1981): Failed to subscribe to group.
I/GcmGroups( 1981): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 1981): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 1981): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 1981): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 1981): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 1981): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 1981): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 1981): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 1981): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 1981): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 1981): 	at android.os.Looper.loop(Looper.java:145)
I/GcmGroups( 1981): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetworkLogImpl( 1981): Loaded NetworkSpeedPredictor
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.Environment( 1981): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/GcmGroups( 1981): Groups upload failed, retrying in 24000:00:00
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.UploadsManager( 1981): num queued entries: 0
,I/Gmail   ( 7062): notifyAccountChanged
,I/iu.UploadsManager( 1981): num updated entries: 0
,D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Gmail   ( 7062): getAccountsCursor
,I/Kids    ( 1981): [GCoreUtils] Current gmscore version, 7899438 is smaller than the required version 8400000
,I/iu.SyncManager( 1981): NEXT; no task
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  892): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  892): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
D/ConnectivityService(  892): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  892): identical MTU - not setting
D/ConnectivityService(  892): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  892): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  281): QcRouteController
E/WifiStateMachine(  892): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/WaitQueueForNetworkActivate( 6487): notifyNetworkActivated
,D/SmartBondingService(  892): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  892): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  892): getSBEnabled() enabled =false
D/SmartBondingService(  892): getSBEnabled() enabled =false
D/SmartBondingService(  892): getSBEnabled() enabled =false
,V/        (  281): QcRouteController
,W/NetworkManagementService(  892): route cmd failed: 
W/NetworkManagementService(  892): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '52 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 52 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  892): '
W/NetworkManagementService(  892): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  892): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  892): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  892): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  892): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  892): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  892): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  892): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  892): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  892): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  892): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  892): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  892): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  892): calling update connectivity
D/ConnectivityService(  892):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  892):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  892): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  892): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  892): calling update connectivity
D/ConnectivityService(  892):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  892):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524295
,D/ConnectivityService(  892): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524295
,I/Gmail   ( 7062): notifyAccountChanged
,I/Gmail   ( 7062): getAccountsCursor
,W/Gmail   ( 7062): Sync complete for account: account:61035162
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 6487): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  892): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/SyncManager(  892): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 18324, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  892): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 108983, reason: Periodic
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  892): mCursor = null
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.util.b.a( 6573): 
D/com.peel.util.b.a( 6573): posting key: epgCountry -- value: unknown
D/com.peel.util.b.a( 6573): 
D/com.peel.util.b.a( 6573): posting key: deviceOem -- value: samsung
D/com.peel.util.b.a( 6573): 
D/com.peel.util.b.a( 6573): posting key: appVersion -- value: 
D/com.peel.util.b.a( 6573): 
D/com.peel.util.b.a( 6573): posting key: androidID -- value: 5f449385fa0cc9d3
D/com.peel.util.b.a( 6573): 
D/com.peel.util.b.a( 6573): posting key: deviceType -- value: Handset
D/com.peel.util.b.a( 6573): 
D/com.peel.util.b.a( 6573): posting key: deviceModel -- value: SM-G900F
D/com.peel.util.b.a( 6573): 
D/com.peel.util.b.a( 6573): posting key: deviceCountry -- value: Germany
D/com.peel.util.b.a( 6573): 
D/com.peel.util.b.a( 6573): posting key: timezone -- value: GMT+02:00
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/app_icon.png
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
,D/GCM     ( 1685): Connected
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
D/ContactsSyncAdapter( 1685): innerSync failed
D/ContactsSyncAdapter( 1685): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1685): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 1685): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1685): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1685): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1685): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1685): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1685): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
D/ContactsSyncAdapter( 1685): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1685): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
D/ContactsSyncAdapter( 1685): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1685): Message class com.google.f.a.a.p
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 6487): AutoUpdateManager:IDLE:execute
,D/SyncManager(  892): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 18324, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
I/FOTA_Client( 6946): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/SyncManager(  892): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 109468, reason: Periodic
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/InitializeManagerStateMachine( 6487): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6487): exit::IDLE
D/InitializeManagerStateMachine( 6487): entry::NETWORK_CHECK
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 6487): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6487): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6487): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6487): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6487): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6487): entry::SUCCESS
D/hcjo    ( 6487): AutoUpdateManager:INITCHECK:onInitializeSuccess
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/com.peel.util.b.a( 6573):  ############# POST RESPONSE ################ (200)
D/com.peel.util.b.a( 6573): 
D/com.peel.util.b.a( 6573): {response:"success"}
D/com.peel.util.b.a( 6573): 
,D/com.peel.receiver.ConnectivityActionReceiver( 6573): true -- {response:"success"} -- null
D/com.peel.util.i( 6573): NON-UI THREAD OnComplete (0ms)
,E/Zygote  ( 7212): MountEmulatedStorage()
E/Zygote  ( 7212): v2
I/libpersona( 7212): KNOX_SDCARD checking this for 10115
I/libpersona( 7212): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=7212 uid=10115 gids={50115, 9997, 3003} abi=armeabi-v7a
,D/hcjo    ( 6487): AutoUpdateTriggerManager:IDLE:setInterval:345600000
I/SA      ( 6097): [RC New] [v2liruge] api execute + 917
I/SA      ( 6097): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6097): AsyncTask #1 calls detatch()
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6097): [ODM] saveOpenData( GEO_IP, PL )
,I/SELinux ( 7212): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7212): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7212): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/hcjo    ( 6487): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6487): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/KLMS-2.4.503: ( 6972): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 6972): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1456908874908
,D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  892): mCursor = null
,I/KLMS-2.4.503: ( 6972): MainReciver(): TIME_CHANGED
,D/InitializeManagerStateMachine( 6487): exit::SUCCESS
,D/InitializeManagerStateMachine( 6487): entry::IDLE
E/com.peel.util.i( 6573): com.peel.util.i
E/com.peel.util.i( 6573): android.content.ReceiverCallNotAllowedException: BroadcastReceiver components are not allowed to bind to services
E/com.peel.util.i( 6573): 	at android.app.ReceiverRestrictedContext.bindService(ContextImpl.java:277)
E/com.peel.util.i( 6573): 	at com.google.android.gms.ads.identifier.AdvertisingIdClient.b(Unknown Source)
E/com.peel.util.i( 6573): 	at com.google.android.gms.ads.identifier.AdvertisingIdClient.a(Unknown Source)
E/com.peel.util.i( 6573): 	at com.peel.util.bx.i(Unknown Source)
E/com.peel.util.i( 6573): 	at com.peel.receiver.a.run(Unknown Source)
E/com.peel.util.i( 6573): 	at com.peel.util.j.run(Unknown Source)
E/com.peel.util.i( 6573): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/com.peel.util.i( 6573): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/com.peel.util.i( 6573): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/com.peel.util.i( 6573): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/com.peel.util.i( 6573): 	at java.lang.Thread.run(Thread.java:818)
D/com.peel.util.i( 6573): BGND THREAD bg report... (847ms)
,I/SA      ( 6097): [OCP] update openData : PL
,I/KLMS-2.4.503: ( 6972): StateImplV2(): dateTimeChanged().START : Wed Mar 02 09:54:34 GMT+01:00 2016
,D/TimaKeyStoreProvider( 7212): TimaSignature is unavailable
,D/ActivityThread( 7212): Added TimaKeyStore provider
,I/KLMS-2.4.503: ( 6972): StateImplV2(): dateTimeChanged().END
,I/SA      ( 6097): [TPMU] getNetworkMcc : 
,I/SA      ( 6097): [SCU] saveMccToPreferece Start
I/SA      ( 6097): [SCU] RegionMCC : 260
I/SA      ( 6097): [SSP] query invoked
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
I/SA      ( 6097): [TPMU] GetMccFromDB : null
I/SA      ( 6097): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6097): [SCU] saveMccToPreferece End
,I/SA      ( 6097): [RC New] executeRequest [v2liruge] end. 1078
D/ResourcesManager( 7212): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
I/SA      ( 6097): [RC New] Execute end
I/SA      ( 6097): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6097): [OR] GetMyCountryZoneTask Success
,E/Zygote  ( 7227): MountEmulatedStorage()
E/Zygote  ( 7227): v2
I/libpersona( 7227): KNOX_SDCARD checking this for 10035
I/libpersona( 7227): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/com.cigna.mobile.coach.CoachBroadcastReceiver: pid=7227 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5460:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7227): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7227): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7227): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7227): TimaSignature is unavailable
,D/ActivityThread( 7227): Added TimaKeyStore provider
,W/AbstractGoogleClient( 7212): Application name is not set. Call Builder#setApplicationName.
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7227): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7243): MountEmulatedStorage()
I/libpersona( 7243): KNOX_SDCARD checking this for 10046
E/Zygote  ( 7243): v2
I/libpersona( 7243): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7243 uid=10046 gids={50046, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_5460/cgroup.procs: No such file or directory
,I/SELinux ( 7243): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7243): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7243): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7243): TimaSignature is unavailable
,D/ActivityThread( 7243): Added TimaKeyStore provider
,D/ResourcesManager( 7243): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 7243): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/CalendarProvider2( 7243): CalendarProvider2.onCreate() called
,D/btif_config_util( 6543): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): checkState()
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7265): MountEmulatedStorage()
E/Zygote  ( 7265): v2
I/libpersona( 7265): KNOX_SDCARD checking this for 10017
I/libpersona( 7265): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=7265 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/SELinux ( 7265): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7265): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7265): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7265): TimaSignature is unavailable
,D/ActivityThread( 7265): Added TimaKeyStore provider
,D/ResourcesManager( 7265): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6936): Authentication error
E/BooksAccountManager( 6936): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6936): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 6936): null auth token
,D/BluetoothManager( 7227): getConnectedDevices
,I/qtaguid ( 6936): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 6936, getuid(): 10082
,D/-----SIC-----( 7227): ------------------skip uv
,D/-----SIC-----( 7227): ------------------skip SPO2
,D/-----SIC-----( 7227): ------------------skip TGH
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SecureStorage( 7265): [INFO]: SPID(0x00000000)Processing data
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7227): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,I/SecureStorage(  335): [INFO]: SPID(0x00000006)Credentials: uid 10017, gid 10017, pid 7265
I/SecureStorage(  335): [INFO]: SPID(0x00000006)Received function mask & code: 0x00000106
,W/ContextImpl( 7227): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,I/SO_AGENT( 6994): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/SA      ( 6097): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/qtaguid ( 6936): Untagging socket 34
,W/ApiaryClient( 6936): Error response from books API: {
W/ApiaryClient( 6936):  "error": {
W/ApiaryClient( 6936):   "errors": [
W/ApiaryClient( 6936):    {
W/ApiaryClient( 6936):     "domain": "global",
W/ApiaryClient( 6936):     "reason": "required",
W/ApiaryClient( 6936):     "message": "Login Required",
W/ApiaryClient( 6936):     "locationType": "header",
W/ApiaryClient( 6936):     "location": "Authorization"
W/ApiaryClient( 6936):    }
W/ApiaryClient( 6936):   ],
W/ApiaryClient( 6936):   "code": 401,
W/ApiaryClient( 6936):   "message": "Login Required"
W/ApiaryClient( 6936):  }
W/ApiaryClient( 6936): }
W/ApiaryClient( 6936): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6936): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7532787961161565543&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6936): Headers suppressed
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/MediaPlayer( 7227): decode(33, 19359868, 4230)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,V/MediaPlayerService(  292): decode(32, 19359868, 4230)
,V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,D/AdaptiveEventManager( 1168): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1168): M updateContainers()
D/AdaptiveEventContainerSmall( 1168): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1168): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1168): pedoEvent == null
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
,V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19359868, 4230)
I/ActivityManager(  892): Killing 6163:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xaf9092e0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
,V/AwesomePlayer(  292): prepareAsync
,V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
,I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
,V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xaf9092e0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
,V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,I/AudioPlayer(  292): First fillBuffer call!!
V/MediaPlayerService(  292): wait for playback complete
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
E/Zygote  ( 7312): MountEmulatedStorage()
I/libpersona( 7312): KNOX_SDCARD checking this for 10050
E/Zygote  ( 7312): v2
I/libpersona( 7312): KNOX_SDCARD not a persona
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,I/ActivityManager(  892): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=7312 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7227): decode(34, 19213040, 15440)
I/ActivityManager(  892): Killing 6264:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,V/MediaPlayerService(  292): decode(32, 19213040, 15440)
,I/SELinux ( 7312): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,I/SELinux ( 7312): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7312): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19213040, 15440)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
D/AdaptiveEventManager( 1168): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1168): M updateContainers()
D/AdaptiveEventContainerSmall( 1168): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1168): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1168): pedoEvent == null
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
,V/StagefrightPlayer(  292): start
,V/AwesomePlayer(  292): play
,V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0b14240, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,D/TimaKeyStoreProvider( 7312): TimaSignature is unavailable
,D/ActivityThread( 7312): Added TimaKeyStore provider
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7227): decode(35, 19257568, 9226)
,V/MediaPlayerService(  292): decode(32, 19257568, 9226)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19257568, 9226)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 200, 973, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 1, 0, 0)
V/AudioCache(  292): prepared
,V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
,I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7227): decode(37, 19364180, 4890)
V/MediaPlayerService(  292): decode(32, 19364180, 4890)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19364180, 4890)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 7312): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
E/SMD     (  287): DCD ON
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
,I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
W/ResourcesManager( 7312): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
W/ResourcesManager( 7312): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/AudioCache(  292): notify(0xaef080b0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
W/ResourcesManager( 7312): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7312): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,W/libprocessgroup(  892): failed to open /acct/uid_10098/pid_6163/cgroup.procs: No such file or directory
,W/libprocessgroup(  892): failed to open /acct/uid_10033/pid_6264/cgroup.procs: No such file or directory
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7227): decode(38, 19290344, 17329)
V/MediaPlayerService(  292): decode(32, 19290344, 17329)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19290344, 17329)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9093d0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/ResourcesManager( 7312): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaf9093d0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9093d0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9093d0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9093d0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/art     (  892): Explicit concurrent mark sweep GC freed 31756(1751KB) AllocSpace objects, 7(437KB) LOS objects, 30% free, 36MB/52MB, paused 1.950ms total 121.251ms
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xaf9093d0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9093d0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9093d0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7227): decode(39, 19190536, 6644)
V/MediaPlayerService(  292): decode(32, 19190536, 6644)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19190536, 6644)
V/AwesomePlayer(  292): reset_l()
E/DatabaseUtils(  892): Writing exception to parcel
E/DatabaseUtils(  892): java.lang.NullPointerException: key == null
E/DatabaseUtils(  892): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  892): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  892): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  892): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  892): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  892): 	at android.os.Binder.execTransact(Binder.java:446)
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef08560, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaef08560, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef08560, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef08560, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef08560, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/MediaPlayerService(  292): wait for playback complete
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/AudioCache(  292): notify(0xaef08560, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xaef08560, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
,V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef08560, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7227): decode(40, 19266876, 23389)
V/MediaPlayerService(  292): decode(32, 19266876, 23389)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19266876, 23389)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
,E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
,V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
,V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
,V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xaf9092e0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
,I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
,V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7227): decode(41, 19156232, 8154)
V/MediaPlayerService(  292): decode(32, 19156232, 8154)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19156232, 8154)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 5, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
,V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0b14240, 6, 0, 0)
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,V/MediaPlayerService(  292): wait for playback complete
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
D/Mms/MmsApp( 7312): [start]    onCreate() consume time = 0.0
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6057): mConnectivityHandler : connected
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
,V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7227): decode(42, 19129712, 4804)
D/Mms/TelephonyPermission( 7312): start operation mode monitor
,V/MediaPlayerService(  292): decode(32, 19129712, 4804)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19129712, 4804)
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
,V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
,I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0954600, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
,V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(1)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0954600, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,V/MediaPlayerService(  292): wait for playback complete
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
,V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,D/ResourcesManager( 7312): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7227): decode(43, 19099164, 9400)
V/MediaPlayerService(  292): decode(32, 19099164, 9400)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19099164, 9400)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/ResourcesManager( 7312): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
V/MediaPlayer( 7227): decode(49, 19172584, 4112)
V/MediaPlayerService(  292): decode(37, 19172584, 4112)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(37, 19172584, 4112)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlaye,r(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9093d0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(39) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4194367, value : -2140176274
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4194367, value : -2140176274
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0,
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaf9093d0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9093d0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9093d0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
W/PCWCLIENTTRACE_AccountUtil( 6057): [hasSamungAccount] - No Samsung Account
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7227): decode(44, 19307764, 52024)
V/MediaPlayerService(  292): decode(32, 19307764, 52024)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19307764, 52024)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef08560, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaef08560, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef08560, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef08560, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9093d0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): First fillBuffer call!!
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(48000, 2, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef08560, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
,V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9093d0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
V/AudioCache(  292): notify(0xaf9093d0, 7, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9093d0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,D/Mms/TelephonyPermission( 7312): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 7312): isDefault true
,D/Mms/MmsApp( 7312): onCreate() com.android.mms
,D/Mms/MmsConfig( 7312): [start]    MmsConfig.init() consume time = 143.605989
,I/CSTORAGE( 6057): ================================================
,I/CSTORAGE( 6057):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6057): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6057): [GetString-S]
,E/art     ( 6057): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 6057): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6057): [GetString-E]
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,I/PCWCLIENTTRACE_PushUtil( 6057): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6057): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6057): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6057): [ensureRegistration] - No Samsung account
,D/Mms/MmsConfig( 7312): before partial update
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef08560, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef08560, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef08560, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
,I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7227): decode(45, 19172584, 4112)
V/MediaPlayerService(  292): decode(32, 19172584, 4112)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19172584, 4112)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
,I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,I/AudioPlayer(  292): First fillBuffer call!!
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
V/MediaPlayerService(  292): wait for playback complete
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
,I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
D/Mms/MmsConfig( 7312): Load Resize quality : 80
V/MediaPlayer( 7227): decode(46, 19235660, 21825)
,V/MediaPlayerService(  292): decode(32, 19235660, 21825)
V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19235660, 21825)
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
,V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0b14240, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
,V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
,V/AwesomePlayer(  292): play
,V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
,E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,V/MediaPlayerService(  292): wait for playback complete
,E/ActivityThread( 7312): Failed to find provider info for com.samsung.android.coreapps.easysignup.public
D/EasySignUpManager( 7312): serviceId : 1, features : -1
D/Mms/MmsConfig( 7312): setFreeMessageEnabled, free message policy(getSupportedFeatures) is = -1
,D/TP/MmsSmsProvider( 1487): query,matched:2117, calling pid = 7312
,D/TP/MmsSmsProvider( 1487): match 2117:Elapsed time : 1.282 ms
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0b14240, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
,V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b14240, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
E/ActivityThread( 7312): Failed to find provider info for com.samsung.android.coreapps.easysignup.public
D/EasySignUpManager( 7312): serviceId : 3, features : -1
,D/Mms/MmsConfig( 7312): Shop agent feature value :-1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
D/Mms/MmsConfig( 7312):  enable multiwindow = true
I/OggExtractor(  292): ~OggSource --
,I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
,I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7227): decode(47, 19134596, 21552)
,V/MediaPlayerService(  292): decode(32, 19134596, 21552)
V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19134596, 21552)
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
E/Mms/MessageUtils( 7312): setCountryDetector : update country detector info 
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
E/Mms/MessageUtils( 7312): updateCountryIso : update country iso info 
I/SecMediaClock(  292): SecMediaClock constructor
,I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  292): notify(0xb0954600, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0954600, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
,V/AwesomePlayer(  292): play
,V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,D/Mms/MmsConfig( 7312): [end]    init() consume time = 118.032865
D/Mms/MmsApp( 7312): [start]    initCountryIso consume time = 0.068229
,D/CountryDetector(  892): The first listener is added
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/Mms/MmsApp( 7312): [end]    initCountryIso consume time = 3.043073
I/AudioPlayer(  292): Audio channels(2)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0954600, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4292761, value : -2137358184
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4292761, value : -2137358184
,D/Mms/Contact( 7312): [start]    init() consume time = 1.701406
V/MediaPlayerService(  292): wait for playback complete
,D/TP/MmsSmsProvider( 1487): query,matched:13, calling pid = 7312
,D/TP/MmsSmsProvider( 1487): match 13:Elapsed time : 2.887 ms
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_list_thumbnail.pkm
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,D/Mms/Contact( 7312): [end]    init consume time = 28.000573
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 2, 0, 0)
,V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0954600, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
,V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0954600, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7227): decode(48, 19228560, 7017)
V/MediaPlayerService(  292): decode(32, 19228560, 7017)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19228560, 7017)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
D/Mms/Conversation( 7312): [start]    init() consume time = 7.499688
,D/TP/MmsSmsProvider( 1487): deleteConversation threadId: 9223372036854775807
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,D/TP/MmsSmsProvider( 1487): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
,I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
E/SQLiteLog( 1487): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1487): (284) automatic index on im_threads(normal_thread_id)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
E/SQLiteLog( 1487): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1487): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1487): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1487): (284) automatic index on im_threads(normal_thread_id)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/ThermalEngine(  306): Sensor:tsens_tz_sensor6:85000 mC
,D/Mms/DraftCache( 7312): [start]    rebuildCache consume time = 9.49849
I/ThermalEngine(  306): Sensor:tsens_tz_sensor6:85000 mC
I/ThermalEngine(  306): TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm raised 1 at 85.0 degC
,I/ThermalEngine(  306): ACTION: OPT_CURR_REQ 1
,D/TP/MmsSmsProvider( 1487): query,matched:12, calling pid = 7312
,I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/TP/MmsSmsProvider( 1487): match 12:Elapsed time : 1.613 ms
,I/ActivityManager(  892): Waited long enough for: ServiceRecord{14bb3808 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 1, 0, 0)
V/AudioCache(  292): prepared
,V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
,V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,D/TP/MmsSmsProvider( 1487): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1487): need read changed broadcast:false
,D/Mms/Conversation( 7312): [end]    init consume time = 9.301198
D/Mms/DraftCache( 7312): [end]    rebuildCache consume time = 0.278854
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioPlayer(  292): Audio channels(2)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaef080b0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xaef080b0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
D/Mms/TelephonyUtils( 7312): getSubId from simSlot 0, return Value = -1
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
,I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
D/Mms/DownloadManager( 7312): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 7312): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 7312): auto download without roaming -> true
D/Mms/DownloadManager( 7312): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,E/Mms/TelephonyUtils( 7312): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 7312): getSubId from simSlot 1, return Value = -1000
D/Mms/DownloadManager( 7312): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 7312): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 7312): auto download without roaming -> true
D/Mms/DownloadManager( 7312): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 7312): auto download during roaming secondary -> false
D/Mms/DownloadManager( 7312): mAutoDownload ------> true
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
D/Mms/MessagingNotification( 7312): [start]    init() consume time = 16.017499
,D/Mms/MessagingNotification( 7312): [end]    init consume time = 1.575522
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/Mms/SpamFilter( 7312): [start]    SpamFilter fill() begin consume time = 1.418541
,D/TP/MmsSmsProvider( 1487): query,matched:400, calling pid = 7312
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/app_icon.png
,D/Mms/SpamFilter( 7312): [end]    SpamFilter fill() finished consume time = 4.694323
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/Mms/ComposeMessageFragment( 7312): [start]    fillCache consume time = 5.742344
,D/Mms/ComposeMessageFragment( 7312): fillCache, easy = false
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/SecureStorage(  335): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  335): [INFO]: SPID(0x00000006)PID: 7265, TID: 7276
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,E/CalendarSyncAdapter( 7212): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 7212): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 7212): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 7212): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 7212): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 7212): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 7212): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 7212): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 7212): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 7212): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 7212): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 7212): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 7212): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 7212): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 7212): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 7212): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 7212): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 7212): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 7212): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 7212): 	... 12 more
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,I/ActivityManager(  892): Killing 6227:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
D/SyncManager(  892): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 18324, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  892): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 111775, reason: Periodic
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  892): mCursor = null
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GoogleURLConnFactory( 1981): Using platform SSLCertificateSocketFactory
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_add.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_contacts.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_contacts.pkm
,W/libprocessgroup(  892): failed to open /acct/uid_10099/pid_6227/cgroup.procs: No such file or directory
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_priority_vzw.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_template_left.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_emotion_off.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_emotion_off.pkm
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_icon_title_recieved_check_msg.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_icon_title_read_check_msg.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_send.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_send.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach_small.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach_small.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_template.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_template.pkm
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ThermalEngine(  306): Sensor:tsens_tz_sensor6:75000 mC
,I/ThermalEngine(  306): Sensor:tsens_tz_sensor6:75000 mC
I/ThermalEngine(  306): TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm cleared 1 at 75.0 degC
,I/ThermalEngine(  306): ACTION: OPT_CURR_REQ 0
V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AbsListView( 7312): Get MotionRecognitionManager
,D/MotionRecognitionService(  892):  ssp status : true
,D/Mms/ComposeMessageFragment( 7312): [end]    fillCache consume time = 164.173645
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_contact_picture.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/sms_msg_bt.pkm
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,W/SubscribedFeeds( 1981): Hard error
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_priority_vzw_2.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_bubble_icon_locked.pkm
,D/SyncManager(  892): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 18324, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  892): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 112591, reason: Periodic
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/progressbar_indeterminate1.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/progressbar_indeterminate2.png
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/progressbar_indeterminate3.png
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_translator_normal.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_press.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_focus.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_disable.pkm
,V/BitmapFactory( 7312): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_normal.pkm
,D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  892): mCursor = null
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1981): Explicit concurrent mark sweep GC freed 15592(1219KB) AllocSpace objects, 20(320KB) LOS objects, 40% free, 19MB/32MB, paused 572us total 30.919ms
,I/SecureStorage( 7265): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 7265): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SecSQLiteOpenHelper( 7227): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper( 7227): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper( 7227): Open platform.db in secure mode
,D/SecSQLiteDatabase( 7227): Android Version: 5.0
D/SecSQLiteDatabase( 7227): Load library secsqlite.so for Android 5.0
,I/SecSQLiteDatabase( 7227): openSecureDatabase...
,I/SecSQLiteDatabase( 7227): private openSecureDatabase...
I/SecSQLiteConnectionPool( 7227): OpenSecure
I/SecSQLiteConnectionPool( 7227): OpenSecure with password
I/SecSQLiteConnectionPool( 7227): openSecureConnectionLocked
,I/SecSQLiteDatabase( 7227): ...private openSecureDatabase
I/SecSQLiteDatabase( 7227): ...openSecureDatabase
,I/ReminderSync( 1981): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=289:priority=5:group=main]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 6936): Soft error
E/BooksSync( 6936): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6936): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7532787961161565543&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6936): Headers suppressed
E/BooksSync( 6936): 
E/BooksSync( 6936): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 6936): Sync error
E/BooksSync( 6936): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6936): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7532787961161565543&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6936): Headers suppressed
E/BooksSync( 6936): 
E/BooksSync( 6936): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 6936): Finished books sync
,I/SecSQLiteOpenHelper( 7227): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper( 7227): ...getDatabaseLocked(b,b,pwd)
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  892): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 18260, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  892): Killing 6318:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,W/System.err( 7227): java.lang.NumberFormatException: Invalid int: "null"
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/System.err( 7227): 	at java.lang.Integer.invalidInt(Integer.java:138)
,W/System.err( 7227): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 7227): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 7227): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
W/System.err( 7227): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
W/System.err( 7227): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 7227): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7227): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7402): MountEmulatedStorage()
I/libpersona( 7402): KNOX_SDCARD checking this for 10181
E/Zygote  ( 7402): v2
I/libpersona( 7402): KNOX_SDCARD not a persona
,I/CalendarProvider2( 7243): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager(  892): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=7402 uid=10181 gids={50181, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  311): Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 285us total 15.879ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 7.690ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.826ms
,I/SELinux ( 7402): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7402): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7402): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  892): Killing 6334:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  892): mCursor = null
,D/TimaKeyStoreProvider( 7402): TimaSignature is unavailable
,D/ActivityThread( 7402): Added TimaKeyStore provider
,D/ResourcesManager( 7402): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/libprocessgroup(  892): failed to open /acct/uid_10003/pid_6318/cgroup.procs: No such file or directory
,D/Mms/BubbleViewCache( 7312): fillCache bubble = 8
,D/Mms/Synchronizer( 7312): [start]    doSync consume time = 332.314479,
D/TP/MmsSmsProvider( 1487): query,matched:0, calling pid = 7312
V/TP/MmsSmsProvider( 1487): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1487): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 1487): syncDBData start
,V/TP/MmsSmsProvider( 1487): syncDBData sms end
,D/TP/MmsSmsProvider( 1487): match 0:Elapsed time : 2.261 ms
V/TP/MmsSmsProvider( 1487): syncDBData mms end
,V/TP/MmsSmsProvider( 1487): syncDBData end
,D/Mms/Synchronizer( 7312): [end]    doSync consume time = 3.685781
,W/ResourcesManager( 7402): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,W/libprocessgroup(  892): failed to open /acct/uid_10020/pid_6334/cgroup.procs: No such file or directory
,D/Mms/MessagingNotification( 7312): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1487): query,matched:26, calling pid = 7312
,D/TP/SmsProvider( 1487): match 26:Elapsed time : 1.170 ms
,D/TP/MmsSmsProvider( 1487): query,matched:6, calling pid = 7312
,D/TP/MmsSmsProvider( 1487): match 6:Elapsed time : 0.880 ms
,I/Mms/ReservationManager( 7312): ReservationManager()
,I/Mms/ReservationManager( 7312): resetAfterConnected()
,D/TP/MmsSmsProvider( 1487): query,matched:7, calling pid = 7312
,D/TP/MmsSmsProvider( 1487): match 7:Elapsed time : 3.845 ms
,I/Mms/ReservationManager( 7312): getReservedSendMessageCount(): retMessageCount=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7419): MountEmulatedStorage()
,E/Zygote  ( 7419): v2
I/libpersona( 7419): KNOX_SDCARD checking this for 10025
I/libpersona( 7419): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7419 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,I/SELinux ( 7419): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7419): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7419): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7419): TimaSignature is unavailable
,D/ActivityThread( 7419): Added TimaKeyStore provider
,D/ResourcesManager( 7419): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
,I/GCoreUlr( 1597): Uploading GCM registration ID for account#2#
,W/ResourcesManager( 7419): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/BaseAppContext( 1597): Using Auth Proxy for data requests.
,I/GLSUser ( 1597): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1597): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Mms/Omacp( 7312): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/Mms/MmsApp( 7312): [end]    onCreate() consume time = 252.613698
,D/Mms/PerformanceUtils( 7312): link cahcing start
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Mms/DownloadManager( 7312): Service state changed: Bundle[mParcelledData.dataSize=692]
,I/ActivityManager(  892): Killing 6371:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,I/ActivityManager(  892): Killing 6349:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##42
D/Mms/DownloadManager( 7312): roaming ------> false, mSimSlot = 0
D/PlayMovies( 7402): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/Mms/TelephonyUtils( 7312): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager( 7312): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 7312): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 7312): auto download without roaming -> true
D/Mms/DownloadManager( 7312): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 7312): mAutoDownload ------> true
,D/PlayMovies( 7402): TransferService.onCreate:52 creating transfer service
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7465): MountEmulatedStorage()
I/libpersona( 7465): KNOX_SDCARD checking this for 10067
E/Zygote  ( 7465): v2
I/libpersona( 7465): KNOX_SDCARD not a persona
,I/PlayMovies( 7402): SyncService$SyncAdapter.onPerformSync:252 Skipping sync for 515013DC511638B0584069811EF28701C0771BF5
,I/ActivityManager(  892): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=7465 uid=10067 gids={50067, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Mms/PerformanceUtils( 7312): link cahcing done
,I/SELinux ( 7465): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7465): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7465): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/AudioCapabilities( 7402): Unsupported mime audio/evrc
,W/AudioCapabilities( 7402): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7402): Unrecognized profile 2130706433 for video/avc
,D/TimaKeyStoreProvider( 7465): TimaSignature is unavailable
,D/ActivityThread( 7465): Added TimaKeyStore provider
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1685): Explicit concurrent mark sweep GC freed 40224(2MB) AllocSpace objects, 21(1571KB) LOS objects, 39% free, 18MB/30MB, paused 588us total 47.752ms
,W/ContextImpl( 7402): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.videos/files/Movies
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7465): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,W/AudioCapabilities( 7402): Unsupported mime audio/mpeg-L1
,D/ResourcesManager( 1981): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/AudioCapabilities( 7402): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 7402): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7402): Unsupported mime audio/x-ima
,W/AudioCapabilities( 7402): Unsupported mime audio/amr-wb-plus
I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,W/AudioCapabilities( 7402): Unsupported mime audio/qcelp
,W/AudioCapabilities( 7402): Unsupported mime audio/evrc
,I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GAV2    ( 6936): Thread[GAThread,5,main]: No campaign data found.
,W/libprocessgroup(  892): failed to open /acct/uid_10112/pid_6371/cgroup.procs: No such file or directory
W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_6349/cgroup.procs: No such file or directory
,D/WVCdm   (  292): Instantiating CDM.
,I/WVCdm   (  292): CdmEngine::QueryStatus
,I/WVCdm   (  292): Level3 Library Sep 25 2014 17:10:03
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/WVCdm   (  292): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/VideoCapabilities( 7402): Unsupported mime video/wvc1
,D/DrmWidevineDash(  292): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  292): Service_Initialize: starts!
D/QSEECOMAPI: (  292): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  292): App is not loaded in QSEE
E/QSEECOMAPI: (  292): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  292): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  292): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  292): App is not loaded in QSEE
,E/QSEECOMAPI: (  292): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  292): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  292): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  292): App is not loaded in QSEE
,W/VideoCapabilities( 7402): Unsupported mime video/x-ms-wmv
,D/QSEECOMAPI: (  292): Loaded image: APP id = 2
,D/DrmWidevineDash(  292): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  292): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb0ae6000
E/DrmWidevineDash(  292): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb0ae6000
,I/ Time Manager ( 7465): Time Difference not stored. TIME_DIFFERENCE,
,W/ResourcesManager( 1981): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,D/accuweather( 7026): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 7026): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/GCoreUlr( 1597): 
E/GCoreUlr( 1597): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1597): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1597): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1597): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1597): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1597): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1597): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1597): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1597): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1597): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1597): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1597): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1597): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1597): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1597): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1597): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,W/VideoCapabilities( 7402): Unrecognized profile/level 32768/2 for video/mp4v-es
,D/DrmWidevineDash(  292): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  292): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  292): hlos api version =  9
D/DrmWidevineDash(  292): tz api version =  8
D/DrmWidevineDash(  292): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  292): OEMCrypto_IsKeyboxValid: starts!
,W/VideoCapabilities( 7402): Unsupported mime video/wvc1
,E/Zygote  ( 7485): MountEmulatedStorage()
I/libpersona( 7485): KNOX_SDCARD checking this for 10091
E/Zygote  ( 7485): v2
I/libpersona( 7485): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=7485 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 6413:com.samsung.helphub/1000 (adj 15): bgCount ##41
,D/DrmWidevineDash(  292): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  292): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  292): OEMCrypto_GetDeviceID: starts! deviceID=0xb1475b60, idLength=0xac0ff978
,D/DrmWidevineDash(  292): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  292): OEMCrypto_GetKeyData: starts! keyData=0xac0ff944, keyDataLength=0xac0ff93c
,I/SELinux ( 7485): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/DrmWidevineDash(  292): OEMCrypto_GetKeyData: ends! returns 0
D/DrmWidevineDash(  292): OEMCrypto_GetKeyData: starts! keyData=0xac0ff944, keyDataLength=0xac0ff93c
I/SELinux ( 7485): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7485): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/DrmWidevineDash(  292): OEMCrypto_GetKeyData: ends! returns 0
D/DrmWidevineDash(  292): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  292): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  292): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  292): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  292): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  292): OEMCrypto_SupportsUsageTable: ends! returns 0x0
I/WVCdm   (  292): L3 Terminate.
D/DrmWidevineDash(  292): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  292): Service_Uninitialize: starts!
W/VideoCapabilities( 7402): Unsupported mime video/x-ms-wmv
D/QSEECOMAPI: (  292): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  292): QSEECom_shutdown_app, app_id = 2
D/DrmWidevineDash(  292): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  292): OEMCrypto_Terminate: ends! returns 0
,I/SurfaceFlinger(  249): id=15 Removed Toast (8/9)
,I/SurfaceFlinger(  249): id=15 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/VideoCapabilities( 7402): Unsupported mime video/x-ms-wmv7
,D/PowerManagerService(  892): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 892) eventTime = 81227
,W/VideoCapabilities( 7402): Unsupported mime video/x-ms-wmv8
,D/PowerManagerService(  892): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=892 (0x0)
,D/TimaKeyStoreProvider( 7485): TimaSignature is unavailable
W/VideoCapabilities( 7402): Unsupported mime video/mp43
D/PowerManagerService(  892): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=892, ws=WorkSource{1000}) (elapsedTime=3492)
,D/ActivityThread( 7485): Added TimaKeyStore provider
,W/VideoCapabilities( 7402): Unsupported mime video/sorenson
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_6413/cgroup.procs: No such file or directory
,D/ResourcesManager( 7485): creating new AssetManager and set to /system/app/ClockPackage/ClockPackage.apk
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 6210): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6210): 
,I/VideoCapabilities( 7402): Unsupported profile 4 for video/mp4v-es
,D/SyncManager(  892): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 18324, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 7485): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7485): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/SyncManager(  892): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 113043, reason: Periodic
W/ResourcesManager( 7485): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7485): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7485): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Kids    ( 1981): [GCoreUtils] Current gmscore version, 7899438 is smaller than the required version 8400000
I/Kids    ( 1981): [KidsDataSyncAdapter] Skipping
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7501): MountEmulatedStorage()
E/Zygote  ( 7501): v2
I/libpersona( 7501): KNOX_SDCARD checking this for 10098
I/libpersona( 7501): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7501 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  892): Explicit concurrent mark sweep GC freed 36406(1807KB) AllocSpace objects, 10(290KB) LOS objects, 30% free, 36MB/52MB, paused 1.332ms total 98.368ms
D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  892): mCursor = null
,I/SELinux ( 7501): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7501): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7501): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7501): TimaSignature is unavailable
,D/ActivityThread( 7501): Added TimaKeyStore provider
,D/ResourcesManager( 7501): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  892): Killing 6386:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,D/SettingsProvider(  892): name = next_alarm_formatted
D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 10091
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SyncAdapterService( 7068): Ignoring sync request for non-current account
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7524): MountEmulatedStorage()
E/Zygote  ( 7524): v2
I/libpersona( 7524): KNOX_SDCARD checking this for 10104
I/libpersona( 7524): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7524 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7524): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7524): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7524): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  892): Killing 6453:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/DocsApplication( 7501): Installing DEX configuration.
,D/DexInstaller( 7501): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,D/TimaKeyStoreProvider( 7524): TimaSignature is unavailable
,D/ActivityThread( 7524): Added TimaKeyStore provider
,I/PackageInfoHelper( 7501): Provided clientMode=RELEASE, packageInfo=PackageInfo{14711634 com.google.android.apps.docs}
,W/libprocessgroup(  892): failed to open /acct/uid_10118/pid_6386/cgroup.procs: No such file or directory
,D/TAG     ( 7501): onCreate()
,D/CrossAppStateProvider( 7501): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/ResourcesManager( 7524): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,W/BaseAppContext( 1981): Using Auth Proxy for data requests.
,W/BaseAppContext( 1981): Using Auth Proxy for data requests.
,W/BaseAppContext( 1981): Using Auth Proxy for data requests.
,D/elm:14451( 7524): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14451( 7524): ELMEngine.ELMEngine( context ).
,D/elm:14451( 7524): MDMBridge.setEnterpriseBridge()
,W/libprocessgroup(  892): failed to open /acct/uid_10166/pid_6453/cgroup.procs: No such file or directory
,D/elm:14451( 7524): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,W/BaseAppContext( 1981): Using Auth Proxy for data requests.
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/elm:14451( 7524): ElmAgentService : onCreate()
,D/elm:14451( 7524): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:14451( 7524): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14451( 7524): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14451( 7524): ModuleBase.ModifySetAlarm()
D/elm:14451( 7524): MDMBridge.getInstance()
D/elm:14451( 7524): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 7541): MountEmulatedStorage()
,E/Zygote  ( 7541): v2
I/libpersona( 7541): KNOX_SDCARD checking this for 10113
I/libpersona( 7541): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.android.GeoLookout for broadcast com.sec.android.GeoLookout/.widget.SafetyCareWidget: pid=7541 uid=10113 gids={50113, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7541): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7541): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7541): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14451( 7524): ElmAgentService : onDestroy().
,I/ActivityManager(  892): Killing 6468:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,W/BaseAppContext( 1981): Using Auth Proxy for data requests.
,D/TimaKeyStoreProvider( 7541): TimaSignature is unavailable
,D/ActivityThread( 7541): Added TimaKeyStore provider
,W/BaseAppContext( 1981): Using Auth Proxy for data requests.
,D/ResourcesManager( 7541): creating new AssetManager and set to /system/app/GeoLookout/GeoLookout.apk
,W/BaseAppContext( 1981): Using Auth Proxy for data requests.
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  892): failed to open /acct/uid_10170/pid_6468/cgroup.procs: No such file or directory
,W/GeoLookout( 7541): H: zOXtzplbN+8pOR8lXMN+zuVFxvDlCo+Yzxg4ugbhd7A04DIT5nFf+o6jguBECoC9dC8nZsnXtcP6wJ/Do8CKbApjnmitl3AiTeKReyJRDttBktCZIh1mNkZuovfXxXoAjd37PhyBM3ng3bcKYjYGOEDyKJaWZrwK1FfNJWfEtzYH8n1Joa422xGgCu3P2tNC0syzQpcTEb6CNvuJmw0Apg==
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
I/GeoLookout( 7541): H: zOXtzplbN+8pOR8lXMN+zq5rYKS75KQLo4xvOOBhIY6eGw1/GT6WQYb1SRYOugxmkGHzev/Lb2j+GB0+6UGDnw==
,D/SettingsProvider(  892): name = safetycare_geolookout_registering
D/SettingsProvider(  892): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  892): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  892): selectionArgs: false
D/SettingsProvider(  892): selectionArgs: 10113
D/SecContentProvider(  892): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  892): ret = -1
,D/GeoLookout( 7541): H: mmqeDLqBgrS1PY9ZxjAERmjpyYDSyckxRVEBLahXFCCjxEHkYkZuzwjV7ldL9/y2wUiG8ZXusFQQzoKG1FCUjw==
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDkvkgPm5dotWx3IPNd1bDZ3HtYRASO8LE3XMTl+CWy7mA0iuhqjXXzZB9tx1thU84s=
,I/dhcpcd  ( 6758): wlan0: sending IPv6 Router Solicitation
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1MpblPvMyD8bF5o9h5mVT9aba68PSLy9IpSfBXGHVgOg==
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDkvkgPm5dotWx3IPNd1bDZ3HtYRASO8LE3XMTl+CWy7mA0iuhqjXXzZB9tx1thU84s=
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjVjhROowReQZ6uZ83+PHbxXxfrUuNQHmPlY4PsIKqeHXpHMfmw7BKa8EvZP1XFE95vEpSHlOxg9XQoR6KQvcMJUezCj+VlRSvYmiaFKv4yMdF9ANJ7ri8t1rvBR++sDAZA==
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  892): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7560 uid=10149 gids={50149, 9997} abi=armeabi-v7a
,E/Zygote  ( 7560): MountEmulatedStorage()
E/Zygote  ( 7560): v2
I/libpersona( 7560): KNOX_SDCARD checking this for 10149
I/libpersona( 7560): KNOX_SDCARD not a persona
,I/SELinux ( 7560): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7560): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7560): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/GHttpClientFactory( 5064): Using the GMSCore's GoogleHttpClient
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7560): TimaSignature is unavailable
,D/ActivityThread( 7560): Added TimaKeyStore provider
,D/ResourcesManager( 7560): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 7560): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7560): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7577): MountEmulatedStorage()
E/Zygote  ( 7577): v2
I/libpersona( 7577): KNOX_SDCARD checking this for 10150
I/libpersona( 7577): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7577 uid=10150 gids={50150, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5804:com.android.vending/u0a30 (adj 15): bgCount ##41
,I/SELinux ( 7577): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7577): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7577): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7577): TimaSignature is unavailable
,D/ActivityThread( 7577): Added TimaKeyStore provider
,W/libprocessgroup(  892): failed to open /acct/uid_10030/pid_5804/cgroup.procs: No such file or directory
,D/ResourcesManager( 7577): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7577): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7577): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7577): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 7062): Thread[GAThread,5,main]: No campaign data found.
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 6210): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6210): 
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_music.png
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,D/SecurityLogAgent( 6503): KnoxConfiguration : Current State = 1
W/MusicSyncAdapter( 5064): Sync failed due to an authentication issue.
D/SecurityLogAgent( 6503): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6503): StateMachine : Current State = 1
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7602): MountEmulatedStorage()
E/Zygote  ( 7602): v2
I/libpersona( 7602): KNOX_SDCARD checking this for 10176
I/libpersona( 7602): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=7602 uid=10176 gids={50176, 9997} abi=armeabi-v7a
,D/SyncManager(  892): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 18325, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  892): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 113869, reason: Periodic
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7602): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7602): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7602): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 6210): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6210): 
,D/TimaKeyStoreProvider( 7602): TimaSignature is unavailable
,D/ActivityThread( 7602): Added TimaKeyStore provider
,D/ResourcesManager( 7602): creating new AssetManager and set to /system/app/TaskManager/TaskManager.apk
,I/GAV4    ( 7068): Thread[GAThread,5,main]: No campaign data found.
,D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  892): mCursor = null
,W/ResourcesManager( 7602): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 6210): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 6210): 
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7621): MountEmulatedStorage()
,E/Zygote  ( 7621): v2
I/libpersona( 7621): KNOX_SDCARD checking this for 1000
I/libpersona( 7621): KNOX_SDCARD not a persona
,I/io.jxcore.node.ConnectivityInfo( 6210): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 6210):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 6210):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 6210):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 6210):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 6210):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 6210):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 6210):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 6210):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 6210): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log( 6210): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 6210): 
I/ActivityManager(  892): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7621 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/jxcore-log( 6210): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 6210): 
I/ActivityManager(  892): Killing 2289:com.google.android.gms.wearable/u0a12 (adj 15): bgCount ##41
,I/SELinux ( 7621): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7621): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7621): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  892): Killing 5950:com.android.defcontainer/u0a5 (adj 15): bgCount ##41
,I/ActivityManager(  892): Killing 6698:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7621): TimaSignature is unavailable
D/ActivityThread( 7621): Added TimaKeyStore provider
,E/Auth.Api.Credentials( 1981): [CredentialSyncAdapter] Unknown sync event.
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7621): creating new AssetManager and set to /system/app/TimeService/TimeService.apk
,D/TimeService( 7621): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1456908878555
,D/        ( 7621): TimeServiceNative: User Time to be set is 1456908878555
D/QC-time-services( 7621): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 7621): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 7621): Lib:time_genoff_operation: pargs->ts_val = 1456908878555
,D/QC-time-services( 7621): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  330): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  330): Daemon:Received base = 2, unit = 1, operation = 0,value = 1456908878555
D/QC-time-services(  330): Daemon:genoff_opr: Base = 2, val = 1456908878555, operation = 0
,D/QC-time-services(  330): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS6/8/70 20:29:14
,D/QC-time-services(  330): Daemon:Value read from RTC seconds = 16316954000
D/QC-time-services(  330): Daemon:new time 1456908878555 
D/QC-time-services(  330): Daemon: delta 1440591924555 genoff 1440591924555 
D/QC-time-services(  330): Daemon:genoff_persistent_update: Writing genoff = 1440591924555 to memory
D/QC-time-services(  330): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  330): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  330): Updating the TOD offset
D/QC-time-services(  330): Daemon:genoff_persistent_update: Writing genoff = 1440591924555 to memory
D/QC-time-services(  330): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  330): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  892): failed to open /acct/uid_10012/pid_2289/cgroup.procs: No such file or directory
,E/QC-time-services(  330): Daemon:Update to modem bit set
D/QC-time-services(  330): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  330): Daemon: Base = 2, Value being sent to MODEM = 1124627124555
,E/QC-time-services( 7621): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  330): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  330): Daemon: Time-services: Waiting to acceptconnection
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/daemonapp( 1328): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1328): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/GAV2    ( 7501): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/libprocessgroup(  892): failed to open /acct/uid_10005/pid_5950/cgroup.procs: No such file or directory
,W/libprocessgroup(  892): failed to open /acct/uid_10075/pid_6698/cgroup.procs: No such file or directory
,D/daemonapp( 1328): [MSC_Daemon]>>> WDSM:41 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1328): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1328): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
,D/comsamsunglog( 1328): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1328): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1328): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1328): [MSC_Daemon]>>> WU:1622 [0:0] PakNme size = 5
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1328): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1328): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1328): [MSC_Daemon]>>> WU:1626 [0:0] CP Name cp_eng
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/Zygote  ( 7651): MountEmulatedStorage()
I/libpersona( 7651): KNOX_SDCARD checking this for 10105
E/Zygote  ( 7651): v2
I/libpersona( 7651): KNOX_SDCARD not a persona
,E/daemonapp( 1328): [MSC_Daemon]>>> WU:1606 [0:0] [NameNotFoundException] !!
,I/ActivityManager(  892): Start proc com.google.android.apps.docs.editors.docs for content provider com.google.android.apps.docs.editors.docs/com.google.android.apps.docs.doclist.statesyncer.CrossAppStateProvider: pid=7651 uid=10105 gids={50105, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 8732(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 285us total 10.738ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 8.058ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.199ms
,E/SMD     (  287): DCD ON
,I/SELinux ( 7651): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7651): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7651): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7651): TimaSignature is unavailable
,D/ActivityThread( 7651): Added TimaKeyStore provider
,D/ResourcesManager( 7651): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/comdaemonstockapp( 1328): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1328): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1685): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7668): MountEmulatedStorage()
E/Zygote  ( 7668): v2
I/libpersona( 7668): KNOX_SDCARD checking this for 10117
I/libpersona( 7668): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=7668 uid=10117 gids={50117, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7668): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7668): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7668): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/GAV2    ( 7501): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7668): TimaSignature is unavailable
,D/ActivityThread( 7668): Added TimaKeyStore provider
,I/ActivityManager(  892): Killing 6057:com.sec.pcw.device/1000 (adj 15): bgCount ##41
,D/ResourcesManager( 7668): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/ChimeraCfgMgr( 1981): Loading module com.google.android.gms.games from APK com.google.android.gms
,W/ResourcesManager( 7668): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_6057/cgroup.procs: No such file or directory
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Babel   ( 7668): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 7668): MmsConfig.loadMmsSettings
I/Babel   ( 7668): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
I/Babel   ( 7668): MmsConfig.loadFromDatabase
,E/Babel   ( 7668): canonicalizeMccMnc: invalid mccmnc 
,D/ResourcesManager( 7668): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/Babel   ( 7668): MmsConfig.loadFromResources
,E/Babel   ( 7668): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 7668): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
,W/AudioCapabilities( 7668): Unsupported mime audio/evrc
,W/AudioCapabilities( 7668): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7668): Unrecognized profile 2130706433 for video/avc
,W/Settings( 7668): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 7668): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 7668): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 7668): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7668): Unsupported mime audio/x-ima
,W/AudioCapabilities( 7668): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7668): Unsupported mime audio/qcelp
,W/AudioCapabilities( 7668): Unsupported mime audio/evrc
,W/VideoCapabilities( 7668): Unsupported mime video/wvc1
,W/VideoCapabilities( 7668): Unsupported mime video/x-ms-wmv
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/VideoCapabilities( 7668): Unrecognized profile/level 32768/2 for video/mp4v-es
,D/ResourcesManager( 7668): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7668): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7668): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/VideoCapabilities( 7668): Unsupported mime video/wvc1
,W/VideoCapabilities( 7668): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 7668): Unsupported mime video/x-ms-wmv7
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthServiceInstalled() : HealthService is Installed.
,W/VideoCapabilities( 7668): Unsupported mime video/x-ms-wmv8
D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7227): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/VideoCapabilities( 7668): Unsupported mime video/mp43
,D/com.sec.android.service.health.cp.common.HttpConnectionConstants( 7227): RegionGroup for  is null
,W/VideoCapabilities( 7668): Unsupported mime video/sorenson
,V/JNIHelp ( 7668): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/VideoCapabilities( 7668): Unsupported profile 4 for video/mp4v-es
,I/art     (  892): Explicit concurrent mark sweep GC freed 38891(2032KB) AllocSpace objects, 3(113KB) LOS objects, 30% free, 36MB/52MB, paused 1.788ms total 102.210ms
,D/BluetoothManager( 7227): getConnectedDevices
,D/BluetoothManager( 7227): getConnectedDevices
D/BluetoothManager( 7227): getConnectedDevices
D/BluetoothManager( 7227): getConnectedDevices
D/BluetoothManager( 7227): getConnectedDevices
,D/BluetoothManager( 7227): getConnectedDevices
,E/DatabaseUtils(  892): Writing exception to parcel
E/DatabaseUtils(  892): java.lang.NullPointerException: key == null
E/DatabaseUtils(  892): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  892): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  892): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  892): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  892): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  892): 	at android.os.Binder.execTransact(Binder.java:446)
,D/AdaptiveEventManager( 1168): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
,D/AdaptiveEventManager( 1168): M updateContainers()
D/AdaptiveEventContainerSmall( 1168): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1168): handlePedoUpdate()
,D/AdaptiveEventContainerSmall( 1168): pedoEvent == null
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,V/BitmapFactory( 7227): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi/s_health_widget_engraft_pedometer_mask.qmg
,W/ActivityThread( 7668): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7668): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1a825b76: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7668): Installed default security provider GmsCore_OpenSSL
,V/BitmapFactory( 7227): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi/s_health_widget_engraft_pedometer_icon.qmg
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7227): DecodeImagePath(decodeResourceStream3) : res/drawable-xxxhdpi/s_health_widget_mask.qmg
,W/ContextImpl( 5064): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,V/BitmapFactory( 7227): DecodeImagePath(decodeResourceStream3) : res/drawable-xxxhdpi/s_health_widget_pedometer_icon_02.qmg
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5064): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/MusicLeanback( 5064): Conditions not met for autocaching.
D/BluetoothManager( 7227): getConnectedDevices
,I/MusicLeanback( 5064): Stop autocaching.
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7721): MountEmulatedStorage()
E/Zygote  ( 7721): v2
I/libpersona( 7721): KNOX_SDCARD checking this for 10012
I/libpersona( 7721): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7721 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 7721): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/BluetoothManager( 7227): getConnectedDevices
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7721): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7721): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/BluetoothManager( 7227): getConnectedDevices
,D/TimaKeyStoreProvider( 7721): TimaSignature is unavailable
,D/ActivityThread( 7721): Added TimaKeyStore provider
,D/ResourcesManager( 7721): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7721): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7721): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ArtDownloadService( 5064): Setting cache size 0
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5064): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5064): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,I/MultiDex( 7721): VM with version 2.1.0 has multidex support
I/MultiDex( 7721): install
I/MultiDex( 7721): VM has multidex support, MultiDex support library is disabled.
,E/Babel   ( 7668): UserRecoverableAuthException.
,E/Babel   ( 7668): cfq: BadAuthentication
E/Babel   ( 7668): 	at cfn.a(Unknown Source)
E/Babel   ( 7668): 	at f.a(PG:191)
E/Babel   ( 7668): 	at ava.a(PG:88)
E/Babel   ( 7668): 	at ava.a(PG:128)
E/Babel   ( 7668): 	at bjs.a(PG:255)
E/Babel   ( 7668): 	at bep.a(PG:602)
E/Babel   ( 7668): 	at bep.a(PG:469)
E/Babel   ( 7668): 	at bpo.run(PG:1141)
,E/Babel   ( 7668): Error getting auth token
E/Babel   ( 7668): bxl
E/Babel   ( 7668): 	at f.a(PG:201)
E/Babel   ( 7668): 	at ava.a(PG:88)
E/Babel   ( 7668): 	at ava.a(PG:128)
E/Babel   ( 7668): 	at bjs.a(PG:255)
E/Babel   ( 7668): 	at bep.a(PG:602)
E/Babel   ( 7668): 	at bep.a(PG:469)
E/Babel   ( 7668): 	at bpo.run(PG:1141)
,I/Babel_RequestWriter( 7668): error sending REQ[fc:24; creat:1456842835469; type:bev-623366251]; took 171 ms (error code == 100)
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Babel   ( 7668): Account registration failedRedacted-21
,E/Babel   ( 7668): bph: null -- null
E/Babel   ( 7668): 	at ava.a(PG:120)
E/Babel   ( 7668): 	at ava.a(PG:128)
E/Babel   ( 7668): 	at bjs.a(PG:255)
E/Babel   ( 7668): 	at bep.a(PG:602)
E/Babel   ( 7668): 	at bep.a(PG:469)
E/Babel   ( 7668): 	at bpo.run(PG:1141)
,I/Babel   ( 7668): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 7668): Account sign in complete with state 106account: Redacted-21
,I/art     ( 7668): Note: end time exceeds epoch: 
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/JNIHelp ( 7721): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 1685): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi/ic_launcher_babel.png
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/Babel   ( 7668): Unexpected exception while authenticating.
,E/Babel   ( 7668): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 7668): 	at cfn.b(Unknown Source)
E/Babel   ( 7668): 	at cfn.a(Unknown Source)
E/Babel   ( 7668): 	at f.a(PG:188)
E/Babel   ( 7668): 	at ava.b(PG:143)
E/Babel   ( 7668): 	at bnr.run(PG:5415)
E/Babel   ( 7668): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 7668): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 7668): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,W/ActivityThread( 7721): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7721): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@563ae60: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7721): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1685): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1685): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1981): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 7721): callingUid 10012, callindPid: 7721
,D/LocationInitializer( 1981): Restart initialization of location
,D/WearableClient( 5064): WearableClientImpl.onPostInitHandler: done
,E/MDM     ( 1597): [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WearableClient( 5064): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 5064): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 5064): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 5064): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5064): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GAV3    ( 7227): Thread[GAThread,5,main]: No campaign data found.
,W/ActiveOrDefaultContextProvider( 7651): Missing scope.enter somewhere. Returning default context
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/GAV2    ( 7651): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/CrossAppStateProvider( 7651): Unknown URI content://com.google.android.apps.docs.editors.kix.statesyncer/accountMetadata
,D/WifiService(  892): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@14d9c0db}
,W/GAV2    ( 7501): SyncManager-thalitester@gmail.com: Need to call initialize() and be in fallback mode to start dispatch.
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 7501): Thread-1197(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7501): Thread-1197(ApacheHTTPLog):isShipBuild true
,I/System.out( 7501): Thread-1197(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/GAV2    ( 7651): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/System.out( 7501): SyncManager calls detatch()
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2: https://www.googleapis.com/auth/drive
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/app/Drive/Drive.apk
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/launcher_drive_icon.png
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,W/PsynchoHelperImpl( 7501): Error fetching or saving configuration
W/PsynchoHelperImpl( 7501): java.io.IOException: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7501): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:145)
W/PsynchoHelperImpl( 7501): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl( 7501): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl( 7501): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl( 7501): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl( 7501): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl( 7501): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl( 7501): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl( 7501): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl( 7501): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl( 7501): 	at agP.run(LegacySyncManager.java:416)
W/PsynchoHelperImpl( 7501): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7501): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
W/PsynchoHelperImpl( 7501): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/PsynchoHelperImpl( 7501): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
W/PsynchoHelperImpl( 7501): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/PsynchoHelperImpl( 7501): 	at android.os.Binder.execTransact(Binder.java:446)
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1685): Explicit concurrent mark sweep GC freed 17464(983KB) AllocSpace objects, 9(729KB) LOS objects, 40% free, 18MB/30MB, paused 467us total 25.356ms
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: writely
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> writely without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/app/Drive/Drive.apk
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/launcher_drive_icon.png
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpIssuerBase( 7501): Attempt to consume entity of HttpIssuer when no request is executing.
,E/HttpIssuerBase( 7501): Attempt to close HttpIssuer when no request is executing.
E/HttpIssuerBase( 7501): java.io.IOException
E/HttpIssuerBase( 7501): 	at TG.b(HttpIssuerBase.java:188)
E/HttpIssuerBase( 7501): 	at Tj.b(DefaultAuthenticatedHttpIssuer.java:151)
E/HttpIssuerBase( 7501): 	at afE.a(AccountMetadataUpdater.java:227)
E/HttpIssuerBase( 7501): 	at afE.a(AccountMetadataUpdater.java:140)
E/HttpIssuerBase( 7501): 	at agO.a(LegacySyncManager.java:828)
E/HttpIssuerBase( 7501): 	at agO.b(LegacySyncManager.java:588)
E/HttpIssuerBase( 7501): 	at agO.a(LegacySyncManager.java:467)
E/HttpIssuerBase( 7501): 	at agO.a(LegacySyncManager.java:97)
E/HttpIssuerBase( 7501): 	at agQ.run(LegacySyncManager.java:419)
E/HttpIssuerBase( 7501): 	at ami.a(NetworkUtilitiesImpl.java:31)
E/HttpIssuerBase( 7501): 	at agP.run(LegacySyncManager.java:416)
,E/SyncManager( 7501): AuthenticatorException
E/SyncManager( 7501): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/SyncManager( 7501): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/SyncManager( 7501): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/SyncManager( 7501): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/SyncManager( 7501): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/SyncManager( 7501): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GAV2    ( 7501): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/WifiService(  892): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@14d9c0db}
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  892): Killing 6859:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##41
,D/SyncManager(  892): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 18325, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  892): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 117368, reason: Periodic
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  892): mCursor = null
,W/libprocessgroup(  892): failed to open /acct/uid_10002/pid_6859/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD ON
,V/AlarmManager(  892): waitForAlarm result :4
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7797): MountEmulatedStorage()
I/libpersona( 7797): KNOX_SDCARD checking this for 10030
E/Zygote  ( 7797): v2
I/libpersona( 7797): KNOX_SDCARD not a persona
I/ActivityManager(  892): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7797 uid=10030 gids={50030, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7797): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7797): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/dhcpcd  ( 6758): wlan0: sending IPv6 Router Solicitation
E/SELinux ( 7797): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 6758): wlan0: no IPv6 Routers available
D/BatteryService(  892): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  892): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  892): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  892): stay LED for charging
,D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  892): Plugged
,I/MotionRecognitionService(  892): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,V/HeadsetService( 6543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6543): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/TimaKeyStoreProvider( 7797): TimaSignature is unavailable
,D/ActivityThread( 7797): Added TimaKeyStore provider
,D/ResourcesManager( 7797): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/Finsky  ( 7797): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7797): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7831): MountEmulatedStorage()
,E/Zygote  ( 7831): v2
I/libpersona( 7831): KNOX_SDCARD checking this for 10012
I/libpersona( 7831): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7831 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 7831): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7831): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7831): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Settings( 7797): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7797): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TimaKeyStoreProvider( 7831): TimaSignature is unavailable
,D/ActivityThread( 7831): Added TimaKeyStore provider
,D/ResourcesManager( 7831): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7831): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7831): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 7797): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7797): [1] 2.run: Finished loading 1 libraries.
,I/MultiDex( 7831): VM with version 2.1.0 has multidex support
,I/MultiDex( 7831): install
I/MultiDex( 7831): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7831): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 7797): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7797): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ActivityThread( 7831): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7831): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@563ae60: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7831): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1685): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1685): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1981): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1597): [161] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1981): Restart initialization of location
,D/ResourcesManager( 7831): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager( 7831): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/Finsky  ( 7797): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7797): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7797): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7797): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  892): Killing 6077:com.policydm/1000 (adj 15): bgCount ##41
,I/ActivityManager(  892): Killing 6898:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##42
,W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_6898/cgroup.procs: No such file or directory
,W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_6077/cgroup.procs: No such file or directory
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,D/GeoLookout( 7541): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,V/AlarmManager(  892): waitForAlarm result :4
,D/Finsky  ( 7797): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7797): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  892): Explicit concurrent mark sweep GC freed 29773(1649KB) AllocSpace objects, 5(275KB) LOS objects, 30% free, 36MB/52MB, paused 1.176ms total 80.474ms
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7797): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GAV2    ( 7501): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7797): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7797): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7797): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7797): [1] DailyHygiene.reschedule: Scheduling new run in 275 minutes (failures=4)
,D/DeviceConnectionService( 1597): client connected with version: 7571000
,I/jxcore-log( 6210): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 6210): 
,E/SQLiteLog( 1685): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  892): SIOP:: AP = 460, PST = 436, CUR = 300
,E/SMD     (  287): DCD ON
,D/PreloadUpdateManagerStateMachine( 6487): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6487): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6487): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6487): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  ( 6487): RestApi Request Add : 2307
,E/File    ( 6487): fail readDirectory() errno=2
,I/System.out( 6487): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6487): (HTTPLog)-Static: isShipBuild true
I/System.out( 6487): (HTTPLog)-Thread-1041-673764932: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 6487): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 6487, getuid(): 10040
,I/qtaguid ( 6487): Untagging socket 26
,D/hcjo    ( 6487): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 6487): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 6487): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6487): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6487): entry::REQ_UPDATE_CHECK
,I/Volley  ( 6487): RestApi Request Add : 2315
,I/qtaguid ( 6487): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 6487, getuid(): 10040
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6210): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 6210): 
,I/qtaguid ( 6487): Untagging socket -1
,I/qtaguid ( 6487): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid ( 6487): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger( 6487): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 6487): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine( 6487): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 6487): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 6487): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 6487): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 6487): exit::FINISH
,D/PreloadUpdateManagerStateMachine( 6487): entry::IDLE
,I/ActivityManager(  892): Killing 5244:com.sec.android.gallery3d/u0a48 (adj 15): bgCount ##41
,I/jxcore-log( 6210): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6210): 
,W/libprocessgroup(  892): failed to open /acct/uid_10048/pid_5244/cgroup.procs: No such file or directory
,I/jxcore-log( 6210): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 6210): 
,D/PackageManager(  892): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  892): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  892): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/ActivityManager(  892): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7897 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/Zygote  ( 7897): MountEmulatedStorage()
,E/Zygote  ( 7897): v2
I/libpersona( 7897): KNOX_SDCARD checking this for 10034
I/libpersona( 7897): KNOX_SDCARD not a persona
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/SELinux ( 7897): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7897): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7897): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/InputReader(  892): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/RegisteredServicesCache( 1473): empty dynamic service
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/RegisteredServicesCache( 1473): empty dynamic service
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 1504): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/TimaKeyStoreProvider( 7897): TimaSignature is unavailable
,D/ActivityThread( 7897): Added TimaKeyStore provider
,W/ResourcesManager( 1504): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 1504): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,W/ResourcesManager( 1504): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1504): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,V/BitmapFactory( 1504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi/ic_launcher_babel.png
,D/ResourcesManager( 1504): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
W/ResourcesManager( 1504): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  892): mCursor = null
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/FeatureConfig( 7897): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 1504): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/Launcher.Workspace( 1504): isBadgeUpdate : false
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
,D/BackupManagerService(  892): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(  892): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  892): mCursor = null
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,V/BitmapFactory( 1504): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_videos.png
,D/BackupManagerService(  892): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager(  892): Killing 7045:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Launcher.Workspace( 1504): isBadgeUpdate : false
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  892): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  892): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  892): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_7045/cgroup.procs: No such file or directory
,D/ResourcesManager(  892): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 7897): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 7897): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 7897): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 7897): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SMD     (  287): DCD ON
,I/ActivityManager(  892): Killing 5740:com.sec.chaton/u0a86 (adj 15): bgCount ##41
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7934): MountEmulatedStorage()
E/Zygote  ( 7934): v2
I/libpersona( 7934): KNOX_SDCARD checking this for 10048
I/libpersona( 7934): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7934 uid=10048 gids={50048, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 7934): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7934): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7934): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7934): TimaSignature is unavailable
,D/ActivityThread( 7934): Added TimaKeyStore provider
,W/libprocessgroup(  892): failed to open /acct/uid_10086/pid_5740/cgroup.procs: No such file or directory
,D/ResourcesManager( 7934): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7934): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7934): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7934): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7934): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7934): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 7934): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7934): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7934): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SensorService(  892): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
,I/SensorService(  892): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  892): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7950): MountEmulatedStorage()
E/Zygote  ( 7950): v2
I/libpersona( 7950): KNOX_SDCARD checking this for 10002
I/libpersona( 7950): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.android.cloudagent for content provider com.sec.android.cloudagent/.CloudProvider: pid=7950 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7950): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7950): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7950): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7950): TimaSignature is unavailable
,D/ActivityThread( 7950): Added TimaKeyStore provider
,D/ResourcesManager( 7950): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Spen    ( 7934): SpenSdk version level = 55
D/Spen    ( 7934): SpenSdk jar version = 3.0.238
,D/Spen    ( 7934): SpenSdk apk version = 3.0.238
D/Spen    ( 7934): Server UPDATE Check
,W/linker  ( 7934): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/SPenError( 7934): JNI_OnLoad
,D/JNI_Bitmap( 7934): Init .. Done
,D/SPenSpiDecoder( 7934): JNI_OnLoad .. Done
D/SPenError( 7934): JNI_OnLoad Success
,D/PluginManager( 7934): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
,D/PluginManager( 7934): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni( 7934): JNI_OnLoad
,D/Init_SPenSdk_Jni( 7934): AndroidSDK: 21
D/Init_SPenSdk_Jni( 7934): JNI_OnLoad .. Done
,D/Model_ObjectBase_Jni( 7934): JNI_OnLoad .. Done
,D/Model_ObjectStroke_Jni( 7934): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni( 7934): JNI_OnLoad .. Done
,D/Model_ObjectText_Jni( 7934): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni( 7934): JNI_OnLoad .. Done
,D/Model_PageDoc_Jni( 7934): JNI_OnLoad .. Done
,D/Model_NoteDoc_Jni( 7934): check build type eng[0]
,D/Model_NoteDoc_Jni( 7934): JNI_OnLoad .. Done
D/Model_NoteFile_Jni( 7934): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni( 7934): JNI_OnLoad .. Done
D/Model   ( 7934): OnLoad class Done
,D/spe_log ( 7934): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library( 7934): Draw Engine JNI_OnLoad enter!!
D/SPen_Library( 7934): Canvas JNI_OnLoad enter!!
,D/SPen_Library( 7934): Canvas JNI_OnLoad Success
D/SPen_Library( 7934): TextView JNI_OnLoad enter!!
,D/SPen_Library( 7934): TextView JNI_OnLoad Success
D/SPen_Library( 7934): Text JNI_OnLoad enter!!
D/SPen_Library( 7934): Text JNI_OnLoad Success
D/SPen_Library( 7934): FontManager JNI_OnLoad enter!!
D/SPen_Library( 7934): FontManager JNI_OnLoad Success
,D/SPen_Library( 7934): CapturePage JNI_OnLoad enter!!
D/SPen_Library( 7934): CapturePage JNI_OnLoad Success
D/SPen_Library( 7934): Multi JNI_OnLoad enter!!
D/SPen_Library( 7934): Multi JNI_OnLoad Success
,D/SPen_Library( 7934): Draw Engine JNI_OnLoad Success
,D/SPen_Library( 7934): Brush JNI_OnLoad enter!!
,D/SPen_Library( 7934): Brush JNI_OnLoad Success
,D/SPen_Library( 7934): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library( 7934): ChineseBrush JNI_OnLoad Success
,D/SPen_Library( 7934): InkPen JNI_OnLoad enter!!,
D/SPen_Library( 7934): InkPen JNI_OnLoad Success
,D/SPen_Library( 7934): Marker JNI_OnLoad enter!!
,D/SPen_Library( 7934): Marker JNI_OnLoad Success
,D/SPen_Library( 7934): Pencil JNI_OnLoad enter!!
,D/SPen_Library( 7934): Pencil JNI_OnLoad Success
,D/SPen_Library( 7934): NativePen JNI_OnLoad enter!!
,D/SPen_Library( 7934): NativePen JNI_OnLoad Success
,D/SPen_Library( 7934): MontblancFountainPen JNI_OnLoad enter!!
,D/SPen_Library( 7934): MontblancFountainPen JNI_OnLoad Success
,D/SPen_Library( 7934): MontblancCalligraphyPen JNI_OnLoad enter!!
,D/SPen_Library( 7934): MontblancCalligraphyPen JNI_OnLoad Success
,D/SPen_Library( 7934): MagicPen JNI_OnLoad enter!!
,D/SPen_Library( 7934): MagicPen JNI_OnLoad Success
,D/SPen_Library( 7934): ObliquePen JNI_OnLoad enter!!
,D/SPen_Library( 7934): ObliquePen JNI_OnLoad Success
,D/SPen_Library( 7934): FountainPen JNI_OnLoad enter!!
,D/SPen_Library( 7934): FountainPen JNI_OnLoad Success
D/Spen    ( 7934): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni( 7934): SPenSdk_init2
D/Init_SPenSdk( 7934): Init - screen_width = 1080, screen_height = 1920, maxCacheSize = 5 M
,D/Init_SPenSdk( 7934): Total S Pen SDK Directory Size = 0
D/Spen    ( 7934): initialize complete
,D/ResourcesManager( 4261): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 4261): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/NearbySource( 7934): Nearby Source Create!
,D/NearbyContext( 7934): Nearby Context Create!
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7934): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 7934): Samsung link source created
,D/SLinkClient( 7934): query devices()
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 4261): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/Zygote  ( 7973): MountEmulatedStorage()
E/Zygote  ( 7973): v2
I/libpersona( 7973): KNOX_SDCARD checking this for 10042
I/libpersona( 7973): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.samsung.android.sdk.samsunglink for content provider com.samsung.android.sdk.samsunglink/com.mfluent.asp.datamodel.ASPMediaStoreProvider: pid=7973 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7973): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7973): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7973): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7973): TimaSignature is unavailable
,D/ActivityThread( 7973): Added TimaKeyStore provider
,D/ResourcesManager( 7973): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,D/ContactProvider( 7934): getAllContactInfoList Start
,D/WifiDisplayAdapter(  892): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ResourcesManager( 7973): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7973): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/WifiDisplayAdapter(  892): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider( 7934): getAllContactInfoList End
,I/syncContacts( 7934): thread: 1250, sync time = 63
,I/ActivityManager(  892): Killing 6850:com.android.chrome/u0a88 (adj 15): bgCount ##41
,I/UpdateIcingCorporaServi( 1578): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7996): MountEmulatedStorage()
,E/Zygote  ( 7996): v2
I/libpersona( 7996): KNOX_SDCARD checking this for 10075
I/libpersona( 7996): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7996 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7996): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7996): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7996): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  892): Killing 6604:com.android.email/u0a163 (adj 15): bgCount ##41
,I/ActivityManager(  892): Killing 7158:com.samsung.android.sconnect/u0a138 (adj 15): bgCount ##42
,D/TimaKeyStoreProvider( 7996): TimaSignature is unavailable
,D/ActivityThread( 7996): Added TimaKeyStore provider
,D/ResourcesManager( 7996): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/ResourcesManager( 1578): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/libprocessgroup(  892): failed to open /acct/uid_10088/pid_6850/cgroup.procs: No such file or directory
,W/ResourcesManager( 1578): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1578): UpdateCorporaTask done [took 75 ms] updated apps [took 75 ms] 
,D/FileShare-Server( 7996): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.talk
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8012): MountEmulatedStorage()
,E/Zygote  ( 8012): v2
I/libpersona( 8012): KNOX_SDCARD checking this for 1000
I/libpersona( 8012): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=8012 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 6573:tv.peel.smartremote/u0a171 (adj 15): bgCount ##41
,I/SELinux ( 8012): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8012): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8012): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  892): failed to open /acct/uid_10138/pid_7158/cgroup.procs: No such file or directory
,W/libprocessgroup(  892): failed to open /acct/uid_10163/pid_6604/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8012): TimaSignature is unavailable
,D/ActivityThread( 8012): Added TimaKeyStore provider
,D/ResourcesManager( 8012): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
W/System.err( 7973): java.lang.NoSuchMethodException: getImeiInCDMAGSMPhone []
,W/System.err( 7973): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 7973): 	at com.sec.pcw.util.c.c(SourceFile:295)
W/System.err( 7973): 	at com.sec.pcw.service.account.a.b(SourceFile:250)
W/System.err( 7973): 	at com.sec.pcw.service.account.a.a(SourceFile:52)
W/System.err( 7973): 	at com.mfluent.asp.datamodel.Device.r(SourceFile:359)
W/System.err( 7973): 	at com.mfluent.asp.datamodel.Device.<init>(SourceFile:248)
W/System.err( 7973): 	at com.mfluent.asp.datamodel.t.a(SourceFile:136)
W/System.err( 7973): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:484)
W/System.err( 7973): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
W/System.err( 7973): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
W/System.err( 7973): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
W/System.err( 7973): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
W/System.err( 7973): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
W/System.err( 7973): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7973): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7973): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7973): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7973): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7973): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7973): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7973): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7973): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ResourcesManager( 8012): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SL_DEBUG( 7973): isLoggable:: isProductShip = 1
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,I/SL_DEBUG( 7973): isLoggable:: SL_DEBUG_EXIST = false
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 8031): MountEmulatedStorage()
E/Zygote  ( 8031): v2
I/libpersona( 8031): KNOX_SDCARD checking this for 10086
I/libpersona( 8031): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.chaton for broadcast com.sec.chaton/.plugin.PlugInMonitor: pid=8031 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 7179:com.samsung.android.service.travel/u0a178 (adj 15): bgCount ##41
,I/art     (  311): Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 271us total 12.910ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.750ms
I/SELinux ( 8031): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8031): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8031): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 8.408ms
,D/TimaKeyStoreProvider( 8031): TimaSignature is unavailable
,D/ActivityThread( 8031): Added TimaKeyStore provider
,D/ActivityThread( 7973): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
,W/libprocessgroup(  892): failed to open /acct/uid_10171/pid_6573/cgroup.procs: No such file or directory
,D/ResourcesManager( 8031): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8031): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/SLinkClient( 7934): queryDevices : cursor.getCount() = [ 0 ]
,D/SLinkClient( 7934): onStorageUpdated(), uri = [ slink://slink ]
,W/libprocessgroup(  892): failed to open /acct/uid_10178/pid_7179/cgroup.procs: No such file or directory
,I/SLinkClient( 7934): SlinkBackgroundJob: slink wake up ok!
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7973): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7973): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,V/Transcoder( 7973): Transcoder(0xaedd1830)::constructor
,V/Transcoder( 7973): addObitRecipient
V/TMI-JNI ( 7973): Mobile Transcoder JNI version 1.6.0/20131120/4.4
,D/PushModule( 8031): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 8031): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 8031): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 8031): [1][isApplicationInstalled] com.android.mms was installed
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 8031): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  892): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 8031): [1][a] ChatONV isn't installed.
D/ChatON  ( 8031): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8060): MountEmulatedStorage()
E/Zygote  ( 8060): v2
I/libpersona( 8060): KNOX_SDCARD checking this for 1000
I/libpersona( 8060): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8060 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 6946:com.sec.android.fotaclient/u0a11 (adj 15): bgCount ##41
,I/SELinux ( 8060): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8060): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8060): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  892): failed to open /acct/uid_10011/pid_6946/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8060): TimaSignature is unavailable
,D/ActivityThread( 8060): Added TimaKeyStore provider
,D/ResourcesManager( 8060): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,D/ShortcutReceiver( 8060):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  892): Killing 6972:com.samsung.klmsagent/u0a19 (adj 15): bgCount ##41
,D/PackageBroadcastService( 1981): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/PeopleContactsSync( 1981): CP2 sync disabled
,W/libprocessgroup(  892): failed to open /acct/uid_10019/pid_6972/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1578): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,D/FileShare-Server( 7996): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.videos
,D/ShortcutReceiver( 8060):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/PackageBroadcastService( 1981): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,D/ResourcesManager( 1578): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/PeopleContactsSync( 1981): CP2 sync disabled
,I/UpdateIcingCorporaServi( 1578): UpdateCorporaTask done [took 85 ms] updated apps [took 85 ms] 
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  892): [PWL] Off : 50s ago
,D/SSRM:m  (  892): SIOP:: AP = 410, PST = 436, CUR = 300
,I/ActivityManager(  892): Waited long enough for: ServiceRecord{fa8e2b8 u0 com.google.android.music/.download.artwork.ArtDownloadService}
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  892): !@Sync 3
,V/AlarmManager(  892): waitForAlarm result :8
,D/FactoryTest( 5615): Not factory mode
,D/FactoryTest( 5615): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5615): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5615): still no open session command from host, so toast
,W/ContextImpl( 5615): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5615): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 5615): Timeline: Activity_launch_request id:com.android.settings time:104789
,E/PersonaManagerService(  892): inState():  stateMachine is null !!
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  892): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  892): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/MTPRx   ( 5615): started activity for popup
,D/X       (  892): broadcastSiopLevelIntent:: currentSiopLevel = 0
,I/SQLiteSecureOpenHelper( 3302): getWritableDatabase(pwd)
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 5615): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 5615): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5615): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5615): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5615): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5615): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5615): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5615): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ContentApp( 1221):  LEVEL : 0
,I/SQLiteSecureOpenHelper( 3302): getDatabaseLocked(b,b,pwd)...
,E/Zygote  ( 8107): MountEmulatedStorage()
E/Zygote  ( 8107): v2
I/libpersona( 8107): KNOX_SDCARD checking this for 10054
I/libpersona( 8107): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8107 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 8107): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/AlarmManager(  892): waitForAlarm result :4
,I/SELinux ( 8107): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8107): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/TimaKeyStoreProvider( 8107): TimaSignature is unavailable
,D/ActivityThread( 8107): Added TimaKeyStore provider
,D/ResourcesManager( 8107): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8107): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8107): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8107): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8107): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8107): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5615): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/InputMethodManagerService(  892): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  892): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@79d3a95 attribute=null, token = android.os.BinderProxy@97fa951
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/BatteryService(  892): level:100, scale:100, status:2, health:2, present:true, voltage: 4363, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  892): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  892): stay LED for charging
D/BatteryService(  892): Sending ACTION_BATTERY_CHANGED.
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  892): Plugged
I/MotionRecognitionService(  892): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/HeadsetService( 6543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6543): Disconnected process message: 10
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 5615): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,E/TranscodeReceiver( 8107): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8107): core_num = 4
,D/SettingsReceiverActivity( 5615): dev.kiessupport is : TRUE
,W/linker  ( 8107): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8107): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8107): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 8107): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/Activity( 5615): performCreate Call secproduct feature valuefalse
D/Activity( 5615): performCreate Call debug elastic valuetrue
,D/TranscodeReceiver( 8107):  SIOP_LEVEL: 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/ActivityManager(  892): Killing 4920:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ActivityManager(  892): post active user change for 0
,D/KnoxTimeoutHandler(  892): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  892): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/Timeline( 6210): Timeline: Activity_idle id: android.os.BinderProxy@29fa7285 time:105208
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/libprocessgroup(  892): failed to open /acct/uid_10038/pid_4920/cgroup.procs: No such file or directory
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,V/AlarmManager(  892): waitForAlarm result :4
,W/ActivityManager(  892): mDVFSHelper.release()
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7797): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7797): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7797): [1] 5.onFinished: Scheduling replication attempt 3.
,D/SSRM:m  (  892): SIOP:: AP = 370, PST = 432, CUR = 300
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,W/art     ( 8107): Suspending all threads took: 9.307ms
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService(  892): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  892): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  892): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  892): Plugged
,I/MotionRecognitionService(  892): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/LightsService(  892): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 892) 
,D/LightsService(  892): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x12 -> 0x42 | SvcLED(id=3) set On
,E/LightSensor(  892): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,V/HeadsetService( 6543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6543): Disconnected process message: 10
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId -2 pkgname com.android.systemui
,D/WindowManager(  892): showStatusBarByNotification() mOpenByNotification=false
,D/SensorManager(  892): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  892): turn on LED for fully charged
,D/PowerManagerService(  892): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1168
,I/PowerManagerService(  892): !@[ps] Screen__On wl: PowerUI.Notification
,I/PowerManagerService(  892): Waking up from sleep (uid 10059)...
,V/KeyguardServiceDelegate(  892): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@20fa22e3)
,D/KeyguardViewMediator( 1168): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1168): notifyScreenOnLocked
,D/PowerManagerService(  892): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/PowerManagerService(  892): [s] UserActivityState : 0 -> 1
,D/PowerManagerService(  892): [PWL] sb acquire: PowerManagerService.Display
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/DisplayPowerController(  892): Blocking screen on until initial contents have been drawn.
,D/SContextService(  892): 	.registerCallback : 1, client=
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_battery_full.png
D/AutomaticBrightnessController(  892): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/AutomaticBrightnessController(  892): [DAB] setLightSensorEnabled : registerListener mLightSensor
,D/DisplayPowerController(  892): getFinalBrightness : 0 -> 0
,D/AutomaticBrightnessController(  892): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
I/AutomaticBrightnessController(  892): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
,I/AutomaticBrightnessController(  892): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
,D/SensorManager(  892): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/PowerManagerService(  892): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
,D/MISC PowerHAL(  892): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL(  892): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PowerManagerService(  892): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 11ms
,I/QCOM PowerHAL(  892): Got set_interactive hint
,E/Sensors (  892): Acc old sensor_state 8704, new sensor_state : 8705 en : 1
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,I/DisplayManagerService(  892): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  249): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Unblanking display: 0
,W/CAE     (  892): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,D/SensorManager(  892): registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
,D/PowerManagerService(  892): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 26ms
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/CAE     (  892): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
I/CAE     (  892): setCAProperty(ContextAwareService.java:469) - result : true
W/CAE     (  892): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  892): sendProperty() : service = Auto Rotation
,W/CAE     (  892): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  892): start(ContextProvider.java:126)
,V/CAE     (  892): clear(AutoRotationRunner.java:182)
V/CAE     (  892): enable(AutoRotationRunner.java:158)
I/CAE     (  892): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager(  892): SendSensorHubData: send data = -79, 7, 0, 0
D/InputManager-JNI(  892): setDeviceInteractive: 1
,D/InputManager-JNI(  892): sysfs_write +: /sys/class/input/event2/device/enabled: 1
,D/InputManager-JNI(  892): sysfs_write +: /sys/class/input/event1/device/enabled: 1
D/ActivityManager(  892): post active user change for 0
,D/KnoxTimeoutHandler(  892): postActiveUserChange for user 0
,D/SamsungIME( 1832): showDlgMsgBox : false true true
,V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_battery_full.png
,D/Sensorhubs(  298): sendContextData: -79, 7, 0, 0
,D/CAE     (  892): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  892): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/NfcService( 1473): call the applyRotuiing
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/KnoxNotification( 1168): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1168): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1168): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1168): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@37bec079
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,V/UserPresentBroadcastReceiver( 1597): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,E/Adreno-ES20( 6210): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 6210): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/CAE     (  892): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  892): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,D/CAE     (  892): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,I/CAE     (  892): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@1c79a45f, Service : AUTO_ROTATION(1)
W/CAE     (  892): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  892): addSContextService() : service = Auto Rotation
D/SContextService(  892): ===== SContext Service List =====
D/SContextService(  892): Listener : android.hardware.scontext.SContextService$Listener@305a1eac, Service : Auto Rotation
D/SContextManager(  892):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@1fb434e0, service=Auto Rotation
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,D/KeyguardViewMediator( 1168): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1168): onScreenTurnedOn()
,I/GoogleURLConnFactory( 1685): Using platform SSLCertificateSocketFactory
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/rmt_storage(  277): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
I/rmt_storage(  277): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  277): wakelock acquired: 1, error no: 42
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
D/InputManager-JNI(  892): sysfs_write -: /sys/class/input/event2/device/enabled: 1
,D/StatusBar.NetworkController( 1168): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/KeyguardServiceDelegate(  892): **** SHOWN CALLED ****
,D/DisplayPowerController(  892): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,D/StatusBarKeyguardViewManager( 1168): callback.onShown()
,I/DisplayPowerController(  892): Unblocked screen on after 211 ms
D/DisplayPowerState(  892): !@ ColorFade exit
,I/SurfaceFlinger(  249): id=12 Removed ColorFade (8/8)
,I/SurfaceFlinger(  249): id=12 Removed ColorFade (-2/8)
E/libEGL  (  892): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/BatteryMeterView( 1168): onDraw batteryColor : -1
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  277): 
,I/rmt_storage(  277): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,I/Timeline( 6210): Timeline: Activity_idle id: android.os.BinderProxy@29fa7285 time:115579
,D/InputManager-JNI(  892): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/PalmMotion(  892): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
D/PalmMotion(  892): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService(  892): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 892) 
D/LightsService(  892): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x42 -> 0x40 | SvcLED(id=4) set Off
,V/ActivityManager(  892): Display changed displayId=0
,D/SSRM:a  (  892): DeviceInfo:: 000000000000
D/SSRM:a  (  892): SettingsAirViewInfo:: 000000000
,D/SLocation(  892): handleMessage got exceptionjava.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
W/System.err(  892): java.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
,W/System.err(  892): 	at com.samsung.location.lib.h.handleMessage(Unknown Source)
W/System.err(  892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  892): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  892): 	at com.samsung.location.SLocationService.run(Unknown Source)
W/System.err(  892): 	at java.lang.Thread.run(Thread.java:818)
,D/KnoxTimeoutHandler(  892): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/LightsService(  892): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager(  892): unregisterListener ::   
D/lights  (  892): led_pattern : 5 +
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LightsService(  892): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 892) 
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  249): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  249): hwc_blank: Done unblanking display: 0
,D/SurfaceControl(  892): Excessive delay in setPowerMode(): 295ms
,D/lights  (  892): led_pattern : 5 -
D/lights  (  892): lcd : 8 +
D/LightsService(  892): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=4) OUT; SvcLED(id=3) IN
,D/LightsService(  892): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService(  892): turn off LED
,D/lights  (  892): lcd : 8 -
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  892): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  892): SecHardwareInterface.setBatteryADC : true
,D/PowerManagerService(  892): [input device light] setInputDeviceLightOn is called : 1
D/PowerManagerService(  892): [input device light] handleInputDeviceLightOn
,D/lights  (  892): button : 1 +
,I/CAE     (  892): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  892): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,I/CAE     (  892): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
,D/SensorHubManager(  892): SendSensorHubData: send data = -76, 13, -47, 0
D/LightsService(  892): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/Sensorhubs(  298): sendContextData: -76, 13, -47, 0
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,D/InputMethodManagerService(  892): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_SCREEN_ON
,D/lights  (  892): button : 1 -
,D/lights  (  892): led_pattern : 0 +
,E/SMD     (  287): DCD ON
,E/MotionRecognitionService(  892):  handler : SCREEN_ON end
,D/lights  (  892): led_pattern : 0 -
,D/LightsService(  892): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/WifiNative-HAL(  892): startHal
E/wifi    (  892): getStaticLongField sWifiHalHandle 0x95ce17fc
D/wifi    (  892): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x1028f2
I/WifiNative-HAL(  892): Could not start hal
D/WifiStateMachine(  892): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  892): handleScreenStateChanged Exit: true
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/NotificationService(  892): ACTION_SCREEN_ON
,D/LightsService(  892): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 892) 
D/LightsService(  892): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  892): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  892): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  292): adev_set_parameters: enter: screen_state=on
V/voice   (  292): voice_set_parameters: enter: screen_state=on
V/voice   (  292): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  292): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  292): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  292): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  292): adev_set_parameters: exit
,E/WifiStateMachine(  892): Force RSSI Broadcast 2/3
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,I/SecExternalDisplayIntents_Java(  892): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/WifiStateMachine(  892): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/native  (  892): do suspend false
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/IpRemoteDisplayController(  892): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  892): Bridge Server is not available
,E/Uploader( 1685): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1685): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1685): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1685): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1685): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1685): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1685): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1685): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1685): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1685): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
I/wpa_supplicant( 6558): reset timer : RESET_TIMER 1
I/wpa_supplicant( 6558): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 6558): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 6558): Scan requested (ret=0) - scan timeout 30 seconds
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,D/PersonaManagerService(  892): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler(  892): MSG_ACTION_SCREEN_ON called
,I/NfcService( 1473): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1473): call the applyRotuiing
,E/WifiStateMachine(  892): Force RSSI Broadcast 3/3
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/accuweather( 2092): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 2092): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
D/accuweather( 2092): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/accuweather( 2092): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
,D/accuweather( 2092): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/accuweather( 2092): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,I/SamsungIME( 1832): getNextShiftState() cursorCapsMode : 0
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SurfaceWidget.Renderer( 2092): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2092): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2092): [237392/6] SurfaceWidget drawing first frame
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PowerManagerService(  892): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:m  (  892): SIOP:: AP = 340, PST = 421, CUR = 300
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 1685): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1685, getuid(): 10012
,D/daemonapp( 1328): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
D/daemonapp( 1328): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1328): [MSC_Daemon]>>> WDSM:41 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1328): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1328): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
,D/comsamsunglog( 1328): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1328): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1328): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
D/daemonapp( 1328): [MSC_Daemon]>>> WDSM:418 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/daemonapp( 1328): [MSC_Daemon]>>> WDSM:421 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1328): [MSC_Daemon]>>> WDSM:422 [0:0] [ASO][NUT] = 1456930380000
D/daemonapp( 1328): [MSC_Daemon]>>> WDSM:423 [0:0] [ASO][CT] = 1456908911997
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1328): [MSC_Daemon]>>> WU:1622 [0:0] PakNme size = 5
,D/daemonapp( 1328): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1328): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1328): [MSC_Daemon]>>> WU:1626 [0:0] CP Name cp_eng
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1328): [MSC_Daemon]>>> WU:1606 [0:0] [NameNotFoundException] !!
,I/qtaguid ( 1685): Tagging socket 66 with tag 120100000000{4609,0} uid -1, pid: 1685, getuid(): 10012
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,W/Uploader( 1685): No account for auth token provided
,I/qtaguid ( 1685): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1685, getuid(): 10012
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,W/Uploader( 1685): No account for auth token provided
,I/qtaguid ( 1685): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1685, getuid(): 10012
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_inout.png
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,W/Uploader( 1685): No account for auth token provided
,I/qtaguid ( 1685): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1685, getuid(): 10012
,D/SSRM:a  (  892): DeviceInfo:: 000000000000
D/SSRM:a  (  892): SettingsAirViewInfo:: 000000000
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,W/Uploader( 1685):  no longer exists, so no auth token.
,I/qtaguid ( 1685): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1685, getuid(): 10012
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,W/Uploader( 1685): No account for auth token provided
,I/qtaguid ( 1685): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1685, getuid(): 10012
,D/PowerManagerService(  892): [input device light] handleInputDeviceLightOff
,D/lights  (  892): button : 0 +
,D/lights  (  892): button : 0 -
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,W/Uploader( 1685): No account for auth token provided
,I/qtaguid ( 1685): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1685, getuid(): 10012
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,W/Uploader( 1685): No account for auth token provided
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,I/qtaguid ( 1685): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1685, getuid(): 10012
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,W/Uploader( 1685): No account for auth token provided
,I/qtaguid ( 1685): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1685, getuid(): 10012
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,W/Uploader( 1685): No account for auth token provided
,I/qtaguid ( 1685): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1685, getuid(): 10012
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/SMD     (  287): DCD ON
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,W/Uploader( 1685): No account for auth token provided
,I/qtaguid ( 1685): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1685, getuid(): 10012
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  892): calculateWifiScore() report new score 60
I/WifiStateMachine(  892): calculateWifiScore : sendNetworkScore in!
,I/WifiStateMachine(  892): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  892): CMD_RSSI_POLL : out!
,D/ConnectivityService(  892): updateNetworkScore for NetworkAgentInfo [WIFI () - 502] to 60
,D/ConnectivityService(  892): rematching NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  892):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  892):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  892): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,D/ConnectivityService(  892): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  892): calling update connectivity
D/ConnectivityService(  892):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  892):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  892): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  892): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524290
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/SQLiteLog( 1685): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,I/wpa_supplicant( 6558): nl80211: Received scan results (16 BSSes)
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/WifiP2pService(  892): InactiveState{ what=147461 }
D/WifiP2pService(  892): P2pEnabledState{ what=147461 }
,E/WifiStateMachine(  892): [1,456,908,915,606 ms] noteScanEnd no scan source
,D/WifiP2pService(  892): DefaultState{ what=147461 }
,E/WifiStateMachine(  892): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3840e5e2 sup_state=COMPLETED debouncing=false
,I/CLocInfoService(  892): External Intent Received android.net.wifi.SCAN_RESULTS
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_in.png
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/SMD     (  287): DCD ON
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  892): CMD_RSSI_POLL : out!
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/SMD     (  287): DCD ON
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  892): CMD_RSSI_POLL : out!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  892): SIOP:: AP = 330, PST = 409, CUR = 300
,D/X       (  892): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1221):  LEVEL : -1
,E/TranscodeReceiver( 8107): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/TranscodeReceiver( 8107):  SIOP_LEVEL: -1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/SMD     (  287): DCD ON
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore in!
D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  892): CMD_RSSI_POLL : out!
,V/AlarmManager(  892): waitForAlarm result :4
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/BatteryService(  892): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  892): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  892): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  892): Plugged
I/MotionRecognitionService(  892): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6543): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,I/art     (  892): Explicit concurrent mark sweep GC freed 89804(4MB) AllocSpace objects, 20(385KB) LOS objects, 30% free, 36MB/52MB, paused 1.779ms total 194.663ms
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,I/art     ( 1685): Explicit concurrent mark sweep GC freed 44566(2MB) AllocSpace objects, 78(4MB) LOS objects, 40% free, 18MB/30MB, paused 826us total 57.912ms
,D/Finsky  ( 7797): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7797): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7797): [1] 5.onFinished: Scheduling replication attempt 4.
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/SMD     (  287): DCD ON
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  892): CMD_RSSI_POLL : out!
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/SMD     (  287): DCD ON
,E/Watchdog(  892): !@Sync 4
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  892): CMD_RSSI_POLL : out!
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,V/AlarmManager(  892): waitForAlarm result :4
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  892): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1168 (0x0)
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 6936): Starting books sync, d
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 6936): Authentication error
E/BooksAccountManager( 6936): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6936): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 6936): null auth token
,I/qtaguid ( 6936): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 6936, getuid(): 10082
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,E/HttpOperation( 5774): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5774): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5774): 	at kfv.a(PG:65)
E/HttpOperation( 5774): 	at kff.u(PG:385)
E/HttpOperation( 5774): 	at kfb.a(PG:29)
E/HttpOperation( 5774): 	at kff.l(PG:132)
E/HttpOperation( 5774): 	at dsf.a(PG:807)
E/HttpOperation( 5774): 	at fhk.a(PG:1126)
E/HttpOperation( 5774): 	at fhk.a(PG:908)
E/HttpOperation( 5774): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5774): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5774): 	at ihi.a(PG:22)
E/HttpOperation( 5774): 	at kft.a(PG:91)
E/HttpOperation( 5774): 	at kfv.a(PG:62)
E/HttpOperation( 5774): 	... 8 more
E/HttpOperation( 5774): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5774): 	at gde.c(Unknown Source)
E/HttpOperation( 5774): 	at gde.b(Unknown Source)
E/HttpOperation( 5774): 	at ihi.a(PG:19)
E/HttpOperation( 5774): 	... 10 more
,I/qtaguid ( 6936): Untagging socket 34
,W/ApiaryClient( 6936): Error response from books API: {
W/ApiaryClient( 6936):  "error": {
W/ApiaryClient( 6936):   "errors": [
W/ApiaryClient( 6936):    {
W/ApiaryClient( 6936):     "domain": "global",
W/ApiaryClient( 6936):     "reason": "required",
W/ApiaryClient( 6936):     "message": "Login Required",
W/ApiaryClient( 6936):     "locationType": "header",
W/ApiaryClient( 6936):     "location": "Authorization"
W/ApiaryClient( 6936):    }
W/ApiaryClient( 6936):   ],
W/ApiaryClient( 6936):   "code": 401,
W/ApiaryClient( 6936):   "message": "Login Required"
W/ApiaryClient( 6936):  }
W/ApiaryClient( 6936): }
,W/ApiaryClient( 6936): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6936): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4387608040802533603&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6936): Headers suppressed
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5774): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5774): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5774): 	at kfv.a(PG:65)
E/HttpOperation( 5774): 	at kff.u(PG:385)
E/HttpOperation( 5774): 	at kfb.a(PG:29)
E/HttpOperation( 5774): 	at kff.l(PG:132)
E/HttpOperation( 5774): 	at ieo.a(PG:43)
E/HttpOperation( 5774): 	at iep.a(PG:93)
E/HttpOperation( 5774): 	at fhn.a(PG:59)
E/HttpOperation( 5774): 	at lex.a(PG:85)
E/HttpOperation( 5774): 	at lex.b(PG:132)
E/HttpOperation( 5774): 	at fhk.a(PG:1146)
E/HttpOperation( 5774): 	at fhk.a(PG:908)
E/HttpOperation( 5774): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5774): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5774): 	at ihi.a(PG:22)
E/HttpOperation( 5774): 	at kft.a(PG:91)
E/HttpOperation( 5774): 	at kfv.a(PG:62)
E/HttpOperation( 5774): 	... 12 more
E/HttpOperation( 5774): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5774): 	at gde.c(Unknown Source)
E/HttpOperation( 5774): 	at gde.b(Unknown Source)
E/HttpOperation( 5774): 	at ihi.a(PG:19)
E/HttpOperation( 5774): 	... 14 more
E/ExperimentLoader( 5774): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5774): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5774): 	at kfv.a(PG:65)
E/ExperimentLoader( 5774): 	at kff.u(PG:385)
E/ExperimentLoader( 5774): 	at kfb.a(PG:29)
E/ExperimentLoader( 5774): 	at kff.l(PG:132)
E/ExperimentLoader( 5774): 	at ieo.a(PG:43)
E/ExperimentLoader( 5774): 	at iep.a(PG:93)
E/ExperimentLoader( 5774): 	at fhn.a(PG:59)
E/ExperimentLoader( 5774): 	at lex.a(PG:85)
E/ExperimentLoader( 5774): 	at lex.b(PG:132)
E/ExperimentLoader( 5774): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5774): 	at fhk.a(PG:908)
E/ExperimentLoader( 5774): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5774): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5774): 	at ihi.a(PG:22)
E/ExperimentLoader( 5774): 	at kft.a(PG:91)
E/ExperimentLoader( 5774): 	at kfv.a(PG:62)
E/ExperimentLoader( 5774): 	... 12 more
E/ExperimentLoader( 5774): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5774): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5774): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5774): 	at ihi.a(PG:19)
E/ExperimentLoader( 5774): 	... 14 more
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5774): [getaccountstatus] Unexpected exception
E/HttpOperation( 5774): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5774): 	at kfv.a(PG:65)
E/HttpOperation( 5774): 	at kff.u(PG:385)
E/HttpOperation( 5774): 	at kfb.a(PG:29)
E/HttpOperation( 5774): 	at ixd.a(PG:248)
E/HttpOperation( 5774): 	at ixd.b(PG:206)
E/HttpOperation( 5774): 	at ixd.a(PG:175)
E/HttpOperation( 5774): 	at fig.a(PG:78)
E/HttpOperation( 5774): 	at lex.a(PG:85)
E/HttpOperation( 5774): 	at lex.b(PG:132)
E/HttpOperation( 5774): 	at fhk.a(PG:1146)
E/HttpOperation( 5774): 	at fhk.a(PG:908)
E/HttpOperation( 5774): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5774): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5774): 	at ihi.a(PG:22)
E/HttpOperation( 5774): 	at kft.a(PG:91)
E/HttpOperation( 5774): 	at kfv.a(PG:62)
E/HttpOperation( 5774): 	... 12 more
E/HttpOperation( 5774): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5774): 	at gde.c(Unknown Source)
E/HttpOperation( 5774): 	at gde.b(Unknown Source)
E/HttpOperation( 5774): 	at ihi.a(PG:19)
E/HttpOperation( 5774): 	... 14 more
E/EsSyncAdapterService( 5774): Sync failure
E/EsSyncAdapterService( 5774): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5774): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5774): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5774): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5774): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5774): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5774): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5774): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5774): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5774): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5774): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5774): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5774): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5774): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5774): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5774): 	... 10 more
E/EsSyncAdapterService( 5774): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5774): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5774): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5774): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5774): 	... 12 more
E/EsSyncAdapterService( 5774): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5774): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5774): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5774): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5774): 	... 14 more
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,D/SyncManager(  892): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 107511, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 2713): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  892): mCursor = null
D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2713): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  892): mCursor = null
,D/SSRM:m  (  892): SIOP:: AP = 320, PST = 396, CUR = 300
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness(),
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/SQLiteLog( 1685): (10) POSIX Error : 11 SQLite Error : 3850
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/SMD     (  287): DCD ON
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 6936): Authentication error
E/BooksAccountManager( 6936): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6936): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 6936): null auth token
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
I/qtaguid ( 6936): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 6936, getuid(): 10082
D/PanelView( 1168): There is/are notification(s) 
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  892): CMD_RSSI_POLL : out!
,I/qtaguid ( 6936): Untagging socket 34
,W/ApiaryClient( 6936): Error response from books API: {
W/ApiaryClient( 6936):  "error": {
W/ApiaryClient( 6936):   "errors": [
W/ApiaryClient( 6936):    {
W/ApiaryClient( 6936):     "domain": "global",
W/ApiaryClient( 6936):     "reason": "required",
W/ApiaryClient( 6936):     "message": "Login Required",
W/ApiaryClient( 6936):     "locationType": "header",
W/ApiaryClient( 6936):     "location": "Authorization"
W/ApiaryClient( 6936):    }
W/ApiaryClient( 6936):   ],
W/ApiaryClient( 6936):   "code": 401,
W/ApiaryClient( 6936):   "message": "Login Required"
W/ApiaryClient( 6936):  }
W/ApiaryClient( 6936): }
W/ApiaryClient( 6936): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6936): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4387608040802533603&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6936): Headers suppressed
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6936): Authentication error
E/BooksAccountManager( 6936): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6936): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 6936): null auth token
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 6936): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 6936, getuid(): 10082
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,I/qtaguid ( 6936): Untagging socket 34
,W/ApiaryClient( 6936): Error response from books API: {
W/ApiaryClient( 6936):  "error": {
W/ApiaryClient( 6936):   "errors": [
W/ApiaryClient( 6936):    {
W/ApiaryClient( 6936):     "domain": "global",
W/ApiaryClient( 6936):     "reason": "required",
W/ApiaryClient( 6936):     "message": "Login Required",
W/ApiaryClient( 6936):     "locationType": "header",
W/ApiaryClient( 6936):     "location": "Authorization"
W/ApiaryClient( 6936):    }
W/ApiaryClient( 6936):   ],
W/ApiaryClient( 6936):   "code": 401,
W/ApiaryClient( 6936):   "message": "Login Required"
W/ApiaryClient( 6936):  }
W/ApiaryClient( 6936): }
,W/ApiaryClient( 6936): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6936): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4387608040802533603&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6936): Headers suppressed
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 8 -> 8
,E/BooksSync( 6936): Soft error
E/BooksSync( 6936): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6936): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4387608040802533603&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6936): Headers suppressed
E/BooksSync( 6936): 
E/BooksSync( 6936): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 6936): Sync error
E/BooksSync( 6936): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6936): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4387608040802533603&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6936): Headers suppressed
E/BooksSync( 6936): 
E/BooksSync( 6936): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 6936): Finished books sync
D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  892): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 112030, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PowerManagerService(  892): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  892): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  892): lcd : 3 +
,D/lights  (  892): lcd : 3 -
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  892): mCursor = null
,D/lights  (  892): lcd : 1 +
,D/lights  (  892): lcd : 1 -
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/SMD     (  287): DCD ON
E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
I/ServiceManager(  322): Waiting for service AtCmdFwd...
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  892): CMD_RSSI_POLL : out!
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/SMD     (  287): DCD ON
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  892): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  892): CMD_RSSI_POLL : out!
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
,D/DisplayPowerController(  892): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  892): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  892): Nap time (uid 1000)...
I/PowerManagerService(  892): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  892): Going to sleep due to screen timeout (uid 1000)...
,D/InputManager-JNI(  892): setDeviceInteractive: 0
,D/PowerManagerService(  892): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  892): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService(  892): handleSandman : startDream()
,D/InputManager-JNI(  892): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,E/PowerManagerService(  892): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  892): Sleeping (uid 1000)...
,D/PowerManagerService(  892): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  892): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  892): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=16 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  892): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  892): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  892): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  892): 	.unregisterCallback : 1, client=
,D/SContextService(  892): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@305a1eac, Service = Auto Rotation, used = 1
,W/CAE     (  892): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  892): stop(ContextProvider.java:149)
,V/CAE     (  892): clear(AutoRotationRunner.java:182)
,V/CAE     (  892): disable(AutoRotationRunner.java:171)
,I/CAE     (  892): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,D/SensorHubManager(  892): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  298): sendContextData: -78, 7, 0, 0
,D/CAE     (  892): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  892): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  892): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  892): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  892): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  892): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  892): removeSContextService() : service = Auto Rotation
D/SContextService(  892): ===== SContext Service List =====
D/SContextManager(  892):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@1fb434e0, service=Auto Rotation
,D/KeyguardViewMediator( 1168): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1168): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1168): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1168): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/KeyguardViewMediator( 1168): timeout : 5000
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/DisplayPowerController(  892): ColorFade: onAnimationStart
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 0
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 0
,D/lights  (  892): lcd : 0 +
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 0
,D/lights  (  892): lcd : 0 -
,I/SQLiteSecureOpenHelper( 3302): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3302): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 1168): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1168): handleNotifyScreenOff
,D/LightsService(  892): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 892) 
D/LightsService(  892): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  892): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  892): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService(  892): turn on LED for fully charged
,D/SensorManager(  892): unregisterListener ::   
D/lights  (  892): led_pattern : 5 +
,I/CAE     (  892): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  892): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  892): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  892): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  298): sendContextData: -76, 13, -46, 0
,D/lights  (  892): led_pattern : 5 -
,D/LightsService(  892): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  892): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 8, 55, 41,
D/SensorHubManager(  892): SendSensorHubData: send data = -63, 14, 8, 55, 41
,D/Sensorhubs(  298): sendContextData: -63, 14, 8, 55, 41
,D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  892):  handler : SCREEN_OFF end 
,D/NotificationService(  892): ACTION_SCREEN_OFF
D/LightsService(  892): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 892) 
D/LightsService(  892): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/WifiStateMachine(  892): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  892): handleScreenStateChanged Exit: false
,D/LightsService(  892): [SvcLED]  onSensorChanged::light value = 0
,E/WifiStateMachine(  892): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  892): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  892): do suspend true
,D/SensorManager(  892): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  892): unregisterListener ::   
D/LightsService(  892): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  292): adev_set_parameters: enter: screen_state=off
V/voice   (  292): voice_set_parameters: enter: screen_state=off
V/voice   (  292): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  292): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  292): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  292): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  292): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  892): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  892): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  892): Bridge Server is not available
,D/VolumePanel( 1168): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1168): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1168): mCoverBroadcastReceiver: Screen OFF end
,D/VolumePanel( 1168): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  892): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  892): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1473): call the applyRotuiing
,E/LightSensor(  892): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  892): mCallbacks.updateBrightness()
D/DisplayPowerController(  892): getFinalBrightness : 8 -> 0
,D/STATUSBAR-PhoneStatusBar( 1168):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1168): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1168): dismissHelpPopup 
,D/accuweather( 2092): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2092): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2092): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/DisplayPowerState(  892): !@ ColorFade entry
,D/DisplayPowerController(  892): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  892): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  892): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
E/LightSensor(  892): Light old sensor_state 8705, new sensor_state : 8193 en : 0
D/AutomaticBrightnessController(  892): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/AutomaticBrightnessController(  892): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  892): unregisterListener ::   
E/Sensors (  892): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  892): unregisterListener ::   
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DisplayPowerController(  892): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  892): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  892): Display changed displayId=0
D/DisplayPowerController(  892): getFinalBrightness : 0 -> 0
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,E/SMD     (  287): DCD ON
,W/ActivityManager(  892): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  892): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  892): [PWL] sb release: PowerManagerService.Broadcasts
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/SSRM:m  (  892): SIOP:: AP = 320, PST = 383, CUR = 300
,D/StatusBar.NetworkController( 1168): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  892): Excessive delay in setPowerMode(): 262ms
D/MISC PowerHAL(  892): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/PowerManagerService(  892): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  892): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  892): Got set_interactive hint
,I/PowerManagerService(  892): [PWL] Off : 0s ago
I/PowerManagerService(  892): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  892): [PWL]     mDisplayReady : false
,D/DisplayPowerController(  892): getFinalBrightness : 0 -> 0
D/PowerManagerService(  892): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  892): [PWL] sb release: PowerManagerService.Display
,V/AlarmManager(  892): waitForAlarm result :4
,D/BatteryService(  892): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  892): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  892): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  892): Plugged
,I/MotionRecognitionService(  892): setPowerConnected  = true
,D/BatteryService(  892): stay LED for fully charged
,E/SMD     (  287): DCD ON
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 6543): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7797): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7797): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7797): [1] 5.onFinished: Scheduling replication attempt 5.
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  892): waitForAlarm result :4
,D/KeyguardViewMediator( 1168): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1168): isKioskContainerExistOnDevice,
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/KeyguardViewMediator( 1168): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  892): [PWL] Off : 5s ago
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  892): SIOP:: AP = 310, PST = 372, CUR = 300
,E/SMD     (  287): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService(  892): [PWL] Off : 15s ago
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD ON
,E/Watchdog(  892): !@Sync 5
,V/AlarmManager(  892): waitForAlarm result :8
,V/AlarmManager(  892): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  892): SIOP:: AP = 300, PST = 359, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  892): waitForAlarm result :4
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7797): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7797): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7797): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  287): DCD ON
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  892): SIOP:: AP = 300, PST = 346, CUR = 300
,I/PowerManagerService(  892): [PWL] Off : 30s ago
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  892): waitForAlarm result :4
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  892): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  892): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  892): stay LED for fully charged
,D/BatteryService(  892): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  892): Plugged
,I/MotionRecognitionService(  892): setPowerConnected  = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6543): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  892): SIOP:: AP = 290, PST = 329, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  892): !@Sync 6
,I/PowerManagerService(  892): [PWL] Off : 50s ago
,D/SSRM:m  (  892): SIOP:: AP = 290, PST = 317, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  892): waitForAlarm result :4
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  892): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  892): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  892): stay LED for fully charged
D/BatteryService(  892): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  892): Plugged
I/MotionRecognitionService(  892): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6543): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,E/HttpOperation( 5774): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5774): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5774): 	at kfv.a(PG:65)
E/HttpOperation( 5774): 	at kff.u(PG:385)
E/HttpOperation( 5774): 	at kfb.a(PG:29)
E/HttpOperation( 5774): 	at kff.l(PG:132)
E/HttpOperation( 5774): 	at dsf.a(PG:807)
E/HttpOperation( 5774): 	at fhk.a(PG:1126)
E/HttpOperation( 5774): 	at fhk.a(PG:908)
E/HttpOperation( 5774): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5774): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5774): 	at ihi.a(PG:22)
E/HttpOperation( 5774): 	at kft.a(PG:91)
E/HttpOperation( 5774): 	at kfv.a(PG:62)
E/HttpOperation( 5774): 	... 8 more
E/HttpOperation( 5774): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5774): 	at gde.c(Unknown Source)
E/HttpOperation( 5774): 	at gde.b(Unknown Source)
E/HttpOperation( 5774): 	at ihi.a(PG:19)
E/HttpOperation( 5774): 	... 10 more
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,E/HttpOperation( 5774): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5774): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5774): 	at kfv.a(PG:65)
E/HttpOperation( 5774): 	at kff.u(PG:385)
E/HttpOperation( 5774): 	at kfb.a(PG:29)
E/HttpOperation( 5774): 	at kff.l(PG:132)
E/HttpOperation( 5774): 	at ieo.a(PG:43)
E/HttpOperation( 5774): 	at iep.a(PG:93)
E/HttpOperation( 5774): 	at fhn.a(PG:59)
E/HttpOperation( 5774): 	at lex.a(PG:85)
E/HttpOperation( 5774): 	at lex.b(PG:132)
E/HttpOperation( 5774): 	at fhk.a(PG:1146)
E/HttpOperation( 5774): 	at fhk.a(PG:908)
E/HttpOperation( 5774): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5774): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5774): 	at ihi.a(PG:22)
E/HttpOperation( 5774): 	at kft.a(PG:91)
E/HttpOperation( 5774): 	at kfv.a(PG:62)
E/HttpOperation( 5774): 	... 12 more
E/HttpOperation( 5774): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5774): 	at gde.c(Unknown Source)
E/HttpOperation( 5774): 	at gde.b(Unknown Source)
E/HttpOperation( 5774): 	at ihi.a(PG:19)
E/HttpOperation( 5774): 	... 14 more
,E/ExperimentLoader( 5774): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5774): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5774): 	at kfv.a(PG:65)
E/ExperimentLoader( 5774): 	at kff.u(PG:385)
E/ExperimentLoader( 5774): 	at kfb.a(PG:29)
E/ExperimentLoader( 5774): 	at kff.l(PG:132)
E/ExperimentLoader( 5774): 	at ieo.a(PG:43)
E/ExperimentLoader( 5774): 	at iep.a(PG:93)
E/ExperimentLoader( 5774): 	at fhn.a(PG:59)
E/ExperimentLoader( 5774): 	at lex.a(PG:85)
E/ExperimentLoader( 5774): 	at lex.b(PG:132)
E/ExperimentLoader( 5774): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5774): 	at fhk.a(PG:908)
E/ExperimentLoader( 5774): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5774): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5774): 	at ihi.a(PG:22)
E/ExperimentLoader( 5774): 	at kft.a(PG:91)
E/ExperimentLoader( 5774): 	at kfv.a(PG:62)
E/ExperimentLoader( 5774): 	... 12 more
E/ExperimentLoader( 5774): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5774): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5774): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5774): 	at ihi.a(PG:19)
E/ExperimentLoader( 5774): 	... 14 more
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,E/HttpOperation( 5774): [getaccountstatus] Unexpected exception
E/HttpOperation( 5774): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5774): 	at kfv.a(PG:65)
E/HttpOperation( 5774): 	at kff.u(PG:385)
E/HttpOperation( 5774): 	at kfb.a(PG:29)
E/HttpOperation( 5774): 	at ixd.a(PG:248)
E/HttpOperation( 5774): 	at ixd.b(PG:206)
E/HttpOperation( 5774): 	at ixd.a(PG:175)
E/HttpOperation( 5774): 	at fig.a(PG:78)
E/HttpOperation( 5774): 	at lex.a(PG:85)
E/HttpOperation( 5774): 	at lex.b(PG:132)
E/HttpOperation( 5774): 	at fhk.a(PG:1146)
E/HttpOperation( 5774): 	at fhk.a(PG:908)
E/HttpOperation( 5774): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5774): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5774): 	at ihi.a(PG:22)
E/HttpOperation( 5774): 	at kft.a(PG:91)
E/HttpOperation( 5774): 	at kfv.a(PG:62)
E/HttpOperation( 5774): 	... 12 more
E/HttpOperation( 5774): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5774): 	at gde.c(Unknown Source)
E/HttpOperation( 5774): 	at gde.b(Unknown Source)
E/HttpOperation( 5774): 	at ihi.a(PG:19)
E/HttpOperation( 5774): 	... 14 more
,E/EsSyncAdapterService( 5774): Sync failure
E/EsSyncAdapterService( 5774): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5774): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5774): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5774): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5774): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5774): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5774): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5774): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5774): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5774): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5774): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5774): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5774): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5774): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5774): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5774): 	... 10 more
E/EsSyncAdapterService( 5774): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5774): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5774): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5774): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5774): 	... 12 more
E/EsSyncAdapterService( 5774): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5774): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5774): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5774): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5774): 	... 14 more
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  892): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 198282, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2713): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2713): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/art     (  892): Explicit concurrent mark sweep GC freed 69393(3MB) AllocSpace objects, 34(1129KB) LOS objects, 30% free, 36MB/52MB, paused 1.961ms total 181.931ms
D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  892): mCursor = null
,E/SQLiteLog( 1685): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  892): SIOP:: AP = 290, PST = 309, CUR = 300
,E/SMD     (  287): DCD ON
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  892): SIOP:: AP = 290, PST = 304, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  892): [PWL] Off : 75s ago
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,E/Watchdog(  892): !@Sync 7
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  892): waitForAlarm result :8
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  892): SIOP:: AP = 290, PST = 300, CUR = 300
,E/SMD     (  287): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager(  892): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/BatteryService(  892): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  892): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  892): stay LED for fully charged
,D/BatteryService(  892): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  892): Plugged
I/MotionRecognitionService(  892): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6543): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 6936): Starting books sync, d
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
D/SecContentProvider2(  892): mCursor = null
,D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 6936): Authentication error
E/BooksAccountManager( 6936): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6936): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 6936): null auth token
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
I/qtaguid ( 6936): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 6936, getuid(): 10082
,I/qtaguid ( 6936): Untagging socket 34
,W/ApiaryClient( 6936): Error response from books API: {
W/ApiaryClient( 6936):  "error": {
W/ApiaryClient( 6936):   "errors": [
W/ApiaryClient( 6936):    {
W/ApiaryClient( 6936):     "domain": "global",
W/ApiaryClient( 6936):     "reason": "required",
W/ApiaryClient( 6936):     "message": "Login Required",
W/ApiaryClient( 6936):     "locationType": "header",
W/ApiaryClient( 6936):     "location": "Authorization"
W/ApiaryClient( 6936):    }
W/ApiaryClient( 6936):   ],
W/ApiaryClient( 6936):   "code": 401,
W/ApiaryClient( 6936):   "message": "Login Required"
W/ApiaryClient( 6936):  }
W/ApiaryClient( 6936): }
,W/ApiaryClient( 6936): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6936): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4499732779107346516&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6936): Headers suppressed
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6936): Authentication error
E/BooksAccountManager( 6936): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6936): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 6936): null auth token
,I/qtaguid ( 6936): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 6936, getuid(): 10082
,I/qtaguid ( 6936): Untagging socket 34
,W/ApiaryClient( 6936): Error response from books API: {
W/ApiaryClient( 6936):  "error": {
W/ApiaryClient( 6936):   "errors": [
W/ApiaryClient( 6936):    {
W/ApiaryClient( 6936):     "domain": "global",
W/ApiaryClient( 6936):     "reason": "required",
W/ApiaryClient( 6936):     "message": "Login Required",
W/ApiaryClient( 6936):     "locationType": "header",
W/ApiaryClient( 6936):     "location": "Authorization"
W/ApiaryClient( 6936):    }
W/ApiaryClient( 6936):   ],
W/ApiaryClient( 6936):   "code": 401,
W/ApiaryClient( 6936):   "message": "Login Required"
W/ApiaryClient( 6936):  }
W/ApiaryClient( 6936): }
,W/ApiaryClient( 6936): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6936): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4499732779107346516&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6936): Headers suppressed
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  892): uri = 14 selection = getSealedState
,D/SecContentProvider2(  892): mCursor = null
D/SecContentProvider2(  892): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  892): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  892): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6936): Authentication error
E/BooksAccountManager( 6936): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6936): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 6936): null auth token
,I/qtaguid ( 6936): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 6936, getuid(): 10082
,I/qtaguid ( 6936): Untagging socket 34
,W/ApiaryClient( 6936): Error response from books API: {
W/ApiaryClient( 6936):  "error": {
W/ApiaryClient( 6936):   "errors": [
W/ApiaryClient( 6936):    {
W/ApiaryClient( 6936):     "domain": "global",
W/ApiaryClient( 6936):     "reason": "required",
W/ApiaryClient( 6936):     "message": "Login Required",
W/ApiaryClient( 6936):     "locationType": "header",
W/ApiaryClient( 6936):     "location": "Authorization"
W/ApiaryClient( 6936):    }
W/ApiaryClient( 6936):   ],
W/ApiaryClient( 6936):   "code": 401,
W/ApiaryClient( 6936):   "message": "Login Required"
W/ApiaryClient( 6936):  }
W/ApiaryClient( 6936): }
,W/ApiaryClient( 6936): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6936): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4499732779107346516&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6936): Headers suppressed
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,E/BooksSync( 6936): Soft error
E/BooksSync( 6936): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6936): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4499732779107346516&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6936): Headers suppressed
E/BooksSync( 6936): 
E/BooksSync( 6936): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 6936): Sync error
E/BooksSync( 6936): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6936): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4499732779107346516&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6936): Headers suppressed
E/BooksSync( 6936): 
E/BooksSync( 6936): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 6936): Finished books sync
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SyncManager(  892): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 202226, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  892): mCursor = null
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  892): SIOP:: AP = 290, PST = 297, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  892): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  892): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  892): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  892): Plugged
,I/MotionRecognitionService(  892): setPowerConnected  = true
,D/BatteryService(  892): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6543): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  892): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  287): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService(  892): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  892): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  892): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  892): Plugged
,I/MotionRecognitionService(  892): setPowerConnected  = true
,D/BatteryService(  892): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6543): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService(  892): [PWL] Off : 105s ago
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD ON
,E/Watchdog(  892): !@Sync 8
,D/SSRM:m  (  892): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  892): waitForAlarm result :4
,D/ConnectivityService(  892): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  892): SIOP:: AP = 290, PST = 291, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,D/BatteryService(  892): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  892): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  892): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  892): Plugged
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService(  892): stay LED for fully charged
,I/MotionRecognitionService(  892): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6543): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  892): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  892): !@Sync 9
,V/AlarmManager(  892): waitForAlarm result :8
,I/PowerManagerService(  892): [PWL] Off : 140s ago
,D/SSRM:m  (  892): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  287): DCD ON
,I/jxcore-log( 6210): Reconnected to the test server
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): --= Surplus to requirements =--
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): ****TEST TOOK:  ms ****
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6210): 
,D/BatteryService(  892): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  892): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  892): stay LED for fully charged
,D/BatteryService(  892): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  892):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  892): Plugged
I/MotionRecognitionService(  892): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6543): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AndroidRuntime( 8334): 
D/AndroidRuntime( 8334): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8334): CheckJNI is OFF
,D/AndroidRuntime( 8334): setted country_code = Germany
D/AndroidRuntime( 8334): setted countryiso_code = DE
,D/AndroidRuntime( 8334): setted sales_code = DBT
,D/AndroidRuntime( 8334): readGMSProperty: start
D/AndroidRuntime( 8334): readGMSProperty: already setted!!
D/AndroidRuntime( 8334): readGMSProperty: end
D/AndroidRuntime( 8334): addProductProperty: start
,E/AffinityControl( 8334): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8334): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  892): START PACKAGE DELETE: observer{13045977}
D/PackageManager(  892): pkg{<packageName>}
D/PackageManager(  892): user{0}
D/PackageManager(  892): caller{2000}
D/PackageManager(  892): flags{3}
,D/PersonaManagerService(  892): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PersonaManagerService(  892): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  892): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  892): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  892): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  892): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  892): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  892): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  892): getApplicationUninstallationEnabled
D/ApplicationPolicy(  892): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  892): !@killApplicatoin: 10200, uninstall pkg
,I/ActivityManager(  892): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
,I/ActivityManager(  892): Killing 6210:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
,I/ActivityManager(  892):   Force finishing activity ActivityRecord{764612c u0 com.test.thalitest/.MainActivity t27}
,D/FocusedStackFrame(  892): Set to : 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=13 Removed com.test.thalitest/com.test.thalitest.MainActivity (6/8)
,I/SurfaceFlinger(  249): id=13 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/WifiService(  892): Client connection lost with reason: 4
,W/PackageSettings(  892): Skipping PackageSetting{11508a65 com.example.hello/10201} due to missing metadata
,I/ActivityManager(  892): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
,D/ConnectivityService(  892): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1578): Explicit concurrent mark sweep GC freed 21930(1302KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/26MB, paused 494us total 37.449ms
,I/art     ( 4261): Explicit concurrent mark sweep GC freed 5131(283KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/24MB, paused 350us total 43.381ms
,E/SMD     (  287): DCD ON
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  892): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1832): mOCRHelper is null
,W/GeofencerStateMachine( 1597): Ignoring removeGeofence because network location is disabled.
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  ( 8366): MountEmulatedStorage()
E/Zygote  ( 8366): v2
I/libpersona( 8366): KNOX_SDCARD checking this for 10019
I/libpersona( 8366): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8366 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 8366): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8366): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/EnterpriseDeviceManagerService(  892): Package has changed for user 0
D/EnterpriseDeviceManagerService(  892): Admin package name: com.google.android.gms
,E/SELinux ( 8366): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/SecContentProvider2(  892): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  892): mCursor = null
,D/TimaKeyStoreProvider( 8366): TimaSignature is unavailable
,D/ActivityThread( 8366): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/SurfaceWidgetView( 1504): destroyHardwareResources():414938670
,V/WindowOrientationListener(  892): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  892): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  892): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  892): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  892): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager( 8366): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/Launcher( 1504): onRestart, Launcher: 455420699
D/Launcher( 1504): onStart, Launcher: 455420699
D/Launcher.HomeView( 1504): onStart
I/art     (  892): Explicit concurrent mark sweep GC freed 35888(2MB) AllocSpace objects, 35(755KB) LOS objects, 30% free, 36MB/52MB, paused 4.425ms total 291.074ms
D/ResourcesManager(  892): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  892): WaitForGcToComplete blocked for 165.749ms for cause Explicit
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2092): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2092): [237392/6] SurfaceWidget drawing first frame
D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/StatusBarManagerService(  892): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  892): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/StatusBarManagerService(  892): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/InputMethodManagerService(  892): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Books/Books.apk
,D/RegisteredServicesCache( 1473): empty dynamic service
,W/InputMethodManagerService(  892): Got RemoteException sending setActive(false) notification to pid 6210 uid 10200
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/KLMS-2.4.503: ( 8366): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/KLMS-2.4.503: ( 8366): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1456909086089
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/KLMS-2.4.503: ( 8366): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 8366): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/Timeline(  892): Timeline: Activity_windows_visible id: ActivityRecord{14085686 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t25} time:290167
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/elm:14451( 7524): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 7524): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14451( 7524): ElmAgentService : onCreate()
,D/elm:14451( 7524): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 7265): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver( 7265): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7265): onReceive() : package name is not s health. Return !!!
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/elm:14451( 7524): MainReceiver.listeningToPackageRemoved()
,D/elm:14451( 7524): MDMBridge.getInstance()
D/elm:14451( 7524): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14451( 7524): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 8386): MountEmulatedStorage()
I/libpersona( 8386): KNOX_SDCARD checking this for 1000
E/Zygote  ( 8386): v2
I/libpersona( 8386): KNOX_SDCARD not a persona
,D/RCPManagerService(  892): PackageReceiver onReceive()
,I/HarmonyEASService(  892): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/ActivityManager(  892): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8386 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 8386): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/KnoxMUMContainerPolicy(  892): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,I/SELinux ( 8386): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/elm:14451( 7524): ElmAgentService : onDestroy().
,E/SELinux ( 8386): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  892): Killing 6994:com.sec.android.soagent/u0a37 (adj 15): bgCount ##41
,D/BackupManagerService(  892): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/EnterpriseBillingPolicy(  892): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService(  892): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  892): uID is 10200
V/EnterpriseBillingPolicy(  892): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  892): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  892): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  892): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  892): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  892): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  892): getBillingProfileForVpnEngine - end - null
W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TaskPersister(  892): removeObsoleteFile: deleting file=27_task.xml
,D/TimaKeyStoreProvider( 8386): TimaSignature is unavailable
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ActivityThread( 8386): Added TimaKeyStore provider
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/art     (  892): Explicit concurrent mark sweep GC freed 12212(620KB) AllocSpace objects, 1(16KB) LOS objects, 30% free, 36MB/52MB, paused 7.336ms total 355.076ms
,D/ResourcesManager( 8386): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/libprocessgroup(  892): failed to open /acct/uid_10037/pid_6994/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_LOG( 8386): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8386): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8386): new DMDBOpenHelper instance
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/PCWCLIENTTRACE_PushUtil( 8386): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 8386): sales region : global
I/PCWCLIENTTRACE_PushUtil( 8386): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 8386): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Zygote  ( 8401): MountEmulatedStorage()
I/libpersona( 8401): KNOX_SDCARD checking this for 10038
E/Zygote  ( 8401): v2
I/libpersona( 8401): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=8401 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/PackageManager(  892): delete codoeFile: 
,D/PackageManager(  892): result of delete: 1{13045977}
,I/SELinux ( 8401): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/SELinux ( 8401): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager(  892): Killing 6097:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
D/ResourcesManager(  892): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/SELinux ( 8401): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/AndroidRuntime( 8334): Shutting down VM
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  892): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  892): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  892): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/TimaKeyStoreProvider( 8401): TimaSignature is unavailable
,D/ActivityThread( 8401): Added TimaKeyStore provider
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/libprocessgroup(  892): failed to open /acct/uid_10045/pid_6097/cgroup.procs: No such file or directory
W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager( 8401): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  892): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  892): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  892): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  892): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/SPPClientService( 8401): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8401): [PushClientApplication] Push log off : This is Ship build version
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/SPPClientService( 8401): PushLog.txt file is not deleted.
D/SPPClientService( 8401): PushLog.txt file is not deleted.
D/SPPClientService( 8401): ============PushLog. stop!
,W/ResourcesManager( 7897): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk,
,W/ResourcesManager( 7897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 8419): MountEmulatedStorage()
I/libpersona( 8419): KNOX_SDCARD checking this for 10038
E/Zygote  ( 8419): v2
I/libpersona( 8419): KNOX_SDCARD not a persona
,I/SELinux ( 8419): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8419): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8419): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager(  892): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8419 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 7312:com.android.mms/u0a50 (adj 15): bgCount ##41
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 8419): TimaSignature is unavailable
,D/ActivityThread( 8419): Added TimaKeyStore provider
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8419): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/CountryDetector(  892): No listener is left
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SPPClientService( 8419): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8419): [PushClientApplication] Push log off : This is Ship build version
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/libprocessgroup(  892): failed to open /acct/uid_10050/pid_7312/cgroup.procs: No such file or directory
,W/ResourcesManager( 7897): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
I/EventHub(  892): Removing device '/dev/input/event4' due to inotify event
W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/SPPClientService( 8419): PushLog.txt file is not deleted.
,D/SPPClientService( 8419): PushLog.txt file is not deleted.
D/SPPClientService( 8419): ============PushLog. stop!
,E/SQLiteLog( 8419): (14) cannot open file at line 32470 of [9491ba7d73]
E/SQLiteLog( 8419): (14) os_unix.c:32470: (2) open(/data/data/com.sec.spp.push/databases/push_noti_db) - 
E/SharedPreferencesImpl( 7897): Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,F/libc    ( 8419): Fatal signal 7 (SIGBUS), code 2, fault addr 0x73f74dc3 in tid 8419 (moteNotiProcess)
,I/EventHub(  892): Removing device '/dev/input/event5' due to inotify event
E/audit_log( 2123): File locking failed. error= Bad file number
,F/libc    ( 8419): Failed while talking to debuggerd: Broken pipe
,E/audit_log( 2123): File locking failed. error= Bad file number
,I/ActivityManager(  892): Process com.sec.spp.push:RemoteNotiProcess (pid 8419)(adj 0) has died(243,446)
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,I/EventHub(  892): Removing device '/dev/input/event6' due to inotify event
,I/Zygote  (  311): Process 8419 exited due to signal (7)
,E/Zygote  ( 8437): MountEmulatedStorage()
E/Zygote  ( 8437): v2
I/libpersona( 8437): KNOX_SDCARD checking this for 10045
I/libpersona( 8437): KNOX_SDCARD not a persona
,I/ActivityManager(  892): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=8437 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/EventHub(  892): Removing device '/dev/input/event7' due to inotify event
,I/SELinux ( 8437): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 8437): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/EventHub(  892): Removing device '/dev/input/event8' due to inotify event
,D/TimaKeyStoreProvider( 8437): TimaSignature is unavailable
,D/ActivityThread( 8437): Added TimaKeyStore provider
,I/EventHub(  892): Removing device '/dev/input/event9' due to inotify event
,D/ResourcesManager( 8437): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,W/ContextImpl( 8437): Unable to create files subdir /data/data/com.osp.app.signin/cache
E/ActivityThread( 8437): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  892): Removing device '/dev/input/event10' due to inotify event
,D/AndroidRuntime( 8437): Shutting down VM
,E/AndroidRuntime( 8437): FATAL EXCEPTION: main
E/AndroidRuntime( 8437): Process: com.osp.app.signin, PID: 8437
E/AndroidRuntime( 8437): java.lang.RuntimeException: Unable to instantiate application com.osp.app.signin.SamsungService: java.lang.ClassNotFoundException: Didn't find class "com.osp.app.signin.SamsungService" on path: DexPathList[[zip file "/system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8437): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
E/AndroidRuntime( 8437): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4980)
E/AndroidRuntime( 8437): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8437): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8437): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8437): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8437): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8437): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8437): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8437): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8437): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.osp.app.signin.SamsungService" on path: DexPathList[[zip file "/system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8437): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 8437): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 8437): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 8437): 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
E/AndroidRuntime( 8437): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
E/AndroidRuntime( 8437): 	... 10 more
E/AndroidRuntime( 8437): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 8437): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 8437): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 8437): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 8437): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 8437): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 8437): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 8437): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 8437): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 8437): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 8437): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
E/AndroidRuntime( 8437): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8437): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8437): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
E/AndroidRuntime( 8437): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
E/AndroidRuntime( 8437): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
E/AndroidRuntime( 8437): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 8437): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 8437): 		... 10 more
E/AndroidRuntime( 8437): 	Caused by: java.io.IOException: Failed to open oat file from ,dex location '/system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk'
E/AndroidRuntime( 8437): 		... 27 more
E/AndroidRuntime( 8437): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/Samsungservice2_xxhdpi/arm/Samsungservice2_xxhdpi.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 8437): 		... 27 more
E/AndroidRuntime( 8437): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 8437): 		... 27 more
E/AndroidRuntime( 8437): 	Suppressed: java.lang.ClassNotFoundException: com.osp.app.signin.SamsungService
E/AndroidRuntime( 8437): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 8437): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 8437): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 8437): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 8437): 		... 13 more
E/AndroidRuntime( 8437): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
F/libc    ( 8437): Fatal signal 7 (SIGBUS), code 2, fault addr 0x76b42230 in tid 8437 (.osp.app.signin)
E/audit_log( 2123): File locking failed. error= Bad file number
F/libc    ( 8437): Unable to open connection to debuggerd: Connection refused
,I/ActivityManager(  892): Process com.osp.app.signin (pid 8437)(adj 0) has died(244,446)
,I/EventHub(  892): Removing device '/dev/input/event11' due to inotify event
,F/libc    ( 2713): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7824c4a8 in tid 2713 (ndroid.contacts)
,F/libc    ( 2713): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2123): File locking failed. error= Bad file number
,I/Zygote  (  311): Process 8437 exited due to signal (7)
,I/ActivityManager(  892): Process com.android.contacts (pid 2713)(adj 0) has died(251,446)
,F/libc    ( 1808): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7819591e in tid 1808 (d.process.acore)
F/libc    ( 1808): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2123): File locking failed. error= Bad file number
E/audit_log( 2123): File locking failed. error= Bad file number
,I/Zygote  (  311): Process 2713 exited due to signal (7)
,I/ActivityManager(  892): Process android.process.acore (pid 1808)(adj 0) has died(257,446)
,E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  892): checkUser: useridlist=null, currentuser=0
,E/SharedPreferencesImpl( 7934): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml
,I/ActivityManager(  892): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8453 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/Zygote  ( 8453): MountEmulatedStorage()
E/Zygote  ( 8453): v2
I/libpersona( 8453): KNOX_SDCARD checking this for 10050
I/libpersona( 8453): KNOX_SDCARD not a persona
,I/Zygote  (  311): Process 1808 exited due to signal (7)
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,I/SELinux ( 8453): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
E/SELinux ( 8453): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL

```
