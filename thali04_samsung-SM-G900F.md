#### Test 573480789efee08_thali04_samsung-SM-G900F Logs


```
--------- beginning of system
W/libprocessgroup(  901): failed to open /acct/uid_10116/pid_5898/cgroup.procs: No such file or directory
--------- beginning of main
D/MyFiles ( 7086): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager(  901): Killing 6297:com.samsung.android.app.FileShareServer/u0a74 (adj 15): bgCount ##41
I/TactileAssist(  901): enable value -1
I/TactileAssist(  901): internal enable value -1
I/TactileAssist(  901): intensity value -1
I/TactileAssist(  901): saveAppList value true
I/TactileAssist(  901): List of disabled apps :
E/installd(  301): system dir 0 : /system/app/
E/installd(  301): system dir 1 : /system/priv-app/
E/installd(  301): system dir 2 : /vendor/app/
E/installd(  301): system dir 3 : /oem/app/
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7108): MountEmulatedStorage()
E/Zygote  ( 7108): v2
I/libpersona( 7108): KNOX_SDCARD checking this for 10057
I/libpersona( 7108): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7108 uid=10057 gids={50057, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 7108): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7108): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/PackageManager(  901): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/SELinux ( 7108): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  901): failed to open /acct/uid_10074/pid_6297/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 7108): TimaSignature is unavailable
D/ActivityThread( 7108): Added TimaKeyStore provider
D/ResourcesManager( 7108): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/ResourcesManager( 7108): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 7108): onReceive() it will make start service
D/Compatibility( 7108): onHandleIntent()
D/Compatibility( 7108): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10191, android.intent.extra.user_handle=0}]
D/Compatibility( 7108): found: 2
D/Compatibility( 7108): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7108): skipping ResolveInfo{3760788c com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7108): considering ResolveInfo{1162bd5 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7108): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7108): enabling receiver ResolveInfo{3389bfea com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7108): enabling receiver ResolveInfo{31c32db com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7108): enabling receiver ResolveInfo{1ae29178 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7108): enabling receiver ResolveInfo{359ab051 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7108): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
I/UpdateIcingCorporaServi( 1567): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/Zygote  ( 7130): MountEmulatedStorage()
E/Zygote  ( 7130): v2
I/libpersona( 7130): KNOX_SDCARD checking this for 1000
I/libpersona( 7130): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7130 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7130): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7130): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7130): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7130): TimaSignature is unavailable
D/ActivityThread( 7130): Added TimaKeyStore provider
D/ResourcesManager( 7130): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
W/ContextImpl( 7130): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
E/SMD     (  290): DCD ON
D/ResourcesManager( 1567): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
I/UpdateIcingCorporaServi( 1567): UpdateCorporaTask done [took 113 ms] updated apps [took 113 ms] 
E/Zygote  ( 7155): MountEmulatedStorage()
I/libpersona( 7155): KNOX_SDCARD checking this for 10097
E/Zygote  ( 7155): v2
I/libpersona( 7155): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7155 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7127): 
D/AndroidRuntime( 7127): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7127): CheckJNI is OFF
I/SELinux ( 7155): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/AndroidRuntime( 7127): setted country_code = Poland
D/AndroidRuntime( 7127): setted countryiso_code = PL
D/AndroidRuntime( 7127): setted sales_code = XEO
D/AndroidRuntime( 7127): readGMSProperty: start
D/AndroidRuntime( 7127): readGMSProperty: already setted!!
I/SELinux ( 7155): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/AndroidRuntime( 7127): readGMSProperty: end
D/AndroidRuntime( 7127): addProductProperty: start
E/SELinux ( 7155): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager(  901): Killing 6318:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
D/TimaKeyStoreProvider( 7155): TimaSignature is unavailable
D/ActivityThread( 7155): Added TimaKeyStore provider
D/ResourcesManager( 7155): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/libprocessgroup(  901): failed to open /acct/uid_1000/pid_6318/cgroup.procs: No such file or directory
E/Watchdog(  901): !@Sync 3
E/AffinityControl( 7127): AffinityControl: registerfunction enter
D/DocsApplication( 7155): Installing DEX configuration.
D/AndroidRuntime( 7127): Calling main entry com.android.commands.am.Am
D/DexInstaller( 7155): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
E/PersonaManagerService(  901): inState():  stateMachine is null !!
V/ApplicationPolicy(  901): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  901): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  901): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/PackageInfoHelper( 7155): Provided clientMode=RELEASE, packageInfo=PackageInfo{295bb9bf com.google.android.apps.docs}
D/CustomFrequencyManagerService(  901): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 901  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  901): mDVFSHelper.acquire()
D/TAG     ( 7155): onCreate()
D/CrossAppStateProvider( 7155): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
I/DBG_DM  ( 3691): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
I/SQLiteSecureOpenHelper( 3469): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3469): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
I/DBG_DM  ( 3691): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 45
D/AndroidRuntime( 7127): Shutting down VM
I/DBG_DM  ( 3691): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
I/DBG_DM  ( 3691): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
I/DBG_DM  ( 3691): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3691): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
I/DBG_DM  ( 3691): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
I/DBG_DM  ( 3691): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/DBG_DM  ( 3691): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 3691): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/LightsService(  901): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 901) 
D/LightsService(  901): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  901): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  901): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/PhoneStatusBar( 1191): Icon Only
D/SecContentProvider2(  901): uri = 14 selection = getSealedState
D/SecContentProvider2(  901): mCursor = null
D/SecContentProvider2(  901): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  901): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  901): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager(  901): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 3691): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
I/DBG_DM  ( 3691): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 3691): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 3691): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7182): MountEmulatedStorage()
I/libpersona( 7182): KNOX_SDCARD checking this for 10191
E/Zygote  ( 7182): v2
I/libpersona( 7182): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7182 uid=10191 gids={50191, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PowerManagerService(  901): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  901): getFinalBrightness : 1 -> 1
D/PowerManagerService(  901): [s] DisplayPowerCallbacks : onStateChanged()
I/art     ( 1191): Explicit concurrent mark sweep GC freed 54362(2MB) AllocSpace objects, 3(236KB) LOS objects, 30% free, 36MB/52MB, paused 499us total 82.104ms
I/SELinux ( 7182): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7182): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7182): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/PanelView( 1191): There is/are notification(s) 
D/PanelView( 1191): There is/are notification(s) 
V/BitmapFactory( 1191): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
D/lights  (  901): lcd : 1 +
D/DisplayPowerController(  901): getFinalBrightness : 1 -> 1
D/lights  (  901): lcd : 1 -
D/DisplayPowerController(  901): getFinalBrightness : 1 -> 1
D/TimaKeyStoreProvider( 7182): TimaSignature is unavailable
D/ActivityThread( 7182): Added TimaKeyStore provider
V/ActivityManager(  901): Display changed displayId=0
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,V/BitmapFactory( 1191): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/KnoxNotification( 1191): ----- inflateViews : modified publicViewLocal -----
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/ResourcesManager( 7182): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/KnoxNotification( 1191): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1191): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1191): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@3428c9d7
D/SecContentProvider2(  901): uri = 14 selection = getSealedState
D/SecContentProvider2(  901): mCursor = null
,D/SecContentProvider2(  901): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1191): Icon Only
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/PanelView( 1191): There is/are notification(s) 
D/PanelView( 1191): There is/are notification(s) 
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,I/WebViewFactory( 7182): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7182): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,I/LibraryLoader( 7182): Loading: webviewchromium
,I/LibraryLoader( 7182): Time to load native libraries: 2 ms (timestamps 4082-4084)
,I/LibraryLoader( 7182): Expected native library version number "",actual native library version number ""
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
V/WebViewChromiumFactoryProvider( 7182): Binding Chromium to main looper Looper (main, tid 1) {1ae29178}
I/LibraryLoader( 7182): Expected native library version number "",actual native library version number ""
I/chromium( 7182): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7182): Initializing chromium process, renderers=0
W/art     ( 7182): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,W/chromium( 7182): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7182): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7182): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,I/Adreno-EGL( 7182): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7182): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7182): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7182): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7182): Remote Branch: 
I/Adreno-EGL( 7182): Local Patches: 
I/Adreno-EGL( 7182): Reconstruct Branch: 
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,W/chromium( 7182): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7182): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,W/art     ( 7182): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7182): onDetachedFromWindow called when already detached. Ignoring
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/SystemWebViewEngine( 7182): CordovaWebView is running on device made by: samsung
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,W/art     ( 7182): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7182): Attempt to remove local handle scope entry from IRT, ignoring
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/Activity( 7182): performCreate Call secproduct feature valuefalse
D/Activity( 7182): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/OpenGLRenderer( 7182): Render dirty regions requested: true
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/ActivityManager(  901): post active user change for 0
D/KnoxTimeoutHandler(  901): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  901): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,I/SurfaceFlinger(  257): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
I/OpenGLRenderer( 7182): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7182): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7182): Enabling debug mode 0
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,I/WifiStateMachine(  901): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  901): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  901): CMD_RSSI_POLL : out!
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/InputMethodManagerService(  901): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,I/ActivityManager(  901): Displayed com.test.thalitest/.MainActivity: +793ms
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,I/Timeline( 7182): Timeline: Activity_idle id: android.os.BinderProxy@114b88cb time:104600
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/9)
D/JsMessageQueue( 7182): Set native->JS mode to OnlineEventsBridgeMode
,I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
,D/CustomFrequencyManagerService(  901): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 901  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  901): mDVFSHelper.release()
I/Timeline(  901): Timeline: Activity_windows_visible id: ActivityRecord{8d4d568 u0 com.test.thalitest/.MainActivity t10} time:104669
,D/CustomFrequencyManagerService(  901): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 901  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/jxcore_app_log( 7182): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361755904
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,I/SurfaceFlinger(  257): id=15 Removed Starting com.test.thalitest (6/8)
I/SurfaceFlinger(  257): id=15 Removed Starting com.test.thalitest (-2/8)
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/GAV2    ( 7155): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Zygote  ( 7240): MountEmulatedStorage()
,E/Zygote  ( 7240): v2
I/libpersona( 7240): KNOX_SDCARD checking this for 10098
I/libpersona( 7240): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7240 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,I/chromium( 7182): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/SELinux ( 7240): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7240): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7240): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7240): TimaSignature is unavailable
,D/ActivityThread( 7240): Added TimaKeyStore provider
E/Adreno-ES20( 7182): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7182): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/chromium( 7182): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7182): 
,D/ResourcesManager( 7240): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,V/AlarmManager(  901): waitForAlarm result :4
,D/CustomFrequencyManagerService(  901): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 901  tag : ACTIVITY_RESUME_BOOSTER@10
,W/ResourcesManager( 7240): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4305, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3217): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3217): Disconnected process message: 10
,E/[CarMode]( 7240): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 7240): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 7240): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,W/GAV2    ( 7155): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager(  901): Killing 6355:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7275): MountEmulatedStorage()
E/Zygote  ( 7275): v2
I/libpersona( 7275): KNOX_SDCARD checking this for 10032
I/libpersona( 7275): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7275 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 7275): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7275): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/libprocessgroup(  901): failed to open /acct/uid_1000/pid_6355/cgroup.procs: No such file or directory
E/SELinux ( 7275): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7275): TimaSignature is unavailable
D/ActivityThread( 7275): Added TimaKeyStore provider
D/ResourcesManager( 7275): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/ResourcesManager( 7275): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/System.out( 7275): Inside onCreate() of WakeupTriggerProvide
I/System.out( 7275): Inside WakeupProvider
E/DatabaseUtils( 7275): Writing exception to parcel
E/DatabaseUtils( 7275): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7275): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7275): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7275): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7275): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7275): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7275): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7275): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7275): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7275): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7275): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7240): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
I/VlingoApplication( 7275): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
W/System.err( 7240): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7240): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7240): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7240): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7240): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7240): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7240): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7240): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7240): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7240): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7240): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7240): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7240): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7240): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7240): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7240): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7240): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7240): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7240): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7240): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7240): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7240): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7240): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7240): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7240): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7240): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7240): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7240): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7240): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7240): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7240): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/DatabaseUtils( 7275): Writing exception to parcel
E/DatabaseUtils( 7275): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7275): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7275): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7275): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7275): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7275): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7275): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7275): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7275): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7275): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7275): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7240): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 7240): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7240): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7240): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7240): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7240): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7240): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7240): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7240): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7240): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7240): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7240): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7240): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7240): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7240): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7240): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 7240): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7240): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7240): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7240): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7240): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7240): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7240): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7240): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7240): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7240): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7240): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7240): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7240): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/VlingoAndroidCore( 7275): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
E/[CarMode]( 7240): [DLApplication]-Init Called!:false
E/[CarMode]( 7240): [DLApplication]-Init Started!:true
I/[CarModeFW]( 7240): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7240): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7240): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7240): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7240): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7240): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7240): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7240): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7240): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7240): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7240): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7240): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7240): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7240): ### com.android.internal.os.ZygoteInit::main(1194)
I/MessageDataHandler( 7240): initialize
D/[CarModeFW]( 7240): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 7240): CDH-initiazlieCaches : after sync
D/[CarModeFW]( 7240): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7240): CDH-ContactDataHandler initiazlieCaches time : 41
D/[CarModeFW]( 7240): CDH-initiazlieCaches : end sync
D/[CarModeFW]( 7240): DrivingManager-initialize...
I/SensorService(  901): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  901): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  901): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
D/VlingoApplication( 7275): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 7275): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
I/MediaPlayer( 7240): Need to enable context aware info
V/MediaPlayer-JNI( 7240): native_setup
V/MediaPlayer( 7240): constructor
V/MediaPlayer( 7240): setListener
E/MediaPlayer-JNI( 7240): QCMediaPlayer mediaplayer NOT present
D/[CarModeFW]( 7240): PushMessageManager-bindPushMessageService
I/[CarModeFW]( 7240): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode]( 7240): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarModeFW]( 7240): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1453981668663
D/[CarModeFW]( 7240): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1453981668665
D/[CarModeFW]( 7240): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1453981668666
D/[CarModeFW]( 7240): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7240): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1453981668669
D/[CarModeFW]( 7240): RecommendHandler-selection = type = '3'
D/[CarModeFW]( 7240): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1453981668678
D/[CarMode]( 7240): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 7240): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1453981668680
D/TP/SmsProvider( 1471): query,matched:2, calling pid = 7240
D/TP/SmsProvider( 1471): query,matched:2, calling pid = 7240
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 1471): match 2:Elapsed time : 1.987 ms
D/TP/SmsProvider( 1471): match 2:Elapsed time : 4.691 ms
E/Zygote  ( 7308): MountEmulatedStorage()
E/Zygote  ( 7308): v2
I/libpersona( 7308): KNOX_SDCARD checking this for 10019
I/libpersona( 7308): KNOX_SDCARD not a persona
I/[CarMode]( 7240): [LogNotNull]-Package name is: com.google.android.apps.maps
I/ActivityManager(  901): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7308 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
I/SELinux ( 7308): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7308): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7308): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
E/[CarMode]( 7240): [DLApplication]-Init End!:true
D/[CarModeFW]( 7240): CDH-buildContactCacheWireFrame : cur len =0
D/TimaKeyStoreProvider( 7308): TimaSignature is unavailable
D/ActivityThread( 7308): Added TimaKeyStore provider
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/[CarMode]( 7240): [DLApplication]-GooglePlayServices SUCCESS.
E/Zygote  ( 7323): MountEmulatedStorage()
E/Zygote  ( 7323): v2
I/libpersona( 7323): KNOX_SDCARD checking this for 10003
I/libpersona( 7323): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7323 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/MessageDataHandler( 7240):  getInboxList smsCursor : 132
I/SELinux ( 7323): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7323): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7323): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TP/MmsProvider( 1471): Query uri=content://mms, match=0, calling pid = 7240
D/TP/MmsProvider( 1471): Query uri=content://mms/inbox, match=2, calling pid = 7240
E/[CarMode]( 7240): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
D/[CarModeFW]( 7240): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7240): RecommendHandler-selection = type = '3'
I/MessageDataHandler( 7240): getUnreadMessageCount :0
D/[CarModeFW]( 7240): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 154
I/UpdateManagerReceiver( 7240): Intent : android.intent.action.PACKAGE_ADDEDThu Jan 28 12:47:48 GMT+01:00 2016
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 7323): TimaSignature is unavailable
D/ActivityThread( 7323): Added TimaKeyStore provider
E/Zygote  ( 7338): MountEmulatedStorage()
E/Zygote  ( 7338): v2
I/libpersona( 7338): KNOX_SDCARD checking this for 1000
I/libpersona( 7338): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7338 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/art     (  319): Explicit concurrent mark sweep GC freed 8754(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 295us total 11.515ms
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 9.151ms
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.998ms
I/SELinux ( 7338): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7338): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7338): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  901): Killing 5504:com.sec.android.app.samsungapps/u0a39 (adj 15): bgCount ##41
D/MessageDataHandler( 7240):  getInboxList mmsCursor : 106
D/MessageDataHandler( 7240):  getInboxList mms,sms cursor join : 9
D/TP/MmsSmsProvider( 1471): query,matched:0, calling pid = 7240
V/TP/MmsSmsProvider( 1471): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1471): match 0:Elapsed time : 3.975 ms
D/TP/MmsSmsProvider( 1471): query,matched:13, calling pid = 7240
D/TP/MmsSmsProvider( 1471): match 13:Elapsed time : 1.432 ms
D/MessageDataHandler( 7240):  getInboxList address cursor : 5
D/TP/MmsSmsProvider( 1471): query,matched:0, calling pid = 7240
V/TP/MmsSmsProvider( 1471): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1471): match 0:Elapsed time : 1.890 ms
D/ResourcesManager( 7323): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
D/TimaKeyStoreProvider( 7338): TimaSignature is unavailable
D/ActivityThread( 7338): Added TimaKeyStore provider
D/MessageDataHandler( 7240):  getInboxList thread cursor : 10
D/[CarModeFW]( 7240): PushMessageService-onCreate
D/MessageDataHandler( 7240):  thread, addr result: 16
I/[CarModeFW]( 7240): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 292
I/[CarModeFW]( 7240): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7240): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 293
D/ResourcesManager( 7308): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
I/ActivityManager(  901): Killing 6070:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
I/ActivityManager(  901): Killing 5699:com.google.android.gm/u0a113 (adj 15): bgCount ##42
I/ActivityManager(  901): Killing 5865:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##43
D/ResourcesManager( 7338): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
W/libprocessgroup(  901): failed to open /acct/uid_10039/pid_5504/cgroup.procs: No such file or directory
D/[CarModeFW]( 7240): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7240): PushMessageService-registerPushMessageServiceListener
W/ContextImpl( 7338): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7354): MountEmulatedStorage()
I/libpersona( 7354): KNOX_SDCARD checking this for 10111
E/Zygote  ( 7354): v2
I/libpersona( 7354): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7354 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 7354): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ResourcesManager( 7338): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SELinux ( 7354): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7354): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/UserAnalysis.PlaceProvider( 7323): PlaceProvider onCreate()
D/TimaKeyStoreProvider( 7354): TimaSignature is unavailable
D/ActivityThread( 7354): Added TimaKeyStore provider
D/ResourcesManager( 7354): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
D/PackageIntentReceiver( 7354): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7354): Not GearManger package! 
D/UserAnalysis.SecureDbManager( 7323): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 7323): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7323): Create SecureDbHelper
E/FilterInstaller( 7338): There is no requred permission
W/libprocessgroup(  901): failed to open /acct/uid_10004/pid_6070/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_10113/pid_5699/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_10167/pid_5865/cgroup.procs: No such file or directory
I/art     (  901): Explicit concurrent mark sweep GC freed 241442(16MB) AllocSpace objects, 3(5MB) LOS objects, 30% free, 36MB/52MB, paused 1.474ms total 105.130ms
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7369): MountEmulatedStorage()
I/libpersona( 7369): KNOX_SDCARD checking this for 10117
E/Zygote  ( 7369): v2
I/libpersona( 7369): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7369 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/IntelligenceServiceApplication( 7323): onCreate()
I/ActivityManager(  901): Killing 6139:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
I/SELinux ( 7369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  901): Killing 6041:com.google.android.music:main/u0a125 (adj 15): bgCount ##41
E/SELinux ( 7369): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/SMD     (  290): DCD ON
I/SQLiteSecureOpenHelper( 7323): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7323): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7323): Open Place.db in secure mode
D/TimaKeyStoreProvider( 7369): TimaSignature is unavailable
D/ActivityThread( 7369): Added TimaKeyStore provider
I/SQLiteSecureOpenHelper( 7323): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7323): ...getDatabaseLocked(b,b,pwd)
D/ResourcesManager( 7369): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
D/[CarModeFW]( 7240): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 7240): MyPlaceProvider-=============
D/[CarModeFW]( 7240): MyPlaceProvider-=============
D/[CarModeFW]( 7240): MyPlaceProvider-=============
D/[CarModeFW]( 7240): MyPlaceProvider-=============
D/[CarModeFW]( 7240): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7240): MyPlaceProvider-==============
D/[CarModeFW]( 7240): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7240): MyPlaceProvider-==============
D/[CarModeFW]( 7240): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7240): MyPlaceProvider-==============
D/[CarModeFW]( 7240): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7240): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 640
D/[CarMode]( 7240): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@1c8f9947, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@ef552931] LOCATIONS
W/ResourcesManager( 7369): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/[CarModeFW]( 7240): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 681
I/[CarModeFW]( 7240): -[snowdeer] Rec : Missed Call : 677
W/libprocessgroup(  901): failed to open /acct/uid_10043/pid_6139/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_10125/pid_6041/cgroup.procs: No such file or directory
I/[CarModeFW]( 7240): -[snowdeer] Rec : Favorite : 11
I/[CarModeFW]( 7240): -[snowdeer] Rec : CallLog : 6
D/MagazineService Version( 7369): Magazine-Administrator: 11
D/MagazineService Version( 7369): Magazine-Provider: 14
D/MagazineService Version( 7369): Magazine-Channel: 14
D/HeadlinesChannelApplication( 7369): [onCreate]
I/[CarModeFW]( 7240): -[snowdeer] Rec : Schedule : 15
I/[CarModeFW]( 7240): -[snowdeer] Rec : During DL app : 2
D/MagazineService::MagazineBroadcastReceiver( 7369): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
I/[CarModeFW]( 7240): -[snowdeer] Rec : Location Sharing : 4
I/[CarModeFW]( 7240): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 7240): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7240): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7240): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 7240): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 7240): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 724
I/[CarModeFW]( 7240): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7240): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7240): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7240): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 722
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7388): MountEmulatedStorage()
E/Zygote  ( 7388): v2
I/libpersona( 7388): KNOX_SDCARD checking this for 1000
I/libpersona( 7388): KNOX_SDCARD not a persona
I/MagazineService::MagazineService( 7369): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/ActivityManager(  901): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7388 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7388): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/MagazineService::MagazineService( 7369): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/SELinux ( 7388): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  901): Killing 5440:com.google.android.apps.plus/u0a134 (adj 15): bgCount ##41
E/SELinux ( 7388): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7388): TimaSignature is unavailable
D/ActivityThread( 7388): Added TimaKeyStore provider
D/ResourcesManager( 7388): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/libprocessgroup(  901): failed to open /acct/uid_10134/pid_5440/cgroup.procs: No such file or directory
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7403): MountEmulatedStorage()
E/Zygote  ( 7403): v2
I/libpersona( 7403): KNOX_SDCARD checking this for 1000
I/libpersona( 7403): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7403 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  901): Killing 6587:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
I/SELinux ( 7403): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7403): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7403): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7403): TimaSignature is unavailable
D/ActivityThread( 7403): Added TimaKeyStore provider
W/libprocessgroup(  901): failed to open /acct/uid_10011/pid_6587/cgroup.procs: No such file or directory
D/ResourcesManager( 7403): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
D/AcmsPackageEventListener( 7403): Received: android.intent.action.PACKAGE_ADDED
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
I/System.out( 7275): INFO:Resource not found:/Common.properties Using default values
W/ContextImpl( 7403): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
E/Zygote  ( 7420): MountEmulatedStorage()
E/Zygote  ( 7420): v2
I/libpersona( 7420): KNOX_SDCARD checking this for 10134
I/libpersona( 7420): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7420 uid=10134 gids={50134, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  901): Killing 6374:com.android.vending/u0a29 (adj 15): bgCount ##41
I/SELinux ( 7420): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7420): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7420): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/AcmsService( 7403): Enter Oncreate
D/AcmsServiceMonitor( 7403): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 7403): creating AcmsCore
D/AcmsCore( 7403): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7403): AcmsCore
D/AcmsCore( 7403): init
D/AcmsCore( 7403): Looper handler is not null
D/AcmsCore( 7403): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7403): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7403): Incrementing - Counter value: 1
D/AcmsCore( 7403): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 7403): onStartCommand
D/AcmsService( 7403): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 7403): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7403): Incrementing - Counter value: 2
D/AcmsService( 7403): Incremented Counter Value : onStartCommand
D/ActivityThread( 7403): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/AcmsCertificateMngr( 7403): AcmsCertificateMngr
D/AcmsRevocationMngr( 7403): AcmsRevocationMngr
D/TimaKeyStoreProvider( 7420): TimaSignature is unavailable
D/ActivityThread( 7420): Added TimaKeyStore provider
,D/ResourcesManager( 7420): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager( 7420): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsService( 7403): Inside handle Intent
D/AcmsService( 7403): App added - package name: com.test.thalitest
D/AcmsCore( 7403): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7403): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7403): Incrementing - Counter value: 3
D/AcmsCore( 7403): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7403): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7403): Decrementing - Counter value: 2
,W/libprocessgroup(  901): failed to open /acct/uid_10029/pid_6374/cgroup.procs: No such file or directory
,W/jxcore-log( 7182): Initializing JXcore engine
W/jxcore-log( 7182): JXcore engine is ready
,E/auditd  ( 2135): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  901): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  901): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,W/jxcore-log( 7182): Starting JXcore engine
,W/jxcore-log( 7182): Platform android
W/jxcore-log( 7182): 
W/jxcore-log( 7182): Process ARCH arm
W/jxcore-log( 7182): 
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TaskPersister(  901): removeObsoleteFile: deleting file=9_task_thumbnail.png
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,V/BitmapFactory( 1191): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_inout.png
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7450): MountEmulatedStorage()
I/libpersona( 7450): KNOX_SDCARD checking this for 10165
E/Zygote  ( 7450): v2
I/libpersona( 7450): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7450 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7450): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7450): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7450): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 2200): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2200): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 7450): TimaSignature is unavailable
,D/ActivityThread( 7450): Added TimaKeyStore provider
,D/ResourcesManager( 7450): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7450): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 7450): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7469): MountEmulatedStorage()
E/Zygote  ( 7469): v2
I/libpersona( 7469): KNOX_SDCARD checking this for 10169
I/libpersona( 7469): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7469 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
,I/WifiStateMachine(  901): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  901): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  901): CMD_RSSI_POLL : out!
,I/SELinux ( 7469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7469): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/jxcore-log( 7182): JXcore Cordova bridge is ready!
I/jxcore-log( 7182): 
,W/jxcore-log( 7182): JXcore engine is started
,D/TimaKeyStoreProvider( 7469): TimaSignature is unavailable
,D/ActivityThread( 7469): Added TimaKeyStore provider
,D/ResourcesManager( 7469): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 7469): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7485): MountEmulatedStorage()
E/Zygote  ( 7485): v2
I/libpersona( 7485): KNOX_SDCARD checking this for 10029
I/libpersona( 7485): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7485 uid=10029 gids={50029, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 6699:com.sec.android.fotaclient/u0a10 (adj 15): bgCount ##41
,I/jxcore-log( 7182): Toggling radios to true
I/jxcore-log( 7182): 
,D/BluetoothAdapter( 7182): enable()
,I/SELinux ( 7485): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/BluetoothAdapter( 7182): enable(): BT is already enabled..!
,I/SELinux ( 7485): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7485): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/WifiService(  901): New client listening to asynchronous messages
,I/WifiManager( 7182): packageName : com.test.thalitest
,D/SecContentProvider(  901): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  901): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  901): mCursor = null
,D/WifiService(  901): setWifiEnabled: true pid=7182, uid=10191
E/WifiService(  901): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  901): Permission Denial: getCurrentUser() from pid=7182, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  901): Failed getting userId using ActivityManagerNative
W/WifiService(  901): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7182, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  901): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  901): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  901): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  901): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  901): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  901): name = wifi_on
,I/WifiService(  901): disconnect: pid=7182, uid=10191
,I/wpa_supplicant( 1274): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7182): Radios toggled
I/jxcore-log( 7182): 
I/jxcore-log( 7182): My device name is: samsung-SM-G900F
I/jxcore-log( 7182): 
,D/TimaKeyStoreProvider( 7485): TimaSignature is unavailable
,D/ActivityThread( 7485): Added TimaKeyStore provider
,I/wpa_supplicant( 1274): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1274): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1274): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  901): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1274): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1274): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1274): Disconnected - do not scan
I/wpa_supplicant( 1274): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/WifiStateMachine(  901): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  901): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  901): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ResourcesManager( 7485): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,E/WifiStateMachine(  901): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  901): InactiveState{ what=143375 }
,D/CommandListener(  284): Clearing all IP addresses on wlan0
,D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/libprocessgroup(  901): failed to open /acct/uid_10010/pid_6699/cgroup.procs: No such file or directory
,V/NativeCrypto( 2200): Read error: ssl=0x9b229e00: I/O error during system call, Connection timed out
,E/WifiStateMachine(  901): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): ignoring duplicate network state non-change
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,V/NativeCrypto( 2200): SSL shutdown failed: ssl=0x9b229e00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  901): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1274): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1274): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1274): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1274): First Scan Start
,I/wpa_supplicant( 1274): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  901): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  901): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  901): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/WifiP2pService(  901): InactiveState{ what=143375 }
D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Validated
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CommandListener(  284): Clearing all IP addresses on wlan0
,D/ConnectivityService(  901): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  901): Not allowed due to - mEnabled false
,D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  901): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  901): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine(  901): updateConfiguredNetworkExpiration - currTime: 1453981670738
D/WifiStateMachine(  901): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  901): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 1191): CM callback handler got msg 524292
I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
,D/ConnectivityService(  901): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
D/Nat464Xlat(  901): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Disconnected - quitting
,D/ConnectivityService(  901): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  901): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,D/TelephonyNetworkFactory( 1471): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  901): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/CSLegacyTypeTracker(  901): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  901): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine(  901): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  901): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  901): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  901): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  901): setDetailed state send new extra info"NG700"
,D/ConnectivityManager.CallbackHandler( 2484): CM callback handler got msg 524292
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  901): mCursor = null
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  901): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
,D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,V/NetworkStats(  901): updateIfacesLocked()
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
V/NetworkStats(  901): performPollLocked(flags=0x1)
,E/ConnectivityService(  901): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/StatusBar.NetworkController( 1191): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1191): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1191): updateDataNetType()
D/StatusBar.NetworkController( 1191): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1191): updateLTEICONDataNetType:0
,D/NetworkStatsFactory(  901): UpdateStatsForKnox
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
V/NetworkStats(  901): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,V/NetworkStats(  901): performPollLocked() took 8ms
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1191): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/Finsky  ( 7485): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7485): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7485): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7485): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7485): Skipping gmscore version check
,D/Finsky  ( 7485): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7485): [1] Libraries$2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 2484): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/Finsky  ( 7485): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/ChimeraCfgMgr( 2484): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2484): Loading module APK com.google.android.play.games
D/Finsky  ( 7485): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/Finsky  ( 7485): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/ResourcesManager( 2484): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,I/ActivityManager(  901): Killing 6715:com.samsung.klmsagent/u0a18 (adj 15): bgCount ##41
,W/libprocessgroup(  901): failed to open /acct/uid_10018/pid_6715/cgroup.procs: No such file or directory
,D/AcmsKeyStoreHelper( 7403):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 7403): Key Store exist
I/AcmsKeyStoreHelper( 7403): Hence loading the keystore file
,D/ChimeraCfgMgr( 2484): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2484): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2484): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 2484): Submit a task: k
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  901): MasterInitialState.processMessage what=3
,I/ApplicationPolicy(  901): updateDataUsageMap
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2293): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
,I/CLocInfoService(  901): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  901): CLoinfo wifi false
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3691): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3691): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ChimeraCfgMgr( 2484): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/SLocation(  901): No Active Data Connection
,D/k       ( 2484): Processing package: com.test.thalitest
,D/ChimeraCfgMgr( 2484): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/GassUtils( 2484): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
D/k       ( 2484): Found info for package com.test.thalitest in db.
,I/PeopleDatabaseHelper( 2484): cleanUpNonGplusAccounts done.
,D/AcmsKeyStoreHelper( 7403):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 7403): getKeyStoreForApplication success 
D/AcmsCore( 7403): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
,D/AcmsServiceMonitor( 7403): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7403): Decrementing - Counter value: 1
,D/AcmsCore( 7403): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 7403): This is NOT a valid MirrorLink app
D/AcmsCore( 7403): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7403): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 7403): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7403): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7403): getSvcCounter - Counter value: 0
,D/AcmsService( 7403): Enter onDestroy
I/AcmsService( 7403): cleanUp(): inside service clean up
D/AcmsCore( 7403): AcmsCore: inside DeInit
,D/AcmsCore( 7403): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7403): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 7403): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7403): KeyStoreHelper: inside cleanup
,D/AcmsAppEntryInterface( 7403): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7403): getSvcCounter - Counter value: 0
,D/AcmsService( 7403): killing acms process
I/Process ( 7403): Sending signal. PID: 7403 SIG: 9
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7554): MountEmulatedStorage()
I/libpersona( 7554): KNOX_SDCARD checking this for 10039
E/Zygote  ( 7554): v2
I/libpersona( 7554): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7554 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7554): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  901): Process ACMS.Process (pid 7403)(adj 0) has died(55,607)
,I/SELinux ( 7554): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7554): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/BaseAppContext( 2484): Using Auth Proxy for data requests.
W/BaseAppContext( 2484): Using Auth Proxy for data requests.
,D/TimaKeyStoreProvider( 7554): TimaSignature is unavailable
,D/ActivityThread( 7554): Added TimaKeyStore provider
,D/ResourcesManager( 7554): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,I/art     (  901): Explicit concurrent mark sweep GC freed 35971(2013KB) AllocSpace objects, 2(32KB) LOS objects, 30% free, 36MB/52MB, paused 1.361ms total 75.597ms
,D/BootupListener( 1471): ACTION_DRIVELINK
,D/SettingsProvider(  901): name = drivelink_navigation
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1001
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/BootupListener( 1471): NAVI : com.google.android.apps.maps
D/SettingsProvider(  901): name = internet_call_settings_visibility
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1001
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SecurityLogAgent( 6837):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6837):  SeDenialReceiver : File path = null
,I/Hs20UtilService( 1323): Starting #6
,I/Hs20UtilService( 1323): Message received 5007
,D/NearbySettings( 1323): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1323): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1323): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1323): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1323): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 1323): Starting #7
I/Hs20UtilService( 1323): Message received 5007
D/NearbySettings( 1323): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1323): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1323): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1323): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1323): MountReceiver.mPrefHandler - 7002
,I/PCWCLIENTTRACE_PushUtil( 6998): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6998): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6998): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6998): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_SYSTEMReceiver( 6998): noConnectivity : true
,E/Zygote  ( 7573): MountEmulatedStorage()
E/Zygote  ( 7573): v2
I/libpersona( 7573): KNOX_SDCARD checking this for 10125
I/libpersona( 7573): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7573 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7573): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  901): Killing 6731:com.sec.android.soagent/u0a36 (adj 15): bgCount ##41
I/SELinux ( 7573): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7573): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/BaseAppContext( 2484): Using Auth Proxy for data requests.
,D/TimaKeyStoreProvider( 7573): TimaSignature is unavailable
,D/ActivityThread( 7573): Added TimaKeyStore provider
,D/ResourcesManager( 7573): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BaseAppContext( 2484): Using Auth Proxy for data requests.
,W/BaseAppContext( 2484): Using Auth Proxy for data requests.
W/BaseAppContext( 2484): Using Auth Proxy for data requests.
,W/BaseAppContext( 2484): Using Auth Proxy for data requests.
,D/FactoryTest( 6226): Not factory mode
D/FactoryTest( 6226): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6226): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6226): still no open session command from host, so toast
,W/ContextImpl( 6226): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6226): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6226): Timeline: Activity_launch_request id:com.android.settings time:108888
E/PersonaManagerService(  901): inState():  stateMachine is null !!
,V/ApplicationPolicy(  901): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  901): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  901): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 901  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  901): mDVFSHelper.acquire()
,I/wpa_supplicant( 1274): nl80211: Received scan results (2 BSSes)
,I/wpa_supplicant( 1274): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1274): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1274): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  901): [1,453,981,671,766 ms] noteScanEnd no scan source
,W/libprocessgroup(  901): failed to open /acct/uid_10036/pid_6731/cgroup.procs: No such file or directory
,E/WifiStateMachine(  901): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2b2c2481 sup_state=SCANNING debouncing=false
,I/SQLiteSecureOpenHelper( 3469): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3469): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,E/MTPRx   ( 6226): started activity for popup
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  901): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  901): setDetailed state send new extra info0x
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  901): External Intent Received android.net.wifi.SCAN_RESULTS
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/ResourcesManager( 6226): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6226): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6226): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6226): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6226): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6226): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6226): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6226): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/wpa_supplicant( 1274): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1274): Associated with C0.AA.48
,E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  901): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/SettingsReceiverActivity( 6226): PREF_DONT_ASK_AGAIN : true
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,E/ActivityManager(  901): Invalid thumbnail dimensions: 576x576
,D/InputMethodManagerService(  901): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/wpa_supplicant( 1274): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,W/InputMethodManagerService(  901): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3ca3d471 attribute=null, token = android.os.BinderProxy@1c18e20c
,E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  901): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  901): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,I/MusicStore( 7573): Database version: 104
,I/SQLiteSecureOpenHelper( 3469): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3469): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,I/wpa_supplicant( 1274): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1274): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  901): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
I/wpa_supplicant( 1274): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1274): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1274): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1274): Blacklist: Clear (temp) 
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  901): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  901): Network connection established
,D/WifiNative-HAL(  901): callSECApiVoid - ID [50]
E/WifiStateMachine(  901): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  901): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  901): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  901): Got NetworkAgent Messenger
D/ConnectivityService(  901): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  901): updateNetworkInfo()
,D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  901): NetworkAgent connected
E/WifiStateMachine(  901): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  901): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,E/WifiStateMachine(  901): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  901): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
E/WifiStateMachine(  901): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,D/CommandListener(  284): Setting iface cfg
,E/WifiStateMachine(  901): Start Dhcp Watchdog 2
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  901): mCursor = null
V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,I/WifiStateMachine(  901): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  901): calculateWifiScore() report new score 60
,I/WifiStateMachine(  901): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  901): calculateWifiScore : sendNetworkScore out!
V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
I/WifiStateMachine(  901): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  901): CMD_RSSI_POLL : out!
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,D/ConnectivityService(  901): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,E/WifiStateMachine(  901): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
E/WifiStateMachine(  901): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6226): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6226): dev.kiessupport is : TRUE
,D/Activity( 6226): performCreate Call secproduct feature valuefalse
D/Activity( 6226): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/ActivityManager(  901): post active user change for 0
D/KnoxTimeoutHandler(  901): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  901): handleActiveUserChange for user 0
,D/ResourcesManager( 7573): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7573): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7573): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,I/Timeline( 7182): Timeline: Activity_idle id: android.os.BinderProxy@114b88cb time:109164
,E/WifiStateMachine(  901): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  901): do suspend false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
D/WifiP2pService(  901): InactiveState{ what=143375 }
,D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
,V/JNIHelp ( 7573): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7573): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7573): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@287666aa: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7573): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7573): GMSCore installation verified
,I/ConfigStore( 7573): Config Database version: 1
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7573): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7573): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7573): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/art     ( 2484): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 101.066ms
,D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  298): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  901): getStreamVolume 3 index 0
,I/MediaRouter( 7573): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/dhcpcd  ( 7601): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7601): version 5.5.6 starting
,E/Zygote  ( 7602): MountEmulatedStorage()
E/Zygote  ( 7602): v2
I/libpersona( 7602): KNOX_SDCARD checking this for 10002
I/libpersona( 7602): KNOX_SDCARD not a persona
E/dhcpcd  ( 7601): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/ActivityManager(  901): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7602 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  319): Explicit concurrent mark sweep GC freed 8734(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 273us total 18.357ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.988ms
,E/SMD     (  290): DCD ON
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.431ms
,I/dhcpcd  ( 7601): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7601): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7601): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7601): bssid match
,I/dhcpcd  ( 7601): wlan0: rebinding lease of 192.168.1.136
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7602): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7602): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7602): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7573): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider( 7602): TimaSignature is unavailable
,D/ActivityThread( 7602): Added TimaKeyStore provider
,D/ResourcesManager( 7602): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  901): Killing 6767:com.samsung.android.scloud.sync/u0a66 (adj 15): bgCount ##41
,I/ActivityManager(  901): Killing 6783:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): bgCount ##41
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  901): failed to open /acct/uid_10066/pid_6767/cgroup.procs: No such file or directory
,E/Zygote  ( 7627): MountEmulatedStorage()
I/libpersona( 7627): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7627): v2
I/libpersona( 7627): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7627 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/Icing   ( 2484): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,I/SELinux ( 7627): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7627): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7627): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7627): TimaSignature is unavailable
,D/ActivityThread( 7627): Added TimaKeyStore provider
,D/ResourcesManager( 7627): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/ChimeraCfgMgr( 2484): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2484): Module APK com.google.android.play.games already loaded
,W/libprocessgroup(  901): failed to open /acct/uid_10070/pid_6783/cgroup.procs: No such file or directory
,D/ResourcesManager( 2484): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/DIAGMON_AGENT( 7627): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7627): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/GAV2    ( 7155): Thread[GAThread,5,main]: No campaign data found.
,I/Icing   ( 2484): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,I/DIAGMON_AGENT( 7627): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7627): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,D/PowerManagerService(  901): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  901): Nap time (uid 1000)...
I/PowerManagerService(  901): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  901): Going to sleep due to screen timeout (uid 1000)...
D/InputManager-JNI(  901): setDeviceInteractive: 0
D/PowerManagerService(  901): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  901): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI(  901): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,I/DIAGMON_AGENT( 7627): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7627): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
D/PowerManagerService(  901): handleSandman : startDream()
,E/PowerManagerService(  901): handleSandman : startDreaming, but isDreaming false
D/InputManager-JNI(  901): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,I/PowerManagerService(  901): Sleeping (uid 1000)...
D/PowerManagerService(  901): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  901): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  901): [input device light] handleInputDeviceLightOff
D/InputManager-JNI(  901): sysfs_write -: /sys/class/input/event1/device/enabled: 0
I/SurfaceFlinger(  257): id=17 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  901): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  901): 	.unregisterCallback : 1, client=
D/SContextService(  901): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@31b2e5e6, Service = Auto Rotation, used = 1
,W/CAE     (  901): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  901): stop(ContextProvider.java:149)
,V/CAE     (  901): clear(AutoRotationRunner.java:182)
V/CAE     (  901): disable(AutoRotationRunner.java:171)
,I/CAE     (  901): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  901): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  305): sendContextData: -78, 7, 0, 0
,D/CAE     (  901): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  901): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/CAE     (  901): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  901): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  901): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  901): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  901): removeSContextService() : service = Auto Rotation
D/SContextService(  901): ===== SContext Service List =====
D/SContextManager(  901):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@2820ace1, service=Auto Rotation
,D/KeyguardViewMediator( 1191): onScreenTurnedOff(3)
D/DisplayPowerController(  901): ColorFade: onAnimationStart
D/DisplayPowerController(  901): getFinalBrightness : 8 -> 0
,I/KeyguardEffectViewController( 1191): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1191): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1191): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/KeyguardViewMediator( 1191): timeout : 5000
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
E/Zygote  ( 7652): MountEmulatedStorage()
I/libpersona( 7652): KNOX_SDCARD checking this for 10010
E/Zygote  ( 7652): v2
I/libpersona( 7652): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7652 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7652): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7652): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7652): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/DisplayPowerController(  901): getFinalBrightness : 8 -> 0
,D/lights  (  901): lcd : 0 +
,D/lights  (  901): lcd : 0 -
,I/SQLiteSecureOpenHelper( 3469): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3469): getDatabaseLocked(b,b,pwd)...
,D/TimaKeyStoreProvider( 7652): TimaSignature is unavailable
,D/ActivityThread( 7652): Added TimaKeyStore provider
,D/KeyguardViewMediator( 1191): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1191): handleNotifyScreenOff
,D/LightsService(  901): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 901) 
,D/LightsService(  901): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  901): [SvcLED]  onSensorChanged::light value = 1
,D/ResourcesManager( 7652): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,D/SensorManager(  901): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService(  901): turn on LED for fully charged
,D/SensorManager(  901): unregisterListener ::   
D/lights  (  901): led_pattern : 5 +
,I/CAE     (  901): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  901): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  901): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  901): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  305): sendContextData: -76, 13, -46, 0
,D/lights  (  901): led_pattern : 5 -
D/LightsService(  901): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  901): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 11, 47, 52,
D/SensorHubManager(  901): SendSensorHubData: send data = -63, 14, 11, 47, 52
D/Sensorhubs(  305): sendContextData: -63, 14, 11, 47, 52
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  901):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  901): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  901): handleScreenStateChanged Exit: false
,D/NotificationService(  901): ACTION_SCREEN_OFF
D/LightsService(  901): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 901) 
D/LightsService(  901): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService(  901): [SvcLED]  onSensorChanged::light value = 1
,E/WifiStateMachine(  901): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,D/SensorManager(  901): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  901): unregisterListener ::   
D/LightsService(  901): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/ActivityManager(  901): Killing 6800:com.sec.android.app.clockpackage/u0a90 (adj 15): bgCount ##41
,I/FOTA_Client( 7652): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/audio_hw_primary(  298): adev_set_parameters: enter: screen_state=off
V/voice   (  298): voice_set_parameters: enter: screen_state=off
V/voice   (  298): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  298): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  298): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  298): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  298): adev_set_parameters: exit
,D/DisplayPowerState(  901): !@ ColorFade entry
D/DisplayPowerController(  901): ColorFade: onAnimationEnd
,I/FOTA_Client( 7652): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/AutomaticBrightnessController(  901): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  901): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController(  901): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  901): Light old sensor_state 513, new sensor_state : 1 en : 0
I/AutomaticBrightnessController(  901): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  901): unregisterListener ::   
E/Sensors (  901): Acc old sensor_state 1, new sensor_state : 0 en : 0
,I/SecExternalDisplayIntents_Java(  901): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  901): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  901): Bridge Server is not available
D/SensorManager(  901): unregisterListener ::   
,D/VolumePanel( 1191): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1191): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1191): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1191): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,I/FOTA_Client( 7652): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/PersonaManagerService(  901): ACTION_SCREEN_OFF onReceive
,D/DisplayPowerController(  901): getFinalBrightness : 0 -> 0
D/DisplayPowerController(  901): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  901): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  257): hwc_blank: Blanking display: 0
D/PersonaManagerServiceHandler(  901): MSG_ACTION_SCREEN_OFF called
,V/ActivityManager(  901): Display changed displayId=0
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,W/libprocessgroup(  901): failed to open /acct/uid_10090/pid_6800/cgroup.procs: No such file or directory
,E/Zygote  ( 7671): MountEmulatedStorage()
E/Zygote  ( 7671): v2
I/libpersona( 7671): KNOX_SDCARD checking this for 10018
I/libpersona( 7671): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7671 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 6815:com.sec.esdk.elm/u0a103 (adj 15): bgCount ##41
,I/SELinux ( 7671): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,I/SELinux ( 7671): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7671): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1191): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/NfcService( 1465): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1191):      ACTION_SCREEN_OFF is finished!!!! 
,D/TimaKeyStoreProvider( 7671): TimaSignature is unavailable
,D/ActivityThread( 7671): Added TimaKeyStore provider
,D/ResourcesManager( 7671): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,E/StatusBar( 1191): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1191): dismissHelpPopup 
,D/accuweather( 2293): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2293): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2293): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,W/libprocessgroup(  901): failed to open /acct/uid_10103/pid_6815/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7671): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7671): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453981673152
,I/rmt_storage(  277): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
,I/rmt_storage(  277): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  277): wakelock acquired: 1, error no: 42
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,I/KLMS-2.4.503: ( 7671): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7671): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7671): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  901): Killing 5818:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
,I/dhcpcd  ( 7601): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,W/ActivityManager(  901): getTasks: caller 10085 does not hold GET_TASKS; limiting output
,W/ActivityManager(  901): getTasks: caller 10085 does not hold GET_TASKS; limiting output
,D/SSRM:m  (  901): SIOP:: AP = 410, PST = 364, CUR = 450
,D/PowerManagerService(  901): [PWL] sb release: PowerManagerService.Broadcasts
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 22
I/rmt_storage(  277): 
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
I/rmt_storage(  277): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,I/dhcpcd  ( 7601): wlan0: leased 192.168.1.136 for 86400 seconds
I/libpersona( 7686): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7686): MountEmulatedStorage()
I/libpersona( 7686): KNOX_SDCARD not a persona
E/Zygote  ( 7686): v2
,E/WifiStateMachine(  901): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  901): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/ActivityManager(  901): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7686 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  257): hwc_blank: Done blanking display: 0
D/SurfaceControl(  901): Excessive delay in setPowerMode(): 252ms
D/PowerManagerService(  901): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  901): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  901): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  901): Got set_interactive hint
,I/PowerManagerService(  901): [PWL] Off : 0s ago
I/PowerManagerService(  901): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  901): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  901): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=901, ws=null) (elapsedTime=2513)
,I/PowerManagerService(  901): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  901): [PWL]     mDisplayReady : false
D/DisplayPowerController(  901): getFinalBrightness : 0 -> 0
D/PowerManagerService(  901): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  901): [PWL] sb release: PowerManagerService.Display
,I/SELinux ( 7686): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7686): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/libprocessgroup(  901): failed to open /acct/uid_10112/pid_5818/cgroup.procs: No such file or directory
,E/SELinux ( 7686): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7686): TimaSignature is unavailable
,D/ActivityThread( 7686): Added TimaKeyStore provider
,D/ResourcesManager( 7686): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7686): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7035): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6749): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6749): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6749): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6749): [SLFUCHKMGR] constructor called
,E/SPPClientService( 7035): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 6749): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6749): [OR] == isSIMCardReady false ==
,I/SA      ( 6749): [SCU] == networkStateCheck == false
I/SA      ( 6749): [OR] onReceive END
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7725): MountEmulatedStorage()
E/Zygote  ( 7725): v2
I/libpersona( 7725): KNOX_SDCARD checking this for 10070
I/libpersona( 7725): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7725 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,E/WifiStateMachine(  901): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  901): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  901): do suspend true
,D/WifiP2pService(  901): InactiveState{ what=143375 }
,D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  901): WifiStateMachine DHCP successful
,E/WifiStateMachine(  901): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  901): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  901): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  901): Not connected state, yet.
E/WifiStateMachine(  901): VerifyingLinkState enter
,I/SELinux ( 7725): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/WifiStateMachine(  901): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  901): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  901): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  901): callSECApiInt - ID [210]
I/ActivityManager(  901): Killing 5550:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): bgCount ##41
E/WifiStateMachine(  901): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  901): updateNetworkInfo()
I/SELinux ( 7725): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ConnectivityService(  901): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
E/SELinux ( 7725): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  901): Adding iface wlan0 to network 503
,I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  901): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,E/WifiStateMachine(  901): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  901): Now, connected state.
E/WifiStateMachine(  901): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  901): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
,I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
,D/TimaKeyStoreProvider( 7725): TimaSignature is unavailable
,D/ActivityThread( 7725): Added TimaKeyStore provider
,D/ConnectivityService(  901): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  901): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  901): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  901): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  901): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  901): updateSourceRoutes : add src route for:192.168.1.136
,E/WifiStateMachine(  901): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  901): mBoosterFLAG : 0
I/WifiTrafficPoller(  901): current booster mode : FullMode
V/        (  284): QcRouteController
,D/WifiNative-HAL(  901): callSECApiVoid - ID [212]
,I/CLocInfoService(  901): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  901): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
I/WifiStateMachine(  901): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,W/libprocessgroup(  901): failed to open /acct/uid_10148/pid_5550/cgroup.procs: No such file or directory
,D/ResourcesManager( 7725): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
V/        (  284): QcRouteController
W/ResourcesManager( 7725): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7725): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7725): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,D/comsamsunglog( 7725): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7725): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7725): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7725): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7725): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7725): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7725): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7725): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  901): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
V/        (  284): QcRouteController
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 10070
,D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/daemonapp( 1363): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,D/accuweather( 7725): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7725): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7725): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7725): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7725): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7725): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1363): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,V/        (  284): QcRouteController
,D/accuweather( 7725): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1363): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7725): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/ConnectivityService(  901): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  901): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/daemonapp( 1363): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ConnectivityService(  901): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901): ignoring duplicate network state non-change
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): ignoring duplicate network state non-change
E/ConnectivityService(  901): updateNetworkInfo()
,D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  901): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Validated
D/ConnectivityService(  901):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  901): currentScore = 0, newScore = 60
,D/ConnectivityService(  901):    accepting network in place of null
D/ConnectivityService(  901): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1471): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  901): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker(  901): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/accuweather( 7725): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7725): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7759): MountEmulatedStorage()
E/Zygote  ( 7759): v2
I/libpersona( 7759): KNOX_SDCARD checking this for 1000
I/libpersona( 7759): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7759 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 4659:com.android.calendar/u0a149 (adj 15): bgCount ##41
,D/ConnectivityService(  901): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  901): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
,V/NetworkStats(  901): updateIfacesLocked()
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
V/NetworkStats(  901): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  901): UpdateStatsForKnox
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/EntConnectivity(  901): Not allowed due to - mEnabled false
D/ConnectivityService(  901): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
,D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkStats(  901): performPollLocked() took 4ms
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/ConnectivityService(  901): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  901):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,D/ConnectivityService(  901): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/SELinux ( 7759): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
,D/StatusBar.NetworkController( 1191): getUpdateDataNetType(): 0
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1191): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1191): updateDataNetType()
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 1191): CM callback handler got msg 524290
I/SELinux ( 7759): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/StatusBar.NetworkController( 1191): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1191): updateLTEICONDataNetType:0
D/ConnectivityManager.CallbackHandler( 1191): CM callback handler got msg 524290
,E/SELinux ( 7759): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 2484): CM callback handler got msg 524290
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,V/NetworkStats(  901): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1191): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1191): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1191): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1191): updateDataNetType()
D/StatusBar.NetworkController( 1191): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1191): updateLTEICONDataNetType:0
,D/ConnectivityManager.CallbackHandler( 2484): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1191): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/TimaKeyStoreProvider( 7759): TimaSignature is unavailable
,D/ActivityThread( 7759): Added TimaKeyStore provider
,W/libprocessgroup(  901): failed to open /acct/uid_10149/pid_4659/cgroup.procs: No such file or directory
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager( 7759): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7759): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7759): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7759): premStatus:2
,I/KnoxUsageLogPro( 7759): isEulaShown : false
I/KnoxUsageLogPro( 7759): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7774): MountEmulatedStorage()
,E/Zygote  ( 7774): v2
I/libpersona( 7774): KNOX_SDCARD checking this for 10087
I/libpersona( 7774): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7774 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 6854:com.sec.android.app.taskmanager/u0a175 (adj 15): bgCount ##41
,I/SELinux ( 7774): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7774): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7774): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7774): TimaSignature is unavailable
,D/ActivityThread( 7774): Added TimaKeyStore provider
,D/ResourcesManager( 7774): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  901): failed to open /acct/uid_10175/pid_6854/cgroup.procs: No such file or directory
,I/ActivityManager(  901): Killing 6870:com.qualcomm.timeservice/1000 (adj 15): bgCount ##41
,D/Headlines( 5352): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5352): getCountryCode(): countryCode = PL
,D/Headlines( 5352): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5352): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5352): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5352): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5352): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5352): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5352): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7790): MountEmulatedStorage()
,E/Zygote  ( 7790): v2
I/libpersona( 7790): KNOX_SDCARD checking this for 10127
I/libpersona( 7790): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7790 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7790): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7790): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7790): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7790): TimaSignature is unavailable
,D/ActivityThread( 7790): Added TimaKeyStore provider
,D/ResourcesManager( 7790): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  901): failed to open /acct/uid_1000/pid_6870/cgroup.procs: No such file or directory
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  901): MasterInitialState.processMessage what=3
D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  901): SmartBondingReceiver: wifi is connected
,D/SmartBondingService(  901): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
I/CLocInfoService(  901): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  901): CLocinfo wifi true 
D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2293): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2182): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2182): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7573): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3691): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3691): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/SecContentProvider2(  901): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  901): mCursor = null
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7790): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7790): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7790): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7790): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2200): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2200): Vacuum at: now=1453981674319 tag=VacuumService
,I/WebViewFactory( 7790): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7790): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/LibraryLoader( 7790): Loading: webviewchromium
,I/LibraryLoader( 7790): Time to load native libraries: 4 ms (timestamps 1577-1581)
I/LibraryLoader( 7790): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7790): Binding Chromium to main looper Looper (main, tid 1) {3244bde4}
,I/LibraryLoader( 7790): Expected native library version number "",actual native library version number ""
,I/chromium( 7790): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7790): Initializing chromium process, renderers=0
,W/art     ( 7790): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid( 7790): Requires BLUETOOTH permission
,W/chromium( 7790): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7790): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7790): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/Adreno-EGL( 7790): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7790): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7790): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7790): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7790): Remote Branch: 
I/Adreno-EGL( 7790): Local Patches: 
I/Adreno-EGL( 7790): Reconstruct Branch: 
,I/NSApplication( 7790): Starting up...
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  901): Killing 4718:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7849): MountEmulatedStorage()
E/Zygote  ( 7849): v2
I/libpersona( 7849): KNOX_SDCARD checking this for 10137
I/libpersona( 7849): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7849 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7849): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7849): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7849): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7849): TimaSignature is unavailable
,D/ActivityThread( 7849): Added TimaKeyStore provider
,D/ResourcesManager( 7849): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,D/ConnectivityService(  901): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/ResourcesManager( 7849): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7849): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7849): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup(  901): failed to open /acct/uid_10045/pid_4718/cgroup.procs: No such file or directory
,D/QuickConnect( 7849): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7849): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7849): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7865): MountEmulatedStorage()
,E/Zygote  ( 7865): v2
I/libpersona( 7865): KNOX_SDCARD checking this for 10162
I/libpersona( 7865): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7865 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 6965:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,D/CustomFrequencyManagerService(  901): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 901  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  901): mDVFSHelper.release()
,I/SELinux ( 7865): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7865): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7865): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7865): TimaSignature is unavailable
,D/ActivityThread( 7865): Added TimaKeyStore provider
,D/ResourcesManager( 7865): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7865): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7865): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7865): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7865): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  901): failed to open /acct/uid_10014/pid_6965/cgroup.procs: No such file or directory
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7887): MountEmulatedStorage()
E/Zygote  ( 7887): v2
I/libpersona( 7887): KNOX_SDCARD checking this for 10077
I/libpersona( 7887): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7887 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,I/art     (  319): Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 296us total 14.975ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 243us total 7.986ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.738ms
,I/SELinux ( 7887): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/RCPManagerService(  901): exchangeData() failure , invalid userId
I/SELinux ( 7887): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7887): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 7887): TimaSignature is unavailable
,D/ActivityThread( 7887): Added TimaKeyStore provider
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6837): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6837): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6837): StateMachine : Current State = 1
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6837): StateMachine : Changed Current State = 1
V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
I/ActivityManager(  901): Killing 6983:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,I/art     (  901): Explicit concurrent mark sweep GC freed 59663(3MB) AllocSpace objects, 5(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.576ms total 114.121ms
,I/ActivityManager(  901): Killing 6262:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,D/ResourcesManager( 7887): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,W/libprocessgroup(  901): failed to open /acct/uid_10015/pid_6983/cgroup.procs: No such file or directory
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7865): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/GAV2    ( 7420): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BadgeProvider( 7887): onCreate
D/BadgeProvider( 7887): DatabaseHelper
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  901): Killing 4781:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7905): MountEmulatedStorage()
I/libpersona( 7905): KNOX_SDCARD checking this for 10177
E/Zygote  ( 7905): v2
I/libpersona( 7905): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7905 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/BadgeProvider( 7887): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/SELinux ( 7905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7905): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,E/SMD     (  290): DCD ON
,D/BadgeProvider( 7887): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7887): sendNotify, [notify] : null
D/BadgeProvider( 7887): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7887): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7887): update, [UpdateCount] : 1
,D/Launcher.Model( 1478): reloadBadges entered.
,D/TimaKeyStoreProvider( 7905): TimaSignature is unavailable
,D/ActivityThread( 7905): Added TimaKeyStore provider
,W/ActivityManager(  901): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ResourcesManager( 7905): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,W/libprocessgroup(  901): failed to open /acct/uid_10033/pid_6262/cgroup.procs: No such file or directory
,W/libprocessgroup(  901): failed to open /acct/uid_10034/pid_4781/cgroup.procs: No such file or directory
,E/WifiStateMachine(  901): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  901): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  901): identical MTU - not setting
D/ConnectivityService(  901): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  901): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
V/        (  284): QcRouteController
E/WifiStateMachine(  901): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
,V/        (  284): QcRouteController
,I/ActivityManager(  901): Killing 7052:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
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
D/ConnectivityService(  901): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  901): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  901): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 2484): CM callback handler got msg 524295
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  901): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1191): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1191): CM callback handler got msg 524295
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityManager.CallbackHandler( 2484): CM callback handler got msg 524295
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7554): notifyNetworkActivated
,W/libprocessgroup(  901): failed to open /acct/uid_10041/pid_7052/cgroup.procs: No such file or directory
,W/ContextImpl( 7554): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  901): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    ( 7554): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7554): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7554): exit::IDLE
D/InitializeManagerStateMachine( 7554): entry::NETWORK_CHECK
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7554): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 7554): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 7554): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7554): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7554): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7554): entry::SUCCESS
D/hcjo    ( 7554): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1323): Starting #8
,I/Hs20UtilService( 1323): Message received 5007
,D/hcjo    ( 7554): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7554): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NearbySettings( 1323): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1323): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/InitializeManagerStateMachine( 7554): exit::SUCCESS
D/InitializeManagerStateMachine( 7554): entry::IDLE
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1323): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1323): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1323): Starting #9
,I/Hs20UtilService( 1323): Message received 5007
,D/NearbySettings( 1323): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1323): MountReceiver.onReceive - Keep current state
,I/jxcore-log( 7182): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7182): 
,I/Hs20UtilService( 1323): Starting #10
,D/NearbySettings( 1323): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 1323): Message received 5007
,V/NearbySettings( 1323): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1323): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1323): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1323): Starting #11
,I/Hs20UtilService( 1323): Message received 5007
,D/NearbySettings( 1323): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1323): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  901): callSECApi what=220
D/WifiStateMachine(  901): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 6998): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6998): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6998): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6998): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  257): id=18 createSurf (1x1),1 flag=4, Toast
,I/DIAGMON_AGENT( 7627): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7627): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/PowerManagerService(  901): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=901
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,I/FOTA_Client( 7652): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7652): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,I/FOTA_Client( 7652): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.503: ( 7671): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7671): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453981675690
,I/KLMS-2.4.503: ( 7671): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7671): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7671): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7671): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7671): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7686): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7035): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6749): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6749): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 6749): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6749): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6749): [OR] == isSIMCardReady false ==
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6749): [SCU] == networkStateCheck == true
,I/SA      ( 6749): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6749): isChinaCountryCode : false
I/SA      ( 6749): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6749): [OR] == networkStateCheck true ==
,I/SA      ( 6749): [OR] GetMyCountryZoneTask
,I/SA      ( 6749): [OR] onReceive END
,I/SA      ( 6749): [SRS] prepareGetMyCountryZone
,I/SA      ( 6749): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6749): [SSP] query invoked
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6749): [TPMU] GetMccFromDB : null
I/SA      ( 6749): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6749): [TPM] isNoProxy(default) : true
,D/accuweather( 7725): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7725): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7759): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7759): premStatus:2
,I/KnoxUsageLogPro( 7759): isEulaShown : false
,I/KnoxUsageLogPro( 7759): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 6749): fail readDirectory() errno=2
,D/Headlines( 5352): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5352): getCountryCode(): countryCode = PL
,D/Headlines( 5352): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5352): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5352): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5352): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5352): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5352): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5352): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7849): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7849): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7849): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6837): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6837): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6837): StateMachine : Current State = 1
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6837): StateMachine : Changed Current State = 1
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7554): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7554): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7554): exit::IDLE
D/InitializeManagerStateMachine( 7554): entry::NETWORK_CHECK
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7554): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7554): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7554): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7554): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7554): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7554): entry::SUCCESS
D/hcjo    ( 7554): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7554): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7554): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7554): exit::SUCCESS
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7554): entry::IDLE
,D/PackageManager(  901): [MSG] MCS_UNBIND
,I/ActivityManager(  901): Killing 5735:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,I/jxcore-log( 7182): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7182): 
,I/jxcore-log( 7182): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7182): 
,I/jxcore-log( 7182): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7182): 
,W/libprocessgroup(  901): failed to open /acct/uid_10047/pid_5735/cgroup.procs: No such file or directory
,I/SA      ( 6749): [RC New] Execute method=[GET] start
,I/jxcore-log( 7182): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7182): 
,I/SA      ( 6749): [RC New] Security=[true]
,I/System.out( 6749): Thread-1045(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/jxcore-log( 7182): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7182): 
,I/jxcore-log( 7182): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7182): 
,I/System.out( 6749): Thread-1045(ApacheHTTPLog):isShipBuild true
,I/System.out( 6749): Thread-1045(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 7182): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7182): 
,I/dhcpcd  ( 7601): wlan0: sending IPv6 Router Solicitation
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  901): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  901): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/WearableService( 2200): callingUid 10011, callindPid: 2200
,D/ResourcesManager( 7573): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7573): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7573): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7573): Using the GMSCore's GoogleHttpClient
,D/WearableClient( 7573): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7573): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7573): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7573): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7573): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7573): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7573): Conditions not met for autocaching.
I/MusicLeanback( 7573): Stop autocaching.
,E/ActivityThread( 7573): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@155ceea4 that was originally bound here
E/ActivityThread( 7573): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@155ceea4 that was originally bound here
E/ActivityThread( 7573): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7573): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7573): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7573): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7573): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7573): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7573): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7573): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7573): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7573): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7573): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7573): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7573): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7573): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7573): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7573): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7573): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7573): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7573): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7573): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7573): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7573): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7573): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7573): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7573): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,V/AlarmManager(  901): waitForAlarm result :4
,D/KeyguardViewMediator( 1191): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1191): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/KeyguardViewMediator( 1191): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  901): [PWL] Off : 5s ago
,E/SMD     (  290): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  257): id=18 Removed Toast (8/9)
,I/SurfaceFlinger(  257): id=18 Removed Toast (-2/9)
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/PowerManagerService(  901): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 901) eventTime = 116250
,D/PowerManagerService(  901): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=901 (0x0)
,D/PowerManagerService(  901): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=901, ws=WorkSource{10058}) (elapsedTime=3486)
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,I/GAV4    ( 7790): Thread[GAThread,5,main]: No campaign data found.
,I/SA      ( 6749): [RC New] [v2liruge] api execute + 3174
,I/SA      ( 6749): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6749): AsyncTask #1 calls detatch()
,I/SA      ( 6749): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6749): [OCP] update openData : PL
,I/SA      ( 6749): [TPMU] getNetworkMcc : 
,I/SA      ( 6749): [SCU] saveMccToPreferece Start
,I/SA      ( 6749): [SCU] RegionMCC : 260
I/SA      ( 6749): [SSP] query invoked
,I/SA      ( 6749): [TPMU] GetMccFromDB : null
,I/SA      ( 6749): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6749): [SCU] saveMccToPreferece End
,I/SA      ( 6749): [RC New] executeRequest [v2liruge] end. 3222
I/SA      ( 6749): [RC New] Execute end
I/SA      ( 6749): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6749): [OR] GetMyCountryZoneTask Success
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,V/AlarmManager(  901): waitForAlarm result :8
,I/dhcpcd  ( 7601): wlan0: sending IPv6 Router Solicitation
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6998): mConnectivityHandler : connected
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6998): [hasSamungAccount] - No Samsung Account
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6998): [GetString-S]
,I/ReactiveServiceManager( 6998): Supported : 1
,D/QSEECOMAPI: (  901): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: (  901): App is not loaded in QSEE
,D/QSEECOMAPI: (  901): Loaded image: APP id = 3
,D/QSEECOMAPI: (  901): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  901): QSEECom_shutdown_app, app_id = 3
E/terrier (  901): handleString: Failed to handle string(-4)
E/terrier (  901): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 6998): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6998): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6998): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6998): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6998): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6998): [ensureRegistration] - No Samsung account
,I/jxcore-log( 7182): Test app app.js loaded
I/jxcore-log( 7182): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7182): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7182): BLE advertisement is supported
I/jxcore-log( 7182): 
,I/chromium( 7182): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SMD     (  290): DCD ON,
,D/SSRM:m  (  901): SIOP:: AP = 400, PST = 361, CUR = 450
,E/SMD     (  290): DCD ON
,I/dhcpcd  ( 7601): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7601): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 7554): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7554): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7554): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7554): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7554): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7554): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7554): entry::IDLE
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7554): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7554): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7554): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7554): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7554): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,V/AlarmManager(  901): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): stay LED for fully charged
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3217): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3217): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/PreloadUpdateManagerStateMachine( 7554): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7554): entry::IDLE
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/Finsky  ( 7485): [1220] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7485): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/PowerManagerService(  901): [PWL] Off : 15s ago
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  901): Waited long enough for: ServiceRecord{45cb9aa u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  901): SIOP:: AP = 330, PST = 354, CUR = 450
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,E/Watchdog(  901): !@Sync 4
,E/SMD     (  290): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,V/AlarmManager(  901): waitForAlarm result :4
,I/PowerManagerService(  901): [PWL] Off : 30s ago
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  901): stay LED for fully charged
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3217): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3217): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  901): SIOP:: AP = 310, PST = 347, CUR = 450
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/SSRM:m  (  901): SIOP:: AP = 300, PST = 339, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3217): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3217): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 50s ago
,D/SSRM:m  (  901): SIOP:: AP = 300, PST = 335, CUR = 450
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD ON
,E/Watchdog(  901): !@Sync 5
,V/AlarmManager(  901): waitForAlarm result :4
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  901): stay LED for fully charged
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3217): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3217): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhenotypeConfigurator( 2200): Scheduling Phenotype for one-off execution 279 seconds from now (1453981728185)
,D/GetConfigurationSnapshotOperation( 2200): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2200): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2200): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  901): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2200): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2200): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2200): Tagging socket 82 with tag 1000040100000000{268436481,0} uid 10011, pid: 2200, getuid(): 10011
,I/qtaguid ( 2200): Tagging socket 86 with tag 1000040100000000{268436481,0} uid 10011, pid: 2200, getuid(): 10011
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2200): Tagging socket 79 with tag 1000120100000000{268440065,0} uid -1, pid: 2200, getuid(): 10011
,I/qtaguid ( 2200): Tagging socket 89 with tag 1000120100000000{268440065,0} uid -1, pid: 2200, getuid(): 10011
,D/SSRM:m  (  901): SIOP:: AP = 290, PST = 332, CUR = 450
,D/LocationManagerService(  901): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2200): Tagging socket 79 with tag 1000120100000000{268440065,0} uid -1, pid: 2200, getuid(): 10011
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LocationManagerService(  901): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2200): Tagging socket 79 with tag 1000120100000000{268440065,0} uid -1, pid: 2200, getuid(): 10011
,D/LocationManagerService(  901): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2200): Tagging socket 79 with tag 1000120100000000{268440065,0} uid -1, pid: 2200, getuid(): 10011
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  290): DCD ON
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,D/BatteryService(  901): stay LED for fully charged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3217): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3217): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,V/AlarmManager(  901): waitForAlarm result :8
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  901): SIOP:: AP = 290, PST = 329, CUR = 450
,E/SMD     (  290): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/PowerManagerService(  901): [PWL] Off : 75s ago
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  901): SIOP:: AP = 290, PST = 326, CUR = 450
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,E/Watchdog(  901): !@Sync 6
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,D/BatteryService(  901): stay LED for fully charged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3217): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3217): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON,
,I/ClearcutLoggerApiImpl( 2200): disconnect managed GoogleApiClient
,D/SSRM:m  (  901): SIOP:: AP = 290, PST = 321, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  901): SIOP:: AP = 280, PST = 308, CUR = 450
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 105s ago
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  901): SIOP:: AP = 270, PST = 295, CUR = 450
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,E/Watchdog(  901): !@Sync 7
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,V/AlarmManager(  901): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  901): stay LED for fully charged
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3217): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3217): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  901): SIOP:: AP = 270, PST = 289, CUR = 450
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7182): --= Surplus to requirements =--
I/jxcore-log( 7182): 
,I/jxcore-log( 7182): ****TEST TOOK:  ms ****
I/jxcore-log( 7182): 
I/jxcore-log( 7182): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7182): 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 8100): 
D/AndroidRuntime( 8100): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8100): CheckJNI is OFF
,D/AndroidRuntime( 8100): setted country_code = Poland
,D/AndroidRuntime( 8100): setted countryiso_code = PL
,D/AndroidRuntime( 8100): setted sales_code = XEO
,D/AndroidRuntime( 8100): readGMSProperty: start
,D/AndroidRuntime( 8100): readGMSProperty: already setted!!
,D/AndroidRuntime( 8100): readGMSProperty: end
D/AndroidRuntime( 8100): addProductProperty: start
,E/AffinityControl( 8100): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8100): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  901): START PACKAGE DELETE: observer{28909674}
D/PackageManager(  901): pkg{<packageName>}
D/PackageManager(  901): user{0}
D/PackageManager(  901): caller{2000}
D/PackageManager(  901): flags{3}
D/PersonaManagerService(  901): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
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
,I/ActivityManager(  901): Killing 7182:com.test.thalitest/u0a191 (adj 0): stop com.test.thalitest
,I/ActivityManager(  901):   Force finishing activity ActivityRecord{8d4d568 u0 com.test.thalitest/.MainActivity t10}
,D/FocusedStackFrame(  901): Set to : 0
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/WifiService(  901): Client connection lost with reason: 4
,I/ActivityManager(  901): Force stopping com.test.thalitest appid=10191 user=0: pkg removed
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1567): Explicit concurrent mark sweep GC freed 33089(1972KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 550us total 36.601ms
,I/art     ( 6106): Explicit concurrent mark sweep GC freed 30238(1657KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 378us total 32.442ms
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 2484): Explicit concurrent mark sweep GC freed 39663(2MB) AllocSpace objects, 7(112KB) LOS objects, 39% free, 21MB/35MB, paused 629us total 80.499ms
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  901): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1851): mOCRHelper is null
,W/GeofencerStateMachine( 2200): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.4.503: ( 7671): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/KLMS-2.4.503: ( 7671): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453981796716
,I/KLMS-2.4.503: ( 7671): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7671): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,I/art     (  901): Explicit concurrent mark sweep GC freed 51072(3MB) AllocSpace objects, 42(672KB) LOS objects, 30% free, 36MB/52MB, paused 1.631ms total 175.523ms
,I/art     (  901): WaitForGcToComplete blocked for 92.727ms for cause Explicit
,D/ResourcesManager(  901): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/SecContentProvider2(  901): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  901): mCursor = null
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/RegisteredServicesCache( 1465): empty dynamic service
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/EnterpriseDeviceManagerService(  901): Package has changed for user 0
D/EnterpriseDeviceManagerService(  901): Admin package name: com.google.android.gms
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/Zygote  ( 8130): MountEmulatedStorage()
E/Zygote  ( 8130): v2
I/libpersona( 8130): KNOX_SDCARD checking this for 10103
I/libpersona( 8130): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8130 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  901): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/art     (  901): Explicit concurrent mark sweep GC freed 12043(599KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 2.001ms total 178.199ms
,I/SELinux ( 8130): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8130): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8130): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService(  901): PackageReceiver onReceive()
,I/HarmonyEASService(  901): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/KnoxMUMContainerPolicy(  901): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/TimaKeyStoreProvider( 8130): TimaSignature is unavailable
,D/ActivityThread( 8130): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/BackupManagerService(  901): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  901): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  901): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  901): uID is 10191
V/EnterpriseBillingPolicy(  901): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  901): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  901): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  901): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  901): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  901): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  901): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager( 8130): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/TaskPersister(  901): removeObsoleteFile: deleting file=10_task.xml
,D/TaskPersister(  901): removeObsoleteFile: deleting file=10_task_thumbnail.png
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/SurfaceWidgetView( 1478): destroyHardwareResources():457394772
,V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  901): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/Launcher( 1478): onRestart, Launcher: 319709762
,D/Launcher( 1478): onStart, Launcher: 319709762
D/Launcher.HomeView( 1478): onStart
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:14451( 8130): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8130): ELMEngine.ELMEngine( context ).
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/elm:14451( 8130): MDMBridge.setEnterpriseBridge()
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/elm:14451( 8130): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/PackageManager(  901): delete codoeFile: 
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2293): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2293): [237392/6] SurfaceWidget drawing first frame
,D/elm:14451( 8130): ElmAgentService : onCreate()
,D/elm:14451( 8130): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/PackageManager(  901): result of delete: 1{28909674}
,E/Zygote  ( 8147): MountEmulatedStorage()
E/Zygote  ( 8147): v2
I/libpersona( 8147): KNOX_SDCARD checking this for 10016
I/libpersona( 8147): KNOX_SDCARD not a persona
,D/elm:14451( 8130): MainReceiver.listeningToPackageRemoved()
,D/elm:14451( 8130): MDMBridge.getInstance()
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
I/ActivityManager(  901): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8147 uid=10016 gids={50016, 9997} abi=armeabi-v7a
D/elm:14451( 8130): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/SELinux ( 8147): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/ResourcesManager(  901): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  901): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  901): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SELinux ( 8147): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8147): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14451( 8130): MDMBridge.getAllLicenseInfoFromSDK()
,I/SurfaceFlinger(  257): id=19 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/AndroidRuntime( 8100): Shutting down VM
D/TimaKeyStoreProvider( 8147): TimaSignature is unavailable
D/ActivityThread( 8147): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
,D/elm:14451( 8130): ElmAgentService : onDestroy().
,I/ActivityManager(  901): Killing 5633:com.android.mms/u0a49 (adj 15): bgCount ##41
,D/InputMethodManagerService(  901): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(  901): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager( 8147): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,W/InputMethodManagerService(  901): Got RemoteException sending setActive(false) notification to pid 7182 uid 10191
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8147): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8147): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8147): onReceive() : package name is not s health. Return !!!
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,I/PCWCLIENTTRACE_PushUtil( 6998): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6998): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6998): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6998): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/CountryDetector(  901): No listener is left
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
E/Zygote  ( 8167): MountEmulatedStorage()
I/libpersona( 8167): KNOX_SDCARD checking this for 10033
E/Zygote  ( 8167): v2
I/libpersona( 8167): KNOX_SDCARD not a persona
D/LockPatternUtilsCache( 1191): value : false
,W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 8167): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  901): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8167 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 8167): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  901): Killing 7086:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
E/SELinux ( 8167): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/UsbSettingsManager(  901): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  901): onPackageRemoved : com.test.thalitest
,D/TimaKeyStoreProvider( 8167): TimaSignature is unavailable
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/ActivityThread( 8167): Added TimaKeyStore provider
,I/Timeline(  901): Timeline: Activity_windows_visible id: ActivityRecord{2b535771 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:234396
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/LockPatternUtilsCache( 1191): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1191): value : false
,I/FeatureConfig( 8167): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,W/libprocessgroup(  901): failed to open /acct/uid_10049/pid_5633/cgroup.procs: No such file or directory
,W/libprocessgroup(  901): failed to open /acct/uid_10050/pid_7086/cgroup.procs: No such file or directory
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8167): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8167): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8167): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8167): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8167): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8167): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8167): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8167): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8167): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8167): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8167): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8167): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8167): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8167): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8167): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8167): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8167): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  901): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8185 uid=10034 gids={50034, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,E/Zygote  ( 8185): MountEmulatedStorage()
E/Zygote  ( 8185): v2
I/libpersona( 8185): KNOX_SDCARD checking this for 10034
I/libpersona( 8185): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Killing 7108:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
,I/SELinux ( 8185): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27,
I/SELinux ( 8185): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8185): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  901): failed to open /acct/uid_10057/pid_7108/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8185): TimaSignature is unavailable
,D/ActivityThread( 8185): Added TimaKeyStore provider
,D/ResourcesManager( 8185): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,F/libc    ( 8185): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa03e2000 in tid 8185 (oid.app.shealth)
,F/libc    ( 8185): Failed while talking to debuggerd: Broken pipe
,E/audit_log( 2135): File locking failed. error= Bad file number
E/audit_log( 2135): File locking failed. error= Bad file number
,I/ActivityManager(  901): Process com.sec.android.app.shealth (pid 8185)(adj 0) has died(211,558)
,I/Zygote  (  319): Process 8185 exited due to signal (7)
,I/EventHub(  901): Removing device '/dev/input/event4' due to inotify event
,F/libc    ( 7035): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7764ea00 in tid 7035 (om.sec.spp.push)
,F/libc    ( 7035): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2135): File locking failed. error= Bad file number
,I/EventHub(  901): Removing device '/dev/input/event5' due to inotify event
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ActivityManager(  901): Process com.sec.spp.push (pid 7035)(adj 0) has died(216,559)
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,I/Zygote  (  319): Process 7035 exited due to signal (7)
,I/EventHub(  901): Removing device '/dev/input/event6' due to inotify event
,E/Zygote  ( 8201): MountEmulatedStorage()
E/Zygote  ( 8201): v2
I/libpersona( 8201): KNOX_SDCARD checking this for 10037
I/libpersona( 8201): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8201 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/EventHub(  901): Removing device '/dev/input/event7' due to inotify event
,I/SELinux ( 8201): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  901): stay LED for fully charged
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/SELinux ( 8201): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/MotionRecognitionService(  901):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,E/SELinux ( 8201): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/EventHub(  901): Removing device '/dev/input/event8' due to inotify event
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3217): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3217): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 8201): TimaSignature is unavailable
,D/ActivityThread( 8201): Added TimaKeyStore provider
,I/EventHub(  901): Removing device '/dev/input/event9' due to inotify event
,D/ResourcesManager( 8201): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/ContextImpl( 8201): Unable to create files subdir /data/data/com.sec.spp.push/cache
,E/ActivityThread( 8201): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8201): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb3b0b27d in tid 8201 (moteNotiProcess)
,F/libc    ( 8201): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2135): File locking failed. error= Bad file number
,I/ActivityManager(  901): Process com.sec.spp.push:RemoteNotiProcess (pid 8201)(adj 0) has died(216,559)
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,I/EventHub(  901): Removing device '/dev/input/event10' due to inotify event
,E/Zygote  ( 8216): MountEmulatedStorage()
,E/Zygote  ( 8216): v2
I/libpersona( 8216): KNOX_SDCARD checking this for 10041
I/libpersona( 8216): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8216 uid=10041 gids={50041, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/EventHub(  901): Removing device '/dev/input/event11' due to inotify event
,I/Zygote  (  319): Process 8201 exited due to signal (7)
,I/SELinux ( 8216): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8216): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8216): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8216): TimaSignature is unavailable
,D/ActivityThread( 8216): Added TimaKeyStore provider
,D/ResourcesManager( 8216): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 8216): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8216): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ContextImpl( 8216): Unable to create files subdir /data/data/com.samsung.android.sdk.samsunglink/cache
,E/ActivityThread( 8216): Unable to setupGraphicsSupport due to missing cache directory
,D/AndroidRuntime( 8216): Shutting down VM
,F/libc    ( 8216): Fatal signal 7 (SIGBUS), code 2, fault addr 0x72800151 in tid 8216 (sdk.samsunglink)
,F/libc    ( 8216): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2135): File locking failed. error= Bad file number
,I/ActivityManager(  901): Process com.samsung.android.sdk.samsunglink (pid 8216)(adj 0) has died(216,559)
,I/SA      ( 6749): [SUR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6749): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10191 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,F/libc    ( 1804): Fatal signal 7 (SIGBUS), code 2, fault addr 0x772a2dd4 in tid 1804 (d.process.acore)
,F/libc    ( 1804): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2135): File locking failed. error= Bad file number
,I/Zygote  (  319): Process 8216 exited due to signal (7)
,I/ActivityManager(  901): Process android.process.acore (pid 1804)(adj 0) has died(221,560)
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8231): MountEmulatedStorage()
E/Zygote  ( 8231): v2
I/libpersona( 8231): KNOX_SDCARD checking this for 10047
I/libpersona( 8231): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=8231 uid=10047 gids={50047, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a

```
