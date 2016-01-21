#### Test 56672827039a409_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
D/MyFiles ( 7259): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
E/installd(  304): system dir 0 : /system/app/
E/installd(  304): system dir 1 : /system/priv-app/
E/installd(  304): system dir 2 : /vendor/app/
E/installd(  304): system dir 3 : /oem/app/
I/TactileAssist(  901): enable value -1
I/TactileAssist(  901): internal enable value -1
I/TactileAssist(  901): intensity value -1
I/TactileAssist(  901): saveAppList value true
I/TactileAssist(  901): List of disabled apps :
--------- beginning of system
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7280): MountEmulatedStorage()
E/Zygote  ( 7280): v2
I/SELinux ( 7280): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7280): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7280): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/libpersona( 7280): KNOX_SDCARD checking this for 10057
I/libpersona( 7280): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7280 uid=10057 gids={50057, 9997, 3003, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 7280): TimaSignature is unavailable
D/ActivityThread( 7280): Added TimaKeyStore provider
D/ResourcesManager( 7280): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
D/PackageManager(  901): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
W/ResourcesManager( 7280): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 7280): onReceive() it will make start service
I/UpdateIcingCorporaServi( 1578): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/Compatibility( 7280): onHandleIntent()
E/Zygote  ( 7299): MountEmulatedStorage()
E/Zygote  ( 7299): v2
I/libpersona( 7299): KNOX_SDCARD checking this for 1000
I/libpersona( 7299): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7299 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/Compatibility( 7280): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10191, android.intent.extra.user_handle=0}]
I/SELinux ( 7299): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7299): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7299): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 7280): found: 2
D/TimaKeyStoreProvider( 7299): TimaSignature is unavailable
D/ActivityThread( 7299): Added TimaKeyStore provider
D/ResourcesManager( 7299): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
D/ResourcesManager( 1578): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/Compatibility( 7280): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7280): skipping ResolveInfo{39972d60 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7280): considering ResolveInfo{d71c219 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7280): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7280): enabling receiver ResolveInfo{1ae972de com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7280): enabling receiver ResolveInfo{c19bcbf com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7280): enabling receiver ResolveInfo{3931bf8c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7280): enabling receiver ResolveInfo{34d366d5 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/UpdateIcingCorporaServi( 1578): UpdateCorporaTask done [took 128 ms] updated apps [took 128 ms] 
D/Compatibility( 7280): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
W/ContextImpl( 7299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
I/ActivityManager(  901): Killing 6395:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7329): MountEmulatedStorage()
E/Zygote  ( 7329): v2
I/libpersona( 7329): KNOX_SDCARD checking this for 10097
I/libpersona( 7329): KNOX_SDCARD not a persona
D/AndroidRuntime( 7300): 
D/AndroidRuntime( 7300): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/ActivityManager(  901): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7329 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7300): CheckJNI is OFF
D/AndroidRuntime( 7300): setted country_code = Poland
D/AndroidRuntime( 7300): setted countryiso_code = PL
D/AndroidRuntime( 7300): setted sales_code = XEO
D/AndroidRuntime( 7300): readGMSProperty: start
D/AndroidRuntime( 7300): readGMSProperty: already setted!!
D/AndroidRuntime( 7300): readGMSProperty: end
D/AndroidRuntime( 7300): addProductProperty: start
I/SELinux ( 7329): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  901): failed to open /acct/uid_1000/pid_6395/cgroup.procs: No such file or directory
I/SELinux ( 7329): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7329): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager(  901): Killing 6431:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
D/TimaKeyStoreProvider( 7329): TimaSignature is unavailable
D/ActivityThread( 7329): Added TimaKeyStore provider
D/ResourcesManager( 7329): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
W/libprocessgroup(  901): failed to open /acct/uid_1000/pid_6431/cgroup.procs: No such file or directory
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
E/AffinityControl( 7300): AffinityControl: registerfunction enter
D/AndroidRuntime( 7300): Calling main entry com.android.commands.am.Am
D/DocsApplication( 7329): Installing DEX configuration.
E/PersonaManagerService(  901): inState():  stateMachine is null !!
V/ApplicationPolicy(  901): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  901): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  901): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/DexInstaller( 7329): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7329): Provided clientMode=RELEASE, packageInfo=PackageInfo{623ad63 com.google.android.apps.docs}
W/ActivityManager(  901): mDVFSHelper.acquire()
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/TAG     ( 7329): onCreate()
E/Zygote  ( 7353): MountEmulatedStorage()
E/Zygote  ( 7353): v2
I/libpersona( 7353): KNOX_SDCARD checking this for 10191
I/libpersona( 7353): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7353 uid=10191 gids={50191, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/CrossAppStateProvider( 7329): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/AndroidRuntime( 7300): Shutting down VM
I/SELinux ( 7353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7353): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7353): TimaSignature is unavailable
D/ActivityThread( 7353): Added TimaKeyStore provider
V/ActivityManager(  901): Display changed displayId=0
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7353): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SQLiteSecureOpenHelper( 3492): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3492): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
I/SurfaceFlinger(  259): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
I/SurfaceFlinger(  259): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
I/WebViewFactory( 7353): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7353): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7353): Loading: webviewchromium
I/LibraryLoader( 7353): Time to load native libraries: 2 ms (timestamps 7989-7991)
I/LibraryLoader( 7353): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7353): Binding Chromium to main looper Looper (main, tid 1) {3931bf8c}
I/LibraryLoader( 7353): Expected native library version number "",actual native library version number ""
I/chromium( 7353): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7353): Initializing chromium process, renderers=0
W/art     ( 7353): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7353): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7353): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7353): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/Adreno-EGL( 7353): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7353): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7353): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7353): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7353): Remote Branch: 
I/Adreno-EGL( 7353): Local Patches: 
I/Adreno-EGL( 7353): Reconstruct Branch: 
,W/chromium( 7353): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7353): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7353): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7353): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7353): CordovaWebView is running on device made by: samsung
,W/art     ( 7353): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 7353): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7353): performCreate Call secproduct feature valuefalse
,D/Activity( 7353): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7353): Render dirty regions requested: true
,D/ActivityManager(  901): post active user change for 0
,D/KnoxTimeoutHandler(  901): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  901): handleActiveUserChange for user 0
,I/SurfaceFlinger(  259): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,I/OpenGLRenderer( 7353): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7353): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7353): Enabling debug mode 0
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
D/InputMethodManagerService(  901): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,W/ActivityManager(  901): mDVFSHelper.release()
I/Timeline(  901): Timeline: Activity_windows_visible id: ActivityRecord{ae0c9b0 u0 com.test.thalitest/.MainActivity t10} time:108303
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,W/IInputConnectionWrapper( 7353): showStatusIcon on inactive InputConnection
,I/Timeline( 7353): Timeline: Activity_idle id: android.os.BinderProxy@310153af time:108307
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/JsMessageQueue( 7353): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7353): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359660032
I/chromium( 7353): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/chromium( 7353): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7353): 
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/GAV2    ( 7329): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/Zygote  ( 7424): MountEmulatedStorage()
I/libpersona( 7424): KNOX_SDCARD checking this for 10098
E/Zygote  ( 7424): v2
I/libpersona( 7424): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7424 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
I/art     (  325): Explicit concurrent mark sweep GC freed 8740(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 270us total 12.595ms
I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 257us total 7.872ms
I/SELinux ( 7424): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 8.270ms
I/SELinux ( 7424): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7424): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/FactoryTest( 6308): Not factory mode
D/FactoryTest( 6308): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 6308): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6308): still no open session command from host, so toast
W/ContextImpl( 6308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 6308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6308): Timeline: Activity_launch_request id:com.android.settings time:108794
E/PersonaManagerService(  901): inState():  stateMachine is null !!
V/ApplicationPolicy(  901): isApplicationStateBlocked userId 0 pkgname com.android.settings
I/ActivityManager(  901): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
W/ActivityManager(  901): mDVFSHelper.acquire()
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/TimaKeyStoreProvider( 7424): TimaSignature is unavailable
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ActivityThread( 7424): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
E/MTPRx   ( 6308): started activity for popup
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SQLiteSecureOpenHelper( 3492): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3492): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ResourcesManager( 7424): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ResourcesManager( 7424): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 6308): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager( 6308): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6308): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6308): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6308): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6308): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6308): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6308): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/SettingsReceiverActivity( 6308): PREF_DONT_ASK_AGAIN : true
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/InputMethodManagerService(  901): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  901): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@20c0f34b attribute=null, token = android.os.BinderProxy@2233bed1
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
V/BitmapFactory( 6308): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
D/SettingsReceiverActivity( 6308): dev.kiessupport is : TRUE
E/[CarMode]( 7424): [DLApplication]-onCreate: Applicatino Started!
D/Activity( 6308): performCreate Call secproduct feature valuefalse
D/Activity( 6308): performCreate Call debug elastic valuetrue
D/SampleAppCoreManager( 7424): SampleAppCoreManager VACVersion '2.2.0.11867'
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
I/VlingoAndroidCore( 7424): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ActivityManager(  901): post active user change for 0
D/KnoxTimeoutHandler(  901): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  901): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
I/Timeline( 7353): Timeline: Activity_idle id: android.os.BinderProxy@310153af time:109024
E/Zygote  ( 7445): MountEmulatedStorage()
E/Zygote  ( 7445): v2
I/libpersona( 7445): KNOX_SDCARD checking this for 10032
I/libpersona( 7445): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7445 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
I/SELinux ( 7445): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7445): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7445): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7445): TimaSignature is unavailable
D/ActivityThread( 7445): Added TimaKeyStore provider
D/ResourcesManager( 7445): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/ResourcesManager( 7445): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/GAV2    ( 7329): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  901): Killing 5558:com.sec.android.app.samsungapps/u0a39 (adj 15): bgCount ##41
I/System.out( 7445): Inside onCreate() of WakeupTriggerProvide
I/System.out( 7445): Inside WakeupProvider
E/DatabaseUtils( 7445): Writing exception to parcel
E/DatabaseUtils( 7445): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7445): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7445): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7445): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7445): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7445): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7445): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7445): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7445): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7445): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7445): 	at android.os.Binder.execTransact(Binder.java:446)
I/VlingoApplication( 7445): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
W/System.err( 7424): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/libprocessgroup(  901): failed to open /acct/uid_10039/pid_5558/cgroup.procs: No such file or directory
I/VlingoAndroidCore( 7445): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
W/System.err( 7424): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7424): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7424): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7424): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7424): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7424): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7424): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7424): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7424): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7424): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7424): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7424): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7424): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7424): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7424): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7424): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7424): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7424): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7424): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7424): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7424): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7424): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7424): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7424): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7424): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7424): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7424): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7424): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7424): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7424): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7424): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 7424): [DLApplication]-Init Called!:false
E/[CarMode]( 7424): [DLApplication]-Init Started!:true
I/[CarModeFW]( 7424): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7424): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7424): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7424): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7424): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7424): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7424): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7424): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7424): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7424): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7424): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7424): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7424): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7424): ### com.android.internal.os.ZygoteInit::main(1194)
I/MessageDataHandler( 7424): initialize
D/VlingoApplication( 7445): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 7445): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
D/[CarModeFW]( 7424): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 7424): CDH-initiazlieCaches : after sync
D/[CarModeFW]( 7424): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7424): CDH-ContactDataHandler initiazlieCaches time : 19
D/[CarModeFW]( 7424): CDH-initiazlieCaches : end sync
D/[CarModeFW]( 7424): DrivingManager-initialize...
I/SensorService(  901): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  901): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  901): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/MediaPlayer( 7424): Need to enable context aware info
V/MediaPlayer-JNI( 7424): native_setup
V/MediaPlayer( 7424): constructor
,V/MediaPlayer( 7424): setListener
,E/MediaPlayer-JNI( 7424): QCMediaPlayer mediaplayer NOT present
,D/[CarModeFW]( 7424): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 7424): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode]( 7424): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarModeFW]( 7424): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1453396604396
D/[CarModeFW]( 7424): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1453396604398
D/[CarModeFW]( 7424): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1453396604400
D/[CarModeFW]( 7424): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7424): RecommendHandler-selection = type = '3'
D/[CarModeFW]( 7424): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1453396604402
D/TP/SmsProvider( 1471): query,matched:2, calling pid = 7424
D/TP/SmsProvider( 1471): match 2:Elapsed time : 1.646 ms
D/[CarModeFW]( 7424): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1453396604408
D/[CarModeFW]( 7424): CDH-buildContactCacheWireFrame : cur len =0
D/[CarMode]( 7424): [DLServiceManager]-requestRecommendedLocationList
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/[CarModeFW]( 7424): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1453396604411
D/TP/SmsProvider( 1471): query,matched:2, calling pid = 7424
D/TP/SmsProvider( 1471): match 2:Elapsed time : 2.966 ms
I/[CarMode]( 7424): [LogNotNull]-Package name is: com.google.android.apps.maps
E/Zygote  ( 7478): MountEmulatedStorage()
I/libpersona( 7478): KNOX_SDCARD checking this for 10019
E/Zygote  ( 7478): v2
I/libpersona( 7478): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7478 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,E/[CarMode]( 7424): [DLApplication]-Init End!:true
,I/SELinux ( 7478): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/MessageDataHandler( 7424):  getInboxList smsCursor : 54
,I/SELinux ( 7478): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7478): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7486): MountEmulatedStorage()
E/Zygote  ( 7486): v2
I/libpersona( 7486): KNOX_SDCARD checking this for 10003
I/libpersona( 7486): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7486 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 7486): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/[CarModeFW]( 7424): CDH-buildContactCacheWireFrame : cur len =0
I/SELinux ( 7486): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7486): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7478): TimaSignature is unavailable
,D/ActivityThread( 7478): Added TimaKeyStore provider
,D/TP/MmsProvider( 1471): Query uri=content://mms, match=0, calling pid = 7424
,E/SMD     (  290): DCD ON
,D/TP/MmsProvider( 1471): Query uri=content://mms/inbox, match=2, calling pid = 7424
,D/[CarModeFW]( 7424): RecommendHandler-selection = type = '3'
,D/MessageDataHandler( 7424):  getInboxList mmsCursor : 71
,I/MessageDataHandler( 7424): getUnreadMessageCount :0
,D/TimaKeyStoreProvider( 7486): TimaSignature is unavailable
,D/ActivityThread( 7486): Added TimaKeyStore provider
,D/[CarModeFW]( 7424): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 125
,D/MessageDataHandler( 7424):  getInboxList mms,sms cursor join : 13
,D/TP/MmsSmsProvider( 1471): query,matched:0, calling pid = 7424
V/TP/MmsSmsProvider( 1471): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1471): match 0:Elapsed time : 0.876 ms
,D/TP/MmsSmsProvider( 1471): query,matched:13, calling pid = 7424
,D/ResourcesManager( 7478): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,D/TP/MmsSmsProvider( 1471): match 13:Elapsed time : 1.212 ms
,D/MessageDataHandler( 7424):  getInboxList address cursor : 4
,D/ResourcesManager( 7486): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/TP/MmsSmsProvider( 1471): query,matched:0, calling pid = 7424
V/TP/MmsSmsProvider( 1471): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1471): match 0:Elapsed time : 1.312 ms
,D/MessageDataHandler( 7424):  getInboxList thread cursor : 5
,D/MessageDataHandler( 7424):  thread, addr result: 1
,I/[CarModeFW]( 7424): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 155
I/[CarModeFW]( 7424): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7424): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 155
D/[CarMode]( 7424): [DLApplication]-GooglePlayServices SUCCESS.
,E/[CarMode]( 7424): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/UserAnalysis.PlaceProvider( 7486): PlaceProvider onCreate()
,I/UpdateManagerReceiver( 7424): Intent : android.intent.action.PACKAGE_ADDEDThu Jan 21 18:16:44 GMT+01:00 2016
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7509): MountEmulatedStorage()
E/Zygote  ( 7509): v2
I/libpersona( 7509): KNOX_SDCARD checking this for 1000
I/libpersona( 7509): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7509 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 5977:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
,D/UserAnalysis.SecureDbManager( 7486): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 7486): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7486): Create SecureDbHelper
,I/SELinux ( 7509): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7509): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7509): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/[CarModeFW]( 7424): PushMessageService-onCreate
,I/ActivityManager(  901): Killing 6241:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
,I/ActivityManager(  901): Killing 6176:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##42
,I/ActivityManager(  901): Killing 5745:com.google.android.gm/u0a113 (adj 15): bgCount ##43
,I/SQLiteSecureOpenHelper( 7486): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7486): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7486): Open Place.db in secure mode
,W/libprocessgroup(  901): failed to open /acct/uid_10167/pid_5977/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7509): TimaSignature is unavailable
,D/ActivityThread( 7509): Added TimaKeyStore provider
,I/SQLiteSecureOpenHelper( 7486): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7486): ...getDatabaseLocked(b,b,pwd)
,D/IntelligenceServiceApplication( 7486): onCreate()
,D/[CarModeFW]( 7424): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7424): PushMessageService-registerPushMessageServiceListener
,I/art     (  901): Explicit concurrent mark sweep GC freed 237387(16MB) AllocSpace objects, 3(4MB) LOS objects, 31% free, 35MB/51MB, paused 1.357ms total 102.429ms
,D/[CarModeFW]( 7424): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 404
,D/[CarModeFW]( 7424): MyPlaceProvider-+++Begin print all data in content provider+++
,D/[CarModeFW]( 7424): MyPlaceProvider-=============
,D/[CarModeFW]( 7424): MyPlaceProvider-=============
D/[CarModeFW]( 7424): MyPlaceProvider-=============
,D/[CarModeFW]( 7424): MyPlaceProvider-=============
D/[CarModeFW]( 7424): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7424): MyPlaceProvider-==============
,D/[CarModeFW]( 7424): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7424): MyPlaceProvider-==============
D/[CarModeFW]( 7424): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7424): MyPlaceProvider-==============
D/[CarModeFW]( 7424): MyPlaceProvider-latitude is not valid
,D/ResourcesManager( 7509): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,I/[CarModeFW]( 7424): -[snowdeer] Rec : Missed Call : 407
,D/[CarModeFW]( 7424): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 401
,D/[CarMode]( 7424): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@18220a92, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@16364020] LOCATIONS
,W/ContextImpl( 7509): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7509): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,E/Zygote  ( 7526): MountEmulatedStorage()
E/Zygote  ( 7526): v2
I/libpersona( 7526): KNOX_SDCARD checking this for 10111
I/libpersona( 7526): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7526 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7526): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/[CarModeFW]( 7424): -[snowdeer] Rec : Favorite : 72
,E/FilterInstaller( 7509): There is no requred permission
,I/[CarModeFW]( 7424): -[snowdeer] Rec : CallLog : 8
,D/TimaKeyStoreProvider( 7526): TimaSignature is unavailable
,D/ActivityThread( 7526): Added TimaKeyStore provider
,I/ActivityManager(  901): Killing 6136:com.google.android.music:main/u0a125 (adj 15): bgCount ##41
,I/[CarModeFW]( 7424): -[snowdeer] Rec : Schedule : 20
,I/[CarModeFW]( 7424): -[snowdeer] Rec : During DL app : 1
,I/[CarModeFW]( 7424): -[snowdeer] Rec : getContactListFromHashMap - core : 0
,I/[CarModeFW]( 7424): -[snowdeer] Rec : Location Sharing : 3
,I/[CarModeFW]( 7424): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 7424): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7424): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7424): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 7424): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 7424): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 529
I/[CarModeFW]( 7424): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7424): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7424): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 526
D/ResourcesManager( 7526): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,W/libprocessgroup(  901): failed to open /acct/uid_10004/pid_6176/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_10043/pid_6241/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_10113/pid_5745/cgroup.procs: No such file or directory
,D/PackageIntentReceiver( 7526): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 7526): Not GearManger package! 
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7541): MountEmulatedStorage()
E/Zygote  ( 7541): v2
I/libpersona( 7541): KNOX_SDCARD checking this for 10117
I/libpersona( 7541): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7541 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 5499:com.google.android.apps.plus/u0a134 (adj 15): bgCount ##41
,I/SELinux ( 7541): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7541): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/SSRM:m  (  901): SIOP:: AP = 380, PST = 364, CUR = 450
W/libprocessgroup(  901): failed to open /acct/uid_10125/pid_6136/cgroup.procs: No such file or directory
,E/SELinux ( 7541): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  901): failed to open /acct/uid_10134/pid_5499/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 7541): TimaSignature is unavailable
D/ActivityThread( 7541): Added TimaKeyStore provider
D/ResourcesManager( 7541): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
W/ResourcesManager( 7541): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/MagazineService Version( 7541): Magazine-Administrator: 11
D/MagazineService Version( 7541): Magazine-Provider: 14
D/MagazineService Version( 7541): Magazine-Channel: 14
D/HeadlinesChannelApplication( 7541): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 7541): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
I/MagazineService::MagazineService( 7541): [onHandleIntent] ACTION_PACKAGE_INSTALLED
E/Zygote  ( 7557): MountEmulatedStorage()
I/libpersona( 7557): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7557): v2
I/libpersona( 7557): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7557 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/MagazineService::MagazineService( 7541): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/SELinux ( 7557): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7557): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7557): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  901): Killing 6615:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
D/TimaKeyStoreProvider( 7557): TimaSignature is unavailable
D/ActivityThread( 7557): Added TimaKeyStore provider
D/ResourcesManager( 7557): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7572): MountEmulatedStorage()
E/Zygote  ( 7572): v2
I/libpersona( 7572): KNOX_SDCARD checking this for 1000
I/libpersona( 7572): KNOX_SDCARD not a persona
W/libprocessgroup(  901): failed to open /acct/uid_10011/pid_6615/cgroup.procs: No such file or directory
I/ActivityManager(  901): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7572 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  901): Killing 6447:com.android.vending/u0a29 (adj 15): bgCount ##41
I/System.out( 7445): INFO:Resource not found:/Common.properties Using default values
I/SELinux ( 7572): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7572): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7572): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/jxcore-log( 7353): Initializing JXcore engine
W/jxcore-log( 7353): JXcore engine is ready
D/TimaKeyStoreProvider( 7572): TimaSignature is unavailable
D/ActivityThread( 7572): Added TimaKeyStore provider
D/ResourcesManager( 7572): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
W/libprocessgroup(  901): failed to open /acct/uid_10029/pid_6447/cgroup.procs: No such file or directory
E/auditd  ( 2116): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  901): Got Modify Event and sending Denial Intent foraudit.log
D/AcmsPackageEventListener( 7572): Received: android.intent.action.PACKAGE_ADDED
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 7572): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
W/jxcore-log( 7353): Starting JXcore engine
E/Zygote  ( 7589): MountEmulatedStorage()
E/Zygote  ( 7589): v2
I/libpersona( 7589): KNOX_SDCARD checking this for 10134
I/libpersona( 7589): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7589 uid=10134 gids={50134, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/SecurityLogAgent:SEDenialService(  901): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
I/ActivityManager(  901): Killing 6765:com.sec.android.fotaclient/u0a10 (adj 15): bgCount ##41
I/SELinux ( 7589): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7589): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7589): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/AcmsService( 7572): Enter Oncreate
D/AcmsServiceMonitor( 7572): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 7572): creating AcmsCore
D/AcmsCore( 7572): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7572): AcmsCore
D/TimaKeyStoreProvider( 7589): TimaSignature is unavailable
D/AcmsCore( 7572): init
D/AcmsCore( 7572): Looper handler is not null
D/AcmsCore( 7572): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7572): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7572): Incrementing - Counter value: 1
D/AcmsCore( 7572): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 7572): onStartCommand
D/AcmsService( 7572): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 7572): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7572): Incrementing - Counter value: 2
D/AcmsService( 7572): Incremented Counter Value : onStartCommand
D/ActivityThread( 7589): Added TimaKeyStore provider
D/AcmsCertificateMngr( 7572): AcmsCertificateMngr
D/AcmsRevocationMngr( 7572): AcmsRevocationMngr
D/ActivityThread( 7572): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/ResourcesManager( 7589): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
W/ResourcesManager( 7589): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/libprocessgroup(  901): failed to open /acct/uid_10010/pid_6765/cgroup.procs: No such file or directory
W/jxcore-log( 7353): Platform android
W/jxcore-log( 7353): 
W/jxcore-log( 7353): Process ARCH arm
W/jxcore-log( 7353): 
D/AcmsService( 7572): Inside handle Intent
D/AcmsService( 7572): App added - package name: com.test.thalitest
D/AcmsCore( 7572): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7572): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7572): Incrementing - Counter value: 3
D/AcmsCore( 7572): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7572): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7572): Decrementing - Counter value: 2
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7620): MountEmulatedStorage()
E/Zygote  ( 7620): v2
I/libpersona( 7620): KNOX_SDCARD checking this for 10165
I/libpersona( 7620): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7620 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 7353): JXcore Cordova bridge is ready!
I/jxcore-log( 7353): 
,W/jxcore-log( 7353): JXcore engine is started
,I/SELinux ( 7620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SELinux ( 7620): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 7620): TimaSignature is unavailable
,D/ActivityThread( 7620): Added TimaKeyStore provider
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager( 7620): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 7620): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7638): MountEmulatedStorage()
E/Zygote  ( 7638): v2
I/libpersona( 7638): KNOX_SDCARD checking this for 10169
I/libpersona( 7638): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7638 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
,I/art     (  325): Explicit concurrent mark sweep GC freed 8761(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 274us total 12.638ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.883ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.626ms
,I/SELinux ( 7638): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7638): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7638): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/jxcore-log( 7353): Toggling radios to true
I/jxcore-log( 7353): 
,D/BluetoothAdapter( 7353): enable()
,D/BluetoothAdapter( 7353): enable(): BT is already enabled..!
,D/WifiService(  901): New client listening to asynchronous messages
,I/WifiManager( 7353): packageName : com.test.thalitest
,D/SecContentProvider(  901): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  901): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  901): mCursor = null
D/TimaKeyStoreProvider( 7638): TimaSignature is unavailable
D/WifiService(  901): setWifiEnabled: true pid=7353, uid=10191
E/WifiService(  901): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  901): Permission Denial: getCurrentUser() from pid=7353, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
D/ActivityThread( 7638): Added TimaKeyStore provider
,W/WifiService(  901): Failed getting userId using ActivityManagerNative
W/WifiService(  901): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7353, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  901): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  901): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  901): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  901): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  901): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  901): name = wifi_on
,I/WifiService(  901): disconnect: pid=7353, uid=10191
,I/jxcore-log( 7353): Radios toggled
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): My device name is: samsung-SM-G900F
I/jxcore-log( 7353): 
I/wpa_supplicant( 1274): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,D/ResourcesManager( 7638): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,I/wpa_supplicant( 1274): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1274): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1274): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  901): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1274): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1274): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1274): Disconnected - do not scan
I/wpa_supplicant( 1274): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  901): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  901): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  901): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  901): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  901): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  901): do suspend true
,D/WifiP2pService(  901): InactiveState{ what=143375 }
,D/CommandListener(  284): Clearing all IP addresses on wlan0
,D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NativeCrypto( 2185): Read error: ssl=0x9b8e2e00: I/O error during system call, Connection timed out
,E/SQLiteLog( 7638): (284) automatic index on shooting_modes(title_id)
,V/NativeCrypto( 2185): SSL shutdown failed: ssl=0x9b8e2e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  901): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/ConnectivityService(  901): updateNetworkInfo()
,D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): ignoring duplicate network state non-change
,I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
,D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/ConnectivityService(  901): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Validated
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,E/WifiStateMachine(  901): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1274): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1274): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1274): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1274): First Scan Start
,I/wpa_supplicant( 1274): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  901): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  901): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  901): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  901): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  901): do suspend true
,D/WifiP2pService(  901): InactiveState{ what=143375 }
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
,E/Zygote  ( 7657): MountEmulatedStorage()
,E/Zygote  ( 7657): v2
I/libpersona( 7657): KNOX_SDCARD checking this for 10029
I/libpersona( 7657): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7657 uid=10029 gids={50029, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 6782:com.samsung.klmsagent/u0a18 (adj 15): bgCount ##41
,D/ConnectivityService(  901): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  901): Not allowed due to - mEnabled false
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  901): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  901): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CommandListener(  284): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Disconnected - quitting
,E/WifiStateMachine(  901): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiStateMachine(  901): updateConfiguredNetworkExpiration - currTime: 1453396606241
D/WifiStateMachine(  901): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/ConnectivityService(  901): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
,E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  901): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/CSLegacyTypeTracker(  901): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  901): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  901): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  901): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  901): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  901): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/ConnectivityService(  901): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  901): setDetailed state send new extra info"NG700"
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NetworkStats(  901): updateIfacesLocked()
V/NetworkStats(  901): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
,D/NetworkStatsFactory(  901): UpdateStatsForKnox
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityService(  901): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,V/NetworkStats(  901): performPollLocked() took 5ms
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,I/SELinux ( 7657): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7657): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7657): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524292
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityManager.CallbackHandler( 2539): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1471): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1183): updateDataNetType()
D/StatusBar.NetworkController( 1183): NoService, mRoamingIconId = 0
D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
E/StatusBar.NetworkController( 1183): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1183): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
V/NetworkStats(  901): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,D/TimaKeyStoreProvider( 7657): TimaSignature is unavailable
D/ActivityThread( 7657): Added TimaKeyStore provider
W/libprocessgroup(  901): failed to open /acct/uid_10018/pid_6782/cgroup.procs: No such file or directory
D/ResourcesManager( 7657): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/Finsky  ( 7657): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7657): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7657): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7657): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7657): Skipping gmscore version check
,D/Finsky  ( 7657): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7657): [1] Libraries$2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 2539): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/Finsky  ( 7657): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ChimeraCfgMgr( 2539): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2539): Loading module APK com.google.android.play.games
,D/Finsky  ( 7657): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 7657): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ResourcesManager( 2539): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/AcmsKeyStoreHelper( 7572):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 7572): Key Store exist
,I/AcmsKeyStoreHelper( 7572): Hence loading the keystore file
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  901): updateDataUsageMap
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/Tethering(  901): MasterInitialState.processMessage what=3
,D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
I/CLocInfoService(  901): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  901): CLoinfo wifi false
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 1950): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_DM  ( 3700): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/SLocation(  901): No Active Data Connection
I/DBG_DM  ( 3700): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/AcmsKeyStoreHelper( 7572):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 7572): getKeyStoreForApplication success 
D/AcmsCore( 7572): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7572): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7572): Decrementing - Counter value: 1
D/AcmsCore( 7572): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 7572): This is NOT a valid MirrorLink app
D/AcmsCore( 7572): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7572): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7572): Decrementing - Counter value: 0
,D/AcmsServiceMonitor( 7572): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7572): getSvcCounter - Counter value: 0
,D/AcmsService( 7572): Enter onDestroy
I/AcmsService( 7572): cleanUp(): inside service clean up
D/AcmsCore( 7572): AcmsCore: inside DeInit
D/AcmsCore( 7572): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7572): AcmsCertificateMngr: inside cleanup
,D/AcmsRevocationMngr( 7572): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7572): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7572): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7572): getSvcCounter - Counter value: 0
,D/AcmsService( 7572): killing acms process
I/Process ( 7572): Sending signal. PID: 7572 SIG: 9
,W/ActivityManager(  901): mDVFSHelper.release()
,D/ChimeraCfgMgr( 2539): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2539): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2539): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/ActivityManager(  901): Process ACMS.Process (pid 7572)(adj 0) has died(62,603)
,D/AsyncTaskServiceImpl( 2539): Submit a task: k
,D/ChimeraCfgMgr( 2539): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 2539): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2539): Processing package: com.test.thalitest
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7722): MountEmulatedStorage()
,E/Zygote  ( 7722): v2
I/libpersona( 7722): KNOX_SDCARD checking this for 10039
I/libpersona( 7722): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7722 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/GassUtils( 2539): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
D/k       ( 2539): Found info for package com.test.thalitest in db.
,I/SELinux ( 7722): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7722): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7722): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7722): TimaSignature is unavailable
,D/ActivityThread( 7722): Added TimaKeyStore provider
,W/BaseAppContext( 2539): Using Auth Proxy for data requests.
,W/BaseAppContext( 2539): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 2539): cleanUpNonGplusAccounts done.
,D/ResourcesManager( 7722): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,W/BaseAppContext( 2539): Using Auth Proxy for data requests.
,W/BaseAppContext( 2539): Using Auth Proxy for data requests.
,W/BaseAppContext( 2539): Using Auth Proxy for data requests.
,W/BaseAppContext( 2539): Using Auth Proxy for data requests.
,D/BootupListener( 1471): ACTION_DRIVELINK
,D/SettingsProvider(  901): name = drivelink_navigation
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1001
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  901): ret = -1
D/BootupListener( 1471): NAVI : com.google.android.apps.maps
,D/SettingsProvider(  901): name = internet_call_settings_visibility
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1001
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SecurityLogAgent( 6924):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6924):  SeDenialReceiver : File path = null
,I/Hs20UtilService( 1318): Starting #6
,I/Hs20UtilService( 1318): Message received 5007
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1318): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1318): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 1318): Starting #7
,I/Hs20UtilService( 1318): Message received 5007
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1318): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1318): MountReceiver.mPrefHandler - 7002
,I/PCWCLIENTTRACE_PushUtil( 7169): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7169): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7169): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7169): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_SYSTEMReceiver( 7169): noConnectivity : true
,E/Zygote  ( 7742): MountEmulatedStorage()
E/Zygote  ( 7742): v2
I/libpersona( 7742): KNOX_SDCARD checking this for 10125
I/libpersona( 7742): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7742 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  901): Explicit concurrent mark sweep GC freed 37806(2MB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 35MB/51MB, paused 1.564ms total 98.556ms
,I/SELinux ( 7742): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7742): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7742): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1274): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 1274): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1274): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1274): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  901): [1,453,396,607,273 ms] noteScanEnd no scan source
,E/WifiStateMachine(  901): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@388c928b sup_state=SCANNING debouncing=false
,I/CLocInfoService(  901): External Intent Received android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  901): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  901): setDetailed state send new extra info0x
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,D/TimaKeyStoreProvider( 7742): TimaSignature is unavailable
,D/ActivityThread( 7742): Added TimaKeyStore provider
,I/ActivityManager(  901): Killing 6797:com.sec.android.soagent/u0a36 (adj 15): bgCount ##41
,D/ResourcesManager( 7742): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BaseAppContext( 2539): Using Auth Proxy for data requests.
,I/wpa_supplicant( 1274): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1274): Associated with C0.AA.48
,E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  901): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  901): mCursor = null
,I/wpa_supplicant( 1274): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  901): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  901): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,I/wpa_supplicant( 1274): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1274): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1274): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1274): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1274): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1274): Blacklist: Clear (temp) 
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  901): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  901): Network connection established
D/WifiNative-HAL(  901): callSECApiVoid - ID [50]
E/WifiStateMachine(  901): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
W/libprocessgroup(  901): failed to open /acct/uid_10036/pid_6797/cgroup.procs: No such file or directory
E/WifiStateMachine(  901): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  901): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  901): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  901): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  901): Got NetworkAgent Messenger
D/ConnectivityService(  901): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  901): NetworkAgent connected
,E/WifiStateMachine(  901): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  901): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  901): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  284): Setting iface cfg
,E/WifiStateMachine(  901): Start Dhcp Watchdog 2
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  901): mCursor = null
,E/WifiStateMachine(  901): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  901): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/MusicStore( 7742): Database version: 104
,E/WifiStateMachine(  901): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  901): do suspend false
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
,D/WifiP2pService(  901): InactiveState{ what=143375 }
,D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
,D/SecContentProvider2(  901): mCursor = null
,D/ResourcesManager( 7742): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7742): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7742): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/SMD     (  290): DCD ON
,V/JNIHelp ( 7742): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7742): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7742): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@83c2d9e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7742): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7742): GMSCore installation verified
,I/ConfigStore( 7742): Config Database version: 1
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7742): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7742): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7742): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  299): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  901): getStreamVolume 3 index 0
,E/dhcpcd  ( 7773): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/MediaRouter( 7742): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/dhcpcd  ( 7773): version 5.5.6 starting
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/dhcpcd  ( 7773): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Zygote  ( 7775): MountEmulatedStorage()
E/Zygote  ( 7775): v2
I/libpersona( 7775): KNOX_SDCARD checking this for 10002
I/libpersona( 7775): KNOX_SDCARD not a persona
,W/art     ( 2539): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 165.985ms
,I/ActivityManager(  901): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7775 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 7773): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7773): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7773): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7773): bssid match
,I/dhcpcd  ( 7773): wlan0: rebinding lease of 192.168.1.136
,I/SELinux ( 7775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7775): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7742): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager(  901): Killing 6831:com.samsung.android.scloud.sync/u0a66 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7775): TimaSignature is unavailable
,D/ActivityThread( 7775): Added TimaKeyStore provider
,D/ResourcesManager( 7775): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,W/libprocessgroup(  901): failed to open /acct/uid_10066/pid_6831/cgroup.procs: No such file or directory
,I/ActivityManager(  901): Killing 6847:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): bgCount ##41
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7799): MountEmulatedStorage()
I/libpersona( 7799): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7799): v2
I/libpersona( 7799): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7799 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7799): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ChimeraCfgMgr( 2539): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2539): Module APK com.google.android.play.games already loaded
,D/TimaKeyStoreProvider( 7799): TimaSignature is unavailable
,D/ActivityThread( 7799): Added TimaKeyStore provider
,W/libprocessgroup(  901): failed to open /acct/uid_10070/pid_6847/cgroup.procs: No such file or directory
,D/ResourcesManager( 7799): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7799): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7799): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/Icing   ( 2539): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,D/ResourcesManager( 2539): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/DIAGMON_AGENT( 7799): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7799): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/Icing   ( 2539): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,I/DIAGMON_AGENT( 7799): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7799): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7818): MountEmulatedStorage()
E/Zygote  ( 7818): v2
I/libpersona( 7818): KNOX_SDCARD checking this for 10010
I/libpersona( 7818): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7818 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7818): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7818): TimaSignature is unavailable
,D/ActivityThread( 7818): Added TimaKeyStore provider
,D/ResourcesManager( 7818): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  901): Killing 6865:com.sec.android.app.clockpackage/u0a90 (adj 15): bgCount ##41
,I/FOTA_Client( 7818): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7818): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7818): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7841): MountEmulatedStorage()
E/Zygote  ( 7841): v2
I/libpersona( 7841): KNOX_SDCARD checking this for 10018
I/libpersona( 7841): KNOX_SDCARD not a persona
,W/libprocessgroup(  901): failed to open /acct/uid_10090/pid_6865/cgroup.procs: No such file or directory
,I/ActivityManager(  901): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7841 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 6880:com.sec.esdk.elm/u0a103 (adj 15): bgCount ##41
,I/SELinux ( 7841): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7841): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7841): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7841): TimaSignature is unavailable
,D/ActivityThread( 7841): Added TimaKeyStore provider
,D/ResourcesManager( 7841): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7841): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7841): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453396608461
,I/KLMS-2.4.503: ( 7841): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7841): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7841): StateImplV2(): networkChangeListener().END
,W/libprocessgroup(  901): failed to open /acct/uid_10103/pid_6880/cgroup.procs: No such file or directory
,I/ActivityManager(  901): Killing 6901:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7858): MountEmulatedStorage()
E/Zygote  ( 7858): v2
I/libpersona( 7858): KNOX_SDCARD checking this for 10036
,I/libpersona( 7858): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7858 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7858): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7858): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7858): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  901): Killing 5587:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7858): TimaSignature is unavailable
D/ActivityThread( 7858): Added TimaKeyStore provider
,D/ResourcesManager( 7858): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7858): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,W/libprocessgroup(  901): failed to open /acct/uid_10112/pid_6901/cgroup.procs: No such file or directory
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7206): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6813): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6813): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6813): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 6813): [SLFUCHKMGR] constructor called
,W/libprocessgroup(  901): failed to open /acct/uid_10148/pid_5587/cgroup.procs: No such file or directory
,I/SA      ( 6813): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6813): [OR] == isSIMCardReady false ==
,I/SA      ( 6813): [SCU] == networkStateCheck == false
I/SA      ( 6813): [OR] onReceive END
,E/SPPClientService( 7206): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7876): MountEmulatedStorage()
,E/Zygote  ( 7876): v2
I/libpersona( 7876): KNOX_SDCARD checking this for 10070
I/libpersona( 7876): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7876 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7876): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7876): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  901): Killing 4624:com.android.calendar/u0a149 (adj 15): bgCount ##41
,E/SELinux ( 7876): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7876): TimaSignature is unavailable
,D/ActivityThread( 7876): Added TimaKeyStore provider
,D/ResourcesManager( 7876): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7876): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7876): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7876): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7876): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7876): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7876): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7876): [KK AccuPhone]>>> ==============================================================================================
,W/libprocessgroup(  901): failed to open /acct/uid_10149/pid_4624/cgroup.procs: No such file or directory
,D/comsamsunglog( 7876): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7876): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7876): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7876): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  901): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 10070
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7876): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7876): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7876): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7876): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7876): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7876): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7876): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7876): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/GAV2    ( 7329): Thread[GAThread,5,main]: No campaign data found.
,D/accuweather( 7876): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7876): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  901): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  901): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/Zygote  ( 7895): MountEmulatedStorage()
E/Zygote  ( 7895): v2
I/libpersona( 7895): KNOX_SDCARD checking this for 1000
I/libpersona( 7895): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7895 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 6941:com.sec.android.app.taskmanager/u0a175 (adj 15): bgCount ##41
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/SELinux ( 7895): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7895): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7895): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 7773): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,D/TimaKeyStoreProvider( 7895): TimaSignature is unavailable
,D/ActivityThread( 7895): Added TimaKeyStore provider
,D/ResourcesManager( 7895): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7895): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/dhcpcd  ( 7773): wlan0: leased 192.168.1.136 for 86400 seconds
W/libprocessgroup(  901): failed to open /acct/uid_10175/pid_6941/cgroup.procs: No such file or directory
,E/WifiStateMachine(  901): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  901): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/KnoxUsageLogPro( 7895): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7895): premStatus:2
,I/KnoxUsageLogPro( 7895): isEulaShown : false
I/KnoxUsageLogPro( 7895): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7917): MountEmulatedStorage()
I/libpersona( 7917): KNOX_SDCARD checking this for 10087
E/Zygote  ( 7917): v2
I/libpersona( 7917): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7917 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 6957:com.qualcomm.timeservice/1000 (adj 15): bgCount ##41
,I/art     (  325): Explicit concurrent mark sweep GC freed 8718(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 267us total 12.832ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 246us total 8.733ms
,I/SELinux ( 7917): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7917): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7917): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 8.622ms
,D/TimaKeyStoreProvider( 7917): TimaSignature is unavailable
,D/ActivityThread( 7917): Added TimaKeyStore provider
,D/ResourcesManager( 7917): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  901): failed to open /acct/uid_1000/pid_6957/cgroup.procs: No such file or directory
,I/ActivityManager(  901): Killing 6022:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,D/Headlines( 5412): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5412): getCountryCode(): countryCode = PL
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/Headlines( 5412): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5412): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5412): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5412): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5412): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5412): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5412): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7956): MountEmulatedStorage()
E/Zygote  ( 7956): v2
I/libpersona( 7956): KNOX_SDCARD checking this for 10127
I/libpersona( 7956): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7956 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine(  901): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  901): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  901): do suspend true
,D/WifiP2pService(  901): InactiveState{ what=143375 }
,D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  901): WifiStateMachine DHCP successful
,E/WifiStateMachine(  901): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  901): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,I/SELinux ( 7956): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,E/WifiStateMachine(  901): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  901): Not connected state, yet.
E/WifiStateMachine(  901): VerifyingLinkState enter
,I/SELinux ( 7956): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/SELinux ( 7956): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/WifiStateMachine(  901): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine(  901): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  901): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  901): callSECApiInt - ID [210]
,E/WifiStateMachine(  901): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService(  901): updateNetworkInfo()
,D/ConnectivityService(  901): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  901): Adding iface wlan0 to network 503
,I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  901): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/TimaKeyStoreProvider( 7956): TimaSignature is unavailable
,E/WifiStateMachine(  901): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  901): Now, connected state.
E/WifiStateMachine(  901): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/ActivityThread( 7956): Added TimaKeyStore provider
,E/WifiStateMachine(  901): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  901): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  901): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  901): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  901): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  901): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  901): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
,V/        (  284): QcRouteController
,W/libprocessgroup(  901): failed to open /acct/uid_10045/pid_6022/cgroup.procs: No such file or directory
,I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
,V/        (  284): QcRouteController
,I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/NetworkManagementService(  901): route cmd failed: 
W/NetworkManagementService(  901): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 67 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  901): '
W/NetworkManagementService(  901): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  901): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  901): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  901): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  901): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  901): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  901): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  901): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:6000)
W/NetworkManagementService(  901): 	at com.android.server.ConnectivityService.access$2000(ConnectivityService.java:230)
W/NetworkManagementService(  901): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2337)
W/NetworkManagementService(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  901): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService(  901): updateSourceRoutes : add src route for:192.168.1.136
,V/        (  284): QcRouteController
,E/WifiStateMachine(  901): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  901): mBoosterFLAG : 0
I/WifiTrafficPoller(  901): current booster mode : FullMode
,D/WifiNative-HAL(  901): callSECApiVoid - ID [212]
,I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,V/        (  284): QcRouteController
,E/WifiStateMachine(  901): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine(  901): REQUEST_POWER_SAVE_ON
,V/        (  284): QcRouteController
,D/ResourcesManager( 7956): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,D/ConnectivityService(  901): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  901): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  901): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): calling update connectivity
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): ignoring duplicate network state non-change
D/ConnectivityService(  901): ignoring duplicate network state non-change
D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  901): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Validated
,D/ConnectivityService(  901): currentScore = 0, newScore = 60
D/ConnectivityService(  901):    accepting network in place of null
D/ConnectivityService(  901): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1471): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  901): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  901): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  901): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  901): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
,V/NetworkStats(  901): updateIfacesLocked()
D/ConnectivityService(  901): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,V/NetworkStats(  901): performPollLocked(flags=0x1)
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524290
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NetworkStatsFactory(  901): UpdateStatsForKnox
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
V/NetworkStats(  901): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): rematching NetworkAgentInfo [WIFI () - 503]
,D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): 0
D/ConnectivityService(  901):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  901): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): mDataTypeBrand = LTE
D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1183): updateDataNetType()
D/StatusBar.NetworkController( 1183): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1183): updateLTEICONDataNetType:0
,D/ConnectivityManager.CallbackHandler( 2539): CM callback handler got msg 524290
,V/NetworkStats(  901): performPollLocked() took 5ms
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524290
,D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 2539): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1183): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1183): updateDataNetType()
D/StatusBar.NetworkController( 1183): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1183): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1183): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7956): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7956): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7956): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7956): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 7956): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7956): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7956): Loading: webviewchromium
,I/LibraryLoader( 7956): Time to load native libraries: 5 ms (timestamps 4458-4463)
I/LibraryLoader( 7956): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7956): Binding Chromium to main looper Looper (main, tid 1) {25f02d38}
,I/LibraryLoader( 7956): Expected native library version number "",actual native library version number ""
,I/chromium( 7956): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7956): Initializing chromium process, renderers=0
,W/art     ( 7956): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7956): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7956): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7956): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7956): Requires BLUETOOTH permission
,I/Adreno-EGL( 7956): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7956): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7956): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7956): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7956): Remote Branch: 
I/Adreno-EGL( 7956): Local Patches: 
I/Adreno-EGL( 7956): Reconstruct Branch: 
,I/NSApplication( 7956): Starting up...
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  901): Killing 7136:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8030): MountEmulatedStorage()
,E/Zygote  ( 8030): v2
I/libpersona( 8030): KNOX_SDCARD checking this for 10137
I/libpersona( 8030): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8030 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 8030): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8030): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8030): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8030): TimaSignature is unavailable
,D/ActivityThread( 8030): Added TimaKeyStore provider
,D/ResourcesManager( 8030): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/libprocessgroup(  901): failed to open /acct/uid_10014/pid_7136/cgroup.procs: No such file or directory
,W/ResourcesManager( 8030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8030): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8030): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 8030): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8030): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8030): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/Zygote  ( 8046): MountEmulatedStorage()
E/Zygote  ( 8046): v2
I/libpersona( 8046): KNOX_SDCARD checking this for 10162
I/libpersona( 8046): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8046 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  901): Killing 7154:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  901): MasterInitialState.processMessage what=3
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  901): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  901): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
I/CLocInfoService(  901): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  901): CLocinfo wifi true 
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 8046): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8046): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
E/SELinux ( 8046): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/accuweather( 1950): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2155): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2155): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3700): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3700): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7742): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 8046): TimaSignature is unavailable
,D/ActivityThread( 8046): Added TimaKeyStore provider
,D/SecContentProvider2(  901): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  901): mCursor = null
,W/libprocessgroup(  901): failed to open /acct/uid_10015/pid_7154/cgroup.procs: No such file or directory
,D/ResourcesManager( 8046): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8046): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8046): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8046): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8046): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/RCPManagerService(  901): exchangeData() failure , invalid userId
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,E/Zygote  ( 8071): MountEmulatedStorage()
E/Zygote  ( 8071): v2
I/libpersona( 8071): KNOX_SDCARD checking this for 10077
I/libpersona( 8071): KNOX_SDCARD not a persona
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,I/ActivityManager(  901): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8071 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,I/SELinux ( 8071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 8071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,E/SELinux ( 8071): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6924): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6924): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6924): StateMachine : Current State = 1
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6924): StateMachine : Changed Current State = 1
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
I/ActivityManager(  901): Killing 6342:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,V/BitmapFactory( 8046): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/TimaKeyStoreProvider( 8071): TimaSignature is unavailable
,D/ActivityThread( 8071): Added TimaKeyStore provider
,I/ActivityManager(  901): Killing 4790:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,D/ResourcesManager( 8071): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8086): MountEmulatedStorage()
E/Zygote  ( 8086): v2
I/libpersona( 8086): KNOX_SDCARD checking this for 10177
I/libpersona( 8086): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8086 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8086): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8086): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8086): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 8071): onCreate
,D/BadgeProvider( 8071): DatabaseHelper
,D/BadgeProvider( 8071): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 8086): TimaSignature is unavailable
,D/ActivityThread( 8086): Added TimaKeyStore provider
,D/BadgeProvider( 8071): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8071): sendNotify, [notify] : null
D/BadgeProvider( 8071): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8071): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8071): update, [UpdateCount] : 1
D/Launcher.Model( 1481): reloadBadges entered.
,D/ResourcesManager( 8086): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,W/libprocessgroup(  901): failed to open /acct/uid_10033/pid_6342/cgroup.procs: No such file or directory
,W/libprocessgroup(  901): failed to open /acct/uid_10034/pid_4790/cgroup.procs: No such file or directory
,W/ActivityManager(  901): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  901): Killing 7224:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7722): notifyNetworkActivated
,D/ConnectivityService(  901): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/ContextImpl( 7722): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  901): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/libprocessgroup(  901): failed to open /acct/uid_10041/pid_7224/cgroup.procs: No such file or directory
,D/hcjo    ( 7722): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7722): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7722): exit::IDLE
D/InitializeManagerStateMachine( 7722): entry::NETWORK_CHECK
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7722): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7722): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7722): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7722): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7722): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7722): entry::SUCCESS
D/hcjo    ( 7722): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1318): Starting #8
,I/Hs20UtilService( 1318): Message received 5007
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
D/hcjo    ( 7722): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7722): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,D/InitializeManagerStateMachine( 7722): exit::SUCCESS
D/InitializeManagerStateMachine( 7722): entry::IDLE
,I/Hs20UtilService( 1318): Starting #9
,I/Hs20UtilService( 1318): Message received 5007
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1318): Starting #10
,I/Hs20UtilService( 1318): Message received 5007
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1318): Starting #11
,I/Hs20UtilService( 1318): Message received 5007
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  901): callSECApi what=220
D/WifiStateMachine(  901): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7169): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7169): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7169): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7169): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7799): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7799): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SurfaceFlinger(  259): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,E/SMD     (  290): DCD ON
,D/PowerManagerService(  901): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=901
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
I/FOTA_Client( 7818): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7818): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7818): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/jxcore-log( 7353): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7353): 
,I/KLMS-2.4.503: ( 7841): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7841): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453396610575
,I/KLMS-2.4.503: ( 7841): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7841): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7841): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7841): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,I/KLMS-2.4.503: ( 7841): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7858): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7206): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6813): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6813): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6813): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6813): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6813): [OR] == isSIMCardReady false ==
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6813): [SCU] == networkStateCheck == true
,I/SA      ( 6813): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6813): isChinaCountryCode : false
I/SA      ( 6813): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6813): [OR] == networkStateCheck true ==
,I/SA      ( 6813): [OR] GetMyCountryZoneTask
,I/SA      ( 6813): [OR] onReceive END
,I/SA      ( 6813): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6813): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6813): [SSP] query invoked
,D/accuweather( 7876): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7876): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/art     (  901): Explicit concurrent mark sweep GC freed 47509(2MB) AllocSpace objects, 1(16KB) LOS objects, 31% free, 35MB/51MB, paused 1.959ms total 81.444ms
,I/SA      ( 6813): [TPMU] GetMccFromDB : null
,I/SA      ( 6813): [SCU] getMccFromPreferece mcc = 260
,I/KnoxUsageLogPro( 7895): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7895): premStatus:2
,I/SA      ( 6813): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7895): isEulaShown : false
I/KnoxUsageLogPro( 7895): KnoxUsageReceiver onReceive : not Processible, just return
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/GAV2    ( 7589): Thread[GAThread,5,main]: No campaign data found.
,E/File    ( 6813): fail readDirectory() errno=2
,D/Headlines( 5412): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5412): getCountryCode(): countryCode = PL
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Headlines( 5412): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5412): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5412): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5412): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5412): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5412): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5412): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 8030): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8030): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 8030): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6924): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6924): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6924): StateMachine : Current State = 1
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6924): StateMachine : Changed Current State = 1
,I/ActivityManager(  901): Killing 5781:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ProcessCpuTracker(  901): Skipping unknown process pid 7943
,W/ProcessCpuTracker(  901): Skipping unknown process pid 7944
,W/ProcessCpuTracker(  901): Skipping unknown process pid 7955
,W/ProcessCpuTracker(  901): Skipping unknown process pid 7979
,W/ProcessCpuTracker(  901): Skipping unknown process pid 8116
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7722): AutoUpdateManager:IDLE:execute
,W/libprocessgroup(  901): failed to open /acct/uid_10047/pid_5781/cgroup.procs: No such file or directory
,D/InitializeManagerStateMachine( 7722): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7722): exit::IDLE
D/InitializeManagerStateMachine( 7722): entry::NETWORK_CHECK
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7722): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7722): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7722): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7722): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7722): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7722): entry::SUCCESS
D/hcjo    ( 7722): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7722): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7722): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7722): exit::SUCCESS
D/InitializeManagerStateMachine( 7722): entry::IDLE
,I/jxcore-log( 7353): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7353): 
,I/SA      ( 6813): [RC New] Execute method=[GET] start
,I/SA      ( 6813): [RC New] Security=[true]
,I/System.out( 6813): Thread-1060(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6813): Thread-1060(ApacheHTTPLog):isShipBuild true
,I/System.out( 6813): Thread-1060(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 7353): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7353): 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7353): Test app app.js loaded
I/jxcore-log( 7353): 
,I/chromium( 7353): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7353): BLE advertisement is supported
I/jxcore-log( 7353): 
,I/dhcpcd  ( 7773): wlan0: sending IPv6 Router Solicitation
,I/SA      ( 6813): [RC New] [v2liruge] api execute + 681
I/SA      ( 6813): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6813): AsyncTask #1 calls detatch()
,I/SA      ( 6813): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6813): [OCP] update openData : PL
,I/SA      ( 6813): [TPMU] getNetworkMcc : 
,I/SA      ( 6813): [SCU] saveMccToPreferece Start
I/SA      ( 6813): [SCU] RegionMCC : 260
I/SA      ( 6813): [SSP] query invoked
,I/SA      ( 6813): [TPMU] GetMccFromDB : null
I/SA      ( 6813): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6813): [SCU] saveMccToPreferece End
I/SA      ( 6813): [RC New] executeRequest [v2liruge] end. 733
,I/SA      ( 6813): [RC New] Execute end
,I/SA      ( 6813): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6813): [OR] GetMyCountryZoneTask Success
,I/WifiStateMachine(  901): REQUEST_POWER_SAVE_ON
,D/PackageManager(  901): [MSG] MCS_UNBIND
,I/ActivityManager(  901): Killing 5672:com.android.mms/u0a49 (adj 15): bgCount ##41
,E/WifiStateMachine(  901): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/CountryDetector(  901): No listener is left
,W/libprocessgroup(  901): failed to open /acct/uid_10049/pid_5672/cgroup.procs: No such file or directory
,D/WearableService( 2185): callingUid 10011, callindPid: 2185
,D/ResourcesManager( 7742): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7742): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7742): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7742): Using the GMSCore's GoogleHttpClient
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,D/WearableClient( 7742): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7742): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7742): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7742): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WearableClient( 7742): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7742): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7742): Conditions not met for autocaching.
I/MusicLeanback( 7742): Stop autocaching.
,E/ActivityThread( 7742): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@11b1d1f8 that was originally bound here
E/ActivityThread( 7742): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@11b1d1f8 that was originally bound here
E/ActivityThread( 7742): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7742): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7742): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7742): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7742): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7742): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7742): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7742): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7742): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7742): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7742): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7742): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7742): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7742): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7742): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7742): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7742): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7742): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7742): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7742): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7742): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7742): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7742): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7742): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7742): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SMD     (  290): DCD ON
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  259): id=16 Removed Toast (8/9)
,I/SurfaceFlinger(  259): id=16 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
,D/PowerManagerService(  901): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 901) eventTime = 118985
,D/PowerManagerService(  901): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=901 (0x0)
D/PowerManagerService(  901): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=901, ws=WorkSource{10058}) (elapsedTime=3531)
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
,I/GAV4    ( 7956): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  901): waitForAlarm result :4
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  901): stay LED for fully charged
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/PowerManagerService(  901): [PWL] Off : 30s ago
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  901): SIOP:: AP = 400, PST = 360, CUR = 450
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7169): mConnectivityHandler : connected
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7169): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7169): [GetString-S]
,I/ReactiveServiceManager( 7169): Supported : 1
,D/QSEECOMAPI: (  901): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: (  901): App is not loaded in QSEE
,D/QSEECOMAPI: (  901): Loaded image: APP id = 3
,D/QSEECOMAPI: (  901): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  901): QSEECom_shutdown_app, app_id = 3
E/terrier (  901): handleString: Failed to handle string(-4)
,E/terrier (  901): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 7169): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7169): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7169): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7169): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7169): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7169): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7773): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  290): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 7773): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7773): wlan0: no IPv6 Routers available
,V/AlarmManager(  901): waitForAlarm result :8
,D/PreloadUpdateManagerStateMachine( 7722): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7722): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7722): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7722): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7722): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7722): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7722): entry::IDLE
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7722): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7722): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7722): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7722): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7722): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7722): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7722): entry::IDLE
,V/AlarmManager(  901): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/Finsky  ( 7657): [1240] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7657): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  901): SIOP:: AP = 340, PST = 350, CUR = 450
,E/SMD     (  290): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,E/Watchdog(  901): !@Sync 4
,E/SMD     (  290): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/PowerManagerService(  901): [PWL] Off : 50s ago
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  901): stay LED for fully charged
,D/SSRM:m  (  901): SIOP:: AP = 310, PST = 341, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/SSRM:m  (  901): SIOP:: AP = 310, PST = 337, CUR = 450
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON,
,E/SMD     (  290): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  901): SIOP:: AP = 300, PST = 334, CUR = 450
,E/SMD     (  290): DCD ON
,I/ClearcutLoggerApiImpl( 2185): disconnect managed GoogleApiClient
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD ON
,E/Watchdog(  901): !@Sync 5
,I/PowerManagerService(  901): [PWL] Off : 75s ago
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  901): SIOP:: AP = 290, PST = 331, CUR = 450
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  901): SIOP:: AP = 290, PST = 328, CUR = 450
,E/SMD     (  290): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,V/AlarmManager(  901): waitForAlarm result :8
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD ON
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/SSRM:m  (  901): SIOP:: AP = 290, PST = 325, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,E/Watchdog(  901): !@Sync 6
,I/PowerManagerService(  901): [PWL] Off : 105s ago
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/SSRM:m  (  901): SIOP:: AP = 290, PST = 320, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/SSRM:m  (  901): SIOP:: AP = 290, PST = 311, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  901): SIOP:: AP = 270, PST = 298, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,E/Watchdog(  901): !@Sync 7
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager(  901): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  901): stay LED for fully charged
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 140s ago
,D/SSRM:m  (  901): SIOP:: AP = 270, PST = 291, CUR = 450
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD ON
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  901): SIOP:: AP = 270, PST = 287, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,V/AlarmManager(  901): waitForAlarm result :8
,E/SMD     (  290): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  901): SIOP:: AP = 260, PST = 282, CUR = 450
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7353): TAP version 13
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # multiplex can send data
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 1 String should be length:200
I/jxcore-log( 7353): 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # enqueue and run in order
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 2 firstPromise setTimeout expected 0 and got 0
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 3 firstPromise result expected 10 and got 10
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 4 firstPromise testValue expected 10 and got 10
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 5 secondPromise setTimeout expected 10 and got 10
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 6 secondPromise result expected 100 and got 100
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 7 secondPromise testValue expected 100 and got 100
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 8 thirdPromise in promise expected 100 and got 100
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 9 thirdPromise result expected 1000 and got 1000
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 10 thirdPromise result expected 1000 and got 1000
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # basic
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 11 sane
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # another
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 12 sane
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 13 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 14 null
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 15 (unnamed assert)
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 16 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 17 should not throw
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 18 (unnamed assert)
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 19 (unnamed assert)
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 20 should not throw
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 21 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 22 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 7353): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 23 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # failed to get mobile documents path
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 24 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 25 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 26 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 27 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # #init should register the networkChanged event
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 28 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # #startBroadcasting should throw on null device name
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 29 should throw
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 30 should throw
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # #startBroadcasting should throw on non-number port
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 31 should throw
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # #startBroadcasting should throw on NaN port
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 32 should throw
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # #startBroadcasting should throw on negative port
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 33 should throw
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # #startBroadcasting should throw on too large port
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 34 should throw
I/jxcore-log( 7353): 
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 35 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 36 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 37 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 38 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 39 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 40 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 41 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 42 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 43 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 44 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,E/Watchdog(  901): !@Sync 8
,I/jxcore-log( 7353): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 45 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 46 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 47 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 48 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 49 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # should call Mobile("Disconnect") without an error
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 50 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 51 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 52 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 53 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749189.7353
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749189.7353","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7353): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7353): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,D/BluetoothSocket( 7353): bindListen(), new LocalSocket 
,D/BluetoothSocket( 7353): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 7353): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@361fad27
,D/BluetoothSocket( 7353): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: OK
,I/io.jxcore.node.ConnectionHelper( 7353): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749189.7353
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): createAdvertiseData: From: 1453396749189.7353 b6a44ad1-d319-4b3a-815d-8b805a47fb51 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): 7C:F9:E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7353): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=ff819502-8806-472d-825a-9f6af1fbcda6
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=ff819502-8806-472d-825a-9f6af1fbcda6, clientIf=6
,D/BluetoothLeAdvertiser( 7353): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 3245): message : 0
,D/BtGatt.AdvertiseManager( 3245): number of adv instance running0
,D/BtGatt.AdvertiseManager( 3245): size of list is =0
,D/BtGatt.AdvertiseManager( 3245): starting advertising
,D/BtGatt.AdvertiseManager( 3245): isDualWavefalse
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): proc btwrite assertion
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): starting multi advertising
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 3245): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=4f46e14a-5f3c-45be-9273-415cf943a8ef
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=4f46e14a-5f3c-45be-9273-415cf943a8ef, clientIf=7
,D/BluetoothLeScanner( 7353): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 3245): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3245): handling starting scan
,D/BluetoothAdapterService( 3245): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@273765db
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 3245): allow scan with filters
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749189.7353","ra":"7C:F9:0E:34:8A:A0"}
,D/BtGatt.ScanManager( 3245): set filter index= 3 for clientIf= 7
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749189.7353","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749189.7353","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=1
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager( 3245): :scan window =2000 Scan interval = 5000
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): start: Starting P2P device discovery...
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): P2pEnabledState{ what=139292 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: RUNNING_BLE_AND_WIFI
D/WifiP2pService(  901): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749189.7353
I/io.jxcore.node.ConnectionHelper( 7353): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: true
,I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/jxcore-log( 7353): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 7353): 
,I/io.jxcore.node.ConnectionHelper( 7353): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): shutdown
,D/BluetoothSocket( 7353): close() in, this: android.bluetooth.BluetoothSocket@e70d140, channel: 6, state: LISTENING
D/BluetoothSocket( 7353): close() this: android.bluetooth.BluetoothSocket@e70d140, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@361fad27, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d4ac879mSocket: android.net.LocalSocket@88269be impl:android.net.LocalSocketImpl@22b31a1f fd:FileDescriptor[116]
D/BluetoothSocket( 7353): Closing mSocket: android.net.LocalSocket@88269be impl:android.net.LocalSocketImpl@22b31a1f fd:FileDescriptor[116]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: NOT_STARTED
D/WifiP2pService(  901): add a new client
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 3245): message : 1
D/BtGatt.AdvertiseManager( 3245): stop advertise for client 6
D/BtGatt.AdvertiseManager( 3245):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: -1
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local service added successfully
D/WifiP2pService(  901): P2pEnabledState{ what=139265 }
,D/WifiService(  901): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  901): callSECApi what=74
,D/BtGatt.GattService( 3245): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/bt_vendor( 3245): op for 7
D/BtGatt.GattService( 3245): Client app is not null!
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiStateMachine(  901): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  901): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1274): USE_NETWORK : USE_NETWORK OFF
D/BtGatt.GattService( 3245): unregisterClient() - clientIf=6
,D/WifiP2pService(  901): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3245): stopScan() - queue size =1
D/BtGatt.GattService( 3245): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): stop: Stopping P2P device discovery...
D/WifiP2pService(  901): InactiveState{ what=139298 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopWifiPeerDiscovery: Stopped
D/WifiP2pService(  901): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 7353): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 7353): 
,W/bt-smp  ( 3245): Key(LSB ~ MSB) = 5a f7 b6 c7 af d3 57 20 0a 7f eb d2 fa dd 35 5d 
W/bt-smp  ( 3245): Plain text(LSB ~ MSB) = 7d cc 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3245): Encrypted text(LSB ~ MSB) = 16 78 68 c9 3b e4 fd a6 b3 4c 43 3e 01 cf 28 4d 
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.ScanManager( 3245): filter size is 1
,D/BtGatt.ScanManager( 3245): delete FilterIndex - 3
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749408.7353
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): stop scan
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): P2pEnabledState clear service
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local services cleared successfully
,D/WifiP2pService(  901): InactiveState{ what=139268 }
I/wpa_supplicant( 1274): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749408.7353","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
,W/BluetoothAdapter( 7353): getBluetoothService() called with no BluetoothManagerCallback
D/WifiP2pService(  901): InactiveState{ what=139307 }
,D/WifiP2pService(  901): P2pEnabledState{ what=139307 }
,D/BluetoothSocket( 7353): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
D/WifiP2pService(  901): P2pEnabledState clear service request
D/BluetoothSocket( 7353): bindListen(), new LocalSocket 
D/BluetoothSocket( 7353): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 7353): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12a67335
D/BluetoothSocket( 7353): channel: 6
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7353): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: RUNNING
D/WifiP2pService(  901): InactiveState{ what=147493 }
,D/WifiP2pService(  901): P2pEnabledState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: OK
I/io.jxcore.node.ConnectionHelper( 7353): start: Using peer discovery mode: BLE_AND_WIFI
D/WifiP2pService(  901): discovery change broadcast false
,I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749408.7353
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): createAdvertiseData: From: 1453396749408.7353 b6a44ad1-d319-4b3a-815d-8b805a47fb51 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): 7C:F9:E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7353): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=d4c50d59-2330-43cc-be96-6cc2f84555e1
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=d4c50d59-2330-43cc-be96-6cc2f84555e1, clientIf=6
,D/BluetoothLeAdvertiser( 7353): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 3245): message : 0
,D/BtGatt.AdvertiseManager( 3245): number of adv instance running0
D/BtGatt.AdvertiseManager( 3245): size of list is =0
,D/BtGatt.AdvertiseManager( 3245): starting advertising
,D/BtGatt.AdvertiseManager( 3245): isDualWavefalse
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): starting multi advertising
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 3245): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=b9df77be-bcd0-498c-833c-28b61986ff04
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=b9df77be-bcd0-498c-833c-28b61986ff04, clientIf=7
,D/BluetoothLeScanner( 7353): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 3245): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3245): handling starting scan
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749408.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749408.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749408.7353","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3245): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 3245): allow scan with filters
D/BtGatt.ScanManager( 3245): set filter index= 4 for clientIf= 7
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): InactiveState{ what=139292 }
D/WifiP2pService(  901): P2pEnabledState{ what=139292 }
D/WifiP2pService(  901): P2pEnabledState add service
,D/WifiP2pService(  901): add a new client
D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=1
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 3245): :scan window =2000 Scan interval = 5000
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): start: Starting P2P device discovery...
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService(  901): InactiveState{ what=139265 }
I/WifiStateMachine(  901): callSECApi what=74
D/WifiP2pService(  901): P2pEnabledState{ what=139265 }
D/WifiStateMachine(  901): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService(  901): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiNative-HAL(  901): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1274): USE_NETWORK : USE_NETWORK OFF
D/WifiP2pService(  901): discovery change broadcast true
I/wpa_supplicant( 1274): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749408.7353
I/io.jxcore.node.ConnectionHelper( 7353): start: OK
,I/jxcore-log( 7353): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 7353): 
I/io.jxcore.node.ConnectionHelper( 7353): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): shutdown
,D/BluetoothSocket( 7353): close() in, this: android.bluetooth.BluetoothSocket@2b0ff296, channel: 6, state: LISTENING
D/BluetoothSocket( 7353): close() this: android.bluetooth.BluetoothSocket@2b0ff296, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12a67335, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@27b82e17mSocket: android.net.LocalSocket@440d204 impl:android.net.LocalSocketImpl@2aed3ed fd:FileDescriptor[116]
D/BluetoothSocket( 7353): Closing mSocket: android.net.LocalSocket@440d204 impl:android.net.LocalSocketImpl@2aed3ed fd:FileDescriptor[116]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): onServerStopped
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): onStartSuccess
D/WifiP2pService(  901): InactiveState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: true
D/WifiP2pService(  901): P2pEnabledState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local service added successfully
D/WifiP2pService(  901): discovery change broadcast false
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/WifiP2pService(  901): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stop: Stopping peer discovery...
D/BtGatt.AdvertiseManager( 3245): message : 1
,I/wpa_supplicant( 1274): P2P-FIND-STOPPED 
D/BtGatt.AdvertiseManager( 3245): stop advertise for client 6
,D/BtGatt.AdvertiseManager( 3245):  dualWaveClientIf = 0client.clientIf6
D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: -1
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING,
D/BtGatt.GattService( 3245): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 3245): Client app is not null!
D/bt_vendor( 3245): op for 7
,D/WifiP2pService(  901): InactiveState{ what=139298 }
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): P2pEnabledState{ what=139298 }
,D/BtGatt.GattService( 3245): unregisterClient() - clientIf=6
,D/WifiP2pService(  901): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3245): stopScan() - queue size =1
,D/WifiP2pService(  901): remove client information from framework
D/BtGatt.ScanManager( 3245): filter size is 1
,D/WifiP2pService(  901): InactiveState{ what=139268 }
,D/BtGatt.ScanManager( 3245): delete FilterIndex - 4
D/BtGatt.GattService( 3245): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsScannerStartedChanged: false
D/WifiP2pService(  901): InactiveState{ what=139307 },
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): setIsStarted: true
,D/WifiP2pService(  901): P2pEnabledState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsBlePeerDiscoveryStartedChanged: true
,D/WifiP2pService(  901): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 7353): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 7353): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749485.7353
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
W/bt-smp  ( 3245): Key(LSB ~ MSB) = 5a f7 b6 c7 af d3 57 20 0a 7f eb d2 fa dd 35 5d 
,W/bt-smp  ( 3245): Plain text(LSB ~ MSB) = e7 49 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3245): Encrypted text(LSB ~ MSB) = 36 0a 8e b4 e3 d1 1a ba a9 be 33 27 47 0f 53 f8 
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749485.7353","ra":"7C:F9:0E:34:8A:A0"}
D/bt_vendor( 3245): op for 7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): setConnectionTimeout: 15000
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): startListeningForIncomingConnections: Starting...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7353): Service requests cleared successfully
D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
W/BluetoothAdapter( 7353): getBluetoothService() called with no BluetoothManagerCallback
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.ScanManager( 3245): stop scan
,D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1,
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue emtpy, scan stopped
D/BluetoothSocket( 7353): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]},
D/BluetoothSocket( 7353): bindListen(), new LocalSocket 
,D/BluetoothSocket( 7353): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7353): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f0794b3
,D/BluetoothSocket( 7353): channel: 6
D/WifiP2pService(  901): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: RUNNING
D/WifiP2pService(  901): P2pEnabledState{ what=139292 }
,D/bt_vendor( 3245): op for 7
D/WifiP2pService(  901): P2pEnabledState add service,
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): add a new client
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: OK
I/io.jxcore.node.ConnectionHelper( 7353): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749485.7353
D/WifiP2pService(  901): InactiveState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
,D/WifiP2pService(  901): P2pEnabledState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): bind: Binding a new listener
D/WifiService(  901): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): createAdvertiseData: From: 1453396749485.7353 b6a44ad1-d319-4b3a-815d-8b805a47fb51 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): 7C:F9:E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7353): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BtGatt.GattService( 3245): registerClient() - UUID=57ee5cd1-8a90-46ef-ae0c-6ae0c2174655
D/WifiP2pService(  901): discovery change broadcast true
D/BtGatt.GattService( 3245): onClientRegistered() - UUID=57ee5cd1-8a90-46ef-ae0c-6ae0c2174655, clientIf=6
D/BluetoothLeAdvertiser( 7353): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 3245): message : 0
D/BtGatt.AdvertiseManager( 3245): number of adv instance running0
D/BtGatt.AdvertiseManager( 3245): size of list is =0
D/BtGatt.AdvertiseManager( 3245): starting advertising
D/BtGatt.AdvertiseManager( 3245): isDualWavefalse
D/WifiP2pService(  901): InactiveState{ what=139268 }
D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.GattService( 3245): onAdvertiseInstanceEnabled() - clientIf=6, status=0
D/BtGatt.AdvertiseManager( 3245): starting multi advertising
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 3245): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
D/BtGatt.GattService( 3245): registerClient() - UUID=611991cb-c9bf-4860-987c-a2af1cb4699b
D/BtGatt.GattService( 3245): onClientRegistered() - UUID=611991cb-c9bf-4860-987c-a2af1cb4699b, clientIf=7
,D/BluetoothLeScanner( 7353): onClientRegistered() - status=0 clientIf=7
D/BtGatt.GattService( 3245): start scan with filters
D/BtGatt.ScanManager( 3245): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749485.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749485.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749485.7353","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  901): InactiveState{ what=147493 }
D/BtGatt.GattService( 3245): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
,D/WifiP2pService(  901): P2pEnabledState{ what=147493 }
D/BtGatt.ScanManager( 3245): allow scan with filters
D/BtGatt.ScanManager( 3245): set filter index= 5 for clientIf= 7
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): start: Starting P2P device discovery...
D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 7353): start: OK
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): InactiveState{ what=139268 }
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 3245): :scan window =2000 Scan interval = 5000
I/jxcore-log( 7353): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 7353): 
I/io.jxcore.node.ConnectionHelper( 7353): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): shutdown
D/BluetoothSocket( 7353): close() in, this: android.bluetooth.BluetoothSocket@19de5d9c, channel: 6, state: LISTENING
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BluetoothSocket( 7353): close() this: android.bluetooth.BluetoothSocket@19de5d9c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f0794b3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@6db93a5mSocket: android.net.LocalSocket@2918537a impl:android.net.LocalSocketImpl@3326e72b fd:FileDescriptor[116]
D/BluetoothSocket( 7353): Closing mSocket: android.net.LocalSocket@2918537a impl:android.net.LocalSocketImpl@3326e72b fd:FileDescriptor[116]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749485.7353
D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 3245): message : 1
D/BtGatt.AdvertiseManager( 3245): stop advertise for client 6
D/BtGatt.AdvertiseManager( 3245):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: -1
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local service added successfully
I/WifiStateMachine(  901): callSECApi what=74
D/WifiStateMachine(  901): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  901): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1274): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1274): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1274): P2P-FIND-STOPPED 
D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.GattService( 3245): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 3245): Client app is not null!
,D/BtGatt.GattService( 3245): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3245): stopScan() - queue size =1
D/BtGatt.ScanManager( 3245): filter size is 1
D/BtGatt.ScanManager( 3245): delete FilterIndex - 5
,D/BtGatt.GattService( 3245): unregisterClient() - clientIf=7
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService(  901): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopWifiPeerDiscovery: Stopped
D/WifiP2pService(  901): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): release: No more listeners, de-initializing...
,D/WifiP2pService(  901): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: No more listeners, de-initializing...
D/WifiP2pService(  901): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local services cleared successfully
D/WifiP2pService(  901): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
D/WifiP2pService(  901): InactiveState{ what=139307 }
D/WifiP2pService(  901): P2pEnabledState{ what=139307 }
I/jxcore-log( 7353): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 7353): 
,D/WifiP2pService(  901): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7353): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749538.7353
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749538.7353","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): startListeningForIncomingConnections: Starting...
W/bt-smp  ( 3245): Key(LSB ~ MSB) = 5a f7 b6 c7 af d3 57 20 0a 7f eb d2 fa dd 35 5d 
W/bt-smp  ( 3245): Plain text(LSB ~ MSB) = 5d a2 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3245): Encrypted text(LSB ~ MSB) = b5 f5 9e 2c 38 8f ac cc 94 34 49 06 cb c9 b2 30 
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
W/BluetoothAdapter( 7353): getBluetoothService() called with no BluetoothManagerCallback
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BluetoothSocket( 7353): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
D/BluetoothSocket( 7353): bindListen(), new LocalSocket 
D/BluetoothSocket( 7353): bindListen(), new LocalSocket.getInputStream() 
D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.ScanManager( 3245): stop scan
,D/BluetoothSocket( 7353): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1516c521
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue emtpy, scan stopped
D/BluetoothSocket( 7353): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: RUNNING
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: OK
I/io.jxcore.node.ConnectionHelper( 7353): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749538.7353
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): bind: Binding a new listener
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): createAdvertiseData: From: 1453396749538.7353 b6a44ad1-d319-4b3a-815d-8b805a47fb51 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): 7C:F9:E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7353): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=107f8185-70f0-41f8-b931-3d9cc65fb889
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=107f8185-70f0-41f8-b931-3d9cc65fb889, clientIf=6
D/BluetoothLeAdvertiser( 7353): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 3245): message : 0
D/BtGatt.AdvertiseManager( 3245): number of adv instance running0
D/BtGatt.AdvertiseManager( 3245): size of list is =0
,D/BtGatt.AdvertiseManager( 3245): starting advertising
D/BtGatt.AdvertiseManager( 3245): isDualWavefalse
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): starting multi advertising
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 3245): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=39282ff1-8a7f-45af-b2ea-b89fd1ae03a5
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=39282ff1-8a7f-45af-b2ea-b89fd1ae03a5, clientIf=7
D/BluetoothLeScanner( 7353): onClientRegistered() - status=0 clientIf=7
D/BtGatt.GattService( 3245): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3245): handling starting scan
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): allow scan with filters
D/BtGatt.ScanManager( 3245): set filter index= 6 for clientIf= 7
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749538.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749538.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749538.7353","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 3245): :scan window =2000 Scan interval = 5000
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): InactiveState{ what=139292 }
,D/WifiP2pService(  901): P2pEnabledState{ what=139292 }
D/WifiP2pService(  901): P2pEnabledState add service
D/WifiP2pService(  901): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): start: Starting P2P device discovery...
,D/WifiP2pService(  901): InactiveState{ what=139265 }
D/WifiP2pService(  901): P2pEnabledState{ what=139265 }
I/WifiStateMachine(  901): callSECApi what=74
D/WifiService(  901): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine(  901): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  901): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1274): USE_NETWORK : USE_NETWORK OFF
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant( 1274): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749538.7353
I/io.jxcore.node.ConnectionHelper( 7353): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
I/jxcore-log( 7353): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 7353): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/io.jxcore.node.ConnectionHelper( 7353): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): shutdown
D/BluetoothSocket( 7353): close() in, this: android.bluetooth.BluetoothSocket@49d7d2, channel: 6, state: LISTENING
D/BluetoothSocket( 7353): close() this: android.bluetooth.BluetoothSocket@49d7d2, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1516c521, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d9f10a3mSocket: android.net.LocalSocket@14ddefa0 impl:android.net.LocalSocketImpl@3741f759 fd:FileDescriptor[116]
D/BluetoothSocket( 7353): Closing mSocket: android.net.LocalSocket@14ddefa0 impl:android.net.LocalSocketImpl@3741f759 fd:FileDescriptor[116]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): onStartSuccess
D/WifiP2pService(  901): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
D/BtGatt.AdvertiseManager( 3245): message : 1
I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery started successfully
D/BtGatt.AdvertiseManager( 3245): stop advertise for client 6
D/BtGatt.AdvertiseManager( 3245):  dualWaveClientIf = 0client.clientIf6
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: -1
,D/WifiP2pService(  901): InactiveState{ what=139268 }
I/wpa_supplicant( 1274): P2P-FIND-STOPPED 
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
D/WifiP2pService(  901): InactiveState{ what=147493 }
D/WifiP2pService(  901): P2pEnabledState{ what=147493 }
D/WifiP2pService(  901): discovery change broadcast false
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): InactiveState{ what=139268 }
,D/BtGatt.GattService( 3245): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 3245): Client app is not null!
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 3245): stopScan() - queue size =1
D/BtGatt.ScanManager( 3245): filter size is 1
D/BtGatt.ScanManager( 3245): delete FilterIndex - 6
,D/BtGatt.GattService( 3245): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): release: No more listeners, de-initializing...
D/WifiP2pService(  901): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiP2pService(  901): P2pEnabledState{ what=139298 }
,I/jxcore-log( 7353): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 7353): 
D/WifiP2pService(  901): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/WifiP2pService(  901): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749593.7353
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
D/WifiP2pService(  901): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
D/WifiP2pService(  901): InactiveState{ what=139307 }
D/WifiP2pService(  901): P2pEnabledState{ what=139307 }
D/WifiP2pService(  901): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7353): Service requests cleared successfully
,W/bt-smp  ( 3245): Key(LSB ~ MSB) = 5a f7 b6 c7 af d3 57 20 0a 7f eb d2 fa dd 35 5d 
W/bt-smp  ( 3245): Plain text(LSB ~ MSB) = 8f dc 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3245): Encrypted text(LSB ~ MSB) = 31 9b 4b 2b 4f fd 20 2c cb f3 1a 0f 59 f9 53 aa 
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749593.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): setConnectionTimeout: 15000
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): startListeningForIncomingConnections: Starting...
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): stop scan
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue emtpy, scan stopped
,W/BluetoothAdapter( 7353): getBluetoothService() called with no BluetoothManagerCallback
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BluetoothSocket( 7353): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
D/BluetoothSocket( 7353): bindListen(), new LocalSocket 
D/BluetoothSocket( 7353): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7353): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@250813ff
D/BluetoothSocket( 7353): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: OK
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7353): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749593.7353
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Waiting for incoming connections...
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): createAdvertiseData: From: 1453396749593.7353 b6a44ad1-d319-4b3a-815d-8b805a47fb51 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): 7C:F9:E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7353): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=afbb38da-a379-44a7-902e-b1c65aedd594
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=afbb38da-a379-44a7-902e-b1c65aedd594, clientIf=6
D/BluetoothLeAdvertiser( 7353): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 3245): message : 0
D/BtGatt.AdvertiseManager( 3245): number of adv instance running0
D/BtGatt.AdvertiseManager( 3245): size of list is =0
,D/BtGatt.AdvertiseManager( 3245): starting advertising
D/BtGatt.AdvertiseManager( 3245): isDualWavefalse
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): starting multi advertising
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 3245): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=cf1a3d96-5f33-415f-8c12-dc6930f4230c
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=cf1a3d96-5f33-415f-8c12-dc6930f4230c, clientIf=7
D/BluetoothLeScanner( 7353): onClientRegistered() - status=0 clientIf=7
D/BtGatt.GattService( 3245): start scan with filters
,D/BtGatt.ScanManager( 3245): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): allow scan with filters
D/BtGatt.ScanManager( 3245): set filter index= 7 for clientIf= 7
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
I/BtGatt.ScanManager( 3245): :scan window =2000 Scan interval = 5000
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749593.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749593.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749593.7353","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): InactiveState{ what=139292 }
,D/WifiP2pService(  901): P2pEnabledState{ what=139292 }
D/WifiP2pService(  901): P2pEnabledState add service
D/WifiP2pService(  901): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
D/WifiP2pService(  901): InactiveState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: RUNNING_BLE_AND_WIFI
D/WifiP2pService(  901): P2pEnabledState{ what=139265 }
D/WifiService(  901): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  901): callSECApi what=74
D/WifiStateMachine(  901): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  901): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1274): USE_NETWORK : USE_NETWORK OFF
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749593.7353
,I/wpa_supplicant( 1274): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 7353): start: OK
D/WifiP2pService(  901): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 7353): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 7353): 
D/WifiP2pService(  901): InactiveState{ what=139268 }
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/wpa_supplicant( 1274): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 7353): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): Shutting down...
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): shutdown
,D/BluetoothSocket( 7353): close() in, this: android.bluetooth.BluetoothSocket@e9612b8, channel: 6, state: LISTENING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
D/BluetoothSocket( 7353): close() this: android.bluetooth.BluetoothSocket@e9612b8, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@250813ff, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@21ea3891mSocket: android.net.LocalSocket@1f1c73f6 impl:android.net.LocalSocketImpl@10b683f7 fd:FileDescriptor[116]
,D/WifiP2pService(  901): InactiveState{ what=147493 }
D/BluetoothSocket( 7353): Closing mSocket: android.net.LocalSocket@1f1c73f6 impl:android.net.LocalSocketImpl@10b683f7 fd:FileDescriptor[116]
D/WifiP2pService(  901): P2pEnabledState{ what=147493 }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): onServerStopped
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: NOT_STARTED
D/WifiP2pService(  901): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 3245): message : 1
,D/BtGatt.AdvertiseManager( 3245): stop advertise for client 6
D/BtGatt.AdvertiseManager( 3245):  dualWaveClientIf = 0client.clientIf6
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: -1
,D/WifiP2pService(  901): InactiveState{ what=139268 }
,D/BtGatt.GattService( 3245): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 3245): Client app is not null!
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.GattService( 3245): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3245): stopScan() - queue size =1
,D/BtGatt.ScanManager( 3245): filter size is 1
D/BtGatt.ScanManager( 3245): delete FilterIndex - 7
,D/BtGatt.GattService( 3245): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): stop: Stopping services
,D/WifiP2pService(  901): InactiveState{ what=139298 }
D/WifiP2pService(  901): P2pEnabledState{ what=139298 }
D/WifiP2pService(  901): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): stop: Stopping P2P device discovery...
,D/WifiP2pService(  901): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: NOT_INITIALIZED
D/WifiP2pService(  901): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): release: No more listeners, de-initializing...
,D/WifiP2pService(  901): InactiveState{ what=139307 }
D/WifiP2pService(  901): P2pEnabledState{ what=139307 }
D/WifiP2pService(  901): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7353): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: NOT_STARTED
,W/bt-smp  ( 3245): Key(LSB ~ MSB) = 5a f7 b6 c7 af d3 57 20 0a 7f eb d2 fa dd 35 5d 
W/bt-smp  ( 3245): Plain text(LSB ~ MSB) = ff e4 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3245): Encrypted text(LSB ~ MSB) = db a5 51 d7 7f 4d 8e 3a 0f 62 a7 9c a2 3b d9 e2 
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/jxcore-log( 7353): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 7353): 
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): stop scan
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue emtpy, scan stopped
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749657.7353
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749657.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7353): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7353): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
D/BluetoothSocket( 7353): bindListen(), new LocalSocket 
D/BluetoothSocket( 7353): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7353): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a68cccd
D/BluetoothSocket( 7353): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: OK
I/io.jxcore.node.ConnectionHelper( 7353): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749657.7353,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): bind: Binding a new listener
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): createAdvertiseData: From: 1453396749657.7353 b6a44ad1-d319-4b3a-815d-8b805a47fb51 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): 7C:F9:E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7353): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=86300b54-9d07-4a6d-88aa-3b49ee07d1a6
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=86300b54-9d07-4a6d-88aa-3b49ee07d1a6, clientIf=6
D/BluetoothLeAdvertiser( 7353): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 3245): message : 0
,D/BtGatt.AdvertiseManager( 3245): number of adv instance running0
D/BtGatt.AdvertiseManager( 3245): size of list is =0
,D/BtGatt.AdvertiseManager( 3245): starting advertising
D/BtGatt.AdvertiseManager( 3245): isDualWavefalse
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): starting multi advertising
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 3245): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=433bce9b-0634-4db6-b4dc-e4c3fc75b2c5
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=433bce9b-0634-4db6-b4dc-e4c3fc75b2c5, clientIf=7
D/BluetoothLeScanner( 7353): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 3245): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3245): handling starting scan
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): allow scan with filters
D/BtGatt.ScanManager( 3245): set filter index= 8 for clientIf= 7
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749657.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749657.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749657.7353","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 3245): :scan window =2000 Scan interval = 5000
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): InactiveState{ what=139292 }
D/WifiP2pService(  901): P2pEnabledState{ what=139292 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: true
D/bt_vendor( 3245): op for 7
D/WifiP2pService(  901): P2pEnabledState add service
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): add a new client
,D/WifiP2pService(  901): InactiveState{ what=139265 }
D/WifiP2pService(  901): P2pEnabledState{ what=139265 }
D/WifiService(  901): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  901): callSECApi what=74
D/WifiStateMachine(  901): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  901): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1274): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1274): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiP2pService(  901): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 7353): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749657.7353
I/jxcore-log( 7353): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 7353): 
,I/io.jxcore.node.ConnectionHelper( 7353): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): shutdown
D/BluetoothSocket( 7353): close() in, this: android.bluetooth.BluetoothSocket@1e2a0bce, channel: 6, state: LISTENING
D/BluetoothSocket( 7353): close() this: android.bluetooth.BluetoothSocket@1e2a0bce, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a68cccd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16d3faefmSocket: android.net.LocalSocket@1290d9fc impl:android.net.LocalSocketImpl@1effc885 fd:FileDescriptor[116]
D/BluetoothSocket( 7353): Closing mSocket: android.net.LocalSocket@1290d9fc impl:android.net.LocalSocketImpl@1effc885 fd:FileDescriptor[116]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): onStartSuccess
D/BtGatt.AdvertiseManager( 3245): message : 1
D/BtGatt.AdvertiseManager( 3245): stop advertise for client 6
D/BtGatt.AdvertiseManager( 3245):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: -1
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 3245): Client app is not null!
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.GattService( 3245): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
D/BtGatt.GattService( 3245): stopScan() - queue size =1
,D/BtGatt.ScanManager( 3245): filter size is 1
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery started successfully
D/BtGatt.ScanManager( 3245): delete FilterIndex - 8
D/WifiP2pService(  901): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: STARTED
I/wpa_supplicant( 1274): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/WifiP2pService(  901): InactiveState{ what=147493 }
D/BtGatt.GattService( 3245): unregisterClient() - clientIf=7
D/WifiP2pService(  901): P2pEnabledState{ what=147493 }
D/WifiP2pService(  901): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): stop: Stopping services
,D/WifiP2pService(  901): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): stop: Stopping P2P device discovery...
D/WifiP2pService(  901): InactiveState{ what=139298 }
D/WifiP2pService(  901): P2pEnabledState{ what=139298 }
D/WifiP2pService(  901): P2pEnabledState clear service
,D/WifiP2pService(  901): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: NOT_INITIALIZED
W/bt-smp  ( 3245): Key(LSB ~ MSB) = 5a f7 b6 c7 af d3 57 20 0a 7f eb d2 fa dd 35 5d 
W/bt-smp  ( 3245): Plain text(LSB ~ MSB) = 46 2d 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3245): Encrypted text(LSB ~ MSB) = e6 4f d1 b1 71 8f 30 11 b8 52 87 89 9a a8 75 65 
D/WifiP2pService(  901): InactiveState{ what=139268 }
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local services cleared successfully
,D/WifiP2pService(  901): InactiveState{ what=139307 }
D/bt_vendor( 3245): op for 7
D/WifiP2pService(  901): P2pEnabledState{ what=139307 }
,D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopWifiPeerDiscovery: Stopped
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): release: No more listeners, de-initializing...
D/BtGatt.ScanManager( 3245): stop scan
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7353): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: No more listeners, de-initializing...
D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 7353): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 7353): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749732.7353
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749732.7353","ra":"7C:F9:0E:34:8A:A0"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): startListeningForIncomingConnections,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7353): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7353): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,D/BluetoothSocket( 7353): bindListen(), new LocalSocket 
D/BluetoothSocket( 7353): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 7353): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@178f570b
D/BluetoothSocket( 7353): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: OK
I/io.jxcore.node.ConnectionHelper( 7353): start: Using peer discovery mode: BLE_AND_WIFI,
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749732.7353
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): createAdvertiseData: From: 1453396749732.7353 b6a44ad1-d319-4b3a-815d-8b805a47fb51 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): 7C:F9:E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7353): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BtGatt.GattService( 3245): registerClient() - UUID=ad734275-a54e-4c11-9d21-23a2055fb5e9
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=ad734275-a54e-4c11-9d21-23a2055fb5e9, clientIf=6
D/BluetoothLeAdvertiser( 7353): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 3245): message : 0
,D/BtGatt.AdvertiseManager( 3245): number of adv instance running0
D/BtGatt.AdvertiseManager( 3245): size of list is =0
,D/BtGatt.AdvertiseManager( 3245): starting advertising
D/BtGatt.AdvertiseManager( 3245): isDualWavefalse
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): starting multi advertising
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 3245): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=f95aeeea-ead2-4374-b940-be3be56c7cdf
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=f95aeeea-ead2-4374-b940-be3be56c7cdf, clientIf=7
D/BluetoothLeScanner( 7353): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 3245): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3245): handling starting scan
D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749732.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749732.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749732.7353","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3245): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): allow scan with filters
D/BtGatt.ScanManager( 3245): set filter index= 9 for clientIf= 7
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: true
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/WifiP2pService(  901): InactiveState{ what=139292 }
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 3245): :scan window =2000 Scan interval = 5000
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: RUNNING_BLE_AND_WIFI
D/WifiP2pService(  901): P2pEnabledState{ what=139292 }
I/io.jxcore.node.ConnectionHelper( 7353): start: OK
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749732.7353
D/WifiP2pService(  901): P2pEnabledState add service
,I/jxcore-log( 7353): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 7353): 
D/WifiP2pService(  901): add a new client
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): InactiveState{ what=139265 }
D/WifiP2pService(  901): P2pEnabledState{ what=139265 }
D/WifiService(  901): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  901): callSECApi what=74
D/WifiStateMachine(  901): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  901): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1274): USE_NETWORK : USE_NETWORK OFF
,I/io.jxcore.node.ConnectionHelper( 7353): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): stop: Stopping Bluetooth...
I/wpa_supplicant( 1274): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): shutdown
D/BluetoothSocket( 7353): close() in, this: android.bluetooth.BluetoothSocket@12386c94, channel: 6, state: LISTENING
,D/BluetoothSocket( 7353): close() this: android.bluetooth.BluetoothSocket@12386c94, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@178f570b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@193833dmSocket: android.net.LocalSocket@1bf9a732 impl:android.net.LocalSocketImpl@3ce99c83 fd:FileDescriptor[116]
D/WifiP2pService(  901): discovery change broadcast true
D/BluetoothSocket( 7353): Closing mSocket: android.net.LocalSocket@1bf9a732 impl:android.net.LocalSocketImpl@3ce99c83 fd:FileDescriptor[116]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: NOT_STARTED
D/WifiP2pService(  901): InactiveState{ what=139268 }
,I/wpa_supplicant( 1274): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 3245): message : 1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
D/BtGatt.AdvertiseManager( 3245): stop advertise for client 6
D/BtGatt.AdvertiseManager( 3245):  dualWaveClientIf = 0client.clientIf6
D/WifiP2pService(  901): InactiveState{ what=147493 }
,D/WifiP2pService(  901): P2pEnabledState{ what=147493 }
D/WifiP2pService(  901): discovery change broadcast false
D/bt_vendor( 3245): op for 7
D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: -1
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): InactiveState{ what=139268 }
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 3245): Client app is not null!
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.GattService( 3245): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3245): stopScan() - queue size =1
D/BtGatt.GattService( 3245): unregisterClient() - clientIf=7
D/BtGatt.ScanManager( 3245): filter size is 1
D/BtGatt.ScanManager( 3245): delete FilterIndex - 9
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): stop: Stopping P2P device discovery...
D/WifiP2pService(  901): InactiveState{ what=139298 }
D/WifiP2pService(  901): P2pEnabledState{ what=139298 }
D/WifiP2pService(  901): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): release: No more listeners, de-initializing...
D/WifiP2pService(  901): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local services cleared successfully
D/WifiP2pService(  901): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
D/WifiP2pService(  901): InactiveState{ what=139307 }
D/WifiP2pService(  901): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  901): P2pEnabledState clear service request
I/jxcore-log( 7353): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 7353): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7353): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE_AND_WIFI
,W/bt-smp  ( 3245): Key(LSB ~ MSB) = 5a f7 b6 c7 af d3 57 20 0a 7f eb d2 fa dd 35 5d 
W/bt-smp  ( 3245): Plain text(LSB ~ MSB) = 08 64 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3245): Encrypted text(LSB ~ MSB) = e2 32 1e a7 77 ad 07 0f cf 3e 49 6f 72 7f d3 b6 
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749799.7353
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): stop scan
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue emtpy, scan stopped
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749799.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7353): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7353): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,D/BluetoothSocket( 7353): bindListen(), new LocalSocket 
D/BluetoothSocket( 7353): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7353): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28ba1639
D/BluetoothSocket( 7353): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: OK
I/io.jxcore.node.ConnectionHelper( 7353): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749799.7353
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): createAdvertiseData: From: 1453396749799.7353 b6a44ad1-d319-4b3a-815d-8b805a47fb51 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): 7C:F9:E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7353): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=567c7d2c-41e9-4cfb-b9ad-0dd6f60c2edc
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=567c7d2c-41e9-4cfb-b9ad-0dd6f60c2edc, clientIf=6
D/BluetoothLeAdvertiser( 7353): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 3245): message : 0
,D/BtGatt.AdvertiseManager( 3245): number of adv instance running0
D/BtGatt.AdvertiseManager( 3245): size of list is =0
,D/BtGatt.AdvertiseManager( 3245): starting advertising
D/BtGatt.AdvertiseManager( 3245): isDualWavefalse
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): starting multi advertising
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 3245): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=f2a3a4c6-655c-4696-a2a9-ea7f230784df
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=f2a3a4c6-655c-4696-a2a9-ea7f230784df, clientIf=7
D/BluetoothLeScanner( 7353): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 3245): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3245): handling starting scan
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749799.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749799.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749799.7353","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 3245): allow scan with filters
D/BtGatt.ScanManager( 3245): set filter index= 10 for clientIf= 7
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: INITIALIZED
D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): start: Starting P2P device discovery...
D/WifiP2pService(  901): InactiveState{ what=139292 }
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 3245): :scan window =2000 Scan interval = 5000
D/WifiP2pService(  901): P2pEnabledState{ what=139292 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: RUNNING_BLE_AND_WIFI
D/WifiP2pService(  901): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749799.7353
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): add a new client
I/io.jxcore.node.ConnectionHelper( 7353): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: Already running
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local service added successfully
D/WifiP2pService(  901): InactiveState{ what=139265 }
D/WifiP2pService(  901): P2pEnabledState{ what=139265 }
D/WifiService(  901): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  901): callSECApi what=74
D/WifiStateMachine(  901): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  901): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1274): USE_NETWORK : USE_NETWORK OFF
,I/jxcore-log( 7353): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 7353): 
I/wpa_supplicant( 1274): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 7353): stop
,D/WifiP2pService(  901): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): shutdown
D/BluetoothSocket( 7353): close() in, this: android.bluetooth.BluetoothSocket@251aea8a, channel: 6, state: LISTENING
D/BluetoothSocket( 7353): close() this: android.bluetooth.BluetoothSocket@251aea8a, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28ba1639, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@30a818fbmSocket: android.net.LocalSocket@3c514d18 impl:android.net.LocalSocketImpl@2cab5371 fd:FileDescriptor[116]
D/BluetoothSocket( 7353): Closing mSocket: android.net.LocalSocket@3c514d18 impl:android.net.LocalSocketImpl@2cab5371 fd:FileDescriptor[116]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WifiP2pService(  901): InactiveState{ what=139268 }
I/wpa_supplicant( 1274): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.AdvertiseManager( 3245): message : 1
D/BtGatt.AdvertiseManager( 3245): stop advertise for client 6
D/BtGatt.AdvertiseManager( 3245):  dualWaveClientIf = 0client.clientIf6
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: -1
D/WifiP2pService(  901): InactiveState{ what=147493 }
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): P2pEnabledState{ what=147493 }
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
D/WifiP2pService(  901): InactiveState{ what=139268 }
,D/BtGatt.GattService( 3245): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 3245): Client app is not null!
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3245): stopScan() - queue size =1
,D/BtGatt.ScanManager( 3245): filter size is 1
D/BtGatt.ScanManager( 3245): delete FilterIndex - 10
D/BtGatt.GattService( 3245): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: NOT_INITIALIZED
W/bt-smp  ( 3245): Key(LSB ~ MSB) = 5a f7 b6 c7 af d3 57 20 0a 7f eb d2 fa dd 35 5d 
W/bt-smp  ( 3245): Plain text(LSB ~ MSB) = fe 72 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopWifiPeerDiscovery: Stopped
W/bt-smp  ( 3245): Encrypted text(LSB ~ MSB) = ef f9 74 6e fc 7c 09 8f ae 3c 7f 21 f2 ca 46 71 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): release: No more listeners, de-initializing...
D/bt_vendor( 3245): op for 7
D/WifiP2pService(  901): InactiveState{ what=139298 }
D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: No more listeners, de-initializing...
D/WifiP2pService(  901): P2pEnabledState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: NOT_STARTED
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): stop scan
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log( 7353): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 7353): 
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749879.7353
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
D/WifiP2pService(  901): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local services cleared successfully
,D/WifiP2pService(  901): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
D/WifiP2pService(  901): InactiveState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749879.7353","ra":"7C:F9:0E:34:8A:A0"}
D/WifiP2pService(  901): P2pEnabledState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): setConnectionTimeout: 15000
D/WifiP2pService(  901): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7353): Service requests cleared successfully
W/BluetoothAdapter( 7353): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket( 7353): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
D/BluetoothSocket( 7353): bindListen(), new LocalSocket 
D/BluetoothSocket( 7353): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7353): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25d549d7
D/BluetoothSocket( 7353): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: OK
I/io.jxcore.node.ConnectionHelper( 7353): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749879.7353
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): createAdvertiseData: From: 1453396749879.7353 b6a44ad1-d319-4b3a-815d-8b805a47fb51 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): 7C:F9:E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7353): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BtGatt.GattService( 3245): registerClient() - UUID=87a81656-1a9d-4ac6-bd03-9bd8bab508ac
D/BtGatt.GattService( 3245): onClientRegistered() - UUID=87a81656-1a9d-4ac6-bd03-9bd8bab508ac, clientIf=6
D/BluetoothLeAdvertiser( 7353): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 3245): message : 0
D/BtGatt.AdvertiseManager( 3245): number of adv instance running0
D/BtGatt.AdvertiseManager( 3245): size of list is =0
D/BtGatt.AdvertiseManager( 3245): starting advertising
D/BtGatt.AdvertiseManager( 3245): isDualWavefalse
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.GattService( 3245): onAdvertiseInstanceEnabled() - clientIf=6, status=0
D/BtGatt.AdvertiseManager( 3245): starting multi advertising
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.GattService( 3245): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 3245): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
D/BtGatt.GattService( 3245): registerClient() - UUID=1a79dade-9e59-4a54-a1b3-e97dce44dea0
D/BtGatt.GattService( 3245): onClientRegistered() - UUID=1a79dade-9e59-4a54-a1b3-e97dce44dea0, clientIf=7
D/BluetoothLeScanner( 7353): onClientRegistered() - status=0 clientIf=7
D/BtGatt.GattService( 3245): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3245): handling starting scan
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.GattService( 3245): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): allow scan with filters
D/BtGatt.ScanManager( 3245): set filter index= 11 for clientIf= 7
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749879.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749879.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749879.7353","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/bt_vendor( 3245): op for 7
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=1
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 3245): :scan window =2000 Scan interval = 5000
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/bt_vendor( 3245): op for 7
D/WifiP2pService(  901): InactiveState{ what=139292 }
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): P2pEnabledState{ what=139292 }
D/WifiP2pService(  901): P2pEnabledState add service
D/WifiP2pService(  901): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: INITIALIZED
D/WifiP2pService(  901): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): start: Starting P2P device discovery...
D/WifiP2pService(  901): P2pEnabledState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiService(  901): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 7353): start: OK
I/WifiStateMachine(  901): callSECApi what=74
D/WifiStateMachine(  901): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  901): callSECApiBoolean - ID [13]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749879.7353
I/wpa_supplicant( 1274): USE_NETWORK : USE_NETWORK OFF
I/jxcore-log( 7353): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 7353): 
I/io.jxcore.node.ConnectionHelper( 7353): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): stop: Stopping Bluetooth...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: Already running
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): shutdown
D/BluetoothSocket( 7353): close() in, this: android.bluetooth.BluetoothSocket@1b78a730, channel: 6, state: LISTENING
D/BluetoothSocket( 7353): close() this: android.bluetooth.BluetoothSocket@1b78a730, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25d549d7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@346fffa9mSocket: android.net.LocalSocket@194b892e impl:android.net.LocalSocketImpl@10899ccf fd:FileDescriptor[116]
D/BluetoothSocket( 7353): Closing mSocket: android.net.LocalSocket@194b892e impl:android.net.LocalSocketImpl@10899ccf fd:FileDescriptor[116]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant( 1274): p2p0: P2P: Reject scan trigger since one is already pending
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): discovery change broadcast true
D/BtGatt.AdvertiseManager( 3245): message : 1
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery started successfully
D/BtGatt.AdvertiseManager( 3245): stop advertise for client 6
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: STARTED
D/BtGatt.AdvertiseManager( 3245):  dualWaveClientIf = 0client.clientIf6
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: -1
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WifiP2pService(  901): InactiveState{ what=139268 }
I/wpa_supplicant( 1274): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
D/WifiP2pService(  901): InactiveState{ what=147493 }
D/BtGatt.GattService( 3245): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 3245): Client app is not null!
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): P2pEnabledState{ what=147493 }
D/BtGatt.GattService( 3245): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: false
D/WifiP2pService(  901): discovery change broadcast false
D/BtGatt.GattService( 3245): stopScan() - queue size =1
D/BtGatt.ScanManager( 3245): filter size is 1
D/BtGatt.ScanManager( 3245): delete FilterIndex - 11
D/BtGatt.GattService( 3245): unregisterClient() - clientIf=7
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopBlePeerDiscovery: Stopped
D/WifiP2pService(  901): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): stop: Stopping P2P device discovery...
W/bt-smp  ( 3245): Key(LSB ~ MSB) = 5a f7 b6 c7 af d3 57 20 0a 7f eb d2 fa dd 35 5d 
W/bt-smp  ( 3245): Plain text(LSB ~ MSB) = 06 3a 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3245): Encrypted text(LSB ~ MSB) = aa 1d 4e e7 bb 44 e4 33 09 f6 ca 58 eb 55 57 2c 
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: false
D/bt_vendor( 3245): op for 7
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopWifiPeerDiscovery: Stopped
D/WifiP2pService(  901): InactiveState{ what=139298 }
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): release: No more listeners, de-initializing...
D/WifiP2pService(  901): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 7353): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 7353): 
D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.ScanManager( 3245): stop scan
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/bt_vendor( 3245): op for 7
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749960.7353
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
D/WifiP2pService(  901): remove client information from framework
D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
D/WifiP2pService(  901): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): InactiveState{ what=139307 }
D/WifiP2pService(  901): P2pEnabledState{ what=139307 }
D/WifiP2pService(  901): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7353): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749960.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): startListeningForIncomingConnections: Starting...
W/BluetoothAdapter( 7353): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket( 7353): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
D/BluetoothSocket( 7353): bindListen(), new LocalSocket 
D/BluetoothSocket( 7353): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7353): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d9fed65
D/BluetoothSocket( 7353): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: OK
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7353): start: Using peer discovery mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749960.7353
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): createAdvertiseData: From: 1453396749960.7353 b6a44ad1-d319-4b3a-815d-8b805a47fb51 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): 7C:F9:E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7353): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=08e75ec3-ed8e-436e-bdca-e39ad0b808fc
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=08e75ec3-ed8e-436e-bdca-e39ad0b808fc, clientIf=6
,D/BluetoothLeAdvertiser( 7353): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 3245): message : 0
,D/BtGatt.AdvertiseManager( 3245): number of adv instance running0
,D/BtGatt.AdvertiseManager( 3245): size of list is =0
,D/BtGatt.AdvertiseManager( 3245): starting advertising
D/BtGatt.AdvertiseManager( 3245): isDualWavefalse
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): starting multi advertising
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 3245): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=af480a81-332d-41ef-a30a-94bd62f4bb49
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=af480a81-332d-41ef-a30a-94bd62f4bb49, clientIf=7
D/BluetoothLeScanner( 7353): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 3245): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3245): handling starting scan
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749960.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749960.7353","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1453396749960.7353","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3245): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 3245): allow scan with filters
D/BtGatt.ScanManager( 3245): set filter index= 12 for clientIf= 7
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
,D/WifiP2pService(  901): InactiveState{ what=139292 }
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=1
D/bt_vendor( 3245): op for 7
D/WifiP2pService(  901): P2pEnabledState{ what=139292 }
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 3245): :scan window =2000 Scan interval = 5000
D/WifiP2pService(  901): P2pEnabledState add service
,D/WifiP2pService(  901): add a new client
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): start: Starting P2P device discovery...
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): InactiveState{ what=139265 }
,D/WifiP2pService(  901): P2pEnabledState{ what=139265 }
D/WifiService(  901): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  901): callSECApi what=74
D/WifiStateMachine(  901): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  901): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1274): USE_NETWORK : USE_NETWORK OFF
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396749960.7353
,I/io.jxcore.node.ConnectionHelper( 7353): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
,I/jxcore-log( 7353): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 7353): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
I/io.jxcore.node.ConnectionHelper( 7353): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): shutdown
D/BluetoothSocket( 7353): close() in, this: android.bluetooth.BluetoothSocket@3b0f9006, channel: 6, state: LISTENING
D/BluetoothSocket( 7353): close() this: android.bluetooth.BluetoothSocket@3b0f9006, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d9fed65, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e2656c7mSocket: android.net.LocalSocket@19adc4f4 impl:android.net.LocalSocketImpl@29b7641d fd:FileDescriptor[116]
D/BluetoothSocket( 7353): Closing mSocket: android.net.LocalSocket@19adc4f4 impl:android.net.LocalSocketImpl@29b7641d fd:FileDescriptor[116]
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
I/wpa_supplicant( 1274): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/WifiP2pService(  901): discovery change broadcast true
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stop: Stopping peer discovery...
,I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: NOT_STARTED
D/WifiP2pService(  901): InactiveState{ what=139268 }
,I/wpa_supplicant( 1274): P2P-FIND-STOPPED 
,D/BtGatt.AdvertiseManager( 3245): message : 1
,D/BtGatt.AdvertiseManager( 3245): stop advertise for client 6
D/BtGatt.AdvertiseManager( 3245):  dualWaveClientIf = 0client.clientIf6
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
D/WifiP2pService(  901): InactiveState{ what=147493 }
,D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: -1
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  901): discovery change broadcast false
,D/BtGatt.GattService( 3245): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 3245): Client app is not null!
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3245): stopScan() - queue size =1
,W/bt-smp  ( 3245): Key(LSB ~ MSB) = 5a f7 b6 c7 af d3 57 20 0a 7f eb d2 fa dd 35 5d 
W/bt-smp  ( 3245): Plain text(LSB ~ MSB) = bf 81 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3245): Encrypted text(LSB ~ MSB) = ec 7b 45 b7 de ce 73 c1 41 c0 11 fa d7 a3 88 bb 
,D/WifiP2pService(  901): InactiveState{ what=139268 }
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.GattService( 3245): unregisterClient() - clientIf=7
,D/BtGatt.ScanManager( 3245): filter size is 1
,D/BtGatt.ScanManager( 3245): delete FilterIndex - 12
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): stop: Stopping services
,D/WifiP2pService(  901): InactiveState{ what=139298 }
,D/bt_vendor( 3245): op for 7
D/WifiP2pService(  901): P2pEnabledState{ what=139298 }
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): stop: Stopping P2P device discovery...
D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): stop scan
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue emtpy, scan stopped
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: No more listeners, de-initializing...
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: NOT_STARTED
D/WifiP2pService(  901): remove client information from framework
,I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiP2pService(  901): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
D/WifiP2pService(  901): InactiveState{ what=139307 }
,D/WifiP2pService(  901): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  901): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7353): Service requests cleared successfully
,I/jxcore-log( 7353): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396750339.7353
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396750339.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7353): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7353): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,D/BluetoothSocket( 7353): bindListen(), new LocalSocket 
D/BluetoothSocket( 7353): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 7353): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16a79863
D/BluetoothSocket( 7353): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: OK
I/io.jxcore.node.ConnectionHelper( 7353): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396750339.7353
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): createAdvertiseData: From: 1453396750339.7353 b6a44ad1-d319-4b3a-815d-8b805a47fb51 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): 7C:F9:E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7353): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=37fe3ce3-d335-4ef3-bd2b-54434439be2f
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=37fe3ce3-d335-4ef3-bd2b-54434439be2f, clientIf=6
,D/BluetoothLeAdvertiser( 7353): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 3245): message : 0
,D/BtGatt.AdvertiseManager( 3245): number of adv instance running0
,D/BtGatt.AdvertiseManager( 3245): size of list is =0
,D/BtGatt.AdvertiseManager( 3245): starting advertising
,D/BtGatt.AdvertiseManager( 3245): isDualWavefalse
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): starting multi advertising
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 3245): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=ca91cf52-f1ac-4abb-8dcb-b879ad83c530
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=ca91cf52-f1ac-4abb-8dcb-b879ad83c530, clientIf=7
,D/BluetoothLeScanner( 7353): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 3245): start scan with filters
,D/BtGatt.ScanManager( 3245): handling starting scan
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): allow scan with filters
,D/BtGatt.ScanManager( 3245): set filter index= 13 for clientIf= 7
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
I/BtGatt.ScanManager( 3245): :scan window =2000 Scan interval = 5000
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396750339.7353","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396750339.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1453396750339.7353","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): InactiveState{ what=139292 }
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  901): P2pEnabledState add service
,D/WifiP2pService(  901): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): start: Starting P2P device discovery...
,D/WifiP2pService(  901): InactiveState{ what=139265 }
,D/WifiP2pService(  901): P2pEnabledState{ what=139265 }
,D/WifiService(  901): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  901): callSECApi what=74
,D/WifiStateMachine(  901): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  901): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1274): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1274): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396750339.7353
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 7353): start: OK
,D/WifiP2pService(  901): discovery change broadcast true
,I/jxcore-log( 7353): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 7353): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/WifiP2pService(  901): InactiveState{ what=139268 }
,I/wpa_supplicant( 1274): P2P-FIND-STOPPED 
,I/jxcore-log( 7353): ok 75 Cannot call startBroadcasting twice
I/jxcore-log( 7353): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
,D/WifiP2pService(  901): InactiveState{ what=147493 }
,D/WifiP2pService(  901): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  901): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
,D/WifiP2pService(  901): InactiveState{ what=139268 }
,I/io.jxcore.node.ConnectionHelper( 7353): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): shutdown
,D/BluetoothSocket( 7353): close() in, this: android.bluetooth.BluetoothSocket@db8be8c, channel: 6, state: LISTENING
D/BluetoothSocket( 7353): close() this: android.bluetooth.BluetoothSocket@db8be8c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16a79863, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@dfff9d5mSocket: android.net.LocalSocket@3da75ea impl:android.net.LocalSocketImpl@10edb0db fd:FileDescriptor[116]
,D/BluetoothSocket( 7353): Closing mSocket: android.net.LocalSocket@3da75ea impl:android.net.LocalSocketImpl@10edb0db fd:FileDescriptor[116]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 3245): message : 1
,D/BtGatt.AdvertiseManager( 3245): stop advertise for client 6
,D/BtGatt.AdvertiseManager( 3245):  dualWaveClientIf = 0client.clientIf6
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: -1
,D/BtGatt.GattService( 3245): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 3245): Client app is not null!
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): unregisterClient() - clientIf=6
,W/bt-smp  ( 3245): Key(LSB ~ MSB) = 5a f7 b6 c7 af d3 57 20 0a 7f eb d2 fa dd 35 5d 
,W/bt-smp  ( 3245): Plain text(LSB ~ MSB) = 06 ad 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3245): Encrypted text(LSB ~ MSB) = ad 4b 36 47 b4 7e 7b ba 7d fc 00 33 66 1d f2 0b 
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3245): stopScan() - queue size =1
,D/BtGatt.ScanManager( 3245): filter size is 1
,D/BtGatt.ScanManager( 3245): delete FilterIndex - 13
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
,D/BtGatt.GattService( 3245): unregisterClient() - clientIf=7
,D/BtGatt.ScanManager( 3245): stop scan
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsScannerStartedChanged: false
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsBlePeerDiscoveryStartedChanged: true
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): stop: Stopping services
,D/WifiP2pService(  901): InactiveState{ what=139298 }
,D/WifiP2pService(  901): P2pEnabledState{ what=139298 }
,D/WifiP2pService(  901): P2pEnabledState clear service
,D/WifiP2pService(  901): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): release: No more listeners, de-initializing...
D/WifiP2pService(  901): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
,I/jxcore-log( 7353): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 7353): 
,D/WifiP2pService(  901): InactiveState{ what=139307 }
,D/WifiP2pService(  901): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  901): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7353): Service requests cleared successfully
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396750783.7353
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396750783.7353","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7353): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7353): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,D/BluetoothSocket( 7353): bindListen(), new LocalSocket 
,D/BluetoothSocket( 7353): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 7353): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22535e51
,D/BluetoothSocket( 7353): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: OK
,I/io.jxcore.node.ConnectionHelper( 7353): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396750783.7353
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): createAdvertiseData: From: 1453396750783.7353 b6a44ad1-d319-4b3a-815d-8b805a47fb51 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): 7C:F9:E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7353): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=89259507-e4ae-4e63-ab2e-9adb68a14777
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=89259507-e4ae-4e63-ab2e-9adb68a14777, clientIf=6
,D/BluetoothLeAdvertiser( 7353): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 3245): message : 0
,D/BtGatt.AdvertiseManager( 3245): number of adv instance running0
,D/BtGatt.AdvertiseManager( 3245): size of list is =0
,D/BtGatt.AdvertiseManager( 3245): starting advertising
,D/BtGatt.AdvertiseManager( 3245): isDualWavefalse
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): starting multi advertising
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 3245): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=91e84a10-d1b5-4a2a-a0a1-1f0d4297be96
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=91e84a10-d1b5-4a2a-a0a1-1f0d4297be96, clientIf=7
,D/BluetoothLeScanner( 7353): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 3245): start scan with filters
,D/BtGatt.ScanManager( 3245): handling starting scan
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): allow scan with filters
,D/BtGatt.ScanManager( 3245): set filter index= 14 for clientIf= 7
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=1
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager( 3245): :scan window =2000 Scan interval = 5000
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396750783.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396750783.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1453396750783.7353","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): InactiveState{ what=139292 }
,D/WifiP2pService(  901): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  901): P2pEnabledState add service
D/WifiP2pService(  901): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): start: Starting P2P device discovery...
,D/WifiP2pService(  901): InactiveState{ what=139265 }
,D/WifiP2pService(  901): P2pEnabledState{ what=139265 }
,D/WifiService(  901): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  901): callSECApi what=74
D/WifiStateMachine(  901): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  901): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1274): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService(  901): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396750783.7353
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/WifiP2pService(  901): InactiveState{ what=139268 }
I/io.jxcore.node.ConnectionHelper( 7353): start: OK
,I/wpa_supplicant( 1274): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
,D/WifiP2pService(  901): InactiveState{ what=147493 }
,D/WifiP2pService(  901): P2pEnabledState{ what=147493 }
D/WifiP2pService(  901): discovery change broadcast false
,I/jxcore-log( 7353): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 7353): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 7353): connect: Trying to connect to peer with ID foobar
,D/WifiP2pService(  901): InactiveState{ what=139268 }
,W/io.jxcore.node.ConnectionHelper( 7353): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,E/io.jxcore.node.ConnectionHelper( 7353): connect: Invalid Bluetooth address: foobar
,I/jxcore-log( 7353): ok 78 Should not connect to a bad peer
I/jxcore-log( 7353): 
,I/io.jxcore.node.ConnectionHelper( 7353): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): shutdown
D/BluetoothSocket( 7353): close() in, this: android.bluetooth.BluetoothSocket@19ffd842, channel: 6, state: LISTENING
,D/BluetoothSocket( 7353): close() this: android.bluetooth.BluetoothSocket@19ffd842, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22535e51, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@adf6053mSocket: android.net.LocalSocket@3a77d90 impl:android.net.LocalSocketImpl@3f28689 fd:FileDescriptor[116]
D/BluetoothSocket( 7353): Closing mSocket: android.net.LocalSocket@3a77d90 impl:android.net.LocalSocketImpl@3f28689 fd:FileDescriptor[116]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 3245): message : 1
,D/BtGatt.AdvertiseManager( 3245): stop advertise for client 6
,D/BtGatt.AdvertiseManager( 3245):  dualWaveClientIf = 0client.clientIf6
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: -1
,D/BtGatt.GattService( 3245): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/bt_vendor( 3245): op for 7
D/BtGatt.GattService( 3245): Client app is not null!
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3245): stopScan() - queue size =1
,D/BtGatt.ScanManager( 3245): filter size is 1
,D/BtGatt.ScanManager( 3245): delete FilterIndex - 14
,D/BtGatt.GattService( 3245): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsBlePeerDiscoveryStartedChanged: true
,W/bt-smp  ( 3245): Key(LSB ~ MSB) = 5a f7 b6 c7 af d3 57 20 0a 7f eb d2 fa dd 35 5d 
W/bt-smp  ( 3245): Plain text(LSB ~ MSB) = f6 3b 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3245): Encrypted text(LSB ~ MSB) = 73 e7 41 62 39 4a d0 e1 0b 0e 3a aa ce fa e4 0b 
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): stop: Stopping services
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/WifiP2pService(  901): InactiveState{ what=139298 }
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.ScanManager( 3245): stop scan
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue emtpy, scan stopped
,D/WifiP2pService(  901): P2pEnabledState{ what=139298 }
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
D/WifiP2pService(  901): P2pEnabledState clear service
,D/WifiP2pService(  901): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): stop: Stopping P2P device discovery...
,D/WifiP2pService(  901): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: NOT_INITIALIZED
,D/WifiP2pService(  901): InactiveState{ what=139307 }
,D/WifiP2pService(  901): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  901): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7353): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 7353): ok 79 Should be able to call stopBroadcasting without error
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396751243.7353
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396751243.7353","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7353): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7353): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,D/BluetoothSocket( 7353): bindListen(), new LocalSocket 
,D/BluetoothSocket( 7353): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 7353): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bf5aeaf
,D/BluetoothSocket( 7353): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): start: OK
,I/io.jxcore.node.ConnectionHelper( 7353): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396751243.7353
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): createAdvertiseData: From: 1453396751243.7353 b6a44ad1-d319-4b3a-815d-8b805a47fb51 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7353): 7C:F9:E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7353): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/bt_upio ( 3245): ..proc_btwrite_timeout..
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Waiting for incoming connections...
,D/BtGatt.GattService( 3245): registerClient() - UUID=204b4f03-e8a9-4ed8-86e9-310a1c331323
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=204b4f03-e8a9-4ed8-86e9-310a1c331323, clientIf=6
,D/BluetoothLeAdvertiser( 7353): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 3245): message : 0
,D/BtGatt.AdvertiseManager( 3245): number of adv instance running0
,D/BtGatt.AdvertiseManager( 3245): size of list is =0
,D/BtGatt.AdvertiseManager( 3245): starting advertising
,D/BtGatt.AdvertiseManager( 3245): isDualWavefalse
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_upio ( 3245): proc btwrite assertion
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): starting multi advertising
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 3245): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 3245): registerClient() - UUID=e848dfae-97d1-4f7c-9a7b-e1a7b36ee919
,D/BtGatt.GattService( 3245): onClientRegistered() - UUID=e848dfae-97d1-4f7c-9a7b-e1a7b36ee919, clientIf=7
,D/BluetoothLeScanner( 7353): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 3245): start scan with filters
,D/BtGatt.ScanManager( 3245): handling starting scan
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): allow scan with filters
,D/BtGatt.ScanManager( 3245): set filter index= 15 for clientIf= 7
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
I/BtGatt.ScanManager( 3245): :scan window =2000 Scan interval = 5000
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7353): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396751243.7353","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1453396751243.7353","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1453396751243.7353","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  901): InactiveState{ what=139292 }
,D/WifiP2pService(  901): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  901): P2pEnabledState add service
,D/WifiP2pService(  901): add a new client
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): start: Starting P2P device discovery...
,D/WifiP2pService(  901): InactiveState{ what=139265 }
,D/WifiP2pService(  901): P2pEnabledState{ what=139265 }
,D/WifiService(  901): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  901): callSECApi what=74
D/WifiStateMachine(  901): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  901): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1274): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1274): p2p0: P2P: Reject scan trigger since one is already pending
,D/WifiP2pService(  901): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1453396751243.7353
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7353): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/WifiP2pService(  901): InactiveState{ what=139268 }
,I/io.jxcore.node.ConnectionHelper( 7353): start: OK
,I/wpa_supplicant( 1274): P2P-FIND-STOPPED 
,I/jxcore-log( 7353): ok 80 Should be able to call startBroadcasting without error
I/jxcore-log( 7353): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
,D/WifiP2pService(  901): InactiveState{ what=147493 }
,D/WifiP2pService(  901): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  901): discovery change broadcast false
,D/io.jxcore.node.ConnectionHelper( 7353): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
,E/io.jxcore.node.ConnectionHelper( 7353): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
,D/io.jxcore.node.ConnectionHelper( 7353): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7353): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: RESTARTING
,D/WifiP2pService(  901): InactiveState{ what=139268 }
,I/jxcore-log( 7353): ok 81 Disconnect should fail to a non-existant peer 
I/jxcore-log( 7353): 
,I/io.jxcore.node.ConnectionHelper( 7353): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): shutdown
D/BluetoothSocket( 7353): close() in, this: android.bluetooth.BluetoothSocket@1656ea8, channel: 6, state: LISTENING
D/BluetoothSocket( 7353): close() this: android.bluetooth.BluetoothSocket@1656ea8, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bf5aeaf, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3dd77dc1mSocket: android.net.LocalSocket@1578966 impl:android.net.LocalSocketImpl@2906c4a7 fd:FileDescriptor[116]
,D/BluetoothSocket( 7353): Closing mSocket: android.net.LocalSocket@1578966 impl:android.net.LocalSocketImpl@2906c4a7 fd:FileDescriptor[116]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7353): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7353): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7353): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 7353): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 3245): message : 1
,D/BtGatt.AdvertiseManager( 3245): stop advertise for client 6
,D/BtGatt.AdvertiseManager( 3245):  dualWaveClientIf = 0client.clientIf6
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.AdvertiseManager( 3245): logClientsSet() - status: -1
,D/BtGatt.GattService( 3245): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 3245): Client app is not null!
D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3245): stopScan() - queue size =1
,D/BtGatt.ScanManager( 3245): filter size is 1
D/BtGatt.ScanManager( 3245): delete FilterIndex - 15
,W/bt-smp  ( 3245): Key(LSB ~ MSB) = 5a f7 b6 c7 af d3 57 20 0a 7f eb d2 fa dd 35 5d 
W/bt-smp  ( 3245): Plain text(LSB ~ MSB) = 17 4d 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3245): Encrypted text(LSB ~ MSB) = ab e1 2f 0d f1 e2 1e 7c 45 ee 6f 89 df ab 55 70 
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BtGatt.GattService( 3245): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3245): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 3245): stop scan
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3245): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.GattService( 3245): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): onIsScannerStartedChanged: false
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7353): setIsStarted: true
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7353): stop: Stopping services
,D/WifiP2pService(  901): InactiveState{ what=139298 }
D/WifiP2pService(  901): P2pEnabledState{ what=139298 }
D/WifiP2pService(  901): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): stop: Stopping P2P device discovery...
D/WifiP2pService(  901): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7353): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): setState: NOT_INITIALIZED
D/WifiP2pService(  901): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7353): P2P device discovery stopped successfully
,D/WifiP2pService(  901): InactiveState{ what=139307 }
D/WifiP2pService(  901): P2pEnabledState{ what=139307 }
D/WifiP2pService(  901): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7353): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7353): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7353): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7353): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 7353): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 7353): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log( 7353): 
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 83 should be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 84 should not be equal
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # setup
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): # teardown
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 85 irrelevant messages should be ignored
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 86 relevant messages should not be ignored
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ok 87 messages from this device should be ignored
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): Tests Complete
I/jxcore-log( 7353): 
,I/chromium( 7353): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7353): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): Toggling radios to false
I/jxcore-log( 7353): 
,I/chromium( 7353): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,D/BluetoothAdapter( 7353): disable()
,D/SettingsProvider(  901): name = bluetooth_on
,D/BluetoothAdapterState( 3245): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 3245): Setting state to 13
,I/BluetoothAdapterState( 3245): Bluetooth adapter state changed: 12-> 13
,I/WifiManager( 7353): packageName : com.test.thalitest
,D/BluetoothAdapterService( 3245): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3245): updateAdapterState state is 13
,I/BluetoothPbapService( 3245): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService( 3245): Autoconnection is available 
,D/BluetoothAdapterService( 3245): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 3245): terminating service from this receiver
,D/BluetoothSocket( 3245): close() in, this: android.bluetooth.BluetoothSocket@31367095, channel: 19, state: LISTENING
,D/BluetoothSocket( 3245): close() this: android.bluetooth.BluetoothSocket@31367095, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21b266b4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@32b985aamSocket: android.net.LocalSocket@2b33e59b impl:android.net.LocalSocketImpl@65a8111 fd:FileDescriptor[72]
,D/BluetoothSocket( 3245): Closing mSocket: android.net.LocalSocket@2b33e59b impl:android.net.LocalSocketImpl@65a8111 fd:FileDescriptor[72]
,D/BluetoothAdapterProperties( 3245): onBluetoothDisable()
,D/SecContentProvider(  901): uri = 3 selection = isDiscoverableEnabled
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,I/BluetoothAdapterState( 3245): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3245): Scan Mode:20
,D/BluetoothAdapterState( 3245): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 3245): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 3245): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/BtOppRfcommListener( 3245): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3245): cmd socket is not created
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,E/bt-btm  ( 3245): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif ( 3245): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/btif_config_util( 3245): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 3245): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3245): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3245): L2CAP - PSM: 0x001b not found for deregistration
,D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/BluetoothPbap( 1318): Proxy object disconnected
,D/PbapServerProfile( 1318): Bluetooth service disconnected
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
,D/bt_vendor( 3245): op for 7
,D/bt_upio ( 3245): BT_WAKE is asserted already
E/ActivityThread( 3245): Service com.samsung.ble.BleAutoConnectService has leaked IntentReceiver com.samsung.ble.BleAutoConnectService$4@1c83208 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3245): android.app.IntentReceiverLeaked: Service com.samsung.ble.BleAutoConnectService has leaked IntentReceiver com.samsung.ble.BleAutoConnectService$4@1c83208 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3245): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:960)
E/ActivityThread( 3245): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:761)
E/ActivityThread( 3245): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1945)
E/ActivityThread( 3245): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1925)
E/ActivityThread( 3245): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1919)
E/ActivityThread( 3245): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
E/ActivityThread( 3245): 	at com.samsung.ble.BleAutoConnectService.onCreate(BleAutoConnectService.java:139)
E/ActivityThread( 3245): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 3245): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 3245): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 3245): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3245): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3245): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 3245): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3245): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3245): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 3245): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/InputMethodManagerService(  901): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  901): [BT Setting State] State =13
D/SecContentProvider(  901): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  901): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  901): mCursor = null
,D/WifiService(  901): setWifiEnabled: false pid=7353, uid=10191
E/WifiService(  901): Invoking mWifiStateMachine.setWifiEnabled
D/SettingsProvider(  901): name = wifi_on
,D/BluetoothTile( 1183): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/STATUSBAR-QSTileView( 1183): onStateChanged: Bluetooth
,I/SamsungIME( 1869): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,V/BluetoothEventManager( 1318): Received android.bluetooth.adapter.action.STATE_CHANGED
,I/jxcore-log( 7353): Radios toggled
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ****TEST TOOK:  ms ****
I/jxcore-log( 7353): 
,I/jxcore-log( 7353): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7353): 
,E/WifiStateMachine(  901): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1274): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1274): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1274): Skip scan - bUseNetwork false
E/WifiStateMachine(  901): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  901): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  901): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/BluetoothSocket( 3245): close() in, this: android.bluetooth.BluetoothSocket@2f614077, channel: 5, state: LISTENING
D/BluetoothSocket( 3245): close() this: android.bluetooth.BluetoothSocket@2f614077, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1778c2dd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2116e4e4mSocket: android.net.LocalSocket@3cd51d4d impl:android.net.LocalSocketImpl@c392002 fd:FileDescriptor[74]
D/BluetoothSocket( 3245): Closing mSocket: android.net.LocalSocket@3cd51d4d impl:android.net.LocalSocketImpl@c392002 fd:FileDescriptor[74]
I/BtOppRfcommListener( 3245): stopping Accept Thread
D/BluetoothSocket( 3245): close() in, this: android.bluetooth.BluetoothSocket@1f9f6d13, channel: 12, state: LISTENING
D/BluetoothSocket( 3245): close() this: android.bluetooth.BluetoothSocket@1f9f6d13, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3db9c07f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@39cf6b50mSocket: android.net.LocalSocket@1fe34149 impl:android.net.LocalSocketImpl@191d3a4e fd:FileDescriptor[77]
D/BluetoothSocket( 3245): Closing mSocket: android.net.LocalSocket@1fe34149 impl:android.net.LocalSocketImpl@191d3a4e fd:FileDescriptor[77]
I/BtOppRfcommListener( 3245): BluetoothSocket listen thread finished
E/WifiStateMachine(  901): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  901): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  901): do suspend true
,W/ContextImpl( 1318): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/WifiP2pService(  901): InactiveState{ what=143375 }
,D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
,D/CommandListener(  284): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/DockEventReceiver( 1318): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
E/WifiStateMachine(  901): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): ignoring duplicate network state non-change
D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 3
,I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
,I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,I/jxcore-log( 7353): Toggling radios to false
I/jxcore-log( 7353): 
,D/BluetoothAdapter( 7353): disable()
,I/WifiManager( 7353): packageName : com.test.thalitest
,E/WifiStateMachine(  901): scanCount==0 - aborting
,E/WifiStateMachine(  901): [1,453,396,752,663 ms] noteScanEnd no scan source
,D/WifiScanningService(  901): SCAN_AVAILABLE : 1
,D/WifiScanningService(  901): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService(  901): SCAN_AVAILABLE : 1
,D/RttService(  901): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/SecContentProvider(  901): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  901): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  901): mCursor = null
E/WifiStateMachine(  901): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,D/AuthorizationBluetoothService( 2185): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/bt_vendor( 3245): op for 6
D/bt_vendor( 3245): op for 7
D/bt_upio ( 3245): BT_WAKE is asserted already
D/bt_userial( 3245): RX termination
W/bt_userial( 3245): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3245): Leaving userial_read_thread()
W/bt-l2cap( 3245): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3245): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3245): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3245): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3245): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3245): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3245): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3245): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3245): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 3245): ag scb idx 1 not allocated
W/bt-btif ( 3245): ag scb idx 2 not allocated
E/bt-btif ( 3245): BTA AG is already disabled, ignoring ...
D/bt_userial( 3245): userial_close_reader Joined userial reader thread: 0
D/bt_vendor( 3245): op for 9
D/bt_hwcfg( 3245): hw_epilog_process
E/WifiStateMachine(  901): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/bt_vendor( 3245): op for 4
I/bt_userial_vendor( 3245): device fd = 65 close
,D/WifiService(  901): setWifiEnabled: false pid=7353, uid=10191
E/WifiService(  901): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider(  901): name = wifi_on
E/WifiController(  901): illegal state found both WifiController and WifiStateMachine
,D/WifiP2pService(  901): InactiveState{ what=131204 }
I/jxcore-log( 7353): Radios toggled
I/jxcore-log( 7353): 
,D/WifiP2pService(  901): P2pEnabledState{ what=131204 }
D/bt_vendor( 3245): op for 0
D/bt_upio ( 3245): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 3245): is_emulator_context : 0
D/bt_upio ( 3245): is_rfkill_disabled ? [0]
,D/WifiP2pService(  901): sending p2p connection changed broadcast: FAILED
,D/WifiDisplayController(  901): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/bt_vendor( 3245): cleanup
,D/WifiDisplayAdapter(  901): onP2pDisconnected
I/GKI_LINUX( 3245): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 3245): GKI_exit_task 0 done
I/GKI_LINUX( 3245): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 3245): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 3245): isSecureModeOn:false
D/BluetoothAdapterService( 3245): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 3245): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 3245): Not skipping com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 3245): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 3245): handleDebugAction() action=null
,W/BluetoothAdapterService( 3245): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.GattService( 3245): Received stop request...Stopping profile...
,D/BtGatt.GattService( 3245): stop()
D/BtGatt.AdvertiseManager( 3245): advertise clients cleared
,D/IpRemoteDisplayController(  901): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  901): WfdBridgeServer is already null
,D/BluetoothAdapterService( 3245): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@273765db
,W/BluetoothAdapterService( 3245): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3245): Not skipping com.android.bluetooth.a2dp.A2dpService
D/HeadsetService( 3245): Received stop request...Stopping profile...
,W/BluetoothAdapterService( 3245): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3245): Not skipping com.android.bluetooth.hid.HidService
,D/WifiP2pService(  901): sending p2p connection changed broadcast: DISCONNECTED
D/BluetoothAdapterService( 3245): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@273765db
,E/WifiStateMachine(  901): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController(  901): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  901): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  901): disconnect
D/WifiDisplayController(  901): updateConnection
D/WifiDisplayController(  901): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AudioService(  901): onServiceDisconnected: Bluetooth profile: 1
,D/ConnectivityService(  901): notifyType LOST for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EntConnectivity(  901): Not allowed due to - mEnabled false
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,W/BluetoothAdapterService( 3245): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524292
W/BluetoothAdapterService( 3245): Not skipping com.android.bluetooth.hdp.HealthService
,D/ConnectivityService(  901): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  901): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Disconnected - quitting
,E/WifiStateMachine(  901): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  901): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  901): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  901): NetworkAgent: NetworkAgent channel lost
D/TelephonyNetworkFactory( 1471): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/BluetoothAdapterService( 3245): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/AllShareCastTile( 1183): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,W/BluetoothAdapterService( 3245): Not skipping com.android.bluetooth.pan.PanService
D/CSLegacyTypeTracker(  901): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  901): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=false
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1183): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
D/ConnectivityManager.CallbackHandler( 2539): CM callback handler got msg 524292
,D/WifiP2pService(  901): P2pDisablingState
,D/WifiP2pService(  901): P2pDisablingState{ what=147458 }
D/WifiP2pService(  901): p2p socket connection lost
,W/BluetoothAdapterService( 3245): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/ConnectivityService(  901): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
W/BluetoothAdapterService( 3245): Not skipping com.android.bluetooth.map.BluetoothMapService
,E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  901): updateNetworkInfo()
,D/ConnectivityService(  901): ignoring duplicate network state non-change
,D/WifiDisplayController(  901): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter(  901): onP2pDisconnected
D/IpRemoteDisplayController(  901): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  901): WfdBridgeServer is already null
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
,D/WifiP2pService(  901): P2pDisabledState
,D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
,V/NetworkStats(  901): updateIfacesLocked()
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
V/NetworkStats(  901): performPollLocked(flags=0x1)
,E/WifiStateMachine(  901): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - enter - invokeEnterMethods
,E/WifiStateMachine(  901): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/NetworkStatsFactory(  901): UpdateStatsForKnox
,E/WifiStateMachine(  901): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  901): do suspend true
D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): 0
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1183): updateDataNetType()
D/StatusBar.NetworkController( 1183): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1183): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/HeadsetProfile( 1318): Bluetooth service disconnected
I/Hs20UtilService( 1318): Starting #12
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,V/NetworkStats(  901): advisePersistThreshold() given 9223372036854775, clamped to 2097152
I/Hs20UtilService( 1318): Message received 5007
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,W/BluetoothAdapterService( 3245): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,V/NetworkStats(  901): performPollLocked() took 13ms
,W/BluetoothAdapterService( 3245): Not skipping com.broadcom.bt.service.sap.SapService
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1183): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,D/WifiP2pService(  901): P2pDisabledState{ what=143375 }
,D/WifiP2pService(  901): DefaultState{ what=143375 }
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
,W/BluetoothAdapterService( 3245): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 3245): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 3245): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 3245): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 3245): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 3245): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 3245): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/BluetoothAdapterService( 3245): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 3245): Stopping profile services that were post enabled
E/BluetoothAdapterService(657941979)( 3245): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/A2dpService( 3245): Received stop request...Stopping profile...
V/Avrcp   ( 3245): doQuit
D/CommandListener(  284): Clearing all IP addresses on wlan0
,D/A2dpStateMachine( 3245): Exit Disconnected: -1
,E/WifiStateMachine(  901): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1318): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1318): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/Avrcp   ( 3245): Unregistering previous receiver
,I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
,E/WifiStateMachine(  901): stopping supplicant
,I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 1274): p2p0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine(  901): setWifiState: disabling
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,D/SmartBondingService(  901): getNetworkEnabled : wifi : false mobile : true
,D/SLocation(  901): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,I/wpa_supplicant( 1274): Blacklist: Clear (all) 
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,D/STATUSBAR-WifiQuickSettingButton( 1183): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1183): Wifi onReceive(0)
,D/STATUSBAR-QSTileView( 1183): onStateChanged: Wi-Fi
,D/HotspotTile( 1183): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/WifiCredService( 1318): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1183): onReceive : 0, 0
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 1183): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_wifi_dim.png
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/BluetoothAdapterService( 3245): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@273765db
,E/WifiStateMachine(  901): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/BluetoothA2dp(  901): Proxy object disconnected
D/AudioService(  901): onServiceDisconnected: Bluetooth profile: 2
,E/WifiStateMachine(  901): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/BluetoothAdapterService(657941979)( 3245): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 3492): Proxy object disconnected
D/BluetoothAdapterService( 3245): Profile still running: com.android.bluetooth.hid.HidService
,D/HidService( 3245): Received stop request...Stopping profile...
D/HidService( 3245): Stopping Bluetooth HidService
D/BluetoothAdapterService( 3245): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@273765db
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1318): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1318): MountReceiver.mPrefHandler - 7002
,D/BluetoothA2dp( 1318): Proxy object disconnected
D/A2dpProfile( 1318): Bluetooth service disconnected
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/BluetoothInputDevice( 1318): Proxy object disconnected
,D/HidProfile( 1318): Bluetooth service disconnected
,I/wpa_supplicant( 1274): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 1274): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1274): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1274): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/Zygote  ( 8353): MountEmulatedStorage()
,E/Zygote  ( 8353): v2
I/libpersona( 8353): KNOX_SDCARD checking this for 10074
,I/libpersona( 8353): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8353 uid=10074 gids={50074, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BluetoothHeadsetServiceJni( 3245): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3245): Cleaning up Bluetooth Handsfree callback object
I/SELinux ( 8353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/HealthService( 3245): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3245): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@273765db
,I/SELinux ( 8353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8353): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PanService( 3245): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3245): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@273765db
,D/BluetoothPan(  901): BluetoothPAN Proxy object disconnected
,D/BluetoothMapService( 3245): Received stop request...Stopping profile...
,D/BluetoothPan( 1318): BluetoothPAN Proxy object disconnected
D/PanProfile( 1318): Bluetooth service disconnected
,D/BluetoothAdapterService( 3245): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@273765db
,D/BluetoothMap( 1318): Proxy object disconnected
,D/SapService( 3245): Received stop request...Stopping profile...
D/SapService( 3245): Stopping Bluetooth SapService
D/BluetoothAdapterService( 3245): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@273765db
,E/BluetoothAdapterService(657941979)( 3245): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 3245): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 3245): Proxy object disconnected
D/BluetoothAdapterService( 3245): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 3245): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3245): GKI_exit_task 2 done
I/GKI_LINUX( 3245): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   ( 3245): cleanup
E/BluetoothAdapterService(657941979)( 3245): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3245): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHidServiceJni( 3245): Cleaning up Bluetooth HID Interface...
D/MapProfile( 1318): Bluetooth service disconnected
W/bt-btif ( 3245): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3245): Cleaning up Bluetooth GID callback object
,D/Bluetoothsap( 1318): BluetoothSAP Proxy object disconnected
D/SapProfile( 1318): Bluetooth service disconnected
,E/BluetoothAdapterService(657941979)( 3245): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3245): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 3245): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3245): Cleaning up Bluetooth Health object
,E/BluetoothAdapterService(657941979)( 3245): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3245): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3245): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3245): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(657941979)( 3245): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 3245): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
I/wpa_supplicant( 1274): Blacklist: Clear (all) 
D/BluetoothAdapterService( 3245): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(657941979)( 3245): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,D/BluetoothAdapterState( 3245): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3245): Setting state to 10
I/BluetoothAdapterState( 3245): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3245): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3245): updateAdapterState state is 10
,D/BluetoothAdapterService( 3245): Autoconnection is available 
W/BluetoothSAPServiceJni( 3245): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
D/BluetoothAdapterService( 3245): updateAdapterState prevState = 13newState = 10
,I/BluetoothAdapterState( 3245): Entering OffState
W/BluetoothSAPServiceJni( 3245): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothPbap( 1318): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  901): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3492): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 1318): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/BluetoothMap( 1318): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/Bluetoothsap( 1318): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1318): Unbinding service...
,D/TimaKeyStoreProvider( 8353): TimaSignature is unavailable
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/ActivityThread( 8353): Added TimaKeyStore provider
,D/BluetoothA2dp( 1318): onBluetoothStateChange: up=false
D/BluetoothA2dp( 3245): onBluetoothStateChange: up=false
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/BluetoothManagerService(  901): Broadcasting onBluetoothServiceDown() to 13 receivers.
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/BluetoothManagerService(  901): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,W/InputMethodManagerService(  901): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
I/InputMethodManagerService(  901): [BT Setting State] State =10
I/InputMethodManagerService(  901): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothAdapter( 1183): 825996618: getState() :  mService = null. Returning STATE_OFF
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,I/GKI_LINUX( 3245): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3245): GKI_exit_task 1 done
,I/GKI_LINUX( 3245): GKI_shutdown(): task [BTIF] terminated
D/AndroidRuntime( 8345): 
D/AndroidRuntime( 8345): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/BluetoothTile( 1183): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/STATUSBAR-QSTileView( 1183): onStateChanged: Bluetooth
D/BluetoothAdapter( 1183): 825996618: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1183): 825996618: getState() :  mService = null. Returning STATE_OFF
I/SamsungIME( 1869): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/BluetoothServiceJni( 3245): cleanupNative: return from cleanup
,D/[CarModeFW]( 7424): ConnectivityManager-handleMessage INITIAL_STATE_OFF
,V/BluetoothEventManager( 1318): Received android.bluetooth.adapter.action.STATE_CHANGED
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/AndroidRuntime( 8345): CheckJNI is OFF
,D/AndroidRuntime( 8345): setted country_code = Poland
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/AndroidRuntime( 8345): setted countryiso_code = PL
,D/AndroidRuntime( 8345): setted sales_code = XEO
I/art     ( 3245): System.exit called, status: 0
I/AndroidRuntime( 3245): VM exiting with result code 0, cleanup skipped.
,D/AndroidRuntime( 8345): readGMSProperty: start
D/AndroidRuntime( 8345): readGMSProperty: already setted!!
,D/AndroidRuntime( 8345): readGMSProperty: end
D/AndroidRuntime( 8345): addProductProperty: start
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/ResourcesManager( 8353): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/BluetoothAdapter( 2185): 656093381: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2185): 656093381: getState() :  mService = null. Returning STATE_OFF
,D/FileShare-Server( 8353): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager(  901): Process com.android.bluetooth (pid 3245)(adj 0) has died(63,605)
,I/ActivityManager(  901): Killing 7259:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,I/Hs20UtilService( 1318): Starting #13
I/Hs20UtilService( 1318): Message received 5007
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1318): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1318): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6924): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6924): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6924): StateMachine : Current State = 1
D/SecurityLogAgent( 6924): StateMachine : Changed Current State = 1
,I/wpa_supplicant( 1274): wlan0: CTRL-EVENT-TERMINATING 
E/WifiStateMachine(  901): Supplicant connection lost
,E/WifiStateMachine(  901): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-HAL(  901): callSECApiBoolean - ID [21]
E/WifiStateMachine(  901): setWifiState: disabled
,D/Tethering(  901): InitialState.processMessage what=4
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation(  901): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/SmartBondingService(  901): getNetworkEnabled : wifi : false mobile : true
,E/Tethering(  901): No numeric data
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1183): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1183): Wifi onReceive(1)
D/STATUSBAR-QSTileView( 1183): onStateChanged: Wi-Fi
,V/BitmapFactory( 1183): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_wifi_off.png
,D/HotspotTile( 1183): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1183): onReceive : 1, 0
,D/Tethering(  901): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiCredService( 1318): Action received :android.net.wifi.WIFI_STATE_CHANGED
,V/NetworkStats(  901): performPollLocked(flags=0x1)
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  901): UpdateStatsForKnox
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/HotspotTile( 1183): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1183): updateTetherState():false, false
,V/NetworkStats(  901): performPollLocked() took 4ms
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,W/libprocessgroup(  901): failed to open /acct/uid_10050/pid_7259/cgroup.procs: No such file or directory
,W/Settings( 2185): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ContextImpl( 1318): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 1318): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8391): MountEmulatedStorage()
E/Zygote  ( 8391): v2
I/libpersona( 8391): KNOX_SDCARD checking this for 1002
I/libpersona( 8391): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=8391 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/SELinux ( 8391): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8391): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8391): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/AffinityControl( 8345): AffinityControl: registerfunction enter
,D/TimaKeyStoreProvider( 8391): TimaSignature is unavailable
,D/ActivityThread( 8391): Added TimaKeyStore provider
,D/AndroidRuntime( 8345): Calling main entry com.android.commands.pm.Pm
,D/ResourcesManager( 8391): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,D/PackageManager(  901): START PACKAGE DELETE: observer{227280087}
D/PackageManager(  901): pkg{<packageName>}
D/PackageManager(  901): user{0}
D/PackageManager(  901): caller{2000}
D/PackageManager(  901): flags{3}
D/PersonaManagerService(  901): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  901): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  901): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  901): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  901): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PackageManagerService(  901): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager(  901): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  901): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,W/ResourcesManager( 8391): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 8391): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ApplicationPolicy(  901): updateDataUsageMap
,D/ApplicationPolicy(  901): getApplicationUninstallationEnabled
D/ApplicationPolicy(  901): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  901): !@killApplicatoin: 10191, uninstall pkg
,D/accuweather( 1950): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  901): MasterInitialState.processMessage what=3
I/CLocInfoService(  901): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
W/SLocation(  901): No Active Data Connection
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  901): CLoinfo wifi false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
,I/DBG_DM  ( 3700): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/SmartBondingService(  901): getNetworkEnabled : wifi : false mobile : true
,E/WifiStateMachine(  901): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,E/WifiStateMachine(  901): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,I/ActivityManager(  901): Force stopping com.test.thalitest appid=10191 user=-1: uninstall pkg
E/WifiStateMachine(  901): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/ActivityManager(  901): Killing 7353:com.test.thalitest/u0a191 (adj 0): stop com.test.thalitest
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  901):   Force finishing activity ActivityRecord{ae0c9b0 u0 com.test.thalitest/.MainActivity t10}
,W/ActivityManager(  901): mDVFSHelper.acquire()
,I/DBG_DM  ( 3700): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/WindowState(  901): WIN DEATH: Window{3ad21d36 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  901): Client connection lost with reason: 4
,I/SurfaceFlinger(  259): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  259): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 7742): type=WIFI subType= reason=null isConnected=false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/BluetoothAdapterApp( 8391): Load D/L JNI Library
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
I/ActivityManager(  901): Force stopping com.test.thalitest appid=10191 user=0: pkg removed
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,I/BluetoothA2dpSinkServiceJni( 8391): register_com_android_bluetooth_a2dp_sink
,D/BluetoothAdapterApp( 8391): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@623ad63 Instance Count = 1
,I/ActivityManager(  901):   Force finishing activity ActivityRecord{ae0c9b0 u0 com.test.thalitest/.MainActivity t10 f}
W/ActivityManager(  901): Duplicate finish request for ActivityRecord{ae0c9b0 u0 com.test.thalitest/.MainActivity t10 f}
,D/FocusedStackFrame(  901): Set to : 0
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3700): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,D/BluetoothAdapterApp( 8391): onCreate
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  901): Reconfiguring input devices.  changes=0x00000010
,I/DBG_DM  ( 3700): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 41
,W/GeofencerStateMachine( 2185): Ignoring removeGeofence because network location is disabled.
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SamsungIME( 1869): mOCRHelper is null
,I/art     ( 6218): Explicit concurrent mark sweep GC freed 32612(1759KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 14MB/24MB, paused 1.302ms total 128.640ms
,I/art     ( 1578): Explicit concurrent mark sweep GC freed 33743(2MB) AllocSpace objects, 1(39KB) LOS objects, 40% free, 16MB/27MB, paused 1.177ms total 190.839ms
,I/DBG_DM  ( 3700): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 3700): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3700): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 41
,I/DBG_DM  ( 3700): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/BtSettings.ProfileConfig( 8391): Adding GattService
,I/DBG_DM  ( 3700): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3700): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/BtSettings.ProfileConfig( 8391): Adding HeadsetService
,D/BtSettings.ProfileConfig( 8391): Adding A2dpService
,D/BtSettings.ProfileConfig( 8391): Adding HidService
,D/BtSettings.ProfileConfig( 8391): Adding HealthService
,D/BtSettings.ProfileConfig( 8391): Adding PanService
,D/BtSettings.ProfileConfig( 8391): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 8391): Adding SapService
,D/BtSettings.ProfileConfig( 8391): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 8391): Adding A2dpSinkService
,D/BtSettings.ProfileConfig( 8391): Adding SapClientService
,D/BtSettings.ProfileConfig( 8391): Adding HidDevService
,I/art     ( 2539): Explicit concurrent mark sweep GC freed 40827(2MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 21MB/28MB, paused 1.197ms total 272.424ms
,I/BtSettings.ProfileConfig( 8391): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  901): ret = -1
,D/SecContentProvider2(  901): uri = 14 selection = getSealedState
,D/SecContentProvider2(  901): mCursor = null
,D/SecContentProvider2(  901): KnoxCustomManagerService offline: service is not available
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
,D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
D/ApplicationPolicy(  901): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  901): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
I/DBG_DM  ( 3700): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 41
,D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
,D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
,D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
D/BluetoothAdapterApp( 8391): checkSWUpdate
D/BluetoothAdapterApp( 8391): sw version in prop is 1431675920
,D/BluetoothAdapterApp( 8391): sw version in file is 1431675920
D/BluetoothAdapterApp( 8391): sw version is same
,I/DBG_DM  ( 3700): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/art     (  901): Explicit concurrent mark sweep GC freed 76679(5MB) AllocSpace objects, 48(768KB) LOS objects, 30% free, 35MB/51MB, paused 4.550ms total 279.335ms
,I/art     (  901): WaitForGcToComplete blocked for 256.006ms for cause Explicit
D/ResourcesManager(  901): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/ActivityManager(  901): Killing 7280:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
,D/AuthorizationBluetoothService( 2185): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3700): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3700): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3700): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3700): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager(  901): post active user change for 0
D/KnoxTimeoutHandler(  901): postActiveUserChange for user 0
,I/DBG_DM  ( 3700): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,D/RegisteredServicesCache( 1465): empty dynamic service
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,W/SQLiteConnectionPool( 2539): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/SecurityLogAgent( 6924): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6924): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6924): StateMachine : Current State = 1
D/SecurityLogAgent( 6924): StateMachine : Changed Current State = 1
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/SurfaceFlinger(  259): id=17 createSurf (1080x1920),2 flag=404, com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/SecContentProvider2(  901): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  901): mCursor = null
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/libprocessgroup(  901): failed to open /acct/uid_10057/pid_7280/cgroup.procs: No such file or directory
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/Timeline( 3700): Timeline: Activity_idle id: android.os.BinderProxy@3a9ae70 time:258810
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/talkback/talkback.apk
,W/ActivityManager(  901): mDVFSHelper.release()
I/Timeline(  901): Timeline: Activity_windows_visible id: ActivityRecord{19d881b9 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t9} time:258854
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/SurfaceWidgetView( 1481): destroyHardwareResources():101178390
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
I/PCWCLIENTTRACE_PushUtil( 7169): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7169): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7169): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7169): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  901): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7169): noConnectivity : true
,I/SurfaceFlinger(  259): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/8)
,I/SurfaceFlinger(  259): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Books/Books.apk
,D/Launcher( 1481): onRestart, Launcher: 199950262
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/EnterpriseDeviceManagerService(  901): Package has changed for user 0
D/EnterpriseDeviceManagerService(  901): Admin package name: com.google.android.gms
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/Launcher( 1481): onStart, Launcher: 199950262
D/Launcher.HomeView( 1481): onStart
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1950): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1950): [237392/6] SurfaceWidget drawing first frame
D/Launcher.HomeView( 1481): onStop
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,I/SurfaceFlinger(  259): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/DIAGMON_AGENT( 7799): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7799): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/InputMethodManagerService(  901): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService(  901): Got RemoteException sending setActive(false) notification to pid 7353 uid 10191
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/RCPManagerService(  901): PackageReceiver onReceive()
,I/HarmonyEASService(  901): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  901): stay LED for fully charged
,I/Timeline(  901): Timeline: Activity_windows_visible id: ActivityRecord{26ffc271 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:259040
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/KnoxMUMContainerPolicy(  901): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  901): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/JobSchedulerService(  901): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  901): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  901): uID is 10191
V/EnterpriseBillingPolicy(  901): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  901): getProfileForApplication - enter
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
V/EnterpriseBillingPolicyStorage(  901): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  901): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  901): packageModificationReceiver - onreceive - might be a vpn vendor package 
,V/EnterpriseBillingPolicyStorage(  901): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  901): getBillingProfileForVpnEngine - end - null
,D/KnoxTimeoutHandler(  901): handleActiveUserChange for user 0
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/FOTA_Client( 7818): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/TaskPersister(  901): removeObsoleteFile: deleting file=10_task.xml
,D/TaskPersister(  901): removeObsoleteFile: deleting file=9_task.xml
,I/art     (  901): Explicit concurrent mark sweep GC freed 18567(936KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 35MB/51MB, paused 5.265ms total 380.538ms
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/FOTA_Client( 7818): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/FOTA_Client( 7818): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.503: ( 7841): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar( 1183): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/KLMS-2.4.503: ( 7841): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453396754187
,I/PhoneStatusBar( 1183): Icon Only
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/PanelView( 1183): There is/are notification(s) 
D/PanelView( 1183): There is/are notification(s) 
I/KLMS-2.4.503: ( 7841): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/KLMS-2.4.503: ( 7841): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7841): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7858): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/PackageManager(  901): delete codoeFile: 
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager(  901): result of delete: 1{227280087}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/SPPClientService( 7206): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/SA      ( 6813): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
I/SA      ( 6813): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6813): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/AndroidRuntime( 8345): Shutting down VM
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,I/SA      ( 6813): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6813): [OR] == isSIMCardReady false ==
,I/SA      ( 6813): [SCU] == networkStateCheck == false
I/SA      ( 6813): [OR] onReceive END
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/SPPClientService( 7206): [[SystemStateMonitorService]] No Active Internet
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/accuweather( 7876): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7876): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
I/KnoxUsageLogPro( 7895): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7895): premStatus:2
,I/KnoxUsageLogPro( 7895): isEulaShown : false
I/KnoxUsageLogPro( 7895): KnoxUsageReceiver onReceive : not Processible, just return
,W/ResourcesManager(  901): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  901): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  901): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/Headlines( 5412): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5412): getCountryCode(): countryCode = PL
,D/Headlines( 5412): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5412): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5412): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5412): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5412): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5412): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5412): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ResourcesManager(  901): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/QuickConnect( 8030): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8030): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8030): PeriphStartReceiver.onReceive - no need to start
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6924): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6924): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6924): StateMachine : Current State = 1
,D/SecurityLogAgent( 6924): StateMachine : Changed Current State = 1
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  901): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  901): onPackageRemoved : com.test.thalitest
,I/iu.Environment( 2539): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2539): num queued entries: 0
,I/iu.UploadsManager( 2539): num updated entries: 0
,I/iu.SyncManager( 2539): NEXT; no task
,I/KLMS-2.4.503: ( 7841): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/SMD     (  290): DCD ON
,I/KLMS-2.4.503: ( 7841): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453396754566
,I/KLMS-2.4.503: ( 7841): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7841): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,I/EventHub(  901): Removing device '/dev/input/event4' due to inotify event
,F/libc    ( 7841): Fatal signal 7 (SIGBUS), code 2, fault addr 0x770f7118 in tid 7841 (msung.klmsagent)
,I/EventHub(  901): Removing device '/dev/input/event5' due to inotify event
,E/audit_log( 2116): File locking failed. error= Bad file number
,E/audit_log( 2116): File locking failed. error= Bad file number
,I/EventHub(  901): Removing device '/dev/input/event6' due to inotify event
I/ActivityManager(  901): Process com.samsung.klmsagent (pid 7841)(adj 0) has died(183,610)
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8424): MountEmulatedStorage()
,E/Zygote  ( 8424): v2
I/libpersona( 8424): KNOX_SDCARD checking this for 10103
I/libpersona( 8424): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8424 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,I/Zygote  (  325): Process 7841 exited due to signal (7)
,I/EventHub(  901): Removing device '/dev/input/event7' due to inotify event
,I/SELinux ( 8424): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
E/SELinux ( 8424): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub(  901): Removing device '/dev/input/event8' due to inotify event
,D/TimaKeyStoreProvider( 8424): TimaSignature is unavailable
,D/ActivityThread( 8424): Added TimaKeyStore provider
,D/ResourcesManager( 8424): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,W/ContextImpl( 8424): Unable to create files subdir /data/data/com.sec.esdk.elm/cache
E/ActivityThread( 8424): Unable to setupGraphicsSupport due to missing cache directory
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,I/EventHub(  901): Removing device '/dev/input/event9' due to inotify event
,D/AndroidRuntime( 8424): Shutting down VM
,I/ActivityManager(  901): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8443 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,E/Zygote  ( 8443): MountEmulatedStorage()
E/Zygote  ( 8443): v2
,I/libpersona( 8443): KNOX_SDCARD checking this for 10016
I/libpersona( 8443): KNOX_SDCARD not a persona
,F/libc    ( 8424): Fatal signal 7 (SIGBUS), code 2, fault addr 0x72800151 in tid 8424 (om.sec.esdk.elm)
,F/libc    ( 8424): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2116): File locking failed. error= Bad file number
,I/EventHub(  901): Removing device '/dev/input/event10' due to inotify event
,I/SELinux ( 8443): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
,E/SELinux ( 8443): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  901): Process com.sec.esdk.elm (pid 8424)(adj 9) has died(181,610)
,D/TimaKeyStoreProvider( 8443): TimaSignature is unavailable
,D/ActivityThread( 8443): Added TimaKeyStore provider
,I/EventHub(  901): Removing device '/dev/input/event11' due to inotify event
,D/ResourcesManager( 8443): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,W/        ( 8443): Zip: read 65557 failed: I/O error
W/zipro   ( 8443): Error opening archive /system/priv-app/HealthService/HealthService.apk: I/O Error
D/asset   ( 8443): failed to open Zip archive '/system/priv-app/HealthService/HealthService.apk'
,I/Zygote  (  325): Process 8424 exited due to signal (7)
,W/ContextImpl( 8443): Unable to create files subdir /data/data/com.sec.android.service.health/cache
E/ActivityThread( 8443): Unable to setupGraphicsSupport due to missing cache directory
,D/ResourcesManager( 8443): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager( 8443): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,F/libc    ( 8443): Fatal signal 7 (SIGBUS), code 2, fault addr 0x74c01231 in tid 8443 (.service.health)
,F/libc    ( 8443): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2116): File locking failed. error= Bad file number
,I/ActivityManager(  901): Process com.sec.android.service.health (pid 8443)(adj 0) has died(182,610)
,I/PCWCLIENTTRACE_PushUtil( 7169): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7169): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7169): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7169): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,I/Zygote  (  325): Process 8443 exited due to signal (7)
,E/Zygote  ( 8460): MountEmulatedStorage()
,E/Zygote  ( 8460): v2
I/libpersona( 8460): KNOX_SDCARD checking this for 10033
,I/libpersona( 8460): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8460 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 8460): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
,E/SELinux ( 8460): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0

```
