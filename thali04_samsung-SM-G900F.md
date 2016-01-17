#### Test 56151093914d164_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
D/MyFiles ( 7366): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/TactileAssist(  901): enable value -1
I/TactileAssist(  901): internal enable value -1
E/installd(  304): system dir 0 : /system/app/
E/installd(  304): system dir 1 : /system/priv-app/
E/installd(  304): system dir 2 : /vendor/app/
I/TactileAssist(  901): intensity value -1
E/installd(  304): system dir 3 : /oem/app/
I/TactileAssist(  901): saveAppList value true
I/TactileAssist(  901): List of disabled apps :
--------- beginning of system
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7389): MountEmulatedStorage()
E/Zygote  ( 7389): v2
I/ActivityManager(  901): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7389 uid=10057 gids={50057, 9997, 3003, 3002} abi=armeabi-v7a
I/libpersona( 7389): KNOX_SDCARD checking this for 10057
I/libpersona( 7389): KNOX_SDCARD not a persona
,I/SELinux ( 7389): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7389): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7389): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/PackageManager(  901): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
D/TimaKeyStoreProvider( 7389): TimaSignature is unavailable
D/ActivityThread( 7389): Added TimaKeyStore provider
D/ResourcesManager( 7389): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/ResourcesManager( 7389): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 7389): onReceive() it will make start service
D/Compatibility( 7389): onHandleIntent()
D/Compatibility( 7389): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10191, android.intent.extra.user_handle=0}]
D/Compatibility( 7389): found: 2
I/UpdateIcingCorporaServi( 1567): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 6184): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
D/Compatibility( 7389): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7389): skipping ResolveInfo{edcbfa2 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7389): considering ResolveInfo{2fad2433 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7389): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7389): enabling receiver ResolveInfo{3223f0 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ResourcesManager( 1567): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/UpdateIcingCorporaServi( 1567): UpdateCorporaTask done [took 67 ms] updated apps [took 67 ms] 
D/Compatibility( 7389): enabling receiver ResolveInfo{17ec9d69 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7389): enabling receiver ResolveInfo{2feb33ee com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7389): enabling receiver ResolveInfo{290bd08f com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7389): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7422): MountEmulatedStorage()
E/Zygote  ( 7422): v2
I/libpersona( 7422): KNOX_SDCARD checking this for 10097
I/libpersona( 7422): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7422 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7406): 
D/AndroidRuntime( 7406): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/SELinux ( 7422): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/AndroidRuntime( 7406): CheckJNI is OFF
I/SELinux ( 7422): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  901): Killing 6282:com.sec.android.app.sns3/u0a35 (adj 15): bgCount ##41
D/AndroidRuntime( 7406): setted country_code = Poland
D/AndroidRuntime( 7406): setted countryiso_code = PL
E/SELinux ( 7422): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 7406): setted sales_code = XEO
D/AndroidRuntime( 7406): readGMSProperty: start
D/AndroidRuntime( 7406): readGMSProperty: already setted!!
D/AndroidRuntime( 7406): readGMSProperty: end
D/AndroidRuntime( 7406): addProductProperty: start
D/TimaKeyStoreProvider( 7422): TimaSignature is unavailable
D/ActivityThread( 7422): Added TimaKeyStore provider
D/ResourcesManager( 7422): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/libprocessgroup(  901): failed to open /acct/uid_10035/pid_6282/cgroup.procs: No such file or directory
E/AffinityControl( 7406): AffinityControl: registerfunction enter
W/ActivityManager(  901): mDVFSHelper.release()
D/DocsApplication( 7422): Installing DEX configuration.
D/AndroidRuntime( 7406): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  901): inState():  stateMachine is null !!
V/ApplicationPolicy(  901): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  901): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  901): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/DexInstaller( 7422): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7422): Provided clientMode=RELEASE, packageInfo=PackageInfo{158af76d com.google.android.apps.docs}
W/ActivityManager(  901): mDVFSHelper.acquire()
D/FocusedStackFrame(  901): Set to : 0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/TAG     ( 7422): onCreate()
E/Zygote  ( 7448): MountEmulatedStorage()
E/Zygote  ( 7448): v2
I/libpersona( 7448): KNOX_SDCARD checking this for 10191
I/libpersona( 7448): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7448 uid=10191 gids={50191, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7448): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/CrossAppStateProvider( 7422): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/AndroidRuntime( 7406): Shutting down VM
I/SELinux ( 7448): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
E/SELinux ( 7448): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/ServiceManager(  341): Waiting for service AtCmdFwd...
D/TimaKeyStoreProvider( 7448): TimaSignature is unavailable
D/ActivityThread( 7448): Added TimaKeyStore provider
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  901): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/SurfaceWidgetView( 1473): destroyHardwareResources():416003878
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/SurfaceFlinger(  257): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (6/8)
I/SurfaceFlinger(  257): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/8)
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1970): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/Launcher( 1473): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/SQLiteSecureOpenHelper( 3548): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3548): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/ResourcesManager( 7448): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/WebViewFactory( 7448): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7448): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7448): Loading: webviewchromium
I/LibraryLoader( 7448): Time to load native libraries: 1 ms (timestamps 5006-5007)
I/LibraryLoader( 7448): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7448): Binding Chromium to main looper Looper (main, tid 1) {2feb33ee}
I/LibraryLoader( 7448): Expected native library version number "",actual native library version number ""
I/chromium( 7448): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7448): Initializing chromium process, renderers=0
W/art     ( 7448): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7448): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7448): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7448): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/Adreno-EGL( 7448): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7448): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7448): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7448): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7448): Remote Branch: 
I/Adreno-EGL( 7448): Local Patches: 
I/Adreno-EGL( 7448): Reconstruct Branch: 
,W/chromium( 7448): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7448): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7448): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7448): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7448): CordovaWebView is running on device made by: samsung
,W/art     ( 7448): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7448): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7448): performCreate Call secproduct feature valuefalse
D/Activity( 7448): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7448): Render dirty regions requested: true
,D/ActivityManager(  901): post active user change for 0
,D/KnoxTimeoutHandler(  901): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  901): handleActiveUserChange for user 0
,I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/OpenGLRenderer( 7448): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7448): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7448): Enabling debug mode 0
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/InputMethodManagerService(  901): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,W/ActivityManager(  901): mDVFSHelper.release()
I/Timeline(  901): Timeline: Activity_windows_visible id: ActivityRecord{7316a29 u0 com.test.thalitest/.MainActivity t10} time:115323
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,W/IInputConnectionWrapper( 7448): showStatusIcon on inactive InputConnection
I/Timeline( 7448): Timeline: Activity_idle id: android.os.BinderProxy@2aaab2d9 time:115328
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/JsMessageQueue( 7448): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7448): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359660672
D/JX-Cordova( 7448): jxcore cordova android initializing
,E/SMD     (  293): DCD ON
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7516): MountEmulatedStorage()
E/Zygote  ( 7516): v2
I/libpersona( 7516): KNOX_SDCARD checking this for 10098
I/libpersona( 7516): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7516 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 6315:com.sec.spp.push:RemoteDlcProcess/u0a37 (adj 15): bgCount ##41
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/SELinux ( 7516): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7516): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7516): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GAV2    ( 7422): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 7516): TimaSignature is unavailable
,D/ActivityThread( 7516): Added TimaKeyStore provider
,D/ResourcesManager( 7516): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/libprocessgroup(  901): failed to open /acct/uid_10037/pid_6315/cgroup.procs: No such file or directory
,W/ResourcesManager( 7516): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/[CarMode]( 7516): [DLApplication]-onCreate: Applicatino Started!
D/SampleAppCoreManager( 7516): SampleAppCoreManager VACVersion '2.2.0.11867'
I/VlingoAndroidCore( 7516): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7546): MountEmulatedStorage()
E/Zygote  ( 7546): v2
I/libpersona( 7546): KNOX_SDCARD checking this for 10032
I/libpersona( 7546): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7546 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/art     (  326): Explicit concurrent mark sweep GC freed 8741(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 280us total 12.343ms
I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.922ms
I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 8.012ms
I/SELinux ( 7546): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7546): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7546): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7546): TimaSignature is unavailable
D/ActivityThread( 7546): Added TimaKeyStore provider
D/ResourcesManager( 7546): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/ResourcesManager( 7546): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/System.out( 7546): Inside onCreate() of WakeupTriggerProvide
I/System.out( 7546): Inside WakeupProvider
E/DatabaseUtils( 7546): Writing exception to parcel
E/DatabaseUtils( 7546): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7546): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7546): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7546): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7546): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7546): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7546): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7546): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7546): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7546): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7546): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7516): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
I/VlingoApplication( 7546): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
W/System.err( 7516): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7516): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7516): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7516): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7516): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7516): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7516): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7516): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7516): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7516): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7516): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7516): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7516): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7516): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7516): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7516): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7516): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7516): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7516): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7516): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7516): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7516): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7516): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7516): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7516): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7516): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7516): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7516): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7516): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/DatabaseUtils( 7546): Writing exception to parcel
E/DatabaseUtils( 7546): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7546): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7546): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7546): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7546): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7546): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7546): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7546): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7546): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7546): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7546): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7516): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 7516): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7516): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7516): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7516): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7516): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7516): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7516): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7516): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7516): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7516): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7516): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7516): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7516): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7516): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7516): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 7516): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7516): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7516): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7516): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7516): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7516): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7516): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7516): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7516): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7516): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7516): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 7516): [DLApplication]-Init Called!:false
E/[CarMode]( 7516): [DLApplication]-Init Started!:true
I/[CarModeFW]( 7516): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7516): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7516): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7516): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7516): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7516): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7516): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7516): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7516): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7516): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7516): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7516): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7516): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7516): ### com.android.internal.os.ZygoteInit::main(1194)
I/VlingoAndroidCore( 7546): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
I/MessageDataHandler( 7516): initialize
D/[CarModeFW]( 7516): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 7516): CDH-initiazlieCaches : after sync
D/[CarModeFW]( 7516): DrivingManager-initialize...
I/SensorService(  901): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  901): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  901): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
D/[CarModeFW]( 7516): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7516): CDH-ContactDataHandler initiazlieCaches time : 22
D/[CarModeFW]( 7516): CDH-initiazlieCaches : end sync
I/MediaPlayer( 7516): Need to enable context aware info
V/MediaPlayer-JNI( 7516): native_setup
V/MediaPlayer( 7516): constructor
V/MediaPlayer( 7516): setListener
E/MediaPlayer-JNI( 7516): QCMediaPlayer mediaplayer NOT present
D/[CarModeFW]( 7516): PushMessageManager-bindPushMessageService
D/VlingoApplication( 7546): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 7546): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
I/[CarModeFW]( 7516): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode]( 7516): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarModeFW]( 7516): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1453043047403
D/[CarMode]( 7516): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 7516): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1453043047403
D/[CarModeFW]( 7516): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1453043047403
D/[CarModeFW]( 7516): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1453043047403
D/[CarModeFW]( 7516): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1453043047404
D/[CarModeFW]( 7516): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1453043047404
I/[CarMode]( 7516): [LogNotNull]-Package name is: com.google.android.apps.maps
D/TP/SmsProvider( 1467): query,matched:2, calling pid = 7516
D/TP/SmsProvider( 1467): match 2:Elapsed time : 1.480 ms
D/TP/SmsProvider( 1467): query,matched:2, calling pid = 7516
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 1467): match 2:Elapsed time : 2.701 ms
E/[CarMode]( 7516): [DLApplication]-Init End!:true
E/Zygote  ( 7578): MountEmulatedStorage()
E/Zygote  ( 7578): v2
I/libpersona( 7578): KNOX_SDCARD checking this for 10003
I/libpersona( 7578): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7578 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/MessageDataHandler( 7516):  getInboxList smsCursor : 33
V/AlarmManager(  901): waitForAlarm result :8
I/SELinux ( 7578): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/[CarModeFW]( 7516): CDH-buildContactCacheWireFrame : cur len =0
I/SELinux ( 7578): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7578): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/[CarMode]( 7516): [DLApplication]-GooglePlayServices SUCCESS.
D/TP/MmsProvider( 1467): Query uri=content://mms/inbox, match=2, calling pid = 7516
D/TP/MmsProvider( 1467): Query uri=content://mms, match=0, calling pid = 7516
D/[CarModeFW]( 7516): RecommendHandler-selection = type = '3'
D/MessageDataHandler( 7516):  getInboxList mmsCursor : 25
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
I/MessageDataHandler( 7516): getUnreadMessageCount :0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/[CarModeFW]( 7516): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 61
E/[CarMode]( 7516): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
I/UpdateManagerReceiver( 7516): Intent : android.intent.action.PACKAGE_ADDEDSun Jan 17 16:04:07 GMT+01:00 2016
E/Zygote  ( 7593): MountEmulatedStorage()
I/libpersona( 7593): KNOX_SDCARD checking this for 10019
E/Zygote  ( 7593): v2
I/libpersona( 7593): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7593 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7599): MountEmulatedStorage()
E/Zygote  ( 7599): v2
I/libpersona( 7599): KNOX_SDCARD checking this for 1000
I/libpersona( 7599): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7599 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7593): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7593): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7593): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/[CarModeFW]( 7516): CDH-buildContactCacheWireFrame : cur len =0
I/SELinux ( 7599): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
W/GAV2    ( 7422): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
I/SELinux ( 7599): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
E/SELinux ( 7599): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BatteryService(  901): stay LED for fully charged
D/TimaKeyStoreProvider( 7578): TimaSignature is unavailable
D/ActivityThread( 7578): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 7593): TimaSignature is unavailable
D/ActivityThread( 7593): Added TimaKeyStore provider
I/ActivityManager(  901): Killing 6334:com.sec.spp.push:RemoteNotiProcess/u0a37 (adj 15): bgCount ##41
D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3252): Disconnected process message: 10
D/[CarModeFW]( 7516): PushMessageService-onCreate
D/TimaKeyStoreProvider( 7599): TimaSignature is unavailable
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/MessageDataHandler( 7516):  getInboxList mms,sms cursor join : 213
I/ActivityManager(  901): Killing 4848:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
D/ActivityThread( 7599): Added TimaKeyStore provider
I/ActivityManager(  901): Killing 6706:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##42
I/ActivityManager(  901): Killing 6199:com.google.android.talk/u0a116 (adj 15): bgCount ##43
D/ResourcesManager( 7578): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
D/[CarModeFW]( 7516): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7516): RecommendHandler-selection = type = '3'
D/TP/MmsSmsProvider( 1467): query,matched:0, calling pid = 7516
V/TP/MmsSmsProvider( 1467): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1467): match 0:Elapsed time : 1.253 ms
D/TP/MmsSmsProvider( 1467): query,matched:13, calling pid = 7516
,D/ResourcesManager( 7599): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
D/TP/MmsSmsProvider( 1467): match 13:Elapsed time : 1.149 ms
,D/MessageDataHandler( 7516):  getInboxList address cursor : 5
,D/[CarModeFW]( 7516): PushMessageManager-onServiceConnected
,D/[CarModeFW]( 7516): PushMessageService-registerPushMessageServiceListener
D/TP/MmsSmsProvider( 1467): query,matched:0, calling pid = 7516
V/TP/MmsSmsProvider( 1467): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1467): match 0:Elapsed time : 1.781 ms
,D/MessageDataHandler( 7516):  getInboxList thread cursor : 10
,D/MessageDataHandler( 7516):  thread, addr result: 2
,I/[CarModeFW]( 7516): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 309
I/[CarModeFW]( 7516): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7516): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 310
,D/UserAnalysis.PlaceProvider( 7578): PlaceProvider onCreate()
,D/ResourcesManager( 7593): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,W/ContextImpl( 7599): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,D/SSRM:m  (  901): SIOP:: AP = 370, PST = 348, CUR = 450
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7599): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,E/Zygote  ( 7625): MountEmulatedStorage()
I/libpersona( 7625): KNOX_SDCARD checking this for 10111
E/Zygote  ( 7625): v2
I/libpersona( 7625): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7625 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/UserAnalysis.SecureDbManager( 7578): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 7578): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7578): Create SecureDbHelper
,I/SELinux ( 7625): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7625): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7625): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/FilterInstaller( 7599): There is no requred permission
,I/ActivityManager(  901): Killing 5941:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,D/IntelligenceServiceApplication( 7578): onCreate()
,I/SQLiteSecureOpenHelper( 7578): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7578): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7578): Open Place.db in secure mode
,I/SQLiteSecureOpenHelper( 7578): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7578): ...getDatabaseLocked(b,b,pwd)
,D/TimaKeyStoreProvider( 7625): TimaSignature is unavailable
,D/ActivityThread( 7625): Added TimaKeyStore provider
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/libprocessgroup(  901): failed to open /acct/uid_10037/pid_6334/cgroup.procs: No such file or directory
,W/libprocessgroup(  901): failed to open /acct/uid_10116/pid_6199/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_1000/pid_6706/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_10045/pid_4848/cgroup.procs: No such file or directory
,I/art     (  901): Explicit concurrent mark sweep GC freed 235039(16MB) AllocSpace objects, 4(4MB) LOS objects, 30% free, 35MB/51MB, paused 1.426ms total 106.240ms
,D/[CarModeFW]( 7516): MyPlaceProvider-+++Begin print all data in content provider+++
,D/[CarModeFW]( 7516): MyPlaceProvider-=============
D/[CarModeFW]( 7516): MyPlaceProvider-=============
,D/[CarModeFW]( 7516): MyPlaceProvider-=============
,D/[CarModeFW]( 7516): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 574
,I/[CarModeFW]( 7516): -[snowdeer] Rec : Missed Call : 519
,D/ResourcesManager( 7625): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,D/[CarModeFW]( 7516): MyPlaceProvider-=============
,D/[CarModeFW]( 7516): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7516): MyPlaceProvider-==============
I/[CarModeFW]( 7516): -[snowdeer] Rec : Favorite : 5
D/[CarModeFW]( 7516): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7516): MyPlaceProvider-==============
D/[CarModeFW]( 7516): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7516): MyPlaceProvider-==============
D/[CarModeFW]( 7516): MyPlaceProvider-latitude is not valid
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
W/libprocessgroup(  901): failed to open /acct/uid_1000/pid_5941/cgroup.procs: No such file or directory
,E/Zygote  ( 7641): MountEmulatedStorage()
I/libpersona( 7641): KNOX_SDCARD checking this for 10045
E/Zygote  ( 7641): v2
I/libpersona( 7641): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7641 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[CarModeFW]( 7516): -[snowdeer] Rec : CallLog : 20
,I/SELinux ( 7641): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7641): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/[CarModeFW]( 7516): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 652
,E/SELinux ( 7641): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/PackageIntentReceiver( 7625): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 7625): Not GearManger package! 
,D/[CarMode]( 7516): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@d1a76628, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@21e9f2fe] LOCATIONS
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 7641): TimaSignature is unavailable
,D/ActivityThread( 7641): Added TimaKeyStore provider
,E/Zygote  ( 7656): MountEmulatedStorage()
I/ActivityManager(  901): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7656 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/Zygote  ( 7656): v2
,I/libpersona( 7656): KNOX_SDCARD checking this for 10117
I/libpersona( 7656): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Killing 6159:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
,W/jxcore-log( 7448): Initializing JXcore engine
W/jxcore-log( 7448): JXcore engine is ready
,W/jxcore-log( 7448): Starting JXcore engine
,I/SELinux ( 7656): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7656): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7656): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  901): Killing 6119:com.google.android.gm/u0a113 (adj 15): bgCount ##41
,D/ResourcesManager( 7641): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 7641): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 7656): TimaSignature is unavailable
,D/ActivityThread( 7656): Added TimaKeyStore provider
,D/ResourcesManager( 7656): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,E/auditd  ( 2184): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  901): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  901): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,W/ResourcesManager( 7656): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/CalendarProvider2( 7641): CalendarProvider2.onCreate() called
,D/MagazineService Version( 7656): Magazine-Administrator: 11
,D/MagazineService Version( 7656): Magazine-Provider: 14
,D/MagazineService Version( 7656): Magazine-Channel: 14
,D/HeadlinesChannelApplication( 7656): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7656): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7656): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 7672): MountEmulatedStorage()
,E/Zygote  ( 7672): v2
I/libpersona( 7672): KNOX_SDCARD checking this for 1000
I/libpersona( 7672): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7672 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7656): [onHandleIntent] Send broadcast to (com.test.thalitest).
,W/jxcore-log( 7448): Platform android
W/jxcore-log( 7448): 
W/jxcore-log( 7448): Process ARCH arm
W/jxcore-log( 7448): 
,I/SELinux ( 7672): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7672): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7672): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  901): failed to open /acct/uid_10167/pid_6159/cgroup.procs: No such file or directory
,W/libprocessgroup(  901): failed to open /acct/uid_10113/pid_6119/cgroup.procs: No such file or directory
,I/ActivityManager(  901): Killing 6381:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7672): TimaSignature is unavailable
D/ActivityThread( 7672): Added TimaKeyStore provider
,D/ResourcesManager( 7672): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/System.out( 7546): INFO:Resource not found:/Common.properties Using default values
,W/libprocessgroup(  901): failed to open /acct/uid_10004/pid_6381/cgroup.procs: No such file or directory
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7690): MountEmulatedStorage()
E/Zygote  ( 7690): v2
I/libpersona( 7690): KNOX_SDCARD checking this for 1000
I/libpersona( 7690): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7690 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 6455:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
,I/SELinux ( 7690): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7690): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7690): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7690): TimaSignature is unavailable
,D/ActivityThread( 7690): Added TimaKeyStore provider
,I/[CarModeFW]( 7516): -[snowdeer] Rec : Schedule : 486
,I/[CarModeFW]( 7516): -[snowdeer] Rec : During DL app : 2
,D/ResourcesManager( 7690): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,I/[CarModeFW]( 7516): -[snowdeer] Rec : Location Sharing : 1
I/[CarModeFW]( 7516): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 7516): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7516): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7516): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
,I/[CarModeFW]( 7516): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 7516): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 1093
,I/[CarModeFW]( 7516): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7516): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7516): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7516): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 1104
,W/libprocessgroup(  901): failed to open /acct/uid_10043/pid_6455/cgroup.procs: No such file or directory
,D/AcmsPackageEventListener( 7690): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 7690): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService( 7690): Enter Oncreate
,D/AcmsServiceMonitor( 7690): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 7690): creating AcmsCore
,D/AcmsCore( 7690): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7690): AcmsCore
,D/AcmsCore( 7690): init
,D/AcmsCore( 7690): Looper handler is not null
D/AcmsCore( 7690): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7690): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7690): Incrementing - Counter value: 1
,D/AcmsCore( 7690): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsCertificateMngr( 7690): AcmsCertificateMngr
,D/AcmsRevocationMngr( 7690): AcmsRevocationMngr
,D/AcmsService( 7690): onStartCommand
,D/AcmsService( 7690): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 7690): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7690): Incrementing - Counter value: 2
D/AcmsService( 7690): Incremented Counter Value : onStartCommand
,D/ActivityThread( 7690): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsService( 7690): Inside handle Intent
,D/AcmsService( 7690): App added - package name: com.test.thalitest
D/AcmsCore( 7690): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7690): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7690): Incrementing - Counter value: 3
D/AcmsCore( 7690): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7690): Decremented Counter Value : handleStartIntent
,D/AcmsServiceMonitor( 7690): Decrementing - Counter value: 2
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7710): MountEmulatedStorage()
E/Zygote  ( 7710): v2
I/libpersona( 7710): KNOX_SDCARD checking this for 10165
I/libpersona( 7710): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7710 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7710): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7710): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7710): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7710): TimaSignature is unavailable
,D/ActivityThread( 7710): Added TimaKeyStore provider
,D/ResourcesManager( 7710): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7710): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/AcmsKeyStoreHelper( 7690):  getKeyStoreForApplication Enter
,D/KidsPlatformStub( 7710): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7725): MountEmulatedStorage()
I/libpersona( 7725): KNOX_SDCARD checking this for 10169
E/Zygote  ( 7725): v2
I/libpersona( 7725): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7725 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
,I/AcmsKeyStoreHelper( 7690): Key Store exist
,I/AcmsKeyStoreHelper( 7690): Hence loading the keystore file
,I/SELinux ( 7725): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7725): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7725): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7725): TimaSignature is unavailable
,D/ActivityThread( 7725): Added TimaKeyStore provider
,D/ResourcesManager( 7725): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 7725): (284) automatic index on shooting_modes(title_id)
,D/AcmsKeyStoreHelper( 7690):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 7690): getKeyStoreForApplication success 
,D/AcmsCore( 7690): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7690): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 7690): Decrementing - Counter value: 1
D/AcmsCore( 7690): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 7690): This is NOT a valid MirrorLink app
,D/AcmsCore( 7690): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7690): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7690): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7690): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7690): getSvcCounter - Counter value: 0
D/AcmsService( 7690): Enter onDestroy
I/AcmsService( 7690): cleanUp(): inside service clean up
D/AcmsCore( 7690): AcmsCore: inside DeInit
D/AcmsCore( 7690): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7690): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 7690): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7690): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7690): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7690): getSvcCounter - Counter value: 0
D/AcmsService( 7690): killing acms process
I/Process ( 7690): Sending signal. PID: 7690 SIG: 9
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Finsky  ( 6642): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/ActivityManager(  901): Process ACMS.Process (pid 7690)(adj 0) has died(51,564)
,D/ChimeraCfgMgr( 2469): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2469): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 2469): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/ActivityManager(  901): Killing 6352:com.google.android.music:main/u0a125 (adj 15): bgCount ##41
,W/libprocessgroup(  901): failed to open /acct/uid_10125/pid_6352/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2469): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2469): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2469): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/jxcore-log( 7448): JXcore Cordova bridge is ready!
I/jxcore-log( 7448): 
W/jxcore-log( 7448): JXcore engine is started
,D/AsyncTaskServiceImpl( 2469): Submit a task: k
D/ChimeraCfgMgr( 2469): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 2469): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 2469): Processing package: com.test.thalitest
D/GassUtils( 2469): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
D/k       ( 2469): Found info for package com.test.thalitest in db.
W/BaseAppContext( 2469): Using Auth Proxy for data requests.
W/BaseAppContext( 2469): Using Auth Proxy for data requests.
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7749): MountEmulatedStorage()
E/Zygote  ( 7749): v2
I/libpersona( 7749): KNOX_SDCARD checking this for 10039
I/libpersona( 7749): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7749 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/art     (  326): Explicit concurrent mark sweep GC freed 8764(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 276us total 13.882ms
I/jxcore-log( 7448): Toggling radios to true
I/jxcore-log( 7448): 
D/BluetoothAdapter( 7448): enable()
I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.889ms
I/SELinux ( 7749): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/BluetoothAdapter( 7448): enable(): BT is already enabled..!
I/SELinux ( 7749): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7749): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 435us total 7.903ms
D/WifiService(  901): New client listening to asynchronous messages
I/WifiManager( 7448): packageName : com.test.thalitest
D/SecContentProvider(  901): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  901): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  901): mCursor = null
D/WifiService(  901): setWifiEnabled: true pid=7448, uid=10191
E/WifiService(  901): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  901): Permission Denial: getCurrentUser() from pid=7448, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  901): Failed getting userId using ActivityManagerNative
W/WifiService(  901): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7448, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  901): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  901): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  901): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  901): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  901): 	at android.os.Binder.execTransact(Binder.java:446)
D/TimaKeyStoreProvider( 7749): TimaSignature is unavailable
D/SettingsProvider(  901): name = wifi_on
D/ActivityThread( 7749): Added TimaKeyStore provider
I/WifiService(  901): disconnect: pid=7448, uid=10191
I/jxcore-log( 7448): Radios toggled
I/jxcore-log( 7448): 
I/wpa_supplicant( 1290): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7448): My device name is: samsung-SM-G900F
I/jxcore-log( 7448): 
I/wpa_supplicant( 1290): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1290): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1290): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine(  901): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1290): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1290): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1290): Disconnected - do not scan
I/wpa_supplicant( 1290): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine(  901): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  901): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  901): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ResourcesManager( 7749): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
E/WifiStateMachine(  901): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  901): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  901): do suspend true
D/WifiP2pService(  901): InactiveState{ what=143375 }
D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
D/CommandListener(  287): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
V/NativeCrypto( 2256): Read error: ssl=0xaf41b600: I/O error during system call, Connection timed out
E/WifiStateMachine(  901): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NativeCrypto( 2256): SSL shutdown failed: ssl=0xaf41b600: I/O error during system call, Broken pipe
D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
E/WifiStateMachine(  901): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1290): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1290): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1290): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1290): First Scan Start
I/wpa_supplicant( 1290): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  901): ConnectModeState: Network connection lost 
E/WifiStateMachine(  901): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  901): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  901): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  901): do suspend true
D/WifiP2pService(  901): InactiveState{ what=143375 }
D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Validated
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/CommandListener(  287): Clearing all IP addresses on wlan0
I/art     ( 2469): Explicit concurrent mark sweep GC freed 54081(3MB) AllocSpace objects, 21(336KB) LOS objects, 25% free, 20MB/27MB, paused 1.513ms total 142.733ms
D/ConnectivityService(  901): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/EntConnectivity(  901): Not allowed due to - mEnabled false
D/ConnectivityService(  901): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  901): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 2469): CM callback handler got msg 524292
E/WifiStateMachine(  901): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  901): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  901): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WifiStateMachine(  901): updateConfiguredNetworkExpiration - currTime: 1453043049247
D/WifiStateMachine(  901): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/TelephonyNetworkFactory( 1467): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  901): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/CSLegacyTypeTracker(  901): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  901): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  901): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  901): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  901): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  901): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  901): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  901): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  901): setDetailed state send new extra info"NG700"
D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
V/NetworkStats(  901): updateIfacesLocked()
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
V/NetworkStats(  901): performPollLocked(flags=0x1)
D/NetworkStatsFactory(  901): UpdateStatsForKnox
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
E/ConnectivityService(  901): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
E/ConnectivityService(  901): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
V/NetworkStats(  901): performPollLocked() took 12ms
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
V/NetworkStats(  901): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
I/ActivityManager(  901): Killing 6902:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
W/SQLiteConnectionPool( 2469): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/BaseAppContext( 2469): Using Auth Proxy for data requests.
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/BootupListener( 1467): ACTION_DRIVELINK
D/SettingsProvider(  901): name = drivelink_navigation
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1001
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
D/BootupListener( 1467): NAVI : com.google.android.apps.maps
D/SettingsProvider(  901): name = internet_call_settings_visibility
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1001
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
E/Zygote  ( 7782): MountEmulatedStorage()
I/libpersona( 7782): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7782): v2
I/libpersona( 7782): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7782 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7782): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
I/SELinux ( 7782): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/libprocessgroup(  901): failed to open /acct/uid_10011/pid_6902/cgroup.procs: No such file or directory
E/SELinux ( 7782): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
W/BaseAppContext( 2469): Using Auth Proxy for data requests.
W/BaseAppContext( 2469): Using Auth Proxy for data requests.
W/BaseAppContext( 2469): Using Auth Proxy for data requests.
D/TimaKeyStoreProvider( 7782): TimaSignature is unavailable
D/ActivityThread( 7782): Added TimaKeyStore provider
W/BaseAppContext( 2469): Using Auth Proxy for data requests.
D/ResourcesManager( 7782): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
D/SecurityLogAgent( 7782):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
D/SecurityLogAgent( 7782):  SeDenialReceiver : File path = null
I/ActivityManager(  901): Killing 6059:com.sec.android.widgetapp.digitalclock/u0a93 (adj 15): bgCount ##41
I/Hs20UtilService( 1311): Starting #6
I/Hs20UtilService( 1311): Message received 5007
D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
I/Hs20UtilService( 1311): Starting #7
I/Hs20UtilService( 1311): Message received 5007
D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
I/CalendarProvider2( 7641): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7802): MountEmulatedStorage()
I/libpersona( 7802): KNOX_SDCARD checking this for 10148
E/Zygote  ( 7802): v2
I/libpersona( 7802): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7802 uid=10148 gids={50148, 9997} abi=armeabi-v7a
I/SELinux ( 7802): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7802): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  901): Killing 6074:com.sec.android.widgetapp.dualclockdigital/u0a102 (adj 15): bgCount ##41
E/SELinux ( 7802): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  901): failed to open /acct/uid_10093/pid_6059/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 7802): TimaSignature is unavailable
D/ActivityThread( 7802): Added TimaKeyStore provider
D/ResourcesManager( 7802): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/ResourcesManager( 7802): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7802): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
E/SMD     (  293): DCD ON
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7817): MountEmulatedStorage()
E/Zygote  ( 7817): v2
I/libpersona( 7817): KNOX_SDCARD checking this for 10149
I/libpersona( 7817): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7817 uid=10149 gids={50149, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager(  901): Killing 5827:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
I/SELinux ( 7817): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  901): failed to open /acct/uid_10102/pid_6074/cgroup.procs: No such file or directory
I/SELinux ( 7817): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7817): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7817): TimaSignature is unavailable
D/ActivityThread( 7817): Added TimaKeyStore provider
D/ResourcesManager( 7817): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 7817): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7817): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7817): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/libprocessgroup(  901): failed to open /acct/uid_10112/pid_5827/cgroup.procs: No such file or directory
W/art     ( 2469): Verification of void com.google.android.gms.games.broker.LeaderboardAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 139.809ms
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/daemonapp( 1370): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/ApplicationPolicy(  901): updateDataUsageMap
D/Tethering(  901): MasterInitialState.processMessage what=3
D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
I/CLocInfoService(  901): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  901): CLoinfo wifi false
D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/SLocation(  901): No Active Data Connection
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 1970): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/DBG_DM  ( 3725): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3725): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
I/PCWCLIENTTRACE_PushUtil( 7277): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7277): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7277): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7277): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_SYSTEMReceiver( 7277): noConnectivity : true
E/Zygote  ( 7840): MountEmulatedStorage()
E/Zygote  ( 7840): v2
I/libpersona( 7840): KNOX_SDCARD checking this for 10125
I/libpersona( 7840): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7840 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7840): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7840): TimaSignature is unavailable
D/ActivityThread( 7840): Added TimaKeyStore provider
D/ResourcesManager( 7840): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/ActivityManager(  901): Killing 6094:com.sec.android.app.camera/u0a153 (adj 15): bgCount ##41
,I/MusicStore( 7840): Database version: 104
,W/libprocessgroup(  901): failed to open /acct/uid_10153/pid_6094/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2469): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2469): Module APK com.google.android.play.games already loaded
,D/ResourcesManager( 7840): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7840): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7840): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7840): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Icing   ( 2469): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,W/ActivityThread( 7840): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7840): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a2540b0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7840): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7840): GMSCore installation verified
,I/ConfigStore( 7840): Config Database version: 1
,D/ResourcesManager( 2469): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7840): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/Icing   ( 2469): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7840): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7840): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  299): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  901): getStreamVolume 3 index 0
,I/MediaRouter( 7840): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7868): MountEmulatedStorage()
E/Zygote  ( 7868): v2
I/libpersona( 7868): KNOX_SDCARD checking this for 10002
I/libpersona( 7868): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7868 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 1290): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 1290): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1290): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1290): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  901): [1,453,043,050,291 ms] noteScanEnd no scan source
,E/WifiStateMachine(  901): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@190cfb0c sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  901): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  901): setDetailed state send new extra info0x
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  901): mCursor = null
,I/SELinux ( 7868): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7868): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7868): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CLocInfoService(  901): External Intent Received android.net.wifi.SCAN_RESULTS
,D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider( 7868): TimaSignature is unavailable
,D/ActivityThread( 7868): Added TimaKeyStore provider
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7840): type=WIFI subType= reason=null isConnected=false
,D/ResourcesManager( 7868): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  901): Killing 7028:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): bgCount ##41
,I/ActivityManager(  901): Killing 7094:com.sec.enterprise.knox.cloudmdm.smdms/u0a178 (adj 15): bgCount ##41
,I/wpa_supplicant( 1290): wlan0: State: ASSOCIATING -> ASSOCIATED
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,I/wpa_supplicant( 1290): Associated with C0.AA.48
,E/WifiStateMachine(  901): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,E/Zygote  ( 7888): MountEmulatedStorage()
,E/Zygote  ( 7888): v2
I/libpersona( 7888): KNOX_SDCARD checking this for 1000
I/libpersona( 7888): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7888 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/wpa_supplicant( 1290): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  901): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  901): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,I/wpa_supplicant( 1290): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1290): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  901): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 1290): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1290): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1290): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1290): Blacklist: Clear (temp) 
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  901): Network connection established
,D/WifiNative-HAL(  901): callSECApiVoid - ID [50]
E/WifiStateMachine(  901): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  901): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
D/ConnectivityService(  901): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  901): Got NetworkAgent Messenger
D/ConnectivityService(  901): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  901): NetworkAgent connected
E/WifiStateMachine(  901): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  901): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/SELinux ( 7888): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7888): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7888): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/libprocessgroup(  901): failed to open /acct/uid_10070/pid_7028/cgroup.procs: No such file or directory
,E/WifiStateMachine(  901): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  901): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  901): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  287): Setting iface cfg
,E/WifiStateMachine(  901): Start Dhcp Watchdog 2
D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,E/WifiStateMachine(  901): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  901): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/TimaKeyStoreProvider( 7888): TimaSignature is unavailable
,D/ActivityThread( 7888): Added TimaKeyStore provider
,D/ResourcesManager( 7888): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  901): failed to open /acct/uid_10178/pid_7094/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7888): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7888): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/WifiStateMachine(  901): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  901): do suspend false
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  901): InactiveState{ what=143375 }
D/SecContentProvider2(  901): mCursor = null
D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
,I/DIAGMON_AGENT( 7888): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7888): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7888): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7888): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7908): MountEmulatedStorage()
,E/Zygote  ( 7908): v2
I/libpersona( 7908): KNOX_SDCARD checking this for 10010
I/libpersona( 7908): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7908 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7908): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7908): TimaSignature is unavailable
,D/ActivityThread( 7908): Added TimaKeyStore provider
,E/dhcpcd  ( 7923): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7923): version 5.5.6 starting
,E/dhcpcd  ( 7923): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/ResourcesManager( 7908): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/dhcpcd  ( 7923): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7923): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7923): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7923): bssid match
,I/dhcpcd  ( 7923): wlan0: rebinding lease of 192.168.1.136
,I/ActivityManager(  901): Killing 6527:com.samsung.android.app.FileShareServer/u0a74 (adj 15): bgCount ##41
,I/FOTA_Client( 7908): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7908): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7908): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7935): MountEmulatedStorage()
E/Zygote  ( 7935): v2
I/libpersona( 7935): KNOX_SDCARD checking this for 10018
I/libpersona( 7935): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7935 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 6552:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,I/SELinux ( 7935): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7935): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7935): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  901): failed to open /acct/uid_10074/pid_6527/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7935): TimaSignature is unavailable
,D/ActivityThread( 7935): Added TimaKeyStore provider
,D/ResourcesManager( 7935): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/libprocessgroup(  901): failed to open /acct/uid_1000/pid_6552/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7935): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7935): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453043051000
,I/KLMS-2.4.503: ( 7935): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7935): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7935): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  901): Killing 6596:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7951): MountEmulatedStorage()
,E/Zygote  ( 7951): v2
I/libpersona( 7951): KNOX_SDCARD checking this for 10036
I/libpersona( 7951): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7951 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7951): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7951): TimaSignature is unavailable
,D/ActivityThread( 7951): Added TimaKeyStore provider
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7951): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,W/libprocessgroup(  901): failed to open /acct/uid_1000/pid_6596/cgroup.procs: No such file or directory
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5310): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 7343): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7343): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7343): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 7343): [SLFUCHKMGR] constructor called
,I/SA      ( 7343): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7343): [OR] == isSIMCardReady false ==
,I/SA      ( 7343): [SCU] == networkStateCheck == false
I/SA      ( 7343): [OR] onReceive END
,E/SPPClientService( 5310): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7968): MountEmulatedStorage()
E/Zygote  ( 7968): v2
I/libpersona( 7968): KNOX_SDCARD checking this for 10070
I/libpersona( 7968): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7968 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7968): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7968): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7968): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  901): Killing 5958:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7968): TimaSignature is unavailable
,D/ActivityThread( 7968): Added TimaKeyStore provider
,D/ResourcesManager( 7968): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7968): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7968): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7968): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7968): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7968): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7968): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
,D/comsamsunglog( 7968): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7968): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7968): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7968): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7968): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  901): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
W/libprocessgroup(  901): failed to open /acct/uid_10157/pid_5958/cgroup.procs: No such file or directory
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 10070
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/daemonapp( 1370): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7968): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7968): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7968): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7968): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7968): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7968): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1370): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7968): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1370): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7968): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1370): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7968): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7968): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7985): MountEmulatedStorage()
E/Zygote  ( 7985): v2
I/libpersona( 7985): KNOX_SDCARD checking this for 1000
I/libpersona( 7985): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7985 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 7243:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,I/art     (  326): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 272us total 12.548ms
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.910ms
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.902ms
,I/SELinux ( 7985): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7985): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7985): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7985): TimaSignature is unavailable
,D/ActivityThread( 7985): Added TimaKeyStore provider
,D/ResourcesManager( 7985): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7985): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7985): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7985): premStatus:2
,I/KnoxUsageLogPro( 7985): isEulaShown : false
,I/KnoxUsageLogPro( 7985): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  901): failed to open /acct/uid_10014/pid_7243/cgroup.procs: No such file or directory
,E/Zygote  ( 8003): MountEmulatedStorage()
,E/Zygote  ( 8003): v2
I/libpersona( 8003): KNOX_SDCARD checking this for 10087
I/libpersona( 8003): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8003 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  901): Killing 7262:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,I/SELinux ( 8003): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8003): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8003): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8003): TimaSignature is unavailable
,D/ActivityThread( 8003): Added TimaKeyStore provider
,D/ResourcesManager( 8003): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  901): failed to open /acct/uid_10015/pid_7262/cgroup.procs: No such file or directory
,I/ActivityManager(  901): Killing 6505:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,D/Headlines( 5559): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5559): getCountryCode(): countryCode = PL
,D/Headlines( 5559): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5559): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5559): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5559): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5559): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5559): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5559): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8019): MountEmulatedStorage()
,E/Zygote  ( 8019): v2
I/libpersona( 8019): KNOX_SDCARD checking this for 10127
I/libpersona( 8019): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8019 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 7448): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7448): 
,I/SELinux ( 8019): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  901): failed to open /acct/uid_10033/pid_6505/cgroup.procs: No such file or directory
I/SELinux ( 8019): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8019): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8019): TimaSignature is unavailable
,D/ActivityThread( 8019): Added TimaKeyStore provider
,D/ResourcesManager( 8019): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/art     (  901): Explicit concurrent mark sweep GC freed 52884(2MB) AllocSpace objects, 2(32KB) LOS objects, 30% free, 35MB/51MB, paused 3.318ms total 109.099ms
,I/GAV2    ( 7422): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  ( 7923): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,I/dhcpcd  ( 7923): wlan0: leased 192.168.1.136 for 86400 seconds
,E/WifiStateMachine(  901): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  901): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8019): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8019): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8019): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8019): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 8019): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 8019): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 8019): Loading: webviewchromium
,I/LibraryLoader( 8019): Time to load native libraries: 5 ms (timestamps 1098-1103)
,I/LibraryLoader( 8019): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8019): Binding Chromium to main looper Looper (main, tid 1) {2215b7dc}
,I/LibraryLoader( 8019): Expected native library version number "",actual native library version number ""
,I/chromium( 8019): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/jxcore-log( 7448): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7448): 
,I/jxcore-log( 7448): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7448): 
,I/BrowserStartupController( 8019): Initializing chromium process, renderers=0
,W/art     ( 8019): Attempt to remove local handle scope entry from IRT, ignoring
,E/WifiStateMachine(  901): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  901): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  901): do suspend true
,D/WifiP2pService(  901): InactiveState{ what=143375 }
D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  901): WifiStateMachine DHCP successful
,E/WifiStateMachine(  901): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  901): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  901): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  901): Not connected state, yet.
E/WifiStateMachine(  901): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
W/chromium( 8019): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,D/WifiStateMachine(  901): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  901): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  901): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  901): callSECApiInt - ID [210]
,I/chromium( 8019): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium( 8019): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
E/WifiStateMachine(  901): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  901): updateNetworkInfo()
,D/ConnectivityService(  901): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  901): Adding iface wlan0 to network 503
,I/jxcore-log( 7448): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7448): 
,I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  901): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  901): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  901): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,W/AudioManagerAndroid( 8019): Requires BLUETOOTH permission
D/ConnectivityService(  901): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  901): Unexpected mtu value: 0, wlan0
,I/jxcore-log( 7448): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7448): 
,E/WifiStateMachine(  901): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  901): Now, connected state.
E/WifiStateMachine(  901): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  901): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  901): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  901): updateSourceRoutes : add src route for:192.168.1.136
,V/        (  287): QcRouteController
I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
,I/jxcore-log( 7448): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7448): 
,I/Adreno-EGL( 8019): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8019): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8019): Build Date: 03/03/15 Tue
I/Adreno-EGL( 8019): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 8019): Remote Branch: 
I/Adreno-EGL( 8019): Local Patches: 
I/Adreno-EGL( 8019): Reconstruct Branch: 
,I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  901): mBoosterFLAG : 0
I/WifiTrafficPoller(  901): current booster mode : FullMode
E/WifiStateMachine(  901): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,V/        (  287): QcRouteController
,E/WifiStateMachine(  901): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/WifiNative-HAL(  901): callSECApiVoid - ID [212]
I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
I/WifiStateMachine(  901): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
,V/        (  287): QcRouteController
,I/jxcore-log( 7448): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7448): 
,V/        (  287): QcRouteController
,V/        (  287): QcRouteController
,V/        (  287): QcRouteController
,V/        (  287): QcRouteController
,I/NSApplication( 8019): Starting up...
,V/        (  287): QcRouteController
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
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Validated
,D/ConnectivityService(  901): currentScore = 0, newScore = 60
D/ConnectivityService(  901):    accepting network in place of null
D/ConnectivityService(  901): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1467): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  901): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  901): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  901): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  901): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
,D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
V/NetworkStats(  901): updateIfacesLocked()
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
V/NetworkStats(  901): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  901): UpdateStatsForKnox
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
V/NetworkStats(  901): advisePersistThreshold() given 9223372036854775, clamped to 2097152
V/NetworkStats(  901): performPollLocked() took 4ms
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/EntConnectivity(  901): Not allowed due to - mEnabled false
D/ConnectivityService(  901): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
,D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524290
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  901): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524290
,D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/ConnectivityManager.CallbackHandler( 2469): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 2469): CM callback handler got msg 524290
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8119): MountEmulatedStorage()
I/libpersona( 8119): KNOX_SDCARD checking this for 10137
E/Zygote  ( 8119): v2
I/libpersona( 8119): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8119 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 4902:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,I/SELinux ( 8119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8119): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8119): TimaSignature is unavailable
,D/ActivityThread( 8119): Added TimaKeyStore provider
,D/ResourcesManager( 8119): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 8119): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8119): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8119): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup(  901): failed to open /acct/uid_10034/pid_4902/cgroup.procs: No such file or directory
,D/QuickConnect( 8119): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8119): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8119): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8134): MountEmulatedStorage()
I/libpersona( 8134): KNOX_SDCARD checking this for 10162
E/Zygote  ( 8134): v2
I/libpersona( 8134): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8134 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 7314:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,E/SMD     (  293): DCD ON
I/SELinux ( 8134): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8134): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8134): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8134): TimaSignature is unavailable
,D/ActivityThread( 8134): Added TimaKeyStore provider
,W/libprocessgroup(  901): failed to open /acct/uid_10041/pid_7314/cgroup.procs: No such file or directory
,D/ResourcesManager( 8134): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8134): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8134): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8134): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8134): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,I/jxcore-log( 7448): Test app app.js loaded
I/jxcore-log( 7448): 
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,I/chromium( 7448): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8160): MountEmulatedStorage()
,E/Zygote  ( 8160): v2
I/libpersona( 8160): KNOX_SDCARD checking this for 10077
I/libpersona( 8160): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8160 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,I/SELinux ( 8160): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  901): exchangeData() failure , invalid userId
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 8160): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,E/SELinux ( 8160): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/SecurityLogAgent( 7782): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7782): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7782): StateMachine : Current State = 1
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 8160): TimaSignature is unavailable
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
D/SecurityLogAgent( 7782): StateMachine : Changed Current State = 1
,D/ActivityThread( 8160): Added TimaKeyStore provider
,I/ActivityManager(  901): Killing 6019:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,I/ActivityManager(  901): Killing 5728:com.android.mms/u0a49 (adj 15): bgCount ##41
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
D/ResourcesManager( 8160): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,E/Zygote  ( 8176): MountEmulatedStorage()
I/libpersona( 8176): KNOX_SDCARD checking this for 10177
E/Zygote  ( 8176): v2
I/libpersona( 8176): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8176 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/chromium( 7448): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  901): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  901): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  901): MasterInitialState.processMessage what=3
I/CLocInfoService(  901): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  901): CLocinfo wifi true 
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  901): getSBEnabled() enabled =false
V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
D/SmartBondingService(  901): getSBEnabled() enabled =false
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,I/SELinux ( 8176): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
,I/SELinux ( 8176): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8176): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/accuweather( 1970): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/PowerManagerService(  901): [PWL] Off : 15s ago
,I/PowerManagerService(  901): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  901): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  901): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=901, ws=null) (elapsedTime=3599)
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 7840): type=WIFI subType= reason=null isConnected=true
,D/CountryDetector(  901): No listener is left
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,W/ContextImpl( 2238): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,I/DBG_DM  ( 3725): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
W/ContextImpl( 2238): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,I/DBG_DM  ( 3725): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,D/TimaKeyStoreProvider( 8176): TimaSignature is unavailable
D/ActivityThread( 8176): Added TimaKeyStore provider
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,D/BadgeProvider( 8160): onCreate
D/BadgeProvider( 8160): DatabaseHelper
,I/chromium( 7448): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7448): 
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,D/ResourcesManager( 8176): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
D/SecContentProvider2(  901): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  901): mCursor = null
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/BadgeProvider( 8160): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 1473): reloadBadges entered.
D/BadgeProvider( 8160): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8160): sendNotify, [notify] : null
,D/BadgeProvider( 8160): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8160): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8160): update, [UpdateCount] : 1
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 8134): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/ActivityManager(  901): Killing 7366:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,W/libprocessgroup(  901): failed to open /acct/uid_10047/pid_6019/cgroup.procs: No such file or directory
,W/libprocessgroup(  901): failed to open /acct/uid_10049/pid_5728/cgroup.procs: No such file or directory
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7749): notifyNetworkActivated
,W/ContextImpl( 7749): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager(  901): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/libprocessgroup(  901): failed to open /acct/uid_10050/pid_7366/cgroup.procs: No such file or directory
,W/ActivityManager(  901): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/hcjo    ( 7749): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7749): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7749): exit::IDLE
D/InitializeManagerStateMachine( 7749): entry::NETWORK_CHECK
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7749): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7749): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7749): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7749): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7749): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7749): entry::SUCCESS
D/hcjo    ( 7749): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1311): Starting #8
,I/Hs20UtilService( 1311): Message received 5007
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Keep current state
,D/hcjo    ( 7749): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7749): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7749): exit::SUCCESS
D/InitializeManagerStateMachine( 7749): entry::IDLE
,I/Hs20UtilService( 1311): Starting #9
,I/Hs20UtilService( 1311): Message received 5007
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1311): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1311): Starting #10
,I/Hs20UtilService( 1311): Message received 5007
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1311): Starting #11
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 1311): Message received 5007
,I/NearbySettings( 1311): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  901): callSECApi what=220
D/WifiStateMachine(  901): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7277): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7277): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7277): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7277): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7888): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7888): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SurfaceFlinger(  257): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/PowerManagerService(  901): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=901
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/FOTA_Client( 7908): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7908): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7908): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/KLMS-2.4.503: ( 7935): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7935): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453043053274
,I/KLMS-2.4.503: ( 7935): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7935): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
I/KLMS-2.4.503: ( 7935): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7935): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7935): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/SO_AGENT( 7951): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5310): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7343): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7343): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7343): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7343): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7343): [OR] == isSIMCardReady false ==
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7343): [SCU] == networkStateCheck == true
I/SA      ( 7343): [DM] getCountryCodeFromCSC : PL
I/SA      ( 7343): isChinaCountryCode : false
I/SA      ( 7343): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7343): [OR] == networkStateCheck true ==
,I/SA      ( 7343): [OR] GetMyCountryZoneTask
,I/SA      ( 7343): [OR] onReceive END
,I/SA      ( 7343): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7343): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7343): [SSP] query invoked
,D/accuweather( 7968): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7968): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7985): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7985): premStatus:2
,I/KnoxUsageLogPro( 7985): isEulaShown : false
I/KnoxUsageLogPro( 7985): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      ( 7343): [TPMU] GetMccFromDB : null
,I/SA      ( 7343): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7343): [TPM] isNoProxy(default) : true
,D/Headlines( 5559): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5559): getCountryCode(): countryCode = PL
,D/Headlines( 5559): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5559): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5559): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5559): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5559): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5559): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5559): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 7343): fail readDirectory() errno=2
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 8119): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8119): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 8119): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7782): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7782): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7782): StateMachine : Current State = 1
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7782): StateMachine : Changed Current State = 1
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7749): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7749): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7749): exit::IDLE
D/InitializeManagerStateMachine( 7749): entry::NETWORK_CHECK
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7749): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7749): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7749): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7749): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7749): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7749): entry::SUCCESS
D/hcjo    ( 7749): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7749): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7749): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7749): exit::SUCCESS
D/InitializeManagerStateMachine( 7749): entry::IDLE
,I/SA      ( 7343): [RC New] Execute method=[GET] start
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/SA      ( 7343): [RC New] Security=[true]
,I/System.out( 7343): Thread-1135(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7343): Thread-1135(ApacheHTTPLog):isShipBuild true
,I/System.out( 7343): Thread-1135(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/SA      ( 7343): [RC New] [v2liruge] api execute + 655
,I/SA      ( 7343): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7343): AsyncTask #1 calls detatch()
,I/SA      ( 7343): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7343): [OCP] update openData : PL,
,I/SA      ( 7343): [TPMU] getNetworkMcc : 
,I/SA      ( 7343): [SCU] saveMccToPreferece Start
,I/SA      ( 7343): [SCU] RegionMCC : 260
,I/SA      ( 7343): [SSP] query invoked
,I/SA      ( 7343): [TPMU] GetMccFromDB : null
,I/SA      ( 7343): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 7343): [SCU] saveMccToPreferece End
,I/SA      ( 7343): [RC New] executeRequest [v2liruge] end. 772
,I/SA      ( 7343): [RC New] Execute end
,I/SA      ( 7343): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 7343): [OR] GetMyCountryZoneTask Success
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 7923): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 7923): wlan0: sendmsg: Cannot assign requested address
,D/WearableService( 2256): callingUid 10011, callindPid: 2256
,D/ResourcesManager( 7840): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,E/WifiStateMachine(  901): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  901): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  901): identical MTU - not setting
D/ConnectivityService(  901): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  901): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
E/WifiStateMachine(  901): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
V/        (  287): QcRouteController
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
,D/SmartBondingService(  901): getSBEnabled() enabled =false
,W/ResourcesManager( 7840): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7840): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7840): Using the GMSCore's GoogleHttpClient
,V/        (  287): QcRouteController
,W/NetworkManagementService(  901): route cmd failed: 
W/NetworkManagementService(  901): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  901): '
W/NetworkManagementService(  901): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  901): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  901): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  901): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  901): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  901): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  901): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  901): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  901): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  901): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  901): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  901): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  901): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  901): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
,D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 2469): CM callback handler got msg 524295
,D/ConnectivityService(  901): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WearableClient( 7840): WearableClientImpl.onPostInitHandler: done
D/ConnectivityService(  901): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524295
,D/WearableClient( 7840): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7840): WearableClientImpl.onPostInitHandler: done
,D/ConnectivityManager.CallbackHandler( 2469): CM callback handler got msg 524295
,D/WearableClient( 7840): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7840): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 7840): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7840): Conditions not met for autocaching.
I/MusicLeanback( 7840): Stop autocaching.
,E/ActivityThread( 7840): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2447ce7a that was originally bound here
E/ActivityThread( 7840): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2447ce7a that was originally bound here
E/ActivityThread( 7840): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7840): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7840): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7840): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7840): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7840): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7840): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7840): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7840): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7840): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7840): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7840): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7840): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7840): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7840): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7840): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7840): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7840): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7840): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7840): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7840): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7840): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7840): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7840): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/PackageManager(  901): [MSG] MCS_UNBIND
,I/ActivityManager(  901): Killing 7389:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
,I/WifiStateMachine(  901): REQUEST_POWER_SAVE_ON
,W/libprocessgroup(  901): failed to open /acct/uid_10057/pid_7389/cgroup.procs: No such file or directory
,E/SMD     (  293): DCD ON
,E/WifiStateMachine(  901): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  257): id=16 Removed Toast (8/9)
,I/SurfaceFlinger(  257): id=16 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/PowerManagerService(  901): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 901) eventTime = 125703
,D/PowerManagerService(  901): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=901 (0x0)
,D/PowerManagerService(  901): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=901, ws=WorkSource{10058}) (elapsedTime=3522)
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/GAV4    ( 8019): Thread[GAThread,5,main]: No campaign data found.
,D/SSRM:m  (  901): SIOP:: AP = 380, PST = 344, CUR = 450
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7277): mConnectivityHandler : connected
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7277): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7277): [GetString-S]
,I/ReactiveServiceManager( 7277): Supported : 1
,D/QSEECOMAPI: (  901): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: (  901): App is not loaded in QSEE
,D/QSEECOMAPI: (  901): Loaded image: APP id = 3
,D/QSEECOMAPI: (  901): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  901): QSEECom_shutdown_app, app_id = 3
,E/terrier (  901): handleString: Failed to handle string(-4)
E/terrier (  901): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 7277): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7277): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7277): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7277): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7277): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7277): [ensureRegistration] - No Samsung account
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 2
,I/dhcpcd  ( 7923): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  293): DCD ON,
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  ( 7923): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7923): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 7749): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7749): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7749): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7749): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7749): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7749): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7749): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7749): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 7749): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7749): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7749): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7749): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7749): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7749): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7749): entry::IDLE
,V/AlarmManager(  901): waitForAlarm result :4
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  901): stay LED for fully charged
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6642): [1085] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6642): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  293): DCD ON
,E/Watchdog(  901): !@Sync 4
,E/SMD     (  293): DCD ON
,V/AlarmManager(  901): waitForAlarm result :4
,D/SSRM:m  (  901): SIOP:: AP = 330, PST = 337, CUR = 450
,I/PowerManagerService(  901): [PWL] Off : 30s ago
,I/ActivityManager(  901): Waited long enough for: ServiceRecord{7ce01f0 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  901): SIOP:: AP = 310, PST = 333, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  293): DCD ON
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 50s ago
,D/SSRM:m  (  901): SIOP:: AP = 300, PST = 330, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,E/Watchdog(  901): !@Sync 5
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  901): SIOP:: AP = 290, PST = 326, CUR = 450
,V/AlarmManager(  901): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  901): SIOP:: AP = 290, PST = 323, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 75s ago
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  901): stay LED for fully charged
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  901): SIOP:: AP = 290, PST = 320, CUR = 450
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,E/Watchdog(  901): !@Sync 6
,I/ClearcutLoggerApiImpl( 2256): disconnect managed GoogleApiClient
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  901): SIOP:: AP = 280, PST = 317, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  901): SIOP:: AP = 270, PST = 311, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 105s ago
,I/Atfwd_Sendcmd(  341): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  341): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  901): SIOP:: AP = 270, PST = 301, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,E/Watchdog(  901): !@Sync 7
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  901): SIOP:: AP = 260, PST = 289, CUR = 450
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...,
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/AlarmManager(  901): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  901): stay LED for fully charged
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  901): SIOP:: AP = 260, PST = 282, CUR = 450
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  901): [PWL] Off : 140s ago
,D/SSRM:m  (  901): SIOP:: AP = 260, PST = 277, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD ON
,E/Watchdog(  901): !@Sync 8
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  901): SIOP:: AP = 260, PST = 273, CUR = 450
,I/jxcore-log( 7448): --= Surplus to requirements =--
I/jxcore-log( 7448): 
,I/jxcore-log( 7448): ****TEST TOOK:  ms ****
I/jxcore-log( 7448): 
I/jxcore-log( 7448): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7448): 
,D/AndroidRuntime( 8324): 
D/AndroidRuntime( 8324): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8324): CheckJNI is OFF
,D/AndroidRuntime( 8324): setted country_code = Poland
,D/AndroidRuntime( 8324): setted countryiso_code = PL
,D/AndroidRuntime( 8324): setted sales_code = XEO
,D/AndroidRuntime( 8324): readGMSProperty: start
,D/AndroidRuntime( 8324): readGMSProperty: already setted!!
D/AndroidRuntime( 8324): readGMSProperty: end
D/AndroidRuntime( 8324): addProductProperty: start
,E/AffinityControl( 8324): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8324): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  901): START PACKAGE DELETE: observer{211416693}
D/PackageManager(  901): pkg{<packageName>}
D/PackageManager(  901): user{0}
D/PackageManager(  901): caller{2000}
D/PackageManager(  901): flags{3}
,D/PersonaManagerService(  901): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  901): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  901): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  901): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  901): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  901): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  901): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  901): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  901): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  901): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  901): !@killApplicatoin: 10191, uninstall pkg
,I/ActivityManager(  901): Force stopping com.test.thalitest appid=10191 user=-1: uninstall pkg
,I/ActivityManager(  901): Killing 7448:com.test.thalitest/u0a191 (adj 0): stop com.test.thalitest
,I/ActivityManager(  901):   Force finishing activity ActivityRecord{7316a29 u0 com.test.thalitest/.MainActivity t10}
,D/FocusedStackFrame(  901): Set to : 0
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/SurfaceFlinger(  257): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (6/8)
,I/SurfaceFlinger(  257): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/WifiService(  901): Client connection lost with reason: 4
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  901): Force stopping com.test.thalitest appid=10191 user=0: pkg removed
,I/art     ( 2469): Explicit concurrent mark sweep GC freed 5754(266KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/35MB, paused 569us total 48.568ms
,I/art     ( 1567): Explicit concurrent mark sweep GC freed 7856(561KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 408us total 44.036ms
,I/art     ( 6430): Explicit concurrent mark sweep GC freed 31953(1741KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 370us total 42.945ms
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  901): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 1473): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
W/ResourcesManager( 1473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/SamsungIME( 1865): mOCRHelper is null
,D/ResourcesManager( 1473): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,D/EnterpriseDeviceManagerService(  901): Package has changed for user 0
D/EnterpriseDeviceManagerService(  901): Admin package name: com.google.android.gms
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 1473): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/GeofencerStateMachine( 2256): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.4.503: ( 7935): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7935): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453043190279
,I/KLMS-2.4.503: ( 7935): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7935): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,I/art     (  901): Explicit concurrent mark sweep GC freed 66709(4MB) AllocSpace objects, 48(768KB) LOS objects, 30% free, 35MB/51MB, paused 1.936ms total 195.545ms
,I/art     (  901): WaitForGcToComplete blocked for 116.794ms for cause Explicit
D/ResourcesManager(  901): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/RegisteredServicesCache( 1461): empty dynamic service
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/SecContentProvider2(  901): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  901): mCursor = null
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/Zygote  ( 8354): MountEmulatedStorage()
E/Zygote  ( 8354): v2
I/libpersona( 8354): KNOX_SDCARD checking this for 10103
I/libpersona( 8354): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8354 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,I/SELinux ( 8354): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8354): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8354): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/TimaKeyStoreProvider( 8354): TimaSignature is unavailable
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ActivityThread( 8354): Added TimaKeyStore provider
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/art     (  901): Explicit concurrent mark sweep GC freed 10948(536KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 35MB/51MB, paused 6.709ms total 237.980ms
D/SurfaceWidgetView( 1473): destroyHardwareResources():416003878
,D/ResourcesManager(  901): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  901): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/ResourcesManager( 8354): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/Launcher( 1473): onRestart, Launcher: 387088648
,D/Launcher( 1473): onStart, Launcher: 387088648
D/Launcher.HomeView( 1473): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1970): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1970): [237392/6] SurfaceWidget drawing first frame
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,I/SurfaceFlinger(  257): id=17 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1180): value : false
,D/RCPManagerService(  901): PackageReceiver onReceive()
I/HarmonyEASService(  901): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/KnoxMUMContainerPolicy(  901): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/BackupManagerService(  901): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  901): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  901): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  901): uID is 10191
V/EnterpriseBillingPolicy(  901): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  901): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  901): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  901): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  901): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  901): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  901): getBillingProfileForVpnEngine - end - null
,D/TaskPersister(  901): removeObsoleteFile: deleting file=10_task.xml
,D/elm:14451( 8354): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8354): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8354): MDMBridge.setEnterpriseBridge()
,D/elm:14451( 8354): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/InputMethodManagerService(  901): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/elm:14451( 8354): ElmAgentService : onCreate()
W/InputMethodManagerService(  901): Got RemoteException sending setActive(false) notification to pid 7448 uid 10191
,E/Zygote  ( 8373): MountEmulatedStorage()
E/Zygote  ( 8373): v2
I/libpersona( 8373): KNOX_SDCARD checking this for 10016
I/libpersona( 8373): KNOX_SDCARD not a persona
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/ActivityManager(  901): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8373 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,D/elm:14451( 8354): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14451( 8354): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8354): MDMBridge.getInstance()
D/elm:14451( 8354): MDMBridge.getAllLicenseInfoFromSDK()
,E/SMD     (  293): DCD ON
,I/SELinux ( 8373): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/SELinux ( 8373): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,E/SELinux ( 8373): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/elm:14451( 8354): MDMBridge.getAllLicenseInfoFromSDK()
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/Timeline(  901): Timeline: Activity_windows_visible id: ActivityRecord{b431cbc u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:259632
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/TimaKeyStoreProvider( 8373): TimaSignature is unavailable
,D/ActivityThread( 8373): Added TimaKeyStore provider
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/elm:14451( 8354): ElmAgentService : onDestroy().
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/ResourcesManager( 8373): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,I/ActivityManager(  901): Killing 6184:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8373): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8373): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8373): onReceive() : package name is not s health. Return !!!
,W/ResourcesManager(  901): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  901): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  901): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,I/PCWCLIENTTRACE_PushUtil( 7277): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7277): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7277): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7277): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/PackageManager(  901): delete codoeFile: 
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  901): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/PackageManager(  901): result of delete: 1{211416693}
,W/libprocessgroup(  901): failed to open /acct/uid_1000/pid_6184/cgroup.procs: No such file or directory
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/AndroidRuntime( 8324): Shutting down VM
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,E/Zygote  ( 8392): MountEmulatedStorage()
E/Zygote  ( 8392): v2
I/libpersona( 8392): KNOX_SDCARD checking this for 10033
I/libpersona( 8392): KNOX_SDCARD not a persona
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
I/ActivityManager(  901): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8392 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 7422:com.google.android.apps.docs/u0a97 (adj 15): bgCount ##41
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  901): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  901): onPackageRemoved : com.test.thalitest
,I/SELinux ( 8392): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8392): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8392): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8392): TimaSignature is unavailable
,D/ActivityThread( 8392): Added TimaKeyStore provider
,W/libprocessgroup(  901): failed to open /acct/uid_10097/pid_7422/cgroup.procs: No such file or directory
,D/ResourcesManager( 8392): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/FeatureConfig( 8392): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 8392): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8392): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8392): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8392): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ResourcesManager( 8392): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 8392): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8392): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8392): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8392): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8392): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8392): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8392): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8392): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8392): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8392): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8392): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8392): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8392): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8392): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8392): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8392): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8392): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8392): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8392): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8392): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8392): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/EventHub(  901): Removing device '/dev/input/event4' due to inotify event
,W/ResourcesManager( 8392): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8392): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,F/libc    ( 8392): Fatal signal 7 (SIGBUS), code 2, fault addr 0x9a8c8cb3 in tid 8392 (pp.galaxyfinder)
,I/EventHub(  901): Removing device '/dev/input/event5' due to inotify event
,E/audit_log( 2184): File locking failed. error= Bad file number
,E/audit_log( 2184): File locking failed. error= Bad file number
,I/ActivityManager(  901): Process com.samsung.android.app.galaxyfinder (pid 8392)(adj 0) has died(206,575)
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,I/EventHub(  901): Removing device '/dev/input/event6' due to inotify event
,E/Zygote  ( 8413): MountEmulatedStorage()
,E/Zygote  ( 8413): v2
I/libpersona( 8413): KNOX_SDCARD checking this for 10034
I/libpersona( 8413): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8413 uid=10034 gids={50034, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/Zygote  (  326): Process 8392 exited due to signal (7)
,I/EventHub(  901): Removing device '/dev/input/event7' due to inotify event
,I/SELinux ( 8413): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
,E/SELinux ( 8413): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/EventHub(  901): Removing device '/dev/input/event8' due to inotify event
,I/EventHub(  901): Removing device '/dev/input/event9' due to inotify event
,D/TimaKeyStoreProvider( 8413): TimaSignature is unavailable
,D/ActivityThread( 8413): Added TimaKeyStore provider
,D/ResourcesManager( 8413): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/ContextImpl( 8413): Unable to create files subdir /data/data/com.sec.android.app.shealth/cache
,E/ActivityThread( 8413): Unable to setupGraphicsSupport due to missing cache directory
,W/        ( 8413): Zip: failed reading lfh name from offset 418254
,I/EventHub(  901): Removing device '/dev/input/event10' due to inotify event
,D/AndroidRuntime( 8413): Shutting down VM
,E/AndroidRuntime( 8413): FATAL EXCEPTION: main
E/AndroidRuntime( 8413): Process: com.sec.android.app.shealth, PID: 8413
E/AndroidRuntime( 8413): java.lang.RuntimeException: Unable to instantiate application com.sec.android.app.shealth.SHealthApplication: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.app.shealth.SHealthApplication" on path: DexPathList[[zip file "/system/priv-app/SHealth3_5/SHealth3_5.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8413): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
E/AndroidRuntime( 8413): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4980)
E/AndroidRuntime( 8413): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8413): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8413): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8413): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8413): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8413): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8413): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8413): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8413): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8413): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.app.shealth.SHealthApplication" on path: DexPathList[[zip file "/system/priv-app/SHealth3_5/SHealth3_5.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8413): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 8413): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 8413): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 8413): 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
E/AndroidRuntime( 8413): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
E/AndroidRuntime( 8413): 	... 10 more
E/AndroidRuntime( 8413): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/SHealth3_5/SHealth3_5.apk' doesn't contain classes.dex (error msg: I/O Error)
E/AndroidRuntime( 8413): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 8413): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 8413): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 8413): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 8413): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 8413): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 8413): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 8413): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 8413): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 8413): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
E/AndroidRuntime( 8413): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8413): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8413): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
E/AndroidRuntime( 8413): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
E/AndroidRuntime( 8413): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
E/AndroidRuntime( 8413): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 8413): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 8413): 		... 10 more
E/AndroidRuntime( 8413): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app,/SHealth3_5/SHealth3_5.apk'
E/AndroidRuntime( 8413): 		... 27 more
E/AndroidRuntime( 8413): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/SHealth3_5/arm/SHealth3_5.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 8413): 		... 27 more
E/AndroidRuntime( 8413): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 8413): 		... 27 more
E/AndroidRuntime( 8413): 	Suppressed: java.lang.ClassNotFoundException: com.sec.android.app.shealth.SHealthApplication
E/AndroidRuntime( 8413): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 8413): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 8413): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 8413): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 8413): 		... 13 more
E/AndroidRuntime( 8413): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
F/libc    (  901): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa0a64f04 in tid 1578 (Binder_D)
F/libc    (  901): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2184): File locking failed. error= Bad file number
,I/ServiceManager(  255): service 'sec_analytics' died
I/ServiceManager(  255): service 'application_policy' died
I/ServiceManager(  255): service 'wifi_policy' died
I/ServiceManager(  255): service 'phone_restriction_policy' died
I/ServiceManager(  255): service 'remoteinjection' died
I/ServiceManager(  255): service 'mum_container_policy' died
I/ServiceManager(  255): service 'enterprise_billing_policy' died
I/ServiceManager(  255): service 'knox_timakeystore_policy' died
I/ServiceManager(  255): service 'enterprise_policy' died
I/ServiceManager(  255): service 'statusbar' died
I/ServiceManager(  255): service 'clipboard' died
I/ServiceManager(  255): service 'clipboardEx' died
I/ServiceManager(  255): service 'network_management' died
I/ServiceManager(  255): service 'ABTPersistenceService' died
I/ServiceManager(  255): service 'textservices' died
I/ServiceManager(  255): service 'network_score' died
I/ServiceManager(  255): service 'netstats' died
I/ServiceManager(  255): service 'netpolicy' died
I/ServiceManager(  255): service 'backup' died
I/ServiceManager(  255): service 'wifi' died
I/ServiceManager(  255): service 'msapwifi' died
I/ServiceManager(  255): service 'wifiscanner' died
I/ServiceManager(  255): service 'rttmanager' died
I/ServiceManager(  255): service 'connectivity' died
I/ServiceManager(  255): service 'sb_service' died
I/ServiceManager(  255): service 'clinfo' died
I/ServiceManager(  255): service 'servicediscovery' died
I/ServiceManager(  255): service 'updatelock' died
I/ServiceManager(  255): service 'notification' died
I/ServiceManager(  255): service 'devicestoragemonitor' died
I/ServiceManager(  255): service 'location' died
I/ServiceManager(  255): service 'country_detector' died
I/ServiceManager(  255): service 'sec_location' died
I/ServiceManager(  255): service 'search' died
I/ServiceManager(  255): service 'dropbox' died
I/ServiceManager(  255): service 'wallpaper' died
I/ServiceManager(  255): service 'appwidget' died
I/ServiceManager(  255): service 'voiceinteraction' died
I/ServiceManager(  255): service 'SecExternalDisplayService' died
I/ServiceManager(  255): service 'diskstats' died
I/ServiceManager(  255): service 'spengestureservice' died
I/ServiceManager(  255): service 'quickconnect' died
I/ServiceManager(  255): service 'samplingprofiler' died
I/ServiceManager(  255): service 'commontime_management' died
I/ServiceManager(  255): service 'dreams' died
I/ServiceManager(  255): service 'print' died
I/ServiceManager(  255): service 'restrictions' died
I/ServiceManager(  255): service 'media_session' died
I/ServiceManager(  255): service 'media_router' died
I/ServiceManager(  255): service 'trust' died
I/ServiceManager(  255): service 'fingerprint' died
I/ServiceManager(  255): service 'launcherapps' died
I/ServiceManager(  255): service 'voip' died
I/ServiceManager(  255): service 'media_projection' died
I/ServiceManager(  255): service 'imms' died
I/ServiceManager(  255): service 'audio' died
I/ServiceManager(  255): service 'DockObserver' died
I/ServiceManager(  255): service 'usb' died
I/ServiceManager(  255): service 'serial' died
I/ServiceManager(  255): service 'uimode' died
I/ServiceManager(  255): service 'jobscheduler' died
I/ServiceManager(  255): service 'wifip2p' died
I/ServiceManager(  255): service 'rcp' died
I/ServiceManager(  255): service 'input_method' died
I/ServiceManager(  255): service 'accessibility' died
I/ServiceManager(  255): service 'motion_recognition' died
I/ServiceManager(  255): service 'cover' died
I/ServiceManager(  255): service 'mount' died
I/ServiceManager(  255): service 'lock_settings' died
I/ServiceManager(  255): service 'device_policy' died
I/ServiceManager(  255): service 'harmony_eas_service' died
I/ServiceManager(  255): service 'sdp' died
I/ServiceManager(  255): service 'log_manager_service' died
I/ServiceManager(  255): service 'batterystats' died
I/ServiceManager(  255): service 'appops' died
I/ServiceManager(  255): service 'power' died
I/ServiceManager(  25,5): service 'display' died
I/ServiceManager(  255): service 'enterprise_license_policy' died
I/ServiceManager(  255): service 'samsung.smartfaceservice' died
I/ServiceManager(  255): service 'consumer_ir' died
I/ServiceManager(  255): service 'alarm' died
I/ServiceManager(  255): service 'SEAMService' died
I/ServiceManager(  255): service 'persona' died
I/ServiceManager(  255): service 'account' died
I/ServiceManager(  255): service 'content' died
I/ServiceManager(  255): service 'DirEncryptService' died
I/ServiceManager(  255): service 'ReactiveService' died
I/ServiceManager(  255): service 'persona_policy' died
I/ServiceManager(  255): service 'sedenial' died
I/ServiceManager(  255): service 'vibrator' died
I/ServiceManager(  255): service 'tw_toolbox' died
I/ServiceManager(  255): service 'tima' died
I/ServiceManager(  255): service 'cepproxyks' died
I/ServiceManager(  255): service 'CustomFrequencyManagerService' died
I/ServiceManager(  255): service 'context_aware' died
I/ServiceManager(  255): service 'scontext' died
I/ServiceManager(  255): service 'barbeam' died
I/ServiceManager(  255): service 'multiwindow_facade' died
I/ServiceManager(  255): service 'window' died
I/ServiceManager(  255): service 'input' died
I/ServiceManager(  255): service 'tactileassist' died
I/ServiceManager(  255): service 'bluetooth_manager' died
I/ServiceManager(  255): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  255): service 'activity' died
I/ServiceManager(  255): service 'dbinfo' died
I/ServiceManager(  255): service 'telephony.registry' died
I/ServiceManager(  255): service 'user' died
I/ServiceManager(  255): service 'procstats' died
I/ServiceManager(  255): service 'entropy' died
I/ServiceManager(  255): service 'gfxinfo' died
I/ServiceManager(  255): service 'cpuinfo' died
I/ServiceManager(  255): service 'permission' died
I/ServiceManager(  255): service 'webviewupdate' died
I/ServiceManager(  255): service 'meminfo' died
I/ServiceManager(  255): service 'hardware' died
I/ServiceManager(  255): service 'battery' died
I/ServiceManager(  255): service 'usagestats' died
I/ServiceManager(  255): service 'scheduling_policy' died
I/ServiceManager(  255): service 'package' died
I/ServiceManager(  255): service 'edmnativehelper' died
I/ServiceManager(  255): service 'sensorservice' died
I/ServiceManager(  255): service 'mdm.remotedesktop' died
W/Sensors ( 1180): sensorservice died [0xaefce0c0]
W/AudioFlinger(  299): power manager service died !!!
W/AudioFlinger(  299): power manager service died !!!
W/Sensors ( 2287): sensorservice died [0xaefbbc40]
E/WifiManager( 1180): Channel connection lost
W/Sensors ( 1467): sensorservice died [0xaefd23c0]
W/Sensors ( 1473): sensorservice died [0xaef52440]
I/SurfaceFlinger(  257): restart the boot-animation @ binderDied
W/Sensors ( 7516): sensorservice died [0xaef71f40]
D/SurfaceFlinger(  257): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  257): hwc_blank: Unblanking display: 0
E/WifiManager( 1311): Channel connection lost
E/WifiManager( 1467): Channel connection lost
W/Sensors ( 2256): sensorservice died [0xaef7b840]
I/SurfaceFlinger(  257): id=2 Removed FocusedStackFrame (5/8)
E/WifiManager( 2256): Channel connection lost
I/SurfaceFlinger(  257): id=3 Removed DimLayer (0/7)
I/SurfaceFlinger(  257): id=4 Removed DimLayer (0/6)
I/SurfaceFlinger(  257): id=5 Removed DimLayer (0/5)
I/SurfaceFlinger(  257): id=6 Removed DimLayer (0/4)
I/SurfaceFlinger(  257): id=2 Removed FocusedStackFrame (-2/4)
I/SurfaceFlinger(  257): id=3 Removed DimLayer (-2/4)
I/SurfaceFlinger(  257): id=4 Removed DimLayer (-2/4)
E/WifiManager( 1567): Channel connection lost
I/SurfaceFlinger(  257): id=5 Removed DimLayer (-2/4)
I/SurfaceFlinger(  257): id=6 Removed DimLayer (-2/4)
I/SurfaceFlinger(  257): id=14 Removed ColorFade (3/3)
I/SurfaceFlinger(  257): id=17 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (1/2)
I/SurfaceFlinger(  257): id=7 Removed com.android.systemui.ImageWallpaper (0/1)
I/SurfaceFlinger(  257): id=7 Removed com.android.systemui.ImageWallpaper (-2/1)
I/SurfaceFlinger(  257): id=17 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/1)
I/SurfaceFlinger(  257): id=9 Removed StatusBar (0/0)
I/SurfaceFlinger(  257): id=9 Removed StatusBar (-2/0)
I/SurfaceFlinger(  257): id=14 Removed ColorFade (-2/0)
W/Sensors ( 1450): sensorservice died [0xaefbbc00]
,F/libc    ( 8413): Fatal signal 7 (SIGBUS), code 2, fault addr 0x74d1fda1 in tid 8413 (oid.app.shealth)
W/Sensors ( 1311): sensorservice died [0x9d3212c0]
F/libc    ( 8413): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2184): File locking failed. error= Bad file number
,I/Zygote  (  326): Process 8413 exited due to signal (7)
,E/installd(  304): eof
E/installd(  304): failed to read size
I/installd(  304): closing connection
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  257): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  257): hwc_blank: Done unblanking display: 0
,E/qdhwcomposer(  257): hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
E/SurfaceFlinger(  257): eventControl(0, 1) failed Operation not permitted
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,I/lowmemorykiller(  254): ActivityManager disconnected
I/lowmemorykiller(  254): Closing Activity Manager data connection
,F/libc    (  292): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb6f6c314 in tid 1083 (ddexe)
,F/libc    (  292): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2184): File locking failed. error= Bad file number
,F/libc    (  294): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb6f953f6 in tid 294 (connfwexe)
F/libc    (  294): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2184): File locking failed. error= Bad file number
,E/SMD     (  293): ***Received data notification[DR->SMD]***
E/SMD     (  293): The connection is closed by peer
E/SMD     (  293): connect error:111
,I/SurfaceFlinger(  257): Disp[0] Orientation 0=>0

```
