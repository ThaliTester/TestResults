#### Test 549702618c0ebdb_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
,D/MyFiles ( 7217): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
E/installd(  303): system dir 0 : /system/app/
E/installd(  303): system dir 1 : /system/priv-app/
E/installd(  303): system dir 2 : /vendor/app/
E/installd(  303): system dir 3 : /oem/app/
I/TactileAssist(  914): enable value -1
I/TactileAssist(  914): internal enable value -1
I/TactileAssist(  914): intensity value -1
I/TactileAssist(  914): saveAppList value true
I/TactileAssist(  914): List of disabled apps :
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7237): MountEmulatedStorage()
E/Zygote  ( 7237): v2
I/libpersona( 7237): KNOX_SDCARD checking this for 10057
I/libpersona( 7237): KNOX_SDCARD not a persona
I/ActivityManager(  914): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7237 uid=10057 gids={50057, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 7237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/PackageManager(  914): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/SELinux ( 7237): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7237): TimaSignature is unavailable
D/ActivityThread( 7237): Added TimaKeyStore provider
D/ResourcesManager( 7237): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/ResourcesManager( 7237): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 7237): onReceive() it will make start service
E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
I/UpdateIcingCorporaServi( 1649): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 7237): onHandleIntent()
W/ContextImpl( 6092): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
D/Compatibility( 7237): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10356, android.intent.extra.user_handle=0}]
D/Compatibility( 7237): found: 2
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  914): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7259 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7259): MountEmulatedStorage()
E/Zygote  ( 7259): v2
I/libpersona( 7259): KNOX_SDCARD checking this for 10097
I/libpersona( 7259): KNOX_SDCARD not a persona
D/Compatibility( 7237): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7237): skipping ResolveInfo{2e6a7ed7 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7237): considering ResolveInfo{2747b3c4 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7237): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/ResourcesManager( 1649): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SELinux ( 7259): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/UpdateIcingCorporaServi( 1649): UpdateCorporaTask done [took 93 ms] updated apps [took 93 ms] 
I/SELinux ( 7259): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/Compatibility( 7237): enabling receiver ResolveInfo{1fe572ad com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/SELinux ( 7259): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/Compatibility( 7237): enabling receiver ResolveInfo{1c70b9e2 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/AndroidRuntime( 7247): 
D/AndroidRuntime( 7247): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/Compatibility( 7237): enabling receiver ResolveInfo{1b6e3173 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/AndroidRuntime( 7247): CheckJNI is OFF
D/AndroidRuntime( 7247): setted country_code = Poland
D/AndroidRuntime( 7247): setted countryiso_code = PL
D/AndroidRuntime( 7247): setted sales_code = XEO
D/AndroidRuntime( 7247): readGMSProperty: start
D/AndroidRuntime( 7247): readGMSProperty: already setted!!
D/AndroidRuntime( 7247): readGMSProperty: end
D/AndroidRuntime( 7247): addProductProperty: start
D/Compatibility( 7237): enabling receiver ResolveInfo{32ee4830 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7237): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 7259): TimaSignature is unavailable
I/ActivityManager(  914): Killing 4755:com.android.calendar/u0a149 (adj 15): bgCount ##41
D/ActivityThread( 7259): Added TimaKeyStore provider
D/ResourcesManager( 7259): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/SSRM:m  (  914): SIOP:: AP = 320, PST = 348, CUR = 450
E/AffinityControl( 7247): AffinityControl: registerfunction enter
W/libprocessgroup(  914): failed to open /acct/uid_10149/pid_4755/cgroup.procs: No such file or directory
D/AndroidRuntime( 7247): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  914): inState():  stateMachine is null !!
V/ApplicationPolicy(  914): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  914): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  914): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  914): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 914  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  914): mDVFSHelper.acquire()
D/FocusedStackFrame(  914): Set to : 0
D/Launcher.HomeView( 1473): onPause
D/Launcher( 1473): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 7247): Shutting down VM
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
I/SurfaceFlinger(  259): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/DocsApplication( 7259): Installing DEX configuration.
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
E/Zygote  ( 7290): MountEmulatedStorage()
E/Zygote  ( 7290): v2
I/libpersona( 7290): KNOX_SDCARD checking this for 10356
I/libpersona( 7290): KNOX_SDCARD not a persona
I/ActivityManager(  914): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7290 uid=10356 gids={50356, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7290): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SELinux ( 7290): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/SELinux ( 7290): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/StatusBarManagerService(  914): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/MicrophoneInputStream( 1649): mic_close gfk@2eda16c8
D/TimaKeyStoreProvider( 7290): TimaSignature is unavailable
D/ActivityThread( 7290): Added TimaKeyStore provider
D/DexInstaller( 7259): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
V/AudioPolicyManager(  300): stopInput() input 29
V/AudioPolicyManager(  300): releaseInput() 29
V/AudioPolicyManager(  300): closeInput(29)
V/WindowOrientationListener(  914): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  914): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  914): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  914): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  914): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
I/HotwordRecognitionRnr( 1649): Hotword detection finished
V/audio_hw_primary(  300): in_standby: enter
I/HotwordRecognitionRnr( 1649): Stopping hotword detection.
D/Launcher.HomeView( 1473): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2113): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2113): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
V/ActivityManager(  914): Display changed displayId=0
D/accuweather( 2113): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2113): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2113): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/SurfaceWidgetView( 1473): destroyHardwareResources():186673867
I/PackageInfoHelper( 7259): Provided clientMode=RELEASE, packageInfo=PackageInfo{1a4a0e56 com.google.android.apps.docs}
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/StatusBarManagerService(  914): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
V/audio_hw_primary(  300): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  300): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  300): disable_audio_route: reset mixer path: audio-record
D/audio_route(  300): ++++ audio_route_update_mixer ==============
D/audio_route(  300): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  300): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/audio_route(  300): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  300): disable_audio_route: exit
V/audio_hw_primary(  300): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  300): ++++ audio_route_update_mixer ==============
D/audio_route(  300): Setting mixer control: DEC2 Volume
D/audio_route(  300): Setting mixer control: value: 0
D/audio_route(  300): Setting mixer control: SLIM TX7 MUX, value: 0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/audio_route(  300): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  300): Setting mixer control: value: 0
D/audio_route(  300): Setting mixer control: DEC2 MUX, value: 0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/audio_route(  300): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  300): stop_input_stream: exit: status(0)
V/audio_hw_primary(  300): in_standby: exit:  status(0)
V/audio_hw_primary(  300): adev_close_input_stream
V/audio_hw_primary(  300): in_standby: enter
V/audio_hw_primary(  300): in_standby: exit:  status(0)
E/audio_hw_primary(  300): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  300): releaseInput() exit
D/accuweather( 2113): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/TAG     ( 7259): onCreate()
D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Launcher( 1473): onTrimMemory. Level: 20
D/accuweather( 2113): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/ResourcesManager( 7290): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/SurfaceWidgetView( 1473): destroyHardwareResources():186673867
D/CrossAppStateProvider( 7259): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/WebViewFactory( 7290): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7290): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/SMD     (  295): DCD ON
I/LibraryLoader( 7290): Loading: webviewchromium
I/LibraryLoader( 7290): Time to load native libraries: 2 ms (timestamps 6673-6675)
I/LibraryLoader( 7290): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
V/WebViewChromiumFactoryProvider( 7290): Binding Chromium to main looper Looper (main, tid 1) {1b6e3173}
I/LibraryLoader( 7290): Expected native library version number "",actual native library version number ""
I/chromium( 7290): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7290): Initializing chromium process, renderers=0
W/art     ( 7290): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
W/chromium( 7290): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7290): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7290): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/Adreno-EGL( 7290): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7290): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7290): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7290): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7290): Remote Branch: 
I/Adreno-EGL( 7290): Local Patches: 
I/Adreno-EGL( 7290): Reconstruct Branch: 
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
V/AlarmManager(  914): waitForAlarm result :4
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
W/chromium( 7290): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7290): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
W/art     ( 7290): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7290): onDetachedFromWindow called when already detached. Ignoring
E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  914): Plugged
I/MotionRecognitionService(  914): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3255): Disconnected process message: 10
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/SystemWebViewEngine( 7290): CordovaWebView is running on device made by: samsung
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
W/art     ( 7290): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7290): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/Activity( 7290): performCreate Call secproduct feature valuefalse
D/Activity( 7290): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7290): Render dirty regions requested: true
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/ActivityManager(  914): post active user change for 0
D/KnoxTimeoutHandler(  914): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  914): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SurfaceFlinger(  259): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/OpenGLRenderer( 7290): Initialized EGL, version 1.4
I/OpenGLRenderer( 7290): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7290): Enabling debug mode 0
E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SurfaceFlinger(  259): id=6 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  259): id=6 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/InputMethodManagerService(  914): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/ActivityManager(  914): Displayed com.test.thalitest/.MainActivity: +635ms
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/Timeline( 7290): Timeline: Activity_idle id: android.os.BinderProxy@347f5f92 time:107070
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore in!
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  914): CMD_RSSI_POLL : out!
D/LockPatternUtilsCache( 1184): value : false
E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/JsMessageQueue( 7290): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/chromium( 7290): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7290): 
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/jxcore_app_log( 7290): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359661312
D/JX-Cordova( 7290): jxcore cordova android initializing
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/CustomFrequencyManagerService(  914): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 914  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  914): mDVFSHelper.release()
D/CustomFrequencyManagerService(  914): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 914  pkgName : ACTIVITY_RESUME_BOOSTER@10
I/Timeline(  914): Timeline: Activity_windows_visible id: ActivityRecord{4ab93c6 u0 com.test.thalitest/.MainActivity t3} time:107285
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SurfaceFlinger(  259): id=14 Removed Starting com.test.thalitest (7/8)
I/SurfaceFlinger(  259): id=14 Removed Starting com.test.thalitest (-2/8)
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/LightSensor(  914): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
D/CustomFrequencyManagerService(  914): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 914  tag : ACTIVITY_RESUME_BOOSTER@10
D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
W/GAV2    ( 7259): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/Zygote  ( 7348): MountEmulatedStorage()
E/Zygote  ( 7348): v2
I/libpersona( 7348): KNOX_SDCARD checking this for 10098
I/libpersona( 7348): KNOX_SDCARD not a persona
I/ActivityManager(  914): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7348 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
I/SELinux ( 7348): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7348): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7348): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7348): TimaSignature is unavailable
D/ActivityThread( 7348): Added TimaKeyStore provider
D/ResourcesManager( 7348): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
E/LightSensor(  914): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
W/ResourcesManager( 7348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
E/[CarMode]( 7348): [DLApplication]-onCreate: Applicatino Started!
D/SampleAppCoreManager( 7348): SampleAppCoreManager VACVersion '2.2.0.11867'
I/VlingoAndroidCore( 7348): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  914): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7375 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
E/Zygote  ( 7375): MountEmulatedStorage()
E/Zygote  ( 7375): v2
I/libpersona( 7375): KNOX_SDCARD checking this for 10032
I/libpersona( 7375): KNOX_SDCARD not a persona
I/SELinux ( 7375): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7375): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7375): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/LightSensor(  914): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
D/TimaKeyStoreProvider( 7375): TimaSignature is unavailable
D/ActivityThread( 7375): Added TimaKeyStore provider
D/ResourcesManager( 7375): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/ResourcesManager( 7375): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/System.out( 7375): Inside onCreate() of WakeupTriggerProvide
I/System.out( 7375): Inside WakeupProvider
E/DatabaseUtils( 7375): Writing exception to parcel
E/DatabaseUtils( 7375): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7375): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7375): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7375): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7375): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7375): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7375): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7375): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7375): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7375): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7375): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7348): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/GAV2    ( 7259): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  914): Killing 6193:com.sec.android.app.sns3/u0a35 (adj 15): bgCount ##41
W/System.err( 7348): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7348): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7348): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7348): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7348): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7348): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7348): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7348): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7348): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7348): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7348): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7348): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7348): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7348): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7348): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7348): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7348): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7348): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7348): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
I/VlingoApplication( 7375): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
W/System.err( 7348): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7348): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7348): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7348): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7348): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7348): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7348): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7348): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7348): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7348): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7348): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7348): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/DatabaseUtils( 7375): Writing exception to parcel
E/DatabaseUtils( 7375): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7375): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7375): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7375): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7375): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7375): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7375): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7375): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7375): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7375): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7375): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7348): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 7348): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7348): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7348): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7348): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7348): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7348): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7348): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7348): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7348): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7348): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7348): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7348): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7348): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7348): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7348): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 7348): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7348): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7348): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7348): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7348): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7348): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7348): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7348): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7348): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7348): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7348): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7348): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7348): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 7348): [DLApplication]-Init Called!:false
E/[CarMode]( 7348): [DLApplication]-Init Started!:true
I/VlingoAndroidCore( 7375): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
I/[CarModeFW]( 7348): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7348): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7348): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7348): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7348): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7348): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7348): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7348): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7348): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7348): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7348): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7348): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7348): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7348): ### com.android.internal.os.ZygoteInit::main(1194)
I/MessageDataHandler( 7348): initialize
D/[CarModeFW]( 7348): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 7348): CDH-initiazlieCaches : after sync
E/LightSensor(  914): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
W/libprocessgroup(  914): failed to open /acct/uid_10035/pid_6193/cgroup.procs: No such file or directory
D/[CarModeFW]( 7348): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7348): CDH-ContactDataHandler initiazlieCaches time : 27
D/[CarModeFW]( 7348): CDH-initiazlieCaches : end sync
D/[CarModeFW]( 7348): DrivingManager-initialize...
D/VlingoApplication( 7375): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
I/SensorService(  914): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  914): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  914): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
D/VlingoApplication( 7375): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
I/MediaPlayer( 7348): Need to enable context aware info
V/MediaPlayer-JNI( 7348): native_setup
V/MediaPlayer( 7348): constructor
V/MediaPlayer( 7348): setListener
E/MediaPlayer-JNI( 7348): QCMediaPlayer mediaplayer NOT present
D/[CarModeFW]( 7348): PushMessageManager-bindPushMessageService
I/[CarModeFW]( 7348): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode]( 7348): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarModeFW]( 7348): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1452267202188
D/[CarMode]( 7348): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 7348): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1452267202189
I/[CarMode]( 7348): [LogNotNull]-Package name is: com.google.android.apps.maps
D/[CarModeFW]( 7348): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1452267202190
D/[CarModeFW]( 7348): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1452267202191
D/[CarModeFW]( 7348): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1452267202191
D/[CarModeFW]( 7348): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1452267202191
E/[CarMode]( 7348): [DLApplication]-Init End!:true
D/TP/SmsProvider( 1464): query,matched:2, calling pid = 7348
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 1464): match 2:Elapsed time : 1.671 ms
E/Zygote  ( 7415): MountEmulatedStorage()
I/libpersona( 7415): KNOX_SDCARD checking this for 10003
E/Zygote  ( 7415): v2
I/libpersona( 7415): KNOX_SDCARD not a persona
I/ActivityManager(  914): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7415 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
E/LightSensor(  914): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
I/SELinux ( 7415): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/TP/SmsProvider( 1464): query,matched:2, calling pid = 7348
I/SELinux ( 7415): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/TP/SmsProvider( 1464): match 2:Elapsed time : 0.948 ms
D/[CarModeFW]( 7348): CDH-buildContactCacheWireFrame : cur len =0
D/MessageDataHandler( 7348):  getInboxList smsCursor : 55
E/SELinux ( 7415): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TP/MmsProvider( 1464): Query uri=content://mms/inbox, match=2, calling pid = 7348
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
D/[CarMode]( 7348): [DLApplication]-GooglePlayServices SUCCESS.
,E/Zygote  ( 7429): MountEmulatedStorage()
E/Zygote  ( 7429): v2
I/libpersona( 7429): KNOX_SDCARD checking this for 10019
I/libpersona( 7429): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7429 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,E/[CarMode]( 7348): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,I/UpdateManagerReceiver( 7348): Intent : android.intent.action.PACKAGE_ADDEDFri Jan 08 16:33:22 GMT+01:00 2016
,I/SELinux ( 7429): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7429): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7429): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/TimaKeyStoreProvider( 7415): TimaSignature is unavailable
,D/ActivityThread( 7415): Added TimaKeyStore provider
,D/MessageDataHandler( 7348):  getInboxList mmsCursor : 92
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/Zygote  ( 7437): MountEmulatedStorage()
I/libpersona( 7437): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7437): v2
I/libpersona( 7437): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7437 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7437): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7437): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7437): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7429): TimaSignature is unavailable
D/ActivityThread( 7429): Added TimaKeyStore provider
E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
D/[CarModeFW]( 7348): CDH-buildContactCacheWireFrame : cur len =0
I/ActivityManager(  914): Killing 6231:com.sec.spp.push:RemoteDlcProcess/u0a37 (adj 15): bgCount ##41
D/TP/MmsProvider( 1464): Query uri=content://mms, match=0, calling pid = 7348
D/MessageDataHandler( 7348):  getInboxList mms,sms cursor join : 95
D/TimaKeyStoreProvider( 7437): TimaSignature is unavailable
D/ActivityThread( 7437): Added TimaKeyStore provider
D/ResourcesManager( 7415): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/TP/MmsSmsProvider( 1464): query,matched:0, calling pid = 7348
,V/TP/MmsSmsProvider( 1464): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1464): match 0:Elapsed time : 1.267 ms
D/[CarModeFW]( 7348): RecommendHandler-selection = type = '3'
,I/MessageDataHandler( 7348): getUnreadMessageCount :0
,D/[CarModeFW]( 7348): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 273
,D/ResourcesManager( 7437): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/[CarModeFW]( 7348): PushMessageService-onCreate
,D/[CarModeFW]( 7348): CDH-buildContactCacheWireFrame : cur len =0
,D/TP/MmsSmsProvider( 1464): query,matched:13, calling pid = 7348
,D/ResourcesManager( 7429): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,D/TP/MmsSmsProvider( 1464): match 13:Elapsed time : 2.130 ms
,D/UserAnalysis.PlaceProvider( 7415): PlaceProvider onCreate()
,D/[CarModeFW]( 7348): RecommendHandler-selection = type = '3'
,I/ActivityManager(  914): Killing 4811:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,I/ActivityManager(  914): Killing 6418:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##42
,I/ActivityManager(  914): Killing 6250:com.sec.spp.push:RemoteNotiProcess/u0a37 (adj 15): bgCount ##43
,D/MessageDataHandler( 7348):  getInboxList address cursor : 16
,D/TP/MmsSmsProvider( 1464): query,matched:0, calling pid = 7348
V/TP/MmsSmsProvider( 1464): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1464): match 0:Elapsed time : 1.330 ms
,D/MessageDataHandler( 7348):  getInboxList thread cursor : 8
,D/[CarModeFW]( 7348): PushMessageManager-onServiceConnected
D/MessageDataHandler( 7348):  thread, addr result: 1
I/[CarModeFW]( 7348): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 307
I/[CarModeFW]( 7348): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7348): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 308
,D/[CarModeFW]( 7348): PushMessageService-registerPushMessageServiceListener
,W/ContextImpl( 7437): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7462): MountEmulatedStorage()
I/libpersona( 7462): KNOX_SDCARD checking this for 10111
E/Zygote  ( 7462): v2
I/libpersona( 7462): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7462 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  914): failed to open /acct/uid_10037/pid_6231/cgroup.procs: No such file or directory
,I/SELinux ( 7462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7462): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UserAnalysis.SecureDbManager( 7415): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 7415): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7415): Create SecureDbHelper
,D/ResourcesManager( 7437): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/TimaKeyStoreProvider( 7462): TimaSignature is unavailable
,D/ActivityThread( 7462): Added TimaKeyStore provider
,E/FilterInstaller( 7437): There is no requred permission
,D/ResourcesManager( 7462): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/ActivityManager(  914): Killing 6107:com.google.android.talk/u0a116 (adj 15): bgCount ##41
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/IntelligenceServiceApplication( 7415): onCreate()
,I/SQLiteSecureOpenHelper( 7415): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 7415): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7415): Open Place.db in secure mode
,I/SQLiteSecureOpenHelper( 7415): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 7415): ...getDatabaseLocked(b,b,pwd)
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,D/PackageIntentReceiver( 7462): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7462): Not GearManger package! 
,E/Zygote  ( 7479): MountEmulatedStorage()
I/libpersona( 7479): KNOX_SDCARD checking this for 10045
E/Zygote  ( 7479): v2
I/libpersona( 7479): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7479 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,I/art     (  321): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 267us total 11.562ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 7.908ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 260us total 7.791ms
,E/Zygote  ( 7486): MountEmulatedStorage()
I/libpersona( 7486): KNOX_SDCARD checking this for 10117
E/Zygote  ( 7486): v2
I/libpersona( 7486): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7486 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  914): Killing 6476:com.samsung.android.app.FileShareServer/u0a74 (adj 15): bgCount ##41
,I/SELinux ( 7479): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7479): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/SELinux ( 7486): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,E/SELinux ( 7479): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/SELinux ( 7486): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7486): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  914): failed to open /acct/uid_1000/pid_6418/cgroup.procs: No such file or directory
,W/libprocessgroup(  914): failed to open /acct/uid_10037/pid_6250/cgroup.procs: No such file or directory
W/libprocessgroup(  914): failed to open /acct/uid_10045/pid_4811/cgroup.procs: No such file or directory
,D/[CarModeFW]( 7348): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 7348): MyPlaceProvider-=============
,D/[CarModeFW]( 7348): MyPlaceProvider-=============
D/[CarModeFW]( 7348): MyPlaceProvider-=============
D/[CarModeFW]( 7348): MyPlaceProvider-=============
D/[CarModeFW]( 7348): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7348): MyPlaceProvider-==============
D/[CarModeFW]( 7348): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7348): MyPlaceProvider-==============
D/[CarModeFW]( 7348): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7348): MyPlaceProvider-==============
D/[CarModeFW]( 7348): MyPlaceProvider-latitude is not valid
,D/TimaKeyStoreProvider( 7479): TimaSignature is unavailable
E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/TimaKeyStoreProvider( 7486): TimaSignature is unavailable
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/ActivityThread( 7486): Added TimaKeyStore provider
D/ActivityThread( 7479): Added TimaKeyStore provider
,D/[CarModeFW]( 7348): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 592
I/[CarModeFW]( 7348): -[snowdeer] Rec : Missed Call : 300
D/[CarModeFW]( 7348): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 594
,I/ActivityManager(  914): Killing 6494:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,W/jxcore-log( 7290): Initializing JXcore engine
W/jxcore-log( 7290): JXcore engine is ready
,W/jxcore-log( 7290): Starting JXcore engine
,D/[CarMode]( 7348): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@df4cb24f, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@dba94199] LOCATIONS
,D/ResourcesManager( 7479): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 7479): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/ResourcesManager( 7486): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 7486): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/auditd  ( 2177): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  914): Got Modify Event and sending Denial Intent foraudit.log
,W/libprocessgroup(  914): failed to open /acct/uid_10116/pid_6107/cgroup.procs: No such file or directory
,W/libprocessgroup(  914): failed to open /acct/uid_10074/pid_6476/cgroup.procs: No such file or directory
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/MagazineService Version( 7486): Magazine-Administrator: 11
,D/SecurityLogAgent:SEDenialService(  914): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,D/MagazineService Version( 7486): Magazine-Provider: 14
,D/MagazineService Version( 7486): Magazine-Channel: 14
,D/HeadlinesChannelApplication( 7486): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7486): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,I/CalendarProvider2( 7479): CalendarProvider2.onCreate() called
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7486): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 7511): MountEmulatedStorage()
,E/Zygote  ( 7511): v2
I/libpersona( 7511): KNOX_SDCARD checking this for 1000
I/libpersona( 7511): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7511 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7486): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/art     (  914): Explicit concurrent mark sweep GC freed 217558(14MB) AllocSpace objects, 5(4MB) LOS objects, 31% free, 35MB/51MB, paused 1.942ms total 115.776ms
,I/ActivityManager(  914): Killing 6536:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/[CarModeFW]( 7348): -[snowdeer] Rec : Favorite : 138
,I/[CarModeFW]( 7348): -[snowdeer] Rec : CallLog : 5
,E/LightSensor(  914): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
W/jxcore-log( 7290): Platform android
W/jxcore-log( 7290): 
W/jxcore-log( 7290): Process ARCH arm
W/jxcore-log( 7290): 
,I/SELinux ( 7511): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7511): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7511): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  914): failed to open /acct/uid_1000/pid_6494/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7511): TimaSignature is unavailable
,D/ActivityThread( 7511): Added TimaKeyStore provider
,D/ResourcesManager( 7511): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/libprocessgroup(  914): failed to open /acct/uid_1000/pid_6536/cgroup.procs: No such file or directory
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7527): MountEmulatedStorage()
E/Zygote  ( 7527): v2
I/libpersona( 7527): KNOX_SDCARD checking this for 1000
I/libpersona( 7527): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7527 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  914): Killing 5842:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,I/System.out( 7375): INFO:Resource not found:/Common.properties Using default values
,I/SELinux ( 7527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7527): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7527): TimaSignature is unavailable
,D/ActivityThread( 7527): Added TimaKeyStore provider
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/[CarModeFW]( 7348): -[snowdeer] Rec : Schedule : 212
,I/[CarModeFW]( 7348): -[snowdeer] Rec : During DL app : 5
,D/ResourcesManager( 7527): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,I/[CarModeFW]( 7348): -[snowdeer] Rec : Location Sharing : 2
I/[CarModeFW]( 7348): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 7348): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7348): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
,I/[CarModeFW]( 7348): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 7348): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 7348): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 961
,I/[CarModeFW]( 7348): -[snowdeer] Rec : getContactListFromHashMap - core : 0
,I/[CarModeFW]( 7348): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7348): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7348): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 960
,W/libprocessgroup(  914): failed to open /acct/uid_1000/pid_5842/cgroup.procs: No such file or directory
,D/AcmsPackageEventListener( 7527): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 7527): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService( 7527): Enter Oncreate
D/AcmsServiceMonitor( 7527): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 7527): creating AcmsCore
,D/AcmsCore( 7527): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7527): AcmsCore
,D/AcmsCore( 7527): init
D/AcmsCore( 7527): Looper handler is not null
D/AcmsCore( 7527): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7527): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7527): Incrementing - Counter value: 1
D/AcmsCore( 7527): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 7527): onStartCommand
D/AcmsCertificateMngr( 7527): AcmsCertificateMngr
,D/AcmsRevocationMngr( 7527): AcmsRevocationMngr
D/AcmsService( 7527): Action: android.intent.action.PACKAGE_ADDED
,D/AcmsServiceMonitor( 7527): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7527): Incrementing - Counter value: 2
D/AcmsService( 7527): Incremented Counter Value : onStartCommand
,D/ActivityThread( 7527): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7549): MountEmulatedStorage()
E/Zygote  ( 7549): v2
I/libpersona( 7549): KNOX_SDCARD checking this for 10165
I/libpersona( 7549): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7549 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/SELinux ( 7549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7549): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7549): TimaSignature is unavailable
,D/AcmsService( 7527): Inside handle Intent
D/AcmsService( 7527): App added - package name: com.test.thalitest
D/AcmsCore( 7527): Post to AcmsCoreHandler
,D/ActivityThread( 7549): Added TimaKeyStore provider
D/AcmsServiceMonitor( 7527): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7527): Incrementing - Counter value: 3
D/AcmsCore( 7527): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7527): Decremented Counter Value : handleStartIntent
,D/AcmsServiceMonitor( 7527): Decrementing - Counter value: 2
,D/ResourcesManager( 7549): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7549): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 7549): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7564): MountEmulatedStorage()
E/Zygote  ( 7564): v2
I/libpersona( 7564): KNOX_SDCARD checking this for 10169
I/libpersona( 7564): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7564 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 7564): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7564): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7564): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/TimaKeyStoreProvider( 7564): TimaSignature is unavailable
,D/ActivityThread( 7564): Added TimaKeyStore provider
,D/ResourcesManager( 7564): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/PowerManagerService(  914): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  914): [s] DisplayPowerCallbacks : onStateChanged()
,W/art     ( 7375): Suspending all threads took: 6.478ms
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
D/lights  (  914): lcd : 1 +
,D/AcmsKeyStoreHelper( 7527):  getKeyStoreForApplication Enter
,D/lights  (  914): lcd : 1 -
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/SQLiteLog( 7564): (284) automatic index on shooting_modes(title_id)
,I/AcmsKeyStoreHelper( 7527): Key Store exist
I/AcmsKeyStoreHelper( 7527): Hence loading the keystore file
,D/Finsky  ( 6581): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/PackageBroadcastService( 2473): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/ActivityManager(  914): Killing 6070:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
,D/ChimeraCfgMgr( 2473): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2473): Loading module APK com.google.android.play.games
,D/ResourcesManager( 2473): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,I/jxcore-log( 7290): JXcore Cordova bridge is ready!
I/jxcore-log( 7290): 
,W/jxcore-log( 7290): JXcore engine is started
,W/libprocessgroup(  914): failed to open /acct/uid_10167/pid_6070/cgroup.procs: No such file or directory
,E/SMD     (  295): DCD ON
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/Adreno-ES20( 7290): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7290): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/AcmsKeyStoreHelper( 7527):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 7527): getKeyStoreForApplication success 
D/AcmsCore( 7527): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7527): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7527): Decrementing - Counter value: 1
D/AcmsCore( 7527): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 7527): This is NOT a valid MirrorLink app
D/AcmsCore( 7527): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7527): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 7527): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7527): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7527): getSvcCounter - Counter value: 0
,D/AcmsService( 7527): Enter onDestroy
,I/AcmsService( 7527): cleanUp(): inside service clean up
D/AcmsCore( 7527): AcmsCore: inside DeInit
D/AcmsCore( 7527): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7527): AcmsCertificateMngr: inside cleanup
,D/AcmsRevocationMngr( 7527): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7527): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7527): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 7527): getSvcCounter - Counter value: 0
,D/AcmsService( 7527): killing acms process
I/Process ( 7527): Sending signal. PID: 7527 SIG: 9
,I/ActivityManager(  914): Process ACMS.Process (pid 7527)(adj 0) has died(55,581)
,I/jxcore-log( 7290): Toggling radios to true
I/jxcore-log( 7290): 
,D/BluetoothAdapter( 7290): enable()
,D/BluetoothAdapter( 7290): enable(): BT is already enabled..!
,D/WifiService(  914): New client listening to asynchronous messages
,I/WifiManager( 7290): packageName : com.test.thalitest
,D/SecContentProvider(  914): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  914): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  914): mCursor = null
,D/WifiService(  914): setWifiEnabled: true pid=7290, uid=10356
E/WifiService(  914): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  914): Permission Denial: getCurrentUser() from pid=7290, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  914): Failed getting userId using ActivityManagerNative
W/WifiService(  914): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7290, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  914): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  914): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  914): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  914): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  914): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  914): name = wifi_on
,I/WifiService(  914): disconnect: pid=7290, uid=10356
,I/jxcore-log( 7290): Radios toggled
I/jxcore-log( 7290): 
,I/wpa_supplicant( 1305): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 1305): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1305): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1305): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1305): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  914): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1305): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1305): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1305): Disconnected - do not scan
I/wpa_supplicant( 1305): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  914): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  914): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  914): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  914): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ChimeraCfgMgr( 2473): Loading module com.google.android.gms.games from APK com.google.android.play.games
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/WifiStateMachine(  914): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  914): InactiveState{ what=143375 }
,D/CommandListener(  286): Clearing all IP addresses on wlan0
D/WifiP2pService(  914): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ChimeraModuleLdr( 2473): Module APK com.google.android.play.games already loaded
,V/NativeCrypto( 2256): Read error: ssl=0xb4e64600: I/O error during system call, Connection timed out
,V/NativeCrypto( 2256): SSL shutdown failed: ssl=0xb4e64600: I/O error during system call, Broken pipe
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  914): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  914): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  914): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  914): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  914): Validated
D/ConnectivityService(  914): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  914): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  914):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  914):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  914):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  914): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  914): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  914): calling update connectivity
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  914): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  914): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  914): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524290
,E/WifiConfigStore(  914): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/ConnectivityService(  914): updateNetworkInfo()
,D/ConnectivityService(  914): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  914): updateNetworkInfo()
D/ConnectivityService(  914): ignoring duplicate network state non-change
,D/ConnectivityService(  914): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/ConnectivityManager.CallbackHandler( 2473): CM callback handler got msg 524290
,E/WifiStateMachine(  914): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1305): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1305): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1305): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1305): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1305): First Scan Start
,I/wpa_supplicant( 1305): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  914): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  914): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  914): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  914): InactiveState{ what=143375 }
,D/WifiP2pService(  914): P2pEnabledState{ what=143375 }
,I/WifiTrafficPoller(  914): evaluateTrafficStatsPolling
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  914): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/ChimeraCfgMgr( 2473): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/CommandListener(  286): Clearing all IP addresses on wlan0
,D/ConnectivityService(  914): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  914): calling update connectivity
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  914): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  914): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  914): Not allowed due to - mEnabled false
D/Nat464Xlat(  914): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 2473): CM callback handler got msg 524292
E/WifiStateMachine(  914): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  914): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  914): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker(  914): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WifiStateMachine(  914): updateConfiguredNetworkExpiration - currTime: 1452267203972
D/CSLegacyTypeTracker(  914): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/WifiStateMachine(  914): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine(  914): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  914): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiNetworkAgent(  914): NetworkAgent: NetworkAgent channel lost
I/WifiTrafficPoller(  914): evaluateTrafficStatsPolling
,D/TelephonyNetworkFactory( 1464): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  914): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  914): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  914): setDetailed state send new extra info"NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  914): ValidatedState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  914): DefaultState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  914): Disconnected - quitting
,I/CLocInfoService(  914): External Intent Received android.net.wifi.STATE_CHANGE
,D/SecContentProvider2(  914): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  914): mCursor = null
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  914): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  914): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  914): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  914): getSBEnabled() enabled =false
,V/NetworkStats(  914): updateIfacesLocked()
D/SecContentProvider2(  914): uri = 20 selection = getPromptCredentialsEnabled
V/NetworkStats(  914): performPollLocked(flags=0x1)
D/SecContentProvider2(  914): mCursor = null
D/NtpTrustedTime(  914): currentTimeMillis() cache hit
,D/SmartBondingService(  914): getSBEnabled() enabled =false
D/SmartBondingService(  914): getSBEnabled() enabled =false
,D/NetworkStatsFactory(  914): UpdateStatsForKnox
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1184): updateDataNetType()
D/StatusBar.NetworkController( 1184): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1184): updateLTEICONDataNetType:0
,V/NetworkStats(  914): performPollLocked() took 5ms
D/NtpTrustedTime(  914): currentTimeMillis() cache hit
,D/SmartBondingService(  914): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  914): currentTimeMillis() cache hit
D/NtpTrustedTime(  914): currentTimeMillis() cache hit
D/NtpTrustedTime(  914): currentTimeMillis() cache hit
V/NetworkStats(  914): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  914): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1184): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/NtpTrustedTime(  914): currentTimeMillis() cache hit
,D/NtpTrustedTime(  914): currentTimeMillis() cache hit
,D/AsyncTaskServiceImpl( 2473): Submit a task: k
,D/ChimeraCfgMgr( 2473): Loading module com.google.android.gms.gass from APK com.google.android.gms
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,D/ChimeraCfgMgr( 2473): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2473): Processing package: com.test.thalitest
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,W/BaseAppContext( 2473): Using Auth Proxy for data requests.
W/BaseAppContext( 2473): Using Auth Proxy for data requests.
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,I/PeopleDatabaseHelper( 2473): cleanUpNonGplusAccounts done.
,D/GassUtils( 2473): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
,D/k       ( 2473): Found info for package com.test.thalitest in db.
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7607): MountEmulatedStorage()
E/Zygote  ( 7607): v2
I/libpersona( 7607): KNOX_SDCARD checking this for 10039
I/libpersona( 7607): KNOX_SDCARD not a persona
I/ActivityManager(  914): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7607 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7607): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7607): TimaSignature is unavailable
,D/ActivityThread( 7607): Added TimaKeyStore provider
,I/CalendarProvider2( 7479): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,W/BaseAppContext( 2473): Using Auth Proxy for data requests.
,D/ResourcesManager( 7607): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,I/ActivityManager(  914): Killing 6028:com.google.android.gm/u0a113 (adj 15): bgCount ##41
,W/BaseAppContext( 2473): Using Auth Proxy for data requests.
,W/BaseAppContext( 2473): Using Auth Proxy for data requests.
W/BaseAppContext( 2473): Using Auth Proxy for data requests.
,W/BaseAppContext( 2473): Using Auth Proxy for data requests.
,W/libprocessgroup(  914): failed to open /acct/uid_10113/pid_6028/cgroup.procs: No such file or directory
,V/TaskCloserActivity( 5859): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,I/ActivityManager(  914): Killing 6299:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,D/BootupListener( 1464): ACTION_DRIVELINK
,D/SettingsProvider(  914): name = drivelink_navigation
D/SettingsProvider(  914): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  914): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  914): selectionArgs: false
D/SettingsProvider(  914): selectionArgs: 1001
D/SecContentProvider(  914): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  914): ret = -1
D/BootupListener( 1464): NAVI : com.google.android.apps.maps
,D/SettingsProvider(  914): name = internet_call_settings_visibility
D/SettingsProvider(  914): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  914): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  914): selectionArgs: false
D/SettingsProvider(  914): selectionArgs: 1001
,D/SecContentProvider(  914): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  914): ret = -1
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7624): MountEmulatedStorage()
E/Zygote  ( 7624): v2
I/libpersona( 7624): KNOX_SDCARD checking this for 1000
I/libpersona( 7624): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7624 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,I/SELinux ( 7624): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7624): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7624): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7624): TimaSignature is unavailable
,D/ActivityThread( 7624): Added TimaKeyStore provider
,W/libprocessgroup(  914): failed to open /acct/uid_10004/pid_6299/cgroup.procs: No such file or directory
,D/ResourcesManager( 7624): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7624):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7624):  SeDenialReceiver : File path = null
,I/ActivityManager(  914): Killing 6371:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
,I/Hs20UtilService( 1313): Starting #6
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  914): updateDataUsageMap
,D/Tethering(  914): MasterInitialState.processMessage what=3
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  914): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  914): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  914): getSBEnabled() enabled =false
D/SmartBondingService(  914): getSBEnabled() enabled =false
D/SmartBondingService(  914): getSBEnabled() enabled =false
I/CLocInfoService(  914): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  914): CLoinfo wifi false
D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/SLocation(  914): No Active Data Connection
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2113): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/SmartBondingService(  914): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6267): type=WIFI subType= reason=null isConnected=false
,I/Hs20UtilService( 1313): Starting #7
,I/Hs20UtilService( 1313): Message received 5007
,I/DBG_DM  ( 3748): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3748): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7639): MountEmulatedStorage()
I/libpersona( 7639): KNOX_SDCARD checking this for 10148
E/Zygote  ( 7639): v2
I/libpersona( 7639): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7639 uid=10148 gids={50148, 9997} abi=armeabi-v7a
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,I/SELinux ( 7639): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  914): failed to open /acct/uid_10043/pid_6371/cgroup.procs: No such file or directory
,I/SELinux ( 7639): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7639): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7639): TimaSignature is unavailable
,D/ActivityThread( 7639): Added TimaKeyStore provider
,D/ResourcesManager( 7639): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 7639): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7639): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7654): MountEmulatedStorage()
,E/Zygote  ( 7654): v2
I/libpersona( 7654): KNOX_SDCARD checking this for 10149
I/libpersona( 7654): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7654 uid=10149 gids={50149, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager(  914): Killing 6267:com.google.android.music:main/u0a125 (adj 15): bgCount ##41
,W/art     ( 2473): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 107.710ms
,I/SELinux ( 7654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7654): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  914): failed to open /acct/uid_10125/pid_6267/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7654): TimaSignature is unavailable
,D/ActivityThread( 7654): Added TimaKeyStore provider
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 7654): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7654): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7654): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7654): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1349): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/PCWCLIENTTRACE_PushUtil( 7156): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7156): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7156): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7156): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7156): noConnectivity : true
,E/Zygote  ( 7677): MountEmulatedStorage()
E/Zygote  ( 7677): v2
I/libpersona( 7677): KNOX_SDCARD checking this for 10125
I/libpersona( 7677): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7677 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ChimeraCfgMgr( 2473): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2473): Module APK com.google.android.play.games already loaded
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,I/SELinux ( 7677): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7677): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7677): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7677): TimaSignature is unavailable
,D/ActivityThread( 7677): Added TimaKeyStore provider
,D/ResourcesManager( 7677): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/ActivityManager(  914): Killing 6811:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
,I/wpa_supplicant( 1305): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 1305): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1305): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1305): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1305): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
E/WifiStateMachine(  914): [1,452,267,204,996 ms] noteScanEnd no scan source
,E/WifiStateMachine(  914): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@249e677f sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  914): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  914): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  914): setDetailed state send new extra info0x
,D/SecContentProvider2(  914): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  914): mCursor = null
,I/CLocInfoService(  914): External Intent Received android.net.wifi.SCAN_RESULTS
,W/libprocessgroup(  914): failed to open /acct/uid_10011/pid_6811/cgroup.procs: No such file or directory
,I/MusicStore( 7677): Database version: 104
,I/wpa_supplicant( 1305): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1305): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine(  914): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  914): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/wpa_supplicant( 1305): Associated with C0.AA.48
,D/SecContentProvider2(  914): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  914): mCursor = null
,I/wpa_supplicant( 1305): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1305): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  914): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  914): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  914): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  914): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  914): mCursor = null
,I/wpa_supplicant( 1305): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1305): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1305): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1305): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1305): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1305): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1305): Blacklist: Clear (temp) 
I/wpa_supplicant( 1305): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  914): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  914): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  914): Network connection established
,D/WifiNative-HAL(  914): callSECApiVoid - ID [50]
E/WifiStateMachine(  914): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,D/ResourcesManager( 7677): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/CLocInfoService(  914): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  914): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  914): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,W/ResourcesManager( 7677): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/ConnectivityService(  914): Got NetworkAgent Messenger
D/ConnectivityService(  914): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  914): updateNetworkInfo()
D/ConnectivityService(  914): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  914): NetworkAgent connected
E/WifiStateMachine(  914): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  914): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  914): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/ResourcesManager( 7677): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/WifiStateMachine(  914): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  914): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  914): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  914): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  286): Setting iface cfg
,E/WifiStateMachine(  914): Start Dhcp Watchdog 2
,D/SecContentProvider2(  914): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  914): mCursor = null
,V/JNIHelp ( 7677): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  914): calculateWifiScore() report new score 60
I/WifiStateMachine(  914): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  914): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  914): CMD_RSSI_POLL : out!
,D/ConnectivityService(  914): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  914): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  914): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  914): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,W/ActivityThread( 7677): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7677): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1324146d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7677): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7677): GMSCore installation verified
,I/ConfigStore( 7677): Config Database version: 1
,I/Icing   ( 2473): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,E/WifiStateMachine(  914): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  914): do suspend false
,W/ContextImpl( 7677): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/SecContentProvider2(  914): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  914): mCursor = null
D/WifiP2pService(  914): InactiveState{ what=143375 }
D/WifiP2pService(  914): P2pEnabledState{ what=143375 }
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7677): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7677): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  914): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager( 2473): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/WifiDisplayAdapter(  914): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  300): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  914): getStreamVolume 3 index 0
,I/MediaRouter( 7677): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,I/Icing   ( 2473): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7706): MountEmulatedStorage()
E/Zygote  ( 7706): v2
I/libpersona( 7706): KNOX_SDCARD checking this for 10002
I/libpersona( 7706): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7706 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  321): Explicit concurrent mark sweep GC freed 8741(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 12.207ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 246us total 7.737ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.927ms
,I/SELinux ( 7706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7706): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter(  914): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider( 7706): TimaSignature is unavailable
,D/ActivityThread( 7706): Added TimaKeyStore provider
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7706): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/NetworkMonitor( 7677): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager(  914): Killing 5959:com.sec.android.widgetapp.digitalclock/u0a93 (adj 15): bgCount ##41
,I/ActivityManager(  914): Killing 5978:com.sec.android.widgetapp.dualclockdigital/u0a102 (adj 15): bgCount ##41
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7726): MountEmulatedStorage()
,E/Zygote  ( 7726): v2
I/libpersona( 7726): KNOX_SDCARD checking this for 1000
I/libpersona( 7726): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7726 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/dhcpcd  ( 7725): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7725): version 5.5.6 starting
,E/dhcpcd  ( 7725): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,I/SELinux ( 7726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7726): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  914): failed to open /acct/uid_10093/pid_5959/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7726): TimaSignature is unavailable
,D/ActivityThread( 7726): Added TimaKeyStore provider
I/dhcpcd  ( 7725): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7725): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7725): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7725): bssid match
,I/dhcpcd  ( 7725): wlan0: rebinding lease of 192.168.1.136
,D/ResourcesManager( 7726): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  914): failed to open /acct/uid_10102/pid_5978/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7726): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7726): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,W/SQLiteConnectionPool( 2473): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,I/DIAGMON_AGENT( 7726): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7726): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7726): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7726): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7748): MountEmulatedStorage()
E/Zygote  ( 7748): v2
I/libpersona( 7748): KNOX_SDCARD checking this for 10010
I/libpersona( 7748): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7748 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7748): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7748): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7748): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7748): TimaSignature is unavailable
,D/ActivityThread( 7748): Added TimaKeyStore provider
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 7748): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  914): Killing 5704:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
,I/FOTA_Client( 7748): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7748): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7748): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7766): MountEmulatedStorage()
,E/Zygote  ( 7766): v2
I/libpersona( 7766): KNOX_SDCARD checking this for 10018
I/libpersona( 7766): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7766 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  914): Killing 6001:com.sec.android.app.camera/u0a153 (adj 15): bgCount ##41
,I/dhcpcd  ( 7725): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,I/SELinux ( 7766): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7766): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7766): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  914): failed to open /acct/uid_10112/pid_5704/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7725): wlan0: leased 192.168.1.136 for 86400 seconds
,D/TimaKeyStoreProvider( 7766): TimaSignature is unavailable
,E/WifiStateMachine(  914): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  914): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  914): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/ActivityThread( 7766): Added TimaKeyStore provider
,D/ResourcesManager( 7766): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/libprocessgroup(  914): failed to open /acct/uid_10153/pid_6001/cgroup.procs: No such file or directory
,D/FactoryTest( 6631): Not factory mode
D/FactoryTest( 6631): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6631): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6631): still no open session command from host, so toast
,W/ContextImpl( 6631): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6631): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6631): Timeline: Activity_launch_request id:com.android.settings time:112002
,E/PersonaManagerService(  914): inState():  stateMachine is null !!
,V/ApplicationPolicy(  914): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  914): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  914): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 914  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  914): mDVFSHelper.acquire()
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,I/KLMS-2.4.503: ( 7766): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7766): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452267206020
,I/KLMS-2.4.503: ( 7766): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7766): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7766): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,E/MTPRx   ( 6631): started activity for popup
I/ActivityManager(  914): Killing 6991:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): bgCount ##41
,I/SQLiteSecureOpenHelper( 3520): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3520): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7797): MountEmulatedStorage()
E/Zygote  ( 7797): v2
I/libpersona( 7797): KNOX_SDCARD checking this for 10036
I/libpersona( 7797): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7797 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7797): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7797): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7797): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7797): TimaSignature is unavailable
,D/ActivityThread( 7797): Added TimaKeyStore provider
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  914): failed to open /acct/uid_10070/pid_6991/cgroup.procs: No such file or directory
,D/ResourcesManager( 7797): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7797): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/SPPClientService( 5198): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/ResourcesManager( 6631): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/SA      ( 7196): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7196): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 7196): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7196): [SLFUCHKMGR] constructor called
W/ResourcesManager( 6631): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6631): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6631): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6631): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6631): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6631): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6631): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SPPClientService( 5198): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 7196): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7196): [OR] == isSIMCardReady false ==
,I/SA      ( 7196): [SCU] == networkStateCheck == false
,I/SA      ( 7196): [OR] onReceive END
,E/SettingsReceiverActivity( 6631): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,E/WifiStateMachine(  914): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,I/ActivityManager(  914): Killing 7122:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
D/WifiP2pService(  914): InactiveState{ what=143375 }
,D/WifiP2pService(  914): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  914): WifiStateMachine DHCP successful
,E/WifiStateMachine(  914): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/Zygote  ( 7826): MountEmulatedStorage()
I/libpersona( 7826): KNOX_SDCARD checking this for 10070
E/Zygote  ( 7826): v2
I/libpersona( 7826): KNOX_SDCARD not a persona
,D/ConnectivityService(  914): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  914): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,I/ActivityManager(  914): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7826 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,E/WifiStateMachine(  914): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine(  914): Not connected state, yet.
E/WifiStateMachine(  914): VerifyingLinkState enter
,I/SELinux ( 7826): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/SELinux ( 7826): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7826): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  914): failed to open /acct/uid_10014/pid_7122/cgroup.procs: No such file or directory
,D/WifiStateMachine(  914): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  914): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  914): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
,D/WifiNative-HAL(  914): callSECApiInt - ID [210]
E/WifiStateMachine(  914): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  914): updateNetworkInfo()
,D/ConnectivityService(  914): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  914): Adding iface wlan0 to network 503
,I/CLocInfoService(  914): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiWatchdogStateMachine(  914): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  914): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  914): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  914): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  914): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,E/WifiStateMachine(  914): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  914): Now, connected state.
E/WifiStateMachine(  914): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/WifiTrafficPoller(  914): evaluateTrafficStatsPolling
,I/CLocInfoService(  914): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  914): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/TimaKeyStoreProvider( 7826): TimaSignature is unavailable
,D/ActivityThread( 7826): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/art     (  914): Explicit concurrent mark sweep GC freed 53484(2MB) AllocSpace objects, 2(1312KB) LOS objects, 30% free, 36MB/52MB, paused 7.001ms total 109.472ms
,E/WifiStateMachine(  914): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  914): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  914): mBoosterFLAG : 0
I/WifiTrafficPoller(  914): current booster mode : FullMode
,E/WifiStateMachine(  914): ConnectedState Enter  mScreenOn=true scanperiod=20000
,D/ConnectivityService(  914): Adding Route [fe80::/64 -> :: wlan0] to network 503
D/WifiNative-HAL(  914): callSECApiVoid - ID [212]
,D/ConnectivityService(  914): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  914): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/ConnectivityService(  914): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  914): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  914): updateSourceRoutes : add src route for:192.168.1.136
V/        (  286): QcRouteController
I/CLocInfoService(  914): External Intent Received android.net.wifi.STATE_CHANGE
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  914): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/        (  286): QcRouteController
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/        (  286): QcRouteController
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,D/ResourcesManager( 7826): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,W/ResourcesManager( 7826): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7826): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,W/ResourcesManager( 7826): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
V/        (  286): QcRouteController
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6631): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/        (  286): QcRouteController
,D/SettingsReceiverActivity( 6631): dev.kiessupport is : TRUE
,V/        (  286): QcRouteController
,V/        (  286): QcRouteController
,D/Activity( 6631): performCreate Call secproduct feature valuefalse
D/Activity( 6631): performCreate Call debug elastic valuetrue
,D/comsamsunglog( 7826): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7826): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7826): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7826): [KK AccuPhone]>>> ==============================================================================================
,V/        (  286): QcRouteController
,D/comsamsunglog( 7826): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7826): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7826): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
,D/comsamsunglog( 7826): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  914): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider(  914): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  914): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  914): selectionArgs: false
D/SettingsProvider(  914): selectionArgs: 10070
,D/SecContentProvider(  914): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  914): ret = -1
,D/daemonapp( 1349): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ConnectivityService(  914): Setting Dns servers for network 503 to [/192.168.1.1]
,E/ConnectivityService(  914): updateNetworkInfo()
D/Nat464Xlat(  914): requiresClat: netType=1, connected=false, hasIPv4Address=true
E/ConnectivityService(  914): updateNetworkInfo()
D/ConnectivityService(  914): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  914): calling update connectivity
D/ConnectivityService(  914): ignoring duplicate network state non-change
D/ConnectivityService(  914): ignoring duplicate network state non-change
D/ConnectivityService(  914): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  914): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  914): calling update connectivity
,D/ConnectivityService(  914): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  914):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  914):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  914):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  914):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  914): DefaultState{ when=-5ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  914): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  914): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  914): Validated
D/ConnectivityService(  914): currentScore = 0, newScore = 60
D/ConnectivityService(  914):    accepting network in place of null
D/ConnectivityService(  914): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1464): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  914): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  914): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  914): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  914): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/EntConnectivity(  914): Not allowed due to - mEnabled false
D/ConnectivityService(  914): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  914): calling update connectivity
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  914): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524290
D/SmartBondingService(  914): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  914): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/SmartBondingService(  914): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  914): getSBEnabled() enabled =false
D/SmartBondingService(  914): getSBEnabled() enabled =false
D/SmartBondingService(  914): getSBEnabled() enabled =false
,D/ConnectivityManager.CallbackHandler( 2473): CM callback handler got msg 524290
D/ConnectivityService(  914): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  914): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  914):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  914):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  914):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  914): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  914): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  914): calling update connectivity
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/SmartBondingService(  914): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  914): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  914): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524290
,V/NetworkStats(  914): updateIfacesLocked()
D/NtpTrustedTime(  914): currentTimeMillis() cache hit
V/NetworkStats(  914): performPollLocked(flags=0x1)
,D/ConnectivityManager.CallbackHandler( 2473): CM callback handler got msg 524290
D/NetworkStatsFactory(  914): UpdateStatsForKnox
D/ConnectivityService(  914): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1184): updateDataNetType()
D/StatusBar.NetworkController( 1184): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1184): updateLTEICONDataNetType:0
D/NtpTrustedTime(  914): currentTimeMillis() cache hit
,V/NetworkStats(  914): performPollLocked() took 4ms
D/NtpTrustedTime(  914): currentTimeMillis() cache hit
D/NtpTrustedTime(  914): currentTimeMillis() cache hit
D/NtpTrustedTime(  914): currentTimeMillis() cache hit
V/NetworkStats(  914): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  914): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1184): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NtpTrustedTime(  914): currentTimeMillis() cache hit
D/NtpTrustedTime(  914): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1184): updateDataNetType()
D/StatusBar.NetworkController( 1184): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1184): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1184): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/accuweather( 7826): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7826): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7826): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7826): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7826): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7826): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1349): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7826): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1349): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7826): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1349): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7826): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7826): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,W/ActivityManager(  914): Activity pause timeout for ActivityRecord{4ab93c6 u0 com.test.thalitest/.MainActivity t3}
,E/Zygote  ( 7860): MountEmulatedStorage()
,E/Zygote  ( 7860): v2
I/libpersona( 7860): KNOX_SDCARD checking this for 1000
I/libpersona( 7860): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7860 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  914): Killing 7140:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,I/SELinux ( 7860): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7860): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7860): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/TimaKeyStoreProvider( 7860): TimaSignature is unavailable
,D/ActivityThread( 7860): Added TimaKeyStore provider
,I/GAV2    ( 7259): Thread[GAThread,5,main]: No campaign data found.
,W/libprocessgroup(  914): failed to open /acct/uid_10015/pid_7140/cgroup.procs: No such file or directory
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7860): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7860): premStatus:2
,I/KnoxUsageLogPro( 7860): isEulaShown : false
,I/KnoxUsageLogPro( 7860): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7877): MountEmulatedStorage()
E/Zygote  ( 7877): v2
I/libpersona( 7877): KNOX_SDCARD checking this for 10087
I/libpersona( 7877): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7877 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  914): Killing 6449:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,E/SMD     (  295): DCD ON
,I/SELinux ( 7877): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7877): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7877): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7877): TimaSignature is unavailable
,D/ActivityThread( 7877): Added TimaKeyStore provider
,D/ResourcesManager( 7877): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  914): failed to open /acct/uid_10033/pid_6449/cgroup.procs: No such file or directory
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ActivityManager(  914): Killing 4840:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,D/Headlines( 5395): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5395): getCountryCode(): countryCode = PL
,D/Headlines( 5395): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5395): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5395): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5395): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5395): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5395): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5395): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7894): MountEmulatedStorage()
I/libpersona( 7894): KNOX_SDCARD checking this for 10127
E/Zygote  ( 7894): v2
I/libpersona( 7894): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7894 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7894): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7894): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7894): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,D/TimaKeyStoreProvider( 7894): TimaSignature is unavailable
,D/ActivityThread( 7894): Added TimaKeyStore provider
,D/ResourcesManager( 7894): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  914): failed to open /acct/uid_10034/pid_4840/cgroup.procs: No such file or directory
,D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  914): MasterInitialState.processMessage what=3
D/SmartBondingService(  914): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  914): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  914): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  914): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  914): CLocinfo wifi true 
D/SmartBondingService(  914): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  914): getSBEnabled() enabled =false
D/SmartBondingService(  914): getSBEnabled() enabled =false
D/SmartBondingService(  914): getSBEnabled() enabled =false
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  914): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2113): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2225): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3748): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3748): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
W/ContextImpl( 2225): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 7677): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  914): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  914): mCursor = null
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,V/GLSActivity( 2256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2256): Vacuum at: now=1452267207159 tag=VacuumService
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7894): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7894): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7894): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7894): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,I/WebViewFactory( 7894): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7894): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7894): Loading: webviewchromium
,I/LibraryLoader( 7894): Time to load native libraries: 4 ms (timestamps 3310-3314)
,I/LibraryLoader( 7894): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7894): Binding Chromium to main looper Looper (main, tid 1) {7d4058f}
,I/LibraryLoader( 7894): Expected native library version number "",actual native library version number ""
,I/chromium( 7894): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7894): Initializing chromium process, renderers=0
,W/art     ( 7894): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7894): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
W/AudioManagerAndroid( 7894): Requires BLUETOOTH permission
,I/chromium( 7894): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7894): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,I/Adreno-EGL( 7894): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7894): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7894): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7894): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7894): Remote Branch: 
I/Adreno-EGL( 7894): Local Patches: 
I/Adreno-EGL( 7894): Reconstruct Branch: 
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,I/NSApplication( 7894): Starting up...
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  914): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7953): MountEmulatedStorage()
,E/Zygote  ( 7953): v2
I/libpersona( 7953): KNOX_SDCARD checking this for 10137
I/libpersona( 7953): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7953 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  914): Killing 5943:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,I/SELinux ( 7953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7953): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7953): TimaSignature is unavailable
,D/ActivityThread( 7953): Added TimaKeyStore provider
,D/ResourcesManager( 7953): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7953): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7953): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7953): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup(  914): failed to open /acct/uid_10041/pid_5943/cgroup.procs: No such file or directory
,D/QuickConnect( 7953): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7953): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7953): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/Zygote  ( 7968): MountEmulatedStorage()
E/Zygote  ( 7968): v2
I/libpersona( 7968): KNOX_SDCARD checking this for 10162
I/libpersona( 7968): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7968 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  914): Killing 5916:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,I/SELinux ( 7968): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7968): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7968): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7968): TimaSignature is unavailable
,D/ActivityThread( 7968): Added TimaKeyStore provider
,D/ResourcesManager( 7968): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7968): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7968): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7968): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7968): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  914): failed to open /acct/uid_10047/pid_5916/cgroup.procs: No such file or directory
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/RCPManagerService(  914): exchangeData() failure , invalid userId
,D/RCPManagerService(  914): exchangeData() failure , invalid userId
,D/RCPManagerService(  914): exchangeData() failure , invalid userId
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  914): exchangeData() failure , invalid userId
,E/Zygote  ( 7990): MountEmulatedStorage()
E/Zygote  ( 7990): v2
I/libpersona( 7990): KNOX_SDCARD checking this for 10077
I/libpersona( 7990): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7990 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,I/art     (  321): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 626us total 11.803ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.182ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.478ms
,I/SELinux ( 7990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7990): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  914): exchangeData() failure , invalid userId
,D/RCPManagerService(  914): exchangeData() failure , invalid userId
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/TimaKeyStoreProvider( 7990): TimaSignature is unavailable
D/ActivityThread( 7990): Added TimaKeyStore provider
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7624): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7624): KnoxConfiguration : Current State Mapping Found 
I/ActivityManager(  914): Killing 5598:com.android.mms/u0a49 (adj 15): bgCount ##41
D/SecurityLogAgent( 7624): StateMachine : Current State = 1
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7624): StateMachine : Changed Current State = 1
,D/ResourcesManager( 7990): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,I/ActivityManager(  914): Killing 7217:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,D/CountryDetector(  914): No listener is left
,D/BadgeProvider( 7990): onCreate
,D/BadgeProvider( 7990): DatabaseHelper
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,D/BadgeProvider( 7990): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,E/Zygote  ( 8008): MountEmulatedStorage()
I/libpersona( 8008): KNOX_SDCARD checking this for 10177
E/Zygote  ( 8008): v2
I/libpersona( 8008): KNOX_SDCARD not a persona
V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,I/ActivityManager(  914): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8008 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7968): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/SELinux ( 8008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8008): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 7990): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7990): sendNotify, [notify] : null
D/BadgeProvider( 7990): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7990): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7990): update, [UpdateCount] : 1
,D/Launcher.Model( 1473): reloadBadges entered.
,D/TimaKeyStoreProvider( 8008): TimaSignature is unavailable
,D/ActivityThread( 8008): Added TimaKeyStore provider
,D/ResourcesManager( 8008): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,W/libprocessgroup(  914): failed to open /acct/uid_10049/pid_5598/cgroup.procs: No such file or directory
,W/libprocessgroup(  914): failed to open /acct/uid_10050/pid_7217/cgroup.procs: No such file or directory
,I/ActivityManager(  914): Killing 7237:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7607): notifyNetworkActivated
,W/ContextImpl( 7607): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  914): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
W/ActivityManager(  914): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/libprocessgroup(  914): failed to open /acct/uid_10057/pid_7237/cgroup.procs: No such file or directory
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore in!
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : out!
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,D/hcjo    ( 7607): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7607): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7607): exit::IDLE
D/InitializeManagerStateMachine( 7607): entry::NETWORK_CHECK
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7607): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7607): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7607): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7607): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7607): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7607): entry::SUCCESS
D/hcjo    ( 7607): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1313): Starting #8
,I/Hs20UtilService( 1313): Message received 5007
,D/hcjo    ( 7607): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7607): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7607): exit::SUCCESS
,D/InitializeManagerStateMachine( 7607): entry::IDLE
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1313): Starting #9
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1313): Starting #10
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1313): Starting #11
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1313): Message received 5007
I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  914): callSECApi what=220
D/WifiStateMachine(  914): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7156): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7156): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7156): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7156): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  259): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,I/DIAGMON_AGENT( 7726): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7726): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  914): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=914
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
D/PowerManagerService(  914): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/lights  (  914): lcd : 8 +
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/lights  (  914): lcd : 8 -
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/FOTA_Client( 7748): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7748): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7748): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/KLMS-2.4.503: ( 7766): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7766): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452267208374
,I/KLMS-2.4.503: ( 7766): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7766): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7766): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7766): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7766): StateImplV2(): networkChangeListener().END
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/SO_AGENT( 7797): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5198): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/SA      ( 7196): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7196): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7196): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7196): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7196): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7196): [SCU] == networkStateCheck == true
,I/SA      ( 7196): [DM] getCountryCodeFromCSC : PL
I/SA      ( 7196): isChinaCountryCode : false
I/SA      ( 7196): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7196): [OR] == networkStateCheck true ==
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/SA      ( 7196): [OR] GetMyCountryZoneTask
,I/SA      ( 7196): [OR] onReceive END
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7196): [SRS] prepareGetMyCountryZone
,I/SA      ( 7196): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SA      ( 7196): [SSP] query invoked
,D/accuweather( 7826): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7826): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7860): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7860): premStatus:2
,I/KnoxUsageLogPro( 7860): isEulaShown : false
I/KnoxUsageLogPro( 7860): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      ( 7196): [TPMU] GetMccFromDB : null
,I/SA      ( 7196): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7196): [TPM] isNoProxy(default) : true
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,E/File    ( 7196): fail readDirectory() errno=2
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/Headlines( 5395): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5395): getCountryCode(): countryCode = PL
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Headlines( 5395): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5395): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5395): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5395): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5395): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5395): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5395): requestUpdateNewsWelcomeCard !!! no welcome card
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/QuickConnect( 7953): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7953): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7953): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  914): exchangeData() failure , invalid userId
,D/RCPManagerService(  914): exchangeData() failure , invalid userId
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7624): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7624): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7624): StateMachine : Current State = 1
D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/SecurityLogAgent( 7624): StateMachine : Changed Current State = 1
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7607): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7607): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7607): exit::IDLE
D/InitializeManagerStateMachine( 7607): entry::NETWORK_CHECK
D/ConnectivityService(  914): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7607): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7607): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7607): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7607): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7607): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7607): entry::SUCCESS
D/hcjo    ( 7607): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 7607): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7607): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7607): exit::SUCCESS
D/InitializeManagerStateMachine( 7607): entry::IDLE
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/SA      ( 7196): [RC New] Execute method=[GET] start
,D/CustomFrequencyManagerService(  914): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 914  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  914): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  914): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 914  pkgName : ACTIVITY_RESUME_BOOSTER@10
,I/SA      ( 7196): [RC New] Security=[true]
,I/System.out( 7196): Thread-1110(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7196): Thread-1110(ApacheHTTPLog):isShipBuild true
,I/System.out( 7196): Thread-1110(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  914): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 914  tag : ACTIVITY_RESUME_BOOSTER@10
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/WifiStateMachine(  914): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  914): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,E/WifiStateMachine(  914): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  914): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  914): identical MTU - not setting
D/ConnectivityService(  914): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  914): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
,V/        (  286): QcRouteController
,D/SmartBondingService(  914): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  914): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  914): getSBEnabled() enabled =false
D/SmartBondingService(  914): getSBEnabled() enabled =false
D/SmartBondingService(  914): getSBEnabled() enabled =false
,V/        (  286): QcRouteController
,W/NetworkManagementService(  914): route cmd failed: 
W/NetworkManagementService(  914): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  914): '
W/NetworkManagementService(  914): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  914): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  914): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  914): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  914): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  914): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  914): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  914): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  914): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  914): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  914): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  914): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  914): calling update connectivity
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  914): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  914): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  914): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524295
D/ConnectivityService(  914): calling update connectivity
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 2473): CM callback handler got msg 524295
D/ConnectivityService(  914): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  914):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524295
,D/ConnectivityService(  914): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/PowerManagerService(  914): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  914): [PWL] On : 85523 (30001 ms ago)
,I/PowerManagerService(  914): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService(  914): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=914, ws=WorkSource{10058}) (elapsedTime=1223)
,D/ConnectivityManager.CallbackHandler( 2473): CM callback handler got msg 524295
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  914): REQUEST_POWER_SAVE_ON
,E/SMD     (  295): DCD ON
,I/dhcpcd  ( 7725): wlan0: sending IPv6 Router Solicitation
,I/SA      ( 7196): [RC New] [v2liruge] api execute + 651
I/SA      ( 7196): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7196): AsyncTask #1 calls detatch()
,I/SA      ( 7196): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7196): [OCP] update openData : PL
,I/SA      ( 7196): [TPMU] getNetworkMcc : 
,I/SA      ( 7196): [SCU] saveMccToPreferece Start
I/SA      ( 7196): [SCU] RegionMCC : 260
I/SA      ( 7196): [SSP] query invoked
,I/SA      ( 7196): [TPMU] GetMccFromDB : null
I/SA      ( 7196): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 7196): [SCU] saveMccToPreferece End
I/SA      ( 7196): [RC New] executeRequest [v2liruge] end. 701
I/SA      ( 7196): [RC New] Execute end
I/SA      ( 7196): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 7196): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine(  914): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/PackageManager(  914): [MSG] MCS_UNBIND
,I/ActivityManager(  914): Killing 6092:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  914): failed to open /acct/uid_1000/pid_6092/cgroup.procs: No such file or directory
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  914): SIOP:: AP = 400, PST = 346, CUR = 450
,D/WearableService( 2256): callingUid 10011, callindPid: 2256
,D/ResourcesManager( 7677): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7677): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7677): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7677): Using the GMSCore's GoogleHttpClient
,D/WearableClient( 7677): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7677): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7677): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7677): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7677): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7677): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7677): Conditions not met for autocaching.
I/MusicLeanback( 7677): Stop autocaching.
,E/ActivityThread( 7677): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@151594f that was originally bound here
E/ActivityThread( 7677): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@151594f that was originally bound here
E/ActivityThread( 7677): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7677): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7677): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7677): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7677): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7677): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7677): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7677): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7677): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7677): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7677): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7677): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7677): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7677): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7677): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7677): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7677): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7677): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7677): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7677): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7677): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7677): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7677): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7677): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7677): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,V/AlarmManager(  914): waitForAlarm result :8
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/LightSensor(  914): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7290): Test app app.js loaded
I/jxcore-log( 7290): 
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/Choreographer( 7290): Skipped 436 frames!  The application may be doing too much work on its main thread.
,D/InputMethodManagerService(  914): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  914): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@383574bb attribute=null, token = android.os.BinderProxy@15943d67
,D/ActivityManager(  914): post active user change for 0
D/KnoxTimeoutHandler(  914): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  914): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/chromium( 7290): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Timeline( 7290): Timeline: Activity_idle id: android.os.BinderProxy@347f5f92 time:117092
,I/chromium( 7290): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  914): CMD_RSSI_POLL : out!
,E/LightSensor(  914): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/PowerManagerService(  914): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 914) eventTime = 117779
,D/PowerManagerService(  914): [s] UserActivityState : 4 -> 1
,D/PowerManagerService(  914): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=914 (0x0)
D/PowerManagerService(  914): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=914, ws=WorkSource{10058}) (elapsedTime=3481)
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,I/GAV4    ( 7894): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/SurfaceFlinger(  259): id=16 Removed Toast (8/8)
,I/SurfaceFlinger(  259): id=16 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/SMD     (  295): DCD ON
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7156): mConnectivityHandler : connected
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7156): [hasSamungAccount] - No Samsung Account
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7156): [GetString-S]
,I/ReactiveServiceManager( 7156): Supported : 1
D/QSEECOMAPI: (  914): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: (  914): App is not loaded in QSEE
,D/QSEECOMAPI: (  914): Loaded image: APP id = 3
,D/QSEECOMAPI: (  914): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  914): QSEECom_shutdown_app, app_id = 3
E/terrier (  914): handleString: Failed to handle string(-4)
E/terrier (  914): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 7156): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7156): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7156): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7156): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7156): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7156): [ensureRegistration] - No Samsung account
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7725): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : out!
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/SMD     (  295): DCD ON
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  914): CMD_RSSI_POLL : out!
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7725): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7725): wlan0: no IPv6 Routers available
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7607): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7607): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7607): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7607): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7607): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 7607): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7607): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7607): entry::IDLE
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,V/AlarmManager(  914): waitForAlarm result :4
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560,
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7607): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7607): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7607): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7607): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 7607): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7607): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7607): entry::IDLE
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  914): Plugged
I/MotionRecognitionService(  914): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/Finsky  ( 6581): [1076] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6581): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : out!
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  914): SIOP:: AP = 330, PST = 338, CUR = 450
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : out!
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/art     (  914): Explicit concurrent mark sweep GC freed 53024(3MB) AllocSpace objects, 10(1440KB) LOS objects, 31% free, 35MB/51MB, paused 1.688ms total 134.143ms
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/SMD     (  295): DCD ON
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : out!
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/SMD     (  295): DCD ON
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/Watchdog(  914): !@Sync 4
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  914): Plugged
I/MotionRecognitionService(  914): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  914): CMD_RSSI_POLL : out!
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  914): SIOP:: AP = 300, PST = 330, CUR = 450
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/SMD     (  295): DCD ON
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  914): CMD_RSSI_POLL : out!
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560,
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8,
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth,
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1184): applyOpen,
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560,
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  914): CMD_RSSI_POLL : out!
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/PowerManagerService(  914): [s] UserActivityState : 1 -> 2,
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
D/PowerManagerService(  914): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  914): lcd : 5 +
,D/lights  (  914): lcd : 5 -
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
D/lights  (  914): lcd : 1 +
,D/lights  (  914): lcd : 1 -
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness(),
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1,
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/SMD     (  295): DCD ON
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : out!
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
I/MotionRecognitionService(  914): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/SMD     (  295): DCD ON
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,V/AlarmManager(  914): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1184): handleTimeUpdate
,D/KeyguardEffectViewController( 1184): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1184): *** don't update sliding image ***
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,D/SSRM:m  (  914): SIOP:: AP = 290, PST = 323, CUR = 450
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  914): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  914): CMD_RSSI_POLL : out!
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
,D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/PowerManagerService(  914): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  914): Nap time (uid 1000)...
I/PowerManagerService(  914): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  914): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  914): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  914): SecHardwareInterface.setBatteryADC : false
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false),
D/PowerManagerService(  914): handleSandman : startDream()
,D/StatusBar.NetworkController( 1184): applyOpen
,E/PowerManagerService(  914): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  914): Sleeping (uid 1000)...
D/PowerManagerService(  914): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  914): [input device light] setInputDeviceLightOn is called : 0
I/SurfaceFlinger(  259): id=17 createSurf (1080x1920),2 flag=404, ColorFade
D/PowerManagerService(  914): [input device light] handleInputDeviceLightOff
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
D/InputManager-JNI(  914): setDeviceInteractive: 0
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
D/InputManager-JNI(  914): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  914): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  914): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  914): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  914): 	.unregisterCallback : 1, client=
D/SContextService(  914): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3198111a, Service = Auto Rotation, used = 1
,W/CAE     (  914): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  914): stop(ContextProvider.java:149)
,V/CAE     (  914): clear(AutoRotationRunner.java:182)
,V/CAE     (  914): disable(AutoRotationRunner.java:171)
,I/CAE     (  914): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  914): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  306): sendContextData: -78, 7, 0, 0
,D/CAE     (  914): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  914): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  914): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
I/CAE     (  914): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  914): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  914): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  914): removeSContextService() : service = Auto Rotation
D/SContextService(  914): ===== SContext Service List =====
D/SContextManager(  914):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@a7b7f00, service=Auto Rotation
D/KeyguardViewMediator( 1184): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1184): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1184): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1184): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/KeyguardViewMediator( 1184): timeout : 5000
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/DisplayPowerController(  914): ColorFade: onAnimationStart
,D/DisplayPowerController(  914): getFinalBrightness : 8 -> 0
,I/SQLiteSecureOpenHelper( 3520): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3520): getDatabaseLocked(b,b,pwd)...
,D/lights  (  914): lcd : 0 +
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 0
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 0
D/lights  (  914): lcd : 0 -
,D/KeyguardViewMediator( 1184): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1184): handleNotifyScreenOff
,D/LightsService(  914): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 914) 
,D/LightsService(  914): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  914): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  914): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  914): unregisterListener ::   
D/lights  (  914): led_pattern : 5 +
,D/BatteryService(  914): turn on LED for fully charged
,D/lights  (  914): led_pattern : 5 -
,D/LightsService(  914): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  914): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  914): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  914): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  914): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  306): sendContextData: -76, 13, -46, 0
,I/CAE     (  914): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 15, 34, 2,
,D/SensorHubManager(  914): SendSensorHubData: send data = -63, 14, 15, 34, 2
D/Sensorhubs(  306): sendContextData: -63, 14, 15, 34, 2
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  914):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  914): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  914): handleScreenStateChanged Exit: false
,D/NotificationService(  914): ACTION_SCREEN_OFF
,E/WifiStateMachine(  914): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  914): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  914): do suspend true
,D/LightsService(  914): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 914) 
D/LightsService(  914): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService(  914): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  914): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  914): unregisterListener ::   
D/LightsService(  914): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  300): adev_set_parameters: enter: screen_state=off
,V/voice   (  300): voice_set_parameters: enter: screen_state=off
,V/voice   (  300): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  300): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  300): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  300): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  300): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  914): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  914): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  914): Bridge Server is not available
,D/VolumePanel( 1184): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1184): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1184): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1184): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  914): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  914): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1449): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1184):      ACTION_SCREEN_OFF is finished!!!! 
,E/LightSensor(  914): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  914): mCallbacks.updateBrightness()
D/DisplayPowerController(  914): getFinalBrightness : 8 -> 0
,E/StatusBar( 1184): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1184): dismissHelpPopup 
,D/accuweather( 2113): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2113): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2113): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/DisplayPowerState(  914): !@ ColorFade entry
,D/DisplayPowerController(  914): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  914): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
D/AutomaticBrightnessController(  914): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  914): Light old sensor_state 513, new sensor_state : 1 en : 0
I/AutomaticBrightnessController(  914): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  914): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  914): unregisterListener ::   
E/Sensors (  914): Acc old sensor_state 1, new sensor_state : 0 en : 0
,D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SensorManager(  914): unregisterListener ::   
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/DisplayPowerController(  914): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  914): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6a62000
V/ActivityManager(  914): Display changed displayId=0
D/qdhwcomposer(  259): hwc_blank: Blanking display: 0
,W/ActivityManager(  914): getTasks: caller 10085 does not hold GET_TASKS; limiting output
D/DisplayPowerController(  914): getFinalBrightness : 0 -> 0
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,W/ActivityManager(  914): getTasks: caller 10085 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  914): [PWL] sb release: PowerManagerService.Broadcasts
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/SSRM:m  (  914): SIOP:: AP = 290, PST = 316, CUR = 450
,D/StatusBar.NetworkController( 1184): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/rmt_storage(  281): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
,I/rmt_storage(  281): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  281): wakelock acquired: 1, error no: 42
I/rmt_storage(  281): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229454592)
,I/rmt_storage(  281): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  281): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  281): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229454592) wakelock released: 1, error no: 22
I/rmt_storage(  281): 
,I/rmt_storage(  281): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  259): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  914): Excessive delay in setPowerMode(): 253ms
D/PowerManagerService(  914): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  914): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  914): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  914): Got set_interactive hint
,I/PowerManagerService(  914): [PWL] Off : 0s ago
I/PowerManagerService(  914): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  914): [PWL]     mDisplayReady : false
D/DisplayPowerController(  914): getFinalBrightness : 0 -> 0
D/PowerManagerService(  914): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  914): [PWL] sb release: PowerManagerService.Display
,E/SMD     (  295): DCD ON
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,V/AlarmManager(  914): waitForAlarm result :4
,D/KeyguardViewMediator( 1184): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1184): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/KeyguardViewMediator( 1184): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  914): [PWL] Off : 5s ago
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  914): SIOP:: AP = 290, PST = 313, CUR = 450,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,I/PowerManagerService(  914): [PWL] Off : 15s ago
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 5
,E/SMD     (  295): DCD ON
,V/AlarmManager(  914): waitForAlarm result :4
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhenotypeConfigurator( 2256): Scheduling Phenotype for one-off execution 2193 seconds from now (1452267261470)
,D/GetConfigurationSnapshotOperation( 2256): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2256): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2256): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  914): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 2256): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 2256): (HTTPLog)-Static: isShipBuild true
,I/System.out( 2256): (HTTPLog)-Thread-309-606562842: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/SSRM:m  (  914): SIOP:: AP = 270, PST = 310, CUR = 450
,I/qtaguid ( 2256): Tagging socket 71 with tag 1000040100000000{268436481,0} uid 10011, pid: 2256, getuid(): 10011
,I/qtaguid ( 2256): Tagging socket 77 with tag 1000040100000000{268436481,0} uid 10011, pid: 2256, getuid(): 10011
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2256): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 2256, getuid(): 10011
,I/qtaguid ( 2256): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 2256, getuid(): 10011
,D/LocationManagerService(  914): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2256): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 2256, getuid(): 10011
,D/LocationManagerService(  914): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2256): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 2256, getuid(): 10011
,D/LocationManagerService(  914): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2256): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 2256, getuid(): 10011
,E/SMD     (  295): DCD ON
,D/LocationManagerService(  914): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2256): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 2256, getuid(): 10011
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,V/AlarmManager(  914): waitForAlarm result :4
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 306, CUR = 450
,I/PowerManagerService(  914): [PWL] Off : 30s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 301, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 6
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  914): [PWL] Off : 50s ago
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 295, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/ClearcutLoggerApiImpl( 2256): disconnect managed GoogleApiClient
,E/SMD     (  295): DCD ON
,V/AlarmManager(  914): waitForAlarm result :8
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 281, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 274, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/PowerManagerService(  914): [PWL] Off : 75s ago
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 7
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,V/AlarmManager(  914): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1184): handleTimeUpdate
,D/KeyguardEffectViewController( 1184): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1184): *** don't update sliding image ***
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  914): stay LED for fully charged
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 270, CUR = 450
,E/SMD     (  295): DCD ON,
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 267, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 264, CUR = 450
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,I/PowerManagerService(  914): [PWL] Off : 105s ago
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 8
,I/jxcore-log( 7290): TAP version 13
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # multiplex can send data
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,D/BatteryService(  914): stay LED for fully charged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 261, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): ok 1 String should be length:200
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # basic
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,V/AlarmManager(  914): waitForAlarm result :8
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 7290): ok 2 sane
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): # another
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,E/SMD     (  295): DCD ON
,I/MotionRecognitionService(  914): Plugged
,D/BatteryService(  914): stay LED for fully charged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7290): ok 3 sane
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 9
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): ok 4 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 5 null
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 6 (unnamed assert)
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 7 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 8 should not throw
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,I/PowerManagerService(  914): [PWL] Off : 140s ago
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7290): ok 9 (unnamed assert)
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 10 (unnamed assert)
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 11 should not throw
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 12 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 13 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 7290): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 7290): 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 7290): ok 14 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): # failed to get mobile documents path
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7290): ok 15 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 7290): 
,D/TimaService(  914): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  914): TimaServiceHandler.handleMessage what =1
,D/TimaService(  914): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  914): initializing...
,I/TLC_TIMA_PKM_initialize(  914): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  914): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  914): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  914): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  914): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  914): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  914): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  914): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  914): App is not loaded in QSEE
,D/QSEECOMAPI: (  914): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  914): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  914): Trustlet response is completed
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  914): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  914): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  914): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  914): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): ok 16 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 17 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 18 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # #init should register the networkChanged event
I/jxcore-log( 7290): 
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 19 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  914): [PWL] Off : 180s ago
,I/jxcore-log( 7290): # #startBroadcasting should throw on null device name
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,V/AlarmManager(  914): waitForAlarm result :4
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8238): MountEmulatedStorage()
,E/Zygote  ( 8238): v2
,I/libpersona( 8238): KNOX_SDCARD checking this for 10080
I/libpersona( 8238): KNOX_SDCARD not a persona
,I/ActivityManager(  914): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8238 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1184): handleTimeUpdate
,I/SELinux ( 8238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/KeyguardEffectViewController( 1184): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1184): *** don't update sliding image ***
,I/SELinux ( 8238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8238): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 8238): TimaSignature is unavailable
,D/ActivityThread( 8238): Added TimaKeyStore provider
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  914): Killing 7259:com.google.android.apps.docs/u0a97 (adj 15): bgCount ##41
,W/libprocessgroup(  914): failed to open /acct/uid_10097/pid_7259/cgroup.procs: No such file or directory
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 7290): ok 20 should throw
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 11
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 7290): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 7290): 
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): ok 21 should throw
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # #startBroadcasting should throw on non-number port
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 7290): ok 22 should throw
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # #startBroadcasting should throw on NaN port
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 7290): ok 23 should throw
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # #startBroadcasting should throw on negative port
I/jxcore-log( 7290): 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,I/jxcore-log( 7290): ok 24 should throw
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): # #startBroadcasting should throw on too large port
I/jxcore-log( 7290): 
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  914): stay LED for fully charged
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  914): [PWL] Off : 225s ago
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 12
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): ok 25 should throw
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,I/jxcore-log( 7290): ok 26 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 27 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 28 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 7290): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,V/AlarmManager(  914): waitForAlarm result :8
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 7290): ok 29 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 30 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 31 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,I/jxcore-log( 7290): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 7290): 
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 13
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 7290): ok 32 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 33 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 7290): 
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): ok 34 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 35 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 7290): 
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  914): [PWL] Off : 275s ago
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 36 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 37 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 38 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,I/jxcore-log( 7290): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 14
,E/SMD     (  295): DCD ON
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): ok 39 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 40 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # should call Mobile("Disconnect") without an error
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 41 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 42 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 7290): 
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 43 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): ok 44 should be equal
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 7290): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 7290): 
,I/jxcore-log( 7290): # teardown
I/jxcore-log( 7290): 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 15
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559156.7290
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559156.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7290): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7290): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[152]}
,D/BluetoothSocket( 7290): bindListen(), new LocalSocket 
,D/BluetoothSocket( 7290): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 7290): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e0fcfce
,D/BluetoothSocket( 7290): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: OK
,I/io.jxcore.node.ConnectionHelper( 7290): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559156.7290
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559156.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559156.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559156.7290","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  914): InactiveState{ what=139292 }
,D/WifiP2pService(  914): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  914): P2pEnabledState add service
,D/WifiP2pService(  914): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): start: Starting P2P device discovery...
,D/WifiP2pService(  914): InactiveState{ what=139265 }
,D/WifiP2pService(  914): P2pEnabledState{ what=139265 }
,D/WifiService(  914): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  914): callSECApi what=74
,D/WifiStateMachine(  914): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  914): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1305): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7290): start: OK
,D/WifiP2pService(  914): discovery change broadcast true
,I/jxcore-log( 7290): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 7290): 
,I/io.jxcore.node.ConnectionHelper( 7290): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): shutdown
D/BluetoothSocket( 7290): close() in, this: android.bluetooth.BluetoothSocket@c635c85, channel: 6, state: LISTENING
D/BluetoothSocket( 7290): close() this: android.bluetooth.BluetoothSocket@c635c85, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e0fcfce, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@205d1adamSocket: android.net.LocalSocket@46f0b0b impl:android.net.LocalSocketImpl@e273de8 fd:FileDescriptor[152]
,D/BluetoothSocket( 7290): Closing mSocket: android.net.LocalSocket@46f0b0b impl:android.net.LocalSocketImpl@e273de8 fd:FileDescriptor[152]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): stop: Stopping services
,D/WifiP2pService(  914): InactiveState{ what=139298 }
,D/WifiP2pService(  914): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): stop: Stopping P2P device discovery...
,D/WifiP2pService(  914): P2pEnabledState clear service
,D/WifiP2pService(  914): remove client information from framework
,D/WifiP2pService(  914): InactiveState{ what=139268 }
,I/wpa_supplicant( 1305): P2P-FIND-STOPPED 
,D/WifiP2pService(  914): InactiveState{ what=147493 }
,D/WifiP2pService(  914): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  914): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: false
,D/WifiP2pService(  914): InactiveState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
D/WifiP2pService(  914): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: NOT_STARTED
,D/WifiP2pService(  914): P2pEnabledState clear service request
,I/jxcore-log( 7290): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 7290): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559368.7290
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559368.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7290): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7290): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[152]}
,D/BluetoothSocket( 7290): bindListen(), new LocalSocket 
D/BluetoothSocket( 7290): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7290): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a020aa6
D/BluetoothSocket( 7290): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: OK
I/io.jxcore.node.ConnectionHelper( 7290): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559368.7290
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559368.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559368.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559368.7290","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  914): InactiveState{ what=139292 }
,D/WifiP2pService(  914): P2pEnabledState{ what=139292 }
D/WifiP2pService(  914): P2pEnabledState add service
,D/WifiP2pService(  914): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): start: Starting P2P device discovery...
,D/WifiP2pService(  914): InactiveState{ what=139265 }
,D/WifiP2pService(  914): P2pEnabledState{ what=139265 }
D/WifiService(  914): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  914): callSECApi what=74
D/WifiStateMachine(  914): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  914): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1305): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1305): p2p0: P2P: Reject scan trigger since one is already pending
,D/WifiP2pService(  914): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7290): start: OK
,I/jxcore-log( 7290): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 7290): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Waiting for incoming connections...
,I/io.jxcore.node.ConnectionHelper( 7290): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): shutdown
,D/BluetoothSocket( 7290): close() in, this: android.bluetooth.BluetoothSocket@1d55973d, channel: 6, state: LISTENING
D/BluetoothSocket( 7290): close() this: android.bluetooth.BluetoothSocket@1d55973d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a020aa6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7b42b32mSocket: android.net.LocalSocket@78bd083 impl:android.net.LocalSocketImpl@1861e200 fd:FileDescriptor[152]
D/BluetoothSocket( 7290): Closing mSocket: android.net.LocalSocket@78bd083 impl:android.net.LocalSocketImpl@1861e200 fd:FileDescriptor[152]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): stop: Stopping services
,D/WifiP2pService(  914): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: NOT_INITIALIZED
D/WifiP2pService(  914): P2pEnabledState{ what=139298 }
,D/WifiP2pService(  914): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: The given listener does not exist in the list
,D/WifiP2pService(  914): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
I/wpa_supplicant( 1305): P2P-FIND-STOPPED 
D/WifiP2pService(  914): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: NOT_STARTED
,D/WifiP2pService(  914): InactiveState{ what=139307 }
D/WifiP2pService(  914): P2pEnabledState{ what=139307 }
D/WifiP2pService(  914): P2pEnabledState clear service request
,D/WifiP2pService(  914): InactiveState{ what=147493 }
D/WifiP2pService(  914): P2pEnabledState{ what=147493 }
D/WifiP2pService(  914): discovery change broadcast false
,I/jxcore-log( 7290): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 7290): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559427.7290
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559427.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7290): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7290): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[152]}
,D/BluetoothSocket( 7290): bindListen(), new LocalSocket 
,D/BluetoothSocket( 7290): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7290): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39f5c87e
,D/BluetoothSocket( 7290): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: OK
I/io.jxcore.node.ConnectionHelper( 7290): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559427.7290
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559427.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559427.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559427.7290","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  914): InactiveState{ what=139292 }
D/WifiP2pService(  914): P2pEnabledState{ what=139292 }
D/WifiP2pService(  914): P2pEnabledState add service
D/WifiP2pService(  914): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService(  914): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7290): start: OK
,D/WifiP2pService(  914): P2pEnabledState{ what=139265 }
D/WifiService(  914): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  914): callSECApi what=74
D/WifiStateMachine(  914): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  914): callSECApiBoolean - ID [13]
I/jxcore-log( 7290): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 7290): 
,I/wpa_supplicant( 1305): USE_NETWORK : USE_NETWORK OFF
I/io.jxcore.node.ConnectionHelper( 7290): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): shutdown
D/BluetoothSocket( 7290): close() in, this: android.bluetooth.BluetoothSocket@68d70f5, channel: 6, state: LISTENING
,D/BluetoothSocket( 7290): close() this: android.bluetooth.BluetoothSocket@68d70f5, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39f5c87e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3521ee8amSocket: android.net.LocalSocket@3edcccfb impl:android.net.LocalSocketImpl@f99f118 fd:FileDescriptor[152]
I/wpa_supplicant( 1305): p2p0: P2P: Reject scan trigger since one is already pending
,D/BluetoothSocket( 7290): Closing mSocket: android.net.LocalSocket@3edcccfb impl:android.net.LocalSocketImpl@f99f118 fd:FileDescriptor[152]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
,D/WifiP2pService(  914): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): release: No more listeners, de-initializing...
D/WifiP2pService(  914): InactiveState{ what=139298 }
D/WifiP2pService(  914): P2pEnabledState{ what=139298 }
D/WifiP2pService(  914): P2pEnabledState clear service
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: NOT_STARTED
,D/WifiP2pService(  914): remove client information from framework
,I/jxcore-log( 7290): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 7290): 
,D/WifiP2pService(  914): InactiveState{ what=139268 }
,I/wpa_supplicant( 1305): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559482.7290
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,D/WifiP2pService(  914): InactiveState{ what=139307 }
,D/WifiP2pService(  914): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  914): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559482.7290","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): startListeningForIncomingConnections: Starting...
,D/WifiP2pService(  914): InactiveState{ what=147493 }
,W/BluetoothAdapter( 7290): getBluetoothService() called with no BluetoothManagerCallback
,D/WifiP2pService(  914): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  914): discovery change broadcast false
,D/BluetoothSocket( 7290): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[152]}
,D/BluetoothSocket( 7290): bindListen(), new LocalSocket 
D/BluetoothSocket( 7290): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 7290): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16386956
D/BluetoothSocket( 7290): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: OK
I/io.jxcore.node.ConnectionHelper( 7290): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559482.7290
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559482.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559482.7290","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559482.7290","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  914): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: INITIALIZED
D/WifiP2pService(  914): P2pEnabledState{ what=139292 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7290): start: OK
,I/jxcore-log( 7290): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 7290): 
,D/WifiP2pService(  914): P2pEnabledState add service
I/io.jxcore.node.ConnectionHelper( 7290): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): shutdown
D/BluetoothSocket( 7290): close() in, this: android.bluetooth.BluetoothSocket@393fc9ad, channel: 6, state: LISTENING
D/BluetoothSocket( 7290): close() this: android.bluetooth.BluetoothSocket@393fc9ad, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16386956, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3869c4e2mSocket: android.net.LocalSocket@27d1e073 impl:android.net.LocalSocketImpl@32b1cb30 fd:FileDescriptor[152]
D/BluetoothSocket( 7290): Closing mSocket: android.net.LocalSocket@27d1e073 impl:android.net.LocalSocketImpl@32b1cb30 fd:FileDescriptor[152]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: NOT_INITIALIZED
D/WifiP2pService(  914): add a new client
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: NOT_STARTED
,I/jxcore-log( 7290): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 7290): 
,D/WifiP2pService(  914): InactiveState{ what=139265 }
,D/WifiP2pService(  914): P2pEnabledState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to WIFI
,D/WifiService(  914): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  914): callSECApi what=74
D/WifiStateMachine(  914): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559526.7290
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): bind: Binding a new listener
D/WifiNative-HAL(  914): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1305): USE_NETWORK : USE_NETWORK OFF
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1305): p2p0: P2P: Reject scan trigger since one is already pending
,D/WifiP2pService(  914): discovery change broadcast true
,D/WifiP2pService(  914): InactiveState{ what=139298 }
D/WifiP2pService(  914): P2pEnabledState{ what=139298 }
D/WifiP2pService(  914): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559526.7290","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): setConnectionTimeout: 15000
D/WifiP2pService(  914): remove client information from framework
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): startListeningForIncomingConnections
D/WifiP2pService(  914): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): startListeningForIncomingConnections: Starting...
,I/wpa_supplicant( 1305): P2P-FIND-STOPPED 
,D/WifiP2pService(  914): InactiveState{ what=139307 }
,W/BluetoothAdapter( 7290): getBluetoothService() called with no BluetoothManagerCallback
D/WifiP2pService(  914): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  914): P2pEnabledState clear service request
,D/BluetoothSocket( 7290): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[152]}
D/BluetoothSocket( 7290): bindListen(), new LocalSocket 
,D/WifiP2pService(  914): InactiveState{ what=147493 }
D/BluetoothSocket( 7290): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7290): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7634d2e
D/BluetoothSocket( 7290): channel: 6
D/WifiP2pService(  914): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  914): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: OK
I/io.jxcore.node.ConnectionHelper( 7290): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559526.7290
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559526.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559526.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559526.7290","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  914): InactiveState{ what=139292 }
D/WifiP2pService(  914): P2pEnabledState{ what=139292 }
D/WifiP2pService(  914): P2pEnabledState add service
D/WifiP2pService(  914): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: RUNNING
,D/WifiP2pService(  914): InactiveState{ what=139265 }
,I/io.jxcore.node.ConnectionHelper( 7290): start: OK
,D/WifiP2pService(  914): P2pEnabledState{ what=139265 }
D/WifiService(  914): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  914): callSECApi what=74
D/WifiStateMachine(  914): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  914): callSECApiBoolean - ID [13]
,I/jxcore-log( 7290): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 7290): 
I/wpa_supplicant( 1305): USE_NETWORK : USE_NETWORK OFF
I/io.jxcore.node.ConnectionHelper( 7290): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): stop: Stopping Bluetooth...
I/wpa_supplicant( 1305): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): shutdown
D/BluetoothSocket( 7290): close() in, this: android.bluetooth.BluetoothSocket@3c5d8165, channel: 6, state: LISTENING
D/BluetoothSocket( 7290): close() this: android.bluetooth.BluetoothSocket@3c5d8165, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7634d2e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a5b0e3amSocket: android.net.LocalSocket@1f6eaeb impl:android.net.LocalSocketImpl@2e77d048 fd:FileDescriptor[152]
D/BluetoothSocket( 7290): Closing mSocket: android.net.LocalSocket@1f6eaeb impl:android.net.LocalSocketImpl@2e77d048 fd:FileDescriptor[152]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): onServerStopped
,D/WifiP2pService(  914): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: NOT_INITIALIZED
D/WifiP2pService(  914): InactiveState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService(  914): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): release: No more listeners, de-initializing...
D/WifiP2pService(  914): P2pEnabledState clear service
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
D/WifiP2pService(  914): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: NOT_STARTED
,D/WifiP2pService(  914): InactiveState{ what=139268 }
I/wpa_supplicant( 1305): P2P-FIND-STOPPED 
,D/WifiP2pService(  914): InactiveState{ what=139307 }
D/WifiP2pService(  914): P2pEnabledState{ what=139307 }
D/WifiP2pService(  914): P2pEnabledState clear service request
D/WifiP2pService(  914): InactiveState{ what=147493 }
D/WifiP2pService(  914): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  914): discovery change broadcast false
,I/jxcore-log( 7290): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 7290): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559582.7290
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559582.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7290): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7290): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[152]}
,D/BluetoothSocket( 7290): bindListen(), new LocalSocket 
D/BluetoothSocket( 7290): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 7290): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@13dbd406
D/BluetoothSocket( 7290): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: OK
I/io.jxcore.node.ConnectionHelper( 7290): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559582.7290
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559582.7290","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559582.7290","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559582.7290","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  914): InactiveState{ what=139292 }
D/WifiP2pService(  914): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  914): P2pEnabledState add service
D/WifiP2pService(  914): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: OK
D/WifiP2pService(  914): InactiveState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: RUNNING
,D/WifiP2pService(  914): P2pEnabledState{ what=139265 }
I/io.jxcore.node.ConnectionHelper( 7290): start: OK
D/WifiService(  914): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  914): callSECApi what=74
D/WifiStateMachine(  914): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  914): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1305): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1305): p2p0: P2P: Reject scan trigger since one is already pending
,D/WifiP2pService(  914): discovery change broadcast true
I/jxcore-log( 7290): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 7290): 
I/io.jxcore.node.ConnectionHelper( 7290): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): shutdown
D/BluetoothSocket( 7290): close() in, this: android.bluetooth.BluetoothSocket@2813781d, channel: 6, state: LISTENING
D/BluetoothSocket( 7290): close() this: android.bluetooth.BluetoothSocket@2813781d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@13dbd406, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2512a92mSocket: android.net.LocalSocket@3673cc63 impl:android.net.LocalSocketImpl@2f266060 fd:FileDescriptor[152]
,D/BluetoothSocket( 7290): Closing mSocket: android.net.LocalSocket@3673cc63 impl:android.net.LocalSocketImpl@2f266060 fd:FileDescriptor[152]
D/WifiP2pService(  914): InactiveState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Exiting thread
D/WifiP2pService(  914): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): onServerStopped
D/WifiP2pService(  914): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): stop: Stopping services
D/WifiP2pService(  914): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): stop: Stopping P2P device discovery...
D/WifiP2pService(  914): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: NOT_INITIALIZED
I/wpa_supplicant( 1305): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: The given listener does not exist in the list
D/WifiP2pService(  914): InactiveState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
D/WifiP2pService(  914): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: NOT_STARTED
D/WifiP2pService(  914): P2pEnabledState clear service request
,D/WifiP2pService(  914): InactiveState{ what=147493 }
D/WifiP2pService(  914): P2pEnabledState{ what=147493 }
D/WifiP2pService(  914): discovery change broadcast false
,I/jxcore-log( 7290): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 7290): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559631.7290
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559631.7290","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7290): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7290): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[152]}
D/BluetoothSocket( 7290): bindListen(), new LocalSocket 
D/BluetoothSocket( 7290): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7290): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d535dde
D/BluetoothSocket( 7290): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: OK
I/io.jxcore.node.ConnectionHelper( 7290): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559631.7290
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559631.7290","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559631.7290","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559631.7290","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  914): InactiveState{ what=139292 }
,D/WifiP2pService(  914): P2pEnabledState{ what=139292 }
D/WifiP2pService(  914): P2pEnabledState add service
,D/WifiP2pService(  914): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService(  914): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: OK
D/WifiP2pService(  914): P2pEnabledState{ what=139265 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: RUNNING
D/WifiService(  914): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/io.jxcore.node.ConnectionHelper( 7290): start: OK
,I/WifiStateMachine(  914): callSECApi what=74
D/WifiStateMachine(  914): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  914): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1305): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 1305): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiP2pService(  914): discovery change broadcast true
,I/jxcore-log( 7290): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 7290): 
I/io.jxcore.node.ConnectionHelper( 7290): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): shutdown
D/BluetoothSocket( 7290): close() in, this: android.bluetooth.BluetoothSocket@114a8dd5, channel: 6, state: LISTENING
D/BluetoothSocket( 7290): close() this: android.bluetooth.BluetoothSocket@114a8dd5, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d535dde, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1bb379eamSocket: android.net.LocalSocket@2f8c64db impl:android.net.LocalSocketImpl@21e3db78 fd:FileDescriptor[152]
,D/BluetoothSocket( 7290): Closing mSocket: android.net.LocalSocket@2f8c64db impl:android.net.LocalSocketImpl@21e3db78 fd:FileDescriptor[152]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stop: Stopping peer discovery...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): stop: Stopping P2P device discovery...
,D/WifiP2pService(  914): InactiveState{ what=139298 }
D/WifiP2pService(  914): P2pEnabledState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: NOT_INITIALIZED
,D/WifiP2pService(  914): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: NOT_STARTED
D/WifiP2pService(  914): remove client information from framework
,D/WifiP2pService(  914): InactiveState{ what=139268 }
I/jxcore-log( 7290): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 7290): 
,I/wpa_supplicant( 1305): P2P-FIND-STOPPED 
,D/WifiP2pService(  914): InactiveState{ what=139307 }
,D/WifiP2pService(  914): P2pEnabledState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to WIFI
,D/WifiP2pService(  914): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559687.7290
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): bind: Binding a new listener
,D/WifiP2pService(  914): InactiveState{ what=147493 }
,D/WifiP2pService(  914): P2pEnabledState{ what=147493 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
D/WifiP2pService(  914): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559687.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7290): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7290): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[152]}
,D/BluetoothSocket( 7290): bindListen(), new LocalSocket 
D/BluetoothSocket( 7290): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 7290): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e474ab6
D/BluetoothSocket( 7290): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: OK
I/io.jxcore.node.ConnectionHelper( 7290): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559687.7290
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559687.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559687.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559687.7290","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  914): InactiveState{ what=139292 }
,D/WifiP2pService(  914): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  914): P2pEnabledState add service
,D/WifiP2pService(  914): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7290): start: OK
,D/WifiP2pService(  914): InactiveState{ what=139265 }
,D/WifiP2pService(  914): P2pEnabledState{ what=139265 }
I/WifiStateMachine(  914): callSECApi what=74
,D/WifiService(  914): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine(  914): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  914): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1305): USE_NETWORK : USE_NETWORK OFF
I/jxcore-log( 7290): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 7290): 
I/wpa_supplicant( 1305): p2p0: P2P: Reject scan trigger since one is already pending
,I/io.jxcore.node.ConnectionHelper( 7290): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): stop: Stopping Bluetooth...
D/WifiP2pService(  914): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): shutdown
D/BluetoothSocket( 7290): close() in, this: android.bluetooth.BluetoothSocket@2527a28d, channel: 6, state: LISTENING
,D/BluetoothSocket( 7290): close() this: android.bluetooth.BluetoothSocket@2527a28d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e474ab6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b755c42mSocket: android.net.LocalSocket@20209453 impl:android.net.LocalSocketImpl@2642a190 fd:FileDescriptor[152]
,D/BluetoothSocket( 7290): Closing mSocket: android.net.LocalSocket@20209453 impl:android.net.LocalSocketImpl@2642a190 fd:FileDescriptor[152]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): stop: Stopping services
D/WifiP2pService(  914): InactiveState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): stop: Stopping P2P device discovery...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: NOT_INITIALIZED,
D/WifiP2pService(  914): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: false
,D/WifiP2pService(  914): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): release: No more listeners, de-initializing...,
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: The given listener does not exist in the list
,D/WifiP2pService(  914): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: NOT_STARTED
I/jxcore-log( 7290): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 7290): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to WIFI
,D/WifiP2pService(  914): InactiveState{ what=139268 }
I/wpa_supplicant( 1305): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559764.7290
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): bind: Binding a new listener
,D/WifiP2pService(  914): InactiveState{ what=139307 },
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,D/WifiP2pService(  914): P2pEnabledState{ what=139307 }
D/WifiP2pService(  914): P2pEnabledState clear service request,
,D/WifiP2pService(  914): InactiveState{ what=147493 }
,D/WifiP2pService(  914): P2pEnabledState{ what=147493 }
D/WifiP2pService(  914): discovery change broadcast false,
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559764.7290","ra":"7C:F9:0E:34:8A:A0"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7290): getBluetoothService() called with no BluetoothManagerCallback,
,D/BluetoothSocket( 7290): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[152]},
D/BluetoothSocket( 7290): bindListen(), new LocalSocket 
,D/BluetoothSocket( 7290): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7290): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3780fa8e
,D/BluetoothSocket( 7290): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: OK
I/io.jxcore.node.ConnectionHelper( 7290): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559764.7290
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559764.7290","ra":"7C:F9:0E:34:8A:A0"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559764.7290","ra":"7C:F9:0E:34:8A:A0"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559764.7290","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  914): InactiveState{ what=139292 },
D/WifiP2pService(  914): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  914): P2pEnabledState add service
,D/WifiP2pService(  914): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7290): start: OK
I/jxcore-log( 7290): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 7290): ,
I/io.jxcore.node.ConnectionHelper( 7290): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): Shutting down...
,D/WifiP2pService(  914): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): shutdown
,D/WifiP2pService(  914): P2pEnabledState{ what=139265 }
,D/BluetoothSocket( 7290): close() in, this: android.bluetooth.BluetoothSocket@348b9645, channel: 6, state: LISTENING
D/WifiService(  914): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/BluetoothSocket( 7290): close() this: android.bluetooth.BluetoothSocket@348b9645, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3780fa8e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2596319amSocket: android.net.LocalSocket@3b2c3acb impl:android.net.LocalSocketImpl@2fc112a8 fd:FileDescriptor[152]
D/BluetoothSocket( 7290): Closing mSocket: android.net.LocalSocket@3b2c3acb impl:android.net.LocalSocketImpl@2fc112a8 fd:FileDescriptor[152]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Exiting thread,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): onServerStopped
I/WifiStateMachine(  914): callSECApi what=74
,D/WifiStateMachine(  914): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
,D/WifiNative-HAL(  914): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1305): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1305): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stop: Stopping peer discovery...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: NOT_INITIALIZED,
D/WifiP2pService(  914): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: false,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stopWifiPeerDiscovery: Stopped
D/WifiP2pService(  914): InactiveState{ what=139298 },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): release: No more listeners, de-initializing...
D/WifiP2pService(  914): P2pEnabledState{ what=139298 },
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: The given listener does not exist in the list
D/WifiP2pService(  914): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: NOT_STARTED
,I/jxcore-log( 7290): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 7290): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to BLE
D/WifiP2pService(  914): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setDiscoveryMode: Mode set to WIFI
D/WifiP2pService(  914): InactiveState{ what=139268 }
I/wpa_supplicant( 1305): P2P-FIND-STOPPED 
,D/WifiP2pService(  914): InactiveState{ what=139307 }
,D/WifiP2pService(  914): P2pEnabledState{ what=139307 }
D/WifiP2pService(  914): P2pEnabledState clear service request
,D/WifiP2pService(  914): InactiveState{ what=147493 }
,D/WifiP2pService(  914): P2pEnabledState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559840.7290
D/WifiP2pService(  914): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559840.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7290): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7290): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[152]}
D/BluetoothSocket( 7290): bindListen(), new LocalSocket 
D/BluetoothSocket( 7290): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7290): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d95cd66
D/BluetoothSocket( 7290): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): start: OK
I/io.jxcore.node.ConnectionHelper( 7290): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: Peer ID: 7C:F9:0E:34:8A:A0, peer name: 1452267559840.7290
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7290): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559840.7290","ra":"7C:F9:0E:34:8A:A0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): start: {"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559840.7290","ra":"7C:F9:0E:34:8A:A0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): start: Identity string: "{"pi":"7C:F9:0E:34:8A:A0","pn":"1452267559840.7290","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  914): InactiveState{ what=139292 }
D/WifiP2pService(  914): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  914): P2pEnabledState add service
D/WifiP2pService(  914): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): start: Starting P2P device discovery...
,D/WifiP2pService(  914): InactiveState{ what=139265 }
,D/WifiP2pService(  914): P2pEnabledState{ what=139265 }
I/WifiStateMachine(  914): callSECApi what=74
D/WifiService(  914): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine(  914): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  914): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1305): USE_NETWORK : USE_NETWORK OFF
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiP2pService(  914): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7290): start: OK
I/wpa_supplicant( 1305): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 7290): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 7290): 
,I/io.jxcore.node.ConnectionHelper( 7290): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): shutdown
D/BluetoothSocket( 7290): close() in, this: android.bluetooth.BluetoothSocket@2f9348fd, channel: 6, state: LISTENING
D/BluetoothSocket( 7290): close() this: android.bluetooth.BluetoothSocket@2f9348fd, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d95cd66, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@12a159f2mSocket: android.net.LocalSocket@1b473843 impl:android.net.LocalSocketImpl@17498ec0 fd:FileDescriptor[152]
,D/BluetoothSocket( 7290): Closing mSocket: android.net.LocalSocket@1b473843 impl:android.net.LocalSocketImpl@17498ec0 fd:FileDescriptor[152]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7290): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7290): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7290): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7290): stop: Stopping services
D/WifiP2pService(  914): InactiveState{ what=139298 }
,D/WifiP2pService(  914): P2pEnabledState{ what=139298 }
D/WifiP2pService(  914): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7290): release: No more listeners, de-initializing...
D/WifiP2pService(  914): remove client information from framework
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7290): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7290): setState: NOT_STARTED
,I/jxcore-log( 7290): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 7290): 
,D/WifiP2pService(  914): InactiveState{ what=139268 }
,I/wpa_supplicant( 1305): P2P-FIND-STOPPED 
,I/jxcore-log( 7290): # setup
I/jxcore-log( 7290): 
,I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7290): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7290): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7290): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery stopped successfully
D/WifiP2pService(  914): InactiveState{ what=139307 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7290): Service requests cleared successfully
D/WifiP2pService(  914): P2pEnabledState{ what=139307 }
,I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: RUNNING
D/WifiP2pService(  914): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local service added successfully
,D/WifiP2pService(  914): InactiveState{ what=147493 }
I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: RUNNING
,D/WifiP2pService(  914): P2pEnabledState{ what=147493 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery started successfully
D/WifiP2pService(  914): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local services cleared successfully
,I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7290): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7290): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7290): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7290): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7290): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: RUNNING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7290): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7290): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7290): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7290): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7290): Service requests cleared successfully
,I/wpa_supplicant( 1305): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1,
,D/WifiP2pService(  914): InactiveState{ what=147477 }
,D/WifiP2pService(  914): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  914): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  914): InactiveState{ what=139283 }
,D/WifiP2pService(  914): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  914): DefaultState{ what=139283 }
,D/WifiDisplayController(  914): Received list of peers.
,D/WifiDisplayController(  914):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  914): [PWL] Off : 330s ago
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/bootchecker(  325): bootchecker wake up!!
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  914): !@Sync 16
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 17
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  914): [PWL] Off : 390s ago
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  914): !@Sync 18
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,V/AlarmManager(  914): waitForAlarm result :8
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/Atfwd_Daemon(  329): Stop the daemon....
,E/Watchdog(  914): !@Sync 19
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  914): [PWL] Off : 455s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/TimaService(  914): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  914): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  914): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 20
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/TLC_TIMA_PKM_measure_kernel(  914): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  914): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/TimaService(  914): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  914): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,I/ActivityManager(  914): Killing 7375:com.vlingo.midas/u0a32 (adj 15): bgCount ##41
,W/libprocessgroup(  914): failed to open /acct/uid_10032/pid_7375/cgroup.procs: No such file or directory
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 21
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  914): [PWL] Off : 525s ago
,E/Watchdog(  914): !@Sync 22
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 23
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 24
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  914): [PWL] Off : 600s ago
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 25
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 26
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 27
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  914): [PWL] Off : 680s ago
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 28
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 29
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,D/BatteryService(  914): stay LED for fully charged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/TimaService(  914): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  914): TimaServiceHandler.handleMessage what =1
,D/TimaService(  914): TIMA: checkEvent, operation: 50000 subject: 10000
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,I/PowerManagerService(  914): [PWL] Off : 765s ago
,I/PowerManagerService(  914): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  914): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  914): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=914, ws=null) (elapsedTime=2180)
,E/Watchdog(  914): !@Sync 30
,E/SMD     (  295): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  914): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  914): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  914): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  914): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  295): DCD ON,
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 31
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged,
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 32
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,I/PowerManagerService(  914): [PWL] Off : 855s ago
,E/Watchdog(  914): !@Sync 33
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,D/BatteryService(  914): stay LED for fully charged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 34
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 35
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 36
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  914): [PWL] Off : 950s ago
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 37
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  914): stay LED for fully charged
D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 38
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,D/BatteryService(  914): stay LED for fully charged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,D/BatteryService(  914): stay LED for fully charged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 39
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  914): [PWL] Off : 1050s ago
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  295): DCD ON
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/TimaService(  914): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  914): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  914): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  914): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  914): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  914): Updating Usage Statistics in DB @ 1452268305956
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  914): ::getAppControlDB: Exception to create DB
,W/System.err(  914): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  914): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  914): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  914): Done Updating Usage Statistics in DB @ 1452268306163
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 40
,E/SMD     (  295): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  914): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  914): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  914): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  914): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 41
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  914): !@Sync 42
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 259, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 258, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  914): [PWL] Off : 1155s ago
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 257, CUR = 450
,E/Watchdog(  914): !@Sync 43
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 256, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 255, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 254, CUR = 450
,E/Watchdog(  914): !@Sync 44
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 253, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 252, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 45
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 251, CUR = 450
,E/SMD     (  295): DCD ON
,I/art     (  914): Background sticky concurrent mark sweep GC freed 94577(9MB) AllocSpace objects, 375(5MB) LOS objects, 18% free, 35MB/43MB, paused 2.302ms total 127.183ms
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 46
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  914): [PWL] Off : 1265s ago
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 47
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 48
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  914): !@Sync 49
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/TimaService(  914): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  914): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  914): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  914): !@Sync 50
,E/SMD     (  295): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  914): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  914): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  914): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  914): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 251, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 252, CUR = 450
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  914): [PWL] Off : 1380s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 252, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 51
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 252, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 252, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 252, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  914): !@Sync 52
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 252, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 252, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 252, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  914): !@Sync 53
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 252, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 251, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 54
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  914): [PWL] Off : 1500s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  914): !@Sync 55
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  914): !@Sync 56
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 57
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  914): !@Sync 58
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,I/PowerManagerService(  914): [PWL] Off : 1625s ago
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 59
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/NetworkStatsFactory(  914): UpdateStatsForKnox
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/TimaService(  914): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  914): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  914): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
I/MotionRecognitionService(  914): Plugged
I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  914): !@Sync 60
,E/SMD     (  295): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  914): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  914): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  914): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  914): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  914): SIOP:: AP = 260, PST = 251, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 251, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 251, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 61
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,E/SMD     (  295): DCD ON
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 251, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 251, CUR = 450
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  914): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 251, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  914): !@Sync 62
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 251, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,D/BatteryService(  914): stay LED for fully charged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 251, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 251, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  914): [PWL] Off : 1755s ago
,E/Watchdog(  914): !@Sync 63
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 251, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  914): Plugged
,I/MotionRecognitionService(  914): setPowerConnected  = true
,D/BatteryService(  914): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  914): SIOP:: AP = 250, PST = 250, CUR = 450
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  295): DCD ON
E/SMD     (  295): DCD ON
D/AndroidRuntime( 8364): 
D/AndroidRuntime( 8364): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8364): CheckJNI is OFF
D/AndroidRuntime( 8364): setted country_code = Poland
D/AndroidRuntime( 8364): setted countryiso_code = PL
D/AndroidRuntime( 8364): setted sales_code = XEO
D/AndroidRuntime( 8364): readGMSProperty: start
D/AndroidRuntime( 8364): readGMSProperty: already setted!!
D/AndroidRuntime( 8364): readGMSProperty: end
D/AndroidRuntime( 8364): addProductProperty: start
E/AffinityControl( 8364): AffinityControl: registerfunction enter
D/AndroidRuntime( 8364): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  914): START PACKAGE DELETE: observer{981920675}
D/PackageManager(  914): pkg{<packageName>}
D/PackageManager(  914): user{0}
D/PackageManager(  914): caller{2000}
D/PackageManager(  914): flags{3}
D/PersonaManagerService(  914): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  914): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  914): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  914): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  914): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  914): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  914): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  914): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  914): getApplicationUninstallationEnabled
D/ApplicationPolicy(  914): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  914): !@killApplicatoin: 10356, uninstall pkg
I/ActivityManager(  914): Force stopping com.test.thalitest appid=10356 user=-1: uninstall pkg
I/ActivityManager(  914): Killing 7290:com.test.thalitest/u0a356 (adj 0): stop com.test.thalitest
I/ActivityManager(  914): Killing 7953:com.samsung.android.sconnect/u0a137 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 6554:com.google.android.apps.plus/u0a134 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 7894:com.google.android.apps.magazines/u0a127 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 7877:com.android.chrome/u0a87 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 6517:com.sec.chaton/u0a85 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 7860:com.sec.knox.bridge/1000 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 7826:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 7196:com.osp.app.signin/u0a44 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 7173:com.policydm/1000 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 7797:com.sec.android.soagent/u0a36 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 7766:com.samsung.klmsagent/u0a18 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 7748:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 7726:com.sec.android.diagmonagent/1000 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 7706:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 7156:com.sec.pcw.device/1000 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 7990:com.sec.android.provider.badge/u0a77 (adj 15): empty for 1809s
I/ActivityManager(  914): Killing 7479:com.android.providers.calendar/u0a45 (adj 15): empty for 1812s
I/ActivityManager(  914): Killing 7654:com.android.calendar/u0a149 (adj 15): empty for 1812s
I/ActivityManager(  914): Killing 7639:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): empty for 1812s
I/ActivityManager(  914): Killing 5859:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): empty for 1813s
I/ActivityManager(  914): Killing 7564:com.samsung.android.provider.shootingmodeprovider/u0a169 (adj 15): empty for 1814s
I/ActivityManager(  914): Killing 7549:com.sec.kidsplat.installer/u0a165 (adj 15): empty for 1814s
I/ActivityManager(  914): Killing 7511:com.samsung.helphub/1000 (adj 15): empty for 1814s
I/ActivityManager(  914): Killing 7486:com.samsung.android.magazine.service/u0a117 (adj 15): empty for 1814s
I/ActivityManager(  914): Killing 7462:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): empty for 1814s
I/ActivityManager(  914): Killing 7437:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1815s
I/ActivityManager(  914): Killing 7429:com.sec.android.provider.logsprovider/u0a19 (adj 15): empty for 1815s
I/ActivityManager(  914): Killing 7415:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty for 1815s
I/ActivityManager(  914): Killing 7348:com.sec.android.automotive.drivelink/u0a98 (adj 15): empty for 1815s
I/ActivityManager(  914):   Force finishing activity ActivityRecord{4ab93c6 u0 com.test.thalitest/.MainActivity t3}
D/FocusedStackFrame(  914): Set to : 0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/ProcessStatsService(  914): Prepared write state in 9ms
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SurfaceFlinger(  259): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
I/SurfaceFlinger(  259): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/WifiService(  914): Client connection lost with reason: 4
W/PackageSettings(  914): Skipping PackageSetting{32572caa com.example.hello/10357} due to missing metadata
I/ActivityManager(  914): Force stopping com.test.thalitest appid=10356 user=0: pkg removed
D/ConnectivityService(  914): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/libprocessgroup(  914): failed to kill 1 processes for processgroup 7290
D/ResourcesManager(  914): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  914): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager( 1473): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 1473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/art     ( 1649): Explicit concurrent mark sweep GC freed 4580(426KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/27MB, paused 1.258ms total 74.787ms
W/ResourcesManager( 1473): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
W/GeofencerStateMachine( 2256): Ignoring removeGeofence because network location is disabled.
E/Zygote  ( 8394): MountEmulatedStorage()
E/Zygote  ( 8394): v2
I/libpersona( 8394): KNOX_SDCARD checking this for 10018
I/libpersona( 8394): KNOX_SDCARD not a persona
I/ActivityManager(  914): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8394 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
E/SamsungIME( 1836): mOCRHelper is null
D/ResourcesManager(  914): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/art     ( 6343): Explicit concurrent mark sweep GC freed 28664(1590KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 574us total 96.625ms
I/art     ( 2473): Explicit concurrent mark sweep GC freed 9574(469KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 21MB/28MB, paused 757us total 114.721ms
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 1473): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
I/SELinux ( 8394): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/ResourcesManager( 1473): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/SELinux ( 8394): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8394): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/TimaKeyStoreProvider( 8394): TimaSignature is unavailable
D/ActivityThread( 8394): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/ResourcesManager(  914): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/SurfaceWidgetView( 1473): destroyHardwareResources():186673867
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
V/WindowOrientationListener(  914): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  914): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  914): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  914): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  914): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/Launcher( 1473): onRestart, Launcher: 720325221
D/Launcher( 1473): onStart, Launcher: 720325221
D/Launcher.HomeView( 1473): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2113): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2113): [237392/6] SurfaceWidget drawing first frame
D/ResourcesManager(  914): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 8394): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/ResourcesManager(  914): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/Books/Books.apk
I/SurfaceFlinger(  259): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/SecContentProvider2(  914): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  914): mCursor = null
D/RegisteredServicesCache( 1449): empty dynamic service
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/StatusBarManagerService(  914): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/StatusBarManagerService(  914): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/InputMethodManagerService(  914): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService(  914): Got RemoteException sending setActive(false) notification to pid 7290 uid 10356
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/KLMS-2.4.503: ( 8394): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.503: ( 8394): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1452269018257
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
I/KLMS-2.4.503: ( 8394): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 8394): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  914): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/RCPManagerService(  914): PackageReceiver onReceive()
I/HarmonyEASService(  914): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/KnoxMUMContainerPolicy(  914): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  914): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/JobSchedulerService(  914): Receieved: android.intent.action.PACKAGE_REMOVED
I/Timeline(  914): Timeline: Activity_windows_visible id: ActivityRecord{e36b785 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1924320
V/EnterpriseBillingPolicy(  914): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  914): uID is 10356
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
V/EnterpriseBillingPolicy(  914): Removed Packageuid is0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
V/EnterpriseBillingPolicyStorage(  914): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  914): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  914): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  914): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  914): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  914): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  914): removeObsoleteFile: deleting file=3_task.xml
D/TaskPersister(  914): removeObsoleteFile: deleting file=3_task_thumbnail.png
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8415): MountEmulatedStorage()
I/libpersona( 8415): KNOX_SDCARD checking this for 10103
E/Zygote  ( 8415): v2
I/libpersona( 8415): KNOX_SDCARD not a persona
I/ActivityManager(  914): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8415 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  914): Killing 7968:com.android.email/u0a162 (adj 15): empty for 1809s
I/art     (  914): Explicit concurrent mark sweep GC freed 54275(5MB) AllocSpace objects, 177(4MB) LOS objects, 31% free, 34MB/50MB, paused 1.418ms total 348.887ms
I/art     (  914): WaitForGcToComplete blocked for 55.435ms for cause Background
I/art     (  914): WaitForGcToComplete blocked for 38.791ms for cause Explicit
I/SELinux ( 8415): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SELinux ( 8415): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8415): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8415): TimaSignature is unavailable
D/ActivityThread( 8415): Added TimaKeyStore provider
D/ResourcesManager( 8415): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/elm:14451( 8415): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8415): ELMEngine.ELMEngine( context ).
D/elm:14451( 8415): MDMBridge.setEnterpriseBridge()
D/elm:14451( 8415): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
D/elm:14451( 8415): ElmAgentService : onCreate()
D/elm:14451( 8415): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8415): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8415): MDMBridge.getInstance()
D/elm:14451( 8415): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14451( 8415): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 8431): MountEmulatedStorage()
E/Zygote  ( 8431): v2
I/libpersona( 8431): KNOX_SDCARD checking this for 10016
I/libpersona( 8431): KNOX_SDCARD not a persona
I/ActivityManager(  914): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8431 uid=10016 gids={50016, 9997} abi=armeabi-v7a
I/art     (  914): Explicit concurrent mark sweep GC freed 9490(433KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 5.260ms total 114.326ms
I/SELinux ( 8431): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8431): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8431): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PackageManager(  914): delete codoeFile: 
D/elm:14451( 8415): ElmAgentService : onDestroy().
D/PackageManager(  914): result of delete: 1{981920675}
I/ActivityManager(  914): Killing 7624:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1809s
D/TimaKeyStoreProvider( 8431): TimaSignature is unavailable
D/ActivityThread( 8431): Added TimaKeyStore provider
D/AndroidRuntime( 8364): Shutting down VM
D/ResourcesManager( 8431): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8431): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8431): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8431): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8448): MountEmulatedStorage()
E/Zygote  ( 8448): v2
I/libpersona( 8448): KNOX_SDCARD checking this for 1000
I/libpersona( 8448): KNOX_SDCARD not a persona
I/ActivityManager(  914): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8448 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  914): Killing 8008:com.samsung.android.service.travel/u0a177 (adj 15): empty for 1810s
I/SELinux ( 8448): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8448): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8448): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BatteryService(  914): level:100, scale:100, status:5, health:2, present:true, voltage: 4342, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  914): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  914): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  914): stay LED for fully charged
D/MotionRecognitionService(  914):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  914): Plugged
I/MotionRecognitionService(  914): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3255): Disconnected process message: 10
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/TimaKeyStoreProvider( 8448): TimaSignature is unavailable
D/ActivityThread( 8448): Added TimaKeyStore provider
D/ResourcesManager( 8448): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
I/PCWCLIENTTRACE_LOG( 8448): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8448): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8448): new DMDBOpenHelper instance
I/PCWCLIENTTRACE_PushUtil( 8448): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 8448): sales region : global
I/PCWCLIENTTRACE_PushUtil( 8448): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 8448): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  914): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8463): MountEmulatedStorage()
E/Zygote  ( 8463): v2
I/libpersona( 8463): KNOX_SDCARD checking this for 10033
I/libpersona( 8463): KNOX_SDCARD not a persona
I/ActivityManager(  914): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8463 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  914): Killing 7059:com.android.defcontainer/u0a5 (adj 15): empty for 1808s
I/SELinux ( 8463): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8463): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8463): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8463): TimaSignature is unavailable
D/ActivityThread( 8463): Added TimaKeyStore provider
D/ResourcesManager( 8463): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/FeatureConfig( 8463): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/ResourcesManager( 8463): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 8463): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 8463): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
I/EventHub(  914): Removing device '/dev/input/event4' due to inotify event
W/ResourcesManager( 8463): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ResourcesManager( 8463): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 8463): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/EventHub(  914): Removing device '/dev/input/event5' due to inotify event
D/ResourcesManager( 8463): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager( 8463): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 8463): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 8463): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
E/SMD     (  295): DCD ON
W/ResourcesManager( 8463): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 8463): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/ResourcesManager( 8463): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8463): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
F/libc    (  914): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa09665a5 in tid 1043 (android.bg)
F/libc    (  914): Failed while talking to debuggerd: Broken pipe
E/audit_log( 2177): File locking failed. error= Bad file number
E/audit_log( 2177): File locking failed. error= Bad file number
W/AudioFlinger(  300): power manager service died !!!
W/AudioFlinger(  300): power manager service died !!!
E/WifiManager( 1848): Channel connection lost

```
