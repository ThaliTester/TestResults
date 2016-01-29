#### Test 56818254e6f5c3b_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
D/Compatibility( 7082): onHandleIntent()
D/Compatibility( 7082): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10191, android.intent.extra.user_handle=0}]
D/Compatibility( 7082): found: 2
I/UpdateIcingCorporaServi( 1568): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 7082): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7082): skipping ResolveInfo{b8dea97 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7082): considering ResolveInfo{30b11484 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7082): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7082): enabling receiver ResolveInfo{11be246d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7082): enabling receiver ResolveInfo{165ce8a2 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7082): enabling receiver ResolveInfo{23bc9933 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
--------- beginning of system
W/ContextImpl( 6032): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
D/Compatibility( 7082): enabling receiver ResolveInfo{1e6cf4f0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7082): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7106): MountEmulatedStorage()
E/Zygote  ( 7106): v2
I/libpersona( 7106): KNOX_SDCARD checking this for 10097
I/libpersona( 7106): KNOX_SDCARD not a persona
I/ActivityManager(  863): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7106 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ResourcesManager( 1568): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/UpdateIcingCorporaServi( 1568): UpdateCorporaTask done [took 66 ms] updated apps [took 66 ms] 
I/SELinux ( 7106): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7106): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7106): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager(  863): Killing 5922:com.sec.android.widgetapp.dualclockdigital/u0a102 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7106): TimaSignature is unavailable
D/ActivityThread( 7106): Added TimaKeyStore provider
E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
D/ResourcesManager( 7106): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/libprocessgroup(  863): failed to open /acct/uid_10102/pid_5922/cgroup.procs: No such file or directory
D/DocsApplication( 7106): Installing DEX configuration.
D/DexInstaller( 7106): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7106): Provided clientMode=RELEASE, packageInfo=PackageInfo{3aecd116 com.google.android.apps.docs}
D/TAG     ( 7106): onCreate()
D/CrossAppStateProvider( 7106): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 7123): 
D/AndroidRuntime( 7123): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7123): CheckJNI is OFF
D/AndroidRuntime( 7123): setted country_code = Poland
D/AndroidRuntime( 7123): setted countryiso_code = PL
D/AndroidRuntime( 7123): setted sales_code = XEO
D/AndroidRuntime( 7123): readGMSProperty: start
D/AndroidRuntime( 7123): readGMSProperty: already setted!!
D/AndroidRuntime( 7123): readGMSProperty: end
D/AndroidRuntime( 7123): addProductProperty: start
E/AffinityControl( 7123): AffinityControl: registerfunction enter
D/AndroidRuntime( 7123): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  863): inState():  stateMachine is null !!
V/ApplicationPolicy(  863): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  863): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  863): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  863): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 863  pkgName : ACTIVITY_RESUME_BOOSTER@6
E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
W/ActivityManager(  863): mDVFSHelper.acquire()
I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=404, Starting com.test.thalitest
I/SQLiteSecureOpenHelper( 3484): getWritableDatabase(pwd)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SQLiteSecureOpenHelper( 3484): getDatabaseLocked(b,b,pwd)...
I/DBG_DM  ( 3682): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/DBG_DM  ( 3682): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 47
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/AndroidRuntime( 7123): Shutting down VM
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/DBG_DM  ( 3682): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/DBG_DM  ( 3682): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3682): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3682): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
I/DBG_DM  ( 3682): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
I/DBG_DM  ( 3682): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/DBG_DM  ( 3682): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 3682): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/LightsService(  863): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 863) 
D/LightsService(  863): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  863): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  863): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SecContentProvider2(  863): uri = 14 selection = getSealedState
D/SecContentProvider2(  863): mCursor = null
D/SecContentProvider2(  863): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1181): Icon Only
D/ApplicationPolicy(  863): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  863): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager(  863): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 3682): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
I/DBG_DM  ( 3682): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 3682): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 3682): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/PanelView( 1181): There is/are notification(s) 
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
D/PanelView( 1181): There is/are notification(s) 
E/Zygote  ( 7146): MountEmulatedStorage()
I/libpersona( 7146): KNOX_SDCARD checking this for 10191
E/Zygote  ( 7146): v2
I/libpersona( 7146): KNOX_SDCARD not a persona
I/ActivityManager(  863): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7146 uid=10191 gids={50191, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7146): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7146): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7146): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7146): TimaSignature is unavailable
D/ActivityThread( 7146): Added TimaKeyStore provider
I/art     ( 1181): Explicit concurrent mark sweep GC freed 54232(2MB) AllocSpace objects, 5(296KB) LOS objects, 30% free, 36MB/52MB, paused 547us total 92.058ms
V/ActivityManager(  863): Display changed displayId=0
V/BitmapFactory( 1181): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/StatusBarManagerService(  863): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
V/BitmapFactory( 1181): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/KnoxNotification( 1181): ----- inflateViews : modified publicViewLocal -----
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager( 7146): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/KnoxNotification( 1181): ----- inflateViews : modified KnoxViewLocal -----
D/PersonaManager( 1181): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1181): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@3c42e58e
D/SecContentProvider2(  863): uri = 14 selection = getSealedState
D/SecContentProvider2(  863): mCursor = null
D/SecContentProvider2(  863): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1181): Icon Only
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): There is/are notification(s) 
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
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
I/WebViewFactory( 7146): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7146): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/LibraryLoader( 7146): Loading: webviewchromium
I/LibraryLoader( 7146): Time to load native libraries: 3 ms (timestamps 7253-7256)
I/LibraryLoader( 7146): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
V/WebViewChromiumFactoryProvider( 7146): Binding Chromium to main looper Looper (main, tid 1) {23bc9933}
I/LibraryLoader( 7146): Expected native library version number "",actual native library version number ""
I/chromium( 7146): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7146): Initializing chromium process, renderers=0
W/art     ( 7146): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/chromium( 7146): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7146): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7146): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/Adreno-EGL( 7146): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7146): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7146): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7146): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7146): Remote Branch: 
I/Adreno-EGL( 7146): Local Patches: 
I/Adreno-EGL( 7146): Reconstruct Branch: 
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/chromium( 7146): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/chromium( 7146): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7146): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7146): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/SystemWebViewEngine( 7146): CordovaWebView is running on device made by: samsung
W/art     ( 7146): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7146): Attempt to remove local handle scope entry from IRT, ignoring
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
D/Activity( 7146): performCreate Call secproduct feature valuefalse
D/Activity( 7146): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
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
D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/GAV2    ( 7106): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/Zygote  ( 7200): MountEmulatedStorage()
I/libpersona( 7200): KNOX_SDCARD checking this for 10098
E/Zygote  ( 7200): v2
I/libpersona( 7200): KNOX_SDCARD not a persona
I/ActivityManager(  863): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7200 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SELinux ( 7200): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7200): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7200): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/OpenGLRenderer( 7146): Render dirty regions requested: true
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/TimaKeyStoreProvider( 7200): TimaSignature is unavailable
D/ActivityThread( 7200): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager( 7200): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
W/ResourcesManager( 7200): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityManager(  863): post active user change for 0
D/KnoxTimeoutHandler(  863): postActiveUserChange for user 0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/KnoxTimeoutHandler(  863): handleActiveUserChange for user 0
E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
I/SurfaceFlinger(  257): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
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
I/OpenGLRenderer( 7146): Initialized EGL, version 1.4
I/OpenGLRenderer( 7146): HWUI protection enabled for context ,  &this =0xb3a31ba0 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7146): Enabling debug mode 0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/[CarMode]( 7200): [DLApplication]-onCreate: Applicatino Started!
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/SampleAppCoreManager( 7200): SampleAppCoreManager VACVersion '2.2.0.11867'
I/VlingoAndroidCore( 7200): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/InputMethodManagerService(  863): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  863): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7223 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
E/Zygote  ( 7223): MountEmulatedStorage()
E/Zygote  ( 7223): v2
I/libpersona( 7223): KNOX_SDCARD checking this for 10032
I/libpersona( 7223): KNOX_SDCARD not a persona
I/ActivityManager(  863): Displayed com.test.thalitest/.MainActivity: +851ms
W/ContextImpl(  863): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Adreno-ES20( 7146): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7146): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
I/SELinux ( 7223): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SELinux ( 7223): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7223): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/9)
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/Timeline( 7146): Timeline: Activity_idle id: android.os.BinderProxy@834be52 time:87888
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/JsMessageQueue( 7146): Set native->JS mode to OnlineEventsBridgeMode
D/CustomFrequencyManagerService(  863): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 863  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  863): mDVFSHelper.release()
I/Timeline(  863): Timeline: Activity_windows_visible id: ActivityRecord{da77b61 u0 com.test.thalitest/.MainActivity t10} time:87902
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/CustomFrequencyManagerService(  863): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 863  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/TimaKeyStoreProvider( 7223): TimaSignature is unavailable
D/ActivityThread( 7223): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager( 7223): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/ResourcesManager( 7223): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  863): CMD_RSSI_POLL : out!
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/GAV2    ( 7106): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  863): Killing 5681:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/jxcore_app_log( 7146): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359494784
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/System.out( 7223): Inside onCreate() of WakeupTriggerProvide
I/System.out( 7223): Inside WakeupProvider
E/DatabaseUtils( 7223): Writing exception to parcel
E/DatabaseUtils( 7223): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7223): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7223): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7223): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7223): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7223): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7223): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7223): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7223): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7223): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7223): 	at android.os.Binder.execTransact(Binder.java:446)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/System.err( 7200): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/libprocessgroup(  863): failed to open /acct/uid_10112/pid_5681/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
W/System.err( 7200): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7200): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7200): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7200): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7200): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7200): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7200): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7200): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7200): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7200): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7200): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7200): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7200): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7200): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7200): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7200): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7200): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7200): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7200): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7200): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7200): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/System.err( 7200): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7200): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7200): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7200): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7200): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7200): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7200): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7200): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7200): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7200): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/VlingoApplication( 7223): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
E/DatabaseUtils( 7223): Writing exception to parcel
E/DatabaseUtils( 7223): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7223): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7223): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7223): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7223): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7223): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7223): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7223): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7223): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7223): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7223): 	at android.os.Binder.execTransact(Binder.java:446)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/System.err( 7200): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/System.err( 7200): 	at android.os.Parcel.readException(Parcel.java:1546)
I/SurfaceFlinger(  257): id=15 Removed Starting com.test.thalitest (6/8)
W/System.err( 7200): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
I/SurfaceFlinger(  257): id=15 Removed Starting com.test.thalitest (-2/8)
W/System.err( 7200): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7200): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7200): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7200): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7200): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7200): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/System.err( 7200): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7200): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7200): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7200): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7200): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7200): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7200): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 7200): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7200): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7200): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7200): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7200): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7200): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7200): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7200): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7200): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7200): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7200): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7200): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7200): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/[CarMode]( 7200): [DLApplication]-Init Called!:false
E/[CarMode]( 7200): [DLApplication]-Init Started!:true
I/[CarModeFW]( 7200): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7200): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7200): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7200): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7200): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7200): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7200): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7200): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7200): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7200): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7200): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7200): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7200): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7200): ### com.android.internal.os.ZygoteInit::main(1194)
I/VlingoAndroidCore( 7223): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/MessageDataHandler( 7200): initialize
D/[CarModeFW]( 7200): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 7200): CDH-initiazlieCaches : after sync
D/[CarModeFW]( 7200): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7200): CDH-ContactDataHandler initiazlieCaches time : 27
D/[CarModeFW]( 7200): CDH-initiazlieCaches : end sync
I/chromium( 7146): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7146): 
I/chromium( 7146): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/[CarModeFW]( 7200): DrivingManager-initialize...
I/SensorService(  863): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  863): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  863): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
D/VlingoApplication( 7223): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 7223): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
D/CustomFrequencyManagerService(  863): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 863  tag : ACTIVITY_RESUME_BOOSTER@10
E/LightSensor(  863): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
I/MediaPlayer( 7200): Need to enable context aware info
V/MediaPlayer-JNI( 7200): native_setup
V/MediaPlayer( 7200): constructor
V/MediaPlayer( 7200): setListener
E/MediaPlayer-JNI( 7200): QCMediaPlayer mediaplayer NOT present
D/[CarModeFW]( 7200): PushMessageManager-bindPushMessageService
I/[CarModeFW]( 7200): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode]( 7200): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarMode]( 7200): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 7200): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1454085742154
D/[CarModeFW]( 7200): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1454085742155
D/[CarModeFW]( 7200): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1454085742155
D/[CarModeFW]( 7200): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1454085742155
D/[CarModeFW]( 7200): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1454085742155
D/[CarModeFW]( 7200): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1454085742160
D/TP/SmsProvider( 1478): query,matched:2, calling pid = 7200
D/TP/SmsProvider( 1478): query,matched:2, calling pid = 7200
D/TP/SmsProvider( 1478): match 2:Elapsed time : 0.642 ms
D/TP/SmsProvider( 1478): match 2:Elapsed time : 2.460 ms
D/MessageDataHandler( 7200):  getInboxList smsCursor : 18
I/[CarMode]( 7200): [LogNotNull]-Package name is: com.google.android.apps.maps
E/[CarMode]( 7200): [DLApplication]-Init End!:true
D/[CarModeFW]( 7200): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7200): RecommendHandler-selection = type = '3'
D/TP/MmsProvider( 1478): Query uri=content://mms/inbox, match=2, calling pid = 7200
D/[CarModeFW]( 7200): CDH-buildContactCacheWireFrame : cur len =0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7264): MountEmulatedStorage()
E/Zygote  ( 7264): v2
I/libpersona( 7264): KNOX_SDCARD checking this for 10019
I/libpersona( 7264): KNOX_SDCARD not a persona
I/ActivityManager(  863): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7264 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
I/SELinux ( 7264): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7264): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7264): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/[CarModeFW]( 7200): CDH-buildContactCacheWireFrame : cur len =0
D/TimaKeyStoreProvider( 7264): TimaSignature is unavailable
D/ActivityThread( 7264): Added TimaKeyStore provider
D/MessageDataHandler( 7200):  getInboxList mmsCursor : 86
D/[CarModeFW]( 7200): RecommendHandler-selection = type = '3'
E/LightSensor(  863): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
D/MessageDataHandler( 7200):  getInboxList mms,sms cursor join : 13
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 7264): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
E/Zygote  ( 7279): MountEmulatedStorage()
E/Zygote  ( 7279): v2
I/libpersona( 7279): KNOX_SDCARD checking this for 10003
I/libpersona( 7279): KNOX_SDCARD not a persona
I/ActivityManager(  863): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7279 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
I/SELinux ( 7279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7279): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TP/MmsProvider( 1478): Query uri=content://mms, match=0, calling pid = 7200
D/TP/MmsSmsProvider( 1478): query,matched:0, calling pid = 7200
V/TP/MmsSmsProvider( 1478): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1478): match 0:Elapsed time : 1.764 ms
D/TP/MmsSmsProvider( 1478): query,matched:13, calling pid = 7200
D/TP/MmsSmsProvider( 1478): match 13:Elapsed time : 1.207 ms
D/TimaKeyStoreProvider( 7279): TimaSignature is unavailable
D/ActivityThread( 7279): Added TimaKeyStore provider
I/MessageDataHandler( 7200): getUnreadMessageCount :0
D/[CarModeFW]( 7200): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 201
D/[CarMode]( 7200): [DLApplication]-GooglePlayServices SUCCESS.
D/MessageDataHandler( 7200):  getInboxList address cursor : 21
D/TP/MmsSmsProvider( 1478): query,matched:0, calling pid = 7200
D/ResourcesManager( 7279): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
V/TP/MmsSmsProvider( 1478): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1478): match 0:Elapsed time : 1.345 ms
D/MessageDataHandler( 7200):  getInboxList thread cursor : 7
D/MessageDataHandler( 7200):  thread, addr result: 1
I/[CarModeFW]( 7200): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 220
I/[CarModeFW]( 7200): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7200): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 221
E/[CarMode]( 7200): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
I/UpdateManagerReceiver( 7200): Intent : android.intent.action.PACKAGE_ADDEDFri Jan 29 17:42:22 GMT+01:00 2016
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7294): MountEmulatedStorage()
E/Zygote  ( 7294): v2
I/libpersona( 7294): KNOX_SDCARD checking this for 1000
I/libpersona( 7294): KNOX_SDCARD not a persona
I/ActivityManager(  863): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7294 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  863): Killing 5944:com.sec.android.app.camera/u0a153 (adj 15): bgCount ##41
I/SELinux ( 7294): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7294): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7294): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/UserAnalysis.PlaceProvider( 7279): PlaceProvider onCreate()
E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
D/[CarModeFW]( 7200): PushMessageService-onCreate
I/ActivityManager(  863): Killing 6102:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
I/ActivityManager(  863): Killing 4686:com.android.calendar/u0a149 (adj 15): bgCount ##42
I/ActivityManager(  863): Killing 5698:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): bgCount ##43
D/TimaKeyStoreProvider( 7294): TimaSignature is unavailable
D/ActivityThread( 7294): Added TimaKeyStore provider
E/SMD     (  285): DCD ON
D/ResourcesManager( 7294): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
W/libprocessgroup(  863): failed to open /acct/uid_10153/pid_5944/cgroup.procs: No such file or directory
D/[CarModeFW]( 7200): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7200): PushMessageService-registerPushMessageServiceListener
W/ContextImpl( 7294): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7310): MountEmulatedStorage()
E/Zygote  ( 7310): v2
I/libpersona( 7310): KNOX_SDCARD checking this for 10111
I/libpersona( 7310): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7310 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/UserAnalysis.SecureDbManager( 7279): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 7279): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7279): Create SecureDbHelper
,I/SELinux ( 7310): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7310): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7310): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 7294): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/IntelligenceServiceApplication( 7279): onCreate()
,D/TimaKeyStoreProvider( 7310): TimaSignature is unavailable
,D/ActivityThread( 7310): Added TimaKeyStore provider
,I/SQLiteSecureOpenHelper( 7279): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7279): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7279): Open Place.db in secure mode
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/FilterInstaller( 7294): There is no requred permission
,I/ActivityManager(  863): Killing 6117:com.sec.android.app.sns3/u0a35 (adj 15): bgCount ##41
,I/SQLiteSecureOpenHelper( 7279): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7279): ...getDatabaseLocked(b,b,pwd)
,I/art     (  863): Explicit concurrent mark sweep GC freed 192485(12MB) AllocSpace objects, 6(4MB) LOS objects, 30% free, 36MB/52MB, paused 1.436ms total 103.236ms
,D/[CarModeFW]( 7200): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 7200): MyPlaceProvider-=============
D/[CarModeFW]( 7200): MyPlaceProvider-=============
D/[CarModeFW]( 7200): MyPlaceProvider-=============
D/[CarModeFW]( 7200): MyPlaceProvider-=============
D/[CarModeFW]( 7200): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7200): MyPlaceProvider-==============
D/[CarModeFW]( 7200): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 571
D/[CarModeFW]( 7200): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7200): MyPlaceProvider-==============
D/[CarModeFW]( 7200): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7200): MyPlaceProvider-==============
D/[CarModeFW]( 7200): MyPlaceProvider-latitude is not valid
I/[CarModeFW]( 7200): -[snowdeer] Rec : Missed Call : 458
D/[CarModeFW]( 7200): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 580
W/libprocessgroup(  863): failed to open /acct/uid_10149/pid_4686/cgroup.procs: No such file or directory
D/[CarMode]( 7200): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@6dd77b8f, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@bd9271d9] LOCATIONS
,W/libprocessgroup(  863): failed to open /acct/uid_10148/pid_5698/cgroup.procs: No such file or directory
,W/libprocessgroup(  863): failed to open /acct/uid_1000/pid_6102/cgroup.procs: No such file or directory
,I/[CarModeFW]( 7200): -[snowdeer] Rec : Favorite : 21
,I/[CarModeFW]( 7200): -[snowdeer] Rec : CallLog : 5
,D/ResourcesManager( 7310): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/[CarModeFW]( 7200): -[snowdeer] Rec : Schedule : 20
,I/[CarModeFW]( 7200): -[snowdeer] Rec : During DL app : 4
,W/libprocessgroup(  863): failed to open /acct/uid_10035/pid_6117/cgroup.procs: No such file or directory
,D/PackageIntentReceiver( 7310): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7310): Not GearManger package! 
,I/[CarModeFW]( 7200): -[snowdeer] Rec : Location Sharing : 3
,I/[CarModeFW]( 7200): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 7200): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7200): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
,I/[CarModeFW]( 7200): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
I/[CarModeFW]( 7200): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 7200): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 632
,I/[CarModeFW]( 7200): -[snowdeer] Rec : getContactListFromHashMap - core : 0
,I/[CarModeFW]( 7200): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7200): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7200): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 633
,E/Zygote  ( 7327): MountEmulatedStorage()
E/Zygote  ( 7327): v2
I/libpersona( 7327): KNOX_SDCARD checking this for 10117
I/libpersona( 7327): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7327 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  863): Killing 6147:com.sec.spp.push:RemoteDlcProcess/u0a37 (adj 15): bgCount ##41
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/SELinux ( 7327): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7327): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7327): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7327): TimaSignature is unavailable
,D/ActivityThread( 7327): Added TimaKeyStore provider
,W/libprocessgroup(  863): failed to open /acct/uid_10037/pid_6147/cgroup.procs: No such file or directory
,D/ResourcesManager( 7327): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 7327): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/MagazineService Version( 7327): Magazine-Administrator: 11
,D/MagazineService Version( 7327): Magazine-Provider: 14
,D/MagazineService Version( 7327): Magazine-Channel: 14
,D/HeadlinesChannelApplication( 7327): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7327): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7327): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 7343): MountEmulatedStorage()
E/Zygote  ( 7343): v2
I/libpersona( 7343): KNOX_SDCARD checking this for 1000
I/libpersona( 7343): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7343 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7327): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/art     (  317): Explicit concurrent mark sweep GC freed 8753(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 273us total 14.574ms
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 9.225ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 243us total 8.002ms
,I/SELinux ( 7343): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7343): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7343): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  863): Killing 6166:com.sec.spp.push:RemoteNotiProcess/u0a37 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7343): TimaSignature is unavailable
D/ActivityThread( 7343): Added TimaKeyStore provider
,D/ResourcesManager( 7343): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  863): failed to open /acct/uid_10037/pid_6166/cgroup.procs: No such file or directory
,E/Zygote  ( 7358): MountEmulatedStorage()
E/Zygote  ( 7358): v2
I/libpersona( 7358): KNOX_SDCARD checking this for 1000
I/libpersona( 7358): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7358 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  863): Killing 6346:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/SELinux ( 7358): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7358): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7358): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7358): TimaSignature is unavailable
,D/ActivityThread( 7358): Added TimaKeyStore provider
,D/ResourcesManager( 7358): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,W/libprocessgroup(  863): failed to open /acct/uid_1000/pid_6346/cgroup.procs: No such file or directory
,I/System.out( 7223): INFO:Resource not found:/Common.properties Using default values
,D/AcmsPackageEventListener( 7358): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 7358): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService( 7358): Enter Oncreate
,D/AcmsServiceMonitor( 7358): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 7358): creating AcmsCore
D/AcmsCore( 7358): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7358): AcmsCore
,D/AcmsCore( 7358): init
,D/AcmsCore( 7358): Looper handler is not null
D/AcmsCore( 7358): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7358): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7358): Incrementing - Counter value: 1
D/AcmsCore( 7358): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsCertificateMngr( 7358): AcmsCertificateMngr
,D/AcmsRevocationMngr( 7358): AcmsRevocationMngr
,D/AcmsService( 7358): onStartCommand
D/AcmsService( 7358): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 7358): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7358): Incrementing - Counter value: 2
D/AcmsService( 7358): Incremented Counter Value : onStartCommand
,D/ActivityThread( 7358): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsService( 7358): Inside handle Intent
D/AcmsService( 7358): App added - package name: com.test.thalitest
D/AcmsCore( 7358): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7358): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7358): Incrementing - Counter value: 3
D/AcmsCore( 7358): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7358): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7358): Decrementing - Counter value: 2
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7378): MountEmulatedStorage()
E/Zygote  ( 7378): v2
I/libpersona( 7378): KNOX_SDCARD checking this for 10165
I/libpersona( 7378): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7378 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7378): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7378): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7378): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 7146): Initializing JXcore engine
W/jxcore-log( 7146): JXcore engine is ready
,D/TimaKeyStoreProvider( 7378): TimaSignature is unavailable
,D/ActivityThread( 7378): Added TimaKeyStore provider
,D/ResourcesManager( 7378): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7378): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 7378): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7395): MountEmulatedStorage()
E/Zygote  ( 7395): v2
I/libpersona( 7395): KNOX_SDCARD checking this for 10169
I/libpersona( 7395): KNOX_SDCARD not a persona
,E/auditd  ( 2132): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  863): Got Modify Event and sending Denial Intent foraudit.log
,I/ActivityManager(  863): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7395 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
W/ContextImpl(  863): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,I/ActivityManager(  863): Killing 5805:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): bgCount ##41
,D/SecurityLogAgent:SEDenialService(  863): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,W/jxcore-log( 7146): Starting JXcore engine
,I/SELinux ( 7395): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7395): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7395): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7395): TimaSignature is unavailable
,D/ActivityThread( 7395): Added TimaKeyStore provider
,D/ResourcesManager( 7395): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 7395): (284) automatic index on shooting_modes(title_id)
,W/jxcore-log( 7146): Platform android
W/jxcore-log( 7146): 
W/jxcore-log( 7146): Process ARCH arm
W/jxcore-log( 7146): 
,W/libprocessgroup(  863): failed to open /acct/uid_10157/pid_5805/cgroup.procs: No such file or directory
,D/Finsky  ( 6506): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/ActivityManager(  863): Killing 4741:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,D/PackageBroadcastService( 2490): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2490): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2490): Loading module APK com.google.android.play.games
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 2490): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,W/libprocessgroup(  863): failed to open /acct/uid_10045/pid_4741/cgroup.procs: No such file or directory
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/ChimeraCfgMgr( 2490): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2490): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2490): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 2490): Submit a task: k
,D/ChimeraCfgMgr( 2490): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 2490): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2490): Processing package: com.test.thalitest
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,D/GassUtils( 2490): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
D/k       ( 2490): Found info for package com.test.thalitest in db.
,E/Zygote  ( 7418): MountEmulatedStorage()
E/Zygote  ( 7418): v2
I/libpersona( 7418): KNOX_SDCARD checking this for 10039
I/libpersona( 7418): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7418 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/jxcore-log( 7146): JXcore Cordova bridge is ready!
I/jxcore-log( 7146): 
,W/jxcore-log( 7146): JXcore engine is started
,I/SELinux ( 7418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7418): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/TimaKeyStoreProvider( 7418): TimaSignature is unavailable
,D/ActivityThread( 7418): Added TimaKeyStore provider
,D/ResourcesManager( 7418): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,W/BaseAppContext( 2490): Using Auth Proxy for data requests.
W/BaseAppContext( 2490): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 2490): cleanUpNonGplusAccounts done.
,W/BaseAppContext( 2490): Using Auth Proxy for data requests.
,W/BaseAppContext( 2490): Using Auth Proxy for data requests.
,W/BaseAppContext( 2490): Using Auth Proxy for data requests.
,W/BaseAppContext( 2490): Using Auth Proxy for data requests.
,W/BaseAppContext( 2490): Using Auth Proxy for data requests.
,I/jxcore-log( 7146): Toggling radios to true
I/jxcore-log( 7146): 
,D/BluetoothAdapter( 7146): enable()
,D/BluetoothAdapter( 7146): enable(): BT is already enabled..!
,D/WifiService(  863): New client listening to asynchronous messages
,I/WifiManager( 7146): packageName : com.test.thalitest
,D/SecContentProvider(  863): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  863): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  863): mCursor = null
,D/WifiService(  863): setWifiEnabled: true pid=7146, uid=10191
E/WifiService(  863): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  863): Permission Denial: getCurrentUser() from pid=7146, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  863): Failed getting userId using ActivityManagerNative
W/WifiService(  863): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7146, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  863): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  863): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  863): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  863): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  863): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  863): name = wifi_on
,I/WifiService(  863): disconnect: pid=7146, uid=10191
,I/wpa_supplicant( 1295): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7146): Radios toggled
I/jxcore-log( 7146): 
,I/jxcore-log( 7146): My device name is: samsung-SM-G900F
I/jxcore-log( 7146): 
,I/wpa_supplicant( 1295): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1295): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1295): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1295): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine(  863): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1295): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1295): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1295): Disconnected - do not scan
,I/wpa_supplicant( 1295): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  863): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  863): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  863): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  863): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TaskPersister(  863): removeObsoleteFile: deleting file=9_task_thumbnail.png
,E/WifiStateMachine(  863): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  863): InactiveState{ what=143375 }
,D/WifiP2pService(  863): P2pEnabledState{ what=143375 }
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NativeCrypto( 2226): Read error: ssl=0x9b42be00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2226): SSL shutdown failed: ssl=0x9b42be00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  863): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityService(  863): updateNetworkInfo()
D/ConnectivityService(  863): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  863): updateNetworkInfo()
D/ConnectivityService(  863): ignoring duplicate network state non-change
,D/ConnectivityService(  863): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/ConnectivityService(  863): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,E/WifiConfigStore(  863): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller(  863): evaluateTrafficStatsPolling
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  863): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  863): DefaultState{ when=-6ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  863): External Intent Received android.net.wifi.STATE_CHANGE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  863): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  863): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  863): Validated
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  863): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1295): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1295): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1295): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1295): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1295): First Scan Start
,D/StatusBar.NetworkController( 1181): applyOpen
I/wpa_supplicant( 1295): Scan requested (ret=0) - scan timeout 30 seconds
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,I/ActivityManager(  863): Killing 6047:com.google.android.talk/u0a116 (adj 15): bgCount ##41
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/WifiStateMachine(  863): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  863): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  863): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  863): InactiveState{ what=143375 }
D/WifiP2pService(  863): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/BootupListener( 1478): ACTION_DRIVELINK
,D/SettingsProvider(  863): name = drivelink_navigation
D/SettingsProvider(  863): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  863): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  863): selectionArgs: false
D/SettingsProvider(  863): selectionArgs: 1001
D/SecContentProvider(  863): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  863): ret = -1
,D/BootupListener( 1478): NAVI : com.google.android.apps.maps
D/SettingsProvider(  863): name = internet_call_settings_visibility
D/SettingsProvider(  863): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  863): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  863): selectionArgs: false
D/SettingsProvider(  863): selectionArgs: 1001
D/SecContentProvider(  863): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  863): ret = -1
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7441): MountEmulatedStorage()
E/Zygote  ( 7441): v2
I/libpersona( 7441): KNOX_SDCARD checking this for 1000
I/libpersona( 7441): KNOX_SDCARD not a persona
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/ConnectivityService(  863): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  863): calling update connectivity
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/EntConnectivity(  863): Not allowed due to - mEnabled false
D/ConnectivityService(  863): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
I/ActivityManager(  863): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7441 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  863): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  863): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  863): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  863): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  863): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  863): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  863): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  863): Disconnected - quitting
,D/WifiStateMachine(  863): updateConfiguredNetworkExpiration - currTime: 1454085744416
D/WifiStateMachine(  863): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,E/WifiStateMachine(  863): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  863): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiNetworkAgent(  863): NetworkAgent: NetworkAgent channel lost
I/WifiTrafficPoller(  863): evaluateTrafficStatsPolling
,D/CSLegacyTypeTracker(  863): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  863): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,I/CLocInfoService(  863): External Intent Received android.net.wifi.STATE_CHANGE
D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  863): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  863): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  863): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,E/WifiStateMachine(  863): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  863): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  863): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  863): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  863): mCursor = null
,D/SmartBondingService(  863): getSBEnabled() enabled =false
,D/SmartBondingService(  863): getSBEnabled() enabled =false
D/SmartBondingService(  863): getSBEnabled() enabled =false
V/NetworkStats(  863): updateIfacesLocked()
E/ConnectivityService(  863): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NtpTrustedTime(  863): currentTimeMillis() cache hit
V/NetworkStats(  863): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  863): UpdateStatsForKnox
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/SecContentProvider2(  863): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  863): mCursor = null
,I/SELinux ( 7441): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
V/NetworkStats(  863): performPollLocked() took 8ms
D/NtpTrustedTime(  863): currentTimeMillis() cache hit
I/SELinux ( 7441): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524292
E/SELinux ( 7441): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 1478): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  863): currentTimeMillis() cache hit
,D/NtpTrustedTime(  863): currentTimeMillis() cache hit
D/NtpTrustedTime(  863): currentTimeMillis() cache hit
,V/NetworkStats(  863): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  863): currentTimeMillis() cache hit
D/SmartBondingService(  863): getNetworkEnabled : wifi : true mobile : true
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/NtpTrustedTime(  863): currentTimeMillis() cache hit
D/NtpTrustedTime(  863): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 7441): TimaSignature is unavailable
,D/ActivityThread( 7441): Added TimaKeyStore provider
,W/libprocessgroup(  863): failed to open /acct/uid_10116/pid_6047/cgroup.procs: No such file or directory
,D/ResourcesManager( 7441): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/SecurityLogAgent( 7441):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7441):  SeDenialReceiver : File path = null
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,I/ActivityManager(  863): Killing 6401:com.samsung.android.app.FileShareServer/u0a74 (adj 15): bgCount ##41
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,I/Hs20UtilService( 1313): Starting #6
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 1313): Starting #7
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,W/libprocessgroup(  863): failed to open /acct/uid_10074/pid_6401/cgroup.procs: No such file or directory
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/AcmsKeyStoreHelper( 7358):  getKeyStoreForApplication Enter
,W/art     ( 2490): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 139.630ms
,I/AcmsKeyStoreHelper( 7358): Key Store exist
I/AcmsKeyStoreHelper( 7358): Hence loading the keystore file
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/AcmsKeyStoreHelper( 7358):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 7358): getKeyStoreForApplication success 
D/AcmsCore( 7358): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7358): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7358): Decrementing - Counter value: 1
D/AcmsCore( 7358): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 7358): This is NOT a valid MirrorLink app
D/AcmsCore( 7358): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7358): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7358): Decrementing - Counter value: 0
,D/AcmsServiceMonitor( 7358): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7358): getSvcCounter - Counter value: 0
D/AcmsService( 7358): Enter onDestroy
I/AcmsService( 7358): cleanUp(): inside service clean up
D/AcmsCore( 7358): AcmsCore: inside DeInit
D/AcmsCore( 7358): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7358): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 7358): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7358): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7358): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7358): getSvcCounter - Counter value: 0
D/AcmsService( 7358): killing acms process
I/Process ( 7358): Sending signal. PID: 7358 SIG: 9
,I/ActivityManager(  863): Process ACMS.Process (pid 7358)(adj 0) has died(54,570)
,D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ChimeraCfgMgr( 2490): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2490): Module APK com.google.android.play.games already loaded
,I/ApplicationPolicy(  863): updateDataUsageMap
,D/Tethering(  863): MasterInitialState.processMessage what=3
D/SmartBondingService(  863): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  863): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  863): getSBEnabled() enabled =false
D/SmartBondingService(  863): getSBEnabled() enabled =false
D/SmartBondingService(  863): getSBEnabled() enabled =false
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  863): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  863): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  863): CLoinfo wifi false
,W/SLocation(  863): No Active Data Connection
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 1971): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SystemBroadcastReceiver( 6232): [#DCM#] [DCM_Performance] onReceive completed in time  5374 microsec. 
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6186): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3682): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/PCWCLIENTTRACE_PushUtil( 7007): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7007): sales region : global
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PCWCLIENTTRACE_PushUtil( 7007): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7007): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/DBG_DM  ( 3682): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/SystemBroadcastReceiver( 6232): [#DCM#] Calling notifyListeners. 
,I/DCMController( 6232): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 6232): [#DCM#] setIsConnectedForExtractors 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7007): noConnectivity : true
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7478): MountEmulatedStorage()
E/Zygote  ( 7478): v2
I/libpersona( 7478): KNOX_SDCARD checking this for 10002
I/libpersona( 7478): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7478 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ContextImpl(  863): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 7478): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7478): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7478): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7478): TimaSignature is unavailable
,D/ActivityThread( 7478): Added TimaKeyStore provider
,D/ResourcesManager( 7478): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  863): Killing 6419:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7495): MountEmulatedStorage()
,E/Zygote  ( 7495): v2
I/libpersona( 7495): KNOX_SDCARD checking this for 1000
I/libpersona( 7495): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7495 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7495): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7495): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7495): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Icing   ( 2490): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,D/TimaKeyStoreProvider( 7495): TimaSignature is unavailable
,D/ActivityThread( 7495): Added TimaKeyStore provider
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 7495): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  863): failed to open /acct/uid_1000/pid_6419/cgroup.procs: No such file or directory
,D/ResourcesManager( 2490): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/DIAGMON_AGENT( 7495): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7495): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/Icing   ( 2490): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,I/DIAGMON_AGENT( 7495): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7495): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7495): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7495): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7511): MountEmulatedStorage()
E/Zygote  ( 7511): v2
I/libpersona( 7511): KNOX_SDCARD checking this for 10010
I/libpersona( 7511): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7511 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7511): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7511): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7511): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1295): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 1295): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1295): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1295): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1295): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  863): [1,454,085,745,439 ms] noteScanEnd no scan source
,E/WifiStateMachine(  863): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1481cf6a sup_state=SCANNING debouncing=false
,I/CLocInfoService(  863): External Intent Received android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine(  863): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  863): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  863): setDetailed state send new extra info0x
,D/SecContentProvider2(  863): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  863): mCursor = null
,D/TimaKeyStoreProvider( 7511): TimaSignature is unavailable
,D/ActivityThread( 7511): Added TimaKeyStore provider
,D/ResourcesManager( 7511): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,E/SMD     (  285): DCD ON
,I/ActivityManager(  863): Killing 6464:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/FOTA_Client( 7511): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/FOTA_Client( 7511): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/wpa_supplicant( 1295): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 1295): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1295): Associated with C0.AA.48
,E/WifiStateMachine(  863): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  863): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  863): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  863): mCursor = null
,I/FOTA_Client( 7511): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1295): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1295): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  863): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  863): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  863): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  863): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  863): mCursor = null
,E/Zygote  ( 7526): MountEmulatedStorage()
,E/Zygote  ( 7526): v2
I/libpersona( 7526): KNOX_SDCARD checking this for 10018
I/libpersona( 7526): KNOX_SDCARD not a persona
I/wpa_supplicant( 1295): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1295): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1295): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1295): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1295): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 1295): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/ActivityManager(  863): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7526 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
I/wpa_supplicant( 1295): Blacklist: Clear (temp) 
I/wpa_supplicant( 1295): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/ActivityManager(  863): Killing 5789:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,E/WifiStateMachine(  863): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  863): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  863): Network connection established
,D/WifiNative-HAL(  863): callSECApiVoid - ID [50]
,E/WifiStateMachine(  863): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  863): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService(  863): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  863): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/ConnectivityService(  863): updateNetworkInfo()
D/ConnectivityService(  863): Got NetworkAgent Messenger
E/WifiStateMachine(  863): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  863): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine(  863): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  863): NetworkAgent connected
E/WifiConfigStore(  863): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/CLocInfoService(  863): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  863): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  863): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  863): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  863): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/SELinux ( 7526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SELinux ( 7526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7526): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  863): failed to open /acct/uid_1000/pid_6464/cgroup.procs: No such file or directory
,D/CommandListener(  280): Setting iface cfg
,E/WifiStateMachine(  863): Start Dhcp Watchdog 2
,D/SecContentProvider2(  863): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  863): mCursor = null
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  863): calculateWifiScore() report new score 60
I/WifiStateMachine(  863): calculateWifiScore : sendNetworkScore in!
,I/WifiStateMachine(  863): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  863): CMD_RSSI_POLL : out!
,D/ConnectivityService(  863): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,D/TimaKeyStoreProvider( 7526): TimaSignature is unavailable
,D/ActivityThread( 7526): Added TimaKeyStore provider
,E/WifiStateMachine(  863): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  863): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  863): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/SecContentProvider2(  863): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  863): mCursor = null
,D/ResourcesManager( 7526): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/libprocessgroup(  863): failed to open /acct/uid_1000/pid_5789/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7526): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7526): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454085745617
,I/KLMS-2.4.503: ( 7526): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7526): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7526): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  863): Killing 6009:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7542): MountEmulatedStorage()
I/libpersona( 7542): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7542): v2
I/libpersona( 7542): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7542 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,E/WifiStateMachine(  863): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  863): do suspend false
,D/WifiP2pService(  863): InactiveState{ what=143375 }
,D/WifiP2pService(  863): P2pEnabledState{ what=143375 }
,I/SELinux ( 7542): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7542): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7542): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/TimaKeyStoreProvider( 7542): TimaSignature is unavailable
,D/ActivityThread( 7542): Added TimaKeyStore provider
,D/ResourcesManager( 7542): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7542): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5171): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 7044): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7044): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7044): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7044): [SLFUCHKMGR] constructor called
,W/libprocessgroup(  863): failed to open /acct/uid_10167/pid_6009/cgroup.procs: No such file or directory
,I/SA      ( 7044): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7044): [OR] == isSIMCardReady false ==
,I/SA      ( 7044): [SCU] == networkStateCheck == false
I/SA      ( 7044): [OR] onReceive END
,E/SPPClientService( 5171): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7559): MountEmulatedStorage()
,E/Zygote  ( 7559): v2
I/libpersona( 7559): KNOX_SDCARD checking this for 10070
I/libpersona( 7559): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7559 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  317): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 267us total 14.911ms
,I/SELinux ( 7559): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 243us total 7.678ms
,I/ActivityManager(  863): Killing 5969:com.google.android.gm/u0a113 (adj 15): bgCount ##41
,I/SELinux ( 7559): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7559): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 8.463ms
,D/TimaKeyStoreProvider( 7559): TimaSignature is unavailable
,D/ActivityThread( 7559): Added TimaKeyStore provider
,D/ResourcesManager( 7559): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7559): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7559): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7559): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/comsamsunglog( 7559): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7559): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7559): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7559): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7559): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7559): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7559): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7559): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  863): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  863): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  863): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  863): selectionArgs: false
D/SettingsProvider(  863): selectionArgs: 10070
D/SecContentProvider(  863): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  863): ret = -1
,W/libprocessgroup(  863): failed to open /acct/uid_10113/pid_5969/cgroup.procs: No such file or directory
,D/daemonapp( 1344): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/dhcpcd  ( 7576): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7576): version 5.5.6 starting
,E/dhcpcd  ( 7576): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/accuweather( 7559): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7559): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7559): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7559): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7559): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7559): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1344): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7559): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1344): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7559): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1344): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7559): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7559): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7583): MountEmulatedStorage()
,E/Zygote  ( 7583): v2
I/libpersona( 7583): KNOX_SDCARD checking this for 1000
I/libpersona( 7583): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7583 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/dhcpcd  ( 7576): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7576): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7576): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7576): bssid match
,I/ActivityManager(  863): Killing 6232:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,I/dhcpcd  ( 7576): wlan0: rebinding lease of 192.168.1.136
,I/SELinux ( 7583): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7583): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7583): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7583): TimaSignature is unavailable
,D/ActivityThread( 7583): Added TimaKeyStore provider
,D/ResourcesManager( 7583): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7583): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7583): premStatus:2
,I/KnoxUsageLogPro( 7583): isEulaShown : false
I/KnoxUsageLogPro( 7583): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,W/libprocessgroup(  863): failed to open /acct/uid_10004/pid_6232/cgroup.procs: No such file or directory
,E/Zygote  ( 7598): MountEmulatedStorage()
E/Zygote  ( 7598): v2
I/libpersona( 7598): KNOX_SDCARD checking this for 10087
I/libpersona( 7598): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7598 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  863): Killing 6295:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
,I/SELinux ( 7598): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7598): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7598): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7598): TimaSignature is unavailable
,D/ActivityThread( 7598): Added TimaKeyStore provider
,D/ResourcesManager( 7598): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  863): failed to open /acct/uid_10043/pid_6295/cgroup.procs: No such file or directory
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/ActivityManager(  863): Killing 6713:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
,D/Headlines( 5403): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5403): getCountryCode(): countryCode = PL
,D/Headlines( 5403): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
I/dhcpcd  ( 7576): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,D/HeadlinesCardManager( 5403): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5403): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5403): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5403): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5403): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5403): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7614): MountEmulatedStorage()
E/Zygote  ( 7614): v2
I/libpersona( 7614): KNOX_SDCARD checking this for 10127
I/libpersona( 7614): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7614 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 7576): wlan0: leased 192.168.1.136 for 86400 seconds
,E/WifiStateMachine(  863): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  863): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  863): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/SELinux ( 7614): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7614): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7614): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  863): failed to open /acct/uid_10011/pid_6713/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7614): TimaSignature is unavailable
,D/ActivityThread( 7614): Added TimaKeyStore provider
,D/ResourcesManager( 7614): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/GAV2    ( 7106): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  863): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  863): InactiveState{ what=143375 }
,D/WifiP2pService(  863): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  863): WifiStateMachine DHCP successful
,E/WifiStateMachine(  863): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  863): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  863): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  863): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine(  863): Not connected state, yet.
E/WifiStateMachine(  863): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  863): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine(  863): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  863): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  863): callSECApiInt - ID [210]
,E/WifiStateMachine(  863): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService(  863): updateNetworkInfo()
,D/ConnectivityService(  863): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  863): Adding iface wlan0 to network 503
,I/CLocInfoService(  863): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  863): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  863): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  863): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  863): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  863): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  863): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  863): Now, connected state.
E/WifiStateMachine(  863): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  863): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  863): evaluateTrafficStatsPolling
,I/CLocInfoService(  863): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  863): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  863): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  863): mBoosterFLAG : 0
I/WifiTrafficPoller(  863): current booster mode : FullMode
,D/WifiNative-HAL(  863): callSECApiVoid - ID [212]
,I/CLocInfoService(  863): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  863): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine(  863): ConnectedState Enter  mScreenOn=true scanperiod=20000
,I/WifiStateMachine(  863): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/ConnectivityService(  863): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,V/BitmapFactory( 1181): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_inout.png
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/ConnectivityService(  863): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  863): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  863): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  863): updateSourceRoutes : add src route for:192.168.1.136
,V/        (  280): QcRouteController
,V/        (  280): QcRouteController
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7614): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
V/        (  280): QcRouteController
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7614): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,V/        (  280): QcRouteController
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7614): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/ContextImpl( 7614): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,V/        (  280): QcRouteController
,V/        (  280): QcRouteController
,V/        (  280): QcRouteController
,V/        (  280): QcRouteController
,D/ConnectivityService(  863): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  863): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  863): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  863): updateNetworkInfo()
D/ConnectivityService(  863): calling update connectivity
E/ConnectivityService(  863): updateNetworkInfo()
D/ConnectivityService(  863): ignoring duplicate network state non-change
D/ConnectivityService(  863): ignoring duplicate network state non-change
D/ConnectivityService(  863): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  863): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  863): calling update connectivity
D/ConnectivityService(  863): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  863):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  863):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  863): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  863):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  863): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  863): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  863): Validated
,D/ConnectivityService(  863): currentScore = 0, newScore = 60
D/ConnectivityService(  863):    accepting network in place of null
D/ConnectivityService(  863): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1478): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  863): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  863): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  863): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  863): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  863): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  863): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  863): getSBEnabled() enabled =false
D/SmartBondingService(  863): getSBEnabled() enabled =false
D/SmartBondingService(  863): getSBEnabled() enabled =false
D/ConnectivityService(  863): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  863): calling update connectivity
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  863): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
,D/ConnectivityService(  863): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  863): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  863):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NtpTrustedTime(  863): currentTimeMillis() cache hit
D/ConnectivityService(  863):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkStats(  863): updateIfacesLocked()
V/NetworkStats(  863): performPollLocked(flags=0x1)
D/ConnectivityService(  863): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  863): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  863): calling update connectivity
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkStatsFactory(  863): UpdateStatsForKnox
D/ConnectivityService(  863): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524290
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  863): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  863): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
,V/NetworkStats(  863): performPollLocked() took 3ms
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  863): currentTimeMillis() cache hit
D/NtpTrustedTime(  863): currentTimeMillis() cache hit
,D/NtpTrustedTime(  863): currentTimeMillis() cache hit
D/NtpTrustedTime(  863): currentTimeMillis() cache hit
D/NtpTrustedTime(  863): currentTimeMillis() cache hit
V/NetworkStats(  863): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/NtpTrustedTime(  863): currentTimeMillis() cache hit
D/NtpTrustedTime(  863): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WebViewFactory( 7614): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7614): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7614): Loading: webviewchromium
,I/LibraryLoader( 7614): Time to load native libraries: 4 ms (timestamps 2858-2862)
,I/LibraryLoader( 7614): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7614): Binding Chromium to main looper Looper (main, tid 1) {34305829}
,I/LibraryLoader( 7614): Expected native library version number "",actual native library version number ""
,I/chromium( 7614): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7614): Initializing chromium process, renderers=0
,W/art     ( 7614): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7614): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/chromium( 7614): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium( 7614): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7614): Requires BLUETOOTH permission
,I/Adreno-EGL( 7614): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7614): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7614): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7614): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7614): Remote Branch: 
I/Adreno-EGL( 7614): Local Patches: 
I/Adreno-EGL( 7614): Reconstruct Branch: 
,I/NSApplication( 7614): Starting up...
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7708): MountEmulatedStorage()
I/libpersona( 7708): KNOX_SDCARD checking this for 10137
E/Zygote  ( 7708): v2
I/libpersona( 7708): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7708 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  863): Killing 6973:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/SELinux ( 7708): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7708): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7708): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7708): TimaSignature is unavailable
,D/ActivityThread( 7708): Added TimaKeyStore provider
,W/libprocessgroup(  863): failed to open /acct/uid_10014/pid_6973/cgroup.procs: No such file or directory
,D/ResourcesManager( 7708): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7708): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7708): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7708): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7708): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7708): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7708): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7723): MountEmulatedStorage()
E/Zygote  ( 7723): v2
I/libpersona( 7723): KNOX_SDCARD checking this for 10162
I/libpersona( 7723): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7723 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  863): Killing 6991:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/SELinux ( 7723): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7723): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7723): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7723): TimaSignature is unavailable
,D/ActivityThread( 7723): Added TimaKeyStore provider
,D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  863): MasterInitialState.processMessage what=3
,D/SmartBondingService(  863): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  863): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  863): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  863): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  863): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  863): getSBEnabled() enabled =false
,D/SmartBondingService(  863): getSBEnabled() enabled =false
D/SmartBondingService(  863): getSBEnabled() enabled =false
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  863): CLocinfo wifi true 
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  863): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2200): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2200): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  863): failed to open /acct/uid_10015/pid_6991/cgroup.procs: No such file or directory
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 6186): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7723): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/DBG_DM  ( 3682): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3682): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 1971): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 7723): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7723): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7723): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7723): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/WifiStateMachine(  863): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  863): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  863): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
E/WifiStateMachine(  863): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/SmartBondingService(  863): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  863): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  863): getSBEnabled() enabled =false
D/SmartBondingService(  863): getSBEnabled() enabled =false
D/SmartBondingService(  863): getSBEnabled() enabled =false
D/ConnectivityService(  863): identical MTU - not setting
D/ConnectivityService(  863): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  863): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
,V/        (  280): QcRouteController
,V/        (  280): QcRouteController
,W/NetworkManagementService(  863): route cmd failed: 
W/NetworkManagementService(  863): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  863): '
W/NetworkManagementService(  863): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  863): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  863): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  863): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  863): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  863): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  863): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  863): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  863): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  863): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  863): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  863): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  863): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  863): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  863): calling update connectivity
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  863): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524295
D/ConnectivityService(  863): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524295
D/ConnectivityService(  863): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  863): calling update connectivity
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  863): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524295
D/ConnectivityService(  863): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524295
,I/art     (  863): Explicit concurrent mark sweep GC freed 67581(3MB) AllocSpace objects, 2(32KB) LOS objects, 30% free, 37MB/53MB, paused 2.501ms total 125.947ms
,D/SecContentProvider2(  863): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  863): mCursor = null
,D/RCPManagerService(  863): exchangeData() failure , invalid userId
,D/RCPManagerService(  863): exchangeData() failure , invalid userId
,D/RCPManagerService(  863): exchangeData() failure , invalid userId
,D/RCPManagerService(  863): exchangeData() failure , invalid userId
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7759): MountEmulatedStorage()
E/Zygote  ( 7759): v2
I/libpersona( 7759): KNOX_SDCARD checking this for 10077
I/libpersona( 7759): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7759 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
I/SELinux ( 7759): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7759): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SELinux ( 7759): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  863): exchangeData() failure , invalid userId
,D/RCPManagerService(  863): exchangeData() failure , invalid userId
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/TimaKeyStoreProvider( 7759): TimaSignature is unavailable
,D/ActivityThread( 7759): Added TimaKeyStore provider
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
I/ActivityManager(  863): Killing 6367:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7441): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7441): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7441): StateMachine : Current State = 1
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7441): StateMachine : Changed Current State = 1
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
D/ResourcesManager( 7759): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,I/ActivityManager(  863): Killing 4806:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,V/BitmapFactory( 1181): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_out.png
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,E/Zygote  ( 7775): MountEmulatedStorage()
E/Zygote  ( 7775): v2
I/libpersona( 7775): KNOX_SDCARD checking this for 10177
I/libpersona( 7775): KNOX_SDCARD not a persona
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,I/ActivityManager(  863): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7775 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,I/SELinux ( 7775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7775): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 7759): onCreate
,D/BadgeProvider( 7759): DatabaseHelper
,D/BadgeProvider( 7759): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,D/TimaKeyStoreProvider( 7775): TimaSignature is unavailable
,D/ActivityThread( 7775): Added TimaKeyStore provider
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,D/BadgeProvider( 7759): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7759): sendNotify, [notify] : null
D/BadgeProvider( 7759): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7759): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7759): update, [UpdateCount] : 1
,D/Launcher.Model( 1506): reloadBadges entered.
,D/ResourcesManager( 7775): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,W/libprocessgroup(  863): failed to open /acct/uid_10033/pid_6367/cgroup.procs: No such file or directory
W/libprocessgroup(  863): failed to open /acct/uid_10034/pid_4806/cgroup.procs: No such file or directory
,D/ConnectivityService(  863): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
I/ActivityManager(  863): Killing 5891:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7723): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7418): notifyNetworkActivated
,W/ContextImpl( 7418): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  863): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/libprocessgroup(  863): failed to open /acct/uid_10041/pid_5891/cgroup.procs: No such file or directory
,W/ActivityManager(  863): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/hcjo    ( 7418): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7418): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7418): exit::IDLE
D/InitializeManagerStateMachine( 7418): entry::NETWORK_CHECK
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7418): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7418): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7418): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7418): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7418): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7418): entry::SUCCESS
,D/hcjo    ( 7418): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1313): Starting #8
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
D/hcjo    ( 7418): AutoUpdateTriggerManager:IDLE:notifyNextTime
I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
D/hcjo    ( 7418): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7418): exit::SUCCESS
D/InitializeManagerStateMachine( 7418): entry::IDLE
,I/Hs20UtilService( 1313): Starting #9
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1313): Starting #10
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1313): Starting #11
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1313): Message received 5007
I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  863): callSECApi what=220
,D/WifiStateMachine(  863): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7007): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7007): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7007): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7007): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7495): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7495): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SurfaceFlinger(  257): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/PowerManagerService(  863): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=863
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/FOTA_Client( 7511): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/FOTA_Client( 7511): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/FOTA_Client( 7511): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.503: ( 7526): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7526): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454085748032
,I/KLMS-2.4.503: ( 7526): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7526): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7526): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7526): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/KLMS-2.4.503: ( 7526): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/SO_AGENT( 7542): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5171): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/SA      ( 7044): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7044): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7044): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7044): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7044): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7044): [SCU] == networkStateCheck == true
,I/SA      ( 7044): [DM] getCountryCodeFromCSC : PL
I/SA      ( 7044): isChinaCountryCode : false
I/SA      ( 7044): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7044): [OR] == networkStateCheck true ==
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/SA      ( 7044): [OR] GetMyCountryZoneTask
,I/SA      ( 7044): [OR] onReceive END
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/SA      ( 7044): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7044): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7044): [SSP] query invoked
,D/accuweather( 7559): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7559): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/KnoxUsageLogPro( 7583): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7583): premStatus:2
,I/SA      ( 7044): [TPMU] GetMccFromDB : null
,I/SA      ( 7044): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7044): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7583): isEulaShown : false
I/KnoxUsageLogPro( 7583): KnoxUsageReceiver onReceive : not Processible, just return
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,E/File    ( 7044): fail readDirectory() errno=2
,D/Headlines( 5403): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5403): getCountryCode(): countryCode = PL
,D/Headlines( 5403): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5403): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5403): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5403): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5403): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5403): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5403): requestUpdateNewsWelcomeCard !!! no welcome card
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7708): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7708): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7708): PeriphStartReceiver.onReceive - no need to start
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  863): exchangeData() failure , invalid userId
,D/RCPManagerService(  863): exchangeData() failure , invalid userId
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7441): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7441): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7441): StateMachine : Current State = 1
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7441): StateMachine : Changed Current State = 1
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7418): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7418): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7418): exit::IDLE
D/InitializeManagerStateMachine( 7418): entry::NETWORK_CHECK
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7418): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7418): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7418): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7418): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7418): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7418): entry::SUCCESS
D/hcjo    ( 7418): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7418): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7418): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7418): exit::SUCCESS
D/InitializeManagerStateMachine( 7418): entry::IDLE
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,E/SMD     (  285): DCD ON
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  863): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SA      ( 7044): [RC New] Execute method=[GET] start
,I/SA      ( 7044): [RC New] Security=[true]
,I/System.out( 7044): Thread-1105(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7044): Thread-1105(ApacheHTTPLog):isShipBuild true
,I/System.out( 7044): Thread-1105(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7146): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7146): 
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  863): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10058 pid=1181 (0x0)
,I/SA      ( 7044): [RC New] [v2liruge] api execute + 738
I/SA      ( 7044): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7044): AsyncTask #1 calls detatch()
,I/SA      ( 7044): [ODM] saveOpenData( GEO_IP, PL )
,D/BatteryService(  863): level:100, scale:100, status:5, health:2, present:true, voltage: 4351, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  863): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  863): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  863):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  863): Plugged
I/MotionRecognitionService(  863): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/SA      ( 7044): [OCP] update openData : PL
,I/SA      ( 7044): [TPMU] getNetworkMcc : 
,I/SA      ( 7044): [SCU] saveMccToPreferece Start
,I/SA      ( 7044): [SCU] RegionMCC : 260
I/SA      ( 7044): [SSP] query invoked
,I/SA      ( 7044): [TPMU] GetMccFromDB : null,
I/SA      ( 7044): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 7044): [SCU] saveMccToPreferece End
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SA      ( 7044): [RC New] executeRequest [v2liruge] end. 809
,I/SA      ( 7044): [RC New] Execute end
,I/SA      ( 7044): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 7044): [OR] GetMyCountryZoneTask Success
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7146): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7146): 
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  863): REQUEST_POWER_SAVE_ON
,I/jxcore-log( 7146): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7146): 
,I/jxcore-log( 7146): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7146): 
,I/jxcore-log( 7146): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7146): 
,I/jxcore-log( 7146): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7146): 
,I/jxcore-log( 7146): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7146): 
,I/jxcore-log( 7146): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7146): 
,D/SSRM:m  (  863): SIOP:: AP = 420, PST = 384, CUR = 450
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7576): wlan0: sending IPv6 Router Solicitation
,E/WifiStateMachine(  863): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/PackageManager(  863): [MSG] MCS_UNBIND
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/ActivityManager(  863): Killing 5859:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,W/libprocessgroup(  863): failed to open /acct/uid_10047/pid_5859/cgroup.procs: No such file or directory
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/PowerManagerService(  863): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 863) eventTime = 97578
,D/PowerManagerService(  863): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=863 (0x0)
D/PowerManagerService(  863): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=863, ws=WorkSource{10058}) (elapsedTime=3471)
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/SMD     (  285): DCD ON
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,I/GAV4    ( 7614): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  863): CMD_RSSI_POLL : out!
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/SurfaceFlinger(  257): id=17 Removed Toast (8/8)
,I/SurfaceFlinger(  257): id=17 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7007): mConnectivityHandler : connected
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7007): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7007): [GetString-S]
,I/ReactiveServiceManager( 7007): Supported : 1
,D/QSEECOMAPI: (  863): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: (  863): App is not loaded in QSEE
,D/QSEECOMAPI: (  863): Loaded image: APP id = 4
,D/QSEECOMAPI: (  863): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  863): QSEECom_shutdown_app, app_id = 4
,E/terrier (  863): handleString: Failed to handle string(-4)
E/terrier (  863): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 7007): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7007): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7007): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7007): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7007): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7007): [ensureRegistration] - No Samsung account
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7576): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  863): CMD_RSSI_POLL : out!
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7146): Test app app.js loaded
I/jxcore-log( 7146): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7146): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7146): BLE advertisement is supported
I/jxcore-log( 7146): 
,I/chromium( 7146): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/Watchdog(  863): !@Sync 3
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  863): CMD_RSSI_POLL : out!
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7418): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7418): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7418): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7418): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7418): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7418): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7418): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7418): entry::IDLE
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7576): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7576): wlan0: no IPv6 Routers available
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7418): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7418): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7418): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7418): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7418): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7418): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7418): entry::IDLE
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/StatusBar.NetworkController( 1181): applyOpen
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,V/AlarmManager(  863): waitForAlarm result :4
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  863): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  863): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  863): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  863):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService(  863): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService(  863): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2226): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2226): Vacuum at: now=1454085759957 tag=VacuumService
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  863): SIOP:: AP = 380, PST = 382, CUR = 450
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/Finsky  ( 6506): [1075] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6506): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/PhenotypeConfigurator( 2226): Scheduling Phenotype for one-off execution 14043 seconds from now (1454085760260)
,D/GetConfigurationSnapshotOperation( 2226): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2226): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2226): Using platform SSLCertificateSocketFactory
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2226): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2226): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/System.out( 2226): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 2226): (HTTPLog)-Static: isShipBuild true
,I/System.out( 2226): (HTTPLog)-Thread-304-109888446: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  863): CMD_RSSI_POLL : out!
,I/qtaguid ( 2226): Tagging socket 74 with tag 3000120100000000{805310977,0} uid -1, pid: 2226, getuid(): 10011
,I/qtaguid ( 2226): Tagging socket 78 with tag 3000120100000000{805310977,0} uid -1, pid: 2226, getuid(): 10011
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2226): Tagging socket 74 with tag 3000120100000000{805310977,0} uid -1, pid: 2226, getuid(): 10011
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2226): Tagging socket 74 with tag 3000120100000000{805310977,0} uid -1, pid: 2226, getuid(): 10011
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2226): Tagging socket 74 with tag 3000120100000000{805310977,0} uid -1, pid: 2226, getuid(): 10011
,D/ConnectivityService(  863): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  863): CMD_RSSI_POLL : out!
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/FactoryTest( 6560): Not factory mode
,D/FactoryTest( 6560): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6560): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6560): still no open session command from host, so toast
,W/ContextImpl( 6560): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6560): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6560): Timeline: Activity_launch_request id:com.android.settings time:110806
,E/PersonaManagerService(  863): inState():  stateMachine is null !!
,V/ApplicationPolicy(  863): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  863): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  863): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 863  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  863): mDVFSHelper.acquire()
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/MTPRx   ( 6560): started activity for popup
,I/SQLiteSecureOpenHelper( 3484): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3484): getDatabaseLocked(b,b,pwd)...
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6560): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6560): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6560): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6560): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6560): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6560): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6560): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6560): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6560): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/ActivityManager(  863): Invalid thumbnail dimensions: 576x576
,D/InputMethodManagerService(  863): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  863): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@24f1e413 attribute=null, token = android.os.BinderProxy@375639b1
,I/SQLiteSecureOpenHelper( 3484): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3484): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6560): dev.kiessupport is : TRUE
,D/Activity( 6560): performCreate Call secproduct feature valuefalse
,D/Activity( 6560): performCreate Call debug elastic valuetrue
E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ActivityManager(  863): post active user change for 0
D/KnoxTimeoutHandler(  863): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  863): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/Timeline( 7146): Timeline: Activity_idle id: android.os.BinderProxy@834be52 time:111056
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,W/ContextImpl(  863): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,V/BitmapFactory( 1181): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_in.png
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  863): CMD_RSSI_POLL : out!
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/CustomFrequencyManagerService(  863): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 863  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  863): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  863): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 863  pkgName : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  863): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 863  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore in!
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  863): CMD_RSSI_POLL : out!
,D/BatteryService(  863): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  863): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  863): Sending ACTION_BATTERY_CHANGED.
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/MotionRecognitionService(  863):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  863): Plugged
I/MotionRecognitionService(  863): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  863): SIOP:: AP = 340, PST = 372, CUR = 450
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  863): CMD_RSSI_POLL : out!
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  863): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  863): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,D/lights  (  863): lcd : 1 +
,D/lights  (  863): lcd : 1 -
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/SMD     (  285): DCD ON
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  863): CMD_RSSI_POLL : out!
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/SMD     (  285): DCD ON
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  863): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  863): CMD_RSSI_POLL : out!
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,V/AlarmManager(  863): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/SSRM:m  (  863): SIOP:: AP = 320, PST = 361, CUR = 450
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
,D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  863): [s] UserActivityState : 2 -> 4,
I/PowerManagerService(  863): Nap time (uid 1000)...,
I/PowerManagerService(  863): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  863): Going to sleep due to screen timeout (uid 1000)...,
D/PowerManagerService(  863): [PWL] sb acquire: PowerManagerService.Broadcasts,
D/InputManager-JNI(  863): setDeviceInteractive: 0,
D/PowerManagerService(  863): SecHardwareInterface.setBatteryADC : false,
,D/PowerManagerService(  863): handleSandman : startDream()
I/SurfaceFlinger(  257): id=18 createSurf (1080x1920),2 flag=404, ColorFade,
E/PowerManagerService(  863): handleSandman : startDreaming, but isDreaming false,
I/PowerManagerService(  863): Sleeping (uid 1000)...
D/InputManager-JNI(  863): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/PowerManagerService(  863): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  863): [input device light] setInputDeviceLightOn is called : 0,
D/PowerManagerService(  863): [input device light] handleInputDeviceLightOff
D/InputManager-JNI(  863): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  863): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  863): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  863): 	.unregisterCallback : 1, client=
,D/SContextService(  863): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@179c37da, Service = Auto Rotation, used = 1
,W/CAE     (  863): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  863): stop(ContextProvider.java:149)
,V/CAE     (  863): clear(AutoRotationRunner.java:182)
V/CAE     (  863): disable(AutoRotationRunner.java:171)
,I/CAE     (  863): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  863): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  300): sendContextData: -78, 7, 0, 0
,E/SMD     (  285): DCD ON
,D/CAE     (  863): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  863): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  863): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  863): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  863): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  863): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  863): removeSContextService() : service = Auto Rotation
D/SContextService(  863): ===== SContext Service List =====
D/SContextManager(  863):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@2e94544, service=Auto Rotation
D/KeyguardViewMediator( 1181): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1181): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1181): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1181): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/KeyguardViewMediator( 1181): timeout : 5000
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/SQLiteSecureOpenHelper( 3484): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3484): getDatabaseLocked(b,b,pwd)...
,D/DisplayPowerController(  863): ColorFade: onAnimationStart
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 0
,E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 0
,D/DisplayPowerController(  863): getFinalBrightness : 8 -> 0
,D/lights  (  863): lcd : 0 +
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,D/lights  (  863): lcd : 0 -
,D/KeyguardViewMediator( 1181): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1181): handleNotifyScreenOff
,D/LightsService(  863): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 863) 
D/LightsService(  863): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  863): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  863): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  863): unregisterListener ::   
D/lights  (  863): led_pattern : 5 +
,D/BatteryService(  863): turn on LED for fully charged
,D/lights  (  863): led_pattern : 5 -
,D/LightsService(  863): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  863): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  863): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  863): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  863): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  300): sendContextData: -76, 13, -46, 0
,I/CAE     (  863): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 16, 43, 1,
D/SensorHubManager(  863): SendSensorHubData: send data = -63, 14, 16, 43, 1
D/Sensorhubs(  300): sendContextData: -63, 14, 16, 43, 1
,D/MotionRecognitionService(  863):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  863):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  863): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  863): handleScreenStateChanged Exit: false
,D/NotificationService(  863): ACTION_SCREEN_OFF
,D/LightsService(  863): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 863) 
D/LightsService(  863): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService(  863): [SvcLED]  onSensorChanged::light value = 0
E/WifiStateMachine(  863): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  863): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  863): do suspend true
,D/SensorManager(  863): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  863): unregisterListener ::   
D/LightsService(  863): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  290): adev_set_parameters: enter: screen_state=off
,V/voice   (  290): voice_set_parameters: enter: screen_state=off
V/voice   (  290): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  290): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  290): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  290): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  290): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  863): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  863): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  863): Bridge Server is not available
,D/VolumePanel( 1181): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1181): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1181): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1181): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  863): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  863): MSG_ACTION_SCREEN_OFF called
E/LightSensor(  863): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  863): mCallbacks.updateBrightness()
D/DisplayPowerController(  863): getFinalBrightness : 8 -> 0
,D/NfcService( 1469): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1181):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1181): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1181): dismissHelpPopup 
,D/accuweather( 1971): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1971): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 1971): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/DisplayPowerState(  863): !@ ColorFade entry
,D/DisplayPowerController(  863): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  863): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,D/AutomaticBrightnessController(  863): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  863): Light old sensor_state 513, new sensor_state : 1 en : 0
I/AutomaticBrightnessController(  863): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  863): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  863): unregisterListener ::   
,E/Sensors (  863): Acc old sensor_state 1, new sensor_state : 0 en : 0
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SensorManager(  863): unregisterListener ::   
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/DisplayPowerController(  863): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  863): getFinalBrightness : 0 -> 0
I/DisplayManagerService(  863): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  257): hwc_blank: Blanking display: 0
V/ActivityManager(  863): Display changed displayId=0
,W/ActivityManager(  863): getTasks: caller 10085 does not hold GET_TASKS; limiting output
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/ActivityManager(  863): getTasks: caller 10085 does not hold GET_TASKS; limiting output
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/PowerManagerService(  863): [PWL] sb release: PowerManagerService.Broadcasts
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/SSRM:m  (  863): SIOP:: AP = 320, PST = 353, CUR = 450
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/StatusBar.NetworkController( 1181): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/rmt_storage(  276): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
,I/rmt_storage(  276): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  276): wakelock acquired: 1, error no: 42
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 22
I/rmt_storage(  276): 
,I/rmt_storage(  276): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  257): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  863): Excessive delay in setPowerMode(): 276ms
D/PowerManagerService(  863): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL(  863): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  863): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  863): Got set_interactive hint
,I/PowerManagerService(  863): [PWL] Off : 0s ago
,I/PowerManagerService(  863): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  863): [PWL]     mDisplayReady : false
D/DisplayPowerController(  863): getFinalBrightness : 0 -> 0
D/PowerManagerService(  863): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  863): [PWL] sb release: PowerManagerService.Display
,E/SMD     (  285): DCD ON,
,W/ContextImpl(  863): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  863): waitForAlarm result :4
,D/KeyguardViewMediator( 1181): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/KeyguardViewMediator( 1181): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  863): [PWL] Off : 5s ago
,E/SMD     (  285): DCD ON
,E/Watchdog(  863): !@Sync 4
,D/BatteryService(  863): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  863): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  863): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  863):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  863): Plugged
,D/BatteryService(  863): stay LED for fully charged
,I/MotionRecognitionService(  863): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  863): SIOP:: AP = 310, PST = 348, CUR = 450
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,I/PowerManagerService(  863): [PWL] Off : 15s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  863): SIOP:: AP = 300, PST = 344, CUR = 450
,E/SMD     (  285): DCD ON
,W/ContextImpl(  863): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  863): waitForAlarm result :4
,D/BatteryService(  863): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  863): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  863): stay LED for fully charged
D/BatteryService(  863): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  863):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  863): Plugged
I/MotionRecognitionService(  863): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  863): SIOP:: AP = 290, PST = 339, CUR = 450
,I/PowerManagerService(  863): [PWL] Off : 30s ago
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,E/Watchdog(  863): !@Sync 5
,E/SMD     (  285): DCD ON
,D/BatteryService(  863): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  863): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  863): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  863):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  863): Plugged
,D/BatteryService(  863): stay LED for fully charged
,I/MotionRecognitionService(  863): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/SSRM:m  (  863): SIOP:: AP = 290, PST = 334, CUR = 450
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,W/ContextImpl(  863): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  863): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  863): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  863): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  863):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  863): Plugged
,I/MotionRecognitionService(  863): setPowerConnected  = true
,D/BatteryService(  863): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/PowerManagerService(  863): [PWL] Off : 50s ago
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  863): SIOP:: AP = 290, PST = 326, CUR = 450
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  863): waitForAlarm result :8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  863): SIOP:: AP = 290, PST = 313, CUR = 450
,E/SMD     (  285): DCD ON
,W/ContextImpl(  863): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/Watchdog(  863): !@Sync 6
,I/ClearcutLoggerApiImpl( 2226): disconnect managed GoogleApiClient
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  863): SIOP:: AP = 290, PST = 304, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  863): [PWL] Off : 75s ago
,E/SMD     (  285): DCD ON
,V/AlarmManager(  863): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/BatteryService(  863): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  863): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  863): stay LED for fully charged
,D/BatteryService(  863): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  863):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  863): Plugged
,I/MotionRecognitionService(  863): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:m  (  863): SIOP:: AP = 280, PST = 298, CUR = 450
,E/SMD     (  285): DCD ON
,I/jxcore-log( 7146): --= Surplus to requirements =--
I/jxcore-log( 7146): 
,I/jxcore-log( 7146): ****TEST TOOK:  ms ****
I/jxcore-log( 7146): 
I/jxcore-log( 7146): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7146): 
,D/AndroidRuntime( 7913): 
D/AndroidRuntime( 7913): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7913): CheckJNI is OFF
,D/AndroidRuntime( 7913): setted country_code = Poland
,D/AndroidRuntime( 7913): setted countryiso_code = PL
,D/AndroidRuntime( 7913): setted sales_code = XEO
,D/AndroidRuntime( 7913): readGMSProperty: start
D/AndroidRuntime( 7913): readGMSProperty: already setted!!
,D/AndroidRuntime( 7913): readGMSProperty: end
,D/AndroidRuntime( 7913): addProductProperty: start
,E/AffinityControl( 7913): AffinityControl: registerfunction enter
,D/AndroidRuntime( 7913): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  863): START PACKAGE DELETE: observer{815663636}
D/PackageManager(  863): pkg{<packageName>}
D/PackageManager(  863): user{0}
D/PackageManager(  863): caller{2000}
D/PackageManager(  863): flags{3}
,D/PersonaManagerService(  863): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  863): isFromApprovedUnInstaller: isApproved : true
,D/PersonaManagerService(  863): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  863): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  863): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  863): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  863): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  863): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  863): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  863): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  863): !@killApplicatoin: 10191, uninstall pkg
,I/ActivityManager(  863): Force stopping com.test.thalitest appid=10191 user=-1: uninstall pkg
,I/ActivityManager(  863): Killing 7146:com.test.thalitest/u0a191 (adj 0): stop com.test.thalitest
,I/ActivityManager(  863):   Force finishing activity ActivityRecord{da77b61 u0 com.test.thalitest/.MainActivity t10}
,D/FocusedStackFrame(  863): Set to : 0
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  863): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  863): Force stopping com.test.thalitest appid=10191 user=0: pkg removed
,W/ContextImpl(  863): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     ( 2490): Explicit concurrent mark sweep GC freed 35881(2MB) AllocSpace objects, 7(112KB) LOS objects, 39% free, 21MB/35MB, paused 703us total 61.113ms
,I/art     ( 6273): Explicit concurrent mark sweep GC freed 28650(1590KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 726us total 83.566ms
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,E/SamsungIME( 1875): mOCRHelper is null
,I/InputReader(  863): Reconfiguring input devices.  changes=0x00000010
,D/WifiService(  863): Client connection lost with reason: 4
,W/GeofencerStateMachine( 2226): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1568): Explicit concurrent mark sweep GC freed 31342(1946KB) AllocSpace objects, 1(39KB) LOS objects, 39% free, 16MB/27MB, paused 766us total 80.027ms
,I/KLMS-2.4.503: ( 7526): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7526): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1454085865190
,I/KLMS-2.4.503: ( 7526): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7526): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     (  863): Explicit concurrent mark sweep GC freed 69288(4MB) AllocSpace objects, 46(3MB) LOS objects, 30% free, 37MB/53MB, paused 3.607ms total 211.017ms
,D/ResourcesManager(  863): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  863): WaitForGcToComplete blocked for 112.425ms for cause Explicit
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/SecContentProvider2(  863): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  863): mCursor = null
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/RegisteredServicesCache( 1469): empty dynamic service
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
D/EnterpriseDeviceManagerService(  863): Package has changed for user 0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
D/EnterpriseDeviceManagerService(  863): Admin package name: com.google.android.gms
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/Books/Books.apk
E/Zygote  ( 7943): MountEmulatedStorage()
E/Zygote  ( 7943): v2
I/libpersona( 7943): KNOX_SDCARD checking this for 10103
I/libpersona( 7943): KNOX_SDCARD not a persona
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
I/ActivityManager(  863): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7943 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
I/SELinux ( 7943): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,I/SELinux ( 7943): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,E/SELinux ( 7943): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/TimaKeyStoreProvider( 7943): TimaSignature is unavailable
,D/ActivityThread( 7943): Added TimaKeyStore provider
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 7943): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/SurfaceWidgetView( 1506): destroyHardwareResources():87943819
,V/WindowOrientationListener(  863): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  863): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  863): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  863): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  863): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/Launcher( 1506): onRestart, Launcher: 225735717
,D/Launcher( 1506): onStart, Launcher: 225735717
D/Launcher.HomeView( 1506): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1971): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1971): [237392/6] SurfaceWidget drawing first frame
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/SurfaceFlinger(  257): id=19 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/StatusBarManagerService(  863): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/StatusBarManagerService(  863): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/RCPManagerService(  863): PackageReceiver onReceive()
,I/HarmonyEASService(  863): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  863): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  863): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  863): Receieved: android.intent.action.PACKAGE_REMOVED
D/ResourcesManager(  863): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,V/EnterpriseBillingPolicy(  863): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  863): uID is 10191
V/EnterpriseBillingPolicy(  863): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  863): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  863): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  863): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  863): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  863): getBillingProfileForVpnEngine - start - com.test.thalitest
,E/SMD     (  285): DCD ON
V/EnterpriseBillingPolicyStorage(  863): getBillingProfileForVpnEngine - end - null
,D/TaskPersister(  863): removeObsoleteFile: deleting file=10_task.xml
,D/TaskPersister(  863): removeObsoleteFile: deleting file=10_task_thumbnail.png
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/InputMethodManagerService(  863): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  863): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService(  863): Got RemoteException sending setActive(false) notification to pid 7146 uid 10191
,D/elm:14451( 7943): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 7943): ELMEngine.ELMEngine( context ).
,D/elm:14451( 7943): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/elm:14451( 7943): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14451( 7943): ElmAgentService : onCreate()
,D/elm:14451( 7943): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 7943): MainReceiver.listeningToPackageRemoved()
,D/elm:14451( 7943): MDMBridge.getInstance()
D/elm:14451( 7943): MDMBridge.getAllLicenseInfoFromSDK()
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 7963): MountEmulatedStorage()
,E/Zygote  ( 7963): v2
I/libpersona( 7963): KNOX_SDCARD checking this for 10016
I/libpersona( 7963): KNOX_SDCARD not a persona
D/elm:14451( 7943): MDMBridge.getAllLicenseInfoFromSDK()
,I/ActivityManager(  863): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7963 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/SELinux ( 7963): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/ResourcesManager(  863): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,I/art     (  863): Explicit concurrent mark sweep GC freed 16837(886KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 37MB/53MB, paused 4.985ms total 320.180ms
,I/SELinux ( 7963): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7963): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/elm:14451( 7943): ElmAgentService : onDestroy().
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/ActivityManager(  863): Killing 5584:com.android.mms/u0a49 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7963): TimaSignature is unavailable
,D/ActivityThread( 7963): Added TimaKeyStore provider
,I/Timeline(  863): Timeline: Activity_windows_visible id: ActivityRecord{e3fc09a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:211789
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,W/ResourcesManager(  863): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  863): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/PackageManager(  863): delete codoeFile: 
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/CountryDetector(  863): No listener is left
,D/PackageManager(  863): result of delete: 1{815663636}
,D/AndroidRuntime( 7913): Shutting down VM
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 7963): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 7963): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 7963): onReceive() : package name is not s health. Return !!!
,I/PCWCLIENTTRACE_PushUtil( 7007): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7007): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7007): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7007): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7979): MountEmulatedStorage()
E/Zygote  ( 7979): v2
I/libpersona( 7979): KNOX_SDCARD checking this for 10033
I/libpersona( 7979): KNOX_SDCARD not a persona
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/ActivityManager(  863): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7979 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/ResourcesManager(  863): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/ActivityManager(  863): Killing 7065:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,D/ResourcesManager(  863): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/SELinux ( 7979): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  863): failed to open /acct/uid_10049/pid_5584/cgroup.procs: No such file or directory
,I/SELinux ( 7979): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7979): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 7979): TimaSignature is unavailable
D/ActivityThread( 7979): Added TimaKeyStore provider
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/libprocessgroup(  863): failed to open /acct/uid_10050/pid_7065/cgroup.procs: No such file or directory
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 7979): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  863): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  863): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/FeatureConfig( 7979): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,W/Resources(  863): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  863): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  863): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 7979): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7979): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7979): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7979): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7979): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 7979): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7979): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7979): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7979): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7979): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7979): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7979): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 7979): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7979): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7979): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7979): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7979): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7979): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7979): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7979): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7979): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7979): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7979): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7979): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7979): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7979): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7979): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7979): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7979): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7979): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7979): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7979): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7979): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7979): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ResourcesManager( 7979): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 7979): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7979): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7979): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7979): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 7979): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/ResourcesManager( 7979): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7979): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  863): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8000 uid=10034 gids={50034, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  863): Killing 7082:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
E/Zygote  ( 8000): MountEmulatedStorage()
,E/Zygote  ( 8000): v2
I/libpersona( 8000): KNOX_SDCARD checking this for 10034
,I/libpersona( 8000): KNOX_SDCARD not a persona
,I/art     (  317): Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 7.144ms total 22.501ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.602ms
,I/SELinux ( 8000): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 8.115ms
,I/SELinux ( 8000): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8000): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8000): TimaSignature is unavailable
,D/ActivityThread( 8000): Added TimaKeyStore provider
,D/ResourcesManager( 8000): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/ContextImpl( 8000): Unable to create files subdir /data/data/com.sec.android.app.shealth/cache
E/ActivityThread( 8000): Unable to setupGraphicsSupport due to missing cache directory
,W/        ( 8000): Zip: failed reading lfh name from offset 418254
,D/AndroidRuntime( 8000): Shutting down VM
,F/libc    ( 8000): Fatal signal 7 (SIGBUS), code 2, fault addr 0x72800151 in tid 8000 (oid.app.shealth)
,E/audit_log( 2132): File locking failed. error= Bad file number
,F/libc    ( 8000): Failed while talking to debuggerd: Broken pipe
,E/audit_log( 2132): File locking failed. error= Bad file number
,I/EventHub(  863): Removing device '/dev/input/event4' due to inotify event
,W/libprocessgroup(  863): failed to open /acct/uid_10057/pid_7082/cgroup.procs: No such file or directory
,I/ActivityManager(  863): Process com.sec.android.app.shealth (pid 8000)(adj 0) has died(213,548)
,E/SharedPreferencesImpl( 7979): Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,I/EventHub(  863): Removing device '/dev/input/event5' due to inotify event
,F/libc    ( 5171): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7764ea00 in tid 5171 (om.sec.spp.push)
,F/libc    ( 5171): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2132): File locking failed. error= Bad file number
,I/Zygote  (  317): Process 8000 exited due to signal (7)
,I/ActivityManager(  863): Process com.sec.spp.push (pid 5171)(adj 0) has died(219,549)
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,I/Zygote  (  317): Process 5171 exited due to signal (7)
,E/Zygote  ( 8022): MountEmulatedStorage()
E/Zygote  ( 8022): v2
I/libpersona( 8022): KNOX_SDCARD checking this for 10037
I/libpersona( 8022): KNOX_SDCARD not a persona
I/ActivityManager(  863): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8022 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/EventHub(  863): Removing device '/dev/input/event6' due to inotify event
,I/SELinux ( 8022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/EventHub(  863): Removing device '/dev/input/event7' due to inotify event
,E/SELinux ( 8022): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8022): TimaSignature is unavailable
,D/ActivityThread( 8022): Added TimaKeyStore provider
,D/ResourcesManager( 8022): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,I/EventHub(  863): Removing device '/dev/input/event8' due to inotify event
,W/        ( 8022): Zip: read 65557 failed: I/O error
W/zipro   ( 8022): Error opening archive /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk: I/O Error
D/asset   ( 8022): failed to open Zip archive '/system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk'
,W/ContextImpl( 8022): Unable to create files subdir /data/data/com.sec.spp.push/cache
E/ActivityThread( 8022): Unable to setupGraphicsSupport due to missing cache directory
,W/        ( 8022): Zip: read 65557 failed: I/O error
,W/        ( 8022): Zip: read 65557 failed: I/O error
,D/ResourcesManager( 8022): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,F/libc    ( 8022): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa16d5756 in tid 8022 (moteNotiProcess)
,F/libc    ( 8022): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2132): File locking failed. error= Bad file number
,I/ActivityManager(  863): Process com.sec.spp.push:RemoteNotiProcess (pid 8022)(adj 0) has died(218,549)
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,I/EventHub(  863): Removing device '/dev/input/event9' due to inotify event
,I/Zygote  (  317): Process 8022 exited due to signal (7)
,E/Zygote  ( 8038): MountEmulatedStorage()
E/Zygote  ( 8038): v2
I/libpersona( 8038): KNOX_SDCARD checking this for 10041
I/libpersona( 8038): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8038 uid=10041 gids={50041, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/EventHub(  863): Removing device '/dev/input/event10' due to inotify event
,I/SELinux ( 8038): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8038): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8038): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8038): TimaSignature is unavailable
,D/ActivityThread( 8038): Added TimaKeyStore provider
,I/EventHub(  863): Removing device '/dev/input/event11' due to inotify event
,D/ResourcesManager( 8038): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/        ( 8038): Zip: read 65557 failed: I/O error
W/zipro   ( 8038): Error opening archive /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk: I/O Error
D/asset   ( 8038): failed to open Zip archive '/system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk'
,W/ContextImpl( 8038): Unable to create files subdir /data/data/com.samsung.android.sdk.samsunglink/cache
E/ActivityThread( 8038): Unable to setupGraphicsSupport due to missing cache directory
,D/ResourcesManager( 8038): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,D/AndroidRuntime( 8038): Shutting down VM
,F/libc    ( 8038): Fatal signal 7 (SIGBUS), code 2, fault addr 0x72800151 in tid 8038 (sdk.samsunglink)
,F/libc    ( 8038): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2132): File locking failed. error= Bad file number
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/ActivityManager(  863): Process com.samsung.android.sdk.samsunglink (pid 8038)(adj 0) has died(219,549)
,I/SA      ( 7044): [SUR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7044): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10191 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,F/libc    ( 1802): Fatal signal 7 (SIGBUS), code 2, fault addr 0x772a2dd4 in tid 1802 (d.process.acore)
,F/libc    ( 1802): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2132): File locking failed. error= Bad file number
,I/Zygote  (  317): Process 8038 exited due to signal (7)
,I/ActivityManager(  863): Process android.process.acore (pid 1802)(adj 0) has died(224,550)
,E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  863): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8053): MountEmulatedStorage()
E/Zygote  ( 8053): v2
I/libpersona( 8053): KNOX_SDCARD checking this for 10047
I/libpersona( 8053): KNOX_SDCARD not a persona
,I/ActivityManager(  863): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=8053 uid=10047 gids={50047, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/Zygote  (  317): Process 1802 exited due to signal (7)
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,I/SELinux ( 8053): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8053): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027

```
