#### Test 54312298c831015_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
,D/Mms/BubbleViewCache( 7061): fillCache bubble = 8
D/TP/MmsSmsProvider( 1487): query,matched:0, calling pid = 7061
V/TP/MmsSmsProvider( 1487): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1487): match 0:Elapsed time : 1.278 ms
D/Mms/Synchronizer( 7061): [start]    doSync consume time = 240.66151
D/TP/MmsSmsProvider( 1487): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 1487): syncDBData start
--------- beginning of system
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
V/TP/MmsSmsProvider( 1487): syncDBData sms end
V/TP/MmsSmsProvider( 1487): syncDBData mms end
V/TP/MmsSmsProvider( 1487): syncDBData end
E/Zygote  ( 7092): MountEmulatedStorage()
E/Zygote  ( 7092): v2
I/libpersona( 7092): KNOX_SDCARD checking this for 10077
I/libpersona( 7092): KNOX_SDCARD not a persona
I/ActivityManager(  905): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7092 uid=10077 gids={50077, 9997} abi=armeabi-v7a
D/Mms/Synchronizer( 7061): [end]    doSync consume time = 20.148334
I/SELinux ( 7092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7092): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7092): TimaSignature is unavailable
D/ActivityThread( 7092): Added TimaKeyStore provider
D/ResourcesManager( 7092): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
D/BadgeProvider( 7092): onCreate
D/BadgeProvider( 7092): DatabaseHelper
D/Mms/MessagingNotification( 7061): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1487): query,matched:26, calling pid = 7061
D/TP/SmsProvider( 1487): match 26:Elapsed time : 0.822 ms
D/TP/MmsSmsProvider( 1487): query,matched:6, calling pid = 7061
D/TP/MmsSmsProvider( 1487): match 6:Elapsed time : 0.830 ms
I/Mms/ReservationManager( 7061): ReservationManager()
I/Mms/ReservationManager( 7061): resetAfterConnected()
D/TP/MmsSmsProvider( 1487): query,matched:7, calling pid = 7061
D/TP/MmsSmsProvider( 1487): match 7:Elapsed time : 1.198 ms
I/Mms/ReservationManager( 7061): getReservedSendMessageCount(): retMessageCount=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
V/AlarmManager(  905): waitForAlarm result :4
E/Zygote  ( 7109): MountEmulatedStorage()
E/Zygote  ( 7109): v2
I/libpersona( 7109): KNOX_SDCARD checking this for 10024
I/libpersona( 7109): KNOX_SDCARD not a persona
I/ActivityManager(  905): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7109 uid=10024 gids={50024, 9997} abi=armeabi-v7a
I/SELinux ( 7109): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7109): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7109): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7109): TimaSignature is unavailable
D/ActivityThread( 7109): Added TimaKeyStore provider
D/ResourcesManager( 7109): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
W/ResourcesManager( 7109): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/AndroidRuntime( 7107): 
D/AndroidRuntime( 7107): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7107): CheckJNI is OFF
D/AndroidRuntime( 7107): setted country_code = Poland
D/AndroidRuntime( 7107): setted countryiso_code = PL
D/AndroidRuntime( 7107): setted sales_code = XEO
D/AndroidRuntime( 7107): readGMSProperty: start
D/AndroidRuntime( 7107): readGMSProperty: already setted!!
D/AndroidRuntime( 7107): readGMSProperty: end
D/AndroidRuntime( 7107): addProductProperty: start
D/Mms/Omacp( 7061): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
D/Mms/MmsApp( 7061): [end]    onCreate() consume time = 227.572083
D/Mms/PerformanceUtils( 7061): link cahcing start
D/Mms/DownloadManager( 7061): Service state changed: Bundle[mParcelledData.dataSize=692]
D/Mms/DownloadManager( 7061): roaming ------> false, mSimSlot = 0
D/Mms/TelephonyUtils( 7061): getSubId from simSlot 0, return Value = -1
D/Mms/DownloadManager( 7061): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 7061): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 7061): auto download without roaming -> true
D/Mms/DownloadManager( 7061): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 7061): mAutoDownload ------> true
I/ActivityManager(  905): Killing 6014:com.sec.android.widgetapp.dualclockdigital/u0a102 (adj 15): bgCount ##41
I/ActivityManager(  905): Killing 6033:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
D/Mms/FreeMessageReceiver( 7061): onReceive, action : android.intent.action.PACKAGE_ADDED
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7136): MountEmulatedStorage()
I/libpersona( 7136): KNOX_SDCARD checking this for 10050
E/Zygote  ( 7136): v2
I/libpersona( 7136): KNOX_SDCARD not a persona
D/Mms/PerformanceUtils( 7061): link cahcing done
D/Mms/FreeMessageReceiverService( 7061): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 7061): onHandleIntent: ACTION_PACKAGE_ADDED
I/ActivityManager(  905): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7136 uid=10050 gids={50050, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 7136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7136): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  905): Killing 5527:com.sec.android.app.camera/u0a153 (adj 15): bgCount ##41
E/AffinityControl( 7107): AffinityControl: registerfunction enter
D/TimaKeyStoreProvider( 7136): TimaSignature is unavailable
D/ActivityThread( 7136): Added TimaKeyStore provider
D/AndroidRuntime( 7107): Calling main entry com.android.commands.am.Am
D/ResourcesManager( 7136): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager( 7136): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7136): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
E/PersonaManagerService(  905): inState():  stateMachine is null !!
V/ApplicationPolicy(  905): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  905): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/libprocessgroup(  905): failed to open /acct/uid_10102/pid_6014/cgroup.procs: No such file or directory
W/libprocessgroup(  905): failed to open /acct/uid_10112/pid_6033/cgroup.procs: No such file or directory
W/ActivityManager(  905): mDVFSHelper.acquire()
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7160): MountEmulatedStorage()
E/Zygote  ( 7160): v2
I/libpersona( 7160): KNOX_SDCARD checking this for 10356
I/libpersona( 7160): KNOX_SDCARD not a persona
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7160 uid=10356 gids={50356, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7160): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7160): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7160): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
W/libprocessgroup(  905): failed to open /acct/uid_10153/pid_5527/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1182): value : false
D/AndroidRuntime( 7107): Shutting down VM
D/MyFiles ( 7136): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager(  905): Killing 6062:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/TimaKeyStoreProvider( 7160): TimaSignature is unavailable
D/ActivityThread( 7160): Added TimaKeyStore provider
E/installd(  303): system dir 0 : /system/app/
E/installd(  303): system dir 1 : /system/priv-app/
E/installd(  303): system dir 2 : /vendor/app/
E/installd(  303): system dir 3 : /oem/app/
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/TactileAssist(  905): enable value -1
I/TactileAssist(  905): internal enable value -1
I/TactileAssist(  905): intensity value -1
I/TactileAssist(  905): saveAppList value true
I/TactileAssist(  905): List of disabled apps :
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
D/ResourcesManager( 7160): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
W/libprocessgroup(  905): failed to open /acct/uid_1000/pid_6062/cgroup.procs: No such file or directory
I/SQLiteSecureOpenHelper( 3240): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3240): getDatabaseLocked(b,b,pwd)...
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
E/Zygote  ( 7178): MountEmulatedStorage()
E/Zygote  ( 7178): v2
I/libpersona( 7178): KNOX_SDCARD checking this for 10057
I/libpersona( 7178): KNOX_SDCARD not a persona
I/ActivityManager(  905): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7178 uid=10057 gids={50057, 9997, 3003, 3002} abi=armeabi-v7a
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/SELinux ( 7178): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7178): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7178): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/PackageManager(  905): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/TimaKeyStoreProvider( 7178): TimaSignature is unavailable
D/ActivityThread( 7178): Added TimaKeyStore provider
D/ResourcesManager( 7178): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/ResourcesManager( 7178): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 7178): onReceive() it will make start service
D/Compatibility( 7178): onHandleIntent()
D/Compatibility( 7178): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10356, android.intent.extra.user_handle=0}]
D/Compatibility( 7178): found: 2
I/UpdateIcingCorporaServi( 1583): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 7178): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7178): skipping ResolveInfo{24d48fd com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7178): considering ResolveInfo{37d359f2 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7178): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7178): enabling receiver ResolveInfo{2d913843 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7178): enabling receiver ResolveInfo{2ccb8ec0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/ContextImpl( 6077): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
D/Compatibility( 7178): enabling receiver ResolveInfo{aa77f9 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/WebViewFactory( 7160): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7160): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/Compatibility( 7178): enabling receiver ResolveInfo{3cb9233e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7178): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7198): MountEmulatedStorage()
E/Zygote  ( 7198): v2
I/libpersona( 7198): KNOX_SDCARD checking this for 10097
I/libpersona( 7198): KNOX_SDCARD not a persona
I/LibraryLoader( 7160): Loading: webviewchromium
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7198 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/LibraryLoader( 7160): Time to load native libraries: 3 ms (timestamps 7573-7576)
I/LibraryLoader( 7160): Expected native library version number "",actual native library version number ""
,D/ResourcesManager( 1583): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/UpdateIcingCorporaServi( 1583): UpdateCorporaTask done [took 64 ms] updated apps [took 64 ms] 
,I/SELinux ( 7198): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7198): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7198): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/WebViewChromiumFactoryProvider( 7160): Binding Chromium to main looper Looper (main, tid 1) {aa77f9}
,I/LibraryLoader( 7160): Expected native library version number "",actual native library version number ""
I/chromium( 7160): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7160): Initializing chromium process, renderers=0
,W/art     ( 7160): Attempt to remove local handle scope entry from IRT, ignoring
,D/TimaKeyStoreProvider( 7198): TimaSignature is unavailable
,D/ActivityThread( 7198): Added TimaKeyStore provider
,W/chromium( 7160): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7160): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 7160): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/ResourcesManager( 7198): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/Adreno-EGL( 7160): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7160): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7160): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7160): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7160): Remote Branch: 
I/Adreno-EGL( 7160): Local Patches: 
I/Adreno-EGL( 7160): Reconstruct Branch: 
,W/chromium( 7160): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7160): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7160): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7160): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7160): CordovaWebView is running on device made by: samsung
,W/art     ( 7160): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7160): Attempt to remove local handle scope entry from IRT, ignoring
,D/DocsApplication( 7198): Installing DEX configuration.
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/DexInstaller( 7198): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 7198): Provided clientMode=RELEASE, packageInfo=PackageInfo{bcab154 com.google.android.apps.docs}
,D/Activity( 7160): performCreate Call secproduct feature valuefalse
D/Activity( 7160): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7160): Render dirty regions requested: true
,D/TAG     ( 7198): onCreate()
,D/ActivityManager(  905): post active user change for 0
D/KnoxTimeoutHandler(  905): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  905): handleActiveUserChange for user 0
,D/CrossAppStateProvider( 7198): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,I/SurfaceFlinger(  257): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/StatusBarManagerService(  905): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/StatusBarManagerService(  905): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/OpenGLRenderer( 7160): Initialized EGL, version 1.4
I/OpenGLRenderer( 7160): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7160): Enabling debug mode 0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/InputMethodManagerService(  905): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,W/IInputConnectionWrapper( 7160): showStatusIcon on inactive InputConnection
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 7160): Timeline: Activity_idle id: android.os.BinderProxy@124027f0 time:107899
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,W/ActivityManager(  905): mDVFSHelper.release()
I/Timeline(  905): Timeline: Activity_windows_visible id: ActivityRecord{2803daae u0 com.test.thalitest/.MainActivity t4} time:107915
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/JsMessageQueue( 7160): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7160): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358131200
,D/JX-Cordova( 7160): jxcore cordova android initializing
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/Zygote  ( 7260): MountEmulatedStorage()
I/libpersona( 7260): KNOX_SDCARD checking this for 10098
E/Zygote  ( 7260): v2
I/libpersona( 7260): KNOX_SDCARD not a persona
I/ActivityManager(  905): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7260 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  905): Killing 6159:com.sec.android.app.sns3/u0a35 (adj 15): bgCount ##41
I/SELinux ( 7260): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7260): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7260): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/GAV2    ( 7198): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/TimaKeyStoreProvider( 7260): TimaSignature is unavailable
D/ActivityThread( 7260): Added TimaKeyStore provider
D/ResourcesManager( 7260): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
W/libprocessgroup(  905): failed to open /acct/uid_10035/pid_6159/cgroup.procs: No such file or directory
W/ResourcesManager( 7260): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/[CarMode]( 7260): [DLApplication]-onCreate: Applicatino Started!
D/SampleAppCoreManager( 7260): SampleAppCoreManager VACVersion '2.2.0.11867'
I/VlingoAndroidCore( 7260): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7289): MountEmulatedStorage()
E/Zygote  ( 7289): v2
I/libpersona( 7289): KNOX_SDCARD checking this for 10032
I/libpersona( 7289): KNOX_SDCARD not a persona
I/ActivityManager(  905): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7289 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 7289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7289): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7289): TimaSignature is unavailable
D/ActivityThread( 7289): Added TimaKeyStore provider
W/GAV2    ( 7198): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/ResourcesManager( 7289): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/ResourcesManager( 7289): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/System.out( 7289): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 7289): Inside WakeupProvider
,E/DatabaseUtils( 7289): Writing exception to parcel
E/DatabaseUtils( 7289): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7289): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7289): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7289): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7289): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7289): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7289): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7289): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7289): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7289): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7289): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 7260): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 7260): 	at android.os.Parcel.readException(Parcel.java:1546)
,W/System.err( 7260): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7260): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7260): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7260): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7260): 	at android.content.ContentResolver.query(ContentResolver.java:428)
,W/System.err( 7260): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7260): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7260): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7260): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
,W/System.err( 7260): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7260): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7260): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7260): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
,W/System.err( 7260): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7260): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7260): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7260): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
,W/System.err( 7260): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7260): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7260): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7260): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
,W/System.err( 7260): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
,W/System.err( 7260): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7260): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7260): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 7260): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7260): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7260): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7260): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
,W/System.err( 7260): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/DatabaseUtils( 7289): Writing exception to parcel
E/DatabaseUtils( 7289): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7289): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7289): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7289): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7289): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7289): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7289): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7289): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7289): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7289): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7289): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 7260): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 7260): 	at android.os.Parcel.readException(Parcel.java:1546)
,W/System.err( 7260): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
,W/System.err( 7260): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7260): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7260): 	at android.content.ContentResolver.query(ContentResolver.java:484)
,W/System.err( 7260): 	at android.content.ContentResolver.query(ContentResolver.java:428)
,W/System.err( 7260): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
,W/System.err( 7260): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7260): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7260): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
,W/System.err( 7260): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
,W/System.err( 7260): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7260): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7260): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
,W/System.err( 7260): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
,W/System.err( 7260): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7260): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7260): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7260): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
,W/System.err( 7260): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
,W/System.err( 7260): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7260): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7260): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7260): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
,W/System.err( 7260): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 7260): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7260): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7260): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/[CarMode]( 7260): [DLApplication]-Init Called!:false
,E/[CarMode]( 7260): [DLApplication]-Init Started!:true
,I/[CarModeFW]( 7260): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7260): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7260): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7260): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7260): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7260): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7260): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7260): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7260): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7260): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7260): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7260): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7260): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7260): ### com.android.internal.os.ZygoteInit::main(1194)
,I/VlingoApplication( 7289): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
W/jxcore-log( 7160): Initializing JXcore engine
W/jxcore-log( 7160): JXcore engine is ready
,W/jxcore-log( 7160): Starting JXcore engine
,I/MessageDataHandler( 7260): initialize
,D/[CarModeFW]( 7260): CDH-initiazlieCaches : before sync
,D/[CarModeFW]( 7260): CDH-initiazlieCaches : after sync
,D/[CarModeFW]( 7260): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 7260): CDH-ContactDataHandler initiazlieCaches time : 16
,D/[CarModeFW]( 7260): CDH-initiazlieCaches : end sync
,D/[CarModeFW]( 7260): DrivingManager-initialize...
,I/SensorService(  905): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  905): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  905): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,E/auditd  ( 2169): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  905): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService(  905): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
I/VlingoAndroidCore( 7289): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
,I/MediaPlayer( 7260): Need to enable context aware info
V/MediaPlayer-JNI( 7260): native_setup
V/MediaPlayer( 7260): constructor
,D/FactoryTest( 6353): Not factory mode
,D/FactoryTest( 6353): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6353): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6353): still no open session command from host, so toast
,W/ContextImpl( 6353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6353): Timeline: Activity_launch_request id:com.android.settings time:109433
,E/PersonaManagerService(  905): inState():  stateMachine is null !!
,V/ApplicationPolicy(  905): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,V/MediaPlayer( 7260): setListener
E/MediaPlayer-JNI( 7260): QCMediaPlayer mediaplayer NOT present
,W/ActivityManager(  905): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
E/MTPRx   ( 6353): started activity for popup
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/VlingoApplication( 7289): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 7289): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/[CarModeFW]( 7260): PushMessageManager-bindPushMessageService
,W/jxcore-log( 7160): Platform android
W/jxcore-log( 7160): 
W/jxcore-log( 7160): Process ARCH arm
W/jxcore-log( 7160): 
,I/[CarModeFW]( 7260): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/[CarMode]( 7260): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,I/SQLiteSecureOpenHelper( 3240): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3240): getDatabaseLocked(b,b,pwd)...
,D/[CarMode]( 7260): [DLServiceManager]-requestRecommendedLocationList
,D/[CarModeFW]( 7260): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1450738953287
D/[CarModeFW]( 7260): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1450738953287
D/[CarModeFW]( 7260): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1450738953288
,D/[CarModeFW]( 7260): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1450738953288
,D/[CarModeFW]( 7260): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1450738953292
,I/[CarMode]( 7260): [LogNotNull]-Package name is: com.google.android.apps.maps
,D/[CarModeFW]( 7260): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1450738953301
,D/TP/SmsProvider( 1487): query,matched:2, calling pid = 7260
,E/[CarMode]( 7260): [DLApplication]-Init End!:true
D/TP/SmsProvider( 1487): query,matched:2, calling pid = 7260
D/TP/SmsProvider( 1487): match 2:Elapsed time : 0.101 ms
D/TP/SmsProvider( 1487): match 2:Elapsed time : 1.664 ms
D/ResourcesManager( 6353): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6353): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6353): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6353): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6353): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6353): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6353): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6353): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/[CarModeFW]( 7260): CDH-buildContactCacheWireFrame : cur len =0
,D/MessageDataHandler( 7260):  getInboxList smsCursor : 32
,D/TP/MmsProvider( 1487): Query uri=content://mms/inbox, match=2, calling pid = 7260
,D/TP/MmsProvider( 1487): Query uri=content://mms, match=0, calling pid = 7260
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7331): MountEmulatedStorage()
E/Zygote  ( 7331): v2
I/libpersona( 7331): KNOX_SDCARD checking this for 10019
I/libpersona( 7331): KNOX_SDCARD not a persona
,E/SettingsReceiverActivity( 6353): PREF_DONT_ASK_AGAIN : true
,I/ActivityManager(  905): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7331 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7337): MountEmulatedStorage()
,E/Zygote  ( 7337): v2
I/libpersona( 7337): KNOX_SDCARD checking this for 10003
I/libpersona( 7337): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7337 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,D/MessageDataHandler( 7260):  getInboxList mmsCursor : 46
,I/art     (  321): Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 296us total 12.989ms
,E/SMD     (  295): DCD ON
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 245us total 7.965ms
,I/SELinux ( 7331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 10.345ms
,I/SELinux ( 7337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
E/SELinux ( 7331): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/SELinux ( 7337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1182): value : false
E/SELinux ( 7337): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/[CarMode]( 7260): [DLApplication]-GooglePlayServices SUCCESS.
,I/MessageDataHandler( 7260): getUnreadMessageCount :0
,D/[CarModeFW]( 7260): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 167
,D/[CarModeFW]( 7260): CDH-buildContactCacheWireFrame : cur len =0
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
D/TimaKeyStoreProvider( 7331): TimaSignature is unavailable
D/ActivityThread( 7331): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 7337): TimaSignature is unavailable
,D/ActivityThread( 7337): Added TimaKeyStore provider
,D/MessageDataHandler( 7260):  getInboxList mms,sms cursor join : 104
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/[CarModeFW]( 7260): RecommendHandler-selection = type = '3'
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/TP/MmsSmsProvider( 1487): query,matched:0, calling pid = 7260
V/TP/MmsSmsProvider( 1487): getSimpleConversations entered.
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/TP/MmsSmsProvider( 1487): match 0:Elapsed time : 1.919 ms
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,D/[CarModeFW]( 7260): CDH-buildContactCacheWireFrame : cur len =0
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,D/[CarModeFW]( 7260): RecommendHandler-selection = type = '3'
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
E/[CarMode]( 7260): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,I/UpdateManagerReceiver( 7260): Intent : android.intent.action.PACKAGE_ADDEDTue Dec 22 00:02:33 GMT+01:00 2015
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,D/TP/MmsSmsProvider( 1487): query,matched:13, calling pid = 7260
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
D/TP/MmsSmsProvider( 1487): match 13:Elapsed time : 2.497 ms
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6353): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/ResourcesManager( 7331): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
D/ResourcesManager( 7337): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,E/Zygote  ( 7362): MountEmulatedStorage()
E/Zygote  ( 7362): v2
I/libpersona( 7362): KNOX_SDCARD checking this for 1000
I/libpersona( 7362): KNOX_SDCARD not a persona
,D/SettingsReceiverActivity( 6353): dev.kiessupport is : TRUE
,I/ActivityManager(  905): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7362 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  905): Killing 6206:com.sec.spp.push:RemoteDlcProcess/u0a37 (adj 15): bgCount ##41
,I/SELinux ( 7362): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7362): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7362): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/MessageDataHandler( 7260):  getInboxList address cursor : 65
,D/TP/MmsSmsProvider( 1487): query,matched:0, calling pid = 7260
,V/TP/MmsSmsProvider( 1487): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1487): match 0:Elapsed time : 6.684 ms
,D/TimaKeyStoreProvider( 7362): TimaSignature is unavailable
,D/ActivityThread( 7362): Added TimaKeyStore provider
,D/MessageDataHandler( 7260):  getInboxList thread cursor : 13
,D/MessageDataHandler( 7260):  thread, addr result: 2
,I/[CarModeFW]( 7260): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 297
I/[CarModeFW]( 7260): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/Activity( 6353): performCreate Call secproduct feature valuefalse
D/Activity( 6353): performCreate Call debug elastic valuetrue
D/[CarModeFW]( 7260): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 304
,D/[CarModeFW]( 7260): PushMessageService-onCreate
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,W/libprocessgroup(  905): failed to open /acct/uid_10037/pid_6206/cgroup.procs: No such file or directory
,D/UserAnalysis.PlaceProvider( 7337): PlaceProvider onCreate()
,I/ActivityManager(  905): Killing 5504:com.android.calendar/u0a149 (adj 15): bgCount ##41
,I/ActivityManager(  905): Killing 5748:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): bgCount ##42
,I/ActivityManager(  905): Killing 6225:com.sec.spp.push:RemoteNotiProcess/u0a37 (adj 15): bgCount ##43
,D/ResourcesManager( 7362): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/[CarModeFW]( 7260): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7260): PushMessageService-registerPushMessageServiceListener
,W/ContextImpl( 7362): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7378): MountEmulatedStorage()
E/Zygote  ( 7378): v2
I/libpersona( 7378): KNOX_SDCARD checking this for 10111
I/libpersona( 7378): KNOX_SDCARD not a persona
,D/UserAnalysis.SecureDbManager( 7337): Key for secure DB is newly created
I/ActivityManager(  905): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7378 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/UserAnalysis.SecurePlaceDbHelper( 7337): SecurePlaceDbHelper() 
,D/UserAnalysis.PlaceProvider( 7337): Create SecureDbHelper
,D/ResourcesManager( 7362): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/SELinux ( 7378): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7378): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7378): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/FilterInstaller( 7362): There is no requred permission
,I/ActivityManager(  905): Killing 5819:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7378): TimaSignature is unavailable
,D/ActivityThread( 7378): Added TimaKeyStore provider
,I/art     (  905): Explicit concurrent mark sweep GC freed 219971(14MB) AllocSpace objects, 2(4MB) LOS objects, 31% free, 35MB/51MB, paused 1.561ms total 114.721ms
,D/IntelligenceServiceApplication( 7337): onCreate()
,D/ResourcesManager( 7378): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/SQLiteSecureOpenHelper( 7337): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 7337): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7337): Open Place.db in secure mode
,D/[CarModeFW]( 7260): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 543
,I/SQLiteSecureOpenHelper( 7337): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 7337): ...getDatabaseLocked(b,b,pwd)
D/PackageIntentReceiver( 7378): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7378): Not GearManger package! 
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7396): MountEmulatedStorage()
E/Zygote  ( 7396): v2
I/libpersona( 7396): KNOX_SDCARD checking this for 10117
I/libpersona( 7396): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7396 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  905): Killing 5485:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,I/[CarModeFW]( 7260): -[snowdeer] Rec : Missed Call : 376
,I/SELinux ( 7396): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7396): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/libprocessgroup(  905): failed to open /acct/uid_10148/pid_5748/cgroup.procs: No such file or directory
W/libprocessgroup(  905): failed to open /acct/uid_10037/pid_6225/cgroup.procs: No such file or directory
E/SELinux ( 7396): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  905): failed to open /acct/uid_10149/pid_5504/cgroup.procs: No such file or directory
,D/[CarModeFW]( 7260): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 7260): MyPlaceProvider-=============
D/[CarModeFW]( 7260): MyPlaceProvider-=============
,I/[CarModeFW]( 7260): -[snowdeer] Rec : Favorite : 50
,D/[CarModeFW]( 7260): MyPlaceProvider-=============
D/[CarModeFW]( 7260): MyPlaceProvider-=============
D/[CarModeFW]( 7260): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7260): MyPlaceProvider-==============
D/[CarModeFW]( 7260): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7260): MyPlaceProvider-==============
D/[CarModeFW]( 7260): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 7260): MyPlaceProvider-==============
D/[CarModeFW]( 7260): MyPlaceProvider-latitude is not valid
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7410): MountEmulatedStorage()
I/libpersona( 7410): KNOX_SDCARD checking this for 10045
E/Zygote  ( 7410): v2
I/libpersona( 7410): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7410 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/[CarModeFW]( 7260): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 625
,I/SELinux ( 7410): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/[CarMode]( 7260): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@2cb0be31, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@1dad2cd3] LOCATIONS
,I/[CarModeFW]( 7260): -[snowdeer] Rec : CallLog : 55
D/SSRM:m  (  905): SIOP:: AP = 380, PST = 374, CUR = 450
I/SELinux ( 7410): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/libprocessgroup(  905): failed to open /acct/uid_1000/pid_5819/cgroup.procs: No such file or directory
E/SELinux ( 7410): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7396): TimaSignature is unavailable
,D/ActivityThread( 7396): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 7410): TimaSignature is unavailable
,D/ActivityThread( 7410): Added TimaKeyStore provider
,D/ResourcesManager( 7396): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,I/ActivityManager(  905): Killing 6092:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
,W/ResourcesManager( 7396): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7410): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 7410): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/libprocessgroup(  905): failed to open /acct/uid_10045/pid_5485/cgroup.procs: No such file or directory
,D/MagazineService Version( 7396): Magazine-Administrator: 11
,D/MagazineService Version( 7396): Magazine-Provider: 14
,D/MagazineService Version( 7396): Magazine-Channel: 14
,W/libprocessgroup(  905): failed to open /acct/uid_10167/pid_6092/cgroup.procs: No such file or directory
D/HeadlinesChannelApplication( 7396): [onCreate]
,I/CalendarProvider2( 7410): CalendarProvider2.onCreate() called
,D/MagazineService::MagazineBroadcastReceiver( 7396): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7396): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 7427): MountEmulatedStorage()
,E/Zygote  ( 7427): v2
I/libpersona( 7427): KNOX_SDCARD checking this for 1000
I/libpersona( 7427): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7427 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7396): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/jxcore-log( 7160): JXcore Cordova bridge is ready!
I/jxcore-log( 7160): 
,W/jxcore-log( 7160): JXcore engine is started
,W/ActivityManager(  905): Activity pause timeout for ActivityRecord{2803daae u0 com.test.thalitest/.MainActivity t4}
,I/SELinux ( 7427): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/InputMethodManagerService(  905): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/SELinux ( 7427): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7427): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/InputMethodManagerService(  905): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@9fa7fcd attribute=null, token = android.os.BinderProxy@3564ee09
,I/ActivityManager(  905): Killing 6379:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,D/ActivityManager(  905): post active user change for 0
D/KnoxTimeoutHandler(  905): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  905): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/TimaKeyStoreProvider( 7427): TimaSignature is unavailable
D/ActivityThread( 7427): Added TimaKeyStore provider
,I/Timeline( 7160): Timeline: Activity_idle id: android.os.BinderProxy@124027f0 time:110326
,D/ResourcesManager( 7427): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,W/libprocessgroup(  905): failed to open /acct/uid_1000/pid_6379/cgroup.procs: No such file or directory
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7443): MountEmulatedStorage()
E/Zygote  ( 7443): v2
I/libpersona( 7443): KNOX_SDCARD checking this for 1000
I/libpersona( 7443): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7443 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  905): Killing 5844:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): bgCount ##41
,I/System.out( 7289): INFO:Resource not found:/Common.properties Using default values
,I/SELinux ( 7443): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7443): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7443): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/[CarModeFW]( 7260): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7260): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7260): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7260): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 980
,D/TimaKeyStoreProvider( 7443): TimaSignature is unavailable
,D/ActivityThread( 7443): Added TimaKeyStore provider
,I/[CarModeFW]( 7260): -[snowdeer] Rec : Schedule : 321
,I/[CarModeFW]( 7260): -[snowdeer] Rec : During DL app : 2
D/ResourcesManager( 7443): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,I/[CarModeFW]( 7260): -[snowdeer] Rec : Location Sharing : 1
I/[CarModeFW]( 7260): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 7260): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7260): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7260): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 7260): -[snowdeer] Rec : getContactListFromHashMap : 0
D/[CarModeFW]( 7260): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 997
,W/libprocessgroup(  905): failed to open /acct/uid_10157/pid_5844/cgroup.procs: No such file or directory
,D/AcmsPackageEventListener( 7443): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 7443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService( 7443): Enter Oncreate
,D/AcmsServiceMonitor( 7443): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 7443): creating AcmsCore
D/AcmsCore( 7443): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7443): AcmsCore
,D/AcmsCore( 7443): init
D/AcmsCore( 7443): Looper handler is not null
D/AcmsCore( 7443): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7443): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7443): Incrementing - Counter value: 1
D/AcmsCore( 7443): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 7443): onStartCommand
D/AcmsService( 7443): Action: android.intent.action.PACKAGE_ADDED
D/AcmsCertificateMngr( 7443): AcmsCertificateMngr
D/AcmsServiceMonitor( 7443): Enter incrementSvcCounter with startId 1
D/AcmsRevocationMngr( 7443): AcmsRevocationMngr
,D/AcmsServiceMonitor( 7443): Incrementing - Counter value: 2
D/AcmsService( 7443): Incremented Counter Value : onStartCommand
,D/ActivityThread( 7443): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsService( 7443): Inside handle Intent
D/AcmsService( 7443): App added - package name: com.test.thalitest
D/AcmsCore( 7443): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7443): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7443): Incrementing - Counter value: 3
D/AcmsCore( 7443): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7443): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7443): Decrementing - Counter value: 2
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7464): MountEmulatedStorage()
I/libpersona( 7464): KNOX_SDCARD checking this for 10165
E/Zygote  ( 7464): v2
I/libpersona( 7464): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7464 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7464): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7464): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7464): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7464): TimaSignature is unavailable
,D/ActivityThread( 7464): Added TimaKeyStore provider
,D/ResourcesManager( 7464): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7464): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 7464): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7479): MountEmulatedStorage()
E/Zygote  ( 7479): v2
I/libpersona( 7479): KNOX_SDCARD checking this for 10169
I/libpersona( 7479): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7479 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 7479): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7479): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7479): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7479): TimaSignature is unavailable
,D/ActivityThread( 7479): Added TimaKeyStore provider
,D/ResourcesManager( 7479): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 7479): (284) automatic index on shooting_modes(title_id)
,D/Finsky  ( 6539): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/PackageBroadcastService( 2493): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2493): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2493): Loading module APK com.google.android.play.games
,D/ResourcesManager( 2493): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ChimeraCfgMgr( 2493): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2493): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2493): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 2493): Submit a task: k
,D/ChimeraCfgMgr( 2493): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 2493): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2493): Processing package: com.test.thalitest
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7503): MountEmulatedStorage()
I/libpersona( 7503): KNOX_SDCARD checking this for 10039
E/Zygote  ( 7503): v2
I/libpersona( 7503): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7503 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/GassUtils( 2493): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
D/k       ( 2493): Found info for package com.test.thalitest in db.
,I/SELinux ( 7503): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7503): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7503): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7503): TimaSignature is unavailable
,D/ActivityThread( 7503): Added TimaKeyStore provider
,D/ResourcesManager( 7503): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,W/BaseAppContext( 2493): Using Auth Proxy for data requests.
W/BaseAppContext( 2493): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 2493): cleanUpNonGplusAccounts done.
,W/BaseAppContext( 2493): Using Auth Proxy for data requests.
,W/BaseAppContext( 2493): Using Auth Proxy for data requests.
,W/BaseAppContext( 2493): Using Auth Proxy for data requests.
W/BaseAppContext( 2493): Using Auth Proxy for data requests.
,W/BaseAppContext( 2493): Using Auth Proxy for data requests.
,I/ActivityManager(  905): Killing 5134:com.google.android.talk/u0a116 (adj 15): bgCount ##41
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7521): MountEmulatedStorage()
E/Zygote  ( 7521): v2
I/libpersona( 7521): KNOX_SDCARD checking this for 1000
I/libpersona( 7521): KNOX_SDCARD not a persona
I/ActivityManager(  905): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7521 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/CalendarProvider2( 7410): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/SELinux ( 7521): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7521): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7521): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  905): Killing 6433:com.samsung.android.app.FileShareServer/u0a74 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7521): TimaSignature is unavailable
,D/ActivityThread( 7521): Added TimaKeyStore provider
,D/ResourcesManager( 7521): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  905): failed to open /acct/uid_10116/pid_5134/cgroup.procs: No such file or directory
,D/SecurityLogAgent( 7521):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7521):  SeDenialReceiver : File path = null
,I/ActivityManager(  905): Killing 6451:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,D/BootupListener( 1487): ACTION_DRIVELINK
,D/SettingsProvider(  905): name = drivelink_navigation
,D/SettingsProvider(  905): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  905): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  905): selectionArgs: false
D/SettingsProvider(  905): selectionArgs: 1001
D/SecContentProvider(  905): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  905): ret = -1
D/BootupListener( 1487): NAVI : com.google.android.apps.maps
,D/SettingsProvider(  905): name = internet_call_settings_visibility
D/SettingsProvider(  905): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  905): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  905): selectionArgs: false
D/SettingsProvider(  905): selectionArgs: 1001
,D/SecContentProvider(  905): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  905): ret = -1
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7537): MountEmulatedStorage()
E/Zygote  ( 7537): v2
I/libpersona( 7537): KNOX_SDCARD checking this for 10148
I/libpersona( 7537): KNOX_SDCARD not a persona
,I/jxcore-log( 7160): Toggling radios to true
I/jxcore-log( 7160): 
,D/BluetoothAdapter( 7160): enable()
,I/ActivityManager(  905): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7537 uid=10148 gids={50148, 9997} abi=armeabi-v7a
,I/art     (  321): Explicit concurrent mark sweep GC freed 8766(373KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 287us total 14.541ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 246us total 8.075ms
,I/SELinux ( 7537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 262us total 7.874ms
I/SELinux ( 7537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7537): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  905): failed to open /acct/uid_10074/pid_6433/cgroup.procs: No such file or directory
,D/BluetoothAdapter( 7160): enable(): BT is already enabled..!
,D/WifiService(  905): New client listening to asynchronous messages
,I/WifiManager( 7160): packageName : com.test.thalitest
,D/SecContentProvider(  905): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  905): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  905): mCursor = null
,I/GoogleURLConnFactory( 2244): Using platform SSLCertificateSocketFactory
,D/WifiService(  905): setWifiEnabled: true pid=7160, uid=10356
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  905): Permission Denial: getCurrentUser() from pid=7160, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
,D/TimaKeyStoreProvider( 7537): TimaSignature is unavailable
,D/ActivityThread( 7537): Added TimaKeyStore provider
,W/WifiService(  905): Failed getting userId using ActivityManagerNative
W/WifiService(  905): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7160, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  905): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  905): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  905): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  905): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  905): name = wifi_on
I/WifiService(  905): disconnect: pid=7160, uid=10356
,I/jxcore-log( 7160): Radios toggled
I/jxcore-log( 7160): 
I/wpa_supplicant( 1285): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,W/libprocessgroup(  905): failed to open /acct/uid_1000/pid_6451/cgroup.procs: No such file or directory
,V/GLSActivity( 2244): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 1285): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1285): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1285): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1285): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  905): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1285): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1285): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1285): Disconnected - do not scan
I/wpa_supplicant( 1285): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/jxcore-log( 7160): Got Device Bluetooth address: 7C:F9:0E:34:8A:A0
I/jxcore-log( 7160): 
,E/WifiStateMachine(  905): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  905): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  905): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  905): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/jxcore-log( 7160): Perf Test app loaded loaded
I/jxcore-log( 7160): 
,I/jxcore-log( 7160): check test folder
I/jxcore-log( 7160): 
,I/jxcore-log( 7160): found test : ./testFindPeers.js
I/jxcore-log( 7160): 
,E/WifiStateMachine(  905): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  905): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  905): do suspend true
,D/WifiP2pService(  905): InactiveState{ what=143375 }
,D/WifiP2pService(  905): P2pEnabledState{ what=143375 }
,D/CommandListener(  288): Clearing all IP addresses on wlan0
,V/NativeCrypto( 2244): Read error: ssl=0xaee47e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2244): SSL shutdown failed: ssl=0xaee47e00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  905): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,I/jxcore-log( 7160): found test : ./testSendData.js
I/jxcore-log( 7160): 
E/ConnectivityService(  905): updateNetworkInfo()
D/ConnectivityService(  905): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  905): updateNetworkInfo()
D/ConnectivityService(  905): ignoring duplicate network state non-change
,D/ConnectivityService(  905): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,E/WifiConfigStore(  905): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  905): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  905): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  905): Forcing reevaluation
D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  905): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiTrafficPoller(  905): evaluateTrafficStatsPolling
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  905): Validated
,I/CLocInfoService(  905): External Intent Received android.net.wifi.STATE_CHANGE
D/ResourcesManager( 7537): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 7537): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
W/ResourcesManager( 7537): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/StatusBar.NetworkController( 1182): applyOpen
,D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
,D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
,E/WifiStateMachine(  905): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1285): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1285): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1285): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1285): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1285): First Scan Start
I/wpa_supplicant( 1285): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  905): ConnectModeState: Network connection lost 
E/WifiStateMachine(  905): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  905): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  905): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  905): do suspend true
D/WifiP2pService(  905): InactiveState{ what=143375 }
D/WifiP2pService(  905): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/jxcore-log( 7160): found test : ./testSendData2.js
I/jxcore-log( 7160): 
,E/jxcore  ( 7160): Error!: missing ) after argument list
E/jxcore  ( 7160): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,D/CommandListener(  288): Clearing all IP addresses on wlan0
D/ConnectivityService(  905): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  905): calling update connectivity
D/ConnectivityService(  905):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  905):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  905): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/EntConnectivity(  905): Not allowed due to - mEnabled false
D/ConnectivityService(  905):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  905): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  905): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  905): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524292
D/ConnectivityService(  905): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  905): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  905): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  905): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  905): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  905): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 2493): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1487): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  905): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/chromium( 7160): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WifiStateMachine(  905): updateConfiguredNetworkExpiration - currTime: 1450738955660
I/WifiTrafficPoller(  905): evaluateTrafficStatsPolling
D/WifiStateMachine(  905): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine(  905): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  905): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/CLocInfoService(  905): External Intent Received android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  905): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  905): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  905): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  905): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  905): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  905): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  905): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  905): setDetailed state send new extra info"NG700"
D/SecContentProvider2(  905): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  905): mCursor = null
E/ConnectivityService(  905): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/SmartBondingService(  905): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  905): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
V/NetworkStats(  905): updateIfacesLocked()
D/SmartBondingService(  905): getSBEnabled() enabled =false
D/SmartBondingService(  905): getSBEnabled() enabled =false
D/SmartBondingService(  905): getSBEnabled() enabled =false
V/NetworkStats(  905): performPollLocked(flags=0x1)
D/NtpTrustedTime(  905): currentTimeMillis() cache hit
D/NetworkStatsFactory(  905): UpdateStatsForKnox
D/NtpTrustedTime(  905): currentTimeMillis() cache hit
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  905): currentTimeMillis() cache hit
D/NtpTrustedTime(  905): currentTimeMillis() cache hit
V/NetworkStats(  905): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  905): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1182): updateDataNetType()
D/StatusBar.NetworkController( 1182): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1182): updateLTEICONDataNetType:0
D/SmartBondingService(  905): getNetworkEnabled : wifi : true mobile : true
D/StatusBar.NetworkController( 1182): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
V/NetworkStats(  905): performPollLocked() took 14ms
D/SecContentProvider2(  905): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  905): mCursor = null
D/NtpTrustedTime(  905): currentTimeMillis() cache hit
D/NtpTrustedTime(  905): currentTimeMillis() cache hit
D/NtpTrustedTime(  905): currentTimeMillis() cache hit
I/PhenotypeConfigurator( 2244): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7561): MountEmulatedStorage()
,E/Zygote  ( 7561): v2
I/libpersona( 7561): KNOX_SDCARD checking this for 10149
I/libpersona( 7561): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7561 uid=10149 gids={50149, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 7561): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7561): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7561): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  905): Killing 6495:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7561): TimaSignature is unavailable
,D/ActivityThread( 7561): Added TimaKeyStore provider
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/ResourcesManager( 7561): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,I/chromium( 7160): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,W/art     ( 2493): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 214.817ms
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,W/ResourcesManager( 7561): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7561): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7561): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/AcmsKeyStoreHelper( 7443):  getKeyStoreForApplication Enter
,I/chromium( 7160): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7160): 
,W/libprocessgroup(  905): failed to open /acct/uid_1000/pid_6495/cgroup.procs: No such file or directory
,I/AcmsKeyStoreHelper( 7443): Key Store exist
I/AcmsKeyStoreHelper( 7443): Hence loading the keystore file
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/Hs20UtilService( 1320): Starting #6
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1320): Message received 5007
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1320): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1320): MountReceiver.mPrefHandler - 7002
,D/ChimeraCfgMgr( 2493): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2493): Module APK com.google.android.play.games already loaded
,I/art     ( 2244): Explicit concurrent mark sweep GC freed 39821(2MB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 20MB/33MB, paused 617us total 50.666ms
I/Hs20UtilService( 1320): Starting #7
I/Hs20UtilService( 1320): Message received 5007
D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1320): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1320): MountReceiver.mPrefHandler - 7002
I/System.out( 2244): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 2244): (HTTPLog)-Static: isShipBuild true
I/System.out( 2244): (HTTPLog)-Thread-299-318012946: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
I/ActivityManager(  905): Killing 6110:com.google.android.gm/u0a113 (adj 15): bgCount ##41
W/PhenotypeConfigurator( 2244): IOException while sending for: 
I/Icing   ( 2493): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
D/AcmsKeyStoreHelper( 7443):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 7443): getKeyStoreForApplication success 
D/AcmsCore( 7443): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7443): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7443): Decrementing - Counter value: 1
D/AcmsCore( 7443): AcmsCore: ACMS_APP_INSTALLED
D/AcmsCore( 7443): This is NOT a valid MirrorLink app
D/AcmsCore( 7443): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7443): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7443): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7443): Counter value is 0: Stopping ACMS service
D/AcmsServiceMonitor( 7443): getSvcCounter - Counter value: 0
D/AcmsService( 7443): Enter onDestroy
I/AcmsService( 7443): cleanUp(): inside service clean up
D/AcmsCore( 7443): AcmsCore: inside DeInit
D/AcmsCore( 7443): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7443): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 7443): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7443): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7443): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7443): getSvcCounter - Counter value: 0
D/AcmsService( 7443): killing acms process
I/Process ( 7443): Sending signal. PID: 7443 SIG: 9
I/ActivityManager(  905): Process ACMS.Process (pid 7443)(adj 0) has died(72,572)
W/libprocessgroup(  905): failed to open /acct/uid_10113/pid_6110/cgroup.procs: No such file or directory
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/ApplicationPolicy(  905): updateDataUsageMap
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2094): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SystemBroadcastReceiver( 6246): [#DCM#] [DCM_Performance] onReceive completed in time  403 microsec. 
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 4286): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
D/Tethering(  905): MasterInitialState.processMessage what=3
D/SmartBondingService(  905): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5777): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  905): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  905): getSBEnabled() enabled =false
D/SmartBondingService(  905): getSBEnabled() enabled =false
D/SmartBondingService(  905): getSBEnabled() enabled =false
I/CLocInfoService(  905): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  905): CLoinfo wifi false
I/PCWCLIENTTRACE_PushUtil( 6999): SPPPushClient is installed : true
D/SmartBondingService(  905): getNetworkEnabled : wifi : true mobile : true
I/PCWCLIENTTRACE_PushUtil( 6999): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6999): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6999): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/SystemBroadcastReceiver( 6246): [#DCM#] Calling notifyListeners. 
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DCMController( 6246): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 6246): [#DCM#] setIsConnectedForExtractors 
W/SLocation(  905): No Active Data Connection
I/VacuumService( 2244): Vacuum at: now=1450738956227 tag=VacuumService
I/PCWCLIENTTRACE_SYSTEMReceiver( 6999): noConnectivity : true
I/DBG_DM  ( 4286): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
W/ActivityManager(  905): mDVFSHelper.release()
I/art     (  905): Explicit concurrent mark sweep GC freed 43078(2MB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 35MB/51MB, paused 3.665ms total 115.236ms
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7607): MountEmulatedStorage()
E/Zygote  ( 7607): v2
I/libpersona( 7607): KNOX_SDCARD checking this for 10002
I/libpersona( 7607): KNOX_SDCARD not a persona
I/ActivityManager(  905): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7607 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ResourcesManager( 2493): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SELinux ( 7607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Icing   ( 2493): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
D/TimaKeyStoreProvider( 7607): TimaSignature is unavailable
D/ActivityThread( 7607): Added TimaKeyStore provider
D/ResourcesManager( 7607): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
I/ActivityManager(  905): Killing 6246:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/SMD     (  295): DCD ON
E/Zygote  ( 7625): MountEmulatedStorage()
E/Zygote  ( 7625): v2
I/libpersona( 7625): KNOX_SDCARD checking this for 1000
I/libpersona( 7625): KNOX_SDCARD not a persona
I/ActivityManager(  905): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7625 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7625): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7625): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7625): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  905): failed to open /acct/uid_10004/pid_6246/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 7625): TimaSignature is unavailable
D/ActivityThread( 7625): Added TimaKeyStore provider
D/ResourcesManager( 7625): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
I/DIAGMON_AGENT( 7625): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
I/DIAGMON_AGENT( 7625): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
I/DIAGMON_AGENT( 7625): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
I/ServiceManager(  332): Waiting for service AtCmdFwd...
I/DIAGMON_AGENT( 7625): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
I/DIAGMON_AGENT( 7625): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7625): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7644): MountEmulatedStorage()
E/Zygote  ( 7644): v2
I/libpersona( 7644): KNOX_SDCARD checking this for 10010
I/libpersona( 7644): KNOX_SDCARD not a persona
I/ActivityManager(  905): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7644 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7644): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7644): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7644): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7644): TimaSignature is unavailable
D/ActivityThread( 7644): Added TimaKeyStore provider
D/ResourcesManager( 7644): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
I/wpa_supplicant( 1285): nl80211: Received scan results (2 BSSes)
I/wpa_supplicant( 1285): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1285): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1285): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1285): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
E/WifiStateMachine(  905): [1,450,738,956,700 ms] noteScanEnd no scan source
E/WifiStateMachine(  905): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@37c19eba sup_state=SCANNING debouncing=false
I/CLocInfoService(  905): External Intent Received android.net.wifi.SCAN_RESULTS
E/WifiStateMachine(  905): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  905): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  905): setDetailed state send new extra info0x
D/SecContentProvider2(  905): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  905): mCursor = null
I/ActivityManager(  905): Killing 6281:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
I/FOTA_Client( 7644): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/FOTA_Client( 7644): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
I/FOTA_Client( 7644): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7659): MountEmulatedStorage()
E/Zygote  ( 7659): v2
I/libpersona( 7659): KNOX_SDCARD checking this for 10018
I/libpersona( 7659): KNOX_SDCARD not a persona
I/ActivityManager(  905): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7659 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  905): Killing 6742:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
I/SELinux ( 7659): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7659): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/libprocessgroup(  905): failed to open /acct/uid_10043/pid_6281/cgroup.procs: No such file or directory
E/SELinux ( 7659): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  905): failed to open /acct/uid_10011/pid_6742/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 7659): TimaSignature is unavailable
D/ActivityThread( 7659): Added TimaKeyStore provider
D/ResourcesManager( 7659): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/wpa_supplicant( 1285): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1285): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine(  905): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  905): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/wpa_supplicant( 1285): Associated with C0.AA.48
D/SecContentProvider2(  905): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  905): mCursor = null
I/KLMS-2.4.503: ( 7659): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/wpa_supplicant( 1285): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1285): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine(  905): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  905): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  905): setDetailed state send new extra info"NG700"
I/KLMS-2.4.503: ( 7659): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450738956820
D/SecContentProvider2(  905): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  905): mCursor = null
,I/KLMS-2.4.503: ( 7659): MainReciver(): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7659): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/KLMS-2.4.503: ( 7659): StateImplV2(): networkChangeListener().END
,I/wpa_supplicant( 1285): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1285): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1285): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/ActivityManager(  905): Killing 6965:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
E/WifiStateMachine(  905): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  905): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 1285): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1285): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1285): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1285): Blacklist: Clear (temp) 
I/wpa_supplicant( 1285): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  905): Network connection established
,D/WifiNative-HAL(  905): callSECApiVoid - ID [50]
E/WifiStateMachine(  905): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  905): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  905): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  905): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  905): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  905): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  905): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  905): Got NetworkAgent Messenger
D/ConnectivityService(  905): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  905): updateNetworkInfo()
D/ConnectivityService(  905): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  905): NetworkAgent connected
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  905): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  905): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  905): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  905): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Zygote  ( 7675): MountEmulatedStorage()
I/libpersona( 7675): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7675): v2
I/libpersona( 7675): KNOX_SDCARD not a persona
D/CommandListener(  288): Setting iface cfg
E/WifiStateMachine(  905): Start Dhcp Watchdog 2
,I/ActivityManager(  905): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7675 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,D/SecContentProvider2(  905): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  905): mCursor = null
,I/SELinux ( 7675): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7675): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7675): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  905): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  905): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  905): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/TimaKeyStoreProvider( 7675): TimaSignature is unavailable
,D/ActivityThread( 7675): Added TimaKeyStore provider
,W/libprocessgroup(  905): failed to open /acct/uid_10014/pid_6965/cgroup.procs: No such file or directory
,D/ResourcesManager( 7675): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7675): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5368): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 7036): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7036): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7036): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7036): [SLFUCHKMGR] constructor called
,I/SA      ( 7036): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7036): [OR] == isSIMCardReady false ==
,I/SA      ( 7036): [SCU] == networkStateCheck == false
I/SA      ( 7036): [OR] onReceive END
,E/WifiStateMachine(  905): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  905): do suspend false
,E/SPPClientService( 5368): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2(  905): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  905): mCursor = null
D/WifiP2pService(  905): InactiveState{ what=143375 }
,D/WifiP2pService(  905): P2pEnabledState{ what=143375 }
,E/Zygote  ( 7692): MountEmulatedStorage()
E/Zygote  ( 7692): v2
I/libpersona( 7692): KNOX_SDCARD checking this for 10070
I/libpersona( 7692): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7692 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7692): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  905): Killing 6984:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,I/SELinux ( 7692): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7692): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7692): TimaSignature is unavailable
,D/ActivityThread( 7692): Added TimaKeyStore provider
,D/ResourcesManager( 7692): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7692): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7692): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7692): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/libprocessgroup(  905): failed to open /acct/uid_10015/pid_6984/cgroup.procs: No such file or directory
,D/comsamsunglog( 7692): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7692): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7692): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7692): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7692): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7692): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7692): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7692): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  905): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  905): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  905): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  905): selectionArgs: false
D/SettingsProvider(  905): selectionArgs: 10070
D/SecContentProvider(  905): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  905): ret = -1
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7692): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7692): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
D/accuweather( 7692): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7692): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7692): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7692): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7692): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7692): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7692): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7692): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7710): MountEmulatedStorage()
E/Zygote  ( 7710): v2
I/libpersona( 7710): KNOX_SDCARD checking this for 1000
I/libpersona( 7710): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7710 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  905): Killing 6413:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,I/SELinux ( 7710): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7710): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7710): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7710): TimaSignature is unavailable
,D/ActivityThread( 7710): Added TimaKeyStore provider
,W/libprocessgroup(  905): failed to open /acct/uid_10033/pid_6413/cgroup.procs: No such file or directory
,D/ResourcesManager( 7710): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7710): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/dhcpcd  ( 7728): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7728): version 5.5.6 starting
,E/dhcpcd  ( 7728): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/KnoxUsageLogPro( 7710): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7710): premStatus:2
,I/KnoxUsageLogPro( 7710): isEulaShown : false
,I/KnoxUsageLogPro( 7710): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7731): MountEmulatedStorage()
,E/Zygote  ( 7731): v2
I/libpersona( 7731): KNOX_SDCARD checking this for 10087
I/libpersona( 7731): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7731 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  905): Killing 4940:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,I/SELinux ( 7731): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7731): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7731): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 7728): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7728): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7728): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7728): bssid match
,I/dhcpcd  ( 7728): wlan0: rebinding lease of 192.168.1.136
,D/TimaKeyStoreProvider( 7731): TimaSignature is unavailable
,D/ActivityThread( 7731): Added TimaKeyStore provider
,D/ResourcesManager( 7731): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  905): failed to open /acct/uid_10034/pid_4940/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7728): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,I/dhcpcd  ( 7728): wlan0: leased 192.168.1.136 for 86400 seconds
,E/WifiStateMachine(  905): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  905): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  905): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/ActivityManager(  905): Killing 5976:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,D/Headlines( 3498): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 3498): getCountryCode(): countryCode = PL
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
D/Headlines( 3498): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
D/HeadlinesCardManager( 3498): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 3498): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 3498): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 3498): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 3498): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 3498): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7770): MountEmulatedStorage()
E/Zygote  ( 7770): v2
I/libpersona( 7770): KNOX_SDCARD checking this for 10127
I/libpersona( 7770): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7770 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7770): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7770): TimaSignature is unavailable
,D/ActivityThread( 7770): Added TimaKeyStore provider
,D/ResourcesManager( 7770): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  905): failed to open /acct/uid_10041/pid_5976/cgroup.procs: No such file or directory
,I/GAV2    ( 7198): Thread[GAThread,5,main]: No campaign data found.
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/WifiStateMachine(  905): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  905): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  905): do suspend true
,D/WifiP2pService(  905): InactiveState{ what=143375 }
,D/WifiP2pService(  905): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  905): WifiStateMachine DHCP successful
,E/WifiStateMachine(  905): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  905): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  905): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  905): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine(  905): Not connected state, yet.
E/WifiStateMachine(  905): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  905): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  905): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  905): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  905): callSECApiInt - ID [210]
,E/WifiStateMachine(  905): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService(  905): updateNetworkInfo()
,D/ConnectivityService(  905): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  905): Adding iface wlan0 to network 503
,I/CLocInfoService(  905): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  905): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  905): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  905): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  905): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  905): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  905): Now, connected state.
E/WifiStateMachine(  905): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/WifiTrafficPoller(  905): evaluateTrafficStatsPolling
,I/CLocInfoService(  905): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  905): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  905): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  905): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  905): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  905): Unexpected mtu value: 0, wlan0
I/WifiTrafficPoller(  905): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  905): mBoosterFLAG : 0
,I/WifiTrafficPoller(  905): current booster mode : FullMode
D/WifiNative-HAL(  905): callSECApiVoid - ID [212]
,D/ConnectivityService(  905): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  905): updateSourceRoutes : add src route for:192.168.1.136
,V/        (  288): QcRouteController
,I/CLocInfoService(  905): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
,E/WifiStateMachine(  905): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/StatusBar.NetworkController( 1182): applyOpen
,D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
,E/WifiStateMachine(  905): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine(  905): REQUEST_POWER_SAVE_ON
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7770): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
V/        (  288): QcRouteController
,W/ContextImpl( 7770): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7770): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,V/        (  288): QcRouteController
W/ContextImpl( 7770): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,D/ConnectivityService(  905): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  905): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  905): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  905): updateNetworkInfo()
D/ConnectivityService(  905): calling update connectivity
E/ConnectivityService(  905): updateNetworkInfo()
D/ConnectivityService(  905): ignoring duplicate network state non-change
D/ConnectivityService(  905): ignoring duplicate network state non-change
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  905): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  905): Connected
D/ConnectivityService(  905): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  905): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): calling update connectivity
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  905): Validated
D/ConnectivityService(  905): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  905):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  905):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  905):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  905):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  905): currentScore = 0, newScore = 60
D/ConnectivityService(  905):    accepting network in place of null
D/ConnectivityService(  905): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1487): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  905): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  905): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  905): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  905): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  905): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  905): getSBEnabled() enabled =false
,D/SmartBondingService(  905): getSBEnabled() enabled =false
D/SmartBondingService(  905): getSBEnabled() enabled =false
D/ConnectivityService(  905): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  905): calling update connectivity
D/ConnectivityService(  905):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  905):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  905): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkStats(  905): updateIfacesLocked()
D/NtpTrustedTime(  905): currentTimeMillis() cache hit
V/NetworkStats(  905): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  905): UpdateStatsForKnox
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524290
D/ConnectivityService(  905): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  905): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  905): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  905):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  905):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  905):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  905): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  905): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  905): calling update connectivity
D/ConnectivityService(  905):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  905):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  905): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,V/NetworkStats(  905): performPollLocked() took 5ms
D/NtpTrustedTime(  905): currentTimeMillis() cache hit
,D/ConnectivityService(  905):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524290
D/ConnectivityService(  905): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 2493): CM callback handler got msg 524290
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1182): updateDataNetType()
D/StatusBar.NetworkController( 1182): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1182): updateLTEICONDataNetType:0
,D/SmartBondingService(  905): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  905): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 2493): CM callback handler got msg 524290
,D/NtpTrustedTime(  905): currentTimeMillis() cache hit
D/NtpTrustedTime(  905): currentTimeMillis() cache hit
D/NtpTrustedTime(  905): currentTimeMillis() cache hit
V/NetworkStats(  905): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  905): currentTimeMillis() cache hit
D/NtpTrustedTime(  905): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1182): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1182): updateDataNetType()
D/StatusBar.NetworkController( 1182): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1182): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1182): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WebViewFactory( 7770): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7770): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7770): Loading: webviewchromium
,I/LibraryLoader( 7770): Time to load native libraries: 3 ms (timestamps 3986-3989)
,I/LibraryLoader( 7770): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7770): Binding Chromium to main looper Looper (main, tid 1) {3c98f95f}
,I/LibraryLoader( 7770): Expected native library version number "",actual native library version number ""
,I/chromium( 7770): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7770): Initializing chromium process, renderers=0
,W/art     ( 7770): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7770): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7770): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7770): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
W/AudioManagerAndroid( 7770): Requires BLUETOOTH permission
,I/Adreno-EGL( 7770): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7770): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7770): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7770): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7770): Remote Branch: 
I/Adreno-EGL( 7770): Local Patches: 
I/Adreno-EGL( 7770): Reconstruct Branch: 
,I/NSApplication( 7770): Starting up...
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7855): MountEmulatedStorage()
I/libpersona( 7855): KNOX_SDCARD checking this for 10137
E/Zygote  ( 7855): v2
I/libpersona( 7855): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7855 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  905): Killing 5936:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,I/art     (  321): Explicit concurrent mark sweep GC freed 8712(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 276us total 11.541ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 245us total 7.680ms
,I/SELinux ( 7855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7855): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 258us total 8.611ms
,D/TimaKeyStoreProvider( 7855): TimaSignature is unavailable
,D/ActivityThread( 7855): Added TimaKeyStore provider
,W/libprocessgroup(  905): failed to open /acct/uid_10047/pid_5936/cgroup.procs: No such file or directory
,D/ResourcesManager( 7855): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7855): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7855): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7855): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7855): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7855): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7873): MountEmulatedStorage()
E/Zygote  ( 7873): v2
I/libpersona( 7873): KNOX_SDCARD checking this for 10162
I/libpersona( 7873): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7873 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  905): Killing 7092:com.sec.android.provider.badge/u0a77 (adj 15): bgCount ##41
,I/SELinux ( 7873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7873): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7873): TimaSignature is unavailable
,D/ActivityThread( 7873): Added TimaKeyStore provider
,D/ResourcesManager( 7873): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7873): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7873): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7873): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7873): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  905): failed to open /acct/uid_10077/pid_7092/cgroup.procs: No such file or directory
,D/RCPManagerService(  905): exchangeData() failure , invalid userId
,D/RCPManagerService(  905): exchangeData() failure , invalid userId
,D/RCPManagerService(  905): exchangeData() failure , invalid userId
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  905): exchangeData() failure , invalid userId
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/Zygote  ( 7896): MountEmulatedStorage()
,E/Zygote  ( 7896): v2
I/libpersona( 7896): KNOX_SDCARD checking this for 10077
I/libpersona( 7896): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7896 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  905): MasterInitialState.processMessage what=3
D/SmartBondingService(  905): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  905): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  905): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  905): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  905): getSBEnabled() enabled =false
D/SmartBondingService(  905): getSBEnabled() enabled =false
D/SmartBondingService(  905): getSBEnabled() enabled =false
I/CLocInfoService(  905): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  905): CLocinfo wifi true 
D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7896): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7896): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7896): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/SmartBondingService(  905): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2094): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 4286): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 4286): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ContextImpl( 2222): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2222): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5777): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7896): TimaSignature is unavailable
,D/ActivityThread( 7896): Added TimaKeyStore provider
,D/ResourcesManager( 7896): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  905): exchangeData() failure , invalid userId
,D/RCPManagerService(  905): exchangeData() failure , invalid userId
,I/ActivityManager(  905): Killing 7109:com.wsomacp/u0a24 (adj 15): bgCount ##41
,D/SecContentProvider2(  905): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  905): mCursor = null
,D/BadgeProvider( 7896): onCreate
,D/BadgeProvider( 7896): DatabaseHelper
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7521): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7521): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7521): StateMachine : Current State = 1
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7521): StateMachine : Changed Current State = 1
,I/ActivityManager(  905): Killing 7061:com.android.mms/u0a49 (adj 15): bgCount ##41
,D/BadgeProvider( 7896): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/BadgeProvider( 7896): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7896): sendNotify, [notify] : null
D/BadgeProvider( 7896): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7896): update, [BadgeCount] : badgecount=0
D/Launcher.Model( 1494): reloadBadges entered.
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/BadgeProvider( 7896): update, [UpdateCount] : 1
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
E/Zygote  ( 7919): MountEmulatedStorage()
I/libpersona( 7919): KNOX_SDCARD checking this for 10177
E/Zygote  ( 7919): v2
I/libpersona( 7919): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7919 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,I/SELinux ( 7919): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
D/CountryDetector(  905): No listener is left
,I/SELinux ( 7919): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7919): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,W/libprocessgroup(  905): failed to open /acct/uid_10024/pid_7109/cgroup.procs: No such file or directory
,W/libprocessgroup(  905): failed to open /acct/uid_10049/pid_7061/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7919): TimaSignature is unavailable
,D/ActivityThread( 7919): Added TimaKeyStore provider
,D/ResourcesManager( 7919): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/ActivityManager(  905): Killing 7136:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7503): notifyNetworkActivated
,W/ContextImpl( 7503): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ActivityManager(  905): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/libprocessgroup(  905): failed to open /acct/uid_10050/pid_7136/cgroup.procs: No such file or directory
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/hcjo    ( 7503): AutoUpdateManager:IDLE:execute
,I/Hs20UtilService( 1320): Starting #8
,I/Hs20UtilService( 1320): Message received 5007
D/InitializeManagerStateMachine( 7503): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7503): exit::IDLE
D/InitializeManagerStateMachine( 7503): entry::NETWORK_CHECK
D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7503): execute::NETWORK_CHECK:NETWORK_STATE_OK
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
D/InitializeManagerStateMachine( 7503): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7503): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7503): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7503): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7503): entry::SUCCESS
D/hcjo    ( 7503): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7503): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7503): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Hs20UtilService( 1320): Starting #9
,I/Hs20UtilService( 1320): Message received 5007
D/InitializeManagerStateMachine( 7503): exit::SUCCESS
D/InitializeManagerStateMachine( 7503): entry::IDLE
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1320): Starting #10
,I/Hs20UtilService( 1320): Message received 5007
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1320): Starting #11
,I/Hs20UtilService( 1320): Message received 5007
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  905): callSECApi what=220
,D/WifiStateMachine(  905): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService(  905): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/PCWCLIENTTRACE_PushUtil( 6999): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6999): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6999): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6999): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7625): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7625): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SurfaceFlinger(  257): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/PowerManagerService(  905): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=905
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  905): stay LED for fully charged
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  905): Plugged
I/MotionRecognitionService(  905): setPowerConnected  = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/FOTA_Client( 7644): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7644): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7644): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.503: ( 7659): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7659): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450738958838
,I/KLMS-2.4.503: ( 7659): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7659): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7659): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7659): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/KLMS-2.4.503: ( 7659): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7675): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5368): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7036): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7036): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7036): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7036): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7036): [OR] == isSIMCardReady false ==
D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7036): [SCU] == networkStateCheck == true
I/SA      ( 7036): [DM] getCountryCodeFromCSC : PL
I/SA      ( 7036): isChinaCountryCode : false
,I/SA      ( 7036): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7036): [OR] == networkStateCheck true ==
,I/SA      ( 7036): [OR] GetMyCountryZoneTask
,I/SA      ( 7036): [OR] onReceive END
,I/SA      ( 7036): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7036): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7036): [SSP] query invoked
,D/accuweather( 7692): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7692): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7710): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7710): premStatus:2
,I/KnoxUsageLogPro( 7710): isEulaShown : false
I/KnoxUsageLogPro( 7710): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      ( 7036): [TPMU] GetMccFromDB : null
,I/SA      ( 7036): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7036): [TPM] isNoProxy(default) : true
,D/Headlines( 3498): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 3498): getCountryCode(): countryCode = PL
,D/Headlines( 3498): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 3498): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 3498): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 3498): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 3498): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 3498): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 3498): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 7036): fail readDirectory() errno=2
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7855): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7855): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7855): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  905): exchangeData() failure , invalid userId
,D/RCPManagerService(  905): exchangeData() failure , invalid userId
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7521): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7521): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7521): StateMachine : Current State = 1
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7521): StateMachine : Changed Current State = 1
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7503): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7503): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7503): exit::IDLE
D/InitializeManagerStateMachine( 7503): entry::NETWORK_CHECK
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7503): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7503): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7503): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7503): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7503): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7503): entry::SUCCESS
D/hcjo    ( 7503): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7503): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7503): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7503): exit::SUCCESS
D/InitializeManagerStateMachine( 7503): entry::IDLE
,I/PowerManagerService(  905): [PWL] Off : 15s ago
,I/SA      ( 7036): [RC New] Execute method=[GET] start
,E/SMD     (  295): DCD ON
,I/SA      ( 7036): [RC New] Security=[true]
,I/System.out( 7036): Thread-1110(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7036): Thread-1110(ApacheHTTPLog):isShipBuild true
,I/System.out( 7036): Thread-1110(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/SA      ( 7036): [RC New] [v2liruge] api execute + 658
,I/SA      ( 7036): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7036): AsyncTask #1 calls detatch()
,I/SA      ( 7036): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7036): [OCP] update openData : PL
,I/SA      ( 7036): [TPMU] getNetworkMcc : 
,I/SA      ( 7036): [SCU] saveMccToPreferece Start
,I/SA      ( 7036): [SCU] RegionMCC : 260
I/SA      ( 7036): [SSP] query invoked
,I/SA      ( 7036): [TPMU] GetMccFromDB : null
,I/SA      ( 7036): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7036): [SCU] saveMccToPreferece End
,I/SA      ( 7036): [RC New] executeRequest [v2liruge] end. 706
,I/SA      ( 7036): [RC New] Execute end
,I/SA      ( 7036): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7036): [OR] GetMyCountryZoneTask Success
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7160): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7160): BLE supported!!
I/jxcore-log( 7160): 
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/WifiStateMachine(  905): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  905): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  905): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  905): identical MTU - not setting
,D/ConnectivityService(  905): updateSourceRoutes : add source routing for type : 1
,E/WifiStateMachine(  905): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  905): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
,V/        (  288): QcRouteController
,D/SmartBondingService(  905): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  905): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  905): getSBEnabled() enabled =false
,D/SmartBondingService(  905): getSBEnabled() enabled =false
,D/SmartBondingService(  905): getSBEnabled() enabled =false
,V/        (  288): QcRouteController
,W/NetworkManagementService(  905): route cmd failed: 
W/NetworkManagementService(  905): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  905): '
W/NetworkManagementService(  905): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  905): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  905): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  905): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  905): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  905): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  905): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  905): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  905): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  905): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  905): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  905): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  905): calling update connectivity
,D/ConnectivityService(  905):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  905):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  905): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524295
,I/WifiStateMachine(  905): REQUEST_POWER_SAVE_ON
,D/ConnectivityService(  905):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  905): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2493): CM callback handler got msg 524295
,D/ConnectivityService(  905): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  905): calling update connectivity
,D/ConnectivityService(  905):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  905):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  905): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524295
,D/ConnectivityService(  905):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  905): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2493): CM callback handler got msg 524295
,E/WifiStateMachine(  905): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/PackageManager(  905): [MSG] MCS_UNBIND
,I/ActivityManager(  905): Killing 7178:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
,I/ActivityManager(  905): Killing 6077:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/dhcpcd  ( 7728): wlan0: sending IPv6 Router Solicitation
,W/libprocessgroup(  905): failed to open /acct/uid_10057/pid_7178/cgroup.procs: No such file or directory
,W/libprocessgroup(  905): failed to open /acct/uid_1000/pid_6077/cgroup.procs: No such file or directory
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  257): id=17 Removed Toast (8/9)
,I/SurfaceFlinger(  257): id=17 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/PowerManagerService(  905): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 905) eventTime = 118492
,D/PowerManagerService(  905): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=905 (0x0)
,D/PowerManagerService(  905): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=905, ws=WorkSource{10058}) (elapsedTime=3533)
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,E/SMD     (  295): DCD ON
,I/GAV4    ( 7770): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6999): mConnectivityHandler : connected
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6999): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6999): [GetString-S]
,I/ReactiveServiceManager( 6999): Supported : 1
,D/QSEECOMAPI: (  905): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: (  905): App is not loaded in QSEE
,D/QSEECOMAPI: (  905): Loaded image: APP id = 3
,D/QSEECOMAPI: (  905): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  905): QSEECom_shutdown_app, app_id = 3
E/terrier (  905): handleString: Failed to handle string(-4)
,E/terrier (  905): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 6999): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6999): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6999): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6999): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6999): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6999): [ensureRegistration] - No Samsung account
,D/SSRM:m  (  905): SIOP:: AP = 380, PST = 367, CUR = 450
,E/SMD     (  295): DCD ON
,I/dhcpcd  ( 7728): wlan0: sending IPv6 Router Solicitation
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...,
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7503): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7503): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7503): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7503): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7503): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7503): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7503): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7503): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 7503): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7503): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7503): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7503): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7503): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7503): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7503): entry::IDLE
,I/dhcpcd  ( 7728): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7728): wlan0: no IPv6 Routers available
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,V/AlarmManager(  905): waitForAlarm result :4
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  905): stay LED for fully charged
D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 6539): [1085] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6539): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,V/AlarmManager(  905): waitForAlarm result :4
,D/SSRM:m  (  905): SIOP:: AP = 330, PST = 356, CUR = 450
,I/PowerManagerService(  905): [PWL] Off : 30s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 4
,V/AlarmManager(  905): waitForAlarm result :8
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  905): SIOP:: AP = 310, PST = 347, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7982): MountEmulatedStorage()
,E/Zygote  ( 7982): v2
I/libpersona( 7982): KNOX_SDCARD checking this for 10037
I/libpersona( 7982): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.util.DlcRegiReceiver: pid=7982 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7982): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7982): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7982): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7982): TimaSignature is unavailable
,D/ActivityThread( 7982): Added TimaKeyStore provider
,D/ResourcesManager( 7982): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 7982): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7982): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7982): PushLog.txt file is not deleted.
,D/SPPClientService( 7982): PushLog.txt file is not deleted.
D/SPPClientService( 7982): ============PushLog. stop!
,I/ActivityManager(  905): Killing 7198:com.google.android.apps.docs/u0a97 (adj 15): bgCount ##41
,W/libprocessgroup(  905): failed to open /acct/uid_10097/pid_7198/cgroup.procs: No such file or directory
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 310, PST = 338, CUR = 450
,I/PowerManagerService(  905): [PWL] Off : 50s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,D/BatteryService(  905): stay LED for fully charged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  905): SIOP:: AP = 300, PST = 334, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 5
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 290, PST = 329, CUR = 450
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  905): [PWL] Off : 75s ago
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 290, PST = 325, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ClearcutLoggerApiImpl( 2244): disconnect managed GoogleApiClient
,D/SSRM:m  (  905): SIOP:: AP = 290, PST = 322, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 6
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 290, PST = 317, CUR = 450
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  905): [PWL] Off : 105s ago
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  905): SIOP:: AP = 290, PST = 308, CUR = 450
,E/SMD     (  295): DCD ON
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 290, PST = 299, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 7
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager(  905): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  905): stay LED for fully charged
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  905): [PWL] Off : 140s ago
,D/SSRM:m  (  905): SIOP:: AP = 270, PST = 291, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,D/BatteryService(  905): stay LED for fully charged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 270, PST = 287, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 8
,V/AlarmManager(  905): waitForAlarm result :8
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 270, PST = 284, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,D/BatteryService(  905): stay LED for fully charged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  905): SIOP:: AP = 270, PST = 282, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,D/BatteryService(  905): stay LED for fully charged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  905): [PWL] Off : 180s ago
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 279, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 9
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 276, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 273, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 270, CUR = 450
,D/TimaService(  905): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  905): TimaServiceHandler.handleMessage what =1
,D/TimaService(  905): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  905): initializing...
,I/TLC_TIMA_PKM_initialize(  905): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  905): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  905): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  905): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  905): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  905): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  905): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  905): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  905): App is not loaded in QSEE
,D/QSEECOMAPI: (  905): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  905): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  905): Trustlet response is completed
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  905): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  905): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  905): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  905): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 270, PST = 268, CUR = 450
,E/SMD     (  295): DCD ON
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  905): [PWL] Off : 225s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 265, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,V/AlarmManager(  905): waitForAlarm result :4
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  905): stay LED for fully charged
E/Zygote  ( 8029): MountEmulatedStorage()
,E/Zygote  ( 8029): v2
I/libpersona( 8029): KNOX_SDCARD checking this for 10080
I/libpersona( 8029): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8029 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
I/MotionRecognitionService(  905): setPowerConnected  = true
,I/SELinux ( 8029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8029): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8029): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 8029): TimaSignature is unavailable
,D/ActivityThread( 8029): Added TimaKeyStore provider
,D/ResourcesManager( 8029): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  905): Killing 7289:com.vlingo.midas/u0a32 (adj 15): bgCount ##41
,W/libprocessgroup(  905): failed to open /acct/uid_10032/pid_7289/cgroup.procs: No such file or directory
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 264, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 11
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 263, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 262, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 261, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 12
,I/PowerManagerService(  905): [PWL] Off : 275s ago
,V/AlarmManager(  905): waitForAlarm result :8
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 261, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 261, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 261, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 13
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 261, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  905): [PWL] Off : 330s ago
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 14
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 15
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/bootchecker(  325): bootchecker wake up!!
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,I/PowerManagerService(  905): [PWL] Off : 390s ago
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 16
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 17
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,D/BatteryService(  905): stay LED for fully charged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 18
,I/PowerManagerService(  905): [PWL] Off : 455s ago
,V/AlarmManager(  905): waitForAlarm result :8
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,I/Atfwd_Daemon(  332): Stop the daemon....
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 19
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/TimaService(  905): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  905): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  905): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  905): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  905): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  905): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  905): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  905): [PWL] Off : 525s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 21
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 22
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  905): [PWL] Off : 600s ago
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 23
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 24
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 25
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  905): [PWL] Off : 680s ago
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,V/AlarmManager(  905): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/LightsService(  905): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  905): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  905): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,E/SMD     (  295): DCD ON
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog(  905): !@Sync 26
,I/art     (  905): Explicit concurrent mark sweep GC freed 92289(7MB) AllocSpace objects, 207(3MB) LOS objects, 30% free, 35MB/51MB, paused 1.817ms total 129ms
,I/EventLogService( 2493): Aggregate from 1450737538563 (log), 1450737538563 (data)
,E/LightSensor(  905): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  905): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  905): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  905): unregisterListener ::   
,D/LightsService(  905): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/AlarmManager(  905): waitForAlarm result :8
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 27
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 28
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  905): [PWL] Off : 765s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 29
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  905): stay LED for fully charged
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/TimaService(  905): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  905): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  905): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  905): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  905): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  905): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  905): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  905): !@Sync 31
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,D/BatteryService(  905): stay LED for fully charged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  905): [PWL] Off : 855s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 32
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 33
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 34
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  295): DCD ON
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  905): [PWL] Off : 950s ago
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,D/BatteryService(  905): stay LED for fully charged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 35
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 36
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  905): stay LED for fully charged
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 37
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  905): [PWL] Off : 1050s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 38
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 39
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/TimaService(  905): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  905): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  905): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  905): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  905): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  905): Updating Usage Statistics in DB @ 1450740055777
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
,W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  905): ::getAppControlDB: Exception to create DB
W/System.err(  905): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  905): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsage(  905): Done Updating Usage Statistics in DB @ 1450740056025
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  905): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  905): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  905): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  905): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,D/BatteryService(  905): stay LED for fully charged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 41
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,I/PowerManagerService(  905): [PWL] Off : 1155s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 42
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 43
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,D/BatteryService(  905): stay LED for fully charged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 44
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,V/AlarmManager(  905): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  905): stay LED for fully charged
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  905): stay LED for fully charged
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 45
,I/PowerManagerService(  905): [PWL] Off : 1265s ago
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,V/AlarmManager(  905): waitForAlarm result :4
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 46
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,V/AlarmManager(  905): waitForAlarm result :8
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 47
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 48
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  905): [PWL] Off : 1380s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 49
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  905): stay LED for fully charged
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/TimaService(  905): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  905): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  905): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  905): !@Sync 50
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  905): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  905): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  905): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  905): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 51
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 52
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,E/SMD     (  295): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  905): [PWL] Off : 1500s ago
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 53
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 54
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 55
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 56
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 57
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  905): [PWL] Off : 1625s ago
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 58
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 59
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,D/BatteryService(  905): stay LED for fully charged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/NetworkStatsFactory(  905): UpdateStatsForKnox
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  905): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/TimaService(  905): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  905): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  905): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  905): !@Sync 60
,E/SMD     (  295): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  905): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  905): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  905): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  905): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,D/BatteryService(  905): stay LED for fully charged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,V/AlarmManager(  905): waitForAlarm result :8
,D/LightsService(  905): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  905): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  905): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,I/ProcessStatsService(  905): Prepared write state in 13ms
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,V/NetworkStats(  905): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  905): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  905): UpdateStatsForKnox
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  905): performPollLocked() took 7ms
,D/NtpTrustedTime(  905): currentTimeMillis() cache hit
,D/NtpTrustedTime(  905): currentTimeMillis() cache hit
,D/NtpTrustedTime(  905): currentTimeMillis() cache hit
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 2244): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2244): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  905): Pruning old procstats: /data/system/procstats/state-2015-12-21-01-32-32.bin
,E/LightSensor(  905): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  905): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  905): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  905): unregisterListener ::   
,D/LightsService(  905): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 61
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  905): [PWL] Off : 1755s ago
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  905): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true,
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 62
,E/SMD     (  295): DCD ON
,V/AlarmManager(  905): waitForAlarm result :8
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  905): !@Sync 63
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  905): Plugged
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/BatteryService(  905): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3832): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  295): DCD ON
D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  905): Plugged
I/MotionRecognitionService(  905): setPowerConnected  = true
D/BatteryService(  905): stay LED for fully charged
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3832): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3832): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRM:m  (  905): SIOP:: AP = 260, PST = 260, CUR = 450
E/SMD     (  295): DCD ON
D/AndroidRuntime( 8236): 
D/AndroidRuntime( 8236): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8236): CheckJNI is OFF
D/AndroidRuntime( 8236): setted country_code = Poland
D/AndroidRuntime( 8236): setted countryiso_code = PL
D/AndroidRuntime( 8236): setted sales_code = XEO
D/AndroidRuntime( 8236): readGMSProperty: start
D/AndroidRuntime( 8236): readGMSProperty: already setted!!
D/AndroidRuntime( 8236): readGMSProperty: end
D/AndroidRuntime( 8236): addProductProperty: start
E/AffinityControl( 8236): AffinityControl: registerfunction enter
D/AndroidRuntime( 8236): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  905): START PACKAGE DELETE: observer{533567196}
D/PackageManager(  905): pkg{<packageName>}
D/PackageManager(  905): user{0}
D/PackageManager(  905): caller{2000}
D/PackageManager(  905): flags{3}
D/PersonaManagerService(  905): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  905): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  905): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  905): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  905): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  905): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  905): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  905): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  905): getApplicationUninstallationEnabled
D/ApplicationPolicy(  905): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  905): !@killApplicatoin: 10356, uninstall pkg
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10356 user=-1: uninstall pkg
I/ActivityManager(  905): Killing 7160:com.test.thalitest/u0a356 (adj 0): stop com.test.thalitest
I/ActivityManager(  905): Killing 7873:com.android.email/u0a162 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 7855:com.samsung.android.sconnect/u0a137 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 7770:com.google.android.apps.magazines/u0a127 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 7731:com.android.chrome/u0a87 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 6472:com.sec.chaton/u0a85 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 7710:com.sec.knox.bridge/1000 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 7692:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 7036:com.osp.app.signin/u0a44 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 7014:com.policydm/1000 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 7675:com.sec.android.soagent/u0a36 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 7659:com.samsung.klmsagent/u0a18 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 7644:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 7625:com.sec.android.diagmonagent/1000 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 7607:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 5777:com.google.android.music:main/u0a125 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 6999:com.sec.pcw.device/1000 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 7896:com.sec.android.provider.badge/u0a77 (adj 15): empty for 1813s
I/ActivityManager(  905): Killing 7561:com.android.calendar/u0a149 (adj 15): empty for 1816s
I/ActivityManager(  905): Killing 7537:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): empty for 1816s
I/ActivityManager(  905): Killing 7479:com.samsung.android.provider.shootingmodeprovider/u0a169 (adj 15): empty for 1817s
I/ActivityManager(  905): Killing 7464:com.sec.kidsplat.installer/u0a165 (adj 15): empty for 1817s
I/ActivityManager(  905): Killing 7410:com.android.providers.calendar/u0a45 (adj 15): empty for 1817s
I/ActivityManager(  905): Killing 7427:com.samsung.helphub/1000 (adj 15): empty for 1818s
I/ActivityManager(  905): Killing 7396:com.samsung.android.magazine.service/u0a117 (adj 15): empty for 1818s
I/ActivityManager(  905): Killing 7378:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): empty for 1818s
I/ActivityManager(  905): Killing 7362:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1818s
I/ActivityManager(  905): Killing 7331:com.sec.android.provider.logsprovider/u0a19 (adj 15): empty for 1818s
I/ActivityManager(  905): Killing 7337:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty for 1818s
I/ActivityManager(  905): Killing 7260:com.sec.android.automotive.drivelink/u0a98 (adj 15): empty for 1818s
I/ActivityManager(  905):   Force finishing activity ActivityRecord{2803daae u0 com.test.thalitest/.MainActivity t4}
W/ActivityManager(  905): mDVFSHelper.acquire()
I/WindowState(  905): WIN DEATH: Window{2076480e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  905): Client connection lost with reason: 4
I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
W/PackageSettings(  905): Skipping PackageSetting{2c30c8c8 com.example.hello/10357} due to missing metadata
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/FocusedStackFrame(  905): Set to : 0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10356 user=0: pkg removed
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/art     ( 1583): Explicit concurrent mark sweep GC freed 20609(1304KB) AllocSpace objects, 1(39KB) LOS objects, 39% free, 16MB/27MB, paused 438us total 33.637ms
E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
I/art     ( 2493): Explicit concurrent mark sweep GC freed 5873(318KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 21MB/28MB, paused 591us total 60.472ms
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  905): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1873): mOCRHelper is null
I/art     ( 3331): Explicit concurrent mark sweep GC freed 33082(1798KB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 14MB/24MB, paused 545us total 67.284ms
W/BroadcastQueue(  905): Failure sending broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/BroadcastQueue(  905): android.os.DeadObjectException
W/BroadcastQueue(  905): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  905): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue(  905): 	at android.app.ApplicationThreadProxy.scheduleRegisteredReceiver(ApplicationThreadNative.java:1175)
W/BroadcastQueue(  905): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:480)
W/BroadcastQueue(  905): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:600)
W/BroadcastQueue(  905): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:652)
W/BroadcastQueue(  905): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:180)
W/BroadcastQueue(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  905): 	at android.os.Looper.loop(Looper.java:145)
W/BroadcastQueue(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue(  905): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
W/BroadcastQueue(  905): Exception when sending broadcast to ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.MainReciver}
W/BroadcastQueue(  905): android.os.DeadObjectException
W/BroadcastQueue(  905): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  905): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue(  905): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:924)
W/BroadcastQueue(  905): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:276)
W/BroadcastQueue(  905): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1124)
W/BroadcastQueue(  905): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:180)
W/BroadcastQueue(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  905): 	at android.os.Looper.loop(Looper.java:145)
W/BroadcastQueue(  905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue(  905): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8266): MountEmulatedStorage()
E/Zygote  ( 8266): v2
I/libpersona( 8266): KNOX_SDCARD checking this for 10018
I/libpersona( 8266): KNOX_SDCARD not a persona
I/ActivityManager(  905): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8266 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
I/DBG_DM  ( 4286): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
W/ActivityManager(  905): Spurious death for ProcessRecord{3b274eba 8266:com.samsung.klmsagent/u0a18}, curProc for 7659: null
I/DBG_DM  ( 4286): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 19
I/DBG_DM  ( 4286): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/DBG_DM  ( 4286): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 4286): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 19
I/DBG_DM  ( 4286): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/art     (  905): Explicit concurrent mark sweep GC freed 89304(9MB) AllocSpace objects, 355(5MB) LOS objects, 31% free, 35MB/51MB, paused 4.239ms total 139.421ms
D/ResourcesManager(  905): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  905): WaitForGcToComplete blocked for 30.393ms for cause Explicit
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/SELinux ( 8266): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8266): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8266): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
I/DBG_DM  ( 4286): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
W/GeofencerStateMachine( 2244): Ignoring removeGeofence because network location is disabled.
D/TimaKeyStoreProvider( 8266): TimaSignature is unavailable
D/ActivityThread( 8266): Added TimaKeyStore provider
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/DBG_DM  ( 4286): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/SecContentProvider2(  905): uri = 14 selection = getSealedState
D/SecContentProvider2(  905): mCursor = null
D/SecContentProvider2(  905): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  905): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  905): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/SurfaceWidgetView( 1494): destroyHardwareResources():509554449
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
V/WindowOrientationListener(  905): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  905): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  905): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  905): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  905): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/DBG_DM  ( 4286): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 19
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager( 8266): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/Launcher( 1494): onRestart, Launcher: 732916923
D/Launcher( 1494): onStart, Launcher: 732916923
D/Launcher.HomeView( 1494): onStart
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2094): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2094): [237392/6] SurfaceWidget drawing first frame
I/DBG_DM  ( 4286): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 4286): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 4286): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 4286): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
I/DBG_DM  ( 4286): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
I/SurfaceFlinger(  257): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/StatusBarManagerService(  905): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Books/Books.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ActivityManager(  905): post active user change for 0
D/KnoxTimeoutHandler(  905): postActiveUserChange for user 0
I/DBG_DM  ( 4286): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
D/StatusBarManagerService(  905): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/SecContentProvider2(  905): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  905): mCursor = null
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/RegisteredServicesCache( 1473): empty dynamic service
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/InputMethodManagerService(  905): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 7160 uid 10356
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
I/KLMS-2.4.503: ( 8266): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
E/ActivityThread( 4286): Performing stop of activity that is not resumed: {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
E/ActivityThread( 4286): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
E/ActivityThread( 4286): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3743)
E/ActivityThread( 4286): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3824)
E/ActivityThread( 4286): 	at android.app.ActivityThread.access$1200(ActivityThread.java:172)
E/ActivityThread( 4286): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1451)
E/ActivityThread( 4286): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4286): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 4286): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 4286): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 4286): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 4286): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 4286): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/KLMS-2.4.503: ( 8266): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450740772832
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/KLMS-2.4.503: ( 8266): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 8266): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/ActivityManager(  905): Activity reported stop, but no longer stopping: ActivityRecord{2bffb69 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t3}
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/Timeline( 4286): Timeline: Activity_idle id: android.os.BinderProxy@366d67cd time:1929039
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/Launcher.HomeView( 1494): onStop
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
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
W/ActivityManager(  905): mDVFSHelper.release()
I/Timeline(  905): Timeline: Activity_windows_visible id: ActivityRecord{5bea3ea u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1929090
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/EnterpriseDeviceManagerService(  905): Package has changed for user 0
D/EnterpriseDeviceManagerService(  905): Admin package name: com.google.android.gms
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/RCPManagerService(  905): PackageReceiver onReceive()
I/HarmonyEASService(  905): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/KnoxMUMContainerPolicy(  905): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  905): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  905): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  905): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  905): uID is 10356
V/EnterpriseBillingPolicy(  905): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  905): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  905): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  905): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  905): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  905): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  905): getBillingProfileForVpnEngine - end - null
D/KnoxTimeoutHandler(  905): handleActiveUserChange for user 0
W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TaskPersister(  905): removeObsoleteFile: deleting file=4_task.xml
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/TaskPersister(  905): removeObsoleteFile: deleting file=3_task.xml
W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 8286): MountEmulatedStorage()
E/Zygote  ( 8286): v2
I/libpersona( 8286): KNOX_SDCARD checking this for 10103
I/libpersona( 8286): KNOX_SDCARD not a persona
I/SELinux ( 8286): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8286): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8286): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  905): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8286 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  905): Killing 7521:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1813s
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
D/TimaKeyStoreProvider( 8286): TimaSignature is unavailable
D/ActivityThread( 8286): Added TimaKeyStore provider
W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/art     (  905): Explicit concurrent mark sweep GC freed 19291(975KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 35MB/51MB, paused 6.258ms total 332.058ms
D/ResourcesManager( 8286): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/elm:14451( 8286): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8286): ELMEngine.ELMEngine( context ).
D/elm:14451( 8286): MDMBridge.setEnterpriseBridge()
D/elm:14451( 8286): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
D/elm:14451( 8286): ElmAgentService : onCreate()
D/elm:14451( 8286): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8286): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8286): MDMBridge.getInstance()
D/elm:14451( 8286): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14451( 8286): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 8302): MountEmulatedStorage()
I/libpersona( 8302): KNOX_SDCARD checking this for 10016
E/Zygote  ( 8302): v2
I/libpersona( 8302): KNOX_SDCARD not a persona
W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager(  905): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8302 uid=10016 gids={50016, 9997} abi=armeabi-v7a
W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/PackageManager(  905): delete codoeFile: 
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/PackageManager(  905): result of delete: 1{533567196}
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}

```
